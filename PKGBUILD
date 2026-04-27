# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.74
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

sha256sums_x86_64=('8e5fe2c7a0013d19c1626b0bc327821796912c4f6728cee5ee55cae9f67f5f6d')
sha256sums_aarch64=('ab63360182f9669d6a74b870c58aab3d2068385d33fa87603ef4f905fc5d8530')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
