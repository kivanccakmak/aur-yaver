# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.78.0
pkgrel=1
pkgdesc="Run AI coding agents from your phone — Claude, Codex, Aider, or custom"
arch=('x86_64' 'aarch64')
url="https://yaver.io"
license=('MIT')
provides=('yaver')

source_x86_64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-amd64.tar.gz")
source_aarch64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-arm64.tar.gz")

sha256sums_x86_64=('8c2ed8582dd2af723715f3d3d7bb5dc7d10c5d63e794020cdc1edc1def49989f')
sha256sums_aarch64=('1e5fc4786ee2ed2cea189b7f5667c6c366a4e4bd057be45262d99f076bc19cc1')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
