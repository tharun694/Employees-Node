# Employees CRUD Application (Express MVC)

A Node.js and Express backend application for managing employee records. The core CRUD functionality of this project was built following the instructional guides by Dave Gray, with custom enhancements added to implement a strict MVC (Model-View-Controller) pattern and advanced update features.

## 🚀 Features

*   **Core CRUD Operations:** Full capabilities to Create, Read, Update, and Delete employee data.
*   **MVC Architecture:** Clean separation of concerns with dedicated layers for data logic (Models), request handling (Controllers), and routing.
*   **Enhanced Employee Management:** Custom-built features allowing precise modification of existing employee details.
*   **RESTful API Design:** Clean, semantic HTTP routing for seamless integration with frontend services.

---

## 🛠️ Tech Stack

*   **Runtime Environment:** Node.js
*   **Framework:** Express.js
*   **Architecture Pattern:** MVC (Model-View-Controller)

---

## 📂 Project Structure

```text
express_mvc/
├── config/             # Configuration files (DB connections, CORS, etc.)
├── controllers/        # Request handling logic (Process inputs, send responses)
├── model/              # Data schemas and manipulation logic
├── routes/             # API endpoint definitions
└── server.js           # Application entry point


⚙️ Getting StartedPrerequisitesMake sure you have Node.js installed on your machine.InstallationClone the repository to your local machine:Bash   git clone [https://github.com/tharun694/Employees-Node.git](https://github.com/tharun694/Employees-Node.git)
Navigate into the project directory:Bash   cd express_mvc
Install the required dependencies:Bash   npm install
Running the ApplicationTo start the server in development mode (using nodemon if configured):Bashnpm start
The server will typically spin up at http://localhost:3500 (or your configured PORT).📡 API EndpointsMethodEndpointDescriptionGET/employeesRetrieve all employeesGET/employees/:idGet details of a single employeePOST/employeesCreate a new employee recordPUT/employeesUpdate/Change existing employee detailsDELETE/employeesRemove an employee record🤝 AcknowledgmentsDave Gray — For the foundational tutorial and structural guidance on building Express applications.
