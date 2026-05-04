<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>COLLECTIONS OF MEMORIES</title>

<!-- Bootstrap 5 CSS (IMPORTANT!) -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- Bootstrap 5 JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js"></script>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600&family=Montserrat:wght@300;400&display=swap" rel="stylesheet">
  


<style>

/* RESET */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Montserrat', sans-serif;
  background-color: lightpink;
}

/* NAVBAR */
.navbar {
  display: flex;
  justify-content: space-between;
  padding: 20px 60px;
  position: fixed;
  width: 100%;
  top: 0;
  background-color: darkpink;
  z-index: 10;
}

.logo {
  font-family: 'Playfair Display', serif;
  font-size: 22px;
}

nav a {
  margin-left: 25px;
  text-decoration: none;
  color: white;
  font-weight: 300;
}
nav a:hover {
  color: #B0E0E6; /* lighten on hover for effect */
}

.logo {
  font-family: 'Playfair Display', serif;
  font-size: 22px;
  color: white; /* white logo text */
}

 h2 {
     font-family: "Courier New", serif;
     text-align: center;
     font-size: 40pt;
     font-weight: bold;
     }
 p {
     font-family: "Courier New", serif;
     text-align: justify;
     font-size: 15pt;
     font-weight: bold;
     }
/* HERO SECTION */
.hero {
  height: 90vh;
  background: url("images/pinkstar.png") center/cover no-repeat;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 80px;
  margin-top: 70px;
  position: relative;
  overflow: hidden; /* para safe ang blur */
}
.overlay {
  position: absolute;
  inset: 0;
  background: rgba(255,255,255,0.6);
}

.hero-content {
  position: relative;
  display: flex;
  width: 100%;
  justify-content: space-between;
  align-items: center;
}

.hero-text {
  max-width: 50%;
}

.hero-text h1 {
  font-family: 'Playfair Display', serif;
  font-size: 60px;
  color: #444;
}

.hero-text p {
  margin-top: 10px;
  letter-spacing: 2px;
  color: #777;
}

.hero-image img {
  width: 600px;
}

/* ACCORDION STYLE */
.accordion {
  max-width: 800px;
  margin: 60px auto;
}

.memory-frame {
    max-width: 900px;
    margin: 60px auto;
    padding: 40px;
    background: #ffffff;
    border-radius: 15px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.08);
    border: 1px solid #eee;
}

.memory-frame h2 {
    text-align: center;
    margin-bottom: 30px;
    font-family: 'Playfair Display', serif;
    color: lightpink;
}

.accordion-button:not(.collapsed) {
    background-color: lightpink;
    color: #fff;
}

</style>
</head>

<body>

<!-- NAVBAR -->
<header class="navbar">
  <div class="logo">📖 MY DIARY</div>
  <nav>
    <a href="#home" target="_self">HOME</a>
    <a href="#gallery"target="_self">GALLERY</a>
    <a href="#about" target="_self">ABOUT</a>
  </nav>
</header>

<!-- HERO SECTION -->
<section class="hero">
  <div class="overlay"></div>
  <div class="hero-content">
    <div class="hero-text">
      <h1>AUSTRIA, EZEKIELE C.</h1>
      <p><strong>SECTION: 2-2</strong></p>
      <p><strong>Bachelor of Science in Information Technology</strong></p>
      <p><strong>COLEGIO DE STA TERESA DE AVILA</strong></p>
    </div>
    <div class="hero-image">
      <img src="bgg.png" alt="My Picture">
    </div>
  </div>
</section>
<br>
<br>
<h2 id="home" style="background-color: #FF69B4; color: white; border: 2px solid #880053; padding: 15px; border-radius: 10px; text-align: center;">
  <strong>THIS IS MY COLLEGE DIARY<br>HOMEPAGE</strong>
</h2>


<section class="chapter-section">
      <br><br>




<div class="memory-frame">
      <h2><strong>FIRST YEAR COLLEGE<br>FIRST SEMESTER</strong></h2>

<div class="accordion" id="accordionExample">

  <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button"
        data-bs-toggle="collapse"
        data-bs-target="#collapseOne">
        My First Memory
      </button>
    </h2>
    <div id="collapseOne" class="accordion-collapse collapse"
      data-bs-parent="#accordionExample">
       <div class="accordion-body" style="display:flex; gap:20px; flex-wrap:wrap; align-items:flex-start;">
        
        <!-- LEFT: VIDEO -->
        <video controls style="width:250px; max-width:100%; border-radius:10px;">
          <source src="1stYr-1vid.mp4" type="video/mp4">
        </video>

        <!-- RIGHT: TEXT -->
        <div style="flex:1; min-width:200px;">
          <p>When I first enrolled at Colegio de Sta. Teresa de Avila, 
