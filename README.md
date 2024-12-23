# Image-Crypt-Information-Security
Image encryption and decryption tool
  The aim of this project is to construct a Python-based tool for image encryption and decryption. This tool uses the XOR logic for both encryption and decryption, and it provides a user-friendly graphical user interface (GUI) developed with Tkinter. The encrypted images can be safely transferred to another user, who can then decrypt them with the same project, the ensuring secure image transmission between users.  The aim of this project is to construct a Python-based tool for image encryption and decryption. This tool uses the XOR logic for both encryption and decryption, and it provides a user-friendly graphical user interface (GUI) developed with Tkinter. The encrypted images can be safely transferred to another user, who can then decrypt them with the same project, the ensuring secure image transmission between users.
  . Key Features
•	Image Encryption and Decryption:
  The tool encrypts and decrypts pictures with XOR logic. The user enters a unique encryption and decryption key, ensuring that only users with the correct key can access the original image.
•	GUI for Easy Usage:
  The project has an easy-to-use graphical user interface (GUI) that allows users to encrypt and decrypt photos without the need for command-line interaction.
•	File Selection:
  Using a file dialog box, the tool enables users to choose which picture files to encrypt or decrypt, making the entire procedure straightforward.
•	Error Handling:
To handle standard issues like choosing the wrong file or using the wrong key to decrypt, the tool has error handling built in.
XOR Encryption Algorithm
          XOR (exclusive OR) is a simple binary operation used for encryption and decryption. In this project, XOR is used to modify the bytes of an image file, based on the provided key. The encryption and decryption process is the same because XOR is a reversible operation: applying the same XOR operation with the same key on an already XOR-ed byte results in the original value.

