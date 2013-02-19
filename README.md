MagicSuggest v1.0
--------------------------

Check out full documentation and examples here: http://nicolasbize.github.com/magicsuggest/

Milestone change log:

v1.0.6 Custom Input Tag
=======================
- (cfg) inputCfg : allows additional parameters passed out to the INPUT tag. Enables usage of AngularJS's custom tags for ex.

v1.0.5 Custom rendering
=======================
- (cfg) renderer : allows custom rendering within the combo.

v1.0.4 Grouping ability
=======================
- (cfg) groupBy : allows grouping within the combo box listing.

v1.0.3 ie compatibility
=======================
- (fix) blur event now registers correctly when selecting an element from the combo
- (fix) flicker in IE when hovering trigger
- (cfg) strictSuggest : set how suggestions will be proposed

v1.0.2 bugfixing
================
- (fix) maxResults is now correctly interpreted
- (fix) maxSelection is now correctly interpreted
- (cfg) method : set the ajax method, default to 'POST'
- ajax request can now interpret multiple results from server base.

v1.0.1 validation and bugfixing
===============================
- fix bug where the blur event would be triggered when clicking upon the page
- required and validation

v1.0. initial component release
===============================
- choose to allow free entries or not
- keyboard management
- theme ability
- static and dynamic data processing
- positionning