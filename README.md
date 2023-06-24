### apprd-parent-pom

### From workspace folder

    mvn install:install-file -Dfile=apprd-parent-pom/pom.xml -DpomFile=apprd-parent-pom/pom.xml

### go to parent-pom folder

    mvn deploy -f pom.xml -Pdeploy-to-exchange-v3
