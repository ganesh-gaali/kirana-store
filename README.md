# KIRANA STORE

## Tools Used

- Git Hooks
- Android Lint : https://developer.android.com/studio/write/lint
  - Inspect & validate Java, Kotlin and XML
  - Integrated into Android Studio
  - Can be integrated with CI Pipeline
  - Configurable checks & Severity

command: ./gradlew lint
- ktLint : https://github.com/pinterest/ktlint
  - Rules based on style guides from kotlinlang.org and Android Kotlin Style Guide
  - Minimal Config
  - Supports Configuration and custom rules
  - Includes and auto-formatting tools
- Detek : https://github.com/detekt/detekt
  - Checks for code complexity, code smells, formatting
  - Can include ktlint checks
  - highly configurable

- Check Styles
  - Checks for naming conventions structural issues , class designs
  - Configurable via XML
  - Rules sets for Google and Sun are available
  
- PMD
  - Checks for a variety of things including conditional complexity, unnecessary object creation, unused variables
  - Configurable via XML

- FindBugs
  - Examins Bytecode


Configuration
- TODO: Need to create a task to copy git hooks to client .git/hooks folder
- chmod a+x .git/hooks/pre-push
- chmod a+x .git/hooks/prepare-commit-msg