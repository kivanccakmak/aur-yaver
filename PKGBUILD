# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.91
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

sha256sums_x86_64=('dc31240bb692b3701347bc0156319ecf3215b9f44f3ea39d041b3159a86cbedc')
sha256sums_aarch64=('0e14aad19488804fc9b48bfa7a548c80821397dacf81c6d1e515ac7f55484df0')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
