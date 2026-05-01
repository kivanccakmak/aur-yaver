# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.101
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

sha256sums_x86_64=('5e65d3949fc32e4ee2923bd0db97c39eba24bef91745a895db048ab36c2cbc6f')
sha256sums_aarch64=('0326ac52326468fa8f20ee209880d631708f2cdbf46be991415edcbb1997518b')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