I felt completely overwhelmed. Just four days after graduating from senior high school 
under the ABM strand, I suddenly found myself stepping into a new chapter of my life college. 
The transition felt too fast, and I struggled to process everything that was happening.
 I had grown used to business-related subjects, but now I was entering an entirely different field. 
I decided to shift to Information Technology because my father encouraged me to pursue this course,
 believing it would provide better opportunities in the future. At first, I was uncertain and even 
doubtful about my decision. Everything felt unfamiliar, from the subjects to the environment and expectations. However, despite the confusion and pressure, I also felt excited. I knew this was a chance to grow, explore new skills, and challenge myself in ways I never had before.
</p>
        </div>

      </div>
    </div>
  </div>



  <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button"
        data-bs-toggle="collapse"
        data-bs-target="#collapseTwo">
        My Second Memory
      </button>
    </h2>
    <div id="collapseTwo" class="accordion-collapse collapse"
      data-bs-parent="#accordionExample">
<div class="accordion-body" style="display:flex; gap:20px; flex-wrap:wrap; align-items:flex-start;">
        
        <!-- LEFT: VIDEO -->
        <video controls style="width:250px; max-width:100%; border-radius:10px;">
          <source src="1st-2vid.mp4" type="video/mp4">
        </video>

        <!-- RIGHT: TEXT -->
        <div style="flex:1; min-width:200px;">
          <p>After a week in college, things slowly began to change for the better.
 I started making new friends in my class, and having people to talk to made me feel 
more comfortable and less overwhelmed. We shared the same struggles, especially since 
many of us were still adjusting to the demands of Information Technology. Their support 
helped me gain confidence and feel that I truly belonged. At the same time, I realized that 
I needed to work harder to keep up with the lessons. Since IT was new to me, 
I decided to start advance studying so I could better understand the topics before they were 
discussed in class. I reviewed lessons, watched tutorial videos, and practiced basic coding exercises.
 This habit helped me follow discussions more easily and improved my performance. Slowly, 
I began to feel more capable, motivated, and ready to face the challenges of my new academic journey.
</p>
        </div>
      </div>
    </div>
  </div>

 <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button"
        data-bs-toggle="collapse"
        data-bs-target="#collapseThree">
        My Third Memory
      </button>
    </h2>
    <div id="collapseThree" class="accordion-collapse collapse"
      data-bs-parent="#accordionExample">
      <div class="accordion-body">
<div class="accordion-body" style="display:flex; gap:20px; flex-wrap:wrap; align-items:flex-start;">
        
        <!-- LEFT: VIDEO -->
        <video controls style="width:250px; max-width:100%; border-radius:10px;">
          <source src="1stYr-3vid.mp4" type="video/mp4">
        </video>

        <!-- RIGHT: TEXT -->
        <div style="flex:1; min-width:200px;">
          <p>One of the most memorable experiences I had during my days in college 
was joining the school’s fun run. At first, I was hesitant to participate because 
I was still adjusting to my new environment and busy schedule. However, my friends 
encouraged me to join, saying it would be a great way to relax and enjoy ourselves. 
I’m glad I said yes because it turned out to be an unforgettable experience. We woke up early,
 feeling excited and energetic as we gathered at the starting line with other students. 
The atmosphere was lively, filled with laughter, music, and cheers. As we ran together,
 we motivated one another to keep going, even when we felt tired. It wasn’t just about 
finishing the race but about sharing the moment and having fun. That day strengthened our 
friendship and gave us a break from academic stress, creating happy memories we will always cherish.
</p>
        </div>

      </div>
    </div>
  </div>



    <div class="accordion-item">
    <h2 class="accordion-header" id="headingFour">
      <button class="accordion-button collapsed" type="button"
        data-bs-toggle="collapse"
        data-bs-target="#collapseFour"
        aria-expanded="false"
        aria-controls="collapseFour">
        My Fourth Memory
      </button>
    </h2>
    <div id="collapseFour" class="accordion-collapse collapse"
      aria-labelledby="headingFour"
      data-bs-parent="#accordionExample">
      <div class="accordion-body" style="display:flex; gap:20px; flex-wrap:wrap; align-items:flex-start;">
        
        <!-- LEFT: PICTURE -->
        <img src="1stYr-2pic.jfif" alt="My Memory" style="width:250px; border-radius:10px;">

        <!-- RIGHT: TEXT -->
        <div style="flex:1; min-width:200px;">
          <p>Looking back, this experience has been truly life-changing for me.
 At first, I doubted myself and questioned whether I could succeed in Information Technology. 
