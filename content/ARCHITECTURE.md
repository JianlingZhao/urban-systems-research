# Repository Architecture

This repository is structured around a clear separation
between mechanisms, actors, and narratives.

## Atlas
The atlas defines system-level mechanisms.
Each mechanism should be fully explained only once.

## Mechanisms
Mechanisms explain WHY the system behaves as it does.
They must not be duplicated elsewhere.

## Actors
Actors describe positions and roles in the system.
They may reference mechanisms, but not redefine them.

## Projects and Stories
Stories guide readers through specific systems
by invoking mechanisms defined in the atlas.

## Rule of Thumb
If you are explaining "why", you are probably in the wrong place
unless you are editing the mechanisms folder.

