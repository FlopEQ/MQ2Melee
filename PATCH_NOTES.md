# MQ2Melee Patch Notes

## FlopEQ Test Build - 2026-06-30

### Stability & Safety
* Fixed a plugin API preprocessor footer issue.
* Made command formatting safer by using bounded formatting and ensuring varargs cleanup.
* Fixed an unsigned discipline timer comparison that could produce incorrect timer behavior.
* Added a pet target null check before pet attack helper logic.
* Restored the original target pointer after pet attack helper checks so follow-up logic does not inherit a temporary pet target.
* Made incoming chat string copying safer.