Everything felt unfamiliar and challenging, especially since my background was in ABM. 
However, as time passed, I began to notice small but meaningful improvements. 
Little by little, my knowledge and skills in IT became broader. I started understanding 
programming concepts, troubleshooting basic technical problems, and learning how different
 systems work. Each lesson, project, and activity helped me grow more confident in my abilities.
 I realized that stepping out of my comfort zone allowed me to discover strengths I never knew I had.
 The challenges that once scared me became opportunities to learn and improve. This journey taught me 
the value of perseverance, hard work, and believing in myself. Now, I see my decision not as a burden,
 but as a blessing that shaped my personal and academic growth.
</p>
        </div>

      </div>
    </div>
  </div>


 <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button"
        data-bs-toggle="collapse"
        data-bs-target="#collapseFive">
        My Fifth Memory
      </button>
    </h2>
    <div id="collapseFive" class="accordion-collapse collapse"
      data-bs-parent="#accordionExample">
      <div class="accordion-body" style="display:flex; gap:20px; flex-wrap:wrap; align-items:flex-start;">
        
        <!-- LEFT: VIDEO -->
        <video controls style="width:250px; max-width:100%; border-radius:10px;">
          <source src="1stYr-4vid.mp4" type="video/mp4">
        </video>

        <!-- RIGHT: TEXT -->
        <div style="flex:1; min-width:200px;">
          <p>After my classes, I made sure to stay connected with my senior high school friends.
 Even though we had already received our diplomas and moved on to different colleges, 
our friendship remained strong. We were enrolled in different schools and taking different 
courses, and some of us were even in different states. Despite the distance, we found time 
to catch up through video calls and group chats. Whenever we talked, we shared our college 
experiences both the challenges and the exciting moments. We exchanged tips on how to manage
 time, deal with difficult subjects, and adjust to new environments. Listening to their 
stories made me realize that we were all going through similar struggles, just in different ways.
 Our conversations became a source of comfort and motivation for me. Even though life had taken us 
on separate paths, our bond stayed the same, and we continued to support one another.
</p>
        </div>

    </div>
  </div>
</div>
</div>
<br>
<br>








<div class="memory-frame">
      <h2><strong>FIRST YEAR COLLEGE<br>SECOND SEMESTER</strong></h2>
<div class="accordion" id="accordionExample">

  <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button"
        data-bs-toggle="collapse"
        data-bs-target="#collapseSix">
        My First Memory
      </button>
    </h2>
    <div id="collapseSix" class="accordion-collapse collapse"
      data-bs-parent="#accordionExample">
     <div class="accordion-body" style="display:flex; gap:20px; flex-wrap:wrap; align-items:flex-start;">
        
        <!-- LEFT: VIDEO -->
        <video controls style="width:250px; max-width:100%; border-radius:10px;">
          <source src="1stYr-5vid.mp4" type="video/mp4">
        </video>

        <!-- RIGHT: TEXT -->
        <div style="flex:1; min-width:200px;">
          <p>My classmates and I decided to join a video editing project to earn additional grades 
and improve our performance in class. At first, we were nervous because not all of us 
had experience in editing videos. However, we saw it as an opportunity to learn 
something new and challenge ourselves. We began by brainstorming creative ideas and 
planning the concept of our video. Some of us worked on the script, while others 
focused on filming and editing. I volunteered to help with organizing the clips and 
learning how to use the editing software. Although it was time-consuming and sometimes 
stressful, we enjoyed the process because we were working together as a team.
 We helped each other understand different tools and techniques, and little by little, 
our project started to improve. In the end, joining the video editing activity not
 only helped us gain higher grades but also enhanced our creativity, teamwork,
 and technical skills.
