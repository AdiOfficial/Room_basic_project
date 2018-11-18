# Room_basic_project
Learning how to use Room
Notes

Intergation

- adding dependencies in app gradle file
- applying kapt plugin
- using kapt for annotation processor in Kotlin
- making sure that we include jcenter and google repositories int he top level gradle file

Creation of the database

- Create an abstract class that will extend RoomDatabase class
- Specify the version number. Everytime changing the database, change the number of the version. 
Otherwise will get runtime exception.
- Define the entities, after defining the version


