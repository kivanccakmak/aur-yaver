# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.43
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

sha256sums_x86_64=('5270545d60ba5ea42239b0b4cf9945f85a3987c56a5fbaa32cc65a223c099b2c')
sha256sums_aarch64=('24c34f10c86bf6b428a14ef4c294c3bfa42629ae693868694bc009db1374def6')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
