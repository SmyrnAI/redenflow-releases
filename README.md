# RedenFlow downloads

Installers for [RedenFlow](https://redenflow.com), a desktop application that
trains a vision model from your own pictures. No Python and no command line at
any point.

**[Download the latest version](https://github.com/SmyrnAI/redenflow-releases/releases/latest)**

| | |
| --- | --- |
| Windows | `RedenFlow_Setup.exe`, Windows 10 and 11, 64-bit |
| macOS | `RedenFlow-macOS.zip`, macOS 12 and later, Apple Silicon and Intel |
| Linux | `RedenFlow-x86_64.AppImage`, Ubuntu 22.04 and later, 64-bit |

On Linux there is also `RedenFlow-linux-x86_64.tar.gz`, for machines where an
AppImage will not run. Extract it and run `RedenFlow/RedenFlow`.

A downloaded AppImage is not allowed to run until you say so, and nothing
warns you about it: double clicking simply does nothing. Give it permission
once, in your file manager under Properties, or with
`chmod +x RedenFlow-x86_64.AppImage`.

There is no source code here. This repository exists to hold the builds, so
that a download link is a stable address that does not change when the
application does.

Builds are produced by GitHub Actions from the application repository and
published here automatically. Nothing is uploaded by hand, which is the point:
an installer somebody built on their own machine is an installer nobody can
reproduce.

## Getting help

The application is documented at [redenflow.com/help](https://redenflow.com/help).
For anything else, write to <info@redenflow.com>.

Terms: [redenflow.com/terms](https://redenflow.com/terms) &middot;
Privacy: [redenflow.com/privacy](https://redenflow.com/privacy)
