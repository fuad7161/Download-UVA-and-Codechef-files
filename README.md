# Download-UVA-files
Download all the problems of UVA Online Judge from its website  
There is a collection of all problems in pdf format available in this [link](https://uva.onlinejudge.org/index.php?option=com_onlinejudge&Itemid=8&category=1)

	The problems of UVA online judge are structured in various folders and where numbered sequentially. The main aim of this small python script is to successfully download all the problem files in pdf format in our computer hard drive.

### Motivation

>I was quite interested in competitive programming and wanted to solve as many 
>problems of UVA to enhance my coding skills and become a  better programmer. 
>So a thought crossed my mind that why not download all the problems available in UVA 
>in pdf format so that I would be able to at least think and read problems even in off-line mode.
>Recently I had learnt python and realised that it has various libraries for helping
>me achieve the same

License
----

GNU GENERAL PUBLIC LICENSE 2.0

### Version 
1.0.0

### Requirements 

* **Python 2.7.4** must be installed in the machine to run this script.
* **Optional**- Python should be added in your path or it should be set 
as environment variable 

### Running the script 
One can simply run the following command in the prompt to start downloading each of the pdf files:

```sh
$ python download.py
```

Moreover after completion of download you will be notified and you can start solving the 
UVA problems. 

The following are the features:

* The pdf files will be downloaded in slots of folders like 1-100 files in a single folder, 2- 100 in another problem and so on....
* Use of urlib2 of python to open each of the pdf files individually so that we can read them.	
* Informing about each successful download of individual pdf file, each directory download is completed as well as when the total download is also completed.
* Generic URL of all pdf files: http://uva.onlinejudge.org/external/<jthfolder>/<ithfile>.pdf 



### Testing Environment 

It was tested on **Windows 8.1 as well as Linux (Ubuntu 14.04)** operating system with **python 2.7.4**  installed in the machine.
