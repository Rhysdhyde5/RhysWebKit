<script lang="ts">
    let name = "Rhys Hyde";
  
    const education = [
      { degree: "BcS Computer Science", grade: "2:1", school: "Swansea University", years: "2021-2024" },
      { degree: "A Level ICT", grade: "B", school: "Brynteg School", years: "2019-2021" },
      { degree: "A Level Physical Education", grade: "B", school: "Brynteg School", years: "2019-2021" },
      { degree: "A Level Psychology", grade: "C", school: "Brynteg School", years: "2019-2021" },
      { degree: "A Level Welsh Baccalaureate", grade: "C", school: "Brynteg School", years: "2019-2021" },
      { degree: "12 GCSE’s", grade: "A*-C", school: "Brynteg School", years: "2013-2018" },
    ];
  </script>
  
  
  <main>
    <section class="about">
      <h1>About Me</h1>
      <p>
        Computer science graduate who has a keen interest in website and application 
        development. Wanting to expand my knowledge learnt at university, and 
        start my computer science career. I am skilled at problem-solving in difficult situations, adapt 
        well to changes within a project and work well under pressure. I am currently looking to use my experience and 
        knowledge, and learn new skills in order to take the next step in my career.
      </p>
    </section>
  
    <section class="experience">
      <h2>Experience</h2>
      <div class="job">
        <h3>Dissertation / University Experience</h3>
        <p>2021 - 2024</p>
        <ul>
          <li>Developed crucial skills throughout my degree and built a large knowledge profile to prepare me for a job within the industry.</li>
          <li>Dissertation based on researching and creating a working web application on a topic of my choice.</li>
          <li>Game development.</li>
          <li>Developed functional apps for mobile devices.</li>
          <li>Developed knowledge of principles used for building web-based systems.</li>
          <li>Introduced to artificial intelligence focusing on reasoning and problem-solving as a search for solutions.</li>
        </ul>
      </div>
  
      <div class="job">
        <h3>Labourer</h3>
        <p>Dean Hyde Builders | 2019 - Current</p>
        <ul>
          <li>Performed manual labour tasks that require physical strength, stamina, and coordination for a family business.</li>
          <li>Operated tools and equipment used in general construction.</li>
          <li>Loaded and unloaded building materials from delivery trucks.</li>
          <li>Responsible for completing solo jobs to a high standard.</li>
          <li>Followed and implemented safety protocols.</li>
          <li>Completed building work such as suspended ceilings, roofing, and carpentry work both as part of a team and solo work.</li>
        </ul>
      </div>
    </section>
  
    <section class="skills">
      <h2>Key Skills</h2>
      <ul>
        <li>App and website development</li>
        <li>Debugging & stress testing</li>
        <li>Hardware & software troubleshooting</li>
        <li>Primarily writing and testing code in Java, Python, JavaScript</li>
      </ul>
    </section>
  
    <section class="education">
      <h2>Education</h2>
      <div class="scroll-container">
        {#each education as edu (edu.degree)}
          <div class="edu-item">
            <h3>{edu.degree}</h3>
            <p>Grade: {edu.grade} | {edu.school} | {edu.years}</p>
          </div>
        {/each}
      </div>
    </section>
  
    <section class="references">
      <h2>References</h2>
      <p>Available upon request.</p>
    </section>

    <section class="information">
        <h2>Information</h2>
        <p>Email: Rhysdhyde@hotmail.co.uk </p>
        <p>Mobile Number: 0754284 9438</p>
        <p2>For more information please feel free to contact me through the email or mobile number above.</p2>
    </section>
  </main>
  
  <style>
    main {
      font-family: Arial, sans-serif;
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
      color: #333;
      z-index: 1;
    }
    
    p2{
        font-size: 1.3em;
    }

    h1, h2, h3 {
      color: #444;
    }
  
    h1 {
      font-size: 2.5em;
      margin-bottom: 20px;
      text-align: center;
      border-bottom: 2px solid #ddd;
      padding-bottom: 10px;
    }
  
    p, ul, li {
      line-height: 1.6;
    }
  
    ul {
      list-style-type: disc;
      margin-left: 20px;
    }
  
    section {
      margin-bottom: 40px;
      background: #9eedda;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }
  
    .about p {
      font-size: 1.2em;
      margin-bottom: 20px;
      color: #555;
    }
  
    .job, .edu-item {
      margin-bottom: 20px;
    }
  
    .job h3, .edu-item h3 {
      margin-bottom: 5px;
      font-size: 1.3em;
      color: #555;
    }
  
    .job p, .edu-item p {
      margin: 0;
      color: #777;
    }
  
    .scroll-container {
      display: flex;
      overflow-x: auto;
      gap: 20px;
      padding: 10px 0;
      scroll-behavior: smooth;
    }
  
    .scroll-container::-webkit-scrollbar {
      height: 8px;
    }
  
    .scroll-container::-webkit-scrollbar-thumb {
      background-color: #365b64;
      border-radius: 4px;
    }
  
    .edu-item {
      min-width: 300px;
      background: #a1ecf6;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
      flex-shrink: 0;
    }
  
    .edu-item h3 {
      margin-bottom: 5px;
      font-size: 1.2em;
      color: #333;
    }
  
    .edu-item p {
      margin: 0;
      color: #777;
    }
  
    .references {
      text-align: center;
      font-style: italic;
    }

  </style>
  