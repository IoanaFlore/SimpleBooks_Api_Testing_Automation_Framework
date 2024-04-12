# SimpleBooks_Api_Testing_Automation_Framework

The main objective of the current project is to test the "Simple Books API", and all the necessary information can be found in the documentation available 
at this [link](https://github.com/rescenic/postman-course/blob/main/simple-books-api.md). <br> The organization of the project is structured around three main directories:

## 1) "reports":
* This directory serves as a storage place for general reports, providing insight into the results of the tests performed. This section provides a clear picture of the integrity and correctness of the API functionality after testing.

![1](https://github.com/IoanaFlore/SimpleBooks_Api_Testing_Automation_Framework/assets/111995212/ed33b337-705d-423a-951f-37612b94464a)


## 2) "requests_folder":
This directory includes two essential Python files:
* "generate_token_requests": In this file, the operations required to obtain and keep the authentication token, essential for the proper functioning of the API, are managed.

![2](https://github.com/IoanaFlore/SimpleBooks_Api_Testing_Automation_Framework/assets/111995212/c6726066-1880-46ff-ba6b-358ea6a6c195)


* "simple_books_requests": This file houses general functions for performing various API operations, including sending commands, retrieving commands, and updating them.

![3](https://github.com/IoanaFlore/SimpleBooks_Api_Testing_Automation_Framework/assets/111995212/877bd3ed-bd3f-4d89-84a9-7ec132e87b54)

![4](https://github.com/IoanaFlore/SimpleBooks_Api_Testing_Automation_Framework/assets/111995212/d0afed53-22b7-4451-bf56-af9df6016645)

![5](https://github.com/IoanaFlore/SimpleBooks_Api_Testing_Automation_Framework/assets/111995212/f678319f-2e1c-4280-ac5f-70b9dbee6fa5)


## 3) "tests":
* This section includes separate Python files for implementing specific tests, focusing on different aspects of the API functionality. The modular approach allows for comprehensive and specific testing of every aspect of the API.

![6](https://github.com/IoanaFlore/SimpleBooks_Api_Testing_Automation_Framework/assets/111995212/b55c0712-d0b9-411e-add1-9253a48e56fe)

![7](https://github.com/IoanaFlore/SimpleBooks_Api_Testing_Automation_Framework/assets/111995212/6e020461-5c11-4f7a-9224-c35ac4f89e53)

![8](https://github.com/IoanaFlore/SimpleBooks_Api_Testing_Automation_Framework/assets/111995212/2da7ba91-f90a-4920-8ac7-ead89ed0401f)

![9](https://github.com/IoanaFlore/SimpleBooks_Api_Testing_Automation_Framework/assets/111995212/e1c6b1b1-6c3a-4154-a7ee-3165c17b72a0)

![10](https://github.com/IoanaFlore/SimpleBooks_Api_Testing_Automation_Framework/assets/111995212/ddd6fcd1-501f-42d6-ad53-6b0637eddcb7)

![11](https://github.com/IoanaFlore/SimpleBooks_Api_Testing_Automation_Framework/assets/111995212/d955c91b-e53e-4003-9c09-7dcd38fc39c9)

![12](https://github.com/IoanaFlore/SimpleBooks_Api_Testing_Automation_Framework/assets/111995212/b7859109-06db-47dd-bf59-0120009be08c)









The project uses the requests library to communicate with the API. Complete test execution is handled by an external Python file called "test_suit", which implements API methods including get, post, patch, and delete.

<img src="imagini-pycharm/test_suit.PNG" width="900" height="500">

This well-defined structure facilitates the management and continuous development of tests, providing transparency and a clear understanding of the results and functionality tested. All these tests were originally written using the Postman tool and then converted using the PyCharm IDE and Python language to run automatically.

<img src="imagini-postman/api-autentification.PNG" width="900" height="500">

<img src="imagini-postman/get-api-status.PNG" width="900" height="500">

<img src="imagini-postman/get-list-of-books.PNG" width="900" height="500">

<img src="imagini-postman/update-an-order.PNG" width="900" height="500">

<img src="imagini-postman/delete-an-order.PNG" width="900" height="500">
