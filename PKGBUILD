# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.5
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

sha256sums_x86_64=('06a42dabee49f0f760d54aa86deebc94f73ae2dcea46c1c44e8e7cf78fafd10c')
sha256sums_aarch64=('6b5f03befef01652d55c283d6900e5550a6f14c6656079c54b21223305aec4bb')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
