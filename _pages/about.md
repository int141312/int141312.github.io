---
permalink: /
title: ""
excerpt: "About me"
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---


<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Two Columns</title>
    <style>
        .columns {
            display: flex;
            justify-content: space-between;
        }

        .column1 {
            width: 30%; /* 조절 가능 */
            border: 1px solid #F2F2F2;
            padding: 10px;
            box-sizing: border-box;
        }

        .column2 {
            width: 70%; /* 조절 가능 */
            border: 1px solid #F2F2F2;
            padding: 10px;
            box-sizing: border-box;
        }

        .column3 {
            width: 40%; /* 조절 가능 */
            border: 1px solid #F2F2F2;
            padding: 10px;
            box-sizing: border-box;
        }

        .column4 {
            width: 60%; /* 조절 가능 */
            border: 1px solid #F2F2F2;
            padding: 10px;
            box-sizing: border-box;
        }

        .column5 {
            width: 100%; /* 조절 가능 */
            border: 1px solid #FFFFFF;
            padding: 20px;
            box-sizing: border-box;
        }

        .column6 {
            width: 50%; /* 조절 가능 */
            border: 1px solid #FFFFFF;
            padding: 20px;
            box-sizing: border-box;
        }

        .card {
            border: 1px solid #0073CF; /* 테두리 */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* 그림자 효과 */
            border-radius: 8px; /* 테두리 둥글게 */
            display: flex;
            justify-content : center;
            align-items : center;
            text-align : center;
            padding : 5px 0;
            
        }

        h1 { text-align: center; }

        li{ list-style-position: inside; 
            text-indent: -20px;
        }

        .inside { list-style-position: inside; }

        
    </style>
</head>


<body bgcolor='#F2F2F2'>

<div class="columns">
    <div class="column1">
        <p>  <img src="https://github.com/int141312/int141312.github.io/blob/gh-pages/images/profile.png?raw=true">   </p> 
        <h1> Jisung Son </h1>
        <a> jisung9973@gmail.com  </a>
    </div>

    <div class="column2">
        <p>I am highly interested in detecting and solving problems using data, machine learning, and deep learning technologies. I have conducted research and projects related to solving problems such as anomaly detection and OOD detection using deep learning, developing counseling chatbots and game NPCs with language models, working with generative models like diffusion models, and enhancing the quality of training data through data-centric AI. 
        </p>
        
        <p>
My dream is contributing to making AI an everyday tool, just like calculators and smartphones.
        </p>
        
    <div class="columns">
      <div class="column3">
        <h3> Interests </h3>
        <ul class="inside">
          <li> Deep Learning </li>
          <li> Generative AI </li>
          <li> Data science </li>
        </ul>
      </div>

      <div class="column2">
        <h3> Education </h3>
        <ul class="inside">
          <li> 2026~. Ph.D candidate. Artificial Intelligence, Seoul National University </li>
        
          <li> 2025. M.S. Artificial Intelligence, Gwangju Institute of Science and Technology (GIST) </li>
           
          <li> 2019. B.S. Physics, Ulsan National Institute of Science and Technology (UNIST)   </li> 
          
        </ul>
        
      </div>

    </div>
        
    </div>
</div>

<br>


