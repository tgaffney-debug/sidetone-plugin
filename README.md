# Sidetone improvement candidate

Windows companion for the native Sidetone iPhone radio panel. Version 0.6.0-sidetone.2.

This branch is a cloud-build launcher. The application source is stored in the standard Git bundle `sidetone-candidate.bundle`, source commit `4b9083a356649f4c3e83a5ce709e9243834e50dd`. The surrounding tree is the upstream baseline. The manual Sidetone workflow verifies the bundle and checks out the exact source commit declared in `sidetone-source.txt` before building.

Bundle SHA-256: `b8e87584e1da495891f1851fc48b5f3916505a1b35ca2df6bb9c3ad8d1ac3984`.

The updated source includes first-run Windows connection help, direct Ally address display, honest readiness, radio-command expiry, readback recovery fixes and expanded failure-path tests. Microphone/headset stay on the Ally. Native build results and physical-device acceptance are distinct checks. No live-flight reliability claim is implied by this source upload.
