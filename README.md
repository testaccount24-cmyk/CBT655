# CBT655
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 655 is from David Kopischke and contains REXX execs to    *   FILE 655
//*           help you clean up your MVS catalogs.                  *   FILE 655
//*                                                                 *   FILE 655
//*         As of this writing, we could not locate the author,     *   FILE 655
//*         David G. Kopischke.  (March 2021)                       *   FILE 655
//*                                                                 *   FILE 655
//*  Note:  There was a small fix to CATCLR3 from Xiayang.          *   FILE 655
//*         See member $$NOTE02 for details.                        *   FILE 655
//*                                                                 *   FILE 655
//*           email:  xiayang <13916076262@139.com>                 *   FILE 655
//*                                                                 *   FILE 655
//*  Description of the CATCLR3 exec:                               *   FILE 655
//*                                                                 *   FILE 655
//*      This exec can function very similarly to the               *   FILE 655
//*      RCNVTCAT program from CBT File 542 or File 970,            *   FILE 655
//*      but it has additional functionality.  The command:         *   FILE 655
//*                                                                 *   FILE 655
//*      TSO CATCLR3 T catalog.name                                 *   FILE 655
//*                                                                 *   FILE 655
//*      will produce output similar to RCNVTCAT, but               *   FILE 655
//*                                                                 *   FILE 655
//*      TSO CATCLR3 D catalog.name                                 *   FILE 655
//*                                                                 *   FILE 655
//*      will produce a list of all datasets cataloged in the       *   FILE 655
//*      catalog, but which either don't exist, or which are        *   FILE 655
//*      cataloged to a volume that is unavailable.  This list      *   FILE 655
//*      of dataset names is surrounded by:                         *   FILE 655
//*                                                                 *   FILE 655
//*           DELETE  dsname  NOSCRATCH                             *   FILE 655
//*                                                                 *   FILE 655
//*      statements for easy uncataloging, in batch or in           *   FILE 655
//*      the foreground.                                            *   FILE 655
//*                                                                 *   FILE 655
```
