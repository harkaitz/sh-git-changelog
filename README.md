GIT CHANGELOG
=============

Update changelogs using git-task(1) tasks.

## Help

wds_changelog

    Usage: git-changelog { -V | -a (add) | -c (close) | -u (update) }
    
    Fill the CHANGELOG.md file with done tasks in git-task(1).
     ______________________________
    | YYYY-MM-DD  VER  TEXT (open) | Reads PROJECT, VERSION from Makefile
    |                              | and searches @done tasks that Changelog
    | [ tab  ]- (@CODE) MESSAGE    | is PROJECT.
    |______________________________|

wds_nextver

    Usage: wds_nextver { -M (major) | -m (minor) | -p (patch) }
    
    Increase the VERSION in the makefile by one.
    When no arguments are given it simply prints the version. If there's
    a "v.LANG" type target it is generated.
    
    Version scheme: MAJOR.MINOR.PATCH

## Collaborating

For making bug reports, feature requests, support or consulting visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)
