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
      background: #ffffff;
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
  