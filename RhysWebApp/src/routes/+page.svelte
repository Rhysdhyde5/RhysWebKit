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
    <div class="background">
      <span></span>
      <span></span>
      <span></span>
      <span></span>
      <span></span>
      <span></span>
      <span></span>
      <span></span>
      <span></span>
      <span></span>
      <span></span>
      <span></span>
      <span></span>
      <span></span>
      <span></span>
      <span></span>
      <span></span>
      <span></span>
      <span></span>
      <span></span>
   </div>
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

    @keyframes move {
    100% {
        transform: translate3d(0, 0, 1px) rotate(360deg);
    }
}

.background {
    position: fixed;
    width: 100vw;
    height: 100vh;
    top: 0;
    left: 0;
    background: #141118;
    overflow: hidden;
    z-index: -1;
}

.background span {
    width: 20vmin;
    height: 20vmin;
    border-radius: 20vmin;
    backface-visibility: hidden;
    position: absolute;
    animation: move;
    animation-duration: 45;
    animation-timing-function: linear;
    animation-iteration-count: infinite;
}


.background span:nth-child(0) {
    color: #3d76b3;
    top: 99%;
    left: 73%;
    animation-duration: 55s;
    animation-delay: -2s;
    transform-origin: 16vw -8vh;
    box-shadow: -40vmin 0 5.509419215446355vmin currentColor;
}
.background span:nth-child(1) {
    color: #3c867d;
    top: 8%;
    left: 13%;
    animation-duration: 49s;
    animation-delay: -25s;
    transform-origin: -11vw 1vh;
    box-shadow: 40vmin 0 5.657450488366031vmin currentColor;
}
.background span:nth-child(2) {
    color: #3c867d;
    top: 26%;
    left: 10%;
    animation-duration: 34s;
    animation-delay: -33s;
    transform-origin: -9vw -21vh;
    box-shadow: 40vmin 0 5.2847707323917135vmin currentColor;
}
.background span:nth-child(3) {
    color: #3d76b3;
    top: 85%;
    left: 39%;
    animation-duration: 39s;
    animation-delay: -31s;
    transform-origin: 8vw -14vh;
    box-shadow: -40vmin 0 5.854302916506819vmin currentColor;
}
.background span:nth-child(4) {
    color: #3d76b3;
    top: 3%;
    left: 54%;
    animation-duration: 47s;
    animation-delay: -9s;
    transform-origin: 10vw 7vh;
    box-shadow: -40vmin 0 5.744327983880025vmin currentColor;
}
.background span:nth-child(5) {
    color: #3d76b3;
    top: 60%;
    left: 20%;
    animation-duration: 48s;
    animation-delay: -37s;
    transform-origin: 1vw -23vh;
    box-shadow: -40vmin 0 5.684615630043944vmin currentColor;
}
.background span:nth-child(6) {
    color: #3c867d;
    top: 57%;
    left: 27%;
    animation-duration: 26s;
    animation-delay: -42s;
    transform-origin: -17vw 14vh;
    box-shadow: 40vmin 0 5.645796758181673vmin currentColor;
}
.background span:nth-child(7) {
    color: #adebff;
    top: 58%;
    left: 31%;
    animation-duration: 32s;
    animation-delay: -27s;
    transform-origin: 0vw 2vh;
    box-shadow: 40vmin 0 5.390130711103919vmin currentColor;
}
.background span:nth-child(8) {
    color: #adebff;
    top: 100%;
    left: 23%;
    animation-duration: 18s;
    animation-delay: -11s;
    transform-origin: 9vw 7vh;
    box-shadow: 40vmin 0 5.884841911486578vmin currentColor;
}
.background span:nth-child(9) {
    color: #3d76b3;
    top: 2%;
    left: 84%;
    animation-duration: 37s;
    animation-delay: -24s;
    transform-origin: 14vw 23vh;
    box-shadow: 40vmin 0 5.4762655854801vmin currentColor;
}
.background span:nth-child(10) {
    color: #3c867d;
    top: 98%;
    left: 36%;
    animation-duration: 12s;
    animation-delay: -34s;
    transform-origin: -8vw 14vh;
    box-shadow: -40vmin 0 5.460473286198827vmin currentColor;
}
.background span:nth-child(11) {
    color: #3c867d;
    top: 92%;
    left: 99%;
    animation-duration: 25s;
    animation-delay: -28s;
    transform-origin: -17vw -22vh;
    box-shadow: 40vmin 0 5.905157661162068vmin currentColor;
}
.background span:nth-child(12) {
    color: #3c867d;
    top: 31%;
    left: 88%;
    animation-duration: 23s;
    animation-delay: -46s;
    transform-origin: 7vw -2vh;
    box-shadow: 40vmin 0 5.783516419704593vmin currentColor;
}
.background span:nth-child(13) {
    color: #3c867d;
    top: 93%;
    left: 98%;
    animation-duration: 36s;
    animation-delay: -2s;
    transform-origin: 19vw -1vh;
    box-shadow: 40vmin 0 5.5725498153716595vmin currentColor;
}
.background span:nth-child(14) {
    color: #3c867d;
    top: 69%;
    left: 55%;
    animation-duration: 14s;
    animation-delay: -36s;
    transform-origin: -12vw 12vh;
    box-shadow: -40vmin 0 5.899681224573236vmin currentColor;
}
.background span:nth-child(15) {
    color: #3d76b3;
    top: 39%;
    left: 4%;
    animation-duration: 27s;
    animation-delay: -28s;
    transform-origin: 15vw 13vh;
    box-shadow: -40vmin 0 5.5091422249414vmin currentColor;
}
.background span:nth-child(16) {
    color: #3c867d;
    top: 59%;
    left: 16%;
    animation-duration: 22s;
    animation-delay: -50s;
    transform-origin: -5vw -1vh;
    box-shadow: -40vmin 0 5.761004551362643vmin currentColor;
}
.background span:nth-child(17) {
    color: #3d76b3;
    top: 38%;
    left: 40%;
    animation-duration: 48s;
    animation-delay: -27s;
    transform-origin: -13vw -15vh;
    box-shadow: 40vmin 0 5.804488870936517vmin currentColor;
}
.background span:nth-child(18) {
    color: #3d76b3;
    top: 50%;
    left: 4%;
    animation-duration: 22s;
    animation-delay: -11s;
    transform-origin: -18vw -12vh;
    box-shadow: 40vmin 0 5.697613695063721vmin currentColor;
}
.background span:nth-child(19) {
    color: #adebff;
    top: 69%;
    left: 45%;
    animation-duration: 24s;
    animation-delay: -18s;
    transform-origin: -4vw -9vh;
    box-shadow: 40vmin 0 5.066541817452778vmin currentColor;
}

  </style>
  