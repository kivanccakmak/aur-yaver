# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.96.7
pkgrel=1
pkgdesc="Run AI coding agents from your phone — Claude, Codex, Aider, or custom"
arch=('x86_64' 'aarch64')
url="https://yaver.io"
license=('AGPL-3.0-only')
provides=('yaver')

source_x86_64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-amd64.tar.gz")
source_aarch64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-arm64.tar.gz")

sha256sums_x86_64=('812d084d9f8b0e7eb3c72f2a579aa19909b86a222595e13d02a41b64bf5c445a')
sha256sums_aarch64=('a0e83ae8d34669f0ed223dfb7e714ec457aafd1215f8def8d27b772dbcad4b20')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
