This project is intended to be used alongside test instructions for the Android Gradle Plugin
Upgrade Assistant located [here]().

It was generated using Android Studio 4.0 by:

1. creating a new project with a Basic Activity, accepting the defaults from the New Project Wizard;
2. creating a new Android Library module named `myandroidlibrary`, with the language set to Java;
3. creating a new Java / Kotlin Library module named `mylibrary`, with the language set to Kotlin;
4. modifying the `myandroidlibrary` `build.gradle` file to have language level directives, marked
   by the comment `// language level directives added here`.
5. modifying the main `app` `build.gradle` file to add dependencies on the `myandroidlibrary` and
   `mylibrary` Gradle projects.