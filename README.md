## Device Description Repository Simple API
W3C Recommendation 05 December 2008

More Info: [http://www.w3.org/TR/DDR-Simple-API/](http://www.w3.org/TR/DDR-Simple-API/)

This is a mavenized version of the Java representation of the API available at [http://www.w3.org/TR/DDR-Simple-API/DDRSimpleAPI.jar](http://www.w3.org/TR/DDR-Simple-API/DDRSimpleAPI.jar)

Clone and deploy to your own repository or get the build from here:
	<repositories>
		<repository>
			<id>jcenter</id>
			<name>JCenter</name>
			<url>http://jcenter.bintray.com</url>
		</repository>
		<repository>
			<snapshots>
				<enabled>false</enabled>
			</snapshots>
			<id>bintray-release</id>
			<name>libs-release</name>
			<url>http://oss.jfrog.org/artifactory/libs-release</url>
		</repository>
		<repository>
			<snapshots>
				<enabled>true</enabled>
			</snapshots>
			<id>bintray-snapshot</id>
			<name>libs-snapshot</name>
			<url>http://oss.jfrog.org/artifactory/libs-snapshot</url>
		</repository>
	</repositories>