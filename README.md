# Movie Ticket Booking
A Basic Movie Ticket Booking System.

## About
The Software system is an online movie ticket booking system where customers can book seats according to their preference.<br>
## Technologies Used
* SpringBoot
* Java
* AngularJS
* Git
* HTML
* CSS
* Bootstrap
## Features
* All active movies are available for booking.
* Customer can select seat according to their preference.
* System is validated for smooth functioning.
## Preview
<table>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/112768196/205480789-a5ff4ac0-6090-49be-b00f-d280084b7e20.png" alt="Your image title" width="250" height="100"/></td>
    <td><img src="https://user-images.githubusercontent.com/112768196/205480811-b27b0670-ed1d-4623-a5ba-250189b6498e.png" alt="Your image title" width="250" height="100"/></td>
    <td><img src="https://user-images.githubusercontent.com/112768196/205480833-44c808d7-da1d-4d43-a058-0b8fa41422cc.png" alt="Your image title" width="250" height="100"/></td>
  </tr>
</table>

## How To Use
##### Software needed to run the application
Eclipse or Spring Tool Suite(STS).
##### How to Extract Files
Files can be extracted in two ways.
1. Download ZIP File
   * Download ZIP File from Code -> Download ZIP
   * After download is completed, extract files
   * Start Eclipse/Spring Boot by choosing a workplace. Import project (Import -> Maven ->Existing Maven Projects ->Choose Root Directory) and click on finish. Project will be imported.
2. Clone Git Repository
   * Use URL - https://github.com/ani1100/busSeatAllocationSystem.git for cloning.
   * Start Eclipse/Spring Boot by choosing a workplace. Go to GIT Perspective -> Clone a Git Repository -> Paste the URL for cloning -> Click on Next -> Click on Finish on next pop up. 
   * After this, a local git repository will be created.
## Database 
For sample purpose, h2 database(local database) is integrated with the application so that application can run for any user.<br>
If user want to change the database, they can make relevant changes in "application.properties" file.<br>
Also, some data is pre-populated for sample purpose<br>
## Sample data
* All are below information are for sample purpose.
* Four movies are activated in four theatres with four shows for the current day only. Program is auto-scheduled for this.  
* If current timing exceeds any show timing's end time, then status is changed to completed and hence,ticket cannot be booked for such shows..
* If current timing exceeds any show timing's start time but not end time , then that show is running and hence,ticket cannot be booked for such shows.
* This information is just for smooth usage. Everything is validated, no worry for the users.
This is enough for sample purpose.