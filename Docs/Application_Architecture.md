<h1> Assignment on Container Orchestration </h1>

## Architecture

| Service | Port | Description |
| --- | --- | --- |
| `adminService` | 3003 | Dedicated admin microservice for asset management and uploads |
| `frontend` | 3000 | React SPA with revamped UI and integrated chat |
| `mongo` | 27017 | Shared MongoDB instance 

All backend services share common database models and utilities through `backend/common`.

<h2>Task 1: Version Control with Git</h2>
Created the main repository into GitHub account to Maintain version by syncing/pushing updates from the main repository as needed.

<h2>Task 2: MERN Application Containerize the Application by Creating Dockerfiles for each component (Admin,Frontend and Backend)</h2>

