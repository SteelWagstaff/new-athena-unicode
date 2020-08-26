# new-athena-unicode
Latest releases of New Athena Unicode, a freeware multilingual font distributed by the Society for Classical Studies

## ABOUT NEW ATHENA UNICODE v. 5.004 (November 2016)

CONTENTS:

I. [Introduction](#i-introduction)
II. [License](#ii-license)
III. [Installation](#iii-installation)
IV. [Revisions in Version 5.0](#iv-revisions-in-version-5.0)
V. [Acknowledgments](#v-acknowledgments)
IV. [Previous Revision History](#vi-previous-revision-history)

### I. Introduction
New Athena Unicode is a freeware multilingual font distributed by the Society for Classical Studies (formerly American Philological Association). It follows the latest version of the Unicode standard and includes characters for English and Western European languages, polytonic Greek, Coptic, Old Italic, and Demotic Egyptian (and Arabic) transliteration, as well as metrical symbols and other characters used by classical scholars.

The font is in TrueType format for four files offering Regular, Italic, Bold, and Bold Italic styles. A woff version is also available for web developers.

For a fuller revision history see the later section of this document.

New Athena Unicode is a "smart font": it contains OpenType ligature instructions that allow the display of well-formed precomposed glyphs in response to input of two or more Unicode code points. This capability allows the use of combinations like alpha with macron and acute and smooth breathing depending only on official Unicode code points. Ligatures are also used for correct placement of dots (U+0323) under Greek characters or strokes over Coptic characters. The same capability is helpful or necessary for some characters needed for papyrological transliterations of Demotic Egyptian or Arabic. Proper display of such features requires use of modern applications that support them. 

In version 5, the ligature definitions have been moved to a different OpenType table (ccmp), and as a result the substitutions should occur automatically in modern programs, and there is no longer a need to hunt for a way turn on special typographic features and enable ligatures of the liga type.

### II. License

Even the earliest versions of New Athena Unicode were distributed for free. For Version 3.4 (and later) of New Athena Unicode the Society has adopted an Open Font License. The license, which is quite expansive and explicit about how it may be used or adapted, is provided in full in a separate PDF in the download folder containing the fonts. For more information on this type of license consult: http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL

### III. Installation

Before installing a new version of the font, be sure to remove or disable the previous version, if you have been using New Athena Unicode before. The earlier versions should be named newathu.ttf or something similar (or New Athena Unicode.dfont, in a very old version). In Mac OS X you can open the Font Book application and remove (or disable) the old version and then add the new version.

New Athena Unicode is provided only in the .ttf format, which works the same on Windows, Mac OS X, and Linux. [A .woff version is available for websites. It is a separate download from the same page where this download is hosted.]

Windows: Either (1) open the Control Panel "Fonts" and use the command "Add Font..." or (2) select the font files you have downloaded, right-click for a contextual menu, and select Install. (For fuller details see http://apagreekkeys.org/installActivate.html).

Mac OS X: Simply double-click on the font file, and you will be presented with the choice to install it. Or open Font Book and use the Add Fonts… command (File menu or gear icon). (For fuller details see http://apagreekkeys.org/installActivate.html). If an application in which you want to use the newly-installed font is running, quit it and relaunch it.  

PUA Incompatibilities

In some installations of earlier versions of Mac OS X, the font LiHei Pro may be present in the font collection available to the system. This font contains conflicts with the PUA code points of precomposed characters like epsilon with circumflex. If you try to enter such a character with the GreekKeys Unicode input or by using the Character Palette, an Asian character may appear instead of the character you want. To have access to the conflicting Greek characters, you should open the application Font Book, then under Collection click on All Fonts. Scroll through the list in the Font column to LiHei Pro and select it. Then under the File menu choose the command Remove Font. Then restart, and the conflict should be gone. (An alternative is to choose the command Disable Font under the Edit menu.)

### IV. Revisions in Version 5
See Section VI below for Previous Revision History

June 2018: 5.005
--This version fixes an error in a font dimension setting in the Regular style. The other three styles did not require any correction in this regard. The error was the loss, of unexplained origin, of a negative sign in the descender setting. It occurred only in vdersionb 5.004 NAU Regular and is not present in version that is part of the GreekKeys2015 package. The error had no effect in many applications, but it does affect typesetting programs like Adobe InDesign and it started to have an effect in MS Word for Mac in 2018.
--For better placement adjacent to characters, the glyph for U+2245 was raised a little so that the bottom bar does not rest on the baseline.

November 2016: 5.004
--The glyph U+ec70 has been revised to be an exact mirror of U+2056 (dots were formerly of different size). 
--For better alignment of punctuation in some sequences of symbols, the position of the following glyphs has been lowered somewhat and made consistent with each other: tilde U+007e, U+2e1e, U+2e1f, dashes U+2012 through U+2015, double cross U+ec60.
--Seven additional PUA characters added for Greek manuscript catalogue purposes: 
----U+ec83, tachygraphic sign for ἐστι, a slash with a dot to either side, somewhat different from the dotted obelus U+2e13.
----U+ec84 has been assigned to the combination of dicolon and tilde-shaped line (the glyph had been present, but was not accessible when the composition command did not operate as expected); in addition, the spacing of the composed glyph has been adjusted and kerning instructions added to the decomposed version of colon + tilde so that the appearance of the two alternatives is more or less the same.
----U+ec85 is a tilde with dots both above and below (compare U+2e1e and U+2e1f, with their single dots).
----U+ec86, a reference symbol similar to the radical sign, but with two dots above the smaller left leg.
----U+ec87, an alternative to the plus sign U+002b that is positioned lower to align better with text and punctuation, for representing the scribal cross used in labeling annotations or text divisions.
----U+ec88, similar to U+2e13, but with a pair of dots on each side of the slash.
----U+ec89, a punctuation sign consisting of two commas stacked with the same spacing as the dicolon.

July 2015: 5.002
--The glyphs for capital stigma (U+03da) and for capital modern koppa (U+03de) have been revised for better matching of the lowercase forms. The previous shapes were based on much earlier versions of the Unicode charts and should have been revised long ago. The regular and the styled versions are now all at version 5.002, dated July 12, 2015.

June 2015: 5.0a
--The only difference from 5.00 in this version is that the regular NAU font has been regenerated on June 11, 2015, as version 5.001, containing the single change that the height of the capital beta has been corrected to match other capitals. This correction was made some time ago in the FontLabStudio file that generates the .ttf font, but for some reason the fonts generated previously still had the old height despite the apparent change in the originating file. By a workaround, FontLabStudio was persuaded that the glyph had indeed been changed, and the newly generated 5.001 version contains the proper height for capital beta. The styled fonts already had the correct height for capital beta and have not been changed.

May 2015: 5.00
--The major change in version 5 is that the instructions for composed characters (those that have to be entered as more than one Unicode code point, like beta with dot below or epsilon with macron above) have been moved from a liga table to a ccmp table, which makes the effect of these instructions automatic, rather than subject to the user’s switching on advanced typographic features.
--precomposed characters with combining overstroke (U+0305) added: 28 new glyphs for the 24 main lowercase Greek letters plus lowercase koppa, stigma, final sigma, and corresponding composition instructions added to ccmp feature.--reduced the height of capital beta and capital delta to conform with other Greek capitals
-- revised 00DE (Thorn); revised 2035 for better mirroring of 2032; revised 2CFE because of recent change of recommended form-- removed duplicates at 2E40-49 (erroneous code points too hastily adopted during pipeline phase in the past; the same exist at the proper code points 2E20-9), and corresponding changes have been made to GreekKeys 2015 symbol inputs.
--characters added:
----0223 for casing with 0222----02BB for fuller set----0318, 0319, 031B-031F, 0321, 0322, 0330, 0334 added glyphs for fuller set----037F capital yot----1EC8-9 for alternative hooked i----2194-9 for fuller set arrows----2921-2 arrows----2CF2-3 new in Coptic----2E3A-B longer dashes----2E3F capitulum----2E40 double hyphen, 2E41-2 reversed punct. ----A730-A778 characters in medieval Latin mss----1018B-C----1018D-E from pipeline----1032F from pipeline  V. Acknowledgments

New Athena Unicode is based on Athena Roman, a Unicode font created by Jeffrey Rusten including the polytonic Greek glyphs from the Athenian font he designed ca. 1990 based on various upright Greek fonts. Ralph Hancock made a number of corrections and improvements to Athena Roman. After I took over support of GreekKeys for the American Philological Association in 2001, I also began development of New Athena Unicode in order to support the use of polytonic Unicode Greek on the WWW. Like all scholars of Greek, I am indebted to the staff of the Thesaurus Linguae Graecae and its Director Maria Pantelia, who have shepherded many additional symbols needed by Hellenists through the process of incorporation into the Unicode Standard (versions 4.0 and later). New Athena Unicode therefore contains all the symbols previously available in the non-standard-encoded SymbolAthenian font (part of the traditional GreekKeys package), but also more.

During work on various versions, advice and help has been generously provided by members of Apple Computer's Font Group (Deborah Goldsmith, Lee Collins, Peter Lofting), Maria Pantelia, Nick Nicholas, and Richard Peevers of TLG, Ralph Hancock (author of the Antioch input schemes for Windows), Juan-José Marcos (author of the ALPHABETUM font), and Deborah Anderson of the Script Encoding Initiative. Work on this font could not have been completed without FontLab 4.x through 6.x for Mac OS X and BBEdit from BareBones Software. In earlier work Apple FontToolsX was also important. 

I am not a professional font designer, and most of my computer knowledge is at the level of the minimum needed to move forward with what I want to accomplish. There are various imperfections in the font, and compromises have been made in the interest of practicality (especially in the use of Private Use Area [=PUA] encoding) and inclusiveness (some glyphs are included whose use I would not myself endorse). For these shortcomings and other errors that may be detected, the responsibility is mine.

Donald Mastronarde
djmastronarde@berkeley.edu
http://ucbclassics.dreamhosters.com/djm/

### VII. Previous Revision History

July 2012: 4.05
--It was discovered that the ligatures were not working correctly in TextEdit and Word for OS X; the OpenType ligature tables were not being used by these applications because there were AAT tables present that were not supposed to be in the font any more, and the AAT tables were corrupt (a symptom of this was that the sequence dg would have ę substituted for it). Version 4.05 for all four styles of the font was generated in such as way as to ensure the AAT tables were not included. Otherwise, there was no change in the glyphs of the font, only an updating of the font information and version number.

February 2012: 4.03
--Working on the other APA fonts revealed that the automatic bolding routine in FontLab Studio may leave some glyph elements of composite characters unenlarged (or even reduced). Therefore, the Bold version of NAU has been carefully revised to remove such errors and to reduce the incidence of overlapping of different parts of composite charactera. Once the Bold version was fixed, a new Bold Italic version was generated. The Regular and Italic version have been updated solely in their font information, so that all styles are at the same version number and nearly the same date. 

July 2011: 4.02
--A typographical error in the OpenType tables was removed after being spotted by a user (it is not clear whether this typo had any effect). Otherwise the same as 4.01.

March 2011: 4.01
--U+2212 (minus) added at the request of a user.

Febuary 2011: 4.00
--revisions have been made in the Supplemental Punctuation block starting at U+2E00; namely, the characters at U+2E18-2E1B, U+2E1E-2E31 have all been added; the ten characters at U+2E20-2E29 were present before at U+2E40-2E49, the code points originally proposed, but in the final approval U+2E20-2E29 were assigned instead (the characters are still duplicated at U+2E41-2E49 in version 4.00 for backward compatibility, but users are advised to replace those characters with the correct ones, as U+2E41-2E49 will be deleted in some future version of the font).
--U+031A and U+2319 added.
--U+2229 (logical intersection) and U+222A (logical union) have been added.
--Italic, Bold, and Bold Italic versions have also been produced for beta testing.

May 2010: 3.71
--design adjustments have been made to many roman glyphs; previously curved letters like o, c,s had "overshoots" which caused irregular screen display of letter heights in Adobe Reader/Acrobat (Mac and Windows) and in Word for Windows, although printed versions and screen display in most other applications was fine; with elimination of the overshoots, even Adobe Reader/Acrobat and Word for Windows now shows the roman characters with a uniform height.
--precomposed characters with epsilon or omicron with breve and diacritics (breathing and/or acute or grave) have been added, along with the needed OpenType ligature definitions; then have to be entered with Character Viewer/Character Map or by composition from epsilon breve or omicron breve followed by combining diacritic, or by using the PUA code points U+EC73 through U+EC82.
--about three dozen additional roman characters with diacritics have been added to cover most or all of what is needed for some kinds of transliteration of Hebrew (please see the revised cmap file that will be posted soon at the GreekKeys site for a complete list of characters).

February 2010: 3.70
--design adjustments have been made to a few glyphs: the shapes of left and right single and double quotes have been made uniform (most noticeable in the improvement of U+2019, which serves as apostrophe in Greek); the dotted crosses U+203B and U+205C have been made similar in size and the dots made uniform with the dots in the nearby punctuation code points; U+10176 has been somewhat enlarged for better conformity to its new alternative form U+EC65; numerical lowercase koppa, U+03DF, has been lowered so that the open loop sits on the baseline and there is a descender; the double vertical bar, U+205B, and the double square brackets, U+301A, U+301B, have been given wider verticals so that they appear more legible and uniform at small sizes.
--a large number of unusual precomposed combinations and a few PUA glyphs (see U+EC55 through U+EC71) have been added in response to the needs of scholars writing catalogues of Greek manuscripts (credit is due to Robert Allison for contributing several glyphs and abundant advice). A table of these new items has been added to the listing on the GreekKeys website (apagreekkeys.org/technicalDetails.html#PUA); please consult it for fuller details.

November 2009: 3.61
--four PUA glyphs added at the request of papyrologists to provide variants for abbreviations common in papyri: U+EC51 (4 chalkoi = half obolos), U+EC52 (drachme), U+EC53 and U+ED54 (two variants of etos).

October 2009: 3.60
--the heights of Cyrillic characters (U+0400 through U+045F) have been made more uniform 

September 2009: 3.502
--four glyphs added for eta with breve, eta with macron, omega with breve, omega with macron (to help with an unusual papyrological text), and OpenType ligature definitions added. These can be displayed only when ligatures are turned on (MS Word 2008); to enter them, you must type the vowel normally and then input U+0304 (combining macron) or U+0306 (combining breve) immediately after the vowel (you can do this by switching to Unicode Hex input and typing 0304 or 0306 while continuously holding down the option key). There is no direct method for this with GreekKeys Unicode input.

September 2009: 3.5
--glyphs have been added to the font to improve support of papyrological transliterations  by adding the precomposed glyphs needed for Arabic. Most of the needed characters were already present, but the new ones are:  U+02BE (modifier letter half ring right, used for Arabic transliteration hams), U+02BF (letter modifier letter half ring left, used for Arabic transliteration yin), U+1E0C (D with dot below) U+1E0D (s with dot below), U+1E20 (G with macron), U+1E21 (g with macron), U+1E62 (S with dot below), U+1E63 (s with dot below), U+1E6C (T with dot below), U+1E6D (t with dot below), U+1E92 (Z with dot below), U+1E93 (z with dot below), precomposed t with diaeresis (U+0074, U+0308). 
--OpenType ligature definitions have been added to reflect the new combinations in the above additions (for instance, g (U+0067) followed by combining macron (U+0304 is replaced in ligature with U+1E21), and for different options for the combining diacritic for Egyptological yod transliteration (the same precomposed ligature result will appear whether i is followed by U+0313 or U+0357 or U+0486).
--modifications have been made to render the heights of the Greek capital letters more uniform in height. Some differences in height previously in the font were probably the result of accidental processes.
--modifications have been made to render the lowercase Roman characters more uniform in height (formerly, some lowercase letters were noticeably shorter than others).
--the numbers 0-9 have been redrawn as modern-style numbers, resting on the baseline and rising to approximately the height of the capitals; the old-style numbers (with some portions descending below the baseline, and the height generally approximately that of lowercase letters) are still present in the font as alternatives, for those who know how to access them.

August 2009: 3.45
--three glyphs have been added to the font to improve support of symbols needed for New Testament textual studies and editions: U+1D459 (symbol small italic l), U+1D513 (capital P symbol in Fraktur style), U+1D516 (capital S symbol in Fraktur style).

January 2009: 3.4
--copyright information embedded in the font has been modified to adopt the Open Font License v. 1.1.

April 2008: 3.3
--corrected height of glyph for lunate sigma to match other lowercase letters better
--corrected Coptic character U+03E7 to match the common shape of this character better, and made minor adjustments to thickness of strokes of a few other Coptic characters
--added dotted glyphs for lowercase Greek characters (including those with diacritics), for better placement of underdots in programs capable of using OpenType ligatures
--added dotted glyphs for lowercase Coptic characters, for better placement of underdots in programs capable of using OpenType ligatures
--added glyphs for lowercase Coptic characters with combining overstroke (U+0305), for better placement of overstrokes in programs capable of using OpenType ligatures

January 2008: 3.2
--corrected glyph for alpha with breve and grave, which had been larger than other alphas
--generated font with OpenType features only, omitting Apple AAT, since the latter features do not work as completely as OpenType and their presence prevents TextEdit and NeoOffice from using the OpenType features; with this change, ligatures now work equally well in Mellel, TextEdit, NeoOffice, and InDesign (and also Word 2008)

December 2007: 3.1
--glyph for middot U+00b7 (now recommended for the Greek high stop or colon) redrawn to match the height of lowercase Greek letters; U+03d5 (phi symbol, not for use as text) redrawn so that vertical rises above loop. 
--added glyphs to cover characters specified in latest quickbeta guide from TLG (various brackets U+2E40-41, U+2E46-49, U+2227-2228
--added glyphs for pipeline characters for Latin inscriptions (reversed F, I longa, etc., U+a7fb-ff)
--added glyphs for pipeline characters for Roman weights and measures and coin symbols (U+10190-1019A)
--added glyphs for pipeline characters for Coptic cryptogrammatic forms and combining ni above, combining spiritus asper and spiritus lenis (U+2CEB-2CF1)
--added definitions for OpenType and AAT ligatures to allow input of completely decomposed Unicode 

June 2007: 3.0
--added glyphs for pipeline characters Egyptological Alef ([new] capital U+A722, small U+A723 = [PUA] U+EC42), Egyptological Ain ([new] U+A724, U+A725 = [PUA] U+EC43) and forthcoming new half square brackets (U+2E42-2E45). These characters are not yet referenced in the respective inputs.
--added glyph for pipeline character Greek capital KAI symbol, U+03CF (previously available in PUA at U+E1A6)
--added epsilon with macron and circumflex (U+EB27), epsilon with macron and smooth and circumflex (U+EB20), epsilon with macron and rough and circumflex (U+EB21), omicron with macron and circumflex (U+EB5A), omicron with macron and smooth and circumflex (U+EB5B), omicron with macron and rough and circumflex (U+EB5C)
--redrew U+03E2, U+03E3 to make the tail of the character more distinct
--redrew some glyphs of Ancient Greek Numbers block (U+10140 to U+1018A) to create greater uniformity of width of stems and size of characters
--added Old Italic block, U+10300 through U+1031E, U+10320 through U+10323
--revised the OpenType tables to include duplication of definitions with various declarations of language and script. This is needed to make OpenType features work uniformly in OpenType-savvy applications in both OS X Tiger and OS X Leopard. OS X Applications using AAT ligatures instead of OpenType still suffer from a bug affecting a few combinations.

August 2006: 2.85/2.86
This is mostly a maintenance release containing a very few under-the-hood corrections to v. 2.8, mainly in glyph names (which are not really significant to the end-user).
--[v. 2.86] added glyphs for Coptic papyrology, U+EC4F coptic iota with diaeresis, U+EC50 coptic ua with diaeresis (these can also be entered decomposed in applications that interpret smart features: U+2C93,U+-308 and U+2CA9,U+0308)
--added glyphs for U+03D2, U_03D3, U+03D4 
--added glyphs for pipeline characters U+0370 capital heta (same shape as  U+10142), U+0371 small heta, U+0372 capital archaic sampi (same shape as Private Use Area U+E19C), U+0373 small archaic sampi, U+0376 capital Pamphylian digamma, U+0377 small Pamphylian digamma, which will be in a future version of Unicode

July 2006: v. 2.8
--added Gcaroν U+01E6
--revised names of some glyphs to match latest recommendation from Adobe for naming glyphs
--added OpenType ligature features so that the font now works if you input decomposed Unicode sequences; added additional features to Apple MIF table to match OpenType ligatures
--exchanged the glyphs for U+2E14 and U+2E15 (had previously followed original proposal made by TLG, but am now informed the mistaken swapping of these two glyphs in Unicode 4 will be permanent

March 2006: v. 2.7
--addition of various combining diacritics, some to complement Coptic characters: 030b, 030d, 030e, 030f, 0315, 0316, 0317, 0320, 0324, 0325, 0327, 0329, 032a, 032b, 032c, 0335, 0337, 0351, 0359, 035e, 035f, 037b, 037c, 037d; Claudian letter half H 2c75, 2c76
--redrew ec46 and ec49 (PUA codepoints for egyptological yod) to make the diacritic match the upper hook of eqyptological alef (closer in form to the combining right half ring above 0359)
--added ec4a as PUA precomposed form of Coptic u (2ca9) with short cross stroke (0335)

September 2005: v 2.6
--addition of capital Egyptological yod (PUA U+ec49) as precomposed character, and of U+0269, U+033f, U+2053, U+2056 to complete set of characters needed for Coptic
--made endash, emdash, and quotation dash (U+2013-2015) thicker to match rest of font

July 2005: v 2.5
--addition of 28 characters, mostly to accommodate the needs of Demotic Egyptian transliteration using Unicode codepoints (roman characters with diacritics) and a few PUA codepoints
--minor adjustments and corrections to a few characters (e.g. those with made with strokes of too little weight, such as U+27C0, U+27C1)
--resized slightly and adjusted vertical height of lowercase epsilon, nu, chi, kappa (nu in particular had somehow become too tall and too heavy)

June 2005: v 2.4
--expanded font to include all official Unicode codepoints mentioned in the May 27, 2005, version of TLG Beta Code Quick Reference Guide [EXCEPTIONS: the astrological symbols on pp. 11-12, betacodes #202-250, in the block starting at U+2600].
--added a few additional symbols closely related to other new symbols (U+2126, 2193, 223C, 271C); added U+0158, omitted by oversight in previous version
--corrected U+25EF
--revised paragraphos symbols U+2E0F, 2E10, 2E11 as zero-width characters to be typed at beginning of line, extending slightly into left margin and under the first characters of the line
--corrected problem with extra height in U+1FB0 (but FontLab may still produce some characters at wrong size)

[April 2005: very limited test release, never posted for download
--added Coptic letters in the Greek and Coptic block (03E2-3EF), imitating the letterforms in the proposals for Unicode 4.1
--added Coptic letters in the new Coptic block (2C80-2CFF), imitating the letterforms in the proposals for Unicode 4.1]

April 2005: v 2.3
--adjusted vertical placement of upper half brackets (U+2308, U+2309) and of square bracket
--corrected orientation of U+0312
--corrected shape of U+0309
--extended length of combining overscore (U+0305); renamed U+00af as "macron" and U+02c9 as "macron2"

March 2005: v. 2.2
--the character U+0123 (gcommaaccent) was corrected (the accent had been turned the wrong way)
--various corrections were made to the character outlines (removal of redundant nodes and the like)
--minor modifications were made to the spacing of characters, and greater consistency was sought for spacing of characters in same class
--combined characters that had accidentally been left composed in the font were decomposed to insure sizes of characters in same class were uniform
--newly generated font apparently fixes a problem that made some sizes of the previous version overlap Greek characters in Windows applications

January 2005: v. 2.1
--representation of U+2058 (four dot punctuation) revised to match picture in Unicode 4.1 chart (four dots form a diamond, not a square).

September 2004: v2.0
--adjustment of height specifications of the font to try to allow correct display of capitals with macron, breve, or diaeresis above in Microsoft Word 2004 for Mac OS X. It is still necessary for the user to manually set the line-spacing (in Format:Paragraph...) to At least: [2 pts larger than the size of the font]. This adjustment did correct a fault in the font that made it unusable in BBEdit 7.x, where earlier versions were displayed with too little line height, cutting off the bottom of the glyphs; and improved rendering in Windows.
--agreed on new PUA assignments for precomposed glyphs for alpha, iota, and upsilon with breve and macron and other diacritics (codepoints will be shared with ALPHABETUM font of Juan-José Marcos and other fonts).
--added precomposed glyphs and assigned PUA codepoints in agreement with scheme already used by Ralph Hancock and others (omicron or epsilon with macron and other diacritics, etc.).
--changed capital vowels with iota adscript to show iota at regular size; retained alternative versions with shrunken iota (and older Unicode versions with subscript iota under capitals) in PUA (starting at EC20) for anyone who really wants those glyphs.
--a number of characters with overlapping contours corrected by merging contours
--roman characters with ogonek revised for correct placement of ogonek
--various roman characters and symbols improved in spacing or design in response to suggestions
--added left and right angle brackets 2329 and 232a as distinct from greater than and lesser than signs
--additional characters from TLG proposals (approved by Unicode, but still in process of ISO approval): 
[for the following codepoints see information at http://www.unicode.org/alloc/Pipeline.html as well as the information at the TLG website about unicode proposals and betacode to Unicode equivalences]
0359 combining asterisk below
035c combining double breve below (papyrological hyphen)
03f4 capital theta symbol
03f5 lunate epsilon symbol
03f6 reversed lunate epsilon symbol
03fc rho with stroke symbol
03fd-03ff antisigma, sigma dotted, antisigma dotted
1dc0-1dc1 dotted grave and acute (combining)
2058-2059 four and five dot punctuation
205a, 205b, 205c, 205d, 205e two dot punctuation,four dot mark,  dotted cross, tricolon, four dots verticaL
23d1-23d9 metrical symbols (along with TLG metrical symbols in other ranges)
27co-27c1 misc. mathematical symbols
2e00-2e0c New Testament editorial characters (and 2e0d as mirror of 2e0c)
2e0e-2e16 supplemental punctuation including coronis, paragraphos, etc.
10140-10174 ancient Greek acrophonic numerals
10175-10189 ancient Greek papyrological numerals
1018a Greek zero sign
1d200-1d245 archaic Greek musical notation

December 2003: v1.9
--The encoding of the double brackets and of the half brackets has been corrected. The former are now U+27e6 and U+27e7 (mathematical) instead of U+301a and U+301b (CJK). The latter are now U+230a, U+230b, U+2308, U+2309 instead of U+231e, U+231f, U+231c (U+2309 has been newly added for completeness). The corrected encodings are those recommended by TLG.

August 2003: v1.85
--characters œ æ ø of the roman portion of the font repaired (these had been out of proportion to other lowercase letters).


May 2003: v1.8
--precomposed glyphs added to facilitate display of macron or circumflex or circumflex plus either breathing over epsilon and omicron
--ligature definitions added to correspond to the added glyphs (again this depends on MIF files supported only by TextEdit)

March 2003
--ligature definitions adjusted to allow correct display of macron or breve with diacritics in sizes 12 and below (Dec 2002 version showed the ligatures only in size 13 and higher)
--spacing of glyphs based on omega regularized (some had insufficient width on right and crashed slightly with the following character)

December 14, 2002: v. 1.55
--uppercase lunate sigma moved to 03f9, the proposed location (had been 03f4, now officially assigned to a different glyph)
--archaic koppa now officially assigned to 03d9
--uppercase archaic koppa added at 03d8
--glyph for 0314 (equivalent to rough breathing with no space) corrected (was turned wrong way)
--archaic san and San added at 03fb and 03fa
--Bactrian sho and Sho added at 03f8 and 03f7
--glyphs added for alpha, iota, or upsilon with macron or breve and other diacritics, with use of Apple-supported MIF files (which work only in TextEdit)
--alternate form of pi (03d6) corrected (had been incompletely drawn and was like omega)
--iota subscript on capital vowels moved to adscript position (as in Unicode 3)
--corrections to included non-Greek glyphs that were incomplete or erroneous:
- Scaron (U+0160): caron missing
- scaron (U+0161): caron missing
- Aring (U+00C5): ring missing
- Yacute (U+00DD): acute missing
- aring (U+00E5): ring missing
- Ebreve (U+0114): E missing
- Ecaron (U+011A): E missing
- Ibreve (U+012C): macron instead of a breve over the I
- Nacute (U+0143): acute too far to the right
- nacute (U+0144): acute too far to the right
- Zacute (U+0179): acute too far to the right
- zacute (U+017A): acute too far to the right
- Edotaccent (U+0116): E missing.
- ring (combining) added (U+030A)

August 2002
-- New Athena Unicode created by additions and revisions to Athena Unicode, a font originated by Jeffrey Rusten (with the Greek characters taken from his GreekKeys Athenian font) and corrected by Ralph Hancock.
