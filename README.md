ShadowBrokers Extracted files
===========

This repository is used to save extracted files of ShadowBrokers archives. I extracted them myself to be sure they weren't modified at all.
Original download link is at : [Shadow Brokers files](https://mega.nz/#!zEAU1AQL!oWJ63n-D6lCuCQ4AY0Cv_405hX8kn7MEsa1iLH5UjKU)

Here, you can find more about the [auction](https://medium.com/@shadowbrokerss/dont-forget-your-base-867d304a94b1) file and the released password

Extraction keys
-------

### Free archive
Password is : **theequationgroup**

You can decrypt it doing the following

~~~ bash
gpg --decrypt --output eqgrp-free-file.tar.xz eqgrp-free-file.tar.xz.gpg
~~~

Then extract it :

~~~ bash
tar xvf eqgrp-free-file.tar.xz -C Free/
~~~

### Auction archive
Password is : **CrDj"(;Va.\*NdlnzB9M?@K2)#>deB7m** (be careful, the original article containing the password : https://medium.com/@shadowbrokerss/dont-forget-your-base-867d304a94b1 encoded the quote : \" differently resulting in a wrong password. Be sure to fixe the quote or copy it from here.)

You can decrypt it doing the following

~~~ bash
gpg --decrypt --output eqgrp-auction-file.tar.xz eqgrp-auction-file.tar.xz.gpg
~~~

Then extract it :

~~~ bash
tar xvf eqgrp-auction-file.tar.xz -C Auction/
~~~

