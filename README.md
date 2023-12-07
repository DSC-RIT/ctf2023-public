# Introduction to Capture The Flag (CTF) Competitions

## What is Capture The Flag (CTF)?

Capture The Flag (CTF) is a type of cybersecurity competition that challenges participants to solve various security-related tasks to find hidden flags. These flags are usually text strings or files and are strategically placed throughout the competition environment.

## What to expect?

- Puzzles, Pranks, Stories, a guy named JIM
- 20 CTFQs(Q=Question)
- 2 hours of crackin
- Figure out how to login, that's the first test...

## Evaluation & Prize

- CTFQs Carry 10-100 points based on difficulty.
- Each CTFQ will have a few clues to help you, a maximum of 3 clues. Some won't have any clue.
- Each clue will reduce the points gained from solving that CTFQ by 10%. ie. If the CTFQ is 50 points, taking 3 clues will reduce it to 50 - 15 = 35 points.
- At the end of the 2hr timer, whichever teams have the highest points will get to take the flag on top of the Apex block
- jokes aside
   - 1st: 6k INR
   - 2nd: 4k INR
   - to our beloved best freshers team: 2K INR
   - all the winners and to the 2 lucky folks who found the hidden flags on our Insta reel: GDSC brand t-shirt
- In the case of any tie for the positions, the teams will be given 15 mins to form their own CTFQ and give it to each other ;)

## ToDo or Not ToDo

- Read the description, title and catchphrase, you will feel like a fool when you realize the clues were there all along.
- Use the Internet, it's not an exam.
- Don't let that ego prevent you from clicking those clues, yes that will reduce the points gained. But hey, your friend will solve em questions using them clues like it's nobody's business..., after all it's the time you need to beat.

## Types of CTF Challenges

### 1. Web Exploitation

Web exploitation in Capture the Flag (CTF) competitions involves finding and exploiting vulnerabilities in web applications to gain unauthorized access or extract sensitive information

**Example**: GET aHEAD

Find the flag being held on this server to get ahead of the competition [LINK](http://mercury.picoctf.net:47967/)

### 2. Forensics

Forensics challenges in CTFs often simulate real-world scenarios where participants need to investigate and analyze digital evidence to discover clues or uncover sensitive information. This can include examining files, network traffic, system logs, memory dumps, or any other digital data that might contain hidden flags.

**Example**: information

Files can always be changed in a secret way. Can you find the flag? [cat.jpg](https://mercury.picoctf.net/static/7cf6a33f90deeeac5c73407a1bdc99b6/cat.jpg)

### 3. Reverse Engineering

Reverse Engineering in CTFs involves looking at a piece of code, analyzing given script and figuring out how it works, the correct password must then be extrapolated. The password is the flag

**Example**: plain sight

Reverse engineer the provided program to find the correct password.
```py
def check_password(input_password):
    secret_password = "p@ssw0rd"
    return input_password == secret_password

user_input = input("Enter the password: ")
if check_password(user_input):
    print("Access granted!")
else:
    print("Access denied!")
```


### 4. Cryptography

Cryptography challenges in CTFs can cover various aspects, including symmetric and asymmetric encryption, hash functions, digital signatures, and more. Participants may encounter encoded messages, encrypted files, or cryptographic protocols that need to be analyzed and exploited to reveal the hidden flag. The goal is to apply cryptographic concepts and techniques to decrypt or manipulate data effectively.

**Example**: Mod 26

Cryptography can be easy, do you know what ROT13 is? cvpbPGS{arkg_gvzr_V'yy_gel_2_ebhaqf_bs_ebg13_GYpXOHqX}

### 5. Steganography

Steganography is the art and science of concealing information within other non-secret data to avoid detection. In the context of Capture the Flag (CTF) challenges, steganography is often used as a means to hide clues, keys, or other important information within seemingly innocent files or data.

**Example**: Glory of the Garden

This [garden](https://jupiter.challenges.picoctf.org/static/43c4743b3946f427e883f6b286f47467/garden.jpg) contains more than it seems.

### 6. Trivia

General knowledge questions related to cybersecurity.

**Example**: Lets Warm Up

If I told you a word started with 0x70 in hexadecimal, what would it start with in ASCII?

**Any discussions? engage with other participants [HERE](https://github.com/DSC-RIT/ctf2023-public/discussions/1)**

## Keep an eye out here, we will update you with some resources 

## Come back here after the CTF to see the solutions
