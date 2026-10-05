# AIRobo Installation Guide

Please follow these steps to install AIRobo Studio and the AIRobo Compiler Tools. 

> [!IMPORTANT] 
> **Do not change the default installation directories during this process.**

## 1. Install AIRobo Studio
1. Locate and double-click the installer file: `Airobo Studio Setup.exe`.
2. Follow the on-screen instructions in the setup wizard.
3. When prompted for an installation location, **leave the default directory as is**. Do not click "Browse" or change the path.
4. Click through to complete the installation process.

## 2. Install AIRobo Compiler Tools
1. Locate and double-click the installer file: `Airobo_Compiler_Tools_Setup_v2.exe`.
2. Follow the on-screen instructions in the setup wizard.
3. When prompted for an installation location, **leave the default directory as is**. Do not click "Browse" or change the path.
4. Click through to complete the installation process.

## 3. Verification
Once both installations are complete, you can launch AIRobo Studio from your Start menu or desktop shortcut to ensure it opens correctly.

## 4. Post-Installation: Login & Usage Scenarios

Upon launching AIRobo Studio, your access and available features will depend on your network connection and account status.

### Online Mode (Internet Connected)
When connected to the internet, you have access to the complete suite of tools and cloud features.

- **Sign Up / Sign In:** Create a new account or log in with your email and password. Your profile name will be displayed in the top-right menu.
- **Guest Access:** You can click "Continue as Guest" to use the software without creating an account. The app will remember this choice for future sessions until you manually log out.
- **Features Included:** 
  - Full access to the block coding interface and hardware deployment.
  - **AIRobo AI Assistant:** Generative AI coding copilot powered by cloud LLMs (Groq / Gemini).
  - **AI Voice Assistant:** Voice recognition and AI chat capabilities requiring cloud APIs.
  - All local extensions and features.

### Offline Mode (No Internet Connection)
If the application is launched without an active internet connection, it automatically switches to **Offline Mode**.

- **Authentication:** Bypasses the cloud login screen and boots directly into the local workspace.
- **Features Included:** 
  - Standard block coding and game logic building.
  - Hardware compiling and uploading to boards (ESP32, MRTX-NODE, etc.) via USB using the installed Compiler Tools.
  - Live Mode execution and debugging.
  - **AI Vision Extensions:** Face, Hand, and Pose tracking are powered by your computer's local CPU and are fully available offline.
- **Features Excluded (Require Internet):** 
  - AIRobo AI Assistant (Generative block coding copilot).
  - AI Voice Assistant (Speech-to-text and cloud LLM chat).
  - Cloud profile management and authentication.
  - AI Tutor
