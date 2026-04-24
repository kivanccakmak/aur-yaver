# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.26
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

sha256sums_x86_64=('291328674606a8de92c3a51d31b483c2d2f27307c53360ee54615d73ef56e71c')
sha256sums_aarch64=('9e20889d73cfe32ca1993fb2c78ad7f184744ba969e17e79e2f21156c81eafbb')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
