# powershell-native-stderr

In PowerShell 5.1, redirecting a native exe's stderr with `2>&1` wraps each line in an ErrorRecord and can make a successful command look failed.
