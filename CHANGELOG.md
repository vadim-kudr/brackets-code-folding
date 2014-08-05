#Changelog
##0.2.17
* BUGFIX - fixed issue #78 - region fold causes brackets IDE to freeze when opening certain minified javascript files.

##0.2.16
* Added Italian translation [Denisov21](https://github.com/Denisov21)
* Update to Spanish translation [JJBocanegra](https://github.com/JJBocanegra)

##0.2.15
* Refactored and simplified region fold so it works for any language recognised in codeMirror
* Added custom region folding [keleko34](https://github.com/keleko34)
* Added Spanish translation [QuijoteShin](https://github.com/QuijoteShin)

##0.2.14
* BUGFIX - fixed issue #67 regarding nested fold regions. When a region becomes invalid it is now automatically expanded.

##0.2.13
* BUGFIX - fixed issue #66 where tags (in html/xml) wont fold if the tag is selected

##0.2.12
* BUGFIX - addresses issue #64 where extension crashed when loading preferences

##0.2.11
* Updated package.json to reflect correct minimum brackets version required to run extension

##0.2.10
* BUGFIX - fixed issue #61 where fold state was not correctly persisted
* Simplified the datastructure for storing foldstates in preference file

##0.2.9
* BUGFIX - fixed issue #57

##0.2.8
* Load code folding addons directly from brackets codemirror addon

##0.2.7
* BUGFIX - fixed issue #51 where extension was crashing for edgecode

##0.2.6
* BUGFIX - fixed issue #50
* Upgraded preference persistence to the new Brackets API

##0.2.5
* BUGFIX - fixed issue #49 where collapse all did not include first foldable item

##0.2.4
* Updated package.json to include title
* BUGFIX - fixed issue #44 [Mafio](https://github.com/Mafio)

##0.2.3
* Added internationalisation [Mafio](https://github.com/Mafio)
* Updated keyboard shortcuts

##0.2.2
* Several improvements to indent fold addressing issue #40

##0.2.1
* made indent the default fold addon for text files to address issue #39

##0.2.0
* added support for ruby files

##0.1.8
* Improved latex code folding
* BUGFIX - fixed issue #37 where multiline comments no longer had fold markers

##0.1.7
* Added support for folding latex documents

##0.1.6
* Change base key for shortcuts to letters in order to reduce chances of conflicts with international keyboards addresses issues #34, #35 and #36
##0.1.4
* Added menu items for collapsing and expanding code regions under view menu (addresses issue #33)
* Removed keybinding (ctrl-alt-+) for expanding current code region and left (ctrl-alt-=) as per issue #34

##0.1.3
* Added instruction to README to address issue #34 where keyboard shortcuts might conflict with typing non alphabetic characters on some non-English keyboards.

##0.1.2
* Addresses issue #32 where line fold state is not being correctly persisted after modifying document. Consequently restoring line folds results in wrong folded regions.

##0.1.1
* Addresses issue #30 where code folding is broken after using Ctrl-Alt-- to fold current code region.
* Fixed minor issue where code range opened and closed on the same line is still marked as folded when using shortcuts