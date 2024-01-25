<h2>Welcome to the Vue Js sample starter project!</h2>

Follow these simple steps to get started:<br>
Open your VsCode terminal.

Run:<br>
npm install<br>
npm run dev  <br>

Step 1:
Head over to https://developer.softrig.com and create an application with a <b>SPA client</b>:
Set the APP to "single tenant"<br>
Application Roles: Sales.Admin<br>
Add redirect/logout urls: http://127.0.0.1:5173 or/and http://localhost:5173<br>

Step 2:
Create a copy of the .env.example file, rename it to <b>.env</b> and fill in the values


VITE_IDENTITY_SERVER_BASE_URL="https://test-login.softrig.com"<br>
VITE_CLIENT_ID="(ADD_YOUR_SPA_CLIENTID)"<br>
VITE_IDENTITY_SERVER_SCOPES="openid profile AppFramework"<br>
VITE_REDIRECT_URL="http://127.0.0.1:5173"<br>
VITE_POST_LOGOUT_REDIRECT_URL="http://127.0.0.1:5173"<br>
VITE_SILENT_REDIRECT_UR="http://127.0.0.1:5173"<br>
VITE_API_BASE_URL="https://test.softrig.com/api"<br>


Step 4:
Log in with your SoftRig user/credentials<br>
On successful login, you will get a valid authentication JWT token in return.

Happy coding! :-)
