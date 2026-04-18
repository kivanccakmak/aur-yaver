# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.96.2
pkgrel=1
pkgdesc="Run AI coding agents from your phone — Claude, Codex, Aider, or custom"
arch=('x86_64' 'aarch64')
url="https://yaver.io"
license=('AGPL-3.0-only')
provides=('yaver')

source_x86_64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-amd64.tar.gz")
source_aarch64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-arm64.tar.gz")

sha256sums_x86_64=('abfa246f87df6944849b51ad8cea3f063b971d92c0822e55845e05394975b75b')
sha256sums_aarch64=('90f745c3e648ef7b757a5bf467068a5813107411190faf7f3c2409036cfa1833')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
