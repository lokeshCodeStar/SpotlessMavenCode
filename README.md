# SpotlessMavenCode
SpotlessMavenCode

Adding plugin to pom.xml
======================================================================================================================================================
                <groupId>com.diffplug.spotless</groupId>
                <artifactId>spotless-maven-plugin</artifactId>
                <version>2.27.2</version>
                
                 <plugin>
                <groupId>com.diffplug.spotless</groupId>
                <artifactId>spotless-maven-plugin</artifactId>
                <version>2.27.2</version>
                <configuration>
                    <java>
                        <includes>
                            <include>src/main/java/**/*.java</include>
                            <include>src/test/java/**/*.java</include>
                        </includes>
                        <googleJavaFormat>
                            <version>1.15.0</version>
                            <style>GOOGLE</style>
                        </googleJavaFormat>
                    </java>
                </configuration>
            </plugin>
============================================================================================================================================================
Use the apply formatting 
============================================================================================================================================================**

mvn spotless:apply

============================================================================================================================================================