<div id="research" name="research" class="columns" style='background-color: #ffffff' >
    <br>
    <div class="column5">
      <h1> Research & Projects </h1> 
      
      <h3> Sample-Incremental Influence Function: A Sensitivity Metric to detect Key Feature Replacement (2024.03 ~ 2024.12) </h3>
      <p> Abstract </p>      

      <div class="columns" style='background-color: #ffffff'>
        <div class="column6">
        <p> Influence function serves as a quantitative metric of model sensitivity, measuring the degree of parameter variation, offering insights into model parameter behavior, and enabling parameter predictions without the need for retraining. The traditional influence function-based sensitivity relies on a sample-decremental approach, which only measures the impact of removing specific samples. This narrow focus restricts its ability to analyze model behavior in response to newly introduced samples, highlighting a significant limitation in adapting to dynamic data environments. In this work, we present the Sample-Incremental Influence Function that leverages influence function to evaluate the impact of additional data on model sensitivity. Correlation analysis and CAM-based visualization demonstrate the validity of our method and reveal its ability to detect key feature replacement. Sensitivity show strong potential for various applications related to feature corresponding to unknown sample. </p>
        </div>        
      
        <div class="column6">
          <p> <img src="https://github.com/int141312/int141312.github.io/blob/gh-pages/images/fig1.png?raw=true"> </p>
        </div>
      
      </div>


      <h3> Development and Training of Reinforcement Learning Environments with Dynamic Terrain Considerations: A Case Study on Robot Vacuum Cleaner (2023.03 ~ 2023.06) </h3>
      <p> * Language: Python </p>

      <div class="columns" style='background-color: #ffffff'>
        <div class="column6">
        <p>  Reinforcement learning is commonly applied to learn optimal decision-making in stationary environments. However, in real-world scenarios, stationary environments are limited, and thus, the use of reinforcement learning in machine intelligence applications is limited. In the case of robot vacuum cleaners, companies typically employ simple algorithms or basic machine learning techniques to determine the robot’s movement path. These approaches fail to address the issue of adapting to environmental changes that occur during the cleaning process. We aim to develop a reinforcement learning environment that can be used to enhance the efficiency of robot vacuum cleaners and use the environment to train a robot vacuum cleaner agent. We created a dynamic grid-world-based learning environment that incorporates potential changes in the real world. We trained a robot vacuum cleaner to navigate the room efficiently and compared its performance with traditional algorithm-based approaches.  </p> 
        </div>

        <div class="column6">
          <p> {% include video.html id="3AfjKQNlUwY"%} </p>
        </div>

      </div>

      <h3> MENU Master : Service that provides food recommendations and information to help you navigate away from menus in languages you don't understand. (2024.03 ~ 2024.06) </h3>
      <p> * Language: Python(Flask) </p>

      <div class="columns" style='background-color: #ffffff'>
        <div class="column6">
        <p>  This service can be useful if the menu is in a language you don't understand and you can't get any information from it. It uses the user's information and the menu information on the menu board to determine the fitness of the food and recommends the top three options.  </p> 
        </div>

        <div class="column6">
          <p>  <!-- {% include video.html id="4RiLnJGKvxI" %} -->
            <iframe width="560" height="315" src="https://www.youtube.com/embed/4RiLnJGKvxI" frameborder="0" allowfullscreen></iframe>
          </p>
        </div>

      </div>


      <h3> Development of efficient dictionary training technology for large Korean language models (2024. 01 ~ 2024. 12) </h3>
      <p> * Language: Python, PyTorch </p>

      <div class="columns" style='background-color: #ffffff'>
      <p> We developed a model to determine whether the input text is ungrammatical, contains hate speech, or discusses a book-related topic. </p>
      </div>


      <h3> Correlation between park area and cost of living (2022.04 ~ 2022.06) </h3>   

      <div class="columns" style='background-color: #ffffff'>
        <div class="column6">
        <p> I recently watched a YouTube video that argued Gangnam’s high cost of living is due to the lack of free recreational spaces, such as nearby parks. This prompted me to start a project to verify whether this claim holds true using data. While I could easily obtain data on metrics like per capita park area, defining a suitable indicator for the cost of living—and collecting the corresponding data—proved challenging. I eventually decided to use hair salon prices and oil prices as proxies for the cost of living, gathering the data by crawling Naver Map. Based on these data, I conducted a correlation analysis. </p>
        </div>        
      
        <div class="column6">
          <!-- <p> <img src="https://github.com/int141312/int141312.github.io/blob/gh-pages/images/fig2.png?raw=true"> </p>  -->
          <p> <img src="https://github.com/int141312/int141312.github.io/blob/gh-pages/images/fig3.png?raw=true"> </p>
        </div>
      
      </div>
      
    </div>
</div>

<br>

<div id="study" name="study" class="columns" style='background-color: #ffffff' >
    <br>
    <div class="column5">
      <h1> Study </h1> 
    <br>

       <div class="columns" style='background-color: #ffffff'>
        <div class="column6">
          <div class="card" onclick='window.location.href = "https://panoramic-timer-f8a.notion.site/Why-ML-lost-and-DL-became-the-trend-2249f0f11b16451c93b79d5214356bc7?pvs=4" ' > <h3 style = "margin-top: 0; margin-bottom: 0; "> Why ML lost and DL became the trend? </h3> </div>

          <br>

          <div class="card" onclick='window.location.href = "https://panoramic-timer-f8a.notion.site/Diffusion-model-Background-9b61df6e3d8846a2a55c378a8024bfa1?pvs=4" ' > <h3 style = "margin-top: 0; margin-bottom: 0; "> Diffusion model Background </h3> </div>

          <br>

          <div class="card" onclick='window.location.href = "https://panoramic-timer-f8a.notion.site/History-of-Large-Language-Model-LLM-Transformer-Attention-Mechanism-21838beeb01680fb9d54d70993c0dd4f?pvs=74" ' > <h3 style = "margin-top: 0; margin-bottom: 0; "> History of Large Language Model(LLM) & Transformer, Attention Mechanism </h3> </div>

        </div>



        <div class="column6"> 

          <div class="card" onclick='window.location.href = "https://panoramic-timer-f8a.notion.site/Discussion-of-deep-learning-representations-a48f244a96264b578ae3ffb277ceb1cf?pvs=4" ' > <h3 style = "margin-top: 0; margin-bottom: 0; "> Discussion of deep learning representations </h3> </div>

          <br>

          <div class="card" onclick='window.location.href = "https://panoramic-timer-f8a.notion.site/Why-Cross-Entropy-4f0809c9077f4bde8cccfa80d849d1b9?pvs=4" ' > <h3 style = "margin-top: 0; margin-bottom: 0; "> Why Cross Entropy? </h3> </div>

          <br>

          <div class="card" onclick='window.location.href = "https://panoramic-timer-f8a.notion.site/Influence-function-Model-Sensitivity-24c38beeb016800c9597d4a6f7910d0b?pvs=74" ' > <h3 style = "margin-top: 0; margin-bottom: 0; "> Influence function & Model Sensitivity </h3> </div>
          
        </div>



        <div class="column6"> 

          <div class="card" onclick='window.location.href = "https://panoramic-timer-f8a.notion.site/AI-21638beeb016801bb2a1d0cb270f7629?source=copy_link" ' > <h3 style = "margin-top: 0; margin-bottom: 0; "> AI History </h3> </div>

          <br>

          <div class="card" onclick='window.location.href = "https://panoramic-timer-f8a.notion.site/How-AI-is-changing-the-world-8d2db8129d5f439bbaecbfbe8d6c6876?source=copy_link" ' > <h3 style = "margin-top: 0; margin-bottom: 0; "> How AI is changing the world </h3> </div>
          
        </div>

        
      </div>
      
    </div>
