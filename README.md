### x). Articles Summary

**First Article**  
It describes that anybody can use threat modeling to recognize what can go wrong in a system, and help mitigate the implementation design for the sake of system security and privacy.

**Second Article**  
It discusses various advantages of threat modeling, such as identifying risks early on, increased security awareness, improved visibility of the target of evaluation, and different threat modeling processes like system modeling, threat identification, and risk response in some form.

 


**Fourth Video**
I have watch one of the episodes from the darknetpodcast, in which one of the episodes they have talk about how google dorking have help found the exact leaked songs on the internet, futhermore they have also talked about how the big artist like skrillex have made their password so easy for a hacker to guess.

**Summary of the all Articles**
In the above articles, threat modeling encourages us to ask the system four important questions:
1. What are we working on?
2. What can go wrong?
3. What can we do about it?
4. Did we do a good enough job?

### a). Security Hygiene

Following are the security practices that everyone should follow:

- **Strong and Unique Passwords**
- **Enable 2-Factor Authorization**
- **Beware of Phishing Scams**
- **Update Your Software**
- **Backing Up Data** will always help

### b). Make-belief Boogie-Man


## 1. What are we working on?

- **Key Assets**:
  - Customer health data
  - Financial records

- **Business Focus**:
  - Protecting customer privacy and data to maintain trust.

- **Company Systems**:
  - The company uses a web application where customers can book appointments in different health categories using a login and signup process. The login system is available for both doctors and customers, with different roles. When a customer books an appointment, the application collects sensitive data like social security numbers and phone numbers.

## 2. What can go wrong?

- **Confidentiality Risks**:
  - Unauthorized access to data due to weak passwords or insufficient security over logins.
  - Information leaks by employees.

- **Integrity Risks**:
  - Customer data may be manipulated by malicious threats.
  - Code errors might cause data corruption, and leading to open a ceratin port number..

- **Availability Risks**:
  - DDoS attacks could increase traffic, leading to delayed response times.
  - Systems and data could be locked, leading to downtime.

## 3. What are we going to do about it?
- **Confidentiality** :
    - encrypting the customer and doctor data can help
    - giving different roles to all employees can protect the data to be seen by limited people.
- **Integrity**:
    - Regularly updating the software and fix bugs for the vulneribilites.
    - use data validation or 2 step authorization method or other authoriation to get inside the customer profile.
- **Availability**:
    - We have deploy some DDoS attack prevention like Firewalls and IDS.
    - Ensuring there is always a data backup
## 4. Did we do good enough?
- we can monitor the applications , penetration testings , secutity audit
- Ask the customers feedback for the security review.
