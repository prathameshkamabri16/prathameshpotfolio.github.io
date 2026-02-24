<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>FY BSc IT Portfolio</title>

  <!-- Font Awesome for Social Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: black;
      color: white;
      margin: 0;
    }

    header {
      background-color: #708090;
      padding: 30px 20px;
    }

    .social-icons {
      text-align: right;
      margin-bottom: 15px;
    }

    .social-icons a {
      color: white;
      font-size: 22px;
      margin-left: 15px;
      transition: 0.3s ease;
    }

    .social-icons a:hover {
      color: #16a085;
      transform: scale(1.2);
    }

    .header-content {
      display: flex;
      align-items: center;
      justify-content: space-between;
      max-width: 1200px;
      margin: auto;
      gap: 20px;
    }

    .header-text h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    .header-text p {
      font-size: 1.1rem;
      opacity: 0.9;
      line-height: 1.5;
    }
.profile-pic {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    object-fit: cover;
    border: 4px solid #333;
}
    .header-image {
      width: 440px;
      height: 220px;
      overflow: hidden;
      border-radius: 15px;
    }

    .header-image img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      transition: transform 0.5s ease;
    }

    .header-image:hover img {
      transform: scale(1.15);
    }

    .container {
      width: 90%;
      margin: auto;
      margin-top: 20px;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 15px;
    }

    .card {
      background-color: #1e1e1e;
      border: 1px solid #444;
      border-radius: 8px;
      overflow: hidden;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 20px rgba(0,0,0,0.3);
    }

    /* IMAGE ZOOM EFFECT ADDED HERE */
    .card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
      transition: transform 0.5s ease;
    }

    .card:hover img {
      transform: scale(1.15);
    }

    .info {
      padding: 10px;
      font-size: 14px;
    }

    .info h3 {
      margin: 5px 0;
    }

    .info p {
      color: #cccccc;
    }

    .form-container {
      background-color: #1e1e1e;
      padding: 20px;
      margin-top: 40px;
      border-radius: 8px;
      border: 1px solid #444;
      width: 100%;
      max-width: 500px;
      margin-left: auto;
      margin-right: auto;
    }

    .form-container h2 {
      text-align: center;
      margin-bottom: 15px;
      color: #1f7a5c;
    }

    .form-container label {
      display: block;
      margin-top: 10px;
      font-weight: bold;
    }

    .form-container input {
      width: 100%;
      padding: 8px;
      margin-top: 5px;
      border-radius: 5px;
      border: 1px solid #555;
      background-color: #111;
      color: white;
    }

     .form-container button {
      margin-top: 15px;
      width: 100%;
      padding: 10px;
      border: none;
      background-color: #1f7a5c;
      color: white;
      font-size: 16px;
      border-radius: 5px;
      cursor: pointer;
      transition: 0.3s ease;
    }

    .form-container button:hover {
      background-color: #16a085;
    }

    footer {
      text-align: center;
      padding: 15px;
      margin-top: 20px;
      background-color: #111;
      color: #cccccc;
    }

    @media (max-width: 768px) {
      .gallery {
        grid-template-columns: repeat(2, 1fr);
      }

      .header-content {
        flex-direction: column;
        text-align: center;
      }

      .header-image {
        width: 180px;
        height: 180px;
        margin-top: 15px;
      }
    }

    @media (max-width: 500px) {
      .gallery {
        grid-template-columns: 1fr;
      }
    }
#contact {
  width: 50%;
  margin: 0;
  padding: 30px 0;
}

form {
  display: flex;
  flex-direction: column;
}

.form-group {
  margin-bottom: 15px;
}

