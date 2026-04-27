# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.67
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

sha256sums_x86_64=('5801e66b25ef544660c0cabbb0bb2335db2d6a2baf80eb18b8b59efe9161274b')
sha256sums_aarch64=('305af02e9cc363dcc4cc9881ab39bcbf1430a13d6ef6071efe35ac7af8cdf1c3')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
