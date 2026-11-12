# carlos_mobprog

A new Flutter project.
## Laboratory Activity 0A: Discussion

### 1. Challenges Encountered While Installing or Configuring Flutter
Configuring the Flutter SDK and Android development tools required careful directory management and environment path setup. Additionally, ensuring the project was initialized inside the proper directory structure (`carlos_mobprogAY2627/carlos_mobprog`) without nested folder or import path mismatches took extra verification.

### 2. Errors Encountered When Running `flutter doctor`
During initial verification with `flutter doctor`, missing Android SDK components (such as Command-line Tools and NDK) and unaccepted Android licenses were flagged before the environment could be fully cleared.

### 3. How Installation, Dependency, SDK, or Device Issues Were Resolved
* **SDK & Licenses:** Installed the required Android SDK Command-line Tools and NDK via Android Studio's SDK Manager, added Flutter to the system `PATH`, and accepted the licenses using `flutter doctor --android-licenses`.
* **Project & Device Execution:** Verified the workspace directory structure in VS Code, resolved package/import configurations, and compiled the application targeting the Windows desktop environment to confirm a clean build.

### 4. What I Learned About Configuring a Flutter Development Environment
I learned how the Flutter SDK interacts with platform-specific toolchains (Android SDK, Visual Studio/Windows desktop build tools, and VS Code extensions), as well as how `flutter doctor` diagnoses missing dependencies and environment variables.

### 5. Practices I Will Follow to Make Future Flutter Development Easier
* Run `flutter doctor` whenever updating SDKs or switching machines to catch dependency issues early.
* Maintain clean, non-nested project directory structures from the start.
* Commit and push incremental changes to GitHub regularly with clear commit messages.