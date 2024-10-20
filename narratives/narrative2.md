---
layout: default
permalink: /narratives/narrative2/
---

## Artifact Overview
The artifact chosen to showcase my development in software design and engineering, algorithms and data structures, and databases all converge within my first project in CS 320: Software Test Automation (Q1 2024). The goal was to establish validation and automated testing for a client’s specification on an in-memory appointment service. To provide a more robust solution, I specialized the program to fit a consultation appointment service incorporating database to manage larger data sets and ensuring long-term storage.
## Justification – Algorithms and Data Structures
## Data Structures
I selected this artifact to showcase my skills in designing and optimizing algorithms and data structures within the real-world scenario of appointment management. Key data structures begin with the appointment, user, and time slot classes which provide object-oriented design principles for sustained encapsulation of important data while staying flexible enough to support further expansion. Within these classes, data types are properly defined and maintained with validation logic for explicit notification of issues in addition to robust unit testing. 
## Security
I also found security to be a key expression of development, starting with SHA-256 hashing encapsulation to prevent exposure of user passwords from the database and logins. In addition, role-based access enforcing appointment booking solely for consultant users while time slot checking remaining generic serves as an entry point for robust security controls. Error handling is also a key and important foundation for isolating database and service errors, keeping data tightly monitored for possible issues while keeping errors secured and away from hackers.
## Algorithms
Algorithms also play a key role in several appointment service functions, the most used being time slot calculation for availability checking. Time slots are generated using tree sets for efficient and ordered analyses of data, while SQL queries are filtered for date and consultant for both security and lower database overhead. Similarly, SQL queries are protected against SQL injections using prepared statements. 
## Skill Outcomes
In terms of directly attributed course outcomes among algorithms and data structures, protection of sensitive user data like passwords and extensive error handling shows **a security mindset anticipating adversarial exploits, mitigate design flaws, and ensuring privacy and security of data and resources**. The appointment scheduling system with algorithmic availability checking proves the ability to **solve problems using algorithmic principles and computer science standards appropriate to its solution while managing the trade-offs in design choices**. 
## Reflection
When I first set out to showcase my development in algorithms and data structures, I initially had a much more ambitious plan of incorporating a hybrid system of in-memory data synchronized with a database. However, I had to humble myself to realize that certain systems, like consultant appointments, benefit more from having a sole source of truth for enforced security and data integrity. This opened my eyes to recognizing the importance of simplicity in analyzing trade-offs between flexibility and reliability – especially when it comes to the security of the application and user data.


<a href="/https://herpa121.github.io">Back to Home</a>

