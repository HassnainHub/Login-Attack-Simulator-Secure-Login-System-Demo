# Login-Attack-Simulator-Secure-Login-System-Demo
. This project demonstrates both offensive and defensive security concepts by implementing two systems: a Login Attack Simulator and a Secure Login System.
1. Introduction
Information Security focuses on protecting systems from unauthorized access and cyber attacks. In modern web applications, the login system is considered the first and most critical security layer because if it is compromised, the entire system becomes vulnerable. This project demonstrates both offensive and defensive security concepts by implementing two systems: a Login Attack Simulator and a Secure Login System.
# 2. Project Overview
This project consists of two main modules:
	Login Attack Simulator
	Secure Login System
Both modules are designed to demonstrate real-world Information Security concepts in a simplified web-based environment. The attack simulator shows how weak passwords can be exploited using dictionary-based attacks, while the secure system demonstrates how authentication can be protected using multiple security layers.
# 2.1 Login Attack Simulator
The Login Attack Simulator is designed to simulate a real attack scenario in which a system automatically tries multiple predefined passwords to guess the correct one. The main purpose of this module is to demonstrate how easily weak passwords can be cracked using automated techniques.
Working Mechanism:
	The user sets a target password
	The system uses a predefined dictionary of common passwords
	Each password is tried sequentially every 800 milliseconds
	If a match is found, the system displays “Password Cracked”
	If no match is found, the system shows “Attack Failed”
Attack Techniques Demonstrated:
	Dictionary Attack
	Brute Force Simulation
# 2.2 Secure Login System
The Secure Login System represents a defensive security model that protects authentication through multiple layers. It ensures that only legitimate users can access the system while blocking automated or suspicious attempts.
# Main Features:
	CAPTCHA verification to prevent bot access
	Strong password validation rules
	Login attempt tracking system
	Account lock after multiple failed attempts
	Automatic unlock timer system
Password Strength Rules:
A password is considered strong only if it meets the following conditions:
	Minimum length of 10 characters
	At least one uppercase letter
	At least one lowercase letter
	At least one numeric digit
	At least one special character (@$!%*?&#)
If the password does not meet these requirements, the system rejects it and counts the attempt.
# 3. Security Concepts Used
This project implements several important Information Security concepts:
	Dictionary Attack: Attempts passwords from a predefined list of commonly used passwords.
	Brute Force Attack: Tries multiple combinations to guess the correct password.
	Password Strength Enforcement: Ensures users create strong and complex passwords.
	CAPTCHA Verification: Prevents automated bots from performing login attempts.
	Account Lockout Policy: Temporarily locks the system after multiple failed attempts.
These concepts are widely used in real-world systems such as banking applications and secure web platforms.
# 4. Working Mechanism
The system workflow is divided into two parts:
Attack Simulator Flow:
	A dictionary array is loaded into the system
	Passwords are tried one by one sequentially
	If a match is found, the attack is marked successful
	If no match is found, the attack fails after the list ends
Secure System Flow:
	The user enters a password
	CAPTCHA verification is performed
	Password strength is checked against defined rules
	Weak passwords are rejected and attempts are counted
	After 3 failed attempts, the system is locked temporarily
	A timer runs until the system is automatically unlocked
# 5. Observations
From this project, the following key observations were made:
	Weak passwords can be cracked very easily using dictionary attacks
	Automated attacks are extremely fast and efficient
	Simple authentication systems are highly insecure
	Security layers such as CAPTCHA, strong password policies, and lockout mechanisms significantly improve system security
6. Conclusion
This project successfully demonstrates both offensive and defensive aspects of Information Security. The Login Attack Simulator highlights how vulnerable weak password systems are to automated attacks, while the Secure Login System shows how multiple security mechanisms can effectively protect user authentication.
It can be concluded that strong password policies, CAPTCHA verification, and account lockout mechanisms are essential components of modern secure systems to prevent unauthorized access and protect sensitive data.
