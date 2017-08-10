## Yeast Network Repository

We have two sources of PWMs: 
* YeTFaSCo: database of evaluated yeast transcription factor sequence specificities (link (http://yetfasco.ccbr.utoronto.ca/downloads.php)) 
	* The parser stored in notebook (yetfascopwm_to_beeml) puts these PWMs in beeml format
	* MEME Suite tool beeml2meme converts this file to meme format
* Gordan et al paper: (link (https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3334620/))
	* PWMs in uniprobe format
	* MEME Suite tool uniprobe2meme converts this file to meme format
