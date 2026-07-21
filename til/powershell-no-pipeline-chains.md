# powershell-no-pipeline-chains

Windows PowerShell 5.1 has no `&&` or `||` pipeline chain operators — they were added in PowerShell 7. Use `A; if ($?) { B }` instead.
