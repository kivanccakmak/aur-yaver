# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.96.11
pkgrel=1
pkgdesc="Run AI coding agents from your phone — Claude, Codex, Aider, or custom"
arch=('x86_64' 'aarch64')
url="https://yaver.io"
license=('AGPL-3.0-only')
provides=('yaver')
depends=('nodejs')
optdepends=('npm: for yaver push (React Native to device)')

source_x86_64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-amd64.tar.gz")
source_aarch64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-arm64.tar.gz")

sha256sums_x86_64=('3fcf4de0d3d4ad196f48432a629b7513cb4a68230421981f1f36954b07758003')
sha256sums_aarch64=('c48b54dc699a3387df6f53cac62b1b936bc9671170544beaeafbc57ebc65367d')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
