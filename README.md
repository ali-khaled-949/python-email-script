# python-email-script

Ali Khaled (alikhaled@csu.fullerton.edu)
Even Yang (evanyang@csu.fullerton.edu)
Joshua Duncan (Jduncan1@csu.fullerton.edu)


File: 

part_a.py (Part A)
part_b.py (Part B) Server 1 Hostinger
part_b2.py (Part B) Server 2 Google

How it works:


# Email Sending Script

This project is a Python script that sends an email using the SMTP protocol. The script connects to an SMTP server, authenticates the user, and sends an email with the specified subject and message body.

## Prerequisites

- Python 3.x
- `pip` (Python package installer)

## Installation

1. **Ensure Python 3 is installed:**

   Verify if Python 3 is installed on your system:
   ```bash
   python3 --version
Install pip:

If pip is not installed, download and install it using the following commands:

curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python3 get-pip.py
Install certifi:

Install the certifi package to handle SSL certificate verification:

pip3 install certifi
Configuration
Edit the script to include your email credentials and the recipient's email address. Replace the placeholders with actual values:

<HIDDEN> with your sender email address.
<HIDDEN> with the recipient email address.
<Hidden> with your app password.


--Run the program --
python3 part_b.py.


Response (Part B) Server 1: 


220 smtp-out.flockmail.com ESMTP Postfix

250 smtp-out.flockmail.com

220 2.0.0 Ready to start TLS

250 smtp-out.flockmail.com

334 <HIDDEN>

334 <HIDDEN>

235 2.7.0 Authentication successful

250 2.1.0 Ok

250 2.1.5 Ok

354 End data with <CR><LF>.<CR><LF>

250 2.0.0 Ok: queued as 19BB36015D

221 2.0.0 Bye


Response (Part B) Server 2:

220 smtp.gmail.com ESMTP <HIDDEN> - gsmtp

250 smtp.gmail.com at your service

220 2.0.0 Ready to start TLS

250 smtp.gmail.com at your service

334 <Hidden>

334 <Hidden>

235 2.7.0 Accepted

250 2.1.0 OK <HIDDEN> - gsmtp

250 2.1.5 OK <HIDDEN> - gsmtp

354  Go ahead <HIDDEN> - gsmtp

250 2.0.0 OK  <HIDDEN> - gsmtp

221 2.0.0 closing connection <HIDDEN> - gsmtp


