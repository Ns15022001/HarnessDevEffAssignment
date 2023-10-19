Building a REST API Project with Bazel and Spring Boot
Welcome to the "Building a REST API Project with Bazel and Spring Boot" project! This README provides detailed information on how to set up, code, and run a REST API project using Spring Boot and Bazel. Follow the steps below to get started.

Requirements
Before you begin, make sure you have the following requirements installed:

Java Development Kit (JDK): Ensure that you have the JDK installed on your system. You can download and install it from the official Oracle website.

Bazel: We use Bazel as our build tool. Install Bazel using the Scoop package manager on Windows or refer to the official Bazel installation guide for other platforms.

Git: You'll need Git to clone the example project from the Bazel repository.

Setup
Step 1: Installing JDK
Download the JDK installer for your system from the official website.
Run the installer and follow the installation instructions.
Set the JAVA_HOME environment variable to the JDK installation path. This is essential for the next steps.
Step 2: Installing Bazel with Scoop
Open PowerShell.

Execute the following command to install Scoop:

powershell
Copy code
iex (new-object net.webclient).downloadstring('https://get.scoop.sh')
Once Scoop is installed, install Bazel using the following command:

powershell
Copy code
scoop install bazel
Step 3: Cloning the Example Project
Clone the example project from the Bazel repository using the following command:

bash
Copy code
git clone <repository_url>
Coding
With the prerequisites in place, you can now start coding your REST API project. This project is built using Spring Boot and Bazel, so you can follow standard Spring Boot practices for creating endpoints, services, and controllers. Don't forget to implement the 'hello' endpoint as described in the video.

Demo
To run and test your REST API project, follow these steps:

Navigate to your project directory in the terminal.
Use Bazel to build and run your project:
bash
Copy code
bazel build //:your-api
bazel-bin/your-api
Your API should now be running, and you can access it through your browser or a tool like Postman. Make a GET request to the '/hello' endpoint to see it in action.
