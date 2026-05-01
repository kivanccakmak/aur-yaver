# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.100
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

sha256sums_x86_64=('28ca654019fe7ab2d6f84d95b0ad3761c315c89f24478bcf9c1eea84ec398930')
sha256sums_aarch64=('2a51b07cd695919b3914961f81c47900449b4db1cc585ac89bdf9622dda2d028')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
