Open Terminal ( Ctrl + Alt + T ).

Remove the OpenJDK from the system, if you have it already installed.

#$ sudo apt-get remove --purge openjdk*

Add repository.

#$ sudo add-apt-repository -y ppa:webupd8team/java

Run the following command to pull the packages information from the newly added repository.

#$ sudo apt-get update

Issue the following command to install Java JDK 1.8.

#$ sudo apt-get -y install oracle-java8-installer

#$ sudo apt install oracle-java8-set-default

While installing, you will be required to accept the Oracle binary licenses.

Verify Java version

#$ java -version

Done.
