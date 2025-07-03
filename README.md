<h1>✈️ Vacation Reservation System – Backend</h1>
<p><strong></strong> A Spring Boot REST API backend for a vacation reservation system.<br/>
Angular front-end integration · MySQL backend · RESTful API design</p>

<h3>📦 Features</h3>
<ul>
  <li>🔁 REST API fully integrated with Angular front-end</li>
  <li>✅ Input validation for customer and cart info</li>
  <li>🛒 Add vacations + excursions to customer orders</li>
  <li>🧾 Auto-generates order tracking numbers</li>
</ul>

<h3>🚧 Project Structure</h3>
<pre>
demo
├── src
│   └── main
│       ├── java
│       │   └── com
│       │       └── example
│       │           └── demo
│       │               ├── config
│       │               ├── controllers
│       │               ├── dao
│       │               ├── entities
│       │               ├── services
│       │               └── DemoApplication.java
│       └── resources
└── pom.xml
</pre>



<h3> 🧱 Tech Stack : </h3> 
<div align="left">
<a href="https://www.java.com" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="40" height="40" alt="Java"/></a>
<a href="https://spring.io/projects/spring-boot" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" width="40" height="40" alt="Spring Boot"/></a>
<a href="https://www.jetbrains.com/idea/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/intellij/intellij-original.svg" width="40" height="40" alt="IntelliJ IDEA"/></a>
<a href="https://www.postman.com/" target="_blank"><img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" width="40" height="40" alt="Postman"/></a>
<a href="https://gitlab.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gitlab/gitlab-original.svg" width="40" height="40" alt="GitLab"/></a>
<a href="https://www.mysql.com/" target="_blank">
  <img src="https://upload.wikimedia.org/wikipedia/en/d/dd/MySQL_logo.svg" width="40" height="40" alt="MySQL"/>
</a>

</div>



<h2>📸 Screenshots</h2>

<h3> 1. Excursion API Endpoint Test (GET /api/excursions)  </h3>
📄 Screenshot:  
<img src="images/api:excursion..png" width="400">

This captures the successful retrieval of excursion data via Postman. It verifies that the backend exposes excursion-related API and returns proper HAL+JSON with excursion_title, excursion_price, and related links.

---

 <h3> 2. MySQL Database: Excursion Cart Table  </h3>
📄 Screenshot:  
<img src="images/sql:data.png" width="400">

The MySQL Workbench screenshot shows the `excursion_cartitem` table from the database. It proves database records are correctly created and linked, enabling the backend to connect excursions to cart items.


