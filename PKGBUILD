# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.108
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

sha256sums_x86_64=('f82591067c2ab016d3ddb541521c80a4550f127f265eea7a99e8b6a5b82db5d1')
sha256sums_aarch64=('8d2fb82ed6d0aa035004bfdbb7d7a7f3a7e667bea72bcc21ae58facfd74218e2')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
