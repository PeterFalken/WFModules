WildFly-Modules
================
Modules for WildFly using JDK 8+

Modules are deployed under $JBOSS_HOME/modules/system/layers/base/

To use these modules you'll need create/update "jboss-deployment-structure.xml" file under the META-INF on the top directory of the WAR file.

**Current modules:

- PostgreSQL [~700KB]
-------------------------------------------------
> - Modules/org/postgresql/main/*
> - Module Activators/postgres/*

- PrimeFaces [~4MB]
-------------------------------------------------
> - Modules/org/primefaces/main/*
> - Module Activators/primefaces/*
