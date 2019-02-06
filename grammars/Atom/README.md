# GuidedTrack language package

Note several features (below) that are not included in the online GT syntax highlighting.

An Atom TextMate grammar for the GuidedTrack language.

One way to set this up on your machine:
* ctrl + shft + p
* Type `language`
* Select `Generate Language Package`
* In the file path given, replace `language-my-language` with `language-guidedtrack`.

Note that you can trigger GuidedTrack syntax highlighting by making the first line of your file follow this format:

  --{program name here}

Includes error highlighting for:
  * illegal spaces

Additional features not found in the online GT syntax highlighter:

* `--notice!` produces error-highlighting for the line that it begins. The purpose is to allow certain comments to be made very visible, such as essential warnings for editors, etc.
* Multi-line block highlighting. This feature has no effect on the actual GT code; it simply allows you to select large blocks of code and make it purple + italic. The idea is that it allows you to make blocks of code visually less distracting without actually having to commit to deleting it or pasting it elsewhere. Begin with `--select` and close with `--endSelect`.
