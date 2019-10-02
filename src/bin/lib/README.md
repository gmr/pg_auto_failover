# Vendored-in librairies

## log.c

A very simple lib for handling logs in C is available at

  https://github.com/rxi/log.c

It says that

  log.c and log.h should be dropped into an existing project and compiled
  along with it.

So this directory contains a _vendored-in_ copy of the log.c repository.

## SubCommands.c

The single-header library is used to implement parsing "modern" command lines.

## Configuration file parsing

We utilize the "ini.h" ini-file reader from https://github.com/mattiasgustavsson/libs

## HTTP and JSON

We use https://github.com/vurtun/mmx implementation of an HTTP server in C,
with some extra facilities such as JSON parsing. The library is licenced
separately for the different files:

  - web.h is BSD licence

We don't use the other files, so those have not been imported in this
repository.

## JSON

The parson librairy at https://github.com/kgabis/parson is a single C file
and MIT licenced. It allows parsing from and serializing to JSON.
