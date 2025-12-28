<h1 align="center">🏦 MiniBankingApp</h1>
<p align="center">
  A console-based banking application built using <b>Java</b>, <b>JDBC</b>, and <b>MySQL</b>
</p>

<hr>

<h2>📌 Project Overview</h2>
<p>
MiniBankingApp is a simple console-based banking system developed to understand
<b>JDBC connectivity</b>, <b>database operations</b>, and <b>Java I/O handling</b>.
It allows users to create an account and log in using credentials stored in a MySQL database.
</p>

<h2>📁 Project Structure</h2>

<pre>
MiniBankingApp/
│
├── src/
│   └── banking/
│       ├── bank.java
│       ├── bankManagement.java
│       └── connection.java
│
├── .idea/
├── .gitignore
├── MiniBankingApp.iml
└── README.md
</pre>

<h2>🚀 Features</h2>
<ul>
  <li>Create a new bank account</li>
  <li>Login using username and password</li>
  <li>JDBC-based MySQL database integration</li>
  <li>Menu-driven console interface</li>
  <li>Exception handling for invalid inputs</li>
</ul>

<h2>🛠️ Tech Stack</h2>
<ul>
  <li><b>Language:</b> Java</li>
  <li><b>Database:</b> MySQL</li>
  <li><b>Backend:</b> JDBC</li>
  <li><b>IDE:</b> IntelliJ IDEA</li>
  <li><b>JDK:</b> Java 21</li>
</ul>

<h2>⚙️ How It Works</h2>
<ol>
  <li>User selects an option from the menu</li>
  <li>Input is taken using <code>BufferedReader</code></li>
  <li>Logic is handled in <code>bankManagement</code> class</li>
  <li>Database interaction is done via JDBC</li>
  <li>Result is displayed on the console</li>
</ol>

<h2>🗄️ Database Schema (Sample)</h2>

<pre>
CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(50) UNIQUE NOT NULL,
    password INT NOT NULL
);
</pre>

<h2>▶️ How to Run</h2>
<ol>
  <li>Clone the repository</li>
  <li>Open in IntelliJ IDEA</li>
  <li>Add MySQL JDBC connector</li>
  <li>Configure database credentials in <code>connection.java</code></li>
  <li>Run <code>bank.java</code></li>
</ol>
