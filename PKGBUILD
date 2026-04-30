# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.95
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

sha256sums_x86_64=('5407cb614844295ba9ae914c53beae3ac8b8a06dc8b40b4bbb33dc7835d77fc8')
sha256sums_aarch64=('e4fed4b77cd1890dcb8f68c37735e66d6a07ad660115bfbfca3486a32e7e310e')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
