# Image-Compression
This project focuses on image compression using Huffman coding, a widely employed 
technique in data compression. The goal is to reduce the storage size of digital images while 
maintaining visual fidelity. The theoretical foundation involves calculating the frequency of 
pixel values in the image, building a Huffman tree based on this frequency information, and 
generating variable-length codes for efficient representation. The implemented algorithm 
iterates through each pixel in the image, counts the frequency of unique pixel values, and 
utilizes Huffman coding to create a compact representation of the image. The project also 
includes features such as displaying image dimensions, calculating compression ratios, and 
presenting sample data before and after compression. The theoretical framework is 
implemented in Python, utilizing libraries such as PIL for image processing. The project aims 
to provide a practical understanding of Huffman coding in image compression and its 
application to real-world scenarios.

# Work Flow
1. Reading Original Image: The original image is read using Image.open from the PIL library.  
The dimensions of the original image are printed. 
 
2. Huffman Coding and Compression: Huffman coding is applied to the original image data. 
The encoded data, compression ratio, and sample data before Huffman coding are printed. The 
codebook is written to the output file with a ".codebook" extension. 
 
3. Resizing the Image: The original image is resized to half of its dimensions using the resize 
method from PIL. The resized dimensions are printed. 
 
4. Compressed Image Summary: The dimensions and size of the compressed image (resized) 
are printed. 
 
5. Decompression: The dimensions and size of the compressed image (resized) are printed. 
 
6. Displaying Images: The show_image function is called to display the original image. 
 
7. Saving Resized Image as JPEG: The resized image is saved as a JPEG file with the same 
name as the output file and ".jpg" extension.

![image](https://github.com/user-attachments/assets/5071a8f9-c707-40eb-bfe7-b3fc421557a8)

# Output
![image](https://github.com/user-attachments/assets/b349231c-a208-49b1-afc0-e3a12db17afe)

![image](https://github.com/user-attachments/assets/386234ce-d6ba-416a-ab8b-a1e132f44c0d)




