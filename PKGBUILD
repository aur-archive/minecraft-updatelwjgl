# Maintainer: vorenon <edelmann.manuel@gmail.com>
pkgname="minecraft-updatelwjgl"
pkgver=20130607
pkgrel=1
pkgdesc="Script to update Minecraft's LWJGL library, preventing the stuck keys issue"
arch=("any")
url="https://gist.github.com/2086385"
license=('unknown')
depends=("wget" "unzip")
install="minecraft-updatelwjgl.install"
source=("https://gist.github.com/aperson/2086385/raw/f6d05ed4902afa1e991a0bd0a2557bd040d129ce/update_lwjgl.sh" "minecraft-updatelwjgl.install")
md5sums=('57df248cd456d71b88571416b067c8f9'
         '95f5f8c325016fe857643b52a38bd5d2')

package() {
    install -D -m755 update_lwjgl.sh ${pkgdir}/usr/bin/minecraft-update-lwjgl.sh
}
