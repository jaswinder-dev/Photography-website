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
        cd photography-website
      </code>
    </pre>
  </li>

  <li><b>Install dependencies:</b>
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

  <li><b>Run the development server:</b>
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

