# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.35
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

sha256sums_x86_64=('07e210e6d95989994451cf4d85161c8d2eb57b5f0dffbc9549b0a52464692818')
sha256sums_aarch64=('177a8bfcd45f1e8fafeb1352f3183081d698524fc7b4552a4d81d117f635a69b')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
