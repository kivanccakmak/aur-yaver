# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.99
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

sha256sums_x86_64=('6b459e7edec36ef1c70a8fb96ae4ecd8869ca39418d7dce342b519b3309afa70')
sha256sums_aarch64=('8c9a692ed90477e20d329f3da850af06205ef7054a7ab9348d73c9e17867f1d8')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
