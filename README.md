scoreGismu

==========

1. Install Perl

2. Put natlang words and frequencies into input.txt in format like
"siani 0.246117399315609 salti 0.213872071597789 salado 0.094630165833114 malix 0.090023690444854 lavanaiukt 0.084890760726507 labanakt 0.05672545406686 salion 0.051855751513556 salgado 0.048828639115557 ciokarai 0.03224532771782 saluni 0.028691760989734 saltsig 0.027375625164517 sali 0.024743353514083"
(the order of languages (ISO-names) is below)

3. run "perl scoreGismu.pl input.txt". But under Windows you may just run "scoreGismu.bat"

Be sure that AlgorithmDiff is installed.

On Linux:

perl scoreGismu.pl input.txt

==========
cmn	siani	0.246117399315609

eng	salti	0.213872071597789

spa	salado	0.094630165833114

ara	malix	0.090023690444854

hin	lavanaiukt	0.084890760726507

ben	labanakt	0.05672545406686

rus	salion	0.051855751513556

por	salgado	0.048828639115557

jap	ciokarai	0.03224532771782

pun	saluni	0.028691760989734

deu	saltsig	0.027375625164517

fra	sali	0.024743353514083
