# Code Style

Record of code style rules I aspire to follow, and configs to help me do so.

## Java

I follow the [Google Java style
guide](https://google.github.io/styleguide/javaguide.html). Google distribute
an XML file,
[eclipse-java-google-style.xml](https://github.com/google/styleguide/blob/gh-pages/eclipse-java-google-style.xml),
that specifies an Eclipse formatter to enforce the style guide rules under
[CC-By 3.0](https://creativecommons.org/licenses/by/3.0/). The Eclipse
formatter specified by
[`eclipse-java-lanecodes-style.xml`](./java/eclipse-java-lanecodes-style.xml)
builds on the Google Java style formatter by including the changes detailed
below

### Improved formatting of code using fluent interfaces

The Google Java style formatter formatter reflows client code that uses a
fluent interface so that multiple method calls appear on the same
line. `eclipse-java-lanecodes-style.xml` produces a formatter which preserves
formatting of code using a fluent interface by allowing one method per
line. See discussion [here](https://stackoverflow.com/questions/4172937) for
details of how this is achieved in Eclipse. Note that this is compatible with
the Google Style Guide itself which
[permits](https://google.github.io/styleguide/javaguide.html#s4.5-line-wrapping)
line wrapping for improved code clarity at programmer discretion.

## License

All the work in this repository is licensed under the [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/">
	<img alt="Creative Commons License"
	     style="border-width:0"
		 src="https://i.creativecommons.org/l/by/4.0/88x31.png"/>
</a>
