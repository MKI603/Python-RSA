# Python-RSA
use python3 to realize RSA Encrypt

## Usage

1.First you should have module **Crypto**, however, you may have some problem when install it.

use

```
python3 -m pip install pycrypto
```

you may see when you run

```
ModuleNotFoundError:No module named "Crypto"
```

if you see this, you’d better go to the index where you python packet like  **xxxxx\Python37\Lib\site-packages**

then change the packages **crypto** to **Crypto**

done.

2.change the c to your text

```
if __name__ == "__main__":
    c = "Hi,this is RSA!"
    RSA(c)
```

then just run it 

3.

```
    p = number.getPrime(256, os.urandom)   

    q = number.getPrime(256, os.urandom) 
```

change the first number of function **number.getPrime** to change the length of p and q 

longer the P/Q is , the harder is the encrypt, for those who don’t have secret key (N,e)
