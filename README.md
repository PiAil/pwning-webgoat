**Pré-requis**

1. Installer le [JDK Java](https://www.oracle.com/technetwork/java/javase/downloads/jdk11-downloads-5066655.html).
2. Installer [Maven](https://maven.apache.org/download.cgi).
3. Créer la variable d'environnement **JAVA_HOME** pointant sur le JDK (par exemple **C:\Program Files\Java\jdk-12.0.1**).

**Installation**

Suivre les consignes du github https://github.com/WebGoat/WebGoat

	git clone https://github.com/WebGoat/WebGoat.git
    cd WebGoat
	mvn clean install
	
**Lancement**

    cd WebGoat
	mvn -pl webgoat-server spring-boot:run
	mvn -pl webwolf spring-boot:run

**Moodle**

Le code HTML de cette page, et du Wiki de correction sont sur ce dépot.

Pour modifier une page sur Moodle avec du code HTML, une fois dans la fenêtre d'édition, cliquer sur **Montrer/cacher les boutons avancés** puis sur **HTML**

**Remarque diverses**:

Certaines leçons sont buggées (certaines uniquement graphiquement, d'autres au niveau de la logique), un ticket est ouvert sur [Github](https://github.com/WebGoat/WebGoat/issues/619).

Ne pas hésiter à compléter mon poste si jamais vous en trouvez d'autres. 

Les personnes en charge du project ont l'air *assez* réactives.

J'espère que les bugs seront résolus rapidement.

Je trouve l'aspect pédagogique de la VM assez unique/bien fait pour continuer avec.
