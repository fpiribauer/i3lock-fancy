# Maintainer: Your Name <youremail@domain.com>
pkgname=i3-fancylock
pkgver=1
pkgrel=2
pkgdesc="A lock screen using i3lock with multi monitor support"
arch=(any)
url="https://github.com/fpiribauer/i3-fancylock"
license=('MIT')
depends=('i3lock' 'imagemagick')
source=(l)
sha256sums=()

build() {
  echo "Nothing to build"
}

package() {
  sudo cp -r .. /opt/i3-fancylock-mm
  sudo ln -s /opt/i3-fancylock-mm/lock /usr/bin/lock
}
