**Student Event Registration System **

**Description**  
A web-based student event registration system that allows students to register for events and manage their registrations. The system uses a dynamic frontend and integrates with AWS services for backend processing and data storage.  

**Technologies Used**  
- Frontend: HTML, CSS, JavaScript  
- Backend: AWS Lambda, API Gateway, DynamoDB  
- Database: Amazon DynamoDB  
- Security & Authentication: AWS IAM  

How to Run the Project  
1. Clone the repository:  
   ```bash
   git clone https://github.com/Swathiyuva/Student-Event-Registration.git
   ```
2. Navigate to the project folder:  
   ```bash
   cd Student-Event-Registration
   ```
3. Open `index.html` in a browser to view the frontend.  
4. Ensure AWS Lambda and API Gateway are properly configured for backend functionality.  
5. Any updates made on the frontend will reflect in the AWS DynamoDB database.  

AWS Services Used
- AWS Lambda: Processes event registrations and updates student data.  
- Amazon API Gateway: Connects the frontend with AWS Lambda securely.  
- Amazon DynamoDB: Stores and retrieves student registration details efficiently.  
- AWS IAM: Manages authentication and access permissions for secure API calls.  

