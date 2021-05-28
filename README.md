# versionUpdateCSharp

Update to new dotnet version automatically

# Usage

```C#
// Create a new UpdateChecker that queries the specified URI with the CurrentVersion defined as 1.0 by default
UpdateChecker checker = new UpdateChecker("http://convex.st4r.io/sample/version.manifest");

// Check for an update, and print.
Console.WriteLine(checker.CheckForUpdates() ? "Update is available!" : "Latest version is in use.");
```
