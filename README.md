# xrwvm-fullstack_developer_capstone

## Project name

**Best Cars Dealership — Full Stack Application**

## Repository name

`xrwvm-fullstack_developer_capstone`

## Overview

This repository is the IBM Skills Network Full Stack Application Development Capstone. It is a Django and React car-dealership application. Visitors can browse dealers, filter by state, read reviews with sentiment analysis, and registered users can sign in and post reviews.

## Project details

| Item | Value |
| --- | --- |
| Repository name | xrwvm-fullstack_developer_capstone |
| Project name | Best Cars Dealership — Full Stack Application |
| Stack | Django, Django REST, React, Node/webpack static build, IBM Cloudant, Watson NLU |
| Frontend | `server/frontend` (React components served by Django) |
| Backend | `server/djangoapp` |

## Features

- About Us and Contact Us static pages
- User registration, login, and logout
- Dealer list, dealer-by-id, and dealers-by-state APIs
- Car makes and models catalog
- Dealer reviews with sentiment analysis
- Admin site for the root user
- GitHub Actions CI and cloud deployment

## Local run

```bash
cd server
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

React assets are built from `server/frontend` and collected into Django static files.