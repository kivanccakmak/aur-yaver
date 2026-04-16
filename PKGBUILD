# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.95.0
pkgrel=1
pkgdesc="Run AI coding agents from your phone — Claude, Codex, Aider, or custom"
arch=('x86_64' 'aarch64')
url="https://yaver.io"
license=('MIT')
provides=('yaver')

source_x86_64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-amd64.tar.gz")
source_aarch64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-arm64.tar.gz")

sha256sums_x86_64=('fda56382fba7be2b0413ae125a4dfd8d83791f38cb8e3d8d7fe8b4b9f40d0dc2')
sha256sums_aarch64=('4a20ca4c70c0ba701ffc2d5cb4ac464f5feeffbd83c2df0c031433096e8f7111')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
