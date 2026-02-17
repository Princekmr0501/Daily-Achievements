## STARTED WORKING ON A NEW PROJECT : `WORKSPACE`
* This is a `multi Tenant SaaS` application where different organizations can do their works without interruption or mixing of the data.
* Organizations can Register themselves and do their daily routine tasks like creating and modifying files.
* Every organization will be authorized with `JWT ` tokens and `Argon 2` will be used for hashing of the passwords so that there is less security breach and data leaks .
* we will use `Postgre SQL` for storing metadata and will store the main data i.e data inside files,photos ,videos inside `AWS S3`.
* This application will have a upgrade plan which will allow the organizations having `PRO` plan to attatch extra attatchements while `free` plan users will not get this facility.
* This project will be deployed on `AWS EC 2` so that it can be available for all users.
* Ther should be a `CI` pipeline which will check and fix my code before pushing it to the github repo.