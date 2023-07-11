# Gmail-Notion API

This software uses Gmail and Notion API to organise emails in the powerful management app Notion.

## Teck Stack
* Python

## Requirements
* Gmail API
* Notion API

## Additional Libraires required
* pip install google-api-python-client
* pip install oauth2client

## Installation
* Download the zip
* run `gmail_api_project.py`

## Features
* Write mails with attachments
* filter the mails based on keyword or sender id and send them to notion

## User Guide

### Setup
* create a Gmail API token
* create a Notion account
* In mailwrite.py change the our_email to you own email
* Delete the `token.pickle`,`credentials.json`,`token.json` file and put your own Gmail API `credentials.json`,`token.json` files
* In `gmail_api_project.py` file in the createNotion function change the Notion API token and database id to your own id

### Write bulk mail
* create a text file with required message
* Select mail write option
* Select the text file
* Select any attachments
* Select subject and destination

### Filter mails
* choose the keyword for filter
* the program takes some time to retrieve the messages
* choose a filteer name(notion page name)
