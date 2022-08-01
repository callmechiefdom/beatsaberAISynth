# beatsaberAISynth
+ [data prepared](https://github.com/callmechiefdom/BeatsaberMapsAnalysis)
	+ ./datasetAll.json
	+ ./glove/malody.txt
+ cd glove && make
+ ./create_glove_embedding.sh
	+ => ./glove/vocab.txt
	+ => ./glove/vectors.txt
+ train
	+ seq2seq