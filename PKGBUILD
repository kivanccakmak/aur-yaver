# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.69
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

sha256sums_x86_64=('8177adc8ae36bdffa366fc7a0d8344acabc21e27b34779d45a53b2702a6143d2')
sha256sums_aarch64=('4e196018acf1920344f40de7899a71b78c752c30ba8dbfea7d7245016701b59b')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
