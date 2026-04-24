# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.32
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

sha256sums_x86_64=('4bf0d000c1a5ebb2e1f18e0e4526cd05397f08e300aac67c64f8fad5e8e1bb47')
sha256sums_aarch64=('f8fac5a97ef3a21679d659f8e4518d167bf854c70789cdbabcaa97f895c0123e')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
