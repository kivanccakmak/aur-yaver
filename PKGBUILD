# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.47
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

sha256sums_x86_64=('18ab699ab5fd5cc48b1e58350fca27ea41d3ebd6f889679319e7d253a18cf523')
sha256sums_aarch64=('590fb790a12eaf463841fa3fe9b0a5b7be7d7d5e5f0b57608c6fc4519d2407fd')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
