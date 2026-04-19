# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.96.12
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

sha256sums_x86_64=('2462fc14ac9cd54ffd95c1ab5f43632b97687be7465c14123d444338942c7f92')
sha256sums_aarch64=('930c5b17fdf2238ebe42533a2d326ba7eeae1be42805243b6ea4c27bba215bb5')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
