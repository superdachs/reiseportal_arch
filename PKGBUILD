pkgname=reiseportal
pkgver=0.1
pkgrel=1
pkgdesc='Reiseportal django app'
arch=('x86_64')
url='https://github.com/superdachs/reiseportal'
license=('GPLv3')
depends=('python' 'python-django' 'nginx' 'python-pillow' 'uwsgi' 'postgresql')
source=('https://github.com/superdachs/reiseportal2/archive/master.zip')
md5sums=('4f6adca37a90720e24ca9d705b320f2b')

build() {
    echo "no build required"
}

package() {
    cd reiseportal2-master
    echo $pkgdir
    install -dm755 $pkgdir/usr/lib/$pkgname
    cp -r reiseportal/* $pkgdir/usr/lib/$pkgname
}