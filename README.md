# Deakin-Unit-Page

## Security Considerations

1. **Input Sanitization**

   * All user inputs (e.g., login forms, search boxes, feedback fields) must be validated and sanitized to prevent common attacks such as SQL injection and cross-site scripting (XSS).
   * Validation should be applied on both client and server sides for stronger protection.

2. **Data Encryption**

   * Sensitive information such as login credentials and personal records must be encrypted in transit using HTTPS/TLS.
   * Future development should consider encryption of sensitive data at rest (e.g., database storage of passwords).

3. **Minimum Password Requirements**

   * User accounts (student/staff portals) must follow a password policy to reduce risks of weak credentials.
   * Agreed baseline password requirements:

     * Minimum length: **8 characters**
     * Must include **uppercase, lowercase, number, and symbol**
     * Avoid use of common/repeated passwords