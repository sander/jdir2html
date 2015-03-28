# How to run JDir2HTML? #

JDir2HTML can be downloaded as a JAR file at our Downloads page. In most cases it will
just run when you double-click file. If it doesn't, here are some instructions:

## Check whether you have the right Java version ##

JDir2HTML has been tested in Sun's Java Runtime Environment version 5.0 (Java 1.5), which
you can [download at java.com](http://www.java.com/download/). Ubuntu users should install
the package `sun-java5-jre` from the commercial repository.

## Open the JAR file with the right application ##

If you have the right Java Runtime Environment installed, but the JAR file is opened with
the wrong application, try right-clicking the file and open it with _Sun Java 5.0 Runtime_.

## If that doesn't work... ##

Run the command `java -jar JDir2HTML-<version>.jar` from the command line (replace
`<version>` with the version number of the file you've downloaded).

If you have multiple Java Runtime Environments installed (for example, also gcj), there
are two options:

  * Replace `java` with the absolute path to your java installation. In Ubuntu, that is:
`/usr/lib/jvm/java-1.5.0-sun/jre/bin/java`
  * Set the default JRE to Sun's. In Ubuntu, you can do that with: `sudo
update-alternatives --set java /usr/lib/jvm/java-1.5.0-sun/jre/bin/java`