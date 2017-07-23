Persnoal Filesystem Hierarchy Standard
======================================

My computer root file system adheres the Filesystem Hierarchy Standard.
But my home directory is a mess.
Thus I try design something like pfhs
(Persnoal Filesystem Hierarchy Standard)
to organize my files.

- bin: executable.

- etc: dotfiles

- img: disk images, including:

    * iso

        + os, including: win, linux, osx, bsd, android

    * vm

        + ova

        + vdi

        + vhd

        + vagrant

        + docker

- VM: Virtual machines

- opt: softwares (like `bin`, but not single executable)

- src: source files, including:

    * repo

      + git

      + hg

      + darcs

      + svn

      + bzr

      + cvs

    * tar: tarballs, zips, etc.

    * code: single files.

- repo: repositories

    * sources: I am the owner

    * contrib: I have push access

    * forks

    * gists

    * private: unpublished, internal usage, without sensitive data

    * secrete: with personal data

- font

- pkg: Binary software distribution/installers.

- game: like pkg, but limited to games

- ref: references, including:

    * dict: dictionaries

    * api: api doc

- tmp: temporary files, no backup needed.

- var: temporary files to process, backup needed.

- bkp:

    * bup

    * attic

    * borg

    * log: chat logs

    * mail: mails

- book: epub, mobi, pdf, djvu, etc.

- image:

    * sample

    * icon

    * wallpaper

    * photo:

        + jpg

        + tiff

    * raw: DNG, X3F, etc

- audio:

    * voice

    * music

- video:

    * sample

    * talk

    * event

    * movie

        + 0: unrated
        + 1: WTF
        + 2: I do not want to waste my time on this
        + 3: to kill my time
        + 4: I probably will not watch it again, but I am not object to.
        + 5: I will watch it again, when I have time.

- UNSORTED: what a mess
- RECYCLED: trash bin