</p>
        </div>

      </div>
    </div>
  </div>

  <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button"
        data-bs-toggle="collapse"
        data-bs-target="#collapseSeven">
        My Second Memory
      </button>
    </h2>
    <div id="collapseSeven" class="accordion-collapse collapse"
      data-bs-parent="#accordionExample">
      <div class="accordion-body" style="display:flex; gap:20px; flex-wrap:wrap; align-items:flex-start;">
        
        <!-- LEFT: VIDEO -->
        <video controls style="width:250px; max-width:100%; border-radius:10px;">
          <source src="1stYr-6vid.mp4" type="video/mp4">
        </video>
<video controls style="width:250px; max-width:100%; border-radius:10px;">
          <source src="1stYr-7vid.mp4" type="video/mp4">
        </video>

        <!-- RIGHT: TEXT -->
        <div style="flex:1; min-width:200px;">
          <p>This was the time when we created a vlog for our project, and it became one of
 the most exciting activities we experienced as a group. We traveled to 
Tanay, Rizal, where we explored and filmed the beautiful surroundings.
 The view was breathtaking, with mountains, fresh air, and peaceful 
scenery that made our vlog more interesting and lively. We enjoyed 
capturing different angles and sharing fun moments while introducing 
the place in our video. After that, we also went to Daranak Falls in 
Tanay, Rizal. It was an unforgettable experience because we had the 
chance to jump into the cool river and swim near the waterfalls.
 The water was refreshing, and the sound of the falls made the place 
even more relaxing. While filming, we were also enjoying ourselves, 
laughing and bonding as classmates. That vlog project was not just 
for grades, but also a memorable adventure we will always treasure.
</p>
        </div>

      </div>
    </div>
  </div>

 <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button"
        data-bs-toggle="collapse"
        data-bs-target="#collapseEight">
        My Third Memory
      </button>
    </h2>
    <div id="collapseEight" class="accordion-collapse collapse"
      data-bs-parent="#accordionExample">
      <div class="accordion-body" style="display:flex; gap:20px; flex-wrap:wrap; align-items:flex-start;">
        
        <!-- LEFT: VIDEO -->
        <video controls style="width:250px; max-width:100%; border-radius:10px;">
          <source src="1stYr-9vid.mp4" type="video/mp4">
        </video>
<video controls style="width:250px; max-width:100%; border-radius:10px;">
          <source src="1stYr-8vid.mp4" type="video/mp4">
        </video>
  <img src="1stYr-3pic.jfif" alt="My Memory" style="width:250px; border-radius:10px;">

        <!-- RIGHT: TEXT -->
        <div style="flex:1; min-width:200px;">
          <p>This was one of the most unforgettable moments of my life. My 8 relatives and I 
traveled to South Cotabato to celebrate my father’s birthday. It was extra special 
because he had just been promoted as Chief of the Highway Patrol. Some of his
 fellow police officers came to join the celebration, making the event even more 
meaningful and joyful. During the trip, my father also transferred the ownership 
of one of his lands there to me, which made me feel proud and grateful for his
trust.</p>

<p>We also explored different places such as Sarangani, 
General Santos City, Lake Cebu, Surallah, and other beautiful 
parts of South Cotabato. One of the best experiences I had was
 riding the HIGHEST ZIPLINE in SOUTHEAST ASIA at Lake Cebu. 
I was very nervous at first because I was afraid of heights,
 but I gathered the courage to try it. I couldn’t believe I made it 
I finally overcame my fear.
</p>
        </div>

      </div>
    </div>
  </div>

<div class="accordion-item">
  <h2 class="accordion-header">
    <button class="accordion-button collapsed" type="button"
      data-bs-toggle="collapse"
      data-bs-target="#collapseNine">
      My Fourth Memory
    </button>
  </h2>

  <div id="collapseNine" class="accordion-collapse collapse"
    data-bs-parent="#accordionExample">

    <div class="accordion-body" style="display:flex; gap:20px; flex-wrap:wrap; align-items:flex-start;">

      <img src="1stYr-6pic.jfif" alt="My Memory"
        style="width:250px; border-radius:10px;">

      <div style="flex:1; min-width:200px;">
        <p>TOne of the happiest moments in my life was the day I passed my exam. 
I had been preparing for it for weeks, studying late into the night and reviewing
 all the lessons carefully. At first, I felt nervous and unsure if I had studied 
enough, but I tried to stay calm and focused during the test. When the 
results were finally announced, I felt an overwhelming sense of joy
 and relief to see that I had passed. It was not just about getting
 a grade it was a confirmation that my hard work and dedication had 
