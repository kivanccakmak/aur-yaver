# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.52
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

sha256sums_x86_64=('15a41b9eeb9378e862cfb0148f21ae4f2c281456b9ae702d51e5f071e1d02734')
sha256sums_aarch64=('476b54a3fec38120eea03cc59b6e642351d53447e83d4c578c708a65e7310b2b')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
