# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.24
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

sha256sums_x86_64=('40fab2ac402c096847294ba27f01c48b5d5e2a58495f7bc0774a318e2e262bea')
sha256sums_aarch64=('c4e6ef52109503396490dc006f7d63a42b082daead951bb0cb53d8c0a7204825')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
