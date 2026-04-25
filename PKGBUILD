# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.43
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

sha256sums_x86_64=('916b00de679904d89f668957bcb426e614aa4c50842715995e3d3ec88ba05596')
sha256sums_aarch64=('90fdd524ed70ec2f05ae6d1bf3b1117702ffc7b597d908a3c6388f6941acac44')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
