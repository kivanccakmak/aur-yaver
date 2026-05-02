# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.117
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

sha256sums_x86_64=('dce58b75249cac653e0af0aae9241a42859861c8268493c7edb2a279ec3d0260')
sha256sums_aarch64=('0f1cb0224eb72fbd79552a92cc20b4add95d37e923c728ec00c9f9a99e00b48d')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
