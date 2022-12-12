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

For Maven:

![Screenshot 2022-12-12 at 19 35 34](https://user-images.githubusercontent.com/114099418/207126917-645526d1-672e-4721-94c7-2427c23f2fed.png)

For Gradle:

![Screenshot 2022-12-12 at 19 41 34](https://user-images.githubusercontent.com/114099418/207127974-0518a6cf-6433-429d-b5b3-d1ca8d1b6083.png)


## Ad 4

Upload spring-petclinic Artifact to Nexus:

Maven:

Using the deploy plugin in pom.xml:

![Screenshot 2022-12-12 at 14 33 55](https://user-images.githubusercontent.com/114099418/207057773-a3eff522-2a01-4adb-a9d3-5838a620b616.png)

To be able to upload arfifact to nexus I also added this in pom.xml:

![Screenshot 2022-12-11 at 21 44 22](https://user-images.githubusercontent.com/114099418/207057966-df50e744-371b-4e97-8568-b3b3646ed4ed.png)

Gradle:

Defining artifact upload as a separate Gradle task in build.gradle:

![Screenshot 2022-12-12 at 19 42 38](https://user-images.githubusercontent.com/114099418/207128127-aa60fcd9-6f72-4123-90a7-194f0740a296.png)

## Ad 5

My arfifact in Nexus:

Maven:

![Screenshot 2022-12-11 at 21 44 06](https://user-images.githubusercontent.com/114099418/207058644-6a0a255c-881b-4517-b4be-1c7ae12d8d21.png)

Gradle:

![Screenshot 2022-12-12 at 19 17 09](https://user-images.githubusercontent.com/114099418/207125602-2c0abc0a-59da-43ce-8dec-13167e3a1b00.png)



