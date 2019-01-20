OddSource OSS Parent
====================

.. image:: https://api.travis-ci.org/OddSource/java-oss-parent.svg
    :target: https://travis-ci.org/OddSource/java-oss-parent

.. image:: https://img.shields.io/github/license/OddSource/java-oss-parent.svg
    :target: https://github.com/OddSource/java-oss-parent/blob/master/LICENSE.txt

.. image:: https://img.shields.io/maven-central/v/io.oddsource.java/oss-parent.svg
    :target: https://search.maven.org/artifact/io.oddsource.java/oss-parent/

.. image:: https://img.shields.io/github/release/OddSource/java-oss-parent/all.svg
    :target: https://github.com/OddSource/java-oss-parent/releases

This project contains the open source parent project POM for all Java projects under the OddSource Code umbrella. All
Java projects sponsored and hosted by OddSource Code must put the following at the top of their ``pom.xml`` files:

.. code-block:: xml

    <parent>
        <groupId>io.oddsource.java</groupId>
        <artifactId>oss-parent</artifactId>
        <version>2.0</version>
    </parent>

Coding Standards
----------------

At OddSource Code, we abide by the following conventions for all Java and XML code:

* Use tabs, not spaces. The exception to this rule is ReStructuredText files, which must use spaces to function
  properly (including code samples in RST files).
* Opening curly braces go on a new line.
* Logic branches always use curly braces.
* Put spaces before all opening parenthesis except annotation parameters and method definitions.
* Put spaces around all operators except unary and reference operators.
* When wrapping method definition arguments and invocation parameters, each argument must go on a separate line,
  indented one tab more than the method definition or invocation (not aligned with the opening parenthesis). The
  closing parenthesis goes on its own line, aligned with the method definition or invocation.
