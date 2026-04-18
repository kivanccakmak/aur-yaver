# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.96.4
pkgrel=1
pkgdesc="Run AI coding agents from your phone — Claude, Codex, Aider, or custom"
arch=('x86_64' 'aarch64')
url="https://yaver.io"
license=('AGPL-3.0-only')
provides=('yaver')

source_x86_64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-amd64.tar.gz")
source_aarch64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-arm64.tar.gz")

sha256sums_x86_64=('a5b38495cb70056e660881037278602f7a55950990d4e98a026501cf99afb652')
sha256sums_aarch64=('20e115caf8f373d3fef1142ce846a4888e9f67d8d9f6544eb33f26b89de302d0')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
