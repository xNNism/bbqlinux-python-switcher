# Maintainer: Daniel Hillenbrand <codeworkx@bbqlinux.org>

pkgname=bbqlinux-python-switcher
pkgver=1.0.1
pkgrel=1
pkgdesc="BBQLinux Python Switcher"
arch=('any')
url="https://github.com/bbqlinux/bbqlinux-python-switcher"
license=('GPL')
depends=('bbqlinux-artwork' 'python2' 'qt4' 'python2-pyqt4')

package() {
  cd "$pkgdir"

  install -Dm755 "$srcdir/usr/bin/bbqlinux-python-switcher" usr/bin/bbqlinux-python-switcher

  cp -R "$srcdir/usr/lib/" usr/lib
  cp -R "$srcdir/usr/share/" usr/share
}
