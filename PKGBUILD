# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.102
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

sha256sums_x86_64=('8fd96848276a8177dce0a9403de827d34c9626a8a17ffc90c98b6a396c73fb0e')
sha256sums_aarch64=('a351ec638dbfc5a3b3f8362ae05a690ec5ebde8173726dc552cbe1aa50ceb01f')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
