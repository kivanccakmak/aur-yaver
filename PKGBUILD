# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.123
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

sha256sums_x86_64=('4e6da23959294898d2e80401333b01cc77710bbaac41da33e1318f0745cb7cc7')
sha256sums_aarch64=('eb739ea8ddff82278ead6b10baec85a1ef0e29673b8fd512bc2cdbbfcf432ef9')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
