# Overview of the Project
- This project is a Spring Boot application that allows users to upload files through a web interface and download them later.
- The application uses Thymeleaf for rendering HTML views and has a structured service layer to handle file storage operations.

## Key Components
- `**StorageProperties**` : Configuration properties for file storage.
- `**FileUploadController**` : The main controller to handle file upload and download requests.
- `**StorageService and its Implementation (StorageServiceImpl)**` : Service to handle file storage operations.
- `**StorageException and StorageFileNotFoundException**` : Custom exceptions for error handling.
- `**Thymeleaf Template (uploadForm.html)**` : HTML template for the file upload interface.
## Key Endpoints:
- **`@GetMapping("/")`**: Lists all uploaded files.
- **`@GetMapping("/files/{filename:.+}")`**: Serves a file for download.
- **`@PostMapping("/")`**: Handles file upload.
![image](https://github.com/Sarthakverse/FileUploading/assets/117356021/880470b3-1204-4455-bf5a-3565d3651585)
![image](https://github.com/Sarthakverse/FileUploading/assets/117356021/d75e9ea5-df2e-4fc9-8932-124577d0f8fb)
![image](https://github.com/Sarthakverse/FileUploading/assets/117356021/83052ab2-8f59-4613-8b58-b3c52152db0f)



