# acs-email-sender-message-model

Email Message model for sending messages with acs-email-sender

## Usage

```python
"""Import model"""
from acs_email_sender_message_model import EmailMessage

"""Create email message"""
message: EmailMessage = EmailMessage(
    to=["user@example.com"],  # list of recipients (REQUIRED)
    subject="Example subject",  # subject string (REQUIRED)
    html="<div>Some <pre>HTML</pre> message.</div",  # HTML email body (optional)
    plaintext="Some plaintext message.",  # Plaintext email body (optional)
    cc=["user2@example.com", "user3@example.com"]  # list of cc recipients (optional)
)
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.