# Maintainer: Your Name <youremail@domain.com>
pkgname=i3-fancylock-mm
pkgver=1
pkgrel=1
pkgdesc="A lock screen using i3lock with multi monitor support"
arch=(any)
url="https://github.com/Freggar/i3-fancylock"
license=('MIT')
groups=()
depends=('i3lock' 'imagemagick')
makedepends=()
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=
changelog=
source=()
noextract=()
md5sums=() #autofill using updpkgsums

build() {
  echo "Nothing to build"
}

package() {
  sudo cp -r .. /opt/i3-fancylock-mm
  sudo ln -s /opt/i3-fancylock-mm/lock /usr/bin/lock
}
