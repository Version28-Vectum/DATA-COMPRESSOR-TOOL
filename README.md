# DATA-COMPRESSOR-TOOL

COMPANY : CODTECH IT SOLUTIONS

NAME : VASU PATHAK 

INTERN ID : CT04DF1007

DOMAIN : C PROGRAMMING

DURATION : 4 WEEKS

MENTOR NAME : NEELA SANTHOSH KUMAR

As part of the CodTech Internship, this task required the implementation of a basic data compression tool using the Run-Length Encoding (RLE) algorithm. Data compression is a crucial concept in computer science and software development, aimed at reducing file size for efficient storage and transmission. This task was designed to familiarize us with fundamental compression logic through hands-on implementation.



Objective

The main objective was to write a program that performs Run-Length Encoding, which is one of the simplest forms of lossless data compression. It replaces sequences of repeated characters (or elements) with a single character followed by the count of repetitions. For example, the string AAAABBBCCDAA gets compressed to 4A3B2C1D2A.



Working of Run-Length Encoding

1. Traverse the input string or data.


2. Count the number of consecutive repeated characters.


3. Replace that sequence with the character followed by its count.


4. Store or print the encoded result.



Example:

Input: WWWWAAADDDCCCC

Output: 4W3A3D4C


This method is especially efficient when the data has many repeated characters, like in image data or simple text patterns.



Tools and Resources Used

To complete this task efficiently, I utilized a mix of resources for both understanding and debugging:

YouTube: To visually understand how the RLE algorithm works in real-world examples and animations.

ChatGPT: For logic structuring, syntax clarification, and optimization suggestions in C/C++.

Grok AI: For real-time code correction, error resolution, and improving the modularity of the program.


These tools helped me avoid common logical bugs and ensured that the code followed best practices in terms of readability and performance.



Applications of Run-Length Encoding

Image Compression: Used in BMP, TIFF, and some fax encoding formats.

Text Compression: In scenarios with long repeated characters like simple logs or pattern-heavy files.

Video and Audio: Some legacy or lightweight compression formats may use RLE for simple frames.

Data Transmission: Reduces size in communication systems where bandwidth is limited.


Although RLE is not optimal for all data types (e.g., random or non-repetitive data), it's widely used in specific cases where simplicity and speed matter more than extreme compression efficiency.



Challenges Faced

1. Edge Case Handling: Ensuring that single characters or no repetition is handled correctly.


2. Input/Output Format: Proper formatting for clarity in both encoding and decoding.


3. Modularity: Designing the code to allow for easy conversion into a more advanced compression format later.


4. Testing: Verifying the correctness of the output using different types of inputs.



Conclusion

This task has helped me understand how even a basic algorithm like RLE can offer powerful results in real-world data handling. It sharpened my skills in data manipulation, compression logic, and code modularity. With support from YouTube, ChatGPT, and Grok AI, I was able to complete this task efficiently and with a deeper understanding of the importance of compression in computer science.
OUTPUT
![Image](https://github.com/user-attachments/assets/96ce5914-b815-4d11-b6a8-3d065a3f3e6f)
