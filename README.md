
# UVA CIO Event App

### Developers
<ul>
    <li> Wadie Abboud (Scrum Master) </li>
    <li> Rishi Sarraff (Dev Ops) </li>
    <li> Gemma Zhou (Testing Manager) </li>
    <li> Stephanie Fang (Requirements Manager) </li>
</ul>

### Description
 A fully functional event planner intended to help UVA student organizations plan, manage, schedule and facilitate club events. This project was completed in Fall 2024 as part of a semester long assignment for CS 3240-Software Engineering at UVA. The app was mainly developed using Django, Python, JavaScript, PostgreSQL, in addition to various other technologies and is currently (Dec 2024) being hosted using Heroku. https://myeventsappf24-b01089f2f950.herokuapp.com/

## Features
- Login Page
    -     
    - Users are provided with three options:
  ```
      1. Log in with Google (have an associated Google account to enter as a common user or PMA administrator)  
      2. View Events as Anonymous (view published events but not their details)  
      3. Access Admin Page (log in as a Django administrator)
  ```
- PMA Administrator
    - 
    - PMA administrators can monitor events by deleting the events themselves or their associated files
- Common User
    - 
    - Common users can do several things:
  ```
    1. View events and their details (such as associated files, messages, etc. based on membership)
    2. Request to join an event
    3. Create their own event and manage members
  ```
- Calendar
    - 
    - Common and anonymous users can view the events in a tabluar format based on month, week, and day
- Upload
    -     
    - Files ending with .png, .jpg, .txt, and .pdf can be uploaded and previewed
    - Each file has certain metadata associated with it that users can add (fields are optional)
- Navigation Menu
    - 
    - Profile: Access information about the user and make updates
    - My Events: View events that a user is either a member or owner of
    - Event Search: Search for events based on specific attributes such as name, location, etc.

# Notes
- Most pages will feature a '?' icon that provides information on the intended usage of each page
