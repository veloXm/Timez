pkgname=timez
pkgver=1.0
pkgrel=1
pkgdesc="A powerful tool for measuring command execution time and resource usage."
arch=('x86_64')
url="https://github.com/veloXm/Timez"
license=('GPL3')
depends=('libstdc++' 'chrono-date')  # Add 'chrono' as dependency if not using timez_s version

package() {
    install -Dm755 timez "$pkgdir/usr/bin/timez"
}