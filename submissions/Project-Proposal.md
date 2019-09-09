# Projct Proposal - TEAMMATES

**TEAMMATES** - Online Peer Feedback/Evaluation System for Student Team Projects

- Software Github: [Github URL](https://github.com/TEAMMATES/teammates)
- Software Home Page: [Home page](http://teammatesv4.appspot.com/)

####OSS project description
TEAMMATES is a free online tool for managing peer evaluations and other feedback paths of students. It is provided as a cloud-based service for educators/students and is currently used by hundreds of universities across the world.

####Security Features

( User authentication to protect data flow from unauthorized users and modifications.

Data Integrity to prevent accidental data loss, corruption and unintentional modifications. )

Student User Security Needs:

**User authentication**: protect data flow from unauthorized users and modifications.

> *Scenario: In this case I believe it should be an instructor who just registered and hence the persistence problem caused the system to view the user as unregistered. And the key does not correspond to a student and hence is seen as an invalid key.*

**Data Integrity**: prevent accidental data loss, corruption and unintentional modifications.

> *Scenario: Data from deleted sessions persist and can be recovered by creating a new session with the same name in the same course.Session data should be deleted entirely from the database once the session is permanently deleted.*

**Access controls**: stored data could be accessed through instructor searching within limits.

> *Chrome has a 2MB limit for URLs, IE8 and 9 have a 2084 character limit. So everything points in keeping your URLs limited to approx. 2000 characters.
Also, from a usability point-of-view, URLs that long are not usable/readable by users.*


####Security Needs
[**Based on Scenario**]

Quality of service - We take pride in our work and we shall do our best to provide good service to users. 

Changes to the service - We strive to improve TEAMMATES continuously and provide its services free for as long as we can. However, TEAMMATES services may change or be terminated at our discretion.

Security and privacy of data - Our data are stored in Google servers and are protected by the same security mechanisms that protect Google data. However, you are advised not to store in TEAMMATES any 'sensitive' data such as credit card numbers and passwords.

####Motivation

TEAMMATES is a free online system that facilitates anonymous peer feedback between students working in groups. This open source project is accepting contributions, it has 409 contributors, 1,7204 commits, and the lates commit is 7 days ago. TEAMMATES basically built on Java, it is more comforatable to team members to read and undertand.

Several Duke instructors have used TEAMMATES and are quite happy with the work it saves them. Having the possibility of security improvements of an online system that involves different group of students and their instructors is interesting. 


####Lincense Summary and Constributor Agreement


####Security History

Table below lists security issues in the TEAMMATES software itself. Developers of TEAMMATES also provided information of issues and trouble shooting([Developer Troubleshooting Guide](https://github.com/TEAMMATES/teammates/blob/master/docs/troubleshooting-guide.md)).
In the last six years.....
Open issues:High: 6
Medium: 67
Low: 66

|Highest Severity|2019|2018|2017|2016|2015|2014|
|----------------|----|----|----|----|----|----|
|Low				|  3 | 26 | 21 |  7 |  7 |  2 |
|Medium			|  4 |  8 | 19 | 12 | 18 |  6 |
|High				|  0 |  2 |  1 |  1 |  2 |  0 |

####Project Planning - Overall team planning and Individual Contribution

