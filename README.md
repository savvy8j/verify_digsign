# verify_digsign
<br>
#Cryptography_project
<br>
Text file is given to us and after issuing certificate ,details are stored in a text file . 
<br>
In the USER's side :-
<br>
->In Hash_generator,we put details of the user and generate the hash
->In final_verification, we enter the hash value, signature and use the public key to decrypt the encrypted hash and verify the new hash and compare with original hash . If its valid,we can say that the digital signature is Valid ,else Valid
