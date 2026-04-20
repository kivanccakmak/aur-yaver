# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.14
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

sha256sums_x86_64=('f052765de5f9862537c16bd43bb3f52b400fbcec89109f7fffa6f8ae4b60374c')
sha256sums_aarch64=('4ff95b4a0c83853ddc7b1b94827ddab2e09155325d3c9d49353b5f7a79c52ac4')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
