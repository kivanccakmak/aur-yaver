# Maintainer: Yaver <packages@yaver.io>
pkgname=yaver
pkgver=1.99.18
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

sha256sums_x86_64=('1d04ad1944c8a19b2251b8fbe5245c289a95e5bdfec53710016bf81d719428e7')
sha256sums_aarch64=('814e900eb8078e9b9f8883c72ff471d5557660df8a1496ed3a429d15ba2376df')

package() {
    install -Dm755 yaver "$pkgdir/usr/bin/yaver"
}
