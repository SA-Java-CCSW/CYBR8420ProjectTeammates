## Project Proposal - TEAMMATES
TEAMMATES is a free online tool for managing peer evaluations and other feedback paths of students. It is provided as a cloud-based service for educators/students and is currently used by hundreds of universities across the world. To facilitate effective teamwork, student peers can provide feedback to each other on their performance as team members. It is primarily developed in Java and comes with a powerful REST API interface. There are 11,596,985 feedback entries submitted so far.

The basic features of TEAMMATES are discussed in the [TEAMMATES featuress]( http://teammatesv4.appspot.com/features.jsp) page.   

TEAMMATES is easy to set up, extremely flexible, and students do not need to create an account. Basically, the instructor creates an account using a gmail address, sets up the course with a list of students and email addresses, and creates a session for peer evaluation. This session contains the questions for the peer evaluation. There are some questions available, or  instructors can create their own or use student questions. Instructors can include a variety of question types including essay, numeric scale, distribute points, multiple choice, and rubrics. Each question response can be adjusted to be visible to the receiving student, the team, or just the instructor, and the responses can be anonymous (except to the instructor).


### Contributors
If users want to become one of contributor, [CONTRIBUTOR ORIENTATION GUIDE](https://github.com/TEAMMATES/teammates/blob/master/docs/CONTRIBUTING.md) This document describes what you need to know/do to become a contributor. The other way to make contribution is to contact contributor by [posting a message in our issue tracker](https://github.com/TEAMMATES/teammates/issues/new). The issue tracker doubles as a discussion forum. You can use it for things like asking questions about the project or requesting technical help.
Alternatively (less preferred), you can email us at teammates@comp.nus.edu.sg.

From the below graph we can analyze the number of people contributing to the TEAMMATES project since Oct, 2011. These statistics are from the TEAMMATES GitHub open source repository.

**image update latter**
![Contributions in GitHub](https://github.com/swrp/CYBR8420-SemesterProject/blob/master/images/Contributor%20GitHub.png)
**image update latter**

The below statistics for contributors per month are based on the another TEAMMATES open source repository, [Elasticsearch open hub source page](https://www.openhub.net/p/teammates-on-github).

**image update latter**
![Contributions in OpenHub](https://github.com/swrp/CYBR8420-SemesterProject/blob/master/images/OpenHub%20Contributor.png)
**image update latter**

### Activity
This project has nearly 16,900 commits by around 494 contributors and over a 138.021 lines of code. These statistics are analyzed from the [TEAMMATES on GitHub](https://www.openhub.net/p/teammates-on-github). 

**image update latter**
![Activity of Elasticsearch](https://github.com/swrp/CYBR8420-SemesterProject/blob/master/images/Activity.png)

![Lines of Code](https://github.com/swrp/CYBR8420-SemesterProject/blob/master/images/Lines%20of%20code.png)
**image update latter**

### Popularity
There are over 1900 institutions from 96 countries around the globe that are using TEAMMATES with more than 200,000 registered users.  Check [TEAMMATES Users Map](http://teammatesv4.appspot.com/usermap.jsp).

TEAMMATES user statistics as end of April 2018 is shown below:

![Popularity of TEAMMATES](https://github.com/SA-Java-CCSW/CYBR8420ProjectTeammates/blob/master/images/popularity.jpg)

### Languages Used
The language used to develop the TEAMMATES is Java.  There are many clients available that can connect to TEAMMATES. The official clients for Elasticsearch are Java, TypeScript, HTML, JavaScript, CSS and other many languages. 

**image update latter**
![Languages used in developing Elasticsearch](https://github.com/swrp/CYBR8420-SemesterProject/blob/master/images/Languages%20used.png)
**image update latter**


**do it latter**
### Platform Used
For developers TEAMMATES recommended tools JDK 1.8, Python 2.7, Google Cloud SDK (minimum version 222.0.0).

Elasticsearch requires at least Java version 1.8.0_131 or a later version in the Java 8 release series to run their project. It supports only Oracle’s Java and the OpenJDK. It is recommended to use same JVM version across all the Elasticsearch nodes and clients. They also tested running Elasticsearch successfully on the various platforms that are listed in their website. They also mentioned that it is also possible that it can work on other platforms that are not listed in their website.

[List of platforms page](https://www.elastic.co/support/matrix) consists of list of platforms that supports Elasticsearch.
**do it latter**

### Documentation Sources
The main features and other detailed information including of TEAMMATES are explained in the [TEAMMATES features page](http://teammatesv4.appspot.com/features.jsp).
The [video about the features of the TEAMMATES](https://www.youtube.com/embed/mDtfmNmRwBM?autoplay=1&rel=0) page consists of a video about the products of the TEAMMATES Stack.

### License
Teammates is licensed under GNU General Public License v2.0 which is the most widely used free software license and has a strong copyleft requirement. When distributing derived works, the source code of the work must be made available under the same license. Therefore our project adopted the same license.

### Procedure for making contributions
TEAMMATES is an open source project so anyone can contribute their code through the GitHub source. TEAMMATES welcome contributions from anyone, in particular, students (see here for the list of our contributors). One of the main objectives of TEAMMATES is to help students get experience in a OSS production environment. Here are some information that might be useful to would-be contributors.[Contributing to TEAMMATES](https://github.com/TEAMMATES/teammates/blob/master/docs/CONTRIBUTING.md)

### Security History
Elastic has good resources and published information about vulnerabilities in the Elasticsearch software.  They have a page summarizing [security issues](https://www.elastic.co/community/security) on their website and a [forum](https://discuss.elastic.co/c/security-announcements) where new security announcements are posted.  Reporting new vulnerabilities to Elastic is as easy as emailing security@elastic.co.  

There have been relatively few security issues in the Elasticsearch software itself.  In the last five years only seven vulnerabilities have been published.  Since the X-Pack software was, until recently, more of a separate code-base, those vulnerabilities were categorized separately with nine flaws found since 2017.  In fact, all security bugs announced in 2017 were due to the X-Pack features.  The table below provides a quick summary of the number of vulnerabilities found in each of the past five years and the most significant severity according to CVSS v2.0. 

| Year | Elasticsearch | X-Pack | Highest Severity|
| ---- | ------------- | ------ | ----------------|
| 2014 | 2             | 0      | Medium          |
| 2015 | 5             | 0      | High            | 
| 2016 | 0             | 0      | N/A             |
| 2017 | 0             | 8      | Medium          |
| 2018 | 2             | 1      | High            |


### User Security Needs
Below are some basic security needs that various types of users would likely need from the software package and couple scenarios to highlight how Elasticsearch might exist in many different types of environments.

**User authentication** to protect data flow from unauthorized users and modifications.

**Data Integrity** to prevent accidental data loss, corruption and unintentional modifications.

    
    Scenario:  Being a responsible project manager I would like to use Elasticsearch for my 
    company. Our projects are driven by agile processes and I want to integrate Elasticsearch 
    with my ticket tracking tool to monitor the progress on project for each sprint.
    But I want authenticated users from my organization to view this progress and restric them 
    from altering any data in the cluster.  
    
   
  **Identity Access Management** to manage user activities on Elasticsearch cluster.
    
   Fine grained **user privileges** and attribute based access controls to prevent unauthorized access to Elasticsearch cluster.
   
    Scenario: As an IT Developer I use Elasctisearch on my version control to monitor the number 
    of commits by each developer for every project. All the developers can view their progress but 
    I would like to limit it to read permissions and restrict them from making any modifications 
    to the cluster. 
    
   **Access controls** on stored data procedures. 
      
      Scenario: If a client finds a bug in the application that gives access to Elasticsearch 
      this gives them access to data in all indexes and grab data that belongs to other clients.
      (This can be eliminated with the use of a commercial plugin called X-Pack Security). 
      As a user I except this to be a part of Elasticsearch.
       
   **Data Encryption** to protect user data (credit card information, email addresses, passwords) as it travels with in the clusters. 

   Secure (TLS/SSL) certificates to establish **trust** between nodes. 
    
    Scenario: I would like to monitor all the incoming IP requests to my home network and expect 
    Elasticsearch to securely encrypt my personal data, share my data to users I have given access.
        
   **Audit logging** for all unauthorized login attempts, nefarious network traffic trying to enter the cluster, detect false connections with no signatures.   

    Scenario: As a stakeholder of an ecommerce organization I expect an audit log to be able 
    to detect brute forced login attempts, unauthorized network access, denial of service attacks,
    and connections from unapproved clients to my Elasticsearch cluster. 
   
   Other security configurations are also important like making sure that clusters are hidden within private networks and only accessible to required applications and 
   manually disabling features that are not used by the application(e.g. default ports).

### Security Features
All user data of Teammates are stored in Google servers and are protected by the same security mechanisms that protect Google data. Following is a further description of the features:

_User Authentication_: Authentication services for student accounts rely on google account authentication. Also, instructor can apply for free instructor account at http://teammatesv4.appspot.com/request.jsp. Students can submit responses and view published responses using the unique links TEAMMATES emails them, without having to login or signup.

_Authorization_: This refers to the process of identifying whether the user is allowed to execute the operations. It involves 4 sub-parts:
*	Fine grained access control
*	Permissions (set of privileges)
*	Role (named set of permission)
*	User

### Motivations
Elasticsearch is widely adopted in various industries like Netflix, Stack Overflow, LinkedIn, Accenture and Tripwire, amongst others. It has immense capabilities made possible due to the fact that it has a distributed architecture. It is interesting to dig into the possibility of security improvements of a search engine that has the scalability of thousands of servers and dealing with petabytes of data. Also, Elasticsearch is mostly built on Java, which all the team members are comfortable with.  

Some team members use or have used Splunk in that past.  The feature set of Elasticsearch is often compared to that of Splunk.  Learning a comparable tool that could potentially have a lower cost of ownership, or work to complement and maximize expensive investments in other solutions could be desirable to current or future employers.

### Project Links
* Team Repository: https://github.com/SA-Java-CCSW/CYBR8420ProjectTeammates
* Project Board: https://github.com/SA-Java-CCSW/CYBR8420ProjectTeammates/projects

