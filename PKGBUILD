# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>
     
pkgname=2gis-tomsk
pkgver=89
pkgrel=1
pkgdesc="Map of Tomsk for 2GIS, May 2012"
arch=('i686' 'x86_64')
url="http://tomsk.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.6.0.2')
source=("http://download.2gis.ru/arhives/2GISData_Tomsk-${pkgver}.orig.zip")
md5sums=('6950855cc68fe2cbad5ddfebc1f76505')
     
build() {
     
   cd $startdir
     
# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Tomsk.dgdat "${startdir}/pkg/opt/2gis/tomsk.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Tomsk.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Tomsk.dglf" || return 1
     
}

