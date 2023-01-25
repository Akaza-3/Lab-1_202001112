Name: Sahil Kothari
Student ID: 202001112
LAB-2


LIBRARY INFORMATION SYSTEM

FUNCTIONAL REQUIREMENTS

User registration: Any new user should be able to register himself/ herself in the system.

User login: Existing members of the system can login into the system and issue or return books.

Forgot/ Change password: If any user forgets their password or wants to change it, there should be an option just below the login form for the same. 

Search book: Anyone can search for the book of their interest. Along with that book, other similar books which are available will also be displayed. Searching for the books should be on the basis of both book name as well as author name.

Issue book: Only the members of the system can issue books. A user can only issue up-to 4 books at a time.

Pre-booking on books: If a user wants a book which is already issued, then he can pre-book it, so that he can issue that as soon as it is available.

Book issue date extension: If any user wants to extend their issue duration, the system must check if that book is pre booked or not. If not, then the duration can be extended. 

Administrator login: The administrator or the librarian has to login into the system if any new book is brought to the library or any old one has  been discarded. The details of those books have to be updated in the system by the librarian.

Email: The user who has issued a book must be emailed about his due date of returning or the book he pre-booked earlier is available now. For those who did not return their book within time, an email with late return penalty fee must be sent. If any book is brought into the library, every user should get an email about it. 

List of non-returnees: The librarian should be able to see the list of users who have not returned their books even after the due date.

Working platforms: The system should work on desktops. However, the user can login into the system from his mobile phone, to check for the return date of his books as well as search for other books.


NON-FUNCTIONAL REQUIREMENTS


Scalability: The number of users and books will always be increasing. Hence. the system should be large enough to handle the data of the users.

Concurrency: The system should be able to handle multiple users at the same time. 

Timings: The system would only work from 10AM-8PM. 

Security: The system must be secure enough to protect the confidential information like the user and administrator password. Also it should prevent any unauthorized access to the system. 

Usability: The system interface should be simple enough so that users from all groups can easily use it without much trouble understanding.

Serviceability: The response time of the system should be as little as possible. Also the system should not be down for more than 30 minutes on any day. 











Q2) 
SCOPE

Many people across the globe suffer from hearing disorders. The suggested application helps these people by catering their special needs. This application recognizes the different sounds from the environment like doorbell, car horn etc and alerts them via signals. In some cases, it even alerts their family members about them. With this application, people with difficulties in hearing can also stay connected with everyone making it an impactful solution for this community.


FUNCTIONAL REQUIREMENTS

Gather information from the surrounding like car horn, baby crying, someone shouting the user’s name etc.

An alert should be sent in the form of a continuous on-off vibration along with a flash from a LED light. 

The latency of the alert message should be less than 2ms. 

The user has to switch off the vibration manually. If the vibration is not stopped even after 5 minutes of its start, an alert message should be sent to the family member of the user. 

The application should work on both android as well as iOS. 


NON-FUNCTIONAL REQUIREMENTS

The sound should be identified correctly.

The response time of the system should have latency less than 2 ms. 

The application should be able to recognize new sounds. 

The price of this application should be minimal enough for a large part of people to benefit from it. 
