<h1>Testing Project for **www.magazinulapicultorului.ro**</h1>

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: www.magazinulapicultorului.ro

Tools used: Jira, Zephyr Squad.

<h2>Functional specifications:</h2>

The below stories (GMT-44 Comparare produse, GMT-45 Elemente din partea inferioara a paginii, GMT-62 Conectare utilizator cu e-mail si parola) were created in Jira and describes the functional specifications of these modules, for which the final project is performed upon.
<br>
![image](https://github.com/user-attachments/assets/b1d355f8-7b9b-47f9-af4f-49777f6a44d4), ![image](https://github.com/user-attachments/assets/57a9f450-3604-4c55-a34f-346e80d543fd), 
![image](https://github.com/user-attachments/assets/a5420e29-1701-49e9-aa22-f1b69f5d00e4)

Here you can find the release that was created for this project:

![image](https://github.com/user-attachments/assets/66d6ae58-21f2-4d9d-bda7-9bada4a09432)


<h2>Testing process</h2>

The test process was performed based on the standard test process as described below.

<h3>1.1 Test planning</h3>

The Test Plan is designed to describe all details of testing for the following modules from the www.magazinulapicultorului.ro application:

<li>Comparare produse</li>
<li>Elemente din partea inferioara a paginii</li>
<li>Conectare utilizator cu e-mail si parola</li>
<br>The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan.

<h4>1.1.1. Roles asigned to the project and persons allocated</h4>

<ul>
  <li>Project manager Popescu Ion</li> 
  <li>Product owner Ionescu Ion</li>
  <li>Software developer Georgescu Ion</li>
  <li>QA Engineer Enachescu Ion</li>
  <li>QA Tester Mirea Gabriel</li>
</ul>

<h4> 1.1.2 Entry criteria defined </h4>

<li> Assignment of roles and responsibilities </li> 
<li> Identification of project risks </li> 
<li> Establishing deadlines </li>
<li> Definition of testing objectives</li>

<h4> 1.1.3 Exit criteria defined </h4>

<li> Compliance with deadlines </li> 
<li> Running at least 90% of the tests </li> 
<li> Completion of test documentation </li> 
<li> Identification and mitigation of product risks </li> 
<li> Completing the documentation of defects and their transmission </li> 

<h4> 1.1.4 Test scope</h4>

<h5> Tests in scope: </h5>
<li>Functional testing</li>
<li>Blackbox testing</li>
<li>Positive and negative testing</li>
<li>Log-in user test</li>
<li>Comparison product test</li>
<li>links at the bottom of the page test</li>

  <h5>Tests not in scope: </h5>

<li> Automation testing is out of scope </li>
<li> Compliance regulation testing is beyond the scope </li>
<li> Portability testing will not be done </li>
<li> Volume testing will not be done </li>


<h4>1.1.5 Risks detected</h4>

<h5>Project risks:</h5>

<li> There are not enough members in the test team for a performance test </li>
<li> Deadline too short </li>

<h5> Product risks: </h5>

<li> Failure to pay by card may result in the user avoiding this site </li>
<li>  Comparing products from different categories can be confusing </li>

<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

<h3>1.2 Test Monitoring and Control<h3>

**(inserati aici motivul pentru care a fost facuta etapa de monitorizare si control si respectiv cum s-a facut aceasta etapa. Aici veti insera de asemenea si raportul de status (test status report) din zephyr - test metrics - primul din lista care sa reflecte activitatea si evolutia testarii. Recomand aici sa executati teste aproape in fiecare zi ca sa vada angajatorul implicarea voastra in testare)**

<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements. <b>(The requirements analysis has been done in order to implement the <i>early testing</i> test principle and the results can be found here - inserati linkul catre documentul de review. Parte asta specificata intre paranteze o puneti doar daca aveti cerinte si daca ati facut review)</b>. <br><br>

The following test conditions were found: <br>

**(aici puteti fie sa puneti o poza din jira cu titlurile tuturor testelor - din issues filtrare dupa type test sau sa scrieti cu bulinuta numele fiecarei conditii de testare pe care ati identificat-o)**

<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here **(inserati linkul catre fisierul cu testele, in format pdf, word sau csv)**

<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:

**(inserati lista de elemente care sunt evaluate in etapa de implementare)**

<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: **(inserati aici numele cycle-ului pe care l-ati creat)**

Bugs have been created based on the failed tests. The complete bug reports can be found here: **(inserati aici fisierul cu bug-urile pe care le-ati identificat)**

The following is a summary of the bugs that have been found
**(inserati o lista cu titlurile bug-urilor identificate impreuna cu prioritatea si severitatea fiecaruia)**

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

<h3> 1.7 Test Completion</h3>
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: **(inserati aici fie o poza cu matricea de trasabilitate din jira, fie linkul catre fiserul excel exportat din jira cu matricea de trasabilitate. Nu uitati sa faceti filtrare dupa type = story)**

Test execution chart was generated and can be found below. 

**(inserati aici raportul de executie generat din jira din sectiunea de dashboards)**

The final report shows that a number **(inserati numarul de teste)** tests have failed of a total of **(inserati numarul de teste)**

A number of **(inserati numarul de bug-uri)** total bugs were found, from which the priority is: **(inserati numarul de bug-uri)** are high and **(inserati numarul de bug-uri)** are medium.

**(inserati aici o concluzie generala a testarii care sa cuprinda cate teste au fost create si executate, ce procentaj aproximativ din cerintele in scop au fost acoperite, daca exista vreo functionalitate pe care nu ai apucat sa o testezi, daca bug-urile gasite impacteaza lansarea produsului in productie sau se pot fixa si ulterior, daca ai identificat riscuri de produs care trebuie mitigate, daca e vreo reecomandare pe care vrei sa o faci pentru lansare, daca sunt ceva lessons learned de care trebuie sa se tina cont la proiectele viitoare etc.)**
