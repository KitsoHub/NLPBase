Project: NCHLT Text IV

Type: w2v-Skipgram
Language: Setswana (tn)
Date: 2023-02-28
Version: 1.0

Description: 
	Static word embeddings for the Skipgram flavour of the word2vec (w2v) architecture (Mikolov et al., 2013).
	The embedding provides real-valued vector representations for Setswana text.

Model:
	Vocab size: 18,379
	Embedding dimensions: 400

Training data sources:
	The model is trained on a combination of data sources, including:
		- NCHLT Setswana Text Corpora
		- Autshumato Setswana Monolingual corpus
		- Leipzig Corpus Collection
		- Common Crawl
	as well as data internally available at CTexT which is not available for distribution.
	All data was language identified with the NCHLT Web Services Language Identifier (Puttkammer et al., 2019) and duplicate paragraphs across the entire set were removed, since at least four of the corpora source data from the web, with substantial overlap.

Training corpus:
	Paragraphs: 515,961
	Token count: 14,518,437

Usage:
	Example code for loading the w2v-Skipgram model is available from https://github.com/reiselen/TrainEmbeddings/scripts
	More details on the w2v architecture is available from https://github.com/RaRe-Technologies/gensim

Reference:
	Mikolov, Tomáš, Kai Chen, Greg Corrado & Jeffrey Dean. 2013. Efficient estimation of word representations in vector space. International Conference on Learning Representations 2013. Scottsdale, AZ.
	Puttkammer, Martin J., Roald Eiselen, Justin Hocking & Frederik Koen. 2018. NLP Web Services for Resource-Scarce Languages. 56th Annual Meeting of the Association for Computational Linguistics 2018. Melbourne, Australia: Association for Computational Linguistics.
_________________________________________________________________________________
Licence for distribution: Creative Commons Attribution 4.0 International
 
URL: http://creativecommons.org/licenses/by/4.0/
 
Attribute work to: 
	CTexT® (Centre for Text Technology, North-West University), South Africa; 
	Department of Sport, Arts and Culture, South Africa.
Attribute work to URL:	
	http://humanities.nwu.ac.za/ctext
	http://www.dac.gov.za
