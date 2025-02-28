# datamods 1.3.2

* Fix bad link in NEWS.



# datamods 1.3.1

* Fixed a bug in `update_variables` module.



# datamods 1.3.0

* New module to read flat data from URLs `import_url_*()`.
* Error messages displayed to the user are more informative on the actual error.
* `filter_data_server()`: new argument `value_na` to set default value for NA's filters widgets.
* `import_copypaste_ui()`: new argument `name_field` to show or not name field.
* `import_copypaste_server()`: new argument `fread_args` to pass arguments to `data.table::fread`.
* i18n: chinese translations added, thanks to [@xmusphlkg](https://github.com/xmusphlkg).
* i18n: spanish translations added, thanks to [@dnldelarosa](https://github.com/dnldelarosa).
* i18n: german translations added, thanks to [@SteEcker](https://github.com/SteEcker) and [@joerghenkebuero](https://github.com/joerghenkebuero).



# datamods 1.2.0

* Switch to [{phosphoricons}](https://github.com/dreamRs/phosphoricons) for icons.
* `import_file_ui()` has a new argument `file_extensions` to select the files that the user can import.
* `import_file_server()` has a new argument `read_fns` to define custom function(s) to read data.

### Translations
* i18n: :macedonia: macedonian translations added, thanks to [@novica](https://github.com/novica).
* i18n: :albania: albanian translations added, thanks to [@novica](https://github.com/novica).
* i18n: :portugal: :brazil: brazilian portuguese translations added, thanks to [@gabrielteotonio](https://github.com/gabrielteotonio).



# datamods 1.1.5

* `import_*_server()` added reset argument to clear the data.
* `import_copypaste_server()` also return a `reactive` function "name" like the others.
* New function `i18n()` to add internationalization in shiny apps.



# datamods 1.1.4

* `filter_data_server`: convert data to `data.frame` (fix [esquisse #149](https://github.com/dreamRs/esquisse/issues/149)).
* `filter_data_server`: fixed bug with timezone if POSIXct.
* Import data from package: use `pkg::data` notation for data's name.



# datamods 1.1.3

* Preserve class `sf` in output.



# datamods 1.1.2

* Fixed a bug when retrieving data from package with parenthesis in name.
* Fixed test on R-oldrel



# datamods 1.1.0

* Added internationalization to translate labels used in modules, see corresponding vignette.



# datamods 1.0.1

* First release on CRAN: Shiny modules import, to update, validate and filter data in interactive applications
* Added a `NEWS.md` file to track changes to the package.
