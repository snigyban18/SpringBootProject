  ## Quickstart

1. Clone the repository
2. Open the project in your IDE: IntelliJ IDEA (recommended) or Eclipse or VS Code
    * If you are using IntelliJ IDEA, make sure the IDE opens project as **Maven** and recognizes the project as a Spring Boot project. Also, you must change the working directory of the project so that the views (the actual web pages to be shown) are found by Spring Boot (check out [Web Directories IntelliJ IDEA](#web-directories).
3. Make sure you are in the `JtProject` directory
4. Configure the database connection in `application.properties` file (check the [Database](#database) section below for more info)
5. Run the project (by running the `main` method in `JtSpringProjectApplication.java`)
6. Open http://localhost:8080/ in your browser!
   * If you ran the [`basedata.sql`](https://github.com/snigyban18/E-commerce-project-springBoot/blob/master/JtProject/basedata.sql)script on the database, you can log in with the following credentials as admin; otherwise you'll have to manually create an admin user in the database:
     * Username: `admin`
     * Password: `123`
   * Log in as a normal user:
     * Username: `lisa`
     * Password: `765`
