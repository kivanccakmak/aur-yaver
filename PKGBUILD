# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.98
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

sha256sums_x86_64=('1ea0cc12a42cb6e8a2ed68a015c1b87b30a72554d4f19011cf3b0b953855491d')
sha256sums_aarch64=('317070c8252ceaeba1aa833c4e7c1f1f7a4050356b38bdb0d0a74c5929c8dcec')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
