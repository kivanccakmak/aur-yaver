# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.11
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

sha256sums_x86_64=('e7427e3de7fffbec2d3a8a50e4e7ff5fd5deaaa324a0a2b3271ffc6835c77cf9')
sha256sums_aarch64=('73c0cef27f35836b6dddb6b1747b32a3e11016741aceabe3ab0eff3e3a83e152')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
