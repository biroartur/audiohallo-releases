# AudioHallo releases

Signed AudioHallo server versions for Raspberry Pi. Activated Pis with *Automatic updates* on (admin page → Settings) download the newest release from here and install it when nobody is listening; each `linux-arm64` bundle comes with an Ed25519 signature (`.sig`) that the Pi checks before installing.

By hand: download `audiohallo-server-<version>-linux-arm64.tar.gz`, then

    tar xzf audiohallo-server-*-linux-arm64.tar.gz && cd audiohallo-server-*/ && sudo ./install.sh

https://audiohallo.szeretet.ro
