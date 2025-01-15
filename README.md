# Digital Steganography in Java

## Overview

This Java-based digital steganography tool enables users to embed secret messages into image files (typically `.png` or `.bmp`) using the least significant bit (LSB) method. It allows encoding and decoding of hidden information within image pixels, providing a simple way to hide text within an image.

## Features

- **Encoding**: Hide a message inside an image using the LSB technique.
- **Decoding**: Extract the hidden message from the image.
- **Support for BMP/PNG**: The tool works with bitmap and PNG image formats.
- **User-friendly**: Command-line interface for easy usage.

## Technologies Used

- **Java 8+**: Programming language used for the implementation.
- **ImageIO**: To handle reading and writing image files in PNG and BMP formats.
- **Bitwise operations**: For encoding/decoding the secret messages.

## Getting Started

### Prerequisites

- JDK 8 or higher installed on your system.
- Basic understanding of Java and image processing.

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/digital-steganography-java.git
    ```

2. Navigate to the project directory:

    ```bash
    cd digital-steganography-java
    ```

3. Compile the Java files:

    ```bash
    javac Steganography.java
    ```

4. Run the program:

    ```bash
    java Steganography
    ```

