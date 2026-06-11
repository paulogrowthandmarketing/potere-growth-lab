# Implementation Notes

## Project

Loxo ATS Migration

## Existing State

The Potere Search website used RecruitFlow to display public job listings.

Several jobs displayed on the website were outdated and no longer reflected active opportunities.

## Implementation

### Step 1

Reviewed existing RecruitFlow integration and Job Postings page.

### Step 2

Verified active jobs were available within Loxo.

### Step 3

Confirmed with internal team that jobs should be published through Loxo.

### Step 4

Replaced RecruitFlow integration with Loxo Careers Page iframe.

Loxo Careers URL:

https://potere-search-ps.app.loxo.co/potere-search-ps

### Step 5

Tested desktop and mobile views.

Issue discovered:

A floating social sharing toolbar displayed on the left side of the page and blocked job content on mobile devices.

### Step 6

Contacted Loxo Support.

Loxo provided the following solution:

https://potere-search-ps.app.loxo.co/potere-search-ps?disable_addthis=true

### Step 7

Updated iframe source to include:

?disable_addthis=true

Result:

* Social sharing toolbar removed
* Mobile usability improved
* Live job synchronization maintained

### Step 8

Adjusted iframe height to better fit displayed job listings and reduce excessive blank space.

## Final Result

The Job Postings page now pulls live jobs directly from Loxo.

Future jobs published within Loxo will automatically appear on the website without requiring additional website updates.

RecruitFlow has been fully replaced for public job listings.
