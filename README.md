# Comment App

**A Spring MVC assessment application with a login flow and comment filtering.**

This repository preserves the project download link and local setup instructions. The application source is distributed separately in the original assessment archive; it is not checked into this repository.

## Application flow

The original instructions describe a login page followed by a comments view, where comments can be filtered for logged-in and logged-out users.

## Get the source archive

[Open the original assessment archive on Google Drive](https://drive.google.com/file/d/1sFoOrwBO-H6t5teNXF9YSSX4u8J95Wnn/view?usp=sharing).

Archive availability and access depend on the external Drive link. After extracting it, check `resources/run_instruction.txt` for the project-specific instructions supplied with the assessment.

## Local setup

The original setup uses **Eclipse** with **Apache Tomcat 8.5**. Check the required Java version and complete dependency list in the downloaded project.

1. Download and extract the assessment archive.
2. In Eclipse, choose **File → Open Projects from File System**, select the extracted project directory, and finish the import.
3. Configure a Tomcat 8.5 server in Eclipse.
4. Right-click the imported app and select **Run As → Run on Server**.
5. Select the configured Tomcat server, add the app, and finish.
6. Open the entry point:

```text
http://localhost:8080/SpringMVC22/yahoo
```

The expected page is the login form. Submit it to continue to the comments view.

## Repository contents

| Item | Availability |
| :--- | :--- |
| Setup and launch instructions | This README |
| App source and bundled run instructions | External assessment archive |
| Build configuration and automated tests | Not included in this repository |

**Author:** [Puneeth R](https://github.com/puneethx47)
