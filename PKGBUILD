# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.15
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

sha256sums_x86_64=('efe3f4c0172cdf7b276eaa260fd9f8d0584f36f90c10a98c3a6067e8626dafa1')
sha256sums_aarch64=('4ae9c99577d7d33b9192ce7488911a1df9c7ac777aa2cde308782b8cd8b5698a')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
