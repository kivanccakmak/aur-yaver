# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.25
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

sha256sums_x86_64=('02f52ac2c6bd51e94c7a0327011d30e165dc641ddff79c5788053989fdcf0aa2')
sha256sums_aarch64=('4d3a27499617c321793509a1479e40851628b2fb69200caf7167ef77f7a0be9b')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
