### API

Authorization and registration path is `api/auth`

 - Authorization `/auth`. Post request, body `{email: string, password: string}`  
 - Registration `/registation`. Method and body same.  
 - Logout `logout`. Post without body, resetting cookie  
 - New refresh token `login/access-token`. Post without body.  

 