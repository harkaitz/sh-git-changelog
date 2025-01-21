GIT CHANGELOG
=============

Update changelogs using git-task(1) tasks.

## Help

git-changelog

    Usage: git-changelog { -V | -a (add) | -c (close) | -u (update) }
    
    Program for automatically filling the changelog from git-task(1)
    tasks. The format of the changelog is as follows:
      __________________________________
     | YYYY-MM-DD  VERSION  TEXT (open) | * The updated section is 
     |                                  |   the last one with (open).
     | [ tab  ]- (@CODE) MESSAGE        | 
     | [ tab  ]- (@CODE) MESSAGE        | * The version or an open section
     | ...                              |   matches the version in the makefile.
     |__________________________________|
    
    Tasks that contain "Changelog" with the same project name in the
    makefile and that are "@done" are selected. Move to @closed once
    the release is done.

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
