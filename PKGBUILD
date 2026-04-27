# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.59
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

sha256sums_x86_64=('c043b8e1b9e463af54f3506fd4b9622861606428477fbfc809e2568b1ea21c38')
sha256sums_aarch64=('34472e85a701d0e8458d37f90f586108f8753689a39403157bdcf6109f193a8a')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
