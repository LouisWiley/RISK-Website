# Risk Website

## Purpose
A website that stores AI bots capable of playing Risk, which can be used in Risk games to test algorithms and strategies. Users will be able to submit their own bots and view bots created by other users.
This project was created for our IUS Capstone course.

## Tool Stack
* Blazor WASM
* Google API

## Project Structure
* Components
  * Account
    * Pages
      * Manage
        * ChangePassword.razor
        * DeletePersonalData.razor
        * Disable2fa.razor
        * Email.razor
        * EnableAuthenticator.razor
        * ExternalLogins.razor
        * GenerateRecoveryCodes.razor
        * Index.razor
        * PersonalData.razor
        * ResetAuthenticator.razor
        * SetPassword.razor
        * TwoFactorAuthentication.razor
        * _Imports. razor
      * AccessDenied.razor
      * ConfirmEmail.razor
      * ConfirmEmailChange.razor
      * ExternalLogin.razor
      * ForgotPassword.razor
      * ForgotPasswordConfirmation.razor
      * InvalidPasswordReset.razor
      * InvalidUser.razor
      * Lockout.razor
      * Login.razor
      * LoginWith2fa.razor
      * LoginWithRecoveryCode.razor
      * Register.razor
    * Shared
      * AccountLayout.razor
      * ExternalLoginPicker.razor
      * ManageLayout.razor
      * ManageNavMenu.razor
      * RedirectToLogin.razor
      * ShowRecoveryCodes.razor
      * StatusMessage.razor
    * IdentityComponentsEndpointRouteBuilderExtensions.cs
    * IdentityNoOpEmailSender.cs
    * IdentityRedirectManager.cs
    * IdentityRevalidatingAuthenticationStateProvider.cs
    * IdentityUserAccessor.cs
  * Layout
    * MainLayout.razor : 
    * NavMenu.razor : 
  * Pages
    * About.razor
    * BotBrowser.razor
    * DatabaseAccess.razor
    * Error.razor
    * Home.razor
    * SoftwareDownload.razor
    * SubmitPage.razor

  * App.razor
  * Routes.razor
  * _Imports.razor
* Data
* Properties
