---
-api-id: T:Windows.ApplicationModel.Activation.ShareTargetActivatedEventArgs
-api-type: winrt class
---

<!-- Class syntax.
public class ShareTargetActivatedEventArgs : Windows.ApplicationModel.Activation.IActivatedEventArgs, Windows.ApplicationModel.Activation.IActivatedEventArgsWithUser, Windows.ApplicationModel.Activation.IShareTargetActivatedEventArgs
-->

# Windows.ApplicationModel.Activation.ShareTargetActivatedEventArgs

## -description
Provides information for an application that is a target for share operations.



> **JavaScript**
> This type appears as [WebUIShareTargetActivatedEventArgs](../windows.ui.webui/webuisharetargetactivatedeventargs.md).

## -remarks
This object is accessed when you implement an event handler to respond to [Activated](../windows.applicationmodel.core/coreapplicationview_activated.md) events when [ActivationKind](activationkind.md) is **ShareTarget**.

UWP app using C++, C#, or Visual Basic typically implement activation points by overriding methods of the [Application](../windows.ui.xaml/application.md) object. The default template app.xaml code-behind files always include an override for [OnLaunched](../windows.ui.xaml/application_onlaunched.md), but defining overrides for other activation points such as [OnShareTargetActivated](../windows.ui.xaml/application_onsharetargetactivated.md) is up to your app code.

All [Application](../windows.ui.xaml/application.md) overrides involved in an activation scenario should call [Window.Activate](../windows.ui.xaml/window_activate.md) in their implementations.

For example code, see [Share target activation sample](http://go.microsoft.com/fwlink/p/?LinkID=231519).

## -examples

## -see-also
[Windows.UI.Core.CoreApplicationView.Activated](../windows.applicationmodel.core/coreapplicationview_activated.md), [Share target activation sample](http://go.microsoft.com/fwlink/p/?LinkID=231519)