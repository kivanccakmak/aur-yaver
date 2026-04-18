# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.96.8
pkgrel=1
pkgdesc="Run AI coding agents from your phone — Claude, Codex, Aider, or custom"
arch=('x86_64' 'aarch64')
url="https://yaver.io"
license=('AGPL-3.0-only')
provides=('yaver')

source_x86_64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-amd64.tar.gz")
source_aarch64=("https://github.com/kivanccakmak/yaver.io/releases/download/v${pkgver}/yaver-linux-arm64.tar.gz")

sha256sums_x86_64=('489e5d8a7dde4f0536a746d428a59ce45833389b0429cac64170bde332c8818b')
sha256sums_aarch64=('e9563a10ef8b770bcdf3595caf4d2235f733bb9d8cfe4f035fff8fc9ec68afb3')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
