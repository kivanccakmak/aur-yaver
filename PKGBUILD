# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.34
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

sha256sums_x86_64=('7b0623684f628b5f8455f82e1935968bad6e5a3bc96bfdfa71a0b1f79fbe7260')
sha256sums_aarch64=('f6ac8268200b2391fccff04261b51ed1e859719e1aa70a7ac574d3e9c901f1e7')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
