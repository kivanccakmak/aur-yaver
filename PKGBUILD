# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.119
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

sha256sums_x86_64=('39a6e0f62828b35d5cbb382b20628490a007c4a5f58909e3ba17843078125fbb')
sha256sums_aarch64=('7463d4922a862b99977f2446893e10845f45d63839a403954e928f606f916411')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
