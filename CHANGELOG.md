0.0.4 (2026-11-25)
==================

* [Enhancement] Do not bundle jackson in the shadow jar. The plugin does not use it directly, and digdag provides it.
* [Enhancement] Include the unreleased changes on main since 0.0.3: digdag 0.10.0, scala 2.13, gradle 6.8.3, dependency locking
* [Fix] Disable dependency locking for the zinc configuration of the scala plugin, which made the build fail

0.0.3 (2021-02-01)
==================

* [#9](https://github.com/civitaspo/digdag-operator-param/pull/9) [Enhancement] Do not use a temporary file to use workspace.temlateFile, use templateEngine.tempale instead
* [#12](https://github.com/civitaspo/digdag-operator-param/pull/12) [Enhancement] Use gha instead of circleci

0.0.2 (2018-10-23)
==================

* [Feature] Add `param_eval>` operator that is a workaround for https://github.com/treasure-data/digdag/issues/862

0.0.1 (2018-10-07)
==================

* First Release