paid off. Passing the exam boosted my confidence and motivated me to 
continue working hard in my studies. I also felt proud of myself
 because I overcame the anxiety and pressure that came with the exam.
 That moment reminded me that persistence and preparation always lead
 to success, making it an experience I will never forget.
</p>
      </div>

    </div>
  </div>
</div>


 <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button"
        data-bs-toggle="collapse"
        data-bs-target="#collapseTen">
        My Fifth Memory
      </button>
    </h2>
    <div id="collapseTen" class="accordion-collapse collapse"
      data-bs-parent="#accordionExample">
      <div class="accordion-body" style="display:flex; gap:20px; flex-wrap:wrap; align-items:flex-start;">
        
        <!-- LEFT: VIDEO -->
        <video controls style="width:250px; max-width:100%; border-radius:10px;">
          <source src="1stYr-10vid.mp4" type="video/mp4">
        </video>

 

        <!-- RIGHT: TEXT -->
        <div style="flex:1; min-width:200px;">
          <p>One of the most unforgettable memories I have is my birthday at school. 
I was sitting in the computer lab, completely focused on my work,
 and had no idea that anything special was planned for me. Suddenly,
 my classmates surprised me, and I was completely overwhelmed.
 I didn’t know that they had bought a cake , so seeing it all 
made me feel shocked and so happy at the same time. Everyone
 gathered around, sang “Happy Birthday,” and gave me warm 
wishes and small gifts. I felt so appreciated and loved, 
and my heart was full of joy. That surprise made me realize 
how thoughtful and caring my classmates are. The laughter, hugs,
 and shared happiness made the moment even more special. 
That day became a memory I will always treasure, reminding 
me of the kindness and support of the people around me.
</p>
        </div>

      </div>
    </div>
  </div>

</div>
</div>
<br>
<br>





<div class="memory-frame">
      <h2><strong>SECOND YEAR COLLEGE<br>FIRST SEMESTER</strong></h2>
<div class="accordion" id="accordionExample">

  <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button"
        data-bs-toggle="collapse"
        data-bs-target="#collapseEleven">
        My First Memory
      </button>
    </h2>
    <div id="collapseEleven" class="accordion-collapse collapse"
      data-bs-parent="#accordionExample">
       <div class="accordion-body" style="display:flex; gap:20px; flex-wrap:wrap; align-items:flex-start;">
        
        <!-- LEFT: VIDEO -->
        <video controls style="width:250px; max-width:100%; border-radius:10px;">
          <source src="2nd-14.mp4" type="video/mp4">
        </video>


        <!-- RIGHT: TEXT -->
        <div style="flex:1; min-width:200px;">
          <p>After school one day, I stepped outside and was completely overwhelmed
 by the beauty of the moment. The sky was painted in soft shades of pink,
 creating a peaceful and almost magical atmosphere. I couldn’t help but 
stop and stare, feeling calm and amazed at how stunning nature could be.
 Birds were flying gracefully around SM Fairview, their movements perfectly 
complementing the colors of the sunset. The combination of the pink sky,
 the gentle breeze, and the sound of the birds made everything feel surreal.
 I felt a sense of gratitude and happiness wash over me, as if the world 
had paused for a moment just for me to enjoy it. It was a simple scene, 
but it left a deep impression on my mind. That afternoon reminded me to 
appreciate small moments in life and the beauty that surrounds us every day.
</p>
        </div>

      </div>
    </div>
  </div>

  <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button"
        data-bs-toggle="collapse"
        data-bs-target="#collapseTwelve">
        My Second Memory
      </button>
    </h2>
    <div id="collapseTwelve" class="accordion-collapse collapse"
      data-bs-parent="#accordionExample">
       <div class="accordion-body" style="display:flex; gap:20px; flex-wrap:wrap; align-items:flex-start;">
        <video controls style="width:250px; max-width:100%; border-radius:10px;">
          <source src="2ndYr-4vid.mp4" type="video/mp4">
        </video>

       
        <!-- RIGHT: TEXT -->
        <div style="flex:1; min-width:200px;">
          <p>Being alone at school after classes was mesmerizing. 
The usually busy campus became peaceful, with sunlight streaming 
through windows and leaves gently rustling. I wandered, noticed 
small details, and sat quietly, reflecting and relaxing.
 That quiet solitude made the familiar surroundings feel 
