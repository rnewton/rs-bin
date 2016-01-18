# rs-bin
Scripts that make working with Research Square repositories a bit easier

## Utilities for cloning

### clone

Usage: `clone REPO [SITE]`

Clone a repository, run `ant init`, and link your vhosts.

## gitclone

Usage: `gitclone REPO DEST`

A shortcut for cloning a researchsquare repository.

## vhosts

Usage: `vhosts`

Automatically create vhosts for every site in your home directory.

## Utilities specific to AJE

### clientid

Usage: `clientid`

Update application/config/aje.ini with a random identity.client_id.

### notices

Usage: `notices [on|off]`

Update application/config/aje.ini to turn notices on or off.  This makes client
review much easier.

## Miscellaneous

### daily

Usage: `daily`

Create a daily log in the `~/daily` directory with the current date as its
filename.

### inoffice

Usage: `inoffice`

Find out who is in the office and logged into the current server.
