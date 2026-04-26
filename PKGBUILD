# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.51
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

sha256sums_x86_64=('71b67487cae82f909bd93826534153502e499e93815cea102a2192faa5f922ea')
sha256sums_aarch64=('cc8badf1e28a2c254a1130b9317c52dd0afc66693e49d5b417ff2fa64565f8cd')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
