# SYSVIEW News and Announcements
This repository contains SYSVIEW news articles. These news articles are purposed for displaying
with SYSVIEW. 

## Index Member
The main index member is named `index.json`. This index member lists all available news articles
and attributes about each.

## News Members
Each news member listed in the index member has an associated `.txt` file in this repository. News
members are formatted as SYSVIEW HELP members and can be displayed using SYSVIEW's `HELP` command.

## Adding New News Members
Follow these steps when adding a new news member:
1. Draft a new SYSVIEW HELP member containing the news article content.
2. Test this member in SYSVIEW: 
    1. Place a copy of the HELP member in the USER or SITE HELPLIB
    2. Use SYSVIEW's `HELP <member> MEMBER` command to test the HELP member.
3. Add the HELP member to this repository as a `.txt` file. Name the member NEWSnnnn, where nnnn is the next sequential number available. Use the index member to determine the next sequential number.
4. Add an entry to the `members` array in the index file.  