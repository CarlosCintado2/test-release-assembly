# test-assembly

### Descarrega els fitxers del Nexus i fa un zip empaquetant els moduls necesaris d'una release.
### S'ha de ficar les versions del moduls al fitxer version.properties

### Per fer la release i pujar al Nexus

mvn release:clean release:prepare release:perform -DreleaseVersion=0.3 -DdevelopmentVersion=0.3-SNAPSHOT
--

Prova


