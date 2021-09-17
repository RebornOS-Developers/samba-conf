# Maintainer: CookieSource <cookiesource@rebornos.org>
# Co maintainer: RebornOS Team <team@rebornos.org>

pkgname=rebornos-samba
confname=nsswitch.conf 
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
source=(${confname})
install=${pkgname}.install

package() {
           mkdir -p ${pkgdir}/etc/
           install -m644 ${confname} ${pkgdir}/etc/${confname}-new
           #cp ${confname} ${pkgdir}/etc/${confname}-new
}

md5sums=('94ef0eaa504b740f2f647cbf121f3d0c')
