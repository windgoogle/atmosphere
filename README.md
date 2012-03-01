## Welcome to the Atmosphere Framework: The Asynchronous WebSocket/Comet Framework
The Atmosphere Framework has both client and server ready to use components. The majority of popular frameworks are either supporting Atmosphere or supported natively by the framework(**).

   Follow us on [Twitter](http://www.twitter.com/atmo_framework) or get the latest news [here](http://jfarcand.wordpress.com)

[Get Started](http://jfarcand.wordpress.com/2010/06/15/using-atmospheres-jquery-plug-in-to-build-applicationsupporting-both-websocket-and-comet/)

[Latest Presentation - Writing highly scalable WebSocket using the Atmosphere Framework](http://www.slideshare.net/jfarcand/writing-highly-scalable-websocket-using-the-atmosphere-framework)

[Which component should I use for my project?](http://jfarcand.wordpress.com/2011/11/07/hitchiker-guide-to-the-atmosphere-framework-using-websocket-long-polling-and-http-streaming/)

Download [White Paper](https://github.com/Atmosphere/atmosphere/blob/master/docs/atmosphere_whitepaper.pdf)

Browse [Javadoc](http://atmosphere.github.com/atmosphere/apidocs/)

To quickly see what Atmosphere can do with WebSocket and Comet, and If you want to play with Redis, Hazelcast, ActiveMQ(JMS) or XMPP(Gmail), [download](https://oss.sonatype.org/content/repositories/releases/org/atmosphere/samples/atmosphere-jquery-pubsub/0.8.6/atmosphere-jquery-pubsub-0.8.6.war) our [JQueryPubSub](https://github.com/Atmosphere/atmosphere/blob/master/samples/jquery-pubsub/src/main/java/org/atmosphere/samples/pubsub/JQueryPubSub.java#L51) sample and uncomments the appropriate technology and rebuild, or drop the atmosphere-{name}.jar under your WEB-INF/lib to enabled it automatically [pom.xml](https://github.com/Atmosphere/atmosphere/blob/master/samples/jquery-pubsub/pom.xml#L2)

To use Atmosphere, add the following dependency:

     <dependency>
         <groupId>org.atmosphere</groupId>
         <artifactId>atmosphere-{atmosphere-module}</artifactId>
         <version>0.8.6</version>
      </dependency>

Where atmosphere-module can be: jersey, runtime, guice, jquery, redis, hazelcast, jms, jgroups or gwt,. Our official release are available from Maven Central.

For SNAPSHOT, you'll have to add the Sonatype repo to your settings in order to be able to access the snapshot builds [Browse the artifact](https://oss.sonatype.org/content/repositories/releases/org/atmosphere/)

Several Samples are available [Download the sample, rename the file without the maven version](https://oss.sonatype.org/content/repositories/snapshots/org/atmosphere/samples/)

Atmosphere 0.8.6 is our official release, and our work in progress version is 0.9, targeted for end of Mid April 2012

If you are interested, subscribe to our [mailing list](http://groups.google.com/group/atmosphere-framework) for more info!  We are on irc.freenode.net under #atmosphere-comet

(**) The list include Jersey, GWT, Wicket, Vaadin, JSF, Scalatra, Play!, Grails and more. All JVM based languages are supported, an massive scalability in natively build in and supported by JGroups, Hazelcast, ActiveMQ, Redis and XMPP based server.

#### Changes logs
[0.8.6](http://is.gd/Pi4ZPo)

[0.8.5](http://is.gd/yVgcaj)

[0.8.4](http://is.gd/Pi4ZPo)

[0.8.3](http://is.gd/znZBKZ)

[0.8.2](http://is.gd/9BesxI)

[0.8.0](https://github.com/Atmosphere/atmosphere/blob/master/CHANGELOGS.txt#L1)