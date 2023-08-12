<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GitHub Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f5f5;
    }
    .header {
      background-color: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
    }
    .profile {
      display: flex;
      align-items: center;
      margin-bottom: 20px;
    }
    .profile img {
      width: 50px;
      height: 50px;
      border-radius: 50%;
      margin-right: 10px;
    }
    .projects {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
    }
    .project {
      background-color: #fff;
      border: 1px solid #ddd;
      padding: 20px;
      margin: 10px 0;
      flex-basis: calc(33.33% - 20px);
    }
    .project img {
      max-width: 100%;
      height: auto;
    }
    .project a {
      display: inline-block;
      margin-top: 10px;
      background-color: #333;
      color: #fff;
      padding: 8px 12px;
      text-decoration: none;
      border-radius: 4px;
    }
    .project a:hover {
      background-color: #555;
    }
    .project h5 {
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <div class="header">
    <h1>Welcome to my GitHub 👋</h1>
    <div class="profile">
      <img src="profile-image-url" alt="Profile Image">
      <p>Fullstack Developer | React.js & Next.js | Node.js | Express.js | Python | Java | MongoDB & MySQL</p>
    </div>
  </div>
  <div class="container">
    <h2>RECENT PROJECTS</h2>
    <div class="projects">
      <!-- Repeat the following project structure for each project -->
      <div class="project">
        <img src="project-image-url" alt="Project Image">
        <h3>Project Title</h3>
        <h5>Technologies</h5>
        <ul>
          <li>Technology 1</li>
          <li>Technology 2</li>
          <!-- Add more technologies as needed -->
        </ul>
        <a href="project-url" target="_blank">View Project</a>
      </div>
      <!-- Repeat the project structure end -->
    </div>
  </div>
</body>
</html>
