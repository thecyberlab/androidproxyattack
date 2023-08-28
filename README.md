This is the repository containing the data for paper:
Animesh Kar, Natalia Stakhanova "Exploiting Android Browsers", Procedings of the 22nd International Conference on Cryptology and Network Security (CANS 2023).


- The files contained in var_www_html folder needs to have some kind of server setup like apache or nginx
- make the server https using self-signed certficate or host them in real server with https, certain features like network information, battery, ram, location, camera access, microphone access requires "https"
- for accessing system apps, use "tel.html" file, no requirement of https. Change the uri in the apk. 
