# Password Cracking & Brute Force Techniques

## Objective

The objective of this lab is to understand and practice password cracking techniques using John the Ripper, a powerful password auditing and recovery tool, the lab will include generating and securing password hashes, exploring different hash algorithms (e.g., MD5, SHA1, bcrypt), and leveraging wordlists, rules-based attacks, and brute-force methods to crack passwords.

### Skills Learned

- Understanding Password Hashing.
- Hash Identification and Extraction.
- Cracking Techniques with John the Ripper.
- Analyzing and Understanding Weak Passwords.
- Password Security Best Practices.
- Ethical Considerations in Password Cracking

### Tools Used

- John the Ripper (JtR).
- Kali Linux Tools for Hash Extraction

## Steps
1. Setup a vulnerable environment using Kali Linux
![image](https://github.com/user-attachments/assets/2c596bad-48b6-4e92-91b0-8956237b65cc)

2. Write a file containing hashed passwords:
![image](https://github.com/user-attachments/assets/6935c310-ceb1-4ba5-a4ac-0e3d98f20da2)

3. Install the John The Ripper tool:
![image](https://github.com/user-attachments/assets/c9357ffe-6c9c-4628-a5ae-48e2af5578a0)
Confirm installation:
![image](https://github.com/user-attachments/assets/c3a7fb21-3c92-43a5-8eb4-6ab54d5925b3)
Ensure your password.txt file has hashes formatted correctly:
![image](https://github.com/user-attachments/assets/eda452af-78be-4727-a0ab-aa1fc99b7793)
Use John The Ripper to attempt cracking weak passwords
![image](https://github.com/user-attachments/assets/7cdff6b5-beae-49d9-b854-220534281f35)
View cracking process:
![image](https://github.com/user-attachments/assets/5f265bef-ecec-4493-b16b-6f64077b00f4)
View cracked passwords:
![image](https://github.com/user-attachments/assets/3913f2de-d344-4595-8d1e-1c5c60ed481d)
Experiment with different hash types; (e.g., MD5, SHA1).
![image](https://github.com/user-attachments/assets/499cb63b-4c04-494e-9419-0086bb0ad37b)
Analyse why certain passwords were cracked faster than others.












