# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.77
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

sha256sums_x86_64=('cffa15f2ac5d781122a12aacf526e743813942a6cfed7899f0417a2e659e695b')
sha256sums_aarch64=('9cc1c5c22d99d03dd399afa9d2673d9847d2ae4ff22eda2eb709a4405c33cbec')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
