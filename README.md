# csl-styles
A few styles using the [Citation Styles Language](https://docs.citationstyles.org/en/stable/index.html). The main difference with the ISO 690 styles available in the (official repository)[https://github.com/citation-style-language/styles/], is that the styles here are multilingual (no attribute `default-locale` is set, see also https://docs.citationstyles.org/en/stable/specification.html#the-root-element-cs-style), so e.g. when using (Zotero)[https://www.zotero.org/], the language can be chosen on creation of a bibliographic entry.

## citation-label

A note on the label styles (`<category citation-format="label"/>`) and (Zotero)[https://www.zotero.org/]: Zotero automatically generates a label (based on the creator and the date), but if you want to assign your own label, then put `citation-label: replaceThisWithYourOwnLabel` in the Extra field, see also https://www.zotero.org/support/kb/item_types_and_fields#citing_fields_from_extra and https://docs.citationstyles.org/en/stable/specification.html#standard-variables.

