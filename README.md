InfinityCord
=========

# The current version of this project is deprecated and will soon be updated to a new, properly updated project.

InfinityCord is a fork of the well-known [BungeeCord](https://github.com/SpigotMC/BungeeCord) server teleportation suite.

Waterfall focuses on three main areas:

- **Stability**: Waterfall aims to be stable. We will achieve this through making the code base testable and discouraging practices that lead to proxy lag.
- **Features**: Waterfall aims to include more features than canonical BungeeCord.
- **Scalability**: Waterfall should be able to handle a large number of concurrent players, given a reasonably modern CPU, memory, and good network connection.

## Why fork BungeeCord?

Think of Waterfall as a principles fork.

Waterfall was forked because of the fact that upstream does not accept many contributions that are intended to better the ecosystem. Simply put, Waterfall aims to better
the ecosystem by allowing changes to be exposed to a wider audience more quickly.

Waterfall will still track upstream BungeeCord and merge changes as needed.

## How To (Server Admins)

Download a copy of InfinityCord.jar here: [InfinityCord](https://github.com/HappyRogelio7/InfinityCord/blob/main/InfinityCord-Downloads/Update/Download-jar/InfinityCord.jar)

InfinityCord requires **Java 8** or above, if you use **GeyserMC** use the version of **Java 17**

## How To (Plugin Developers)
------
 * See our API patches [here InfinityCord-Patches](InfinityCord-Patches)
 * See our API patches [here BungeeCord-Patches](BungeeCord-Patches)
 * See our API patches [here FlameCord-Patches](FlameCord-Patches)
 * Waterfall API JavaDocs here: [papermc.io/javadocs](https://papermc.io/javadocs)
 * Maven repository (for `infinitycord-api`):
```xml
<repository>
    <id>com.github.happyrogelio7.infinitycord</id>
    <url></url>
</repository>
```
 * Artifact information:
```xml
<dependency>
    <groupId>com.github.happyrogelio7.infinitycord</groupId>
    <artifactId>infinitycord-api</artifactId>
    <version>1.19-R0.1-SNAPSHOT-003</version>
    <scope>provided</scope>
</dependency>
 ```

---

## How To (Compiling From Source)

To compile InfinityCord, you need JDK17, git, bash, maven.

Clone the repository with the following command:
```bash
$ git clone https://github.com/HappyRogelio7/InfinityCord.git
```

Once downloaded in the git terminal use the following command:

```bash
$ cd InfinityCord/InfinityCord-Code/InfinityCord-Proxy
```

Now inside the directory you execute the following maven command:

```bash
$ mvn clean install
```

Then you will find the compiled in the following folder

```bash
InfinityCord/InfinityCord-Code/InfinityCord-Proxy/bootstrap/target/
```


--


## Join us

* Feel free to open a PR! We accept contributions.
* [Discord](https://discord.gg/3EebYUyeUX)

## Special Thanks To


![IntelliJ IDEA logo](https://resources.jetbrains.com/storage/products/company/brand/logos/IntelliJ_IDEA_icon.png?size=100px)
![IntelliJ IDEA logo](https://resources.jetbrains.com/storage/products/company/brand/logos/IntelliJ_IDEA.png)
![Azul Java logo](https://www.azul.com/wp-content/themes/azul/dist/img/logo.svg)

[IntelliJ IDEA](https://www.jetbrains.com/idea/), Code editor for Java and other programming languages and programs.

[Azul Java](https://www.azul.com/) The world’s largest commercial provider of OpenJDK

