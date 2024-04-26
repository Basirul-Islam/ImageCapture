Html path url should be like this 
file:///P:/Plorea%20Horeca/Projects/CaptureImage/CaptureImage.html?username=myusername&password=mypassword&customerCardNumber=2156564658151561651&ApiUrl=https://localhost:44339/Image/TestEndpoint
It will contains four query parameters username, password, customerCardNumber and backend api url.
If all of those are provided perfectly then the camera dialog will be pop up.

Next to do: 
1. Change/create new Request model to pass username and password to the backend
2. Add an extra layer of validation/authentication if all the data are correct or not 