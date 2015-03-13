#COMANDOS UTILIZADOS PARA CRIAR O PROJETO

cordova create barcode br.com.cachina.bar "BarCod"
cordova plugin add https://github.com/wildabeast/BarcodeScanner.git
cordova platform add android
cordova platform add ios

#Executar
cordova run android
cordova run ios