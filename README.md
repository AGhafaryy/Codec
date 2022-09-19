# Codec
An encoder/decoder application, that implements A5, RC4, AES and DES algorithms.
The Application will take some time to open for the 
first time.
In RC4 decryption: -If cipher text is XXXXXXXX in hex
		    then write as XX XX XX XX
		   -If cipher text is XXXXXXXXX in hex
		    then write as XX XX XX XX X 
		           not as 0X XX XX XX XX
In A5 Encyrption: -Frame # must be 22 bits
		  -Key must be 64 bits
                  -Message can be up to 228 bits
Have Fun :)
