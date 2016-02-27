# TundraYAML.java ❄

A [YAML] parser and emitter that underlies [Tundra], a package of
cool services for [webMethods Integration Server] 7.1 and higher.

## Related

See [Tundra] and [TundraTN], packages of cool services for
[webMethods Integration Server] and [webMethods Trading
Networks] 7.1 and higher respectively.

## Dependencies

[TundraYAML.java] is compiled for Java 1.6, and is dependent on the
following [webMethods Integration Server] [JAR] libraries, which are
required to be included on the project's classpath:

* `wm-isclient.jar`
* `wm-isserver.jar`

It is also dependent on the following open source libraries, which
are required to be included on the project's classpath:

* `snakeyaml-1.15.jar` - http://www.snakeyaml.org
* `Tundra.jar` - https://github.com/Permafrost/Tundra.java

[JUnit] 4 is required for the unit tests in the project. The
following libraries are required to be included on the test
classpath:

* `junit.jar`
* `hamcrest-core.jar`

## Contributions

1. Check out the latest master to make sure the feature hasn't been
   implemented or the bug hasn't been fixed yet.
2. Check out the issue tracker to make sure someone already hasn't
   requested it and/or contributed it.
3. Fork the project.
4. Start a feature/bugfix branch.
5. Commit and push until you are happy with your contribution.
6. Make sure to add tests for it. This is important so it won't
   break in a future version unintentionally.

Please try not to mess with the project version, or history. If you
want your own version please isolate it to its own commit, so it can
be cherry-picked around.

## Copyright

Copyright &copy; 2015 Lachlan Dowding. See the [LICENSE] file for
further details.

[JAR]: <http://en.wikipedia.org/wiki/JAR_(file_format)>
[JUnit]: <http://junit.org/>
[LICENSE]: <https://github.com/Permafrost/TundraYAML.java/blob/master/LICENSE>
[Tundra]: <https://github.com/Permafrost/Tundra>
[TundraTN]: <https://github.com/Permafrost/TundraTN>
[Tundra.java]: <https://github.com/Permafrost/Tundra.java>
[TundraYAML.java]: <https://github.com/Permafrost/TundraYAML.java>
[webMethods Integration Server]: <http://www.softwareag.com/corporate/products/wm/integration/products/ai/overview/default.asp>
[webMethods Trading Networks]: <http://www.softwareag.com/corporate/products/wm/integration/products/b2b/overview/default.asp>
[YAML]: <http://www.yaml.org>
