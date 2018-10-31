# LSJ Lexicon (CEX, Markdown)

This repository holds an edition of the LSJ Lexicon formatted as a [CEX](https://cite-architecture.github.io/citedx/CEX-spec-3.0.1/) file, with the lexicon's entries formatted lightly in Markdown.

The original digitization of the public domain text of the LSJ is courtesy of the [Perseus Digital Library](http://www.perseus.tufts.edu/):  Text provided by Perseus Digital Library, with funding from The National Endowment for the Humanities.  Original version available for viewing and download at <http://www.perseus.tufts.edu/>.

The transformation of the Perseus text to an XML edition with composed Unicode was done by [Giuseppe Celano](https://github.com/gcelano/LSJ_GreekUnicode). The files here are a further transformation of Celano's work.

License CC 3.0 BY-NC-SA.

## Contents

- **lsj.cex** A Cite Collection of the entries in the LSJ, with accompanying documentation of *a discoverable text property extension* identifying the `entry` property as a having a primtive type `String` and an extended type `Markdown`. URNs for the LSJ collection are, *e.g.* `urn:cts:hmt:lsj.markdown:n51`.

- **lsj.index** A searchable index as tabulated lines, with `#` as the field delimiter. The fields are:

	1. The ID (object-selector) of an entry
	1. The entry's key (*lemma*) in Unicode, normalized to remove diacritical marks
	1. The entry's key (*lemma*) in Beta Code, normalized to remove diacritical marks
	1. A listing of all Greek words in the entry, in Beta Code without accents

- **files** A directory of individual CEX fragments for each alphabetic division of the LSJ.	

## Corrections

Please submit corrections as issues in GitHub or (ideally) in the form of pull-requests.
