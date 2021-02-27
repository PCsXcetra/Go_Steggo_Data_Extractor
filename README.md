# Go_Steggo_Data_Extractor


Tool to extract data from pixels of a Go encoded picture file.

Twitter reference  https://twitter.com/c3rb3ru5d3d53c/status/1365715825320226820

Extracted Shellcode https://bazaar.abuse.ch/sample/011ffbf555965f79fa9876f8240e0779f8ace46e4fc02f9f5b37239069a6cb55/

Go Library used to encode picture file .https://github.com/auyer/steganography

Note: The first 4 bytes of the extracted data appears to be the length of the "message text"
      The remainder may just be garbage.
      
How to Use: Just select the suspected encoded picture file click "Get Pixel Data" and then when it is done, copy paste to a hex editor.


Note: this is doing some string manipulation so very large files could take some time to process.

Needs to be done in bytes and written to a file instead of a text box for large files.

password is "clean"
