# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.60
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

sha256sums_x86_64=('04626f3e1e9fec723423236d625781e9d5db156eeea89e134fec520286f6a0d3')
sha256sums_aarch64=('7fb521906bb5c574bd56398c23cc0d8a02df10008042e5c212aee6c031d3f22b')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
