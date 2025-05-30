Implement global error handling and monitoring in the project:
- Create a global error boundary component to catch and gracefully handle runtime errors
- Mount error boundary on app boot
- Integrate {Sentry or other tool} for runtime error monitoring and reporting.
- Configure {Sentry or other tool} with proper initialization, including environment and release tracking.
- Ensure errors caught by the error boundary are reported to {Sentry or other tool}.
