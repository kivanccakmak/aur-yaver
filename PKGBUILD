# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.96.6
pkgrel=1
pkgdesc="Run AI coding agents from your phone — Claude, Codex, Aider, or custom"
arch=('x86_64' 'aarch64')
url="https://yaver.io"
license=('AGPL-3.0-only')
provides=('yaver')

source_x86_64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-amd64.tar.gz")
source_aarch64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-arm64.tar.gz")

sha256sums_x86_64=('a44b3a671c78c14bf68308b16265e05067c3364b386dcce9ee1874e8213cee86')
sha256sums_aarch64=('fba3969019fe84fd35d9e82f636c058b97a74958748adf2a45aa8a62769b470b')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
