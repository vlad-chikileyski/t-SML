**SML - AngularApp for T-Mobile v1.2.0:**
+ Set @dev mode = false ; 
+ Local structure: images and fonts ; 
+ Changed JSON structure ;
+ *.SVG , *.TTF , *.WOFF , *.EOT;
+ Updated all file structure where was url: //cdn.abee.cloud/resources ; 

**SML - AngularApp for T-Mobile v1.1.1:**
+ Little changes for uploading to server ;

**SML - AngularApp for T-Mobile v1.1.0 :**
+ Create new configuration from production version: *config-standard-nowe-pole.json; 
+ Changed default json configuration in main.bundle.js: "http://s3.eu-central-1.amazonaws.com/abee.execon.pl/p/resources/TMobile/AngularFixer/config-standard-nowe-pole.json'" => "localhost/example/config/config-standard-nowe-pole.json";

**SML - AngularApp for T-Mobile v1.0.0 :**
+ Created file structure;
+ style.css and stylescombined.css from production (t-mobile.pl);
- fonts woff, - we not used this woff fonts, because this fonts exists in:
**http://s.t-mobile.pl/binaries/9049/rwd/assets/font** and **http://cdn.abee.cloud/resources/TMobile/T_SML/fonts**
- deleted *.bundle.js.map;
+ include style in index.html;
+ change default location:  "/"** => "example/[FILE_STRUCTURE]";
@Info: version working in debug configuration for @dev.