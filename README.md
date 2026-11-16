# StokedUp

A minimal C# .NET MAUI app for Android. The Android application ID is
`com.example.stokedup`. Replace it with your own identifier before publishing.

1. Install Visual Studio with the .NET Multi-platform App UI development
   workload and .NET 10 Android tooling.
2. Open `StokedUp.sln` and let Visual Studio restore NuGet dependencies.
3. Select an Android emulator or connected Android device and press F5.
4. Tap **Check local database**. The expected result is **SQLite is ready.**

The check runs a query against `stokedup.db3` in the app's private data
directory. `Data/LocalDatabase.cs` is the starting point for adding tables.

The home screen layout is in `MainPage.xaml`. Its SQLite button handler is
in `MainPage.xaml.cs`. The app displays **Hello, World!** on launch.
