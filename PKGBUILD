# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.110
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

sha256sums_x86_64=('29619fe79e17d972b4ebd6dee52f10b0721b21add9f625c5771e181288076570')
sha256sums_aarch64=('f0fa6e84893a22c77371f014417da93721d2202b1fa21dd09aeb0c1dff90397d')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
