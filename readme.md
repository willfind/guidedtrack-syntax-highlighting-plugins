# GuidedTrack Language Packages

### Syntax highlighters for the GuidedTrack language.

Currently available for Atom, Sublime, and Visual Studio Code. 

The Atom grammar is constructed in Textmate, and may work for other editors as well.

**See the readme files for each grammar, respectively, for more information and installation instructions.**

Please open an issue if you have any difficulties with installation, or find a bug.

### Notes

You can trigger GuidedTrack syntax highlighting by making the first line of your file follow this format:

  `--{program name here}`

A few features not found in the GT web editor: 

* Error highlighting for illegal spaces

* Block commenting (enabled for VSCode, and possibly Atom/Sublime).

* `--notice!` produces error-highlighting for the line that it begins. The purpose is to allow certain comments to be made very visible, such as essential warnings for editors, etc.

* Multi-line block highlighting. This feature has no effect on the actual GT code; it simply allows you to select large blocks of code and make it purple + italic. The idea is that it allows you to make blocks of code visually less distracting without actually having to commit to deleting it or pasting it elsewhere. Begin with `--select` and close with `--endSelect`.
