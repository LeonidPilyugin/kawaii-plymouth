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
sha256sums=('1c9d045c2525ec4ccd6241300a10830f81cd0dec57ff6e3fe61cb75d4e458242')

package() {
    dir=$pkgdir/usr/share/plymouth/themes/kawaii
    install -dm755 $dir
    cp $srcdir/files/* $dir/
}
