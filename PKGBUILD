# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.111
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

sha256sums_x86_64=('dd088d9cd3121e08c17126e534c6d4bcf1406e11ec356dc187ce843452368761')
sha256sums_aarch64=('f5890da85c294b5849dc32140b28368eb78771b68090a87f3bd1e354f46d849b')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
