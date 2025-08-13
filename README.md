# TI-84-PLUS-CE-PRGMS
Programs for RSA Key Generation, Decryption, and Encryption

**Program 1: RSAKEYGEN**

Generates RSA key pairs (public and private keys)
Stores keys in calculator variables A, B, C

**Program 2: RSAENCRYPT**

Encrypts messages using the public key
Stores encrypted message in variable Z

**Program 3: RSADECRYPT**

Decrypts messages using the private key
Recovers original message


How to Use:

**Step 1: Generate Keys**

Run KEYGEN

Program automatically selects two prime numbers

Displays the public key (N, E) and private key (D)

Keys are stored in variables A=N, B=E, C=D


**Step 2: Encrypt a Message**

Run RSAENC

Enter your message (must be a positive integer < N)

Program displays the encrypted result

Encrypted message stored in variable Z


**Step 3: Decrypt the Message**

Run RSADEC

Enter the ciphertext (or use the value in Z)

Program recovers the original message


**Important Notes:**

Message size limit: Your message must be smaller than N

Integer messages only: This implementation works with numbers, not text

Key storage: Keys persist until calculator is reset or variables are cleared

Security: Uses small primes for educational purposes only

**Example Usage:**

Run RSAKEYGEN → might generate N=323, E=5, D=29

Run RSAENCRYPT → encrypt message "42" → get ciphertext "57"

Run RSADECRYPT → decrypt "57" → recover "42"
