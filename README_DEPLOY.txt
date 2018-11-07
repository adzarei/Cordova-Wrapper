To run on cordova:
cordova emulate ios --buildFlag="-UseModernBuildSystem=0"

To deploy on cordova:
ng build --prod --base-href . --output-path {URL TO CORDOVA WRAPPER}/www/


Add to index to capture events on angular proyect.
<script type=”text/javascript” src=”cordova.js”></script>