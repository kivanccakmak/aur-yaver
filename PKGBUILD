# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.96.5
pkgrel=1
pkgdesc="Run AI coding agents from your phone — Claude, Codex, Aider, or custom"
arch=('x86_64' 'aarch64')
url="https://yaver.io"
license=('AGPL-3.0-only')
provides=('yaver')

source_x86_64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-amd64.tar.gz")
source_aarch64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-arm64.tar.gz")

sha256sums_x86_64=('3a7ae4e1d583bd5659a14e8c8762a0e2d4cd5205389ee2379027c55a011e420a')
sha256sums_aarch64=('3500c305a3bc481721fa9960b87b6820b9198d8ce07c8617f570049538b2d443')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
