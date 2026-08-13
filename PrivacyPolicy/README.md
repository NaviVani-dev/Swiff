# Privacy Policy for Swiff
<sub>Last updated: August 13, 2026</sub>

Swiff is an Android application developed and published by NaviVani. It lets users discover, download, import, and run games and animations from supported archives, websites, and local files.

## Summary

Swiff does not operate an analytics, advertising, tracking, or user-account backend. NaviVani does not receive your library, play history, saves, settings, Newgrounds credentials, session cookies, device identifiers, or diagnostic logs through the app.

Swiff does connect directly to third-party services when required for features you choose to use. Those services receive ordinary network information, such as your IP address and request headers, and process data under their own privacy policies.

Swiff does not sell personal information, use it for advertising, or build user profiles.

## Information stored on your device

Swiff stores data needed to provide its features locally on your device. Depending on how you use the app, this can include:

- App settings and per-game settings.
- Catalog metadata, downloaded and imported content, artwork, and download state.
- Likes, playlists, play history, playing time, and Game of the Day state.
- Game saves, browser storage, cookies, and runtime files.
- Custom metadata, layouts, shortcuts, and folders selected through Android's system file picker.
- Newgrounds account display name, profile image, session state, medals, and related game metadata when the optional Newgrounds integration is used.

This information is not uploaded to NaviVani. Files placed in a user-selected external folder remain under the control of the user and the selected storage provider.

Android backup is enabled for the app. Depending on the device and the user's Android backup settings, Android may include eligible app data in the user's private device backup. Backup storage and transfer are controlled by the operating system and the user's backup provider, not by NaviVani.

## Network access and third-party services

Swiff uses network access to retrieve catalogs, metadata, artwork, games, runtime components, updates, and other content requested by the user. Services that may be contacted include:

- Flashpoint Archive and its infrastructure for catalog data, artwork, archived content, and Game of the Day.
- Kahvibreak for J2ME catalog data and content.
- Scratch for project information, project files, assets, and artwork.
- Newgrounds for pages, profile information, game integrations, medals, scoreboards, and content.
- GitHub and runtime hosts for Full-version updates and optional runtime components.
- Google Play for app delivery and optional Play Feature Delivery modules in the Google Play version.
- Mozilla and Google-operated browser infrastructure used by GeckoView for browser configuration and security features.
- Websites entered by the user or contacted by a game, animation, embedded browser, proxy, or imported web shortcut.

Swiff does not control the privacy practices of these services or of third-party content. A website or game opened through Swiff may set cookies, use local storage, make network requests, or request information according to its own code and policies. Users should review the privacy policy of a third-party service before signing in or providing information.

## Newgrounds sign-in

Signing in to Newgrounds is optional. The sign-in page is loaded directly from Newgrounds in an embedded browser. Swiff does not receive or store the password entered on that page.

After a successful sign-in, Newgrounds session cookies remain in Android WebView storage on the device. Swiff uses those cookies to request the user's public profile information and to support Newgrounds features such as compatible game sessions, medals, and scoreboards. These requests go directly from the device to Newgrounds; they do not pass through a server owned by NaviVani.

Swiff may store the Newgrounds display name, profile image, session-detected state, and medal state locally for the interface and offline display. Logging out through Swiff removes the locally stored account state and WebView cookies. Newgrounds controls the account and any information retained on its servers. Newgrounds explains its practices in its [Privacy Policy](https://www.newgrounds.com/wiki/help-information/privacy-policy).

## Permissions and device access

Swiff may use the following Android capabilities:

- Network state and internet access to provide catalogs, downloads, online content, browser features, and updates.
- Notifications to show download progress and results. Notification permission is optional where Android requires it.
- Microphone access for J2ME titles that explicitly request audio recording. Android asks for permission before access. Swiff does not send microphone recordings to NaviVani, but a third-party title with network functionality may process or transmit data according to that title's behavior.
- Motion and other high-rate sensor input for compatible game controls. This input is processed for gameplay and is not sent to NaviVani.
- User-selected files and folders through Android's system file picker for imports, saves, custom drives, frontend synchronization, logs, and storage locations. Swiff accesses only locations granted by the user.
- Package installation in the Full distribution only, so the user can install an app update downloaded from the project's release channel. This permission is not present in the Google Play distribution.

Swiff does not request access to contacts, SMS, call logs, or precise location.

## Diagnostics

Swiff does not include an analytics or remote crash-reporting service. Diagnostic logging is local. If the user enables a log session and selects a destination folder, Swiff writes the log to that folder and redacts recognized URLs and credential-like values. A log is sent to NaviVani only if the user chooses to share it manually, for example in a support request.

## Security

App-private data is stored in Android's application sandbox. Swiff uses HTTPS for its own supported service endpoints when available and validates sensitive runtime downloads with pinned hashes where implemented.

Some archived games, user-entered sites, and legacy services only support unencrypted HTTP. Traffic to those destinations is not protected by HTTPS and may be visible or modified in transit. Data exported to a user-selected folder is protected according to the permissions and security of that storage location or provider.

No method of local storage or network transmission is completely secure.

## Retention and deletion

Local data is retained until it is removed by the user or replaced as part of normal app operation. Users can remove individual downloads, catalogs, runtimes, and other managed content from Data Management where supported.

Users can remove all app-private data by clearing Swiff's storage in Android settings or uninstalling the app. Files exported to or stored in user-selected folders, Android backups, and data held by third-party services may need to be deleted separately through the relevant folder, device settings, backup provider, or third-party service.

Because Swiff does not create or operate a NaviVani account, there is no Swiff server account to delete. Deleting a Newgrounds account or server-side Newgrounds data must be requested from Newgrounds.

## Children's privacy

Swiff is not directed to children under 13. The app can access third-party and user-provided content with independent age requirements and content policies. Parents and guardians should supervise use where appropriate.

## Changes to this policy

This policy may be updated when Swiff's data practices, integrations, or legal requirements change. The date at the top identifies the latest revision. Material changes apply when the updated policy is published.

## Contact

Questions, privacy inquiries, and deletion requests concerning information voluntarily submitted to NaviVani for support can be made through the [Swiff issue tracker](https://github.com/NaviVani-dev/Swiff/issues).

The source repository and this policy are available at [github.com/NaviVani-dev/Swiff](https://github.com/NaviVani-dev/Swiff).
