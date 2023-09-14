### Online Exam System For Cdac

##### Document:
System Requirement Specification Document

###### Title:
System Reqruiement Spefication for Online Exam System of Cdac

###### Team:
Student, Centre Co-ordinator, System Admin, Cdac Authority, Technical Assistant, Faculty, Director of center

###### Objective (Purpose):
The online exam for students is intended to provide knowledge assesment of students. This will also evaluate the performance of a student in an unbiased manner and test their competitiveness. This will be done through a single gateway using internet. 

###### Scope:
This System allows students to login, view questions, attempt those in an multiple choice format presented randomly, within a specified time limit from an authorized centre. enable students to login, view questions, attempt those in an multiple choice format presented randomly, within a specified time limit from an authorized centre.


###### Definitions:
OAS: Online Exam System
QA:  Quality Assurance
Portal: Online Exam Web Application
MIS: Management Information System
SDM: Student Data Managment
KPI:Key Performance Indicators
Dashboard: Personalized information presented using  BI techniques such grid, score card, graph, KPI

###### Functional Requirements:
A registered student will be able to login for the exam. The exam details like the time, number of questions and marking scheme will be displayed to the student before they give the exam. She will be able to select options from the given, leave it unmarked, or mark for review. 
The coordinator will be able to monitor the exam. She can also suspend the access of a student in case of any discrepencies. System admin will verify the smooth conduction of exams. The technical assistant will ensure the input is recieved by the system and the input devices are working properly. Examiner will supervise and assist the students with the exam process.

Student will be able to give the feedback about the exam. The C-DAC authority will be able to make the necessary changes accordingly if they approve of it.

The exam timer will start when the first question appears and it will inform the students five minutes before the exam is over. Questions will be provided subjectwise to the student, however they will be randomly sequenced for each student to avoid the same pattern of questions for students sitting next to each other. Student will be able to mark or unmark the option of a question. System will maintain the responses of each student. Student will be able view all responses from overview section that is question pallete. The student will be able to navigate through different section any time throughout the exam. The screen cannot be minimized or closed until the exam is over. No other window can be opened until the exam is submitted. The student can submit the exam after first hour of the exam is over. If she does not willingly submit, the exam will automatically get submitted after the time is over. 
    
Main co-ordinator can schedule the exam and the course co-ordinator can view who appeared for the exam and the score recieved by the student in the exam. Student can view the number of exams she appeared and scores of that exam. The director of the C-Dac center can view the graphic representation of the performance of the center. The faculty can create question bank and view the right or wrong answer marked by student.

 
#### NonFunctional Requirement:

###### Security
Registered Customer will allowed to give the exam. Each stakeholder will be to access system through authentication process. Who are you ? System will provide access to the content , operations using Role based security (Authorization) (Permissions based on Role) Using SSL in all transactions which will be performed stakeholder. It would protect confidential information shared by system to stake holder of Shared by stakeholder to system. System will automatically log of all stakeholder after some time due to inactiveness. System will block operations for unregistered stakeholder and would redirect for authentication. System will internally maintain secure communiction channel between Servers ( Web Servers, App Servers, databse Server) Sensitive data will be always encrypted across communcation. User proper firewall to protect servers from out side fishing, velnerable attacks.

###### Reliability
The system will backup data on regular basis and recover in short time duration to keep system operational Continous updates are matained , continous Adminstration is done to keep system operational. During peak hours system will maintain same user experaince by managing load balacning .

###### vailability
uptime: 24* 7 available 99.999%

###### Maintainability:
A Commercial database software will be used to maintain System data Persistence. A readymade Web Server will be installed to host online shopping portal (Web Site) to management server capabilities. IT operations team will easily monitor and configure System using Adminstrative tools provided by Servers. Separate enviornment will be maintained for system for isolation in production, testing, and development.

###### Portablility:
PDA: Portable Device Application System will provide portable User Interface ( HTML, CSS, JS) through users will be able to access online exam portal. System can be deployed to single server, multi server, to any OS, Cloud (Azure or AWS or GCP)

###### Accessibility:
only registered student will be login to the exam after authentication. Cdac centre can dismiss a student if found inelligible due to any actions. Student responses are handled by the system admin. Director will be able to view daily, weekly, monthly, annual performance throgh customized dashboard. Students will be able to see their progress graph.

###### Durability:
System will retain exam portal and responses for 30 minutes after the exam. Student if looses internet connection can join again. System will maintain student information. Student will be able to mark, unmark questions anytime during the exam. System will implement backup and recovery for retaining student data, exam operation data and business data over time.

###### Efficiency:
on result, maximum number of students will view the result, and access the portal with same response time. System will be able to manage all transactions with isolation.

###### Modularity:
System will designed and developed using reusable, independent or dependent business senarios in the form of modules. These modules will be loosely coupled and highly cohesive. System will contain CRM , Inventory , shopping cart, order processing, payment processing, Delivery module, membership and Roles managment modules.

###### Scalability:
System will be able to provide consistent user exeprience to stake holder irrespective of load.

###### Safety:
online exam portal will be secure from malicious attack, fishing. online exam portal functionalilites are protected from outside with prper firewall configuration. online shopping portal will be always kept updated with latest anit virus software. Exam data will be backed up periodically to ensure safty of data using increamental back up strategy. Role based security will be applied for Application data and operations accessibility.


