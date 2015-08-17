# Contributor: Florijan Hamzic <florijanh@gmail.com>

_pkgname="python-cairocffi"
pkgname="${_pkgname}"
pkgver=0.6
pkgrel=1
pkgdesc="cairocffi is a CFFI-based drop-in replacement for Pycairo, a set of Python bindings and object-oriented API for cairo."
arch=('any')
url="http://pythonhosted.org/cairocffi/"
license=('BSD')
depends=('python>=3.1')
provides=("${_pkgname}")
conflicts=("${_pkgname}")
source=(https://github.com/SimonSapin/cairocffi/archive/v${pkgver}.tar.gz)
md5sums=('4748b086d414e8e6b43b40e22b738f2c')

package(){
  cd "${srcdir}/cairocffi-${pkgver}"
   python setup.py install --root="$pkgdir" --prefix=/usr
}

