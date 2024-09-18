# Firebase Authentication Setup for React App

## Introduction

Firebase Authentication provides an easy and secure way for users to sign in to your app. It supports various authentication methods such as Email/Password, Google, Facebook, GitHub, Twitter, and more.

This guide will help you integrate Firebase Authentication into your React application.

## Prerequisites

Before starting, make sure you have the following:
- A Google account.
- Node.js and npm installed.
- A React app ready for Firebase integration.

## 1. Sign Up and Create a Firebase Project

1. Go to the [Firebase Console](https://console.firebase.google.com/).
2. Sign in with your Google account or create one if you don't have it.
3. Click **Add Project** and follow the prompts to create a new project.
   - Name the project (e.g., `Focus-app`).
   - You can disable Google Analytics as it is not required for this setup.
4. Once the project is created, you'll be directed to the Firebase dashboard.

## 2. Install Firebase SDK in Your React App

In the terminal, navigate to your React app and install Firebase:

```bash
npm install firebase
