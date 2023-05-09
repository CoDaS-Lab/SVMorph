The input files for the paper, "Modeling Substitution Errors in Spanish Morphology Learning". The files are formated to be used with the Fragment Grammars model as implelmented by (O’Donnell, 2015).

### Settings

The simulations reported in the paper are based on 10 runs of each file with random seeds. Below is an example for the command line used for j-th run of the i-th input file of a simulation with paremeter setting of: 

* sticky concentration = 1
* sticky distribution = 0.5
* Pitman-Yor a = 0.4
* Pitman-Yor b = 100
* 50 sweeps

../code/_opam/bin/bestpcfg -corpus-counts 50SP-$j-$i.counts.txt -corpus-sentences 50SP-$j-$i.forms.txt -pya 0.4 -pyb 100 -sticky-concen 1 -sticky-dist 0.5 -pi 1 -sweeps 50 -debug-file 50SP-$j-$i-a04-s05.FG-output-debug.txt -output-grammar 50SP-$j-$i-a04-s05.FG-output.txt -seed $s -start-symbol START


### How to cite

Barak, L., Fernandez, N., Feldman, N. H. & Shafto, P. (2023). Modeling Substitution Errors in Spanish Morphology Learning. 
In Proceedings of the Annual Meeting of the Cognitive Science Society (Vol. 45, No. 45).

O’Donnell, T. J. (2015). Productivity and reuse in language:
A theory of linguistic computation and storage. MIT Press.
