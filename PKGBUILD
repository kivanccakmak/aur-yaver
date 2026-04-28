# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.93
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

sha256sums_x86_64=('04a7f5dc511a68e010146f1f3c6f02524ac61050eac87676a10c71c37b54353a')
sha256sums_aarch64=('c2566f2e7e9ab44bc8d3cb8bb1d18f40cfb16218c46b22dda8228d542f62f310')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
