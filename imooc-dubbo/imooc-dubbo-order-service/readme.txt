采用了tomcat插件加载war的方式启动provider

<packaging>war</packaging>

<plugin>
				<groupId>org.apache.tomcat.maven</groupId>
				<artifactId>tomcat7-maven-plugin</artifactId>
				<configuration>
					<port>8082</port>
					<path>/</path>
					<useBodyEncodingForURI>true</useBodyEncodingForURI>
					<uriEncoding>UTF-8</uriEncoding>
				</configuration>
			</plugin>