# Maintainer: Daniel Hillenbrand <codeworkx [at] bbqlinux [dot] org>

pkgname=bbqmkiso
pkgver=17
pkgrel=1
pkgdesc="Tools for creating BBQLinux live and install iso images"
arch=('any')
url="https://github.com/bbqlinux/bbqmkiso"
license=('GPL')
depends=('archiso')

package() {
  cd "$pkgdir"
  install -Dm755 "$srcdir/usr/bin/bbqmkiso" usr/bin/bbqmkiso
}
