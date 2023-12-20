## What is this

A simple cjs wrapper to the [move-file](https://github.com/sindresorhus/move-file) module

## Why make a wrapper ?

Since version 3 of move-file, the module [only supports esm import](https://github.com/sindresorhus/move-file/commit/ef6798c4bb1e9b3e3ede3355852166041b98a057).
In order to continue using this module conveniently I decided to wrap it in [fix-esm](https://www.npmjs.com/package/fix-esm).

## Why declare move-file as a peer dependency ?

Doing this allows you to decide the version of move-file in your project.
