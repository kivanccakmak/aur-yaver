# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.71
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

sha256sums_x86_64=('cf989263dee05417d5cec878ad2831773e09ad31b918dc37d10c08a1b727078a')
sha256sums_aarch64=('1a7b7d814006953aeb355218bc9cfa263f6bc4bdb591fd636576df190815cca3')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
