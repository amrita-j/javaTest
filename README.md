# javaTest
A project to test EclipseLink merge option issue.
Issue faced : On setting a referenced object on prepersist method and using entityManager.merge command on the entity, this set object is being persisted as null.

Steps to be followed to run the project :
1> Run the DB create scripts in MySql.
2> Run the main class ELTestMain.
