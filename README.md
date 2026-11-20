# Haven for Android

Public APK downloads for the private Haven personal media drive.

[Download releases](https://github.com/SeefatHimel/haven-releases/releases) · [Open Haven](https://haven-nine-pi.vercel.app)

Personal preview, currently retaining the existing debug signing identity.
Install the APK over your existing Haven preview to keep local files, queue and
pairing. Android asks before installation. Do not uninstall to update it.
Keep originals backed up. The app still requires its owner sign-in/device pairing.

The private source repository remains private. This repository holds only
build-request metadata, the publishing workflow, APKs, checksums and release
metadata. GitHub's source archives contain this publisher repository only. No
provider keys, personal media or account records are included. APK client code
can be inspected/decompiled.

Android changes on source main trigger a verified build on standard public
GitHub-hosted Linux runners. Each published APK retains its package/certificate,
has an increasing Android version code and is independently hash-checked after
publication. Failed builds do not advertise an update. Installation is manual.
