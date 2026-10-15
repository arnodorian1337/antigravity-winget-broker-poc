# Winget broker boundary fixture

This repository contains a benign Windows executable used to test whether a
sandboxed `winget` client can cause an installer to run outside its caller's
AppContainer. The executable only appends diagnostic data to
`%USERPROFILE%\agy-vscode-gitpath-proof.txt`.

This is a research fixture. Opening the repository does not run anything.
