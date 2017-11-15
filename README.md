# MARCO27 OSGi HelloWorld Bundle Consumer

## AEM 6.2
- cd ~/dev/myStash/aem62-servers
- mvn cq-start

## mvn clean install
    - open http://localhost:6200/system/console/bundles
## Install/Update..
    - Start Bundle
    - Refresh Package
    - from /Users/marcoguastalli/dev/repository/git/m27-osgi-helloworld-consumer/m27-osgi-components/m27-osgi-components-core/target/m27-osgi-components-core-1.0.0.jar
      - Install/Update

###### http://localhost:6200/system/console/bundles
   - Filter by net.marco27.osgi.components.m27-osgi-components-core

###### http://localhost:6200/system/console/components
   - Search for net.marco27.osgi.consumer.HelloWorldOsgiConsumer

###### http://localhost:6200/system/console/configMgr
    - Search for