- IDOR: insecure direct object reference: type of access control vulnerability
- Web applications use references to determine what data to send when a user makes a request
- When that application dosent check to see if a user is allowed to view that data before sending it, thats a big issue

- Authentication: verifies who you are
- Authorization: verifies your permissions

- Privilege escalation types:
    - Vertical privilege escalation: you gain access to more features
    - Horizontal privilege escalation: you use features your authorized to use but get access to data your not supposed to have access to
    - Most IDOR cases are horizontal privilege escalation
- Best way to stop IDOR is for the server to check who is asking for the data every time, its not enough to hide or change the id number
