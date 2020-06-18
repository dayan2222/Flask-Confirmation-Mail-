# Flask-Confirmation-Mail-
Flask Confirmation Mail Sending for mail Varifaction During Registeration or for some other purposes.

Important libraries

    from flask import Flask, request, url_for
    from flask_mail import Mail, Message
    from itsdangerous import URLSafeTimedSerializer, SignatureExpired
