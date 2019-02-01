# sakura-editor-themes
C'mon, pull requests!
# pull request
## original files
+ PRs which add files to top level, it won't be merged.
+ Please make sub-directory named by language's name under `theme`, and make directory again named by version, and make directory again your theme's name (e.g. A sanctuary's Java11 theme will be `/theme/java/11/Sanctuary/{theme_name}/{version}`).
+ Please make sure to verify regexp or highlighted-word. Broken themes are useless for user.
+ All language name should be lower-cased, if original is upper-cased.
+ Please commit common version (e.g. `for Python 2.x`, `for Python 3.x`) under `/theme/{language}/{common_version}/{author}/{theme_name}/{version}`. (e.g. `Python 3.x` is `/theme/python/3.x/...`)
++ If all version, common_version should be `*`.
