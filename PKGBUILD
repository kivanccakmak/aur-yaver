# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.89
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

sha256sums_x86_64=('002495649be6832d9b285e582d24199e8bcae71d4ab53cbad959b9fdc3b48de2')
sha256sums_aarch64=('031de802be3f9baec6b1236e8c42d79a4d775a827ef82721cae203ea6a98f392')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
