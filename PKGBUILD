# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.7
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

sha256sums_x86_64=('8edec3da8946677f517b50814b79c2ace6a61758d7e42a0a9b72a9af07544ffc')
sha256sums_aarch64=('0ba4b93fa070851712bb6ba5ccaa65dd8b6b101ee9d11f17350148f2ef4f843d')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
