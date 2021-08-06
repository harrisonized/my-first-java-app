# follow this tutorial: http://tutorials.jenkov.com/java/your-first-java-app.html
# see: https://ymichael.com/2014/09/24/build-and-run-eclipse-java-projects-on-the-command-line.html

cd eclipse-workspace/my-first-java-app

# compile
# javac -d bin/ -cp src /path/to/java/file
javac -d bin/ -cp src $PWD/src/myfirstapp/MyJavaApp.java  # need full path

# run
java -cp bin myfirstapp.MyJavaApp