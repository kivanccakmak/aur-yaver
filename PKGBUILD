# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.79
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

sha256sums_x86_64=('668ad52be61933a659aadf6c55be31cde62ddda0a46e5ad18b1b3060c17239c3')
sha256sums_aarch64=('6dc15180218ffa436095742845eeb3a52589c333e9a0bebfc3f4fb2894ee8d1c')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
