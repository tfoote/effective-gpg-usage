# Goals

My goals are to be able to effectively use GPG to enable secure encrypted communication as well as having the ability to effectively digitally sign things. 



## Approach

Although there are many effective ways to use GPG I will choose to one which matches the right balance of security vs practicality for my purposes.
To this end I plan to use a master key stored in an encrypted USB key, with subkeys also on encrypted USB keys for day to day usage. 
The master key will provide identity and will be required for signing.
The day to day keys can be used for encryption and signing things as well, but can be revoked while maintaining the identity. 
