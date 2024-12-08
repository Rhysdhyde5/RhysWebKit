<script>
    
  </script>
  
  <nav class="navbar">
    <ul>
      <li><a href="/">Projects</a></li>
      <li><a href="/about">About Me</a></li>
      <li><a href="/experience">Experience</a></li>
      <li><a href="/skills">Skills</a></li>
      <li><a href="/education">Education</a></li>
      <li><a href="/contact">Contact</a></li>
    </ul>
  </nav>
  
  <style>
  
    .navbar {
      background-color: #38443877;
      padding: 1rem;
      border-radius: 25px;
      scale: 1.1;
    }
  
    .navbar ul {
      list-style-type: none;
      display: flex;
      justify-content: space-around;
      margin: 0;
      padding: 0;
    }
  
    .navbar ul li {
      margin: 0 1rem;
    }
  
    .navbar ul li a {
      position: relative;
      padding: 10px 20px;
      color: #fff;
      text-decoration: none;
      font-weight: bold;
      background: rgba(255, 255, 255, 0);
      font-size: 16px;
      border-top-right-radius: 10px;
      border-bottom-left-radius: 10px;
      transition: all 1s;
      color: rgb(255, 255, 255); /* Set text color to white */
    }
  
    .navbar ul li a:after, 
    .navbar ul li a:before {
      content: " ";
      width: 10px;
      height: 10px;
      position: absolute;
      border: 0px solid #ffffff00;
      transition: all 1s;
    }
  
    .navbar ul li a:after {
      top: -1px;
      left: -1px;
      border-top: 5px solid rgb(255, 255, 255);
      border-left: 5px solid rgb(255, 255, 255);
    }
  
    .navbar ul li a:before {
      bottom: -1px;
      right: -1px;
      border-bottom: 5px solid rgb(255, 255, 255);
      border-right: 5px solid rgb(255, 255, 255);
    }
  
    .navbar ul li a:hover {
      border-top-right-radius: 0px;
      border-bottom-left-radius: 0px;
    }
  
    .navbar ul li a:hover:before, 
    .navbar ul li a:hover:after {
      width: 100%;
      height: 100%;
    }
  </style>