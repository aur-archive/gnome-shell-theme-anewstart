# Maintainer: Alucryd <alucryd at gmail dot com>
pkgname=gnome-shell-theme-anewstart
pkgver=3.2
pkgrel=1
pkgdesc="A GNOME Shell theme based on the ANewStart Suite"
url="http://alecive.deviantart.com/art/GNOME-shell-ANewStart-268147359"
license=('GPL3')
arch=('any')
depends=('gnome-shell')
optdepends=('gnome-tweak-tool: Easy theme switcher')
source=('http://www.deviantart.com/download/268147359/gnome_shell___anewstart_by_alecive-d4fnbtr.zip')
md5sums=('6cd64fba481f1c293c6bf6112968d8f7')

package() {
    cd $srcdir
    mkdir -p $pkgdir/usr/share/themes
    mv ANewStart ${pkgdir}/usr/share/themes/
}

