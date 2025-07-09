# Text File Compressor

A simple and efficient **text file compressor** based on the **Huffman Coding** algorithm, written in C++.

---

##  Algorithm

This compressor uses **Huffman Coding**, a lossless data compression algorithm that assigns shorter binary codes to more frequent characters, reducing the overall file size.

---

##  Requirements

- C++17 or higher
- A terminal or command-line interface

---

##  How to Use?

1. **Open a terminal** at the directory where `Huffman.cpp` is located.

2. **Compile the program**:

   ```bash
   g++ Huffman.cpp -o main
   ./Huffman.exe inputfile_name outputfile_name
