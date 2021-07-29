# IBM-Watson-to-convert-speech-to-text-and-text-to-speech-Using-python-language
=========================================
 Watson Streaming Speech to Text Example
=========================================

The following is an example of using Watson to real time transcribe                                                                                     
from Speech to Text using the websockets streaming API.                                                                                                                      

You'll need to sign up for the `Watson STT service`_. ,                                                                                               
IBM Cloud accounts get 500 minutes / month free.

In order to connect to the Watson streaming server you need an API Key, and to                                                                                              
specify which region your speech to text service was provisioned in (there are                                                                                                  
different gateways per region). You can find these on your IBM Cloud console                                                                                                 
for the service you have added.                                                                                                      
                                                                                                      
Expected Output
===============

Once you run transcribe.py with a timeout value (-t) you'll get both                                                                                                      
incremental output as data comes back, as well as a final stitching of
things together. The output will look something like this.

python transcribe.py -t 10                                                                                                                    
* recording                                                                                                                   
hi                                                                                                                  
hi                                                                                                                   
hi                                                                                                                   
hi                                                                                                                   
hi                                                                                                                   
hi                                                                                                                   
hi                                                                                                                   
hi no                                                                                                                   
hi no                                                                                                                   
hi now                                                                                                                   
hi now                                                                                                                   
hi now                                                                                                                   
hi now                                                                                                                   
hi now                                                                                                                   
hi now I'm                                                                                                                    
hi now I'm                                                                                                                     
hi now I'm do                                                                                                                     
hi now I'm doing                                                                                                                    
hi now I'm doing                                                                                                                    
hi now I'm doing                                                                                                                    
hi now I'm doing                                                                                                                    
hi now I'm doing                                                                                                                    
hi now I'm doing a test                                                                                                     
hi now I'm doing a test                                                                                                             
hi now I'm doing a test to                                                                                                          
hi now I'm doing a test to                                                                                                       
hi now I'm doing a test to                                                                                                  
hi now I'm doing a test two can                                                                                                       
hi now I'm doing a test to confirm                                                                                                       
hi now I'm doing a test to confirm                                                                                                       
hi now I'm doing a test to convert                                                                                                       
hi now I'm doing a test to convert                                                                                                       
hi now I'm doing a test to convert                                                                                                       
hi now I'm doing a test to converting                                                                                                  
hi now I'm doing a test to converting                                                                                                 
hi now I'm doing a test to converting to                                                                                                       
hi now I'm doing a test to converting to speak                                                                                               
hi now I'm doing a test to converting speech                                                                                                       
hi now I'm doing a test to converting speech                                                                                                       
hi now I'm doing a test to converting speech to                                                                                                  
hi now I'm doing a test to converting speech to                                                                                                       
hi now I'm doing a test to converting speech to                                                                                                       
hi now I'm doing a test to converting speech to                                                                                                       
hi now I'm doing a test to converting speech to text                                                                                                  
hi now I'm doing a test to converting speech to text                                                                                                       
hi now I'm doing a test to converting speech to text                                                                                                      
hi now I'm doing a test to converting speech to text                                                                                                      
hi now I'm doing a test to converting speech to text                                                                                                      
hi now I'm doing a test to converting speech to text                                                                                                      
hi now I'm doing a test to converting speech to text                                                                                                      
hi now I'm doing a test to converting speech to text                                                                                                      
hi now I'm doing a test to converting speech to text                                                                                                      
hi now I'm doing a test to converting speech to text                                                                                                      
* done recording                                                                                                       

=========================================                                                                                                                                    
    Text To Speech
=========================================                                                                                                                              

You'll need to sign up for the `Watson STT service`_. ,                                                                                            
IBM Cloud accounts get 500 minutes / month free.                                                                                                      

In order to connect to the Watson streaming server you need an API Key, and URL and to                                                                                     
specify which region your text to speech service was provisioned in (there are                                                                                                      
different gateways per region). You can find these on your IBM Cloud console for the service you have added.                                                                                                      
