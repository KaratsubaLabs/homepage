
# からつばLABS homepage

simple homepage for **からつばLABS** in both english and japanese

## USAGE

translations are stored under `lang/` as a shell script so arbitrary shell can
be executed. allexport is set before sourcing the translation file so it
suffices to define a variable with the name of the key that is used in the
template.

the utility `transgen` will build the pages. `transcheck` is also included to
warn for any missing translations.

