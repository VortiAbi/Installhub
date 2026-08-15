
````md
# InstallHub

> A simple and modern Windows application installer powered by WinGet.

**Live:** https://installhub.xo.je/

InstallHub makes setting up a new Windows PC easier.

Instead of manually searching for every application, you can select the applications you need and generate a ready-to-use installation setup using Microsoft's Windows Package Manager (WinGet).

---

## Features

- Application search
- Categories
- Multi-app selection
- WinGet command generation
- `.bat` installer generation
- WinGet JSON export
- Package status information
- GitHub-inspired dark interface
- Responsive design
- Growing application catalog

---

## How It Works

1. Open InstallHub
2. Find the applications you want
3. Select them
4. Generate your setup
5. Review the generated commands
6. Run the setup on your Windows PC

InstallHub does not directly host or redistribute the applications.

The actual installation is handled by **WinGet**.

---

## Example

For example, you can select:

```text
Steam
Discord
Spotify
Google Chrome
Visual Studio Code
7-Zip
OBS Studio
VLC
Git
PowerToys
````

InstallHub can generate commands such as:

```powershell
winget install --id "Valve.Steam" -e
winget install --id "Discord.Discord" -e
winget install --id "Spotify.Spotify" -e
winget install --id "Google.Chrome" -e
winget install --id "Microsoft.VisualStudioCode" -e
```

You can review the generated setup before running it.

---

## Requirements

* Windows 10 or Windows 11
* Windows Package Manager (WinGet)
* Internet connection

WinGet is provided by Microsoft and is commonly available through the Windows App Installer.

---

## Security & Trust

InstallHub is designed to keep the installation process transparent.

InstallHub:

* Does not host application installers
* Does not upload your selected applications
* Does not require an account
* Uses WinGet package identifiers for installations
* Shows the commands that will be generated
* Allows you to review the generated setup before execution

**Always review generated commands before running them.**

Package availability and publisher information are determined by WinGet and its configured sources.

---

## Technology

InstallHub currently uses:

* HTML
* CSS
* JavaScript
* Windows Package Manager (WinGet)

The website itself is a static application and does not require a backend for its basic functionality.

---

## AI-Assisted Development

InstallHub was developed with assistance from AI tools.

AI was used to help with:

* Development
* UI and UX ideas
* Code generation
* Debugging
* Documentation
* Feature planning

The project is reviewed and maintained by humans.

AI assistance does not replace testing, verification or responsible development.

---

## Project Status

**Current Version:** V5

InstallHub is an active project and is still being improved.

The application catalog, interface and features may change over time.

---

## Roadmap

* [ ] Larger application catalog
* [ ] Improved package verification
* [ ] Favorites
* [ ] Custom installation profiles
* [ ] Gaming profile
* [ ] Developer profile
* [ ] Streaming profile
* [ ] Privacy profile
* [ ] Better package information
* [ ] Improved setup generation
* [ ] More application categories

---

## Contributing

Suggestions, bug reports and improvements are welcome.

If you find a problem, please open a GitHub Issue.

Pull requests are also welcome.

---

## License

See the `LICENSE` file for license information.

---

## Links

**Website:** [https://installhub.xo.je/](https://installhub.xo.je/)

**Source Code:** This repository

---

## Disclaimer

InstallHub is an independent project and is not affiliated with Microsoft, Valve, Discord, Spotify, Google, or any other application publisher listed on the website.

InstallHub uses WinGet to request application installations. Always verify the package, publisher and generated commands before installing software.

---

**InstallHub**

*Set up your Windows PC faster.*



