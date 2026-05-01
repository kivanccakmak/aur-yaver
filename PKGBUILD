# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.107
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

sha256sums_x86_64=('07ef19e6c0145a8079fb68436dfc4408e619b37ffd0b420fa216de145bbbe065')
sha256sums_aarch64=('04c2f732280d4dbb3d13e4ee6994ac9e82dbbcf29052106e5601f72e8158d4fc')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
