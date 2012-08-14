RNCProPack.js
=============

RNC ProPack - multi-format file packer port to JavaScript

## Background

Rob Northen compression (RNC) is a multi-platform compression format created by Rob Northen in 1991. It is a variant of LZSS and Huffman. Decompression libraries have been written for the PC, Mega Drive, Game Boy, SNES and Atari Lynx. RNC is used in a number of games by UK developers (notably Bullfrog and Traveller's Tales), including Sonic 3D: Flickies' Island, Theme Hospital, Dungeon Keeper 2, Magic Carpet, Syndicate and Syndicate Wars.

## Technical details

Use recently introduced Uint8Array to emulate a basic pointer mechanism in a binary buffer. The library is wrapped in a UMD format so it can be used both browser and server side with Node.

## Based on these previous documentations / implementations :

- http://segaretro.org/Rob_Northen_compression
- http://www.yoda.arachsys.com/dk/utils.html
- http://code.google.com/p/corsix-th/wiki/RNC

## TODO
- pack() method
- make it asynchronous