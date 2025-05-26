# Automated_Msg_And_Calls_project
 This project provides an automated SMS notification system using Twilio's API. It allows you to send SMS messages to multiple recipients with customizable messages.
## Features

- Send SMS messages to multiple recipients
- Customizable message templates
- Secure credential management
- Easy configuration through environment variables

## Prerequisites

- Python 3.7 or higher
- Twilio account with API credentials
- Valid Twilio phone number

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/automated-sms-project.git
cd automated-sms-project
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Set up environment variables:
   - Copy `.env.example` to `.env`
   - Fill in your Twilio credentials and phone numbers

## Configuration

Create a `.env` file with the following variables:
```
TWILIO_ACCOUNT_SID=your_account_sid_here
TWILIO_AUTH_TOKEN=your_auth_token_here
TWILIO_PHONE_NUMBER=your_twilio_phone_number_here
RECIPIENT_PHONE_NUMBERS=+1234567890,+0987654321
```

## Usage

1. To send a single SMS:
```bash
python sendSms.py
```

2. To use Twilio functions:
```bash
python useTwilio.py
```

## Security

- Never commit your `.env` file or any files containing sensitive credentials
- Keep your Twilio credentials secure
- Use environment variables for all sensitive information

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request 
