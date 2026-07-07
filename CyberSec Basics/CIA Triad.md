# CIA Triad

One of the foundational concepts in cybersecurity is the **CIA Triad**. It describes the three main security goals that every system should achieve:

- **Confidentiality**
- **Integrity**
- **Availability**

Rather than being a philosophy, the CIA Triad is a **security mindset**. It helps us ask the right questions whenever we design or analyze a system.

_______________________________________________________________________________________________________

## Confidentiality

Confidentiality means that **only authorized people should be able to access information**.

If an unauthorized person reads sensitive data, confidentiality has been compromised.

### Examples

- Passwords written on sticky notes 
- A hacker stealing login credentials 
- Employees accessing only the files they are permitted to view 

### Common ways to protect confidentiality

- Passwords
- Authentication
- Access permissions
- Encryption

-------------------------------------------------------------------------------------------------------

## Integrity

Integrity means that **data should only be modified by authorized people**. The information should remain accurate and trustworthy.

If someone changes data without permission, integrity has been compromised.

### Examples

- A hacker changing a bank transaction 
- Modifying attendance records after they are locked 
- An approved update made by an authorized employee 

### Common ways to protect integrity

- Access controls
- Hashing
- Digital signatures
- Version control

-------------------------------------------------------------------------------------------------------

## Availability

Availability means that **data and services should be accessible whenever authorized users need them**.

Even if data is secure, it is not useful if users cannot access it.

### Examples

- A company's website going offline during business hours 
- A server crashing due to a Denial-of-Service (DoS) attack 
- Systems remaining accessible to employees during working hours 

### Common ways to improve availability

- Backups
- Redundant systems
- Load balancing
- Protection against DoS attacks

-------------------------------------------------------------------------------------------------------


## How Security Professionals Use the CIA Triad

After a cyber attack, security professionals often ask these three questions:

1. Was any data leaked? → **Confidentiality**
2. Was any data modified? → **Integrity**
3. Can users still access the data or service? → **Availability**

These questions help identify which security property has been affected and guide the response.

-------------------------------------------------------------------------------------------------------


## Summary

| Pillar | Main Question |
|--------|---------------|
| **Confidentiality** | Who can access the data? |
| **Integrity** | Can the data be trusted? |
| **Availability** | Can users access the data when needed? |

> **In one line:**
>
> - **Confidentiality** → Keep data **secret**
> - **Integrity** → Keep data **correct**
> - **Availability** → Keep data **accessible**
