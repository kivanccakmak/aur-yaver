# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.106
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

sha256sums_x86_64=('6ad47bc45a409276665e701569d3be77edf18e5111c1836dc8dd6f5ea0f0d986')
sha256sums_aarch64=('116d490d64c8a0bf2f3e42d03f60d7f8acc9ab92c70ffad577768cf9a8b9d70c')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
