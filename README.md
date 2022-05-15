# SkyBlockRPg
Hypixel Public API (Java)
Maven Package

This is a Java implementation of the Hypixel API. For discussing the API, requesting help or suggestions you can use the GitHub Discussions.

Documentation
Hypixel Public API documentation can be found at https://api.hypixel.net/. Java documentation can be found in the code.


Hypixel Maven Repo
<repository>
    <id>Hypixel</id>
    <url>https://repo.hypixel.net/repository/Hypixel/</url>
</repository>
This repo can also be used with Gradle.

repositories {
    maven { url 'https://repo.hypixel.net/repository/Hypixel/' }
}
Transports
We include three built-in options for communicating with the Hypixel API, you can include either of these or even include the core API directly and create your own instance of HypixelHTTPClient.

Apache HttpClient Transport
Unirest Java Transport
Project Reactor Transport (automatic rate-limiting by default)
Dependencies
The Hypixel API Core implementation has the following dependencies:

Google Gson library - 2.9.0
Transports will also have dependencies where required.

Contributing
When contributing changes to the Java API please provide as much detail on the changes and the reasons for them. We will not accept changes that have no meaningful contribution to the project.
