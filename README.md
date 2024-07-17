# Photography Website Project

## Overview
<p>This project is a fully functional photography website developed using the <strong>MERN stack</strong> (MongoDB, Express.js, React.js, Node.js). The website features secure password encryption, user authentication and authorization, an interactive UI/UX, and a responsive design, ensuring optimal viewing experiences across all devices.</p>

## Features
<ul>
  <li><b>Password Encryption:</b> Ensures that user passwords are stored securely.</li>
  <li><b>User Authentication & Authorization:</b> Provides secure login and access control for users.</li>
  <li><b>Interactive UI/UX:</b> Delivers a user-friendly and engaging interface.</li>
  <li><b>Responsive Design:</b> Ensures the website looks great and functions well on all device sizes.</li>
</ul>

## Technologies Used
<ul>
  <li><b>Frontend:</b> React.js</li>
  <li><b>Backend:</b> Node.js, Express.js</li>
  <li><b>Database:</b> MongoDB</li>
  <li><b>Other Libraries:</b> Swipper.js, AOS (check "package.json" for more information)</li>
</ul>

## Installation

<p>To run this project locally, follow these steps:</p>

<ol>
  <li><b>Clone the repository:</b>
    <pre>
      <code>
        git clone https://github.com/jaswinder-dev/Photography-website.git
        cd Photography-website
      </code>
    </pre>
  </li>

  <li><b>Install dependencies: (for each frontend & backend, separately)</b>
    <pre>
      <code>
        npm install
      </code>
    </pre>
  </li>

  <li><b>Set up environment variables:</b> 
    <p>Create "<code>.env</code>" files in both directories (frontend & backend). Assign them values accordingly:</p>
    <pre>
      <b>backend/.env :</b>
      <code>
          HOST=
          PORT=
          MONGO_URL=
          FRONTEND_URL=
          DATABASE=
          SECRET_KEY=
          JWT_EXPIRES=
          COOKIE_EXPIRES=
      </code>
    </pre>
    <pre>
      <b>fontend/.env :</b>
      <code>
         VITE_ROUTE=
         VITE_BACKEND_BASE_URI=
      </code>
    </pre>
  </li>

  <li><b>Run the development server: (for each frontend & backend, separately)</b>
    <pre>
      <code>
        npm run dev
      </code>
    </pre>
  </li>

</ol>

## Description of '.env' variables
<ul>
  <li>HOST : website host</li>
  <li>PORT : port number</li>
  <li>MONGO_URL : url for mongodb database</li>
  <li>FRONTEND_URL : url of the page fornt-end that will access the backend</li>
  <li>DATABASE : name of the database</li>
  <li>SECRET_KEY : key for authentication</li>
  <li>JWT_EXPIRES : time in days for expiring jwt-token (7d = 7 days)</li>
  <li>COOKIE_EXPIRES : cookie expiry time (7)</li>
  <li>VITE_ROUTE : variable to access the admin pannel</li>
  <li>VITE_BACKEND_BASE_URI : url of the back-end</li>
</ul>

## Contact Information
<p>Designed and developed by: <strong>Jaswinder Singh</strong></p>

<ul>
  <li><b>Email:</b> <a href="mailto:jaswinderdev26@gmail.com">jaswinderdev26@gmail.com</a></li>
  <li><b>Contact No.:</b> +91 8847607834</li>
  <li><b>LinkedIn:</b> <a href="https://linkedin.com/in/jaswinder-singh-68a67b2b0/">@Jaswinder Singh</a></li>
</ul>

## License
<p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>

## Acknowledgements
<p><a href="https://youtu.be/RzHXy0uj6Cs?si=bTNrldb2XDXdH6i_">Web Design Matery</a></p>
<p>A screenshot was taken from this website for the design. code is developer's own.</p>

## Screenshots
<p><b>Landing page :</b></p>

![landing_page](https://github.com/user-attachments/assets/08777a0e-736b-4b0d-86b9-728f8e10e7ef)
![intro](https://github.com/user-attachments/assets/e0818912-6317-4eed-a484-10bdd9dbfe44)
![portfolios](https://github.com/user-attachments/assets/b8d1f1fb-c0de-4b19-a6ce-c80573664f7c)
![service_testimony](https://github.com/user-attachments/assets/39c4035a-8685-4796-92eb-c3e55b50ded6)
![latest_blog](https://github.com/user-attachments/assets/0092a508-ef45-4ffc-8f63-0b7dff28a644)

<p><b>Admin's :</b></p>
<p>Login : </p>

![login](https://github.com/user-attachments/assets/39420aa1-5ede-4e7c-b13b-deec9e32c9f7)

<p><u>Profile : </u></p>

![profile](https://github.com/user-attachments/assets/3c7cd028-53e8-48b0-9c5b-5eeca7128f2e)

<p><u>Dashboard : </u></p>

![dashboard](https://github.com/user-attachments/assets/3052f302-bd2a-456e-a25c-5a239509532a)

<p><u>Edit Logo : </u></p>

![edit_logo](https://github.com/user-attachments/assets/505591ad-8696-433c-8237-58f702088957)

<p><u>Edit Banner : </u></p>

![edit_banner](https://github.com/user-attachments/assets/5833d144-d388-4f7c-a051-14bd92e32387)

<p><u>Edit Social links : </u></p>

![edit_socials](https://github.com/user-attachments/assets/2ec7735a-100d-44ea-bde1-4efe24bbde7a)

<p><u>Add Photographer : </u></p>

![add_artist](https://github.com/user-attachments/assets/f22f82b3-4178-48de-86e2-a5362b0f7566)

<p><u>Add Post : </u></p>

![add_post](https://github.com/user-attachments/assets/9ea34928-eaf5-47c3-a3a9-9344d3fd65ef)

<p><u>Add Blog : </u></p>

![add_blog](https://github.com/user-attachments/assets/5124bac7-506c-4b6a-b23f-b13c8d42e964)

<p><u>Add Portfolio : </u></p>

![add_portfolio](https://github.com/user-attachments/assets/8b979a3c-d343-4fbe-a4b5-5a2aa7a8dba5)

<p><u>Add Testimony : </u></p>

![add_testimony](https://github.com/user-attachments/assets/47b4db43-e991-4669-ae25-888b470a46cf)

<p><u>Add Service : </u></p>

![add_service](https://github.com/user-attachments/assets/e06efb1e-7746-4caa-856a-01f315fc88dd)

<p><b>Records : </b></p>

![photographers](https://github.com/user-attachments/assets/486c5a3e-60d6-47e2-af19-5924a0af3c83)
![posts](https://github.com/user-attachments/assets/107e3e75-e656-487f-977f-ee9332eb26cb)
![services](https://github.com/user-attachments/assets/8a49ab20-20d9-414b-8835-10bdaa724f91)
![portfolio](https://github.com/user-attachments/assets/fe829b0c-e2bc-4565-a498-f6fe761dc139)
![testimonies](https://github.com/user-attachments/assets/1a8d7676-2e30-4ac9-967d-6ca62bb69757)




