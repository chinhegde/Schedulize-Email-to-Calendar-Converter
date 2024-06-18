# Schedulize: Email-to-Calendar Converter

## Overview
Schedulize is a Python script designed to automate the extraction of event details from emails and create corresponding Google Calendar events. It uses Gmail API for fetching emails, Google Generative AI (genai) for natural language processing, and iCalendar (iCal) format for creating calendar invites.

## Features
- Event Extraction: Uses generative AI to parse email content and extract event details.
- Calendar Integration: Creates iCalendar (.ics) files and sends them as calendar invites via Gmail.
- Automated Scheduling: Handles relative dates, default times, and duration assumptions for events.

## Dependencies
1. simplegmail for interacting with Gmail API.
2. icalendar for generating iCalendar (.ics) files.
3. google.generativeai.
