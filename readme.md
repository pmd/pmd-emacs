# PMD Emacs
Major mode for plugging PMD into Emacs.

## Change History

* **???? 0.9**:

  - [PR#5](https://github.com/pmd/pmd-emacs/pull/5): Make pmd.el non-executable

* **2016-01-14 0.8**:

  - Fixed license link
  - Create tag for release

* **2013-08-16 0.7**: Ernst Reissner

  - Updated to work with PMD 5.0.2 and 5.0.5

* **10/21/2005 0.6**: Nascif A. Abousalh-Neto

  - Updated to work with PMD 3.3

* **06/16/2004 0.5**: Nascif A. Abousalh-Neto

  - Tested with PMD 1.08
  - fixed dependency on missing defun

* **03/24/2003 0.4**: Nascif A. Abousalh-Neto

  - Update to align with PMD 1.04.
  - Added new method, pmd-current-dir
  - Removed variable pmd-version
  - Changed customization: string variable pmd-rulesets replaced by list-based variable pmd-ruleset-list

* **02/04/2003 0.3**: Nascif A. Abousalh-Neto

  - Updated the primary plugin with contributions.  Note that these changes include an updated pmd-1.02.jar file to support them.  These changes will be part of pmd-1.03 when it comes out; this is just an updated release of pmd-1.02 to support this Emacs plugin.

* **01/16/2003 0.2**: John Russell

  - Completely rewritten

* **06/06/2002 0.1**
  - First version of PMD for Emacs
  - Defined one function "pmd-current-buffer" which will run PMD on the current buffer, and write the output to *PMD*. Output format is in XML.  I will work in trying to get a better, easier to read format for everyone.
