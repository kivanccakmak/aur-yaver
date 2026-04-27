# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.63
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

sha256sums_x86_64=('78f68cf32fcada28d0e74439ec31fb7cc2c2259762e7c72a20f1159e7b021bcc')
sha256sums_aarch64=('1cd2573e56908714905338a241276c09f2d93b052788dfc4cdb935222e5b5ba9')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
