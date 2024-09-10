# Realocate jar app
App to perform package relocation in .jar classes

Steps to change packages:

1 - Add your .jar library in the libs folder

2 - In app>build.gradle, find the updateJar task and write the name of your library and which packages you want to rename.

3 - Only execute the task.

4 - Find the output app.jar in the build/libs folder.

Tip: Rename the .jar file to .zip and extract to verify that the transformation occurred as expected.

If you have any questions, please, open a issue. :)

Thx, Simonassi!
