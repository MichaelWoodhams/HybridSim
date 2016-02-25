# HybridSim
The HybridSim program plus manual.

Some source code is LGPL (mostly PAL and BioJava), some is 'unlicense' (effectively public domain), occasional snippets 
are CC-BY-SA (code copied from stackoverflow.com or stackexchange.com.)

The program is described in the paper "Modelling Hybrid Evolution" by Michael Woodhams, Peter Lockhart and Barbara Holland. (No publication details available at time of writing this README.) 

Included in this repository are the program as a jar file, the manual, and some sample input files.

hybridsim319.jar: the executable (Java jar file)
HybridSim_manual.pdf: The manual
examples.tgz: Example input files
hybridsim_source.tgz: All the source in one bundle. (Collected for your convenience from sources listed below.) (Some third party libraries supplied as jar files - you can find source at their websites.)
hybridsim_manual_source.tgz: source (*.bib, *.lyx) of the manual, plus a *.tex export of the *.lyx file.

The source code is collected from:

https://github.com/MichaelWoodhams/ABC

https://github.com/MichaelWoodhams/palExtensions

https://github.com/MichaelWoodhams/biojavaExtensions

https://github.com/MichaelWoodhams/HybridSeq

https://github.com/MichaelWoodhams/HybridStats

https://github.com/MichaelWoodhams/pal-1.5.1

https://github.com/MichaelWoodhams/mdwUtils

https://github.com/biojava/biojava-legacy (version 1.8.4)

Sorry about the fragmented source code. Partly this is separating code which may be reusable over many projects while not adding potentially unnecessary dependencies (mdwUtils, palExtensions, biojavaExtensions) and partly it is because when you write research code, often you don't know when you start where you will end up (HybridSeq, HybridStats, ABC.) 
