# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.80
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

sha256sums_x86_64=('9d1187528c1f1446035561db439502e020349631b117f171dc321f4f17e73df6')
sha256sums_aarch64=('9ad62366520b5cf8b8926aebd688ee4942b2c4073ab58de1ecfc153b544455b0')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
