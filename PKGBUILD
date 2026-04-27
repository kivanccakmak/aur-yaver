# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.64
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

sha256sums_x86_64=('2c0b55c01cc92125005167c277ac439ca6483dbc657ee86438f15ab22786173b')
sha256sums_aarch64=('1390004316c55b69aa58a18194cddadb8c979372160a5300d32dc37c6e02c580')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
