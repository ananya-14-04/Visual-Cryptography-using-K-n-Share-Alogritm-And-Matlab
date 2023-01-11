# Visual Cryptography using KN secret Sharing

In this project we take any image which is to be shared secretly. This image is encrypted using a key given by the user. Further, the encrypted image is divided into N different shares using K N Secret Sharing Algorithm. These N shares can be distributed but, the end user needs only K of these shares to generate the original image. After the original image is generated it is still in encrypted form. The key which is used to encrypt the image originally is now required again to decrypt it, thus providing an additional level of security.

## Installation <a name='installation'></a>

### Prerequisites <a name='prerequisites'></a>

1. Matlab 2022a or later

### Using Matlab 2015a <a name='using-matlab-2015a'></a>
<pre>
1. Copy all matlab files in a folder to your computer
2. Open Matlab 2015a
3. Change matlab's current path to the folder  
4. Open matlab and using the matlab app designer open the file encryptgui.m and run it to encrypt the image
5. follow the UI 
</pre>

### Algorithms Used <a name='algo'></a>

Implementing  visual cryptographic algorithm namely,
1. KN Sharing Scheme for colored images


## Applications <a name='applications'></a>
Following are some of the areas in which our project can be helpful -

• DISTRIBUTED SYSTEMS
Suppose we have N distributed servers. Traditionally if we store a file in only one
server, there is a high risk that if it breaks or get hacked, all of our data will be
lost. So we would like to store our information in a distributed manner, with each
server storing a part of the information. We can encrypt and break our data into N
different parts with each part going into a server. Even if N − K servers are broken,
we can still generate our original data using the K alive servers.

• DATA TRANSFER SECURITY
It is obvious that transferring our data through N channels is more secure than
transferring all of it through one channel. We can use the above algorithm to
encrypt and break data into N different parts and transfer the data simultaneously
through N channels. End user can get K shares and ignore the other N − K shares.




## Contributers <a name='contributers'></a>
* Ananya Chopra
* Vivek Arora
* Drishtant Maurya
