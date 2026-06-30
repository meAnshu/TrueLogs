# Feature: SMS/Call Tracking with Notifications

## Overview
Add SMS/Call tracking functionality to TrueLogs that will notify users when their contacts are on a call. Users should be able to select a group of contacts and receive real-time notifications.

## Feature Details

### Scope of Tracking
- [ ] Incoming calls only or both incoming/outgoing?
- [ ] SMS notifications or just calls?

### Contact Management
- [ ] Create custom groups within the app
- [ ] Use existing phone contacts groups
- [ ] Both options available?

### Notification Behavior
- [ ] Immediate notification when call starts
- [ ] Log entry in dedicated tracking section
- [ ] Show caller name + phone number
- [ ] Show call duration
- [ ] Show call time
- [ ] Fetch caller details from Truecaller API

### Notification Format
- [ ] Pop-up notification in app
- [ ] System notification (Android notification bar)
- [ ] Sound/vibration alert
- [ ] All of the above

### Background Tracking
- [ ] Work when app is closed (background service)
- [ ] Work only in foreground
- [ ] Survive app restart

### History & Logging
- [ ] View history of all tracked calls
- [ ] Filter by contact/group
- [ ] Export or delete history

### Privacy & Permissions
- [ ] Requires READ_CALL_LOG permission
- [ ] Enable/disable tracking for specific contacts

## Requirements to Finalize
Waiting for user input on the above questions to proceed with implementation.

## Status
**Planning Phase** - Discussing requirements with user
