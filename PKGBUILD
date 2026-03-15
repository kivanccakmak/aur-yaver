# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.25.0
pkgrel=1
pkgdesc="Run AI coding agents from your phone — Claude, Codex, Aider, or custom"
arch=('x86_64' 'aarch64')
url="https://yaver.io"
license=('custom:Proprietary')
provides=('yaver')

source_x86_64=("https://github.com/kivanccakmak/yaver-cli/releases/download/v${pkgver}/yaver-linux-amd64")
source_aarch64=("https://github.com/kivanccakmak/yaver-cli/releases/download/v${pkgver}/yaver-linux-arm64")

sha256sums_x86_64=('edad246f7232b8e22582a76e3602cdfc4df5fc652eb17245cd09fac7b36095b1')
sha256sums_aarch64=('17dc2029e825980a480c4ad56ca464c522f5ba46c7585ae278839e6e4641400d')

package() {
    if [ "$CARCH" = "x86_64" ]; then
        install -Dm755 yaver-linux-amd64 "$pkgdir/usr/bin/yaver"
    else
        install -Dm755 yaver-linux-arm64 "$pkgdir/usr/bin/yaver"
    fi
}
