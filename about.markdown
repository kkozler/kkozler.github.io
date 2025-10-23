---
layout: page
title: About
permalink: /
redirect_from:
  - /about
---

<div class="about-container">
  <div class="about-text">
    <p>Hi! I'm Keegan! .</p>
    <p>I'm a software engineer with 7+ years of experience building web applications and leading teams. I pride myself on delivering impactful results in both front-end and back-end domains, whether working with legacy systems or greenfield projects.</p>
    <p>In my time as a machine learning engineer at X by 2, I've worked with a great team to build Choreo-ED, a patient flow solution for emergency departments. During that time, I also completed a Master of Science in Computer Science at Georgia Institute of Technology, specializing in machine learning. Prior to that, I served as a technical lead at ProModel (later BigBear.ai) on their Shipyard AI product. (Check out my <a href="/assets/pdf/resume.pdf">resume</a> for more specifics!)</p>
    <p>I get excited when I'm able to work with great people to build cool things, and I love striving with my team toward the best possible version of ourselves as individuals and teammates.  </p>
    <p>In my life outside of work, I'm an avid musician and play piano and guitar. I also enjoy the challenge of strategy games and, in my free time, unwinding with books, movies, and quality time with my wife and two kids. </p>
  </div>
  <img src="/assets/me.jpg" alt="Keegan Kozler" class="about-image">
</div>

<style>

.about-container {
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  gap: 1rem;
  flex-wrap: wrap; /* allows wrapping for small screens */
}

.about-text {
  flex: 1;
  min-width: 250px; /* ensures text doesn’t collapse too much */
}

.about-image {
  width: 300px;
  max-width: 100%; /* scales down on small screens */
  height: auto;
  border-radius: 8px;
  padding-left: 5px;
}

/* Stack image below text on mobile */
@media (max-width: 768px) {
  .post-header {
    display: none;
  }

  .about-container {
    flex-direction: column;
    align-items: center;
    text-align: center;
  }

  .about-image {
    padding-left: 0;
    margin-top: 1rem;
  }
}


</style>