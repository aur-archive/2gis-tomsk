# Contributor: stanislaw <i@archuser.pp.ru>

pkgname=2gis-tomsk
pkgver=74
pkgrel=1
pkgdesc="Map of Tomsk for 2GIS"
arch=('i686' 'x86_64')
url="http://help.2gis.ru/linux/"
license=('custom')
depends=('2gis')
source=("http://download.2gis.ru/arhives/2GISData_Tomsk-${pkgver}.orig.zip")
md5sums=('93f1f80ec4d9af2de033528c2ff6b0f8')

build() {

  cd $startdir

# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Tomsk.dgdat "${startdir}/pkg/opt/2gis/tomsk.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Tomsk.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Tomsk.dglf" || return 1

}
