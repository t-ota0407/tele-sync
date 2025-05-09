# tele-sync

## Overview
tele-sync is a remote communication system using 3D Gaussian Splatting (3DGS) and asymmetric MR. On-site users capture a physical environment, and the system constructs a 3D scene using 3DGS. This system enables communication in a virtual environment that reflects the real-world environment.

<figure>
  <img src="demo_remote.gif" alt="Remote User">
  <figcaption>Remote user and the view of the reconstructed 3D environment</figcaption>
</figure>

<figure>
  <img src="demo_capture.gif" alt="Capture Process">
  <figcaption>On-site user capturing the physical environment</figcaption>
</figure>

## Related Repositories
This system consists of the following programs:

- [tele-sync-capture](https://github.com/t-ota0407/tele-sync-capture) - MR application to capture images of physical environment
- [tele-sync-onsite](https://github.com/t-ota0407/tele-sync-onsite) - MR application used by on-site users
- [tele-sync-remote](https://github.com/t-ota0407/tele-sync-remote) - MR application used by remote users
- [tele-sync-server](https://github.com/t-ota0407/tele-sync-v2) - Server program
- [tele-sync-3dgs](https://github.com/t-ota0407/tele-sync-3dgs) - Program for 3D reconstruction using 3DGS for remote users
