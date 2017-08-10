## Yeast Network Repository

We have two sources of PWMs: 
* [YeTFaSCo](http://yetfasco.ccbr.utoronto.ca/downloads.php) : database of evaluated yeast transcription factor sequence specificities 
	* The parser stored in notebook (yetfascopwm_to_beeml) puts these PWMs in beeml format
	* MEME Suite tool [beeml2meme](http://meme-suite.org/doc/beeml2meme.html) converts this file to meme format
* Gordan et al [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3334620/)
	* PWMs in uniprobe format
	* MEME Suite tool [uniprobe2meme](http://meme-suite.org/doc/uniprobe2meme.html) converts this file to meme format
