# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.22
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

sha256sums_x86_64=('05ee70e877353733372cd8ad3b27083d696891dbcdeaa767703bc1796900dc64')
sha256sums_aarch64=('66ec33f3f74b2494203fd484baa5d0cc8cd32610ac4c358d237d05360795490d')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
