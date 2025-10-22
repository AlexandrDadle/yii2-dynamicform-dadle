# yii2-dynamicform change Log


## [v0.2.1 (2025-10-23)](https://github.com/AlexandrDadle/yii2-dynamicform-dadle/compare/v0.2...v0.2.1)

- Refactored `yii2-dynamic-form.js` to resolve widget options via a safe helper instead of `eval`, restoring nested form cloning behaviour and reducing XSS risk.
- Hardened reinitialisation flow with extra null-checks so dependent widgets (select2, datepicker, etc.) no longer throw when configuration is missing.
- Bumped the `yiisoft/yii2` constraint to `~2.0.5|~2.0.40` for compatibility with the 2.0.40+ patch line.

## [v0.2.0 (2025-10-22)](https://github.com/AlexandrDadle/yii2-dynamicform-dadle/releases/tag/v0.2)

- Fork renamed to `alexandrdadle/yii2-dynamicform-dadle`, namespace switched to `alexandrdadle\\dynamicform`, and installation docs refreshed.
- Expanded compatibility of `symfony/css-selector` and `symfony/dom-crawler` up to the 7.x series.
- Marked project as maintained fork targeting PHP 7.4+/8.x environments.


## [v2.0.3 (2020-05-18)](https://github.com/wbraganca/yii2-dynamicform/compare/v2.0.3...v2.0.2)

- Enh: Updated composer.json ('symfony/dom-crawler': '~2.8|~3.0' and 'symfony/css-selector': '~2.8|~3.0').
- Bug #40: Fixed dropDownList reset after insert item.
- Enh #25: Added enhancements to better support for nested widgets.
- Enh #24: Added support for "jquery.inputmask". It only works with Yii 2.0.4 or higher.
- Enh: Remove "error/success" class css template to be cloned.
- Bug: Fixes for: checkbox(), checkboxList(), radio() and radioList().
- Bug #224: Fixes the cloning of elements.


## [v2.0.2 (2015-02-25)](https://github.com/wbraganca/yii2-dynamicform/compare/v2.0.2...v2.0.1)

- Bug #22: Correct reset attributes (id, name) when we have more than two nested widgets 


## [v2.0.1 (2015-02-23)](https://github.com/wbraganca/yii2-dynamicform/compare/v2.0.1...v2.0.0)

- Bug: Fixed error for the use of multiple nested widgets with zero initial elements


## v2.0.0 (2015-02-22)

- Enh #20: Added trigger 'beforeDelete'
- Bug #19: Fixes checkboxes on new items
- Enh #15: Added support for multiple nested widgets


## v1.1.0 (2014-12-16)

- Bug #7: Added support for "kartik-v/yii2-widget-depdrop" for working with type DepDrop::TYPE_SELECT2
- Bug #8: Fixes to support the latest version of kartik-v widgets
- Bug: Fixed client validation
- Bug #6: Fixed settings for datepicker
- Enh: Added support for "kartik-v/yii2-widget-depdrop"
- Enh: Added support for "kartik-v/yii2-widget-select2"
- Bug: Fixed html name attribute for "kartik-v/yii2-widget-colorinput"
- Enh: Added support for "kartik-v/yii2-widget-timepicker"
- Enh: Added support for "kartik-v/yii2-widget-colorinput"


## v1.0.0 (2014-11-05)

Initial release
