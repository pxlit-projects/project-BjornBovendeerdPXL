# Architecture

:heavy_check_mark:_(COMMENT) The application uses 3 microservices with a web app made in angular, these microservices communicate synchronously using open feign and asynchronously using a messagebus.

![image](https://github.com/user-attachments/assets/a30d6977-d1aa-4578-957f-19b7267a9000)



[link](https://github.com/pxlit-projects/project-BjornBovendeerdPXL/blob/main/architecture/architectuurdiagram.drawio.pdf)


## Synchroon
Het ophalen van posts, comments en reviews.

## Asynchroon
Het plaatsen van reviews en comments op bestaande posts.
