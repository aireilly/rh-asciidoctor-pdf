# Sample asciidoctor-based PDF with Red Hat theme

To install:

	gem install rghost

	gem install text-hyphen

	gem install rouge

	gem install asciidoctor-pdf

Check the install:

	asciidoctor-pdf -v

To build PDF, open a cmd prompt and run: 

	asciidoctor-pdf -a pdf-themesdir=themes -a pdf-theme=redhat master.adoc

## TODO

* Create a container with all this configured!