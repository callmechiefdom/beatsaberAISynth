# beatsaberAISynth
+ data prepared
	+ ./datasetAll.json
	+ ./glove/malody.txt
+ cd glove && make
+ ./create_glove_embedding.sh
	+ => ./glove/vocab.txt
	+ => ./glove/vectors.txt
+ train
	+ seq2seq