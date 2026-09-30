# Sidetone improvement candidate

Windows companion for the native Sidetone iPhone radio panel. Version 0.6.0-sidetone.2.

This branch is a cloud-build launcher. The application source is stored in the standard Git bundle `sidetone-candidate.bundle`, source commit `90606482d745db4c29fbca0c1d2f6570d08002d7`. The surrounding tree is the upstream baseline. The manual Sidetone workflow verifies the bundle and checks out the exact source commit declared in `sidetone-source.txt` before building.

Bundle SHA-256: `c6ed877870ea7f10c4e125029ebfad9a9db44ffa2ac8b731f60c1af185cdd07c`.

The updated source includes first-run Windows connection help, direct Ally address display, honest readiness, radio-command expiry, readback recovery fixes and expanded failure-path tests. Microphone/headset stay on the Ally. Native build results and physical-device acceptance are distinct checks. No live-flight reliability claim is implied by this source upload.
