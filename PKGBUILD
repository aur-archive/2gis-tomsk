# Contributor: Nebulosa <nebulosa2007 na yandekse>

pkgname=2gis-tomsk
pkgver=75
pkgrel=1
pkgdesc="Map of Tomsk for 2GIS"
arch=('i686' 'x86_64')
url="http://help.2gis.ru/linux/"
license=('custom')
depends=('2gis')
source=("http://download.2gis.ru/arhives/2GISData_Tomsk-${pkgver}.orig.zip")
md5sums=('47d948ba34d32739477302a801d97377')

build() {

  cd $startdir

# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Tomsk.dgdat "${startdir}/pkg/opt/2gis/tomsk.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Tomsk.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Tomsk.dglf" || return 1

}
