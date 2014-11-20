WildFly8-Modules
================
Modules for JBoss/WildFly 8.x

Modules are deployed under $JBOSS_HOME/modules/system/layers/base/

To use these modules you'll need to copy the correct "jboss-deployment-structure.xml" file under the META-INF on the top directory of the WAR file.

Current modules:
- PrimeFaces 5.1.x [4MB]
-------------------------------------------------
>  - Modules/org/primefaces/main/*
>  - Module Activators/primefaces 5.1/*
-------------------------------------------------

- Richfaces 4.5.x [10MB]
-------------------------------------------------
>  - Modules/org/richfaces/main/*
>  - Module Activators/richfaces 4.5/*
>> Note: for Richfaces to work you will have to enable the Richfaces Resource Servlet on your web.xml
>>       Add this your web.xml:
<pre><code>
      <servlet>
        <servlet-name>Resource Servlet</servlet-name>
        <servlet-class>org.richfaces.webapp.ResourceServlet</servlet-class>
        <load-on-startup>1</load-on-startup>
      </servlet>
      <servlet-mapping>
        <servlet-name>Resource Servlet</servlet-name>
        <url-pattern>/org.richfaces.resources/*</url-pattern>
      </servlet-mapping>
</code></pre>