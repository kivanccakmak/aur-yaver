# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.75
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

sha256sums_x86_64=('70ad3d1e6924bd392e5317e0b25723f2f2fcd471d02aaa9f1b85aad752517789')
sha256sums_aarch64=('e8bca7766d61df629980c5317b29edda4d9ca4679706244adfc78b72992a5cf7')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
