# This file is part of BlackArch Linux ( https://www.blackarch.org/ ).
# See COPYING for license details.

pkgname=blackarch-wallpaper
pkgver=3.0
pkgrel=2
epoch=1
pkgdesc='The default BlackArch Linux wallpaper.'
arch=('any')
url='https://github.com/BlackArch/blackarch-artwork'
license=('custom:unknown')
source=("$pkgname.png::https://ronosu.xyz/next/blackarch/tasin.png")
sha512sums=('305b97d684b6b2e82c2eb57347fe18e1494c013343fae19bce608c65cd26efcc57c107723d395d9e84551ec6e5139135ce8672fd266b3e2150e1f66057688447')

package() {
  install -Dm 644 "$pkgname.png" "$pkgdir/usr/share/blackarch/wallpaper.png"
  install -Dm 644 "$pkgname.png" "$pkgdir/usr/share/blackarch/wallpaper.jpg"
}
