# gasket-driver

| Package | Build Status |
| --- | --- |
| gasket | ![Build Status](https://copr.fedorainfracloud.org/coprs/goknsh/gasket-driver/package/gasket/status_image/last_build.png) |
| gasket-dkms | ![Build Status](https://copr.fedorainfracloud.org/coprs/goknsh/gasket-driver/package/gasket-dkms/status_image/last_build.png) |
| gasket-kmod | ![Build Status](https://copr.fedorainfracloud.org/coprs/goknsh/gasket-driver/package/gasket-kmod/status_image/last_build.png) |

The Coral Gasket Driver allows usage of the [Coral EdgeTPU](https://coral.ai/) on Linux systems. The driver contains two modules:

* Gasket: Gasket (Google ASIC Software, Kernel Extensions, and Tools) is a top level driver for lightweight communication with Google ASICs.
* Apex: Apex refers to the [EdgeTPU v1](https://coral.ai/technology)

## Installing

You can get releases for Fedora from my [Copr](https://copr.fedorainfracloud.org/coprs/goknsh/gasket-driver/).

If you wish to use this with Secure Boot, follow [this guide](https://gist.github.com/KyleGospo/9adbe078d1d7f160ae43c091df98f773).
