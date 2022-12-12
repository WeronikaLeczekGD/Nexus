# Nexus

1. Install Nexus
2. [Configure admin user](#ad-2)
3. [Configure proxy repo.](#ad-3)
    
    *For Maven: Create setting.xml, maven should use it as mirror
    
    *For Gradle: Define proxy repo in gradle settings
    
4.  [Upload spring-petclinic Artifact to Nexus](#ad-4)
    
    *For Maven: Use the deploy plugin in your pom.xml. You should be able to your upload artifacts to Nexus from Maven
    
    *For Gradle: Define artifact upload as a separate Gradle task
   
5. [Search artifacts in Nexus](#ad-5)



## Ad 2

Configuring admin user:

![Screenshot 2022-12-11 at 20 13 47](https://user-images.githubusercontent.com/114099418/207045592-f8a1419c-6f9c-47f7-a71e-5ddab32a2814.png)

## Ad 3 

Configuring proxy repo:

Maven:

1. Creating repos:

![Screenshot 2022-12-11 at 20 21 24](https://user-images.githubusercontent.com/114099418/207046271-5014402f-7d03-48f3-9698-dc8eba3cf927.png)

![Screenshot 2022-12-11 at 20 56 15](https://user-images.githubusercontent.com/114099418/207046449-1c8d65ef-53c9-4a81-b08c-5335a3e1e32b.png)

2. Changing in setting.xml:

![Screenshot 2022-12-11 at 21 45 37](https://user-images.githubusercontent.com/114099418/207046935-0fdc8e5e-7918-4119-8f23-5fcb26653151.png)

![Screenshot 2022-12-11 at 21 46 11](https://user-images.githubusercontent.com/114099418/207047098-cdf979b7-1684-40c9-ae95-a53c6ae9d62e.png)

![Screenshot 2022-12-12 at 13 41 18](https://user-images.githubusercontent.com/114099418/207047940-a690dbc4-936d-4235-b505-077ccabe7b79.png)

Gradle:


## Ad 4

Upload spring-petclinic Artifact to Nexus:

Maven:

Using the deploy plugin in pom.xml:

![Screenshot 2022-12-12 at 14 33 55](https://user-images.githubusercontent.com/114099418/207057773-a3eff522-2a01-4adb-a9d3-5838a620b616.png)

To be able to upload arfifact to nexus I also added this in pom.xml:

![Screenshot 2022-12-11 at 21 44 22](https://user-images.githubusercontent.com/114099418/207057966-df50e744-371b-4e97-8568-b3b3646ed4ed.png)

## Ad 5

My arfifact in Nexus:

![Screenshot 2022-12-11 at 21 44 06](https://user-images.githubusercontent.com/114099418/207058644-6a0a255c-881b-4517-b4be-1c7ae12d8d21.png)


