# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.46
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

sha256sums_x86_64=('4fdac8d94761bdb127ded02fbce021a356a983143889a75e325cda6de31cc4a3')
sha256sums_aarch64=('24b1b18c49b489c51e442131988763439ac5313f613cf092b15d405e17b8e90b')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
