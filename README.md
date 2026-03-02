## AuthFlow - Authentication System

- A simple and modern authentication application built with Flutter and Supabase.

----

## Overview

AuthFlow is a clean authentication app that provides multiple login methods using Supabase. It
includes email/password authentication, social logins (Google/Facebook), and phone number
verification with OTP.

----





|  Login |   OTPcheck |  resestPassword | sendOTP | newPassword  |register
|----------------|-----------------|--------------|-----------------|-----------------|-----------------|
| <img width="130" height="255" alt="login" src="https://github.com/user-attachments/assets/6c000921-1fd7-44a8-a9a9-8aae7c2e0313" /> |
<img width="139" height="255" alt="Otpcheck" src="https://github.com/user-attachments/assets/7280903f-c1f4-4d11-a82b-f83f0add2b1b" />

## Features

- **Login with Email & Password**
- **Sign up with Email**
- **Social Login** (Google, Facebook)
- **Phone Authentication** with OTP
- **Password Reset**
- **Clean and Modern UI**

----

## Screenshots

<!--  -->

----

## Project Structure

<!-- 

   AppConstants.dart
│   auth_lisener.dart
│   auth_validators.dart
│   main.dart
│   validators.dart
│   
├───screens
│       forgot_password_screen.dart
│       otp_screen.dart
│       phone_input_screen.dart
│       reset_password_screen.dart
│       signin_screen.dart
│       signup_screen.dart
│       
├───service
│       auth_service.dart
│       
└───widgets
    │   auth_footerlink.dart
    │   auth_header_widget.dart
    │   basic_text_field.dart
    │   divider_widget.dart
    │   forgot_password_link.dart
    │   glowing_background.dart
    │   gradient_button.dart
    │   password_text_field.dart
    │   social_auth_button.dart
    │   
    └───phone_input_widget
            otp_input_widget.dart

-->

----

## Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   flutter pub get


   
1. Run the app:
   ```bash
   flutter run
   ```

---

Dependencies

```yaml
dependencies:
  flutter:
    sdk: flutter
  supabase_flutter: ^2.0.0
  get: ^4.6.5
```

