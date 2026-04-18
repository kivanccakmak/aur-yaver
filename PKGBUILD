# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.96.3
pkgrel=1
pkgdesc="Run AI coding agents from your phone — Claude, Codex, Aider, or custom"
arch=('x86_64' 'aarch64')
url="https://yaver.io"
license=('AGPL-3.0-only')
provides=('yaver')

source_x86_64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-amd64.tar.gz")
source_aarch64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-arm64.tar.gz")

sha256sums_x86_64=('948e1cdf93151f975092823b06804f5a4bd435c18db623d4ddc3597f50c85988')
sha256sums_aarch64=('b6eaf1a8123a02978dc6e37d94be2dc51345ed46319eb3323428cba0830742fa')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
