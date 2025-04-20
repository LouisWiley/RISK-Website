# Risk Website

## Purpose
A website that stores AI bots capable of playing Risk, which can be used in Risk games to test algorithms and strategies. Users will be able to submit their own bots and view bots created by other users.
This project was created for our IUS Capstone course.

## Tool Stack
* Blazor WASM
* Google API

## Project Structure
* Components - Provided by default with Blazor WASM
  * Account : Pages that are associated with user account creation and management
    * Pages 
      * Manage : Allows for management of User Account and third party services (Ex: Google API)
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
    * Shared : Shared UI and layout components for account-related views
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
  * Layout : Layout for fixed banners
    * MainLayout.razor 
    * NavMenu.razor 
  * Pages :  Pages created for the use of this project.
    * About.razor
    * BotBrowser.razor
    * DatabaseAccess.razor
    * Error.razor
    * Home.razor
    * SoftwareDownload.razor
    * SubmitPage.razor
  * App.razor
  * Routes.razor
  * _Imports. razor
* Data
  * ApplicationDbContext.cs - Database Functions
  * ApplicationUser.cs - User Fields
  * Bot.cs - Bot Fields
* Properties
  * launchSettings.json - Controls how the app is started in dev 
  * serviceDependencies.json - external services 
  * serviceDependencies.local.json - external services 
