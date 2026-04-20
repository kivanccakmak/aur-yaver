# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.13
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

sha256sums_x86_64=('5dc6a793c8d64a2e33bc05a19e791ed82b00ac88a7d8dec2968e1dfb155c0090')
sha256sums_aarch64=('82ef4d261eb5bd79c6d2445802a055e194669e2da8b02c4ef733b1a568f60ebe')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
