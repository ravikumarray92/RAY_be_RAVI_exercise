# RAY_be_RAVI_exercise
E-Core - Code Challenge Backend
Below are the detailed description of the fixes done .

Add required Junit dependency .
Create new required InvalidMembershipException class .
Add a new method getMembership() in MembershipsService interface .
Modify method names as per Java’s nomenclature standard in RolesService interface .
Update MembershipsServiceImpl class - inject required dependencies, modify logic of assignRoleToMembership() method and, add getMembership() method’s implementation .
Modify methods of RolesServiceImpl class accordingly .
Modify RolesApi interface to ResponseEntity getRoleByUserIdAndTeamId()
Add handle() method for InvalidMembershipException in DefaultExceptionHandler class .
Modify MembershipsRestController class to change methods to correct HTTP method type and correct HTTP code .
Modify RolesRestController class to change methods to correct HTTP method type, correct HTTP code and implement a new endpoint .
Modify TeamsRestController class to change methods to correct HTTP method type and correct HTTP code .
Modify UsersRestController class to change methods to correct HTTP method type and correct HTTP code .
Modify TestData class to add one new test data .
Modify MembershipsApiTests, MembershipsServiceTest, RolesServiceTest to add new test cases, modify test cases , fix failing test cases .
Modify and optimize imports in all the classes .
