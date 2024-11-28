### PhishGuard Security Configuration

PhishGuard uses the GPT API to detect potential voice phishing by analyzing patterns and specific language in real-time conversations. To securely manage the API’s **secret key**—a critical element that must remain confidential—we implemented several protective measures:

1. **Key Management and Storage**: The API secret key is stored separately in a secure file that is excluded from version control. By adding this key file to `.gitignore`, we ensure it is not tracked or accidentally uploaded to any remote repositories, thus reducing the risk of exposure.

2. **Environment Variable Use**: Instead of hardcoding the secret key directly in our codebase, we utilize environment variables to access the key. This prevents accidental exposure within our project files and provides additional security by isolating sensitive information from the main code.

3. **Access Control and Permissions**: We limit access to the secret key to authorized project members only, ensuring that sensitive information is restricted to those who need it.

4. **Regular Key Rotation**: To further enhance security, we follow a regular schedule for rotating the API key, reducing the potential impact of any unforeseen vulnerabilities.

These security practices allow us to leverage the API for real-time phishing detection without compromising the safety of sensitive credentials. By adhering to these guidelines, PhishGuard remains secure and resilient against unauthorized access and potential security threats.
