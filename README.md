## Estructura .xml de logo para el registro BIMI "certificación BIMI" (verificación de marca para mail) ##
1.- Archivo base imagen formato .svg
2.- Convertir archivo .svg en .xml  
-'Se utilizo para crear la conversión 👉 [bimi record tools](https://easydmarc.com/tools/bimi-record-generator)'
3.- Uso de servidor para resguardo del archivo
4.- Generar Record-BIMI
5._ Crear registro en administrador dns:
tipo: txt
host: _bimi.default (obtenido al generar record-bimi)
valor: _bimi1 (obtenido al generar record-bimi)

