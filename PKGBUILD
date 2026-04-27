# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.62
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

sha256sums_x86_64=('34a6109862a42afc9895d5bd67e84915932fb6a04702973ee7ad819bed3274ae')
sha256sums_aarch64=('cd5d2b9f816050b1dbb57fe9ea14dfeb5cfbcedc253f8378423fae4c80ac7ff1')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
