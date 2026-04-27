# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.83
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

sha256sums_x86_64=('b5bd1b33237173642bb78e3ee5191158c0401b3debb479d774bad60510d309ed')
sha256sums_aarch64=('6f42762ad69e24a71335401e60f5554f3724bd60f4a03faf0539e1694797d06d')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
