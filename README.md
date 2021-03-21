### ----------------------------- Burp-Suite Tutorial --------------------------------------------- 


# What is Burp -Suite ?

Burp Suite, a framework of web application pentesting tools, is widely regarded as the de facto tool to use when performing web app testing.Simply ,  a Burp Suite is Web pentesting tools that is use for intercept web data as a proxy server . 

### Installation :

Go to this site ( https://portswigger.net/burp/communitydownload ) and  Download it for Windows user . 

### Note : On Kali Linux  Burp suite is installed in default .


# Set up proxy server and CA Certified :

Before we can start using our new installation (or preinstalled) Burp Suite, we'll have to fix a certificate warning. We need to install a CA certificate as BurpSuite acts as a proxy between your browser and sending it through the internet - It allows the BurpSuite Application to read and send on HTTPS data.

Download CA Certificate using http://burp  OR  http://localhost:8080
 

Use  Foxy Proxy for set up proxy server :

                                                             Proxy ip :127.0.0.1
               
                                                             Port :8080


# Overviewed Of Burp-Suite Features :

### Proxy : 
           What allows us to funnel traffic through Burp Suite for further analysis
### Target :
           How we set the scope of our project. We can also use this to effectively create a site map of the application we are testing.
### Intruder : 
             Incredibly powerful tool for everything from field fuzzing to credential stuffing and more
### Repeater :
             Allows us to 'repeat' requests that have previously been made with or without modification. Often used in a precursor step to fuzzing with the aforementioned Intruder
### Sequencer : 
              Analyzes the 'randomness' present in parts of the web app which are intended to be unpredictable. This is commonly used for testing session cookies
### Decoder : 
            As the name suggests, Decoder is a tool that allows us to perform various transforms on pieces of data. These transforms vary from decoding/encoding to various bases or URL encoding.
### Comparer : 
             Comparer as you might have guessed is a tool we can use to compare different responses or other pieces of data such as site maps or proxy histories (awesome for access control issue testing). This is very similar to the Linux tool diff.
### Extender : 
             Similar to adding mods to a game like Minecraft, Extender allows us to add components such as tool integrations, additional scan definitions, and more!
### Scanner :
            Automated web vulnerability scanner that can highlight areas of the application for further manual investigation or possible exploitation with another section of Burp. This feature, while not in the community edition of Burp Suite, is still a key facet of performing a web application test.


