# GuidedTrack Language Packages

### Syntax highlighters for the [GuidedTrack](https://guidedtrack.com) language.

Currently available for Atom, Sublime, and Visual Studio Code.

The Atom grammar is constructed in Textmate and may work for other editors as well.

**See the readme files for each grammar, respectively, for more information and installation instructions.**

Please open an issue if you have any difficulties with installation or find a bug!

### Notes

Once installed, syntax highlighting should automatically be applied to files with ".guidedtrack" or ".gt" extensions.

This package has a few features not found in the GT web editor:

* Error highlighting for illegal spaces

* Block commenting (enabled for VSCode, and possibly Atom/Sublime).

* `--notice!` produces error-highlighting for the line that it begins. The purpose is to allow certain comments to be made very visible, such as essential warnings for editors, etc.

* Multi-line block highlighting. This feature has no effect on the actual GT code; it simply allows you to select large blocks of code and make it purple + italic. The idea is that it allows you to make blocks of code visually less distracting without actually having to commit to deleting it or pasting it elsewhere. Begin with `--select` and close with `--endSelect`.
