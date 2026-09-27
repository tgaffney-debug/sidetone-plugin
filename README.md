# Sidetone development build

Native iPhone radio panel and hold-to-talk control for vPilot on Windows. This is a development candidate, not yet accepted on physical devices.

This branch is a **cloud-build launcher**. The reviewed Sidetone implementation is stored in `sidetone-candidate.bundle`, a standard Git bundle containing source commit `50cbae2db1fd5c5ea53e596fd6b9c5d31e03e2e7` and its delta from upstream `76cb59d7d84eb60fd13f6dadf090103ae896d254`. The surrounding source tree is the upstream baseline, not the Sidetone application.

The manual **Sidetone** workflow verifies the bundle and checks out that exact candidate before compiling or testing. It has read-only repository permission and does not publish a release. Build manifests identify the candidate source commit, which differs from the workflow launcher commit.

To inspect the candidate locally, fetch the bundle into this clone and check out FETCH_HEAD. The candidate includes setup instructions, protocol documentation, safety tests and build scripts.

Bundle SHA-256: `4b0ec70772c21eb372197c287af0b9c4a3147a1232766f8dbbbbf3fa22ee04aa`

GitHub browser is signed in as tgaffney-debug; the connector is linked to another account. This source-bundle launcher enables platform builds without creating credentials or changing account access.

Microphone and headset remain on the Windows PC. iPhone installation still needs Apple signing. No installer or IPA should be treated as flight-ready until device acceptance.
