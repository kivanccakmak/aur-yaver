# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.45
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

sha256sums_x86_64=('06f0edd118b8de462a41205db28ed4bdd9566ed8d574de5776d3ac7eaa53e3f9')
sha256sums_aarch64=('2141b0d71afcc5c96f2fac819c1825a78f9adfd24b644d8fde72bfe9baeacc45')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
