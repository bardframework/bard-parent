Bard Framework Parent
===================

[![Build Status][ci-badge]][ci]
[![Maven Central][maven-badge]][maven]
[![License][license-badge]][license]

The Bard Framework Parent POM provides common settings for all Bard's components.

Documentation
-------------

More information can be found on the [Bard Framework homepage][homepage].
Questions related to the usage of Bard Framework Parent should be posted to the [user mailing list][mails].

Where can I get the latest release?
-----------------------------------
You can download it from [download page][download].

Alternatively you can pull it from the central Maven repositories:

```xml
<dependency>
    <groupId>org.bardframework</groupId>
    <artifactId>bard-parent</artifactId>
    <version>27</version>
    <type>pom</type>
    <scope>import</scope>
</dependency>
```

or use it as parent pom:

```xml
<parent>
    <groupId>org.bardframework</groupId>
    <artifactId>bard-parent</artifactId>
    <version>27</version>
</parent>
```

Contributing
------------

We accept Pull Requests via GitHub. The [developer mailing list][mails] is the main channel of communication for
contributors.
There are some guidelines which will make applying PRs easier for us:

+ No spaces! Please use tabs for indentation.
+ Respect the code style.
+ Create minimal diffs - disable on save actions like reformat source code or organize imports. If you feel the source
  code should be reformatted create a separate PR for this change.

You can learn more about contributing via GitHub in our [contribution guidelines](CONTRIBUTING.md).

License
-------
This code is under the [Apache Licence v2][license].

Donations
---------
You like Bard Framework? Then [donate][donate] to support the development.

Additional Resources
--------------------

+ [Bard Framework Homepage][homepage]
+ [Bard Framework Parent Issue Tracker][issues]
+ [Bard Framework Twitter Account][twitter]

[ci]:https://travis-ci.org/bardframework/bard-parent

[ci-badge]:https://travis-ci.org/bardframework/bard-parent.svg

[donate]:https://bardframework.org/donate

[download]:https://repo1.maven.org/maven2/org/bardframework/bard-parent

[homepage]:https://bardframework.org

[issues]:https://github.com/bardframework/bard-parent/issues

[license]:http://www.apache.org/licenses/LICENSE-2.0

[license-badge]:http://img.shields.io/:license-apache-blue.svg

[mails]:https://bardframework.org/mails-list.html

[maven]:https://maven-badges.herokuapp.com/maven-central/org.bardframework/bard-parent

[maven-badge]:https://maven-badges.herokuapp.com/maven-central/org.bardframework/bard-parent/badge.svg

[twitter]:https://twitter.com/BardFramework
