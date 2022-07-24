# FastApi_Mongo_JS
created an fastapi application which lets us to do mongodb crud operations through webpages
In this project we have an webpage which integrates with application of fast api framework and
interact with mongodb database for doing certain tasks. The tasks are adding an employee details in db,
updating employee details for a particular emp_id, sorting all employee documents based on salary field,
searching for an particular employee for a given employee id and getting all the employees.

Tools Used:
      DB : MongoDB
      API : FastApi
      Language : Python
      Frontend : JavaScript
Packages Used:
      fastapi==0.73.0
      uvicorn==0.17.4
      pydantic[email]~=1.9.1
      motor==2.5.1
      router~=0.1
      pymongo~=3.12.3
			
Roles and Work Contribution:
      RanaDev Paladugula : Frontend - JavaScript
      Karthik Musunuri : Github, MongoDB , Integration
      Ram Gorantla : Fast Api


      Ram Gorantla : 
            Ram contributed the work regarding creating an app, creating models and data validations . In app file ,
            creating an fastapi object and calling to routes menthod. And then running a server of unicorn so that all
            the tasks regarding to mongodb can be possible. Moreover, In models file , created an employee.py file. 
            In this file he implemented Schema of an employee i.e, how the data should be in db while inserting the data via api.
            And some responsemodels and response message methods. This methods are responsible for giving clear understanding of response 
            and error in case if we get. In data validation , for every field in schema there are some rules which has to be followed 
            while doing crud operations. creating an api’s for 5 different usecases. Namely, creating an employee, reterive employee, 
            reterive all employees, updating employee, deleting employee. And responsible for routing api’s to other method which are 
            mongodb method implemented all creud operations. And while implementing this api method , calling to responsemodel and errorresponsemodel.
            So that in api swagger ui , we can see the response message and error response message. Here implement get, put, post methods of api’s.
            while taking the parameters via swagger UI docs , it gives required fields and optional fileds with their description.
     Karthik Munsuri :
	          Karthik contributed the work regarding to mongodb. He connected python and mongodb using pymongo package. And implemented
            5 methods namely : adding an employee, reterive all employees , reterive employee by id, updating employee, sorting all 
            employees based on salary and deleting an employee . moreover implemented an employee_helper method this method takes dict
            and returns dict. The main intention of this method is to return the data in correct format so that readability increases. 
            Moreover, Tasks related to github. He commited the codes of each member of group.  Integrated Fastapi with mongodb, Fast api with
            Javascript. All setup and configurations of pycharm and roobo3t have been taken care by Karthik. 
            
      RANADEV PALADUGULA: 
	          I even have chipped away at the web page marking and assembled the website online parts with the assistance of HTML, CSS ,
            JQUERY, JSON AND JAVASCRIPT and made the overall plan for the touchdown page. Begun via including html for header, body and footer.
            Added html for Image diversion, top path menu and later on started out adding styles to this multitude of components. Then introduced
            usefulness for bash, route menu utilizing JavaScript
            In upload employee I have created full call, electronic mail identity,role, revel in and income, equal as in replace employee I used jQuery .
            Made each one of the necessary adjustments according to the show enter to fit the varieties, concern always throughout the pages, made 
            json variable and related with objects, delivered item portrayal and surveys and stuck the association problems.
            
            After achievement of the web site, carried out unit testing of the multitude of parts to guarantee the usefulness is filling in as
            I have chipped away at the web page marking and parts for the object portrayal page with the assistance of HTML, CSS, JQUERY,  AND 
            JAVASCRIPT. Begun by means of utilising the html made in landing web page for header, frame and footer into the item web page.
            Added CSS impacts for the item display cards and brought usefulness to reveal photos, object subtleties from variable making use of
            JavaScript/jQuery.
            Included symbols the pinnacle direction to peer truck, and to discover to the landing page.
            Utilized JavaScript/jQuery to expose the things at the tune page and added erase button at the truck and introduced its usefulness.

            Chipped away on the CSS to make the net composition responsive for the house and object portrayal web page. Utilized media questions 
            to attention on the page plan to in shape according to various gadgets.

            In get worker detail with the aid of id I used JavaScript in growing the worker id, complete call,electronic mail id ,function, 
            years of revel in and income.




