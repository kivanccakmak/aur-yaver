# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.0
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

sha256sums_x86_64=('3ca876907d1eda01dc241f17b77111cfa3a5f6b6fdf40d02c03dbdea14340852')
sha256sums_aarch64=('7bc826085222cbe782bd45ffcf0534cae6156fd99af9c8f3fff586e9e3ed9a68')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
