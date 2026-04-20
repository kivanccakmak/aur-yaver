# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.10
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

sha256sums_x86_64=('c715eccf179a076591c51a99aa5a36abd402ad5e9e87729f262b5eb7c49db511')
sha256sums_aarch64=('03bceabf988805de91c08107e004535f8d1db53737abc5ff4e17777ba0e4da38')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
