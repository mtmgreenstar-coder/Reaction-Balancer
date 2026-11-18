# Reaction Balancer

Android WebView wrapper for the original Persian Reaction Balancer HTML application.

## Build

Pushes to `main` and manual workflow dispatch run **Build Reaction Balancer APK**. The debug APK is uploaded as a workflow artifact.

App label: **Reaction Balancer**

## Windows desktop version

The `Build Reaction Balancer Windows EXE` workflow builds one self-contained Windows x64 portable EXE (no installer).
It runs automatically on pushes to `main`, or can be started manually from GitHub Actions.
Download the `Reaction-Balancer-Windows-Portable` artifact from a successful run. The app can be launched directly from the EXE; it does not need an installation folder.
The Windows installer uses the same offline HTML app and the supplied Reaction Balancer logo.
