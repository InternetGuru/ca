# AMS 1 2021-02-16 GNU "User Manuals"

## NAME

AMS - coding assignment handling

## SYNOPSIS

`ams` [`-w`] `<command>` [`<args>`]

## DESCRIPTION

Provides commands to _distribute_ coding assignments to solvers, _evaluate_ individual solutions and _measure_ similarities between each other.

## OPTIONS

-w, --working-dir WORKING_DIR
       Run as if ${SCRIPT} was started in WORKING_DIR instead of the current working directory.

## COMMANDS

These are common ams commands used in various situations:

collect
       Download repositories and evaluate against source tests.

distribute
       Create or update user repositories with files from source project.

evaluate
       Verify Java project and generate badges for README.

help
       Display this usage.

measure
       Compute software similarities between projects using Moss script.

## EXIT STATUS

1      Other error.

## EXAMPLES

TODO

## BUGS

TODO

## AUTHOR

George J. Pavelka <george@internetguru.io>

## SEE ALSO

`ams-collect`(1), `ams-distribute`(1), `ams-evaluate`(1), `ams-measure`(1)
