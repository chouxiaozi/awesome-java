# Awesome Java
java开发相关的牛逼的框架 ide 工具 等等

A curated list of awesome Java frameworks, libraries and software. Inspired by [awesome-python](https://github.com/vinta/awesome-python).

- [Awesome Java](#awesome-java)
    - [Build Tool](#build-tool)
    - [Code Analysis](#code-analysis)
    - [Compiler-compiler](#compiler-compiler)
    - [Continuous Integration](#continuous-integration)
    - [Database](#database)
    - [Date and Time](#date-and-time)
    - [Dependency Injection](#dependency-injection)
    - [Development](#development)
    - [Distributed Applications](#distributed-applications)
    - [Distribution](#distribution)
    - [Document Processing](#document-processing)
    - [GUI](#gui)
    - [Game Development](#game-development)
    - [High Performance](#high-performance)
    - [HTTP](#http)
    - [IDE](#ide)
    - [JVM and JDK](#jvm-and-jdk)
    - [JSON](#json)
    - [Logging](#logging)
    - [Machine Learning](#machine-learning)
    - [Messaging](#messaging)
    - [Miscellaneous](#miscellaneous)
    - [Natural Language Processing](#natural-language-processing)
    - [Networking](#networking)
    - [ORM](#orm)
    - [PDF](#pdf)
    - [Security](#security)
    - [Science](#science)
    - [Server](#server)
    - [Template Engine](#template-engine)
    - [Testing](#testing)
    - [Utility](#utility)
    - [Visualization](#visualization)
    - [Web Crawling](#web-crawling)
    - [Web Frameworks](#web-frameworks)
    - [REST Frameworks](#rest-frameworks)
- [Resources](#resources)
    - [Communities](#communities)
    - [Influential Books](#influential-books)
    - [Podcasts](#podcasts)
    - [Twitter](#twitter)
    - [Websites](#websites)
- [Contributing](#contributing)

## Build Tool

*Tools which handle the buildcycle of an application.*

* [Apache Maven](http://maven.apache.org/) - Declarative build and dependency management which favors convention over configuration. It's preferable to Apache Ant which uses a rather procedural approach and can be rather difficult to maintain.
* [Gradle](http://www.gradle.org/) - Incremental builds which are programmed via Groovy instead of declaring XML. Works well with Maven's dependency management and treats Ant scripts as first-class citizens.

## Code Analysis

*Tools that provide metrics and quality measurements of static code.*

* [SonarQube](http://www.sonarqube.org/) - Inspection tool for code quality. It integrates with several external tools like Gradle, Jira and Jenkins and provides an overview of the metrics over time.
* [FindBugs](http://findbugs.sourceforge.net/) - Static analysis of bytecode to find potential bugs.
* [Metrics](http://metrics.codahale.com/) - Measures the behavior of critical components.

## Compiler-compiler

*Tools that create parsers, interpreters or compilers.*

* [ANTLR](http://www.antlr.org/) - Complex full-featured framework for top-down parsing.
* [JavaCC](https://javacc.java.net/) - More specific and slightly easier to learn. Has syntactic lookahead.

## Continuous Integration

*Tools which support continuously building, testing and releasing applications.*

* [Jenkins](http://jenkins-ci.org/) - Provides server-based services. Often seen as the successor to Hudson, although it is still actively developed.
* [Travis](https://travis-ci.org) - A hosted continuous integration service that integrates with GitHub repositories.
* [Shippable](https://www.shippable.com/) - Based on Docker, it provides also Bitbucket integration.

## Database

*Everything which simplifies interactions with the database.*

* [jOOQ](http://www.jooq.org/) - Generates typesafe code based on SQL schema.
* [Liquibase](http://www.liquibase.org/) - Source control for your database which can be embedded.

## Date and Time

*Libraries related to date and time.*

* [Java 8 SE: Date and Time API](http://www.oracle.com/technetwork/articles/java/jf14-date-time-2125367.html) - Basically, it incorporates Joda-Time.
* [Joda-Time](http://joda-time.sourceforge.net/) - De facto standard date/time-library before Java 8.

## Dependency Injection

*Libraries that help to realize the [Inversion of Control](http://en.wikipedia.org/wiki/Inversion_of_control) paradigm.*

* [Dagger](http://square.github.io/dagger/) - Compile-time injection framework without reflection, mainly for Android.
* [Google Guice](http://de.wikipedia.org/wiki/Google_Guice) - Lightweight but powerful framework.
* [Spring](http://spring.io/) - Only Spring Context is needed for injections.
* [Weld](http://docs.jboss.org/weld/reference/latest/en-US/html_single/) - CDI reference implementation.

## Development

*Integrated environments that augment the process of development at a fundamental level, e.g. classloading.*

* [DCEVM](http://ssw.jku.at/dcevm/) - Modification of the JVM that allows unlimited redefinition of loaded classes at runtime.
* [JRebel](http://zeroturnaround.com/software/jrebel/) - Instantly reloads code and configuration changes without redeploys.

## Distributed Applications

*Libraries and frameworks used to ease writing distributed and fault-tolerant applications.*

* [Akka](http://akka.io) - Toolkit and runtime for building highly concurrent, distributed, and fault tolerant event-driven applications.
* [JGroups](http://www.jgroups.org/) - Toolkit for reliable messaging and creating clusters whose nodes can send messages to each other.
* [Apache ZooKeeper](http://zookeeper.apache.org/) - Coordination service with distributed configuration, synchronization, and naming registry for large distributed systems.

## Distribution

*Tools which handle the distribution of Java applications in native formats.*

* [Launch4j](http://launch4j.sourceforge.net/) - Wraps JARs in lightweight and native Windows executables.
* [packr](https://github.com/libgdx/packr#packr) - Packs your JAR, assets and JVM for native distribution on Windows, Linux and Mac OS X.
* [Bintray](https://bintray.com/) - Version control for your binaries which handles the publishing. Can also be used with Maven or Gradle.

## Document Processing

*Libraries that assist with processing office document formats.*

* [Apache POI](http://poi.apache.org/) - Supports OOXML (e.g XLSX, DOCX, PPTX) as well as OLE2 (e.g. XLS, DOC or PPT).
* [jOpenDocument](http://www.jopendocument.org/) - Processes the OpenDocument format.

## GUI

*Libraries to create modern graphical user interfaces.*

* [JavaFX](http://www.oracle.com/technetwork/java/javase/overview/javafx-overview-2158620.html) - The successor of Swing.
* [Scene Builder](http://www.oracle.com/technetwork/java/javase/downloads/javafxscenebuilder-info-2157684.html) - Visual layout tool for JavaFX applications.

## Game Development

*Frameworks that support the development of games.*

* [jMonkeyEngine](http://jmonkeyengine.org/) - Game engine for modern 3D development.
* [LWJGL](http://lwjgl.org/) - Robust framework that abstracts libraries like OpenGL/CL/AL.
* [libGDX](http://libgdx.badlogicgames.com/) - All-round cross-platform, high-level framework.

## High Performance

*Everything about high performance computation, from collections to specific libraries.*

* [Trove](http://trove.starlight-systems.com/) - Primitive collections.
* [HPPC](http://labs.carrotsearch.com/hppc.html) - Primitive collections.
* [Disruptor](http://lmax-exchange.github.io/disruptor/) - Inter-thread messaging library.
* [Javalution](http://javolution.org/) - Library for real-time and embedded systems.

## HTTP

*Libraries for working with HTTP.*

* [OkHttp](http://square.github.io/okhttp/) - An HTTP+SPDY client for Android and Java applications.

## IDE

*Integrated development environments that try to simplify several aspects of development.*

* [NetBeans](https://netbeans.org/) - Provides integration for several  Java SE and EE features starting with database access and servers to HTML5 and AngularJS.
* [Eclipse](http://www.eclipse.org/) - Does a lot of things in the background. Noteworthy are its large amount of plugins.
* [IntelliJ IDEA](http://www.jetbrains.com/idea/) - Supports a lot of JVM languages and provides good options for Android development. The commercial edition targets the enterprise sector.

## JVM and JDK

*Various implementations of the JVM/JDK.*

* [HotSpot](http://openjdk.java.net/groups/hotspot/) - Official JVM.
* [JDK 9](https://jdk9.java.net/) - Early access releases of JDK 9.
* [OpenJDK](http://openjdk.java.net/) - Open source implementation.

## JSON

*Libraries that simplify JSON processing.*

* [Google Gson](https://code.google.com/p/google-gson/) - Serializes Java objects to JSON and vice versa. Good performance with on-the-fly usage.
* [Jackson](http://wiki.fasterxml.com/JacksonHome) - Similar to GSON but has performance gains if you need to instantiate the library more often.

## Logging

*Libraries that log the behavior of an application.*

* [Apache Log4j 2](http://logging.apache.org/log4j/) - Complete rewrite of the previous version. Now has a powerful plugin and configuration architecture.
* [Logback](http://logback.qos.ch/) - Founded by the same developer as Log4j and proves to be a robust logging library with interesting configuration options via Groovy.
* [SLF4J](http://www.slf4j.org/) - Abstraction layer which is to be used with an implementation.

## Machine Learning

*Tools that provide specific statistical algorithms which allow to learn from data.*

* [Apache Hadoop](http://hadoop.apache.org/) - Open-source software framework for storage and large-scale processing of data-sets on clusters of commodity hardware.
* [Apache Mahout](https://mahout.apache.org/) - Scalable algorithms focused on collaborative filtering, clustering and classification.
* [Apache Spark](http://spark.apache.org/) - Open-source data analytics cluster computing framework.
* [Weka](http://www.cs.waikato.ac.nz/ml/weka/) - Collection of algorithms for data mining tasks ranging from pre-processing to visualization.

## Messaging

*Tools that help sending messages between clients to ensure protocol independency.*

* [Apache ActiveMQ](http://activemq.apache.org/) - Open-source message broker that implements JMS and converts synchronous to asynchronous communication.
* [Apache Kafka](http://kafka.apache.org/) - High-throughput distributed messaging system.
* [JBoss HornetQ](http://hornetq.jboss.org/) - Clear, concise, modular and made to be embedded.

## Miscellaneous

*Everything else.*

* [Jimfs](https://github.com/google/jimfs) - In-memory file system.
* [Lanterna](https://code.google.com/p/lanterna/) - Easy console text GUI library similar to curses.
* [Lombok](http://projectlombok.org/) - Code-generator which aims to reduce the verbosity of Java.
* [RoboVM](http://www.robovm.org/) - Write native iOS apps in Java.

## Natural Language Processing

*Libraries that specialize on processing text.*

* [Apache OpenNLP](https://opennlp.apache.org/) - Toolkit for common tasks like tokenization.
* [LingPipe](http://alias-i.com/lingpipe/) - Toolkit for a variety of tasks ranging from POS tagging to sentiment analysis.
* [Mallet](http://mallet.cs.umass.edu/) - Statistical natural language processing, document classification, clustering, topic modeling, etc.

## Networking

*Libraries for network programming.*

* [Netty](http://netty.io/) - A framework for building high performance network applications.

## ORM

*APIs which handle the persistence of objects.*

* [EclipseLink](https://www.eclipse.org/eclipselink/) - Supports a number of persistence standards: JPA, JAXB, JCA and SDO.
* [Hibernate](http://hibernate.org/orm/) - Robust and widely used with an active community.

## PDF

*Everything that helps with the creation of PDF files.*

* [Apache FOP](http://xmlgraphics.apache.org/fop/) - Creates PDF from XSL-FO.
* [Apache PDFBox](http://pdfbox.apache.org/) - Toolbox for creating and manipulating PDF.
* [JasperReports](http://community.jaspersoft.com/project/jasperreports-library) - Complex reporting engine.
* [DynamicReports](http://dynamicreports.org/) - Simplifies JasperReports.
* [iText](http://itextpdf.com/) - Easy to use PDF library which creates PDF files programmatically but requires a license for commercial purposes.

## Security

*Libraries that handle security, authentication, authorization or session management.*

* [Apache Shiro](http://shiro.apache.org/) - Performs authentication, authorization, cryptography and session management.
* [Keycloak](http://keycloak.jboss.org/) - Integrated SSO and IDM for browser apps and RESTful web services. Currently in beta but looks very promising.
* [PicketLink](http://picketlink.org/) - PicketLink is an umbrella project for security and identity management for Java applications.
* [Spring Security](http://projects.spring.io/spring-security/) - Focuses on authentication/authorization and protects against several attack vectors.

## Science

*Libraries for scientific computing and analysis.*

* [JScience](http://www.jscience.org/) - Comprehensive framework of science related libraries.
* [JTransforms](https://sites.google.com/site/piotrwendykier/software/jtransforms) - Multithread FFT library.
* [Parallel Colt](https://sites.google.com/site/piotrwendykier/software/parallelcolt) - Multithread high performance scientific and technical computing.
* [SCaVis](http://jwork.org/scavis/) - Environment for scientific computation, data analysis and data visualization.

## Server

*Servers which are specifically used to deploy applications.*

* [GlassFish](https://glassfish.java.net/) - Open source reference implementation for Java EE sponsored by Oracle.
* [WildFly](http://www.wildfly.org/) - Formerly known as JBoss and developed by Red Hat with extensive Java EE support.
* [Jetty](http://www.eclipse.org/jetty/) - Lightweight, small server, often embedded in projects.
* [Apache Tomcat](http://tomcat.apache.org/) - Robust all-round server for Servlet and JSP.
* [Apache TomEE](http://tomee.apache.org/) - Tomcat plus Java EE.

## Template Engine

*Tools which substitute expressions in a template.*

* [Apache Velocity](http://velocity.apache.org/) - Templates for HTML pages, emails or source code generation in general.
* [FreeMarker](http://freemarker.org/) - General templating engine without any heavyweight or opinionated dependencies.
* [JavaServer Pages](https://jsp.java.net/) - Aged templating for websites with custom tag libraries.
* [Thymeleaf](http://www.thymeleaf.org/) - Aims to be a substitute for JSP and works for XML files in general.

## Testing

*Tools that test from object to interface level including performance and other benchmarks.*

* [AssertJ](http://joel-costigliola.github.io/assertj/) - Fluent assertions.
* [Apache JMeter](http://jmeter.apache.org/) - Functional testing and performance measurements.
* [Arquillian](http://arquillian.org/) - Integration and functional testing platform with integration of Java EE containers.
* [Calipher](https://code.google.com/p/caliper/) - Microbenchmarking framework.
* [FEST](https://code.google.com/p/fest/) - Collection of testing libraries.
* [Hamcrest](http://hamcrest.org/JavaHamcrest/) - Framework for writing declarative assertion matchers.
* [JMH](http://openjdk.java.net/projects/code-tools/jmh/) - Microbenchmarking.
* [JUnit](http://junit.org/) - Testing framework.
* [Mockito](http://code.google.com/p/mockito/) - Creation of test double objects in automated unit tests for the purpose of TDD or BDD.
* [Selenium](http://docs.seleniumhq.org/) - Portable software testing framework for web applications.
* [TestNG](http://testng.org/) - Testing framework.
* [VisualVM](http://visualvm.java.net/) - Visual interface for viewing detailed information about Java applications while they are running on a JVM.

## Utility

*Libraries which provide unspecific functionality, e.g. optimized datastructures.*

* [Apache Commons](http://commons.apache.org/) - Provides different general purpose functions like configuration, validation, collections, file upload or XML processing.
* [Google Guava](http://code.google.com/p/guava-libraries/) - Collections, caching, primitives support, concurrency libraries, common annotations, string processing, I/O, and so forth.
* [javatuples](http://www.javatuples.org/) - Does what it says, although the concept of tuples in general is debatable.

## Visualization

*Libraries or frameworks which allow you to visualize data.*

* [Processing](https://www.processing.org/) - A project deeply rooted in visual art which allows you to program the visualization of data.

## Web Crawling

*Libraries that analyze the content of websites.*

* [Apache Nutch](http://nutch.apache.org/) - Highly extensible, highly scalable Web crawler for production environment.
* [Crawler4j](https://code.google.com/p/crawler4j/) - Simple lightweight alternative.
* [jsoup](http://jsoup.org/) - Scrapes, parses, manipulates and cleans HTML.

## Web Frameworks

*Frameworks that handle the communication between the layers of an web application.*

* [Apache Tapestry](http://tapestry.apache.org/) - Component oriented framework for creating dynamic, robust, highly scalable web applications in Java.
* [Spring](http://projects.spring.io/spring-framework/) - Aims to simplify the development with Java EE and provides packages for dependency injection and aspect-oriented programming.
* [Spring Boot](http://projects.spring.io/spring-boot/) - Microframework which simplifies the development of new Spring applications.
* [Vaadin](https://vaadin.com/) - Event-driven framework build on top of GWT. Uses server-side architecture with Ajax on the client-side.
* [Google Web Toolkit](http://www.gwtproject.org/) - Toolbox which includes a Java-to-JavaScript compiler for client-side code, XML parser, API for RPC, JUnit integration, internationalization support and widgets for the GUI.
* [Grails](https://grails.org/) - Groovy framework with the aim to provide a highly productive environment by favoring convention over configuration, no XML and support for mixins.
* [Apache Wicket](http://wicket.apache.org/) - Component-based web application framework similar to Tapestry with a stateful GUI.
* [Play](http://www.playframework.com/) - Uses convention over configuration, hot code reloading and display of errors in the browser.
* [PrimeFaces](http://primefaces.org/) - JSF framework which has a free and a commercial version with support. Provides several frontend components.
* [Spark](http://www.sparkjava.com/why.html) - Unique framework which focuses not on complex MVC patterns but on rapid development.

## REST Frameworks

*Frameworks specifically for creating RESTful services.*

* [Dropwizard](https://dropwizard.github.io/dropwizard/) - Opinionated framework for setting up modern web applications, includes Jetty, Jackson, Jersey and Metrics.
* [Jersey](https://jersey.java.net/) - JAX-RS reference implementation.
* [RESTEasy](http://resteasy.jboss.org/) - Fully certified and portable implementation of the JAX-RS specification.
* [RESTX](http://restx.io/) - A lightweight REST framework with emphasis on modularity, speed and dev-friendly features (light specs compiled to unit tests and documentation, authentication needed by default, ...)
* [Retrofit](http://square.github.io/retrofit/) - A type-safe REST client for Java.

# Resources

## Communities

*Active discussions.*

* [r/java](http://www.reddit.com/r/java) - Subreddit for the Java community.
* [stackoverflow](http://stackoverflow.com/questions/tagged/java) - Question/answer platform.

## Influential Books

*Books about Java that had a high impact and are still worth reading.*

* [Effective Java (2nd Edition)](http://www.amazon.com/Effective-Java-Edition-Joshua-Bloch/dp/0321356683)
* [Java Concurrency in Practice](http://www.amazon.com/Java-Concurrency-Practice-Brian-Goetz/dp/0321349601)
* [Thinking in Java](http://www.amazon.com/Thinking-Java-Edition-Bruce-Eckel/dp/0131872486)

## Podcasts

*Something to listen to while programming.*

* [The Java Posse](http://www.javaposse.com/)

## Twitter

*People to follow.*

* [Adam Bien](https://twitter.com/AdamBien/)
* [Antonio Goncalves](https://twitter.com/agoncal/)
* [Arun Gupta](https://twitter.com/arungupta/)
* [Ed Burns](https://twitter.com/edburns)
* [Java](https://twitter.com/java/)
* [Java EE](https://twitter.com/Java_EE/)
* [Java.net](https://twitter.com/javanetbuzz/)
* [Java Magazine](https://twitter.com/Oraclejavamag)
* [Mark Reinhold](https://twitter.com/mreinhold)
* [OpenJDK](https://twitter.com/OpenJDK)
* [Pete Muir](https://twitter.com/plmuir/)
* [Reza Rahman](https://twitter.com/reza_rahman)
* [Simon Maple](https://twitter.com/sjmaple)
* [Tim Boudreau](https://twitter.com/kablosna)

## Websites

*Sites to read.*

* [Java.net](http://java.net/)
* [JavaWorld](http://www.javaworld.com/)
* [Javalobby](http://java.dzone.com/)
* [RebelLabs](http://zeroturnaround.com/rebellabs/)

# Contributing

Contributions are very welcome!

Please have a look at [CONTRIBUTING](https://github.com/akullpp/awesome-java/blob/master/CONTRIBUTING.md) for guidelines.

Topics which have no libraries as of yet are located in [TOPICS](https://github.com/akullpp/awesome-java/blob/master/TOPICS.md).
