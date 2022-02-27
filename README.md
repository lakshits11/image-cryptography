# IMAGE CRYPTOGRAPHY
  

<!-- ![imgcrypto](https://user-images.githubusercontent.com/54276661/120526625-05686c00-c3f7-11eb-9102-9274ec67b2e1.PNG) -->


![poster](./poster.png)



Hide secret texts/messages inside an image! And  you can also optionally encrypt your texts with a password using AES-256 encryption before encoding into the image.


Inspired from this [Medium post](https://medium.com/better-programming/image-steganography-using-python-2250896e48b9)

 

## Installation

You can install the all requirements from **requirements.txt** by using pip.

`pip install -r requirements.txt` 

## Usage

`python main.py`

![1](./img-crypto-1.png)

**Encode**

- Choose *Encode* in the options menu

- Enter the image path (with extension)

- Enter the message to be hidden

- Choose a password to encrypt with AES-256 (optional)
  
<em>The image is encoded and saved as a ***PNG*** file.</em>

  Suppose the image to be encoded is this:

 ![sample.jpg](https://images.unsplash.com/photo-1468276311594-df7cb65d8df6?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=750&q=80)

> Image Credits : [Kristopher Roller](https://unsplash.com/@krisroller)

<br>

After encoding, image looks like this:

![sample-enc.png](https://user-images.githubusercontent.com/54276661/120529596-46ae4b00-c3fa-11eb-82fe-3938dd0739aa.png)

***Visually, no change seen. The size change is just seen because I had to compress images to show in readme. Originally no change seen in images.***

**Decode**

![decoding](./img-crypto-2.png)

- Choose *Decode* from the menu

- Enter the path of the encoded image (with extension) and type in the password to decrypt (leave empty if no password was used)
  

The decoded text will be displayed on the terminal.
