# Maintainer: 3XITLiGHT <3xitlight@gmail.com>

_gitname=awesome-fonts
_autor=3xitlight
pkgname=awesome-fonts
pkgver=r1.1
pkgrel=1
pkgdesc="3xitlight's fav fonts."
arch=('any')
url="https://github.com/${_autor}/${_gitname}"
license=('unknown')
options=('!strip')
provides=("awesome-fonts")
conflicts=("awesome-fonts")
source=("git+${url}.git")
sha256sums=('SKIP')

pkgver() {
    cd "${_gitname}"
    printf "r%s.%s" "$(git rev-list --count HEAD)" "$(git rev-parse --short HEAD)"
}

package() {
	install -d ${pkgdir}/usr/share/fonts
	cp -rf ${_gitname}/Coda ${pkgdir}/usr/share/fonts/
	cp -rf ${_gitname}/Continuum ${pkgdir}/usr/share/fonts/
	cp -rf ${_gitname}/Gruppo ${pkgdir}/usr/share/fonts/
	cp -rf ${_gitname}/Proggy ${pkgdir}/usr/share/fonts/
	cp -rf ${_gitname}/SonySketch ${pkgdir}/usr/share/fonts/
	cp -rf ${_gitname}/SquadaOne ${pkgdir}/usr/share/fonts/
	cp -rf ${_gitname}/Terminess ${pkgdir}/usr/share/fonts/
	cp -rf ${_gitname}/TurretRoad ${pkgdir}/usr/share/fonts/
	cp -rf ${_gitname}/Zekton-rg ${pkgdir}/usr/share/fonts/
    find ${pkgdir}/usr -type f -exec chmod 644 {} \;
    find ${pkgdir}/usr -type d -exec chmod 755 {} \;
}
