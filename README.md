# cpanpm-distroprefs

## ABOUT

This project tracks "**distroprefs**" config files.

It aims to become a, for instance: the, central repository for them.

"Distroprefs" are a config mechanism of the CPAN.pm shell to automate
Perl module installations from CPAN.

They allow to skip installations, answering questions with Expect,
jump to alternative versions, patch before building and many more
stuff. Basically everything you need to bootstrap CPAN dependencies
completely unattended, e.g. for Smoke Testing.

## SEE ALSO

* [CPAN distroprefs manual](http://search.cpan.org/~andk/CPAN/lib/CPAN.pm#Configuration_for_individual_distributions_%28Distroprefs%29)
* [CPANTESTERS wiki](http://wiki.cpantesters.org/wiki/Distroprefs)
* 

## UNIFIED PROJECT STRUCTURE

Several people have already written such distroprefs. I try to track
them all here as git submodules.

The biggest archive is from ANDK, author of CPAN.pm.

Whenever I have too specific personal needs that do not fit into
ANDK's needs I write my own variant in subdir renormalist/.

I then use them by installing first the big collection from
"andk/cpanpm" and then overwrite a few with my own alternatives. I can
imagine other, more elaborate merge strategies.


## CONTRIBUTE

Feel free to contact me to be included here, either as submodule of
your existing repository or to maintain them directly here in your own
subdirectory.

## FUTURE

I can imagine to extend the project with scripts to deploy distroprefs
for different needs and maintain those scripts in the respective
subdirs, to suit your demanding taste.
