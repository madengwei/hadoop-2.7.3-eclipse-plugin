
hadoop-2.7.3-eclipse-plugin

=======================

eclipse plugin for hadoop 2.7.3
 

How to build
----------------------------------------

  cd {hadoop-2.7.3-eclipse-plugin directory}/src/contrib/eclipse-plugin 

  ant jar -Dversion=2.7.3 -Declipse.home={eclipse directory} -Dhadoop.home={hadoop-2.7.3 directory} -debug

final jar will be generated at directory 

  {hadoop-2.7.3-eclipse-plugin directory}/build/contrib/eclipse-plugin/hadoop-eclipse-plugin-2.7.3.jar

  
release version included
-------------------------------------
 
  release/hadoop-eclipse-plugin-2.7.3.jar

  release/hadoop-eclipse-plugin-2.6.0.jar

  release/hadoop-eclipse-kepler-plugin-2.4.1.jar  
 
  release/hadoop-eclipse-kepler-plugin-2.2.0.jar  
  

How to debug
--------------------------------------
  start eclipse with debug parameter:  

    eclipse -clean -consolelog -debug
    
