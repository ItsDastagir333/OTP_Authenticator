# OTP Authenticator

## Overview

OTP Authenticator is a Python script that generates a Time-based One-Time Password (TOTP) using the PyOTP library. The script creates a random base32-encoded key, generates a provisioning URI for the QR code, and then creates a QR code image for easy setup with an authenticator app. Additionally, the script allows users to verify the generated OTP by comparing it with user input.

## Features

- Generates random base32-encoded keys for TOTP.
- Creates a provisioning URI for easy setup with authenticator apps.
- Generates a QR code image for scanning with authenticator apps.
- Verifies user-entered OTP with the generated TOTP.

## Usage

1. Run the script to generate a random TOTP secret and create a QR code image:

   ```bash
   python otp_authenticator.py
   ```

2. Scan the generated QR code with an authenticator app to start generating OTPs.

3. Enter the received OTP when prompted to verify.

## Dependencies

- PyOTP: [https://github.com/pyotp/pyotp](https://github.com/pyotp/pyotp)
- qrcode: [https://github.com/lincolnloop/python-qrcode](https://github.com/lincolnloop/python-qrcode)

## Installation

1. Install the required Python packages:

    ```bash
    pip install pyotp qrcode[pil]
    ```

2. Run the script as described in the Usage section.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
