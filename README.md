WildFly8-Modules
================
Modules for JBoss/WildFly 8.x

Modules are deployed under JBOSS_HOME/modules/system/layers/base/
To use these modules you'll need to copy the correct "jboss-deployment-structure.xml" file under META-INF on the toop directory of the WAR file.

Current modules:
- PrimeFaces 5.1 (Shaves ~ 4 MB of your WAR files)
  - Modules/org/primefaces/main/*
  - Module Activators/primefaces 5.1/*
