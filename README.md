📧 QR Code Email Generator
Easily generate a QR code that opens a pre-filled email when scanned!

🚀 Features
Generate a QR Code linked to an email address.

Pre-fill Subject and Body of the email.

Download the generated QR Code as a PNG image.

No backend required — pure HTML, CSS, and JavaScript.

📷 Demo
<!-- (optional: you can replace with your screenshot) -->

🛠 Technologies Used
HTML5

CSS3

JavaScript (Vanilla)

qrcodejs (for QR generation)

📄 How to Use
Enter the recipient's email address.

(Optional) Enter the email subject and body.

Click "Generate QR Code".

Scan the QR code with your mobile device.

(Optional) Click "Download QR Code" to save it as a PNG image.

🔥 Example
If you enter:

Email: someone@example.com

Subject: Hello

Body: I wanted to contact you!

The QR Code will contain:

perl
Copy
Edit
mailto:someone@example.com?subject=Hello&body=I%20wanted%20to%20contact%20you!
Scanning it will open an email app ready to send!

🧩 Project Structure
python
Copy
Edit
index.html   # Main HTML file
qrcode.min.js # QR Code library (via CDN or local)
README.md    # Project documentation
📥 Download and Run
No installation needed!
Just open index.html directly in your browser.

Or if you want to clone:

bash
Copy
Edit
git clone https://github.com/your-username/qr-code-email-generator.git
cd qr-code-email-generator
open index.html
📝 License
This project is open-source and available under the MIT License.

🙌 Acknowledgements
Thanks to qrcodejs for the awesome QR code library!

✨ Let's Make Communication Faster!
