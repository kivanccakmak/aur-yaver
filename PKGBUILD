# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.105
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

sha256sums_x86_64=('12af6b50ee302d348087d6ea1657b99249049649e08074d7ef5da58a4d37ef68')
sha256sums_aarch64=('810f4ad6f0b432654ddacedde0075bce41e10698aef25aa863f3ee3e892322ed')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
