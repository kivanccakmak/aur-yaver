# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.114
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

sha256sums_x86_64=('971dd2e5d41d059113f480870a4660d0e8bc55ccc6d281535553840289188284')
sha256sums_aarch64=('83546137f5944c9bac897d68131f12c8cfdc7a1ccab741bca863d108a0d90e62')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
