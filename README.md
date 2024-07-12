<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
 
</head>
<body>

  <h1>Amulya's Store</h1>

  <p>Amulya's Store is an eCommerce application built using the MERN (MongoDB, Express.js, React, Node.js) stack. This platform offers a comprehensive shopping experience, featuring user authentication, product management, a shopping cart, and secure order processing.</p>

  <h2>Features</h2>
  <ul>
    <li><strong>User Authentication:</strong>
      <ul>
        <li>Secure registration and login using JWT.</li>
        <li>Role-based access control.</li>
      </ul>
    </li>
    <li><strong>Product Management:</strong>
      <ul>
        <li>Admin interface for adding, updating, and deleting products.</li>
        <li>Detailed product descriptions, images, and pricing.</li>
      </ul>
    </li>
    <li><strong>Shopping Cart:</strong>
      <ul>
        <li>Persistent cart with real-time updates.</li>
      </ul>
    </li>
    <li><strong>Order Processing:</strong>
      <ul>
        <li>Secure checkout with payment gateway integration.</li>
        <li>Order history and tracking.</li>
      </ul>
    </li>
    <li><strong>Responsive Design:</strong>
      <ul>
        <li>Mobile-first approach for optimal viewing on all devices.</li>
      </ul>
    </li>
    <li><strong>State Management:</strong>
      <ul>
        <li>Redux for state management and asynchronous actions.</li>
      </ul>
    </li>
  </ul>

  <h2>Technologies Used</h2>
  <ul>
    <li><strong>Frontend:</strong>
      <ul>
        <li>React</li>
        <li>Redux</li>
        <li>HTML5</li>
        <li>CSS3</li>
        <li>JavaScript</li>
      </ul>
    </li>
    <li><strong>Backend:</strong>
      <ul>
        <li>Node.js</li>
        <li>Express.js</li>
      </ul>
    </li>
    <li><strong>Database:</strong>
      <ul>
        <li>MongoDB</li>
      </ul>
    </li>
    <li><strong>Authentication:</strong>
      <ul>
        <li>JSON Web Tokens (JWT)</li>
      </ul>
    </li>
  
  </ul>

  <h2>Installation</h2>
  <ol>
    <li><strong>Clone the repository:</strong>
      <pre><code>git clone https://github.com/Amulya432/amulyas-store.git</code></pre>
    </li>
    <li><strong>Navigate to the project directory:</strong>
      <pre><code>cd amulyas-store</code></pre>
    </li>
    <li><strong>Install dependencies for both frontend and backend:</strong>
      <pre><code># Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install</code></pre>
    </li>
    <li><strong>Set up environment variables:</strong>
      <p>Create a <code>.env</code> file in the <code>backend</code> directory with the following variables:</p>
      <pre><code>
