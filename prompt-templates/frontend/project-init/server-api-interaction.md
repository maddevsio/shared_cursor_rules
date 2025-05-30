Set up server interaction in the project using Axios:
- Configure Axios with a base URL for API requests.
- Implement request and response interceptors to:
  - Attach access tokens to outgoing requests. 
  - Handle automatic token refresh using refresh tokens on authorization failures. 
  - Manage errors globally. 
- Implement access and refresh token handling logic, including secure storage and token renewal flow. 
- Set a request timeout
