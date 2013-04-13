node-bitcoin-tools
===================

Just playing with the bitcoin API and NodeJS, crafting little command line tools
wrapping the bitcoind API. 

Copyright (C) 2013 Laurent Eschenauer <laurent@eschenauer.be>

Bitsign: Sign a message with a bitcoin key
---------------------------------

In this example, I sign the string "Hello, World" with my key labeled 'mytestkey' in my wallet.
As you can see, the command prompts for the passphrase, it is used only within the timeframe 
of the transaction and immediately forgotten.

    ./sign.js mytestkey "Hello, World"
    Passphrase: 
    INqRSWXtY5qYbTCRIQIqhRB3hkO0rQqFutUzgposZ/45kTHUHLx3UfztVdY33qMIb/BH3UBV3Q6Mhg9eX5/ghQI=

Dependencies
------------

If you are using this from source, you can install the dependencies using npm from the root of the source folder:
    npm install 

License
-------

The MIT License

Copyright (c) 2013 Laurent Eschenauer <laurent@eschenauer.be>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
