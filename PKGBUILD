# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.96.10
pkgrel=1
pkgdesc="Run AI coding agents from your phone — Claude, Codex, Aider, or custom"
arch=('x86_64' 'aarch64')
url="https://yaver.io"
license=('AGPL-3.0-only')
provides=('yaver')

source_x86_64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-amd64.tar.gz")
source_aarch64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-arm64.tar.gz")

sha256sums_x86_64=('254a612b357d5c47012de0608e4d3f12efa6317e5ed97dddd0bcfbc4d01d6b3b')
sha256sums_aarch64=('d68edf6dfab6a3f9aa5f910967c6f72a1a8c7fdcf3701c940fcb11b42972a55d')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
