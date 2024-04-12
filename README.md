# SimpleBooks_Api_Testing_Automation_Framework

The main objective of the current project is to test the "Simple Books API", and all the necessary information can be found in the documentation available 
at this [link](https://github.com/rescenic/postman-course/blob/main/simple-books-api.md). <br> The organization of the project is structured around three main directories:

## 1) "reports":
* This directory serves as a storage place for general reports, providing insight into the results of the tests performed. This section provides a clear picture of the integrity and correctness of the API functionality after testing.

<img src="imagini-pycharm/Api-Test-Report.png" width="900" height="500">

## 2) "requests_folder":
This directory includes two essential Python files:
* "generate_token_requests": In this file, the operations required to obtain and keep the authentication token, essential for the proper functioning of the API, are managed.

<img src="imagini-pycharm/generate_token_requests.PNG" width="900" height="500">

* "simple_books_requests": This file houses general functions for performing various API operations, including sending commands, retrieving commands, and updating them.

<img src="imagini-pycharm/simple_books_requests.PNG" width="900" height="500">
  
## 3) "tests":
* This section includes separate Python files for implementing specific tests, focusing on different aspects of the API functionality. The modular approach allows for comprehensive and specific testing of every aspect of the API.

<img src="imagini-pycharm/simple_books_requests.PNG" width="900" height="500">

<img src="imagini-pycharm/test_get_order.PNG" width="900" height="500">

<img src="imagini-pycharm/test_list_of_books.PNG" width="900" height="500">

<img src="imagini-pycharm/test_submit_order.PNG" width="900" height="500">

<img src="imagini-pycharm/test_update_order.PNG" width="900" height="500">

The project uses the requests library to communicate with the API. Complete test execution is handled by an external Python file called "test_suit", which implements API methods including get, post, patch, and delete.

<img src="imagini-pycharm/test_suit.PNG" width="900" height="500">

This well-defined structure facilitates the management and continuous development of tests, providing transparency and a clear understanding of the results and functionality tested. All these tests were originally written using the Postman tool and then converted using the PyCharm IDE and Python language to run automatically.

<img src="imagini-postman/api-autentification.PNG" width="900" height="500">

<img src="imagini-postman/get-api-status.PNG" width="900" height="500">

<img src="imagini-postman/get-list-of-books.PNG" width="900" height="500">

<img src="imagini-postman/update-an-order.PNG" width="900" height="500">

<img src="imagini-postman/delete-an-order.PNG" width="900" height="500">
