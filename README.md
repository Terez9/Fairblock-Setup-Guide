# Fairblock Setup Guide

## Step 1: Clone the Repositories

First, clone both the fairyring library and the Fairblock.github.io documentation repository to your local machine.

Clone fairyring repository:

```
# Clone the fairyring repository
git clone https://github.com/Fairblock/fairyring.git
```
Clone Fairblock.github.io repository:

```
# Clone the Fairblock documentation website repository
git clone https://github.com/Fairblock/Fairblock.github.io.git
```

## Step 2: Install Dependencies for fairyring

Navigate to the fairyring directory and install any necessary dependencies. The fairyring library may have dependencies that need to be set up in order to run properly.

For example:
Navigate to the fairyring folder:

```
cd fairyring
```

Install required dependencies. This project likely uses Python, so use the following commands to install the dependencies. Ensure you have Python and pip installed:

```
# Install dependencies using pip (if there's a requirements file)
pip install -r requirements.txt
```

Alternatively, if the repository uses other package managers like poetry, follow the appropriate commands.

## Step 3: Explore and Run Cryptographic Functions

The fairyring repository provides a cryptographic library. After installing the dependencies, you can start using or modifying the cryptographic functions provided.

Here’s an example of how to use one of the encryption functions from the library:

Example code (assuming the structure of the library):

```
from fairyring.encryption import encrypt_message, decrypt_message


# Example usage of encryption
message = "Hello, Fairblock!"
public_key = "your_public_key_here"

# Encrypt the message
encrypted_message = encrypt_message(message, public_key)
print("Encrypted Message:", encrypted_message)

# Decrypt the message
private_key = "your_private_key_here"
decrypted_message = decrypt_message(encrypted_message, private_key)
print("Decrypted Message:", decrypted_message)
```

You’ll need to review the functions in the repository to adjust this code to match your use case.

## Step 4: Set Up the Documentation Website (Fairblock.github.io)

To explore or contribute to the documentation site, navigate to the Fairblock.github.io folder.

Navigate to the directory:

```
cd ../Fairblock.github.io
```
The website might be built with tools like Jekyll or other static site generators. For example, if it’s a Jekyll-based site (commonly used for GitHub Pages), you would install dependencies and run the site locally:

```
# Install Jekyll and bundler if not installed
gem install jekyll bundler

# Install site dependencies
bundle install

# Serve the site locally
bundle exec jekyll serve
```

The site will now be available at http://localhost:4000.

## Step 5: Contribute to the Project

Both repositories are open-source, and you can contribute by adding features, fixing bugs, or improving the documentation.

Make your changes locally.

Test your changes.

Commit your work:

```
git add .
git commit -m "Description of changes"
```

Push to your forked repository and create a pull request on GitHub.

