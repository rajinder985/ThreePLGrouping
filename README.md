# 3P Learning Assignment 
It is Rest API created in .Net core to group the students which are adjacent to each other by horizontally, vertically or diagonally
## Input :
It has one HTTP Post method which take input as  multi-dimensional string array. Below are the sample input of multi-dimensional array string.

### Input-1 :
 { {'','',’Simon’,'',''},  {'',’Sergey', '','Thomas’,''},  {'','','','',''},  {'','Chris','','',''},  {'','Harry','', 'Roger',''}, {'','','','',''}  } 
 
### Output :
"{{Simon,Sergey,Thomas},{Chris,Harry},{Roger}}"


### Input-2 :
 
  { {'Rajinder','',’Simon’,'',''},  {'',’Sergey', '','Thomas’,''},  {'','','','',''},  {'','Chris','','',''},  {'','Harry','', 'Roger',''}, {'','','','','RAJ'}  } 
 
 ### Output :
 
 "{{Rajinder,Sergey},{Simon,Thomas},{Chris,Harry},{Roger,RAJ}}"
 
  ## Tool, Features and design pattern Used:
 
 VS 2017
 xUnit
 Swagger UI for the API documentation.
 Dependency Injection
 Solid Principle
 
 
 ## How to test the Rest API
 
 
1. Set the project ThreePLClassRoom as startup project

2. Run the project and open http://localhost:50401/swagger/index.html URL.

3. Click on POST bar and then click on Try it out on right middle.

4. Provide the input data in the textbox.

{ {'','',’Simon’,'',''},  {'',’Sergey', '','Thomas’,''},  {'','','','',''},  {'','Chris','','',''},  {'','Harry','', 'Roger',''}, {'','','','',''}  } 

5. Click on Execute button and see the output string under Response body section
