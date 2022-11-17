# DCU32INT - Delphi Compiled Units Parser
The utility DCU32INT parses *.dcu file and converts it into a close to Pascal form.

This is an updated version of the original utility, which has added partial* support for units of new versions of Delphi. (Delphi 10.4, Delphi 11)

* The utility can now read dcu-files of new versions of Delphi, but the new language features of these versions may not be available and not recognized by the utility, they may contain errors, but this will not greatly affect the final file.

NEW: You can extract DCU (Delphi Compiled Unit) files from dcp (Delphi Compiled Package)
* Example: dcu32int.exe -X mycoollibrary.dcp (contains: mycoollibrary.dcu, mycoollibrary_design.dcu)
* Input: mycoollibrary.dcp
* Output: mycoollibrary.dcu, mycoollibrary_design.dcu
