# Maintainer: Leonid Pilyugin  <l.pilyugin04@gmail.com>

pkgname=kawaii-plymouth
pkgver=1.0
pkgrel=1
pkgdesc='Kawaii Plymouth theme.'
url='https://github.com/LeonidPilyugin/kawaii-plymouth'
groups=(kawaii)
arch=(x86_64)
depends=('plymouth')
license=('GPL3')
source=("$pkgname-$pkgver.tar.gz::https://github.com/LeonidPilyugin/$pkgname/releases/download/v$pkgver/files.tar.gz")
sha256sums=('97f703bc35f8f4cecb489084b20148db5ff5d27c69d8d73f59ddd30b7da26085')

package() {
    dir=$pkgdir/usr/share/plymouth/themes/kawaii
    install -dm755 $dir
    cp $srcdir/files/* $dir/
}
