# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.2
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

sha256sums_x86_64=('69081a056cca741809bc79a60b8a28d584c70dc6ebba932580c708f0044d0780')
sha256sums_aarch64=('7bfa33cb724001534ca29f119b19463d5bb60f8cbc178b7ae4789d16bec2fbd6')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
