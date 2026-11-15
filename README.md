# FileManager updates

This public repository is for compiled Windows x64 FileManager installers,
signed update metadata and release notes. FileManager application source code,
private Git history, credentials and personal settings do not belong here.

Install `FileManager-Setup.exe` from a stable release. FileManager checks this
repository for later stable versions and asks before downloading or installing.
No GitHub account is required. Personal settings, Notes, Favorites, font choices
and shortcuts remain in your separate Windows profile data directory.

The installer retains required third-party notices, Microsoft runtime terms and
7-Zip corresponding source. These terms are included inside the installer.

`stable.json` is signed by the release owner. FileManager verifies that signature
with its embedded public key and verifies the entire installer's size and SHA-256
before it can launch Setup. The private signing key is never hosted here.
