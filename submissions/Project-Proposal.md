## Project Proposal - TEAMMATES
TEAMMATES is a free online tool for managing peer evaluations and other feedback paths of students. It is provided as a cloud-based service for educators/students and is currently used by hundreds of universities across the world. To facilitate effective teamwork, student peers can provide feedback to each other on their performance as team members. It is primarily developed in Java and comes with a powerful REST API interface. There are 11,596,985 feedback entries submitted so far.

The basic features of TEAMMATES are discussed in the [TEAMMATES featuress]( http://teammatesv4.appspot.com/features.jsp) page.   

TEAMMATES is easy to set up, extremely flexible, and students do not need to create an account. Basically, the instructor creates an account using a gmail address, sets up the course with a list of students and email addresses, and creates a session for peer evaluation. This session contains the questions for the peer evaluation. There are some questions available, or  instructors can create their own or use student questions. Instructors can include a variety of question types including essay, numeric scale, distribute points, multiple choice, and rubrics. Each question response can be adjusted to be visible to the receiving student, the team, or just the instructor, and the responses can be anonymous (except to the instructor).


### Contributors
If users want to become one of contributor, [CONTRIBUTOR ORIENTATION GUIDE](https://github.com/TEAMMATES/teammates/blob/master/docs/CONTRIBUTING.md) This document describes what you need to know/do to become a contributor. The other way to make contribution is to contact contributor by [posting a message in our issue tracker](https://github.com/TEAMMATES/teammates/issues/new). The issue tracker doubles as a discussion forum. You can use it for things like asking questions about the project or requesting technical help.
Alternatively (less preferred), you can email us at teammates@comp.nus.edu.sg.

From the below graph we can analyze the number of people contributing to the TEAMMATES project since Oct, 2011. These statistics are from the TEAMMATES GitHub open source repository.

![Contributions in GitHub](https://github.com/SA-Java-CCSW/CYBR8420ProjectTeammates/blob/UpdateProposal-1/images/Contributors.png)

The below statistics for contributors per month are based on the another TEAMMATES open source repository, [Elasticsearch open hub source page](https://www.openhub.net/p/teammates-on-github).

![Contributions in OpenHub](https://github.com/SA-Java-CCSW/CYBR8420ProjectTeammates/blob/UpdateProposal-1/images/Number_of_Contributors.png)

### Activity
This project has nearly 16,900 commits by around 494 contributors and over a 138.021 lines of code. These statistics are analyzed from the [TEAMMATES on GitHub](https://www.openhub.net/p/teammates-on-github). 


![Activity of TEAMMATES](https://github.com/SA-Java-CCSW/CYBR8420ProjectTeammates/blob/UpdateProposal-1/images/Commits_per_Month.png)

![Lines of Code](https://github.com/SA-Java-CCSW/CYBR8420ProjectTeammates/blob/UpdateProposal-1/images/Code.png)


### Popularity
There are over 1900 institutions from 96 countries around the globe that are using TEAMMATES with more than 200,000 registered users.  Check [TEAMMATES Users Map](http://teammatesv4.appspot.com/usermap.jsp).

TEAMMATES user statistics as end of April 2018 is shown below:

![Popularity of TEAMMATES](https://github.com/SA-Java-CCSW/CYBR8420ProjectTeammates/blob/master/images/popularity.jpg)

### Languages Used
The language used to develop the TEAMMATES is Java.  There are many clients available that can connect to TEAMMATES. The official clients for Elasticsearch are Java, TypeScript, HTML, JavaScript, CSS and other many languages. 

![Languages used in developing Elasticsearch](https://github.com/SA-Java-CCSW/CYBR8420ProjectTeammates/blob/UpdateProposal-1/images/Language_Breakdown.png)

### Platform Used
For developers TEAMMATES recommended tools JDK 1.8, Python 2.7, Google Cloud SDK (minimum version 222.0.0).
For users, this application could run in broswer like Chrome.


### Documentation Sources
The main features and other detailed information including of TEAMMATES are explained in the [TEAMMATES features page](http://teammatesv4.appspot.com/features.jsp).
The [video about the features of the TEAMMATES](https://www.youtube.com/embed/mDtfmNmRwBM?autoplay=1&rel=0) page consists of a video about the products of the TEAMMATES Stack.

### License
Teammates is licensed under GNU General Public License v2.0 which is the most widely used free software license and has a strong copyleft requirement. When distributing derived works, the source code of the work must be made available under the same license. Therefore our project adopted the same license.

### Procedure for making contributions
TEAMMATES is an open source project so anyone can contribute their code through the GitHub source. TEAMMATES welcome contributions from anyone, in particular, students (see here for the list of our contributors). One of the main objectives of TEAMMATES is to help students get experience in a OSS production environment. Here are some information that might be useful to would-be contributors.[Contributing to TEAMMATES](https://github.com/TEAMMATES/teammates/blob/master/docs/CONTRIBUTING.md)

### Security History
There have been relatively few security issues in the TEAMMATES software itself. In the last Six years only six vulnerabilities have been published. The table below provides a quick summary of the number of vulnerabilities found in each of the past six years. 

| Year |   TEAMMATES   | Highest Severity|
| ---- | ------------- | ----------------|
| 2014 | 6             | Medium          |
| 2015 | 2             | High            | 
| 2016 | 1             | High            |
| 2017 | 1             | High            |
| 2018 | 2             | High            |
| 2019 | 0             | N/A             |


### User Security Needs
Below are some basic security needs that users would likely need from the software package and couple scenarios to highlight how v might exist in many different types of environments.

**User authentication** to protect data flow from unauthorized users and modifications.

**Data Integrity** to prevent accidental data loss, corruption and unintentional modifications.
> *Scenario:  Data from deleted sessions persist and can be recovered by creating a new session with the same name in the same course.Session data should be deleted entirely from the database once the session is permanently deleted.*  
    
**Identity Access Management** ensure different role of users could appropriately access to corresponding resources.
> *Scenario: After student successfully enrolled, instructor wants to make modification of detail of students' profile information such as editing student's name, section, team, contact email.* 
    
**Access controls** on stored data procedures. 
> *Scenario: Using Getter and Setter to convert data from the old schema to the new schema. In doing this, data migration script can use Java Reflection to determine whether it is old data or not and convert it accordingly.*
       
**Data Encryption** to protect user data (credit card information, email addresses, passwords) as it travels with in the clusters. 
> *Scenario: Student register with storing in TEAMMATES any 'sensitive' data such as credit card numbers and passwords.*
        
### Security Features
All user data of Teammates are stored in Google servers and are protected by the same security mechanisms that protect Google data. Following is a further description of the features:

_User Authentication_: Authentication services for student accounts rely on google account authentication. Also, instructor can apply for free instructor account at http://teammatesv4.appspot.com/request.jsp. Students can submit responses and view published responses using the unique links TEAMMATES emails them, without having to login or signup.

_Authorization_: This refers to the process of identifying whether the user is allowed to execute the operations. It involves 4 sub-parts:
*	Fine grained access control
*	Permissions (set of privileges)
*	Role (named set of permission)
*	User


### Motivations
TEAMMATES is a free online system that facilitates anonymous peer feedback between students working in groups. This open source project is accepting contributions. TEAMMATES has nearly 16,900 commits by around 494 contributors and over a 138.021 lines of code, and the lates commit is 7 days ago. TEAMMATES basically built on Java, it is more comforatable to team members to read and undertand. This opens up many interesting possibilities for generating constructive formative feedback for developing effective teams and team skills.

Several Duke instructors have used TEAMMATES and are quite happy with the work it saves them. Having the possibility of security improvements of an online system that involves different group of students and their instructors is interesting. 

### Project Links
* Team Repository: https://github.com/SA-Java-CCSW/CYBR8420ProjectTeammates
* Project Board: https://github.com/SA-Java-CCSW/CYBR8420ProjectTeammates/projects

