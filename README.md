# skew-correction-KYC-Documents
At present, our world is progressing rapidly towards process automation with the help of AI technologies, one of which is used to automate ID card information extraction. In this process, documents are being digitalized and information is extracted and stored from a text extracted using Optical Character Recognition, cutting edge technology for text extraction. The text extraction accuracy is observed to be higher in zero skewed images with text in black and white background, consequently, we need to eliminate the skewness in the document uploaded.
 
There are different skew correction methods available for text images having black text over the white background as shown in fig1. These methods sometimes do not work for KYC Documents like voter, passport, Driving licence etc, because they contain other information such as pictures, signature, QR codes, watermarks etc. So, In this post, we will discuss my approach of solving the skew correction for the passport as shown in fig2.

![text skew](https://user-images.githubusercontent.com/71541898/133197675-9ab27ae9-f100-4aa6-8615-661c62e2d586.jpg)![passport_front - Copy](https://user-images.githubusercontent.com/71541898/133197797-5ce842df-f506-44dc-993a-265e1f93a770.jpg)
fig1: skewed text images at different angles                      fig 2: Passport sample for skew correction
