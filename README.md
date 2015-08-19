# JEaDy
Easy Dynamic JPA entities management in OSGi container

# Development environment setup

Common software

1. VirtualBox 5.0.3 x64

   https://www.virtualbox.org/wiki/Downloads

2. PostgreSQL JDBC Drivers

   https://jdbc.postgresql.org

3. Eclipse Mars 4.5
   
   http://www.eclipse.org/downloads/

##Virtual environment based on Fedora Workstation Linux:

1. Fedora Workstation Linux 21 x64

   https://getfedora.org/ru/workstation/

2. WildFly 8.1

   http://wildfly.org/downloads/

3. JDK 7 x64

   http://www.oracle.com/technetwork/java/javase/downloads/index-jsp-138363.html

4. Maven 3

   http://maven.apache.org/download.cgi

   yum install maven

5. PostgreSQL 9.3.6

   http://www.postgresql.org/download/

   yum install postgresql-server

##Virtual environment based on Ubuntu Linux:

1. Ubuntu 15.04 x64

   http://ubuntu.ru/get
   
2. WildFly 9.0.1
   
   http://sukharevd.net/wildfly-8-installation.html

3. JDK

   apt-get install openjdk-8-jdk

4. Maven 3

   apt-get install maven

5. PostgreSQL 9.4.4

   https://www.howtoforge.com/tutorial/postgresql-on-ubuntu-15-04

##Environment configuration

In a terminal do:

1. cd ~

2. mkdir git

3. cd git

4. git clone https://github.com/ArchiMageAlex/JEaDy.git

5. Add $ECLIPSE_HOME to $PATH in  Your bashrc file, for example: export PATH=$PATH:/opt/eclipse

6. Close and Open again terminal

7. eclipse

8. Create local git repository in Eclipse: New - Git - Git Repository - ~/git

9. Import project in Eclipse: Import - Git - Projects from Git - Existing local repository - git - Import as general project - JEaDy

10. core - pom.xml - Run As - Maven build - package - Apply - Run

11. Ready!!!
