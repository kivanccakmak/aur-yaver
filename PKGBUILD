# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.92
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

sha256sums_x86_64=('4f0cd3317f4983810cd5a87580ab05663ad44060cdb60482720f3c939c78ebfb')
sha256sums_aarch64=('1a4bd4522ed7fa2e0ff354d50228c8d74e96f0e45d226e660544eeee3ed0660b')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
