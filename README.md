# RetailAutomation
Retail Website Automation 🚀  A Selenium-based automation framework for testing retail e-commerce websites using Java, TestNG, BDD (Cucumber), Maven, and Apache POI. Covers key workflows like login, product search, cart management, and checkout with data-driven testing and CI/CD integration.

🛠 Tech Stack
Language: Java
Automation Tool: Selenium WebDriver
Test Framework: TestNG & Cucumber (BDD)
Build Tool: Maven
Data Handling: Apache POI (Excel)
Version Control: GitHub
CI/CD: Jenkins/GitHub Actions
📌 Features
✅ Automated test cases for key retail functionalities
✅ Page Object Model (POM) for better maintainability
✅ Data-driven testing using Excel (Apache POI)
✅ Cross-browser testing (Chrome, Firefox, Edge)
✅ TestNG-based execution with detailed reporting
✅ CI/CD pipeline integration

📂 Project Structure
bash
Copy
Edit
/src  
  /main/java  
    /pages       # Page Object Model classes  
    /utils       # Utility classes (Excel handling, configs)  
  /test/java  
    /tests       # Test classes  
    /stepDefs    # Cucumber Step Definitions  
  /resources  
    /features    # Cucumber feature files  
    /testData    # Excel files for test data  
pom.xml         # Maven dependencies  
README.md       # Project documentation  
🚀 Setup & Run Instructions
1️⃣ Clone the Repository
sh
Copy
Edit
git clone https://github.com/your-username/your-repo.git
cd your-repo
2️⃣ Install Dependencies
Ensure you have Java (JDK 11+), Maven, and a WebDriver (Chrome/Gecko) installed. Then run:

sh
Copy
Edit
mvn clean install
3️⃣ Run Tests
TestNG:
sh
Copy
Edit
mvn test
Cucumber (BDD):
sh
Copy
Edit
mvn test -Dcucumber.options="--tags @SmokeTest"
4️⃣ View Reports
TestNG Report: target/surefire-reports/index.html
Cucumber Report: target/cucumber-reports/index.html
🤝 Contributing
Feel free to raise issues or submit pull requests for improvements!

📜 License
This project is licensed under the MIT License.

