# Maintainer: Matt C <mdc028[at]bucknell[dot]edu>

pkgname=crystal-grub-theme
pkgver=1.0.0
pkgrel=1
pkgdesc="Grub theme for Crystal Linux"
arch=('any')
url="https://git.tar.black/crystal/grub-theme"
depends=('grub')
source=("stuff::git+https://git.tar.black/crystal/grub-theme.git")

package() {
    cd ${srcdir}/stuff
    mkdir -p ${pkgdir}/usr/share/grub/themes
    cp -rv crystal ${pkgdir}/usr/share/grub/themes/.
}
