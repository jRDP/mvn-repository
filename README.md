mvn-repository
==============

This is a maven repository for jRDP releases and dependencies that are nowhere else available.


Usage
-----

`````
<!-- maven repository hosted on github -->
    <repositories>
        <repository>
            <id>com.github.jrdp.mvn-repository</id>
            <url>https://raw.github.com/jRDP/mvn-repository/master</url>
            <!-- use snapshot version -->
            <snapshots>
                <enabled>true</enabled>
                <updatePolicy>always</updatePolicy>
            </snapshots>
        </repository>
    </repositories>
````
