# Nexus

1. Install Nexus
2. [Configure admin user](#ad-2)
3. Configure proxy repo.
    
    *For Maven: Create setting.xml, maven should use it as mirror
    
    *For Gradle: Define proxy repo in gradle settings
    
4.  [Upload spring-petclinic Artifact to Nexus](#ad-4)
    
    *For Maven: Use the deploy plugin in your pom.xml. You should be able to your upload artifacts to Nexus from Maven
    
    *For Gradle: Define artifact upload as a separate Gradle task
   
5. [Search artifacts in Nexus](#ad-5)



## Ad 2

Configuring admin user:

![Screenshot 2022-12-11 at 20 13 47](https://user-images.githubusercontent.com/114099418/207045592-f8a1419c-6f9c-47f7-a71e-5ddab32a2814.png)

## Ad 4

Upload spring-petclinic Artifact to Nexus:

Maven:

Using the deploy plugin in pom.xml:

![Screenshot 2022-12-12 at 14 33 55](https://user-images.githubusercontent.com/114099418/207057773-a3eff522-2a01-4adb-a9d3-5838a620b616.png)

To be able to upload arfifact to nexus I also added this in pom.xml:

![Screenshot 2022-12-11 at 21 44 22](https://user-images.githubusercontent.com/114099418/207057966-df50e744-371b-4e97-8568-b3b3646ed4ed.png)

Gradle:

![Screenshot 2022-12-12 at 19 16 22](https://user-images.githubusercontent.com/114099418/207125517-b1af5664-b0da-46e7-a9ba-545bb4309835.png)


## Ad 5

My arfifact in Nexus:

Maven:

![Screenshot 2022-12-11 at 21 44 06](https://user-images.githubusercontent.com/114099418/207058644-6a0a255c-881b-4517-b4be-1c7ae12d8d21.png)

Gradle:

![Screenshot 2022-12-12 at 19 17 09](https://user-images.githubusercontent.com/114099418/207125602-2c0abc0a-59da-43ce-8dec-13167e3a1b00.png)



