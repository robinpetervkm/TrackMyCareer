# Track My Career


## Problem
I'm actively job hunting, I Search LinkedIn, Indeed, and other job portals. The issue is that I often lose track of the jobs I've applied to: what the job description said, what URL it was listed at, what cover letter I submitted. And sometimes I plan to apply for a job later, but by the time I remember, the deadline has already passed.

## Solution
Develop a personal job tracking portal where I can store job information, company details, application status, apply date, deadline, and everything else I need for my records.

## User
It's for anyone who wants a simple but effective way to track both applied jobs and jobs they plan to apply to.

## Feature
-
A dashboard with summary cards showing: total applied, interviews, offers, rejected, and deadlines coming soon
The dashboard should also show jobs with upcoming deadlines so we never miss an application.
A separate all-jobs page that lists all entries, with 10 per page by default
The all job page needs to have search functionality.

## Data
JOBS:
    - id
    - job_title
    - job_description
    - applied_status
    - applied_date
    - deadline
    - job_url
    - interview_date
    - notes_id (one job can have many notes)
    - company_id
COMPANY:
    - id
    - company_name
    - about
NOTES:
    -id
    -note
    -created_at