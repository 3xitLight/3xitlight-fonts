# Maintainer: 3XITLiGHT <3xitlight@gmail.com>

_gitname=aw3some-fonts
_autor=3xitlight
pkgname=aw3some-fonts
pkgver=r4.0be2a36
pkgrel=1
pkgdesc="3xitlight's fav fonts."
arch=('any')
url="https://github.com/${_autor}/${_gitname}"
license=('unknown')
options=('!strip')
provides=("aw3some-fonts")
conflicts=("aw3some-fonts")
source=(
		'Coda-ExtraBold.ttf'
		'Coda-Regular.ttf'
		'Continuum-Bold.ttf'
		'Continuum-Light-Regular.ttf'
		'Continuum-Medium.ttf'
		'Gruppo-Regular.ttf'
		'SonySketch_EF.ttf'
		'Terminess.ttf'
		'TurretRoad-Bold.ttf'
		'TurretRoad-ExtraBold.ttf'
		'TurretRoad-ExtraLight.ttf'
		'TurretRoad-Light.ttf'
		'TurretRoad-Medium.ttf'
		'TurretRoad-Regular.ttf'
		'Zekton-rg.ttf')


sha256sums=(
		'07b67e77de3ae9904112658f44554fa1d4faf6f8b7508387d0dfb212c57ba8fc'  
		'b9b68229d333a33c6c270c947d600625e2bdfee38167723a0b5679b220ffd463'   
		'd9cbe0bd28cdc835c6525e789d6d6b2791dec48011662a52b252a08c3da01fdc'  
		'c3e01fc1c51af4d7195bd0fb2f379113a0d882992ea78849b3f0acdd535c2232'  
		'b5766d37c228e1775c5961d58014c8fc36c85ef675e57c54a5447e67d076ef3e'  
		'94a67c2781f03030281af65795b177233d4979d387169d0e5b2f44f537cefaad'  
		'12257e91f3992d663533828c64bc0485bb9bd8f6d9868312c4727363fe442781'  
		'81e8bea860e7acab9bfb3e17a3eb8c5348668edfde9eb19ba16eca566ece55cc'  
		'2bb6d2741ac837431e1c83cd6216594120c34c8cebbf0b70d1b1c3eb43eac38b'  
		'22a04471edce68ba9a239ac0bb703a89b90d810ab5e0ba1340910028bdf42afc'  
		'a4f7df4fa525905350708fb2dc0f656a3757b980cbb8a68d4f262a894a7b2cae'  
		'3be2d5ae82bf8ebb481771635634cc340ec0d5d234917f71bfeaa2285d908bca'  
		'e18a4ecd3a630c9acf6272beb0abd156f40cd806d46403f10bd1847525fb25f0'  
		'7e2db45368891a9fe28c61f569401e036e341091a09746b0bc6547cc5eb7b148'  
		'82904c6613e45c4e5a988d242ce183d10d78a4cc6868e74c618e0dcb773472fe')

#pkgver() {
#    cd "${_gitname}"
#    printf "r%s.%s" "$(git rev-list --count HEAD)" "$(git rev-parse --short HEAD)"
#}

package() {
	install -d ${pkgdir}/usr/share/fonts/aw3some-fonts
	cp -rf *ttf ${pkgdir}/usr/share/fonts//aw3some-fonts
}
