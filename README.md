# Spring Boot Google OAuth2 Login

A Spring Boot application integrating Google OAuth 2.0 authentication.

## Features
- Google OAuth2 login using Spring Security
- Secure authentication with client secrets stored in environment variables
- REST API to fetch authenticated user details

## Setup & Configuration

### 1. Create Google OAuth Credentials
1. Go to [Google Cloud Console](https://console.cloud.google.com/).
2. Create a new project and enable **Google Identity Services** API.
3. Generate **OAuth 2.0 Client ID & Secret**.
4. Set the redirect URI to:
5. Copy the **Client ID** and **Client Secret**.

### 2. Store Secrets Securely
Use environment variables to keep credentials secure:git clone https://github.com/YOUR_USERNAME/spring-boot-google-oauth.git
cd spring-boot-google-oauth
mvn spring-boot:run

---
