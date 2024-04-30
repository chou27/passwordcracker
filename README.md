# Password Cracking Mini-Project

## Description
This Python script demonstrates a simple dictionary attack for password cracking using the hashlib library. It reads passwords from a wordlist file (`wordlist.txt`), hashes each password using MD5, and compares the hash to a target hash to check for a match.

## Files
- `main.py`: Contains the Python script for the password cracking program.
- `wordlist.txt`: Contains a list of sample passwords for testing the cracking algorithm.

## Usage
1. Clone or download the repository to your local machine.
2. Make sure you have Python installed on your system.
3. Run the `main.py` script using the following command:
   ```bash
   python main.py
   ```
4.The program will attempt to crack the target password hash specified in the crackHash function call within main.py.

## Example
Assuming the target hash is `1a1dc91c907325c69271ddf0c944bc72`, the program will search the wordlist for a matching password and print the result if found.

## Wordlist
The `wordlist.txt` file contains sample passwords for testing purposes. You can customize this file with your own list of passwords.

## Notes
- This project is for educational purposes only. Do not use it for unauthorized access or malicious activities.
- Hashing passwords alone is not secure; always use a combination of hashing and salting for password storage in real applications.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Credits
- Created by [Your Name]
- Inspired by the concept of dictionary attacks and hashing algorithms.


