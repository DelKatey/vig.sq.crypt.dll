## Introduction

This repository contains all the files needed to compile a working version of the **vigenere_square_cipher.dll**. This DLL can then be used in other projects without needing to possibly make your code look messier with the source code used for the DLL.

- If you're looking for the GUI version, this is not it. You can find that [here](https://github.com/DelKatey/vig.sq.crypt.gui).
- If you're looking for the command-line version, this is also not it. You can find that [here](https://github.com/DelKatey/vig.sq.crypt).

## Usage Example

An example of how you can call the DLL to help you encrypt a plaintext message is:

    resultTextBox.Text = vigenere_square_cipher_dll.VigenereSquareCipher.Encrypt(inputTextBox.Text, keyTextBox.Text);
	
An example of how you can call the DLL to help you decrypt a ciphertext message is:

    resultTextBox.Text = vigenere_square_cipher_dll.VigenereSquareCipher.Decrypt(inputTextBox.Text, keyTextBox.Text);
	
## How this came to be

Out of boredom, I decided to implement what I learnt in a module of a course I was taking, in C#, and as a quick challenge to myself.

## Installation

This was coded with Visual Studio 2010, using .NET Framework 3.5, and should thus be usable with any version of Visual Studio 2010 and up, as well as SharpDevelop. Compatibility wise, it should present no challenges in being converted to use a newer version of the .NET Framework.

![.NET Framework 4](https://public-dm2306.files.1drv.com/y3pXtgOa3VAq1KJC17mOmtDEPHusKHAB9-7yuC54hI8Y09iMHkj7cSTqPzm-c2hu7OPOEI-ixow1bGvhOElUZRiFtFmgt8BNExvufrWkuXzyzmYY1WE-v_-1nYVuGdbqrPq/NET-Frmwrk_h_rgb.png?rdrts=142979546)

## License

This project is licensed under the [MIT License](LICENSE.md).