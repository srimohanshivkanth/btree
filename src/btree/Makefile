JAR=btreelib.jar

#this is the name of the given project folder
ASSIGNMENT=btree_project_F18

#change the ASSIGN path to the path where you have downloaded on your computer
ASSIGN=/home/s/ss/ssg8948

#change the JDKPATH if you are not using omega.uta.edu
JDKPATH = /opt/jdk1.6.0_20
LIBPATH = $(ASSIGN)/$(ASSIGNMENT)/lib/$(JAR)
CLASSPATH = $(LIBPATH):$(ASSIGN)/$(ASSIGNMENT)/src
BINPATH = $(JDKPATH)/bin
JAVAC = $(JDKPATH)/bin/javac -classpath $(CLASSPATH)
JAVA  = $(JDKPATH)/bin/java  -classpath $(CLASSPATH)

PROGS = together

all: $(PROGS)

together:*.java
	$(JAVAC) *.java

clean:
	\rm -f *.class *~ \#* core
