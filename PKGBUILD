# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.87
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

sha256sums_x86_64=('1397944bf485b044f6524a9466891c9e51c49e1be89b90e1a603673594ed5d8a')
sha256sums_aarch64=('899c48c58fa6dce8a6a20a349a618421238fb8905f6c0871655cf6378b91c514')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
