# DonationForm
Donation Form using Moqui framework
Uses Moqui framework - https://www.moqui.org/framework.html

Download and install Moqui framework

Clone the moqui-framework repository
$ git clone https://github.com/moqui/moqui-framework.git moqui
$ cd moqui
Get desired components, for example PopCommerce and/or HiveMind
$ ./gradlew getComponent -Pcomponent=PopCommerce
$ ./gradlew getComponent -Pcomponent=HiveMind
Alternatively just get the default runtime directory (if you don't want any components)
$ ./gradlew getRuntime
Download ElasticSearch (Linux/Mac/Windows, OSS no-JDK version)
$ ./gradlew downloadElasticSearch
Build then load seed and demo data (the load task depends on the build task)
$ ./gradlew load

Verify that you can see the Moqui modules in your browser - go to http://localhost:8080

cd runtime/component

git clone https://github.com/amahashabde/DonationForm

cd ../.. (go to moqui directory)

Test the DonationForm module by opening up a browser session

java -jar moqui.war

