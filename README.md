The Restful Booker API allows you to perform operations related to booking hotels. 

Import the Restful Booker Collection:

If you don't have the Restful Booker Collection in Postman, you can find it in the Postman API Network or online resources. Import it into your Postman workspace. 

Set the Environment:

Make sure you have an environment set up in Postman for Restful Booker. This environment should contain variables for the base URL of the Restful Booker API. You can create an environment by clicking on the gear icon in the upper right corner of the Postman window.

1)Create a New Booking:

Open the "Create Booking" request from the Restful Booker Collection.

Set Request Method and URL:

1.In the request details, ensure that the HTTP method is set to POST.
2.Set the URL to {{base_url}}/booking.

Send the Request:

Click the "Send" button to make the POST request to create a new booking.

View Response:

Postman will display the response from the API, which will include the booking ID and other details of the newly created booking.

2)GET:

Create a GET Request

1.Inside your collection, create a new request for retrieving data using the GET method.

2.Set the request method to GET.

3.Specify the API endpoint URL you want to retrieve data from.

4.Add any necessary headers or query parameters.

3) Send the GET Request

1.Click the "Send" button to execute the GET request.

2.Postman will display the response from the API, typically showing the data you requested.

4) Create a PUT Request

1.Create a new request in your collection for updating a resource using the PUT method.

2.Set the request method to PUT.

3.Specify the API endpoint URL for the resource you want to update.

4.Include the updated data in the request body.

5) Send the PUT Request

1.Click the "Send" button to execute the PUT request.

2.The API will replace the existing resource with the data you provided in the request body.

6)Create a PATCH Request

1.Create a new request for making partial updates to a resource using the PATCH method.

2.Set the request method to PATCH.

3.Specify the API endpoint URL for the resource you want to update partially.

4.Include only the fields that need to be updated in the request body.

7)Send the PATCH Request

1.Click the "Send" button to execute the PATCH request.

2.The API will update only the specified fields of the resource.

8)Create a POST Request

1.Create a new request for creating a new resource using the POST method.

2.Set the request method to POST.

3.Specify the API endpoint URL where you want to create the new resource.

4.Include the data for the new resource in the request body.

9)Send the POST Request

1.Click the "Send" button to execute the POST request.

2.The API will create a new resource using the data you provided.

10)Create a DELETE Request

1.Create a new request for deleting a resource using the DELETE method.

2.Set the request method to DELETE.

3.Specify the API endpoint URL for the resource you want to delete.

10)Send the DELETE Request

1.Click the "Send" button to execute the DELETE request.

2.The API will remove the specified resource.

TOKEN GENERATOR:

Token generation in a PUT request typically involves sending a request to the server to create or regenerate a token, such as an authentication token or an access token. 

1.Set Request Method and URL:

In Postman, open a new PUT request.

Set the URL to the endpoint responsible for token generation.

2.Request Headers:

Ensure you set any necessary headers for the request, such as Content-Type and authorization headers if required.

3.Request Body:

If the token generation requires specific data in the request body, provide the necessary information. The format of the request body will depend on the API's requirements.

4.Send the Request:

Click the "Send" button to make the PUT request to the token generation endpoint.

5.Receive the Response:

The response will typically include the generated token. Parse the response to extract the token and store it for future use.

I have made used of these token in URL to get the booking details.

ENVIRONMENT VARIABLES:


In Postman, you can create environments to group related variables. To create an environment, click on the gear icon in the upper right corner of the Postman window and select "Add" under the "Environments" section.

1)Define Variables:

Inside the environment, you can define variables with key-value pairs. For example, you can set a variable named base_url with a value .

2)Reference Variables in Requests:

To use these variables in your requests, you can reference them using double curly braces. 

3)Switching Environments:

You can switch between different environments for testing different configurations. Postman allows you to select the active environment from the top-right corner of the Postman window.


ASSERTIONS:

1)Status Code Assertion

2)Response Body Assertions

3)Header Assertions

4)Schema Validation

5)Response Time Assertions

Go to the "Tests" tab.

Write JavaScript code to perform assertions using the pm.expect function. For example, to check the status code, you can use pm.expect(responseCode).to.equal(200);.

Save the request.

When you send the request, Postman will run the assertions, and if any assertion fails, it will be highlighted in the test results.

CSV /TXT FILE:

I have also did this project using csv file and txt file , byt just clicking add  file button .Upload the file , the type of file changes automatically.

Now click the send request button .








