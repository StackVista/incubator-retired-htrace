We forked this project in order to be able to bump the shaded jackson-databind that is part of this package to solve security issues.

## Publishing

Publishinglishing can be done by manually uploading jar and pom files. The published artifacts are part of libs_release.
The files requiring uploading:
- /pom.xml as htrace.pom
- /htrace-core4/dependency-reduced-pom.xml as the actual htrace-core4 pom
- /htrace-core4/target/<package>.jar as the main thing