magical and gave me a rare moment of calm.
</p>
        </div>

      </div>
    </div>
  </div>

 <div class="accordion-item">
  <h2 class="accordion-header">
    <button class="accordion-button collapsed" type="button"
      data-bs-toggle="collapse"
      data-bs-target="#collapseThirteen">
      My Third Memory
    </button>
  </h2>

  <div id="collapseThirteen" class="accordion-collapse collapse"
    data-bs-parent="#accordionExample">

    <div class="accordion-body" style="display:flex; gap:20px; flex-wrap:wrap; align-items:flex-start;">

      <video controls style="width:250px; max-width:100%; border-radius:10px;">
        <source src="2ndYr-2vid.mp4" type="video/mp4">
      </video>

      <div style="flex:1; min-width:200px;">
        <p>One important lesson I learned is that it’s often better to distance yourself
 from people who disrespect or mistreat you rather than try to 
get along with them. At first, I thought it might be possible
 to change the situation or earn their approval by being friendly,
 but I quickly realized that some people will never treat you 
with the respect you deserve. Trying to please them only 
caused stress, frustration, and disappointment. By choosing 
to step back and focus on my own well-being, I began to feel 
more confident and in control of my life. I learned to value 
my own dignity and to surround myself with people who genuinely
 care and support me. This experience taught me that setting
 boundaries is not selfish; it is a way to protect yourself 
from harm and negativity. In the end, prioritizing self-respect 
brought me peace and stronger, healthier relationships.
</p>
      </div>

    </div>
  </div>
</div>




 <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button"
        data-bs-toggle="collapse"
        data-bs-target="#collapseFourteen">
        My Forth Memory
      </button>
    </h2>
    <div id="collapseFourteen" class="accordion-collapse collapse"
      data-bs-parent="#accordionExample">
     <div class="accordion-body" style="display:flex; gap:20px; flex-wrap:wrap; align-items:flex-start;">
        <video controls style="width:250px; max-width:100%; border-radius:10px;">
          <source src="2ndYr-6vid.mp4" type="video/mp4">
        </video>
                <img src="2ndYr-2pic.jfif" alt="My Memory" style="width:250px; border-radius:10px;">
        <!-- RIGHT: TEXT -->
        <div style="flex:1; min-width:200px;">
          <p>One of the most challenging experiences I faced in college was working on our thesis
 in Information Management. At first, I was part of a group, but
 I noticed that some of my groupmates rarely contributed and often 
relied on me to do most of the work. They didn’t take initiative
 or complete tasks voluntarily, which left me feeling frustrated
 and overwhelmed. After struggling to manage the workload and 
realizing that the project was suffering because of the lack 
of collaboration, I made a difficult decision to separate myself 
from the group and work solo. It was not an easy choice, but
 it allowed me to take full responsibility for the quality 
of the thesis and manage my time more effectively. Working 
alone taught me discipline, independence, and problem-solving 
skills. Despite the challenges, I felt proud of my efforts and
 learned that sometimes stepping away from uncooperative team
 members is necessary to achieve your goals.
</p>
        </div>
      </div>
    </div>
  </div>


 <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button"
        data-bs-toggle="collapse"
        data-bs-target="#collapseFifteen">
        My Fifth Memory
      </button>
    </h2>
    <div id="collapseFifteen" class="accordion-collapse collapse"
      data-bs-parent="#accordionExample">
       <div class="accordion-body" style="display:flex; gap:20px; flex-wrap:wrap; align-items:flex-start;">
        <video controls style="width:250px; max-width:100%; border-radius:10px;">
          <source src="2ndYr-7vid.mp4" type="video/mp4">
        </video>
          
        <!-- RIGHT: TEXT -->
        <div style="flex:1; min-width:200px;">
          <p>One of the most rewarding moments in my college journey was the day 
I finished and defended my thesis. After weeks of hard work, 
research, and preparation, I finally presented my work confidently.
 I felt a deep sense of pride and accomplishment because I knew 
that I had done it on my own, overcoming all the challenges 
along the way. Completing the thesis wasn’t just about 
submitting a project; it was a test of my patience, dedication, 
and ability to manage tasks independently.

I also want to express my heartfelt gratitude to my professor, 
who guided me throughout the process. Their support, advice, 
and encouragement not only helped me improve my work but also 
inspired me to develop as a better leader and a more understanding 
friend. Through this experience, I learned the importance of 
perseverance, self-discipline, and taking responsibility for my 
own success. Defending my thesis successfully gave me confidence 
in my abilities and taught me that with focus and determination,
 I can achieve goals I once thought were impossible.
</p>
        </div>
      </div>
    </div>
  </div>
