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
source=(presmaker info_default.pmk blank_slide.svg)
md5sums=('SKIP' 'SKIP' 'SKIP')

package() {
  
  cd $srcdir
  install -D -m 755 presmaker $pkgdir/usr/bin/presmaker
  install -D -m 755 info_default.pmk $pkgdir/usr/share/presmaker/info_default.pmk
  install -D -m 755 blank_slide.svg $pkgdir/usr/share/presmaker/blank_slide.svg
  
}
