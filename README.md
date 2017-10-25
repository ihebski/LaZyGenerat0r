# LaZyGenerat0r
lazy gen is python script that generate wordlist based on companies names,used basically for WPA/WPA2 bruteforcing attack .

# Raison to write such a script

During a long wireless pentesting exercises for multiple company , I noticed that the availble wordlists are always failed against the customized passwords set by the company ,In the most cases ,passphrase includes the company name, date and sometimes a symble .What if we generate a list that includes this one .

# How it works

Easy and nothing special :p 
possible generated strings 

lowercase+date
lowercase+symble+date
lowercase+date+symble

uppercase+date
uppercase+symble+date
uppercase+date+symble

## Exemple

company2014
company*2014
compay2014*

COMPANY2014
COMPANY2014
COMPANY*2014
COMPANY2014*


Company2014
Company*2014
Compay2014*
