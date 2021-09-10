# Maintainer: CookieSource <cookiesource@rebornos.org>
# Co maintainer: RebornOS Team <team@rebornos.org>
pkgname=rebornos-samba
_pkgname1=nsswitch.conf 
pkgver=0.2
pkgrel=0
pkgdesc="Set of configurations for Samba on RebornOS"
arch=('any')
url="https://github.com/RebornOS-Developers/rebornos-samba"
license=('LGPL3')
makedepends=('make')
depends=('samba')
provides=(${pkgname})
conflicts=(${pkgname})
source=(${_pkgname1})

package() {
           mkdir -p ${pkgdir}/etc/
           cp ${srcdir}/* ${pkgdir}/etc/
}

md5sums=('94ef0eaa504b740f2f647cbf121f3d0c')
