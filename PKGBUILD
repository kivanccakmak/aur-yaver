# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.73
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

sha256sums_x86_64=('2852a36f081c2a7467efe8f4fb75c59cddf43e7fc69ac96d439619cbb508f658')
sha256sums_aarch64=('812fe07ee099ee4087f8d3117f89f15d280f983897c18c73ab4c42e522ea7b3e')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
