# encryptie

https://keybase.io/triplesec/ gebruikt in Javascript em HTML

TripleSec is gebruikt om de tekst te versleutelen (de versleutelde teksts wordt opgeslagen in het outputfield, zodat je kunt zien dat het ook daadwerkelijk versleuteld is). Als key voor het versleuten wordt de gebruikersnaam en wachtwoord aan elkaar geplakt en dus alleen die combinatie kan het weer ontsleutelen.

TripleSec is a simple, triple-paranoid, symmetric encryption library for Python, Node.js, Go, C#, and the browser. It encrypts data with Salsa 20, AES, and Twofish, so that a compromise of one or two of the ciphers will not expose the secret.
Of course, encryption is only part of the story. TripleSec also: derives keys with scrypt to defend against password-cracking and rainbow tables; authenticates with HMAC to protect against adaptive chosen-ciphertext attacks; and in the JavaScript version supplements the native entropy sources for fear they are weak.
