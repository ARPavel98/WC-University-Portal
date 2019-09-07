# WC University Management System

  WC University is an Imginary University and this project is to maintain this university.

### Mudules:
  1.    Student View
   - View Registered courses by him/her
   -  View current CGPA, number of credits completed
   -  Apply for convocation if eligible (depends on his/her program’s minimum credits for graduation criteria). Otherwise the option will be disabled
    - Make payment for convocation (Selecting gateway and placing TrxID). This option will be disabled before applying. Also one can make payment only once.

  2.    Coordinator View
    - View students registered in program he is coordinating
    - View their grades and credits completed
    - Select students and register them into different courses offered in that particular program.
  
  3.    Admission Officer View
    - View students registered in all the programs
    - Add students in different programs. Only into one of the programs created in the system, a student can be admitted. 
    - Create initial login credentials for the students
  
  4.    Deputy Registrar(Academic) VIew
    - View all the programs and courses offered in the university
    - Create program
    - Create courses. Course needs to be offered in any one of the created program. A program combo box makes it sure.
    
  5.    Deputy Registrar(Human Resource) VIew
    - View all the employees in all the departments
    - Add employee into any department and create initial credentials.



FrontEnd Link: 
https://wcu-portal.herokuapp.com/

Microservices links:

http://wcu-discovery-server.herokuapp.com/
https://wcu-gateway-api.herokuapp.com/
https://wcu-student-api.herokuapp.com/swagger-ui.html#
https://wcu-program-api.herokuapp.com/swagger-ui.html#
https://wcu-hr-api.herokuapp.com/swagger-ui.html#
https://wcu-auth-server.herokuapp.com/api/v1/auth
https://wcu-convocation-api.herokuapp.com/swagger-ui.html#
