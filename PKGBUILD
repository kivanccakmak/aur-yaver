# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.3
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

sha256sums_x86_64=('8091c1e44fbdef5dca6661dc506f55aab72a9936d8479ec6bf904280bfb4deed')
sha256sums_aarch64=('9366da871025496b86b95dd91a087507ab06f58465da4af6827af9e830515437')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
