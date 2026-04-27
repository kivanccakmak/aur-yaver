# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.90
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

sha256sums_x86_64=('9cd1f73f55f282b7e127fd3408d3bb3d50eb5b7e1e19359831766e5d48aebdea')
sha256sums_aarch64=('8464e9d8082415f78bb671c40c166cba037822216176de50dfcf062abff8b39b')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
