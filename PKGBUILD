pkgname="calla"
pkgver="0.3"
pkgrel="2"
pkgdesc="Calla desktop environement"
arch=("x86_64")
depends=("xorg-server" "pipewire-pulse"
  "brightnessctl" "inotify-tools"
  "awesome-git" "picom" "maim"
  "papirus-icon-theme" "noto-fonts"
  "noto-fonts-cjk" "noto-color-emoji-fontconfig"
  "noto-fonts-extra" "lua-pam-git")
url="https://github.com/LeVraiArdox/calla"
optdepends=("st: terminal",
  "vim-gtk3: vim with clipboard",
  "nemo: file manager",
  "network-manager-gnome: network applet",
  "polkit-gnome: polkit",
  "cbatticon: battery applet",
  "blueman: bluetooth applet",
  "xdg-user-dirs: generate home directories",
  "lollypop: music player",)
conflicts=("axskel-awesome")

package() {
  mkdir -p "${pkgdir}/usr/"
  cp -r "${srcdir}/usr/bin" "${pkgdir}/usr/"
  cp -r "${srcdir}/usr/share" "${pkgdir}/usr/"
}

