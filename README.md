# Full Stack Project Assessment: File Upload and Saving Functionality

## Project Overview
Develop a full-stack web application that allows users to upload files, store them in a MySQL database, and retrieve them when needed. The project will utilize **React** for the frontend, **FastAPI** for the backend, and **MySQL** for database storage.

## Functional Requirements
1. **File Upload & Management**
   - Users can upload files through the frontend.
   - Files should be stored either in the database as BLOBs or in a file system with metadata saved in MySQL.
   - Users can view and download uploaded files.
   
2. **User Dashboard**
   - Users can see a list of uploaded files.
   - Each file should display details like name, type, size, and upload date.
   
3. **API Endpoints**
   - Endpoints for file upload, retrieval, and deletion.
   - Secure API access with authentication and authorization.
   
4. **Database Design**
   - Files table (id, filename, file_type, file_size, storage_path or file_data).

## Technical Requirements
### **Frontend (React)**
- React with functional components and hooks.
- Axios for API calls.
- React Router for navigation.
- Form handling for file uploads.
- Display uploaded files using a table or card-based UI.

### **Backend (FastAPI)**
- FastAPI for handling requests.
- Pydantic for data validation.
- SQLAlchemy for ORM integration with MySQL.
- File handling logic (storing in DB or file system).

### **Database (MySQL)**
- Use MySQL to store file metadata.
- Optimize storage by choosing between storing files as BLOBs or using file paths.

## Non-Functional Requirements
- **Security**: Implement authentication and access control.
- **Performance**: Optimize API and database queries.
- **Scalability**: Design the system to handle multiple users and large files efficiently.
- **Error Handling**: Provide meaningful error messages and validations.

## Development Plan
1. **Setup Environment**
   - Configure React, FastAPI, and MySQL locally or using Docker.
   
2. **Build Frontend**
   - Create UI components for file upload and display.
   - Implement API calls using Axios.
   
3. **Develop Backend APIs**
   - Build file upload and retrieval endpoints.
   - Handle database interactions.
   
4. **Integrate Frontend and Backend**
   - Connect React with FastAPI endpoints.
   - Handle file uploads and downloads properly.
   
5. **Testing and Deployment**
   - Perform unit and integration testing.
   - Deploy using cloud services (AWS, Heroku, etc.).

## Assessment Criteria
- **Correctness**: Functional APIs and UI.
- **Code Quality**: Clean and maintainable code.
- **Security**: Secure file handling.
- **Performance**: Optimized queries and efficient file storage.
- **Documentation**: Clear API and database documentation.

## Conclusion
This project will help in understanding full-stack development with **React, FastAPI, and MySQL** while implementing file upload and storage functionalities securely and efficiently.

