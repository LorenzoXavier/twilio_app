# Twilio API integration

A very simple app that uses Twilio to generate a confirmation text on sign up.

The app uses ``gem 'devise'`` to manage users, with an addition **phone** attribute.
The **phone** is confirmed as a United Kingdom number, that is valid using the ``gem 'phonelib'``.

When users have registered, the app will redirect to the ``root_path`` and send a text welcoming the new client to the platform


