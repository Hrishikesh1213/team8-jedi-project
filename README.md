# team8-jedi-project

Our project supports these endpoints

    DELETE  /admin/dcourses (com.training.resources.AdminResource)
    POST    /admin/professor (com.training.resources.AdminResource)
    POST    /admin/student (com.training.resources.AdminResource)
    
    GET     /professor/course (com.training.resources.ProfessorResource)
    POST    /professor/{pid}/course/{cid} (com.training.resources.ProfessorResource)
    PUT     /professor/{pid}/course/{cid}/student/{sid}/grade (com.training.resources.ProfessorResource)
    GET     /professor/{pid}/course/{cid}/students (com.training.resources.ProfessorResource)
    
    GET     /students/coursecatalog (com.training.resources.StudentResource)
    GET     /students/{sid}/bill (com.training.resources.StudentResource)
    DELETE  /students/{sid}/courses/{cpid} (com.training.resources.StudentResource)
    POST    /students/{sid}/courses/{cpid} (com.training.resources.StudentResource)
    GET     /students/{sid}/myregisteredcourses (com.training.resources.StudentResource)
    POST    /students/{sid}/register (com.training.resources.StudentResource)
    GET     /students/{sid}/report (com.training.resources.StudentResource)
