# common-parent
parent project that serves many subprojects and has the common dependencies used by all of them, if needed to add any new dependency, talk to other collaborators about the intent.
### Version
Latest release: **1.0.0-RELEASE**
* Created initial base structure.

### Pre requisites 
* JAVA 8
* Maven
* Ide Eclipse

### Start configuration <br>
######Program Arguments <br>
* Run Configuration > Arguments > Program arguments: <br>
Add 
--spring.profiles.active=dev --eureka.instance.hostname=10.174.1.48
--spring.cloud.config.uri=https://comum-config-git.interno.srmasset.com:443

#### Installation <br>
* Dependencies download: right click on project > Maven > Update Project
* The project uses another parent to inject many of its dependencies, its the com.trust.parent or common-parent, remember if any error error occurred during the compilation or building of the project, you will have to download common-parent also.