## 1. GitHub Code Upload Phase

In this phase, the system takes the link to the GitHub repository provided by the user and retrieves the code. The code is then stored on AWS S3 for backup purposes. Additionally, the production build is stored on the Amazon SQS service.

### Steps:

1. **Receive GitHub Repository Link**: Get the link from the user.
2. **Fetch Code**: Use the provided link to fetch the source code.
3. **Store on AWS S3**: Save a copy of the source code on AWS S3 for backup.
4. **Store Production Build on SQS**: Save the production build (HTML, CSS, JavaScript files) on the Amazon SQS service.


<img width="925" alt="Screenshot 2024-07-28 at 5 28 32 PM" src="https://github.com/user-attachments/assets/7a26ebec-946d-4bc8-b2d6-37c0e83cf10c">
