# Caesar Cipher CLI Tool

## Overview

The Caesar Cipher CLI Tool is a command-line program designed to encrypt and decrypt messages using the Caesar cipher. This simple substitution cipher involves shifting each letter in the plaintext by a fixed number of positions down the alphabet.

## Features

- **Encryption**: Securely encode messages with a specified shift value.
- **Decryption**: Reverse the encryption process to retrieve the original message.
- **Flexible Shift Value**: Choose the number of positions to shift the alphabet.

## Usage

To use the Caesar Cipher CLI Tool, follow these steps:

1. **Installation**:

   - Ensure you have Rust and Cargo installed on your system. If not, download and install them from the official Rust website: [https://www.rust-lang.org/tools/install](https://www.rust-lang.org/tools/install).

   - Clone this repository and navigate to its directory:

     ```bash
     git clone https://github.com/your-username/caesar-cipher-cli.git
     cd caesar-cipher-cli
     ```

   - Build the tool by running:

     ```bash
     cargo build --release
     ```

2. **Encrypting a Message**:

   - Use the following command structure:

     ```bash
     cargo run --message "Your message" --encrypt --shift <SHIFT_VALUE> --output-format <FORMAT>
     ```

     - `--encrypt`: Specify encryption mode.
     - `--shift <SHIFT_VALUE>`: Define the number of positions to shift each letter in the alphabet.
     - `--output-format <FORMAT>`: Choose between plain or hexadecimal output format (default is plain).

3. **Decrypting a Message**:

   - To decrypt a message, use the `--decrypt` flag along with the `--shift` argument to specify the shift value:

     ```bash
     cargo run --message "Encrypted message" --decrypt --shift <SHIFT_VALUE>
     ```

![image](https://github.com/midspooj/pb226-mini-project-7/assets/142264378/abafa9e7-ec12-44e9-9401-aabbb84bdc1e)

