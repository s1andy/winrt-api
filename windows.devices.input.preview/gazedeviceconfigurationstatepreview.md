---
-api-id: T:Windows.Devices.Input.Preview.GazeDeviceConfigurationStatePreview
-api-type: winrt enum
---

<!-- Enumeration syntax.
public enum GazeDeviceConfigurationStatePreview : int 
-->

# Windows.Devices.Input.Preview.GazeDeviceConfigurationStatePreview

## -description

Specifies the possible configuration states of an eye-tracking device.

## -enum-fields

### -field UserCalibrationNeeded:4

The eye-tracker device needs to be calibrated.

### -field Unknown:0

The eye-tracker device state is unknown. Calibration might resolve this state.

### -field ScreenSetupNeeded:3

The display device is not configured correctly. Calibration might resolve this state.

### -field Ready:1

The eye-tracker device is ready to start eye and head tracking.

### -field Configuring:2

The eye-tracker device is currently being configured.

## -remarks

Use these values to confirm that the eye-tracking device is calibrated and ready to send gaze input events and data.

## -see-also

### Conceptual

[Gaze interactions and eye tracking in UWP apps](https://docs.microsoft.com/windows/uwp/design/input/gaze-interactions)

### Reference

[ConfigurationState](gazedevicepreview_configurationstate.md)

## -examples