</div>
</div>
<br>
<br>






<div class="memory-frame">
      <h2><strong>SECOND YEAR COLLEGE<br>SECOND SEMESTER</strong></h2>
<div class="accordion" id="accordionExample">

  <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button"
        data-bs-toggle="collapse"
        data-bs-target="#collapseSixteen">
        My First Memory
      </button>
    </h2>
    <div id="collapseSixteen" class="accordion-collapse collapse"
      data-bs-parent="#accordionExample">
       <div class="accordion-body" style="display:flex; gap:20px; flex-wrap:wrap; align-items:flex-start;">
        
        <!-- LEFT: VIDEO -->
        <video controls style="width:250px; max-width:100%; border-radius:10px;">
          <source src="2nd-2.mp4" type="video/mp4">
        </video>
                <img src="2nd-1.jfif" alt="My Memory" style="width:250px; border-radius:10px;">
        <!-- RIGHT: TEXT -->
        <div style="flex:1; min-width:200px;">
          <p>This was when I enrolled for the second semester,
 and my cousin joined me because she said she 
also wanted to become an IT professional someday.
 We went together, helping and encouraging each other, 
making my enrollment process fun while I share
 experience for pursuing a future in IT.
</p>
        </div>

      </div>
    </div>
  </div>

  <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button"
        data-bs-toggle="collapse"
        data-bs-target="#collapseSeventeen">
        My Second Memory
      </button>
    </h2>
    <div id="collapseSeventeen" class="accordion-collapse collapse"
      data-bs-parent="#accordionExample">
       <div class="accordion-body" style="display:flex; gap:20px; flex-wrap:wrap; align-items:flex-start;">
                <img src="2nd-3.jfif" alt="My Memory" style="width:250px; border-radius:10px;">
       
        <!-- RIGHT: TEXT -->
        <div style="flex:1; min-width:200px;">
          <p>On my first day in my new section, I felt both nervous and excited. 
The environment was completely new, filled with unfamiliar
 faces and routines, but I was eager to learn. I looked
 forward to gaining new knowledge and developing my skills, 
hoping this fresh start would help me grow academically 
and personally throughout the semester.
</p>
        </div>

      </div>
    </div>
  </div>

 <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button"
        data-bs-toggle="collapse"
        data-bs-target="#collapseEighteen">
        My Third Memory
      </button>
    </h2>
    <div id="collapseEighteen" class="accordion-collapse collapse"
      data-bs-parent="#accordionExample">
       <div class="accordion-body" style="display:flex; gap:20px; flex-wrap:wrap; align-items:flex-start;">
        <img src="2nd-4.jfif" alt="My Memory" style="width:250px; border-radius:10px;">
       
        <!-- RIGHT: TEXT -->
        <div style="flex:1; min-width:200px;">
          <p>This was my first activity in App Development,
 and I was excited to learn about circuits.
 Handling the components and understanding 
how they connect sparked my curiosity. I
 enjoyed experimenting, observing how each 
part worked, and gaining hands-on experience.
 It was both challenging and fun, making me 
eager to learn more about electronics and development.
</p>
        </div>

      </div>
    </div>
  </div>



 <div class="accordion-item">
  <h2 class="accordion-header">
    <button class="accordion-button collapsed" type="button"
      data-bs-toggle="collapse"
      data-bs-target="#collapseNineteen">
      My Fourth Memory
    </button>
  </h2>
  <div id="collapseNineteen" class="accordion-collapse collapse"
    data-bs-parent="#accordionExample">
    
    <div class="accordion-body" style="display:flex; gap:20px; flex-wrap:wrap; align-items:flex-start;">

      <!-- LEFT: IMAGES STACK -->
      <div style="display:flex; flex-direction:column; gap:10px;">
        <img src="2nd-5.jfif" alt="My Memory" style="width:250px; border-radius:10px;">
        <img src="2nd-6.jfif" alt="My Memory" style="width:250px; border-radius:10px;">
        <img src="2nd-7.jfif" alt="My Memory" style="width:250px; border-radius:10px;">
      </div>

      <!-- RIGHT: TEXT -->
      <div style="flex:1; min-width:200px;">
        <p>This was a period in my life when I was truly
 enjoying a fresh start in a new environment. 
I met new classmates and made new friends,
 which made my school life more exciting and 
enjoyable. Every day felt like an opportunity 
to learn something new and build meaningful
 connections. At the same time, I also started 
