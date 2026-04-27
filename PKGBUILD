# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.78
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

sha256sums_x86_64=('7349f940d563c37bcae5afcd7ec1eae973c5c053fd8148571003915998e7a73a')
sha256sums_aarch64=('ca29b041e3e0306d0d84257fe5cf13efb84d2c86a678d9482b875977f6e332b5')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
