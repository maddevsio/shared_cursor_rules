Set up environment variable management for the project:
Create separate .env files for different environments:
- .env.development (dev)
- .env.staging (staging)
- .env.production (production)
Ensure the project loads the correct .env file based on the environment.
Create a .env.example file listing all required environment variables (without sensitive values)
