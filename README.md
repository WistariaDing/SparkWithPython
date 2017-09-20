# SparkWithPython
Here are some cases about Spark Python API, pyspark.

### How to install Spark on Window 10?

#### 1. Install Java 8
    Download Java 8 or later version from the official website.Then set system environment variabls

        variable: JAVA_HOME
        value:    C:\Program Files\Java\jdk1.8.0_144 (Java Installation folder)
        variable: Path
        value:    %JAVA_HOME%\bin

    Run command window, input java -version, check if it is installed successfully.
 
#### 2. Install Scala:
    Download Scala from the website and install. Then set system environment variables.
        
        variable: Path
        value:    C:\Program Files (x86)\scala\bin (Scala Installation folder)
        
    Run command window, input scala, check if the result is the version number of scala.

#### 3. Install Spark:
    Download spark from  https://spark.apache.org/downloads.html  into a certain folder and extract.For example, D:\Spark\spark-2.2.0-bin-hadoop2.7. Then set system environmental variables:
        variable: Path
        value:    D:\Spark\spark-2.2.0-bin-hadoop2.7\bin
    Run command window, cd to the folder 'D:\Spark\spark-2.2.0-bin-hadoop2.7\bin', then input spark-shell, check.
  
