# Self-Destructing-Secure-Notes-with-Encrypted-Storage-and-Access-Pattern-Privacy
A secure note-sharing platform where the sender can set self-destruction functionality based on time expiration and access limits. Notes are secured using AES-GCM where a decryption key is generated and receiver can access message using the shared key. The note is stored only in the encrypted form which ensures confidentiality.

Install Dependencies
pip install -r requirements.txt

To run
python app1.py

Access in Browser

Note creation: http://127.0.0.1:5000/
<img width="238" height="248" alt="image" src="https://github.com/user-attachments/assets/75e804d7-fbd0-4a2d-99f7-77c9209f05b4" />

Note viewer: http://127.0.0.1:5000/view
<img width="865" height="413" alt="image" src="https://github.com/user-attachments/assets/8451c9a9-9587-45f4-b6d3-cea8ade732f9" />

