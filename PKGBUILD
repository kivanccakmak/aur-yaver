# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.94
pkgrel=1
pkgdesc="Run AI coding agents from your phone — Claude, Codex, Aider, or custom"
arch=('x86_64' 'aarch64')
url="https://yaver.io"
license=('custom:FSL-1.1-Apache-2.0')
provides=('yaver')
depends=('nodejs')
optdepends=('npm: for yaver push (React Native to device)')

source_x86_64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-amd64.tar.gz")
source_aarch64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-arm64.tar.gz")

sha256sums_x86_64=('14232bc91cf335bd2d8c6718080239bd060b40e865647e68e737f8f1dce8316c')
sha256sums_aarch64=('e1a16674268ff878771f0b921c2ca0678b00a1f9585ad3332ef6861d76efb3ec')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
