# Only For Termux (Android 5.1+)
# Installation

echo 'deb [trusted=yes] https://binyamin-binni.github.io/paid bxi stable' > $PREFIX/etc/apt/sources.list.d/binni.list

pkg update

pkg install bxi

# Usage

bxi
