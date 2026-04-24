# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.27
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

sha256sums_x86_64=('d76a29b7308f806f3a229d20a531409566f93d0e2fbf422702ce71a2cf2f7b82')
sha256sums_aarch64=('2991299cfa3d1cd9bde6c17807e587687fba87555d7391a434b50bd3d91f753e')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