</div>


<br>

<div id="experience" name="experience" class="columns" style='background-color: #ffffff' >
  <br>
  <div class="column5">
    <h1> Experience </h1>
    <h3> Teaching </h3>
    <ul class="inside">
    <li> General PhysicsⅠ, UNIST (spring 2018) </li>
    <li> General Physics Ⅱ, UNIST (fall 2018) </li>
    <li> Calculus Ⅱ, UNIST (fall 2018) </li>
    </ul>
 
    <h3> Military Service </h3>
    <ul class="inside">
    <li> ROKAF (2020-2022) </li>
    </ul>

    <h3> Additional Education </h3>
    <ul class="inside">
    <li> KIAS-APCTP Statistical Physics Winter School (POSTECH) (2020) - ML & Deep Learning </li>
    <li> Data Youth Campus (Yonsei University) (2022) - Big Data analysis & Deep Learning </li>
    </ul>


  </div>
</div>

<br>

<div id="Motto" name="Motto" class="columns" style='background-color: #ffffff' >
  <br>
  <div class="column5">
    <h1> Life Motto </h1>

    <h3> 3 words abouts suceess </h3>
    <ul class="inside">
    
    <li> Lifeization : Making It a Part of Your Daily Life.  </li>
    <p> Whether you’re eating, taking a walk, or even running errands, constantly thinking about your field and how to improve it is what it means to truly make it a part of your everyday life. So, Let's do something I'm passionate about.No matter what you do, there will always come a time when it's hard and you feel like giving up. To get through those moments, you need to do something you love and are passionate about. This is the secret to success and how I live my life. </p>

    <li> Momentum </li>
    <p> You won’t really know anything until you give it a try. That’s why people who lack the momentum to take action often find it difficult to succeed. To find a field that I have passion for and can fully lifeizate, I must overcome the fear of trying new things. Let’s develop the habit of quickly running pilot tests to determine whether something has potential or not. </p>

    <li> Muscle growth : Mental Fortitude </li>
    <p> When you choose a particular field, you will inevitably face tough and challenging moments. To overcome these moments, having strong mental fortitude is absolutely essential.This is when you think about muscle growth. If you look at the process of muscle development, the first thing that happens is that muscle fibers tear, and new muscle fibers grow to fill the void. Human growth is no different than muscle development. The right amount of "tearing" is what makes you grow. </p>

    </ul>

    
    <h3> 3 words about Happiness </h3>
    <ul class="inside">
    <li> Friday </li>
    <p> Between Friday and Sunday, which day makes people happier? Most choose Friday. A high school senior who is certain of getting into a prestigious university is often happier than a student already attending one. A pair who just succeeded in confessing their love and is about to become a couple can be happier than couples already in a relationship. Essentially, people feel a stronger sense of happiness when the future is assured rather than while things are still unfolding. </p>

    <li> Value (Usefulness) </li>
    <p> Among the five stages of happiness, the highest level is identity. People find value and usefulness when they realize who they are and what unique abilities they possess—things that others can’t do—and this realization leads to happiness. </p>

    <li> Magic </li>
    <p> The magical moment in a performance goes by in a flash, yet magicians spend countless hours practicing to create that brief moment. Life works the same way. Three years of high school are dedicated to preparing for college entrance exams, and four years of college are spent honing skills for employment. We put in a great deal of time and effort to seize those fleeting moments of happiness. This is what happiness is all about. </p>
    </ul>

  </div>
</div>



</body>
</html>







<h2> Skills </h2>
* Python, C++, C#, HTML  
* Deep Learning Frame work: PyTorch
* 3D modeling: Unreal Engine, Unity, Sketchup







