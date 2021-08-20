# Maintainer epsilonKNOT <epsilon.aur@epsilonKNOT.xyz>

pkgbase=uwebsockets
pkgname=uwebsockets
pkgver=19.3.0
pkgrel=1
pkgdesc="Simple, secure & standards compliant web server for the most demanding of applications"
url="https://github.com/uNetworking/uWebSockets"
license=('Apache')
arch=('any')
source=( "${pkgname}-${pkgver}.tar.gz::https://github.com/uNetworking/uWebSockets/archive/v${pkgver}.tar.gz" )
sha256sums=('6f709b4e5fe053a94a952da93c07c919b36bcb8c838c69067560ae85f97c5621')
depends=( usockets )

package() {
	cd "uWebSockets-${pkgver}"
	mkdir -p "${pkgdir}"/usr/include/uWebSockets
	cp -a src/. "${pkgdir}"/usr/include/uWebSockets
}

#vim: syntax=sh
