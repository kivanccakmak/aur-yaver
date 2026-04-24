# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.31
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

sha256sums_x86_64=('d455abb636704f679a030783fed0eb1d1094e6739839ace09d21269b324d943c')
sha256sums_aarch64=('8648c751edbfca6b3ac672537ff188e89c5ab1a69aa2e9f4e74da4c7a37d3eec')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
