# Quickstart UI for Duende IdentityServer
This repo contains a sample UI for login, logout, grant management and consent.

Note that the repo doesn't include solution and project files, but should be copied to your project as described below.

This repo contains the UI for the in-memory test user store as a starting point, see [here](https://github.com/DuendeSoftware/IdentityServer.Quickstart.UI.AspNetIdentity) for a version using Microsoft's ASP.NET Identity user management library.

## Adding the quickstart UI
This repo contains the pages, models, views and CSS files needed for the UI. Simply download/clone it and copy the folders into the web project.

Alternatively you can run this powershell script from your web project directory to download them automatically:

```
iex ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/DuendeSoftware/IdentityServer.Quickstart.UI/main/getmain.ps1'))
```

Or using bash one-liner on macOS or Linux:

```bash
curl -L https://raw.githubusercontent.com/DuendeSoftware/IdentityServer.Quickstart.UI/main/getmain.sh | bash
```

Or you can use our [templates](https://github.com/DuendeSoftware/IdentityServer.Templates):

```
dotnet new -i Duende.IdentityServer.Templates
dotnet new isui
```

## Issues
For issues, use the [Duende IdentityServer issue tracker](https://github.com/DuendeSoftware/IdentityServer/issues).