input, textarea {
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

button {
  padding: 10px;
  background-color: #007bff;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

button:hover {
  background-color: #0056b3;
}
  </style>
</head>
<body>

<header>

  <div class="social-icons">
    <a href="https://github.com/prathameshkamabri16/prathamesh.github.io" target="_blank">
      <i class="fab fa-github"></i>
    </a>
    <a href="https://www.instagram.com/your-username" target="_blank">
      <i class="fab fa-instagram"></i>
    </a>
    <a href="https://www.facebook.com/your-username" target="_blank">
      <i class="fab fa-facebook"></i>
    </a>
    <a href="https://www.youtube.com/@your-channel" target="_blank">
      <i class="fab fa-youtube"></i>
    </a>
  </div>

  <div class="header-content">
    <div class="header-text">
      <h1>Prathamesh Portfolio</h1>
      <p>Hello, I’m Prathamesh Kambari, a First Year B.Sc. IT student with a strong interest in web development. 
I have knowledge of HTML, CSS, and JavaScript, and I enjoy building responsive and user-friendly websites. 
I am continuously learning new technologies to improve my skills and grow as a professional developer.</p>
    </div>

    <div class="header-image">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSVEyR7-WTqw9trB4jMVTdR64wuHkJ-0MUccw&s">
    </div>
  </div>

</header>

<div class="container">

  <div class="gallery">

   <a href="https://www.w3schools.com/" target="_blank" style="text-decoration: none; color: inherit;">
  <div class="card">
    <img src="https://images.unsplash.com/photo-1517694712202-14dd9538aa97?w=800">
    <div class="info">
      <h3>Programming</h3>
      <p>Languages: C, C++, Java</p>
    </div>
  </div>
</a>

   <a href="https://developer.mozilla.org/en-US/docs/Learn" target="_blank" style="text-decoration: none; color: inherit;">
  <div class="card">
    <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?w=800">
    <div class="info">
      <h3>Web Development</h3>
      <p>HTML, CSS</p>
    </div>
  </div>
</a>

   <a href="https://www.tensorflow.org/" target="_blank" style="text-decoration: none; color: inherit;">
  <div class="card">
    <img src="https://images.unsplash.com/photo-1555949963-aa79dcee981c?w=800">
    <div class="info">
      <h3>Machine Learning</h3>
      <p>Python</p>
    </div>
  </div>
</a>


 <a href="https://www.ibm.com/topics/internet-of-things" target="_blank" style="text-decoration: none; color: inherit;">

    <div class="card">
      <img src="https://images.unsplash.com/photo-1550751827-4bd374c3f58b?w=800">
      <div class="info">
        <h3>Cyber Security</h3>
        <p>Network & Data Protection</p>
      </div>
    </div>

    <a href="https://www.ibm.com/topics/internet-of-things" target="_blank" style="text-decoration: none; color: inherit;">
  <div class="card">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS7b0ny1ak9alJZ5bPgDyVvTzwcoqhnLovbpg&s?w=800">
    <div class="info">
      <h3>Internet of Things (IoT)</h3>
      <p>Smart Devices & Automation</p>
    </div>
  </div>
</a>

  <a href="https://aws.amazon.com/" target="_blank" style="text-decoration: none; color: inherit;">
  <div class="card">
    <img src="https://images.unsplash.com/photo-1451187580459-43490279c0fa?w=800">
    <div class="info">
      <h3>Cloud Computing</h3>
      <p>AWS, Azure, Google Cloud</p>
    </div>
  </div>
</a>

  </div>

  <div class="form-container">
    <h2>Submit Your Details</h2>
    <form>
 <div class="form-group">
     
      <input type="text" id="name" name="name" placeholder="prathamesh..." required><br><br></div>
<div class="form-group">
      <input type="email" id="email" name="email" placeholder="prathamesh@gmail.com......." required><br><br>
</div>
<div class="form-group">
       <textarea id="message" name="message" placeholder="Write your message..."></textarea>
</div>
      <button type="submit">Submit</button>
    </form>
  </div>

</div>

<footer>
  <p>Created by PRATHAMESH KAMBARI | FYBSc IT</p>
</footer>

</body>
</html>
