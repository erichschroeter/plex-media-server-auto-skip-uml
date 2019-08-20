This project exists to flush out a potential feature for skipping intro/outro videos on a [Plex Media Server]().

See [the forum feature suggestion](https://forums.plex.tv/t/tv-series-intro-outro-time-span-definition-and-auto-skip/106802) and vote for it.

# How to generate documentation

A few dependencies are required to generate the documentation if you don't want to read plain old [Asciidoc](https://asciidoctor.org/docs/asciidoc-writers-guide/).

- [PlantUML](http://plantuml.com/)
- [Ruby](https://www.ruby-lang.org/en/)
- [asciidoctor](https://asciidoctor.org/docs/asciidoctor-diagram/#installation)
- [asciidoctor-diagram](https://asciidoctor.org/docs/asciidoctor-diagram/)

Assuming everything is on your `PATH`, to generate an all-encompassing _.html_ file:

    asciidoctor -a data-uri -r asciidoctor-diagram docs/design.asciidoc
