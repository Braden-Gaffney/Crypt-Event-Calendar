# Crypt-Event-Calendar
Cryptocurrency trading calendar
made by financial engineer Braden Gaffney.
Blockchain's Node Operator Updates
Note Unsure where to put this document, so it's in a Gist for now

This calendar is meant to be used by blockchain's node operator to track hard forks updates that requires scheduled maintenance. Get reminder in advance to ensure you have updated your node.

Link: https://calendar.google.com/calendar/u/0?cid=Y19hZjg3OGYyNzRiOGYyMTQ2YTUzOGM3Njg1MzQ0N2I0MjRlZDAyZjY5OWY3MjA5YTU3YmJhZWIzNDA3MDcxMDkzQGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20

Overview
For each major protocol/chain supported within The Graph ecosystem, this calendar should have all events denoting hard-fork(s) and mandatory updates for proper node's functioning.

The idea is that we have a central place that collect this information and that configured reminder and pre-notifications helps people ensure they have upgrade by the required time.

You accept/reject invitations as to what chain/protocol you need to support and you should get reminder to ensure to have upgraded in time

Event Format Spec
Here a rough spec of expected details for each event that is going to be created in the calendar

Title: (, ...) @ Block|Time

Description: Should contain a series of links to important places, like release notes, versions, other softwares needed to upgrade like Firehose, etc

Date: Set the event 1 work day before it happens, span weekends if necessary

For example, an upgrade scheduled on a Monday should span Friday, Saturday, Sunday and Monday.

Time: 1 hour before expected merge time and 1 hour after expected merge time, use UTC (it's(GMT+00:00) Coordinated Universal Time in Google Calendar)

Recurring: Should recur as many days as we have span, so that N reminders + N events occurs, the end date is always the date at which the hard-fork is going to happen.

Reminder: Reminds 1 day before

Invitees: <Not clear how we are going to manage that, for now it's a manual process>

Example BNB Mainnet Pluto & Herzt hard-fork
Title: BNB Mainnet v1.2.9+ (Pluto & Hertz) Hard Fork @ 30720096

Description:

[Pluto] https://forum.bnbchain.org/t/bnb-chain-upgrades-mainnet/936#platoupcoming-6
[Herzt] https://forum.bnbchain.org/t/bnb-chain-upgrades-mainnet/936#hertzberlin-london-on-bsc-5
[Node version1.2.9+] https://github.com/bnb-chain/bsc/releases/tag/v1.2.9
[Firehose Node version] **Unreleased**
[firehose-ethereum] _No changes required_
Date: 2023-08-09T02:02:05Z (expected to happen at 2023-08-10T02:02:05Z)

Time: 2023-08-09T01:02:05Z - 2023-08-09T03:02:05Z

Recurring: 2 times (one on the 9th, one on the 10th)

Reminder: Reminds 1 day before

Invitees: <Not clear how we are going to manage that, for now it's a manual process>
