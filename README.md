
# A Flask Server for an E Reader: Version 0.0.01
This is one of a few key programs in an EReader Document Processor. 

This is a really simple bodge to get a chrome and firefox extension to call a python script.

The easiest way I could get that to work was by making the extension send a post request to a local server. The local server would verify the post request, then call the python script, passing along the url of the page the python program. 

This design is surprisngly useful, and might be expanded for a bioinformatics/ncbi extension as well. 

### License
This server is open source [licensed under the MIT License](https://github.com/CrakeNotSnowman/ereader_Flask_Server/blob/master/LICENSE)
