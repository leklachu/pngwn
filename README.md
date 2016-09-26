# The Search for the Missing Penguin

A text-based adventure in Inform, regarding, apparently, some manner
of missing penguin and the search therefor.

Pngwn is playable, and - of a sort - completable - but not truly
finished.

## Playing

You <ahem> might want to play it before delving through the source
code. The .z5 file is the compiled game, to be played in Frotz. Look
for pngwnxby.z5 (e.g. pngwn2b5.z5) as the beta release for
playing. Straight pngwn.z5 is the alpha release with debugging.

## Compiling

Compiles in Inform 6. From memory, alpha releases are compiled with -X
and maybe -D, and beta releases with -S (which inform might add by
default). Beta releases should be compiled with their version in the
name, so version 2.5 becomes pngwn2b5.z5

Beta releases need two adjustments in the source file, commented at
the top. New releases also need a change in the welcome messages,
towards the bottom of the file.

Release minor version wants updating in the alpha after each beta
release, ready for the new beta minor release.