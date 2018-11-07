To run on cordova:
cordova emulate ios --buildFlag="-UseModernBuildSystem=0"

To deploy on cordova:
ng build --prod --base-href . --output-path {URL TO CORDOVA WRAPPER}/www/
