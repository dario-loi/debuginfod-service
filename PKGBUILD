pkgname=debuginfod-service
pkgver=1.0
pkgrel=1
pkgdesc="Systemd service file for debuginfod"
arch=('any')
license=('GPL')
depends=('debuginfod')
source=("debuginfod.service")

# md5sums on source files
md5sums=("9cf3ab8e1cd4a5fa8027c44dd4e29678")

package() {
    install -Dm644 "$srcdir/debuginfod.service" "$pkgdir/usr/lib/systemd/system/debuginfod.service"
}