exploring work outside of school by doing a 
part-time job. I began live selling “ukay-ukay” or 
thrift store items, which was both challenging 
and rewarding. Through this experience, I learned 
how to communicate effectively with customers, 
manage sales, and handle products carefully. 
Balancing school and my part-time work taught me 
discipline, time management, and responsibility.
 It was a busy period, but I genuinely enjoyed the 
process because it allowed me to grow academically, 
socially, and personally. That phase gave me confidence 
and valuable life lessons that I will carry forward.
.</p>
      </div>

    </div>
  </div>
</div>

 <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button"
        data-bs-toggle="collapse"
        data-bs-target="#collapseTwenty">
        My Fifth Memory
      </button>
    </h2>
    <div id="collapseTwenty" class="accordion-collapse collapse"
      data-bs-parent="#accordionExample">
       <div class="accordion-body" style="display:flex; gap:20px; flex-wrap:wrap; align-items:flex-start;">
        <img src="2nd-8.jfif" alt="My Memory" style="width:250px; border-radius:10px;">
               <img src="2nd-9.jfif" alt="My Memory" style="width:250px; border-radius:10px;">
        <img src="2nd-10.jfif" alt="My Memory" style="width:250px; border-radius:10px;">
<br>
        <img src="2nd-11.jfif" alt="My Memory" style="width:250px; border-radius:10px;">
        <!-- RIGHT: TEXT -->
        <div style="flex:1; min-width:200px;">
          <p>One of the most memorable moments on campus was during Valentine’s Day, when we took the opportunity to capture memories and make new friends. The campus was lively and decorated with festive colors, creating a cheerful and welcoming atmosphere. Students gathered to take pictures, share laughs, and enjoy small activities organized for the day. I met classmates I hadn’t spoken to before, and we bonded over taking photos and sharing stories. It was a fun and heartwarming experience that allowed us to connect beyond our usual academic routines. That Valentine’s Day on campus became a memory filled with friendship, laughter, and joy that I will always treasure.
</p>
        </div>
      </div>
    </div>
  </div>
</div>
</div>
<br>
<br>
</frame>








<h2 id="gallery" style="background-color:#FF69B4; color: white; border: 2px solid #880053; padding: 15px; border-radius: 10px; text-align: center;">
  <strong>THIS IS MY COLLEGE DIARY<br>GALLERY</strong>
</h2>
<div id="carouselExampleFade" class="carousel slide carousel-fade" data-bs-ride="carousel">
  <div class="carousel-inner">

    <div class="carousel-item active">
      <video class="d-block w-100" autoplay muted loop>
        <source src="2nd-14.mp4" type="video/mp4">
      </video>
    </div>

    <div class="carousel-item">
      <video class="d-block w-100" autoplay muted loop>
        <source src="1stYr-6vid.mp4" type="video/mp4">
      </video>
    </div>
 <div class="carousel-item">
      <video class="d-block w-100" autoplay muted loop>
        <source src="1stYr-9vid.mp4" type="video/mp4">
      </video>
    </div>
 <div class="carousel-item">
      <video class="d-block w-100" autoplay muted loop>
        <source src="2ndYr-2vid.mp4" type="video/mp4">
      </video>
    </div>

    <div class="carousel-item">
      <img src="2nd-8.jfif" class="d-block w-100" alt="image">
    </div>
<div class="carousel-item">
      <img src="2nd-1.jfif" class="d-block w-100" alt="image">
    </div>
<div class="carousel-item">
      <img src="1stYr-3pic.jfif" class="d-block w-100" alt="image">
    </div>


  </div>

  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="prev">
    <span class="carousel-control-prev-icon"></span>
  </button>

  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="next">
    <span class="carousel-control-next-icon"></span>
  </button>

</div>

<br>
<br>
<h2 id="about" style="background-color:#FF69B4; color: white; border: 2px solid #880053; padding: 15px; border-radius: 10px; text-align: center;">
  <strong>THIS IS MY COLLEGE DIARY<br>ABOUT ME</strong>
</h2>
<p>Hi, I am Ezekiele C. Austria, a Bachelor of Science in Information Technology student at Colegio de Sta. Teresa de Avila. I graduated from the ABM strand in Senior High School, which was very different from my current course. At first, I felt overwhelmed because classes started just days after my graduation. Despite the challenges, I chose to continue and adapt. Now, I am focused on improving my programming skills and becoming a successful IT professional in the future.
</p>

</body>
</html>                 

