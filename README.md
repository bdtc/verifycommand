# verifycommand

The LaTeX verifycommand package — Verifies definitions are unchanged, such as before patching.

For package authors who patch code from other packages.

To improve reliability, the verifycommand package provides a way to verify that macros or environments have not changed. This allows a package author to check before patching a definition. If a definition is not as expected, a warning is issued. At the end of the compile, a list of all changed definitions is displayed.

Uses an MD5 checksum of the expected definition and compares to the checksum of the current definition.

**Be sure to check the _Discussions_ tab above!**

The code and manual are at CTAN: https://ctan.org/pkg/verifycommand
