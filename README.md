**Project Overview**

This project is a simple password manager that securely stores and manages user passwords.
* It uses AES-256 encryption to protect the passwords.
* The master password is hashed using SHA-256 and stored securely.

🎯** Main Features**

✅ Set and Verify Master Password

✅ Add and Retrieve Passwords

✅ Encrypt and Decrypt Passwords using AES-256

✅ Generate Strong Random Passwords

✅ Simple Web Interface using Gradio


🛠️** Technologies Used**
* Python 3.13.2
* Google Colab
* Libraries:
	* pycryptodome – Encryption and decryption
	* gradio – Web-based interface
	* hashlib – Hashing the master password
	* json – Storing passwords securely

📂 **Project Files**

/password-manager-colab/

├── master_password.json        # Stores master password hash

├── passwords.json              # Stores encrypted passwords

├── main.ipynb                  # Main Colab notebook

└── README.md                   # Project documentation

📚 **How to Run the Project**
📌** Step 1: Open the Colab Notebook**
1. Open Google Colab.
2. Upload main.ipynb to Colab.

📌 **Step 2: Install Required Libraries
Run these commands in Colab:**

!pip install pycryptodome
!pip install gradio

📌 **Step 3: Run the Notebook**
* Open main.ipynb in Colab.
* Run all the cells to launch the password manager.
* The Gradio interface will open in a new tab.

📧 **Contact Information**
* Author: Dang Minh Nhan Ho
* 📩 Email: dho@lakeheadu.ca
