# Automated AppSec with ZAP

### What are the three common stages of the Penetration Testing process and what tasks are performed at each one?

1. **Reconnaissance (Information Gathering)**:
    - This stage involves collecting information about the target system or network to identify potential vulnerabilities. Tasks include network scanning, identifying open ports, and gathering details about the target environment.

2. **Exploitation**:
    - During this phase, testers attempt to exploit the identified vulnerabilities to gain unauthorized access. This may involve using various tools and techniques to launch attacks such as SQL injection, cross-site scripting (XSS), and buffer overflow.

3. **Post-Exploitation**:
    - After successfully exploiting the vulnerabilities, the focus shifts to maintaining access and gathering sensitive information. This stage involves assessing the extent of the breach, collecting data, and documenting the findings. Recommendations for remediation and improving security measures are also provided.

### Explain a “man-in-the-middle proxy” in non-technical terms.

A "man-in-the-middle proxy" is like an eavesdropper who secretly listens to and can alter the conversation between two people. Imagine two friends passing notes in class, but someone in the middle intercepts each note, reads it, and possibly changes the message before passing it on. This allows the eavesdropper to see and manipulate the communication without the friends knowing.

### What are the 2 spiders available for use in ZAP? What situations are they best suited for?

1. **Traditional Spider**:
    - This spider is designed to quickly discover URLs within a website by following links. It is best suited for simple and straightforward web applications where content is primarily linked through HTML.

2. **AJAX Spider**:
    - The AJAX Spider is tailored for dynamic web applications that heavily use JavaScript. It can effectively find hidden content in modern, interactive web applications that may not be accessible through traditional link-following methods.

These spiders are essential for thoroughly mapping out a web application's structure and identifying potential vulnerabilities. The Traditional Spider is efficient for simpler sites, while the AJAX Spider excels in dealing with complex, JavaScript-heavy applications.

