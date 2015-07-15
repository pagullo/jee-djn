# jee-djn is part of DirectJNgine #
The JEE/CDI connector is now part of DirectJNgine, as a separate JAR file. Please, visit the [DirectJNgine](https://code.google.com/p/directjngine/) page for further info.

Go to the [downloads](http://www.softwarementors.com/directjngine/downloads/) page to get the compiled library and the source code.

# Introduction #
JEE-DJN is a connector for [DirectJNgine](https://code.google.com/p/directjngine/) that allows using JEE/CDI beans as [ExtJs'](http://www.sencha.com/products/extjs/) Direct actions.

you will be able to manage your action lifecycles with JEE/CDI, reference other beans from them, etc.

## Configuring the JEE DirectJNgine connector ##

Using the JEE connector is as easy as including the corresponding _directjngine-jee-connector-XXX.jar_ in your classpath and then configuring your _web.xml_ as follows:

```
  <init-param>
    <param-name>dispatcherClass</param-name>
    <!-- JEE/CDI connector -->
    <param-value>com.softwarementors.djn.cdi.dispatcher.CdiDispatcher</param-value>
  </init-param>
```

Now, just configure your action classes as a CDI bean, and voilá!

## Download ##

In order to make things easier, we are making the different DirectJNgine connector JARs available in the DirectJNgine [downloads](http://www.softwarementors.com/directjngine/downloads/) section, so that you can find all connectors in just one place.

For more information about DirectJNgine, go to its [main site](https://code.google.com/p/directjngine/).