# Maintainer: liberodark

pkgname=cudatext
pkgver=1.19.0.0
pkgrel=1
pkgdesc="Cross-platform text editor"
arch=('x86_64')
url="https://github.com/Alexey-T/CudaText"
license=('MPL')
depends=('xdg-utils')
source_x86_64=("cudatext-1.19.0.0.tar.gz")
source=($pkgname.desktop
        $pkgname.png)
        
package() {
  cd $srcdir
  tar xvf cudatext-1.19.0.0.tar.gz
  cp -r usr $pkgdir
  install -vDm644 $srcdir/$pkgname.desktop $pkgdir/usr/share/applications/$pkgname.desktop
  install -vDm644 $srcdir/$pkgname.png $pkgdir/usr/share/pixmaps/$pkgname.png
}

sha512sums=('1ad4d5e6852045a73d4f5434c1d6819169b2f4babb6bd36a0d72323c6d8836ca59bada7c395a76477facb4776a0d17e610bea2c01c33bbf9957ef0ebda81ffe1'
         'bf6a4409b8462ac6b9c87cbc554cf1837a7b45ec8859b2cdcbb7b263143da9f6236d074d65aca2044dd2475290c9594e6946ccce1c4e58c1cc44dd5ec78ecfc4')
sha512sums_x86_64=('70668d367dd949a14070352b9ece78a78b790a979ec946d84ed235eddcc33ed28ee8ce90dad3d114d7fcf64b07e5ac7daac4650320d54a373558171e50486195')
