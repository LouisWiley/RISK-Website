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
    * Shared
      * EXAMPLE 1
    * IdentityComponentsEndpointRouteBuilderExtensions.cs
    * IdentityNoOpEmailSender.cs
    * IdentityRedirectManager.cs
    * IdentityRevalidatingAuthenticationStateProvider.cs
    * IdentityUserAccessor.cs
  * Layout
    * MainLayout.razor : 
    * NavMenu.razor : 
  * Pages
    
  * App.razor
  * Routes.razor
  * _Imports.razor
* Data
* Properties
