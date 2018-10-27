# Maintainer: Alexandre Génin <bellette *pwet* tuxfamily[dot]org>
pkgname=presmaker
pkgver=2.0.0
pkgrel=1
pkgdesc="Makes a presentation from svg files"
arch=('any')
license=('GPLv3')
depends=('inkscape' 'pdftk' 'perl-image-exiftool' 'imagemagick')
optdepends=()
makedepends=()
conflicts=()
replaces=()
backup=()
source=(presmaker)
md5sums=('SKIP')

package() {

  cd $srcdir
  install -D -m 755 presmaker $pkgdir/usr/bin/presmaker
  
}
