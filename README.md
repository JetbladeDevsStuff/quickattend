# quickattend

Attendance tracker using NFC tags

## Project goal

Create a system that can track attendance using NFC tags rather than GPS
locations. The NFC tags should use rotating codes to prove that a user scanned
them. A basic scanning app scans in the code and submits them to a server which
records all the responses.

## MVP scope

- NFC tag
- Scanning app
- Server to track scans

## Future plans

- Database to store scans
- App to view stored scans
- Support for background tag scanning in the app

## Tech stack

- C for NFC tag driver
- Python for server
- Swift for app

