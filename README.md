# prodigy-4

html
<div class="bgimage">
  <div class="hero-text">
    <h1 class="hero_title">Welcome to My Portfolio!</h1>
    <p class="hero_desc">I am a skilled web developer with experience in a variety of technologies. I am passionate about building high-quality, user-friendly websites and applications.</p>
  </div>
</div>/* hero background image */
.bgimage {
  height:100vh;
  background: url('images/heroImage.jpeg');
  background-size:cover;
  position:relative;
}

/* text css above hero image*/
.hero_title {
  font-size: 4.5rem;
}

.hero_desc {
  font-size: 2rem;
}

.hero-text {
  text-align: center;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: white;
}


<section id="about">
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-4">
        <img src="images/profile.jpg" alt="Profile picture" class="imageAboutPage">
      </div>
      <div class="col-lg-8">
        <h2>About Me</h2>
        <p>I am a web developer with a passion for creating engaging, user-friendly websites and applications. I have a strong background in HTML, CSS, and JavaScript, and I am always looking for new technologies to learn and incorporate into my work.</p>
        <h3>Education</h3>
        <p>I have a Bachelor's degree in Computer Science from XYZ University.</p>
        <h3>Professional Experience</h3>
        <p>I have been working as a web developer for 5 years, and I have experience in a variety of industries including healthcare, finance, and e-commerce.</p>
      </div>
    </div>
  </div>
</section>

css
/* about section image css */
.imageAboutPage {
  width: 100%;
}

/* about section css */
#about {
  background-color: #f5f5f5;
  padding: 3rem 0;
}

#about h2 {
  font-size: 2.5rem;
  margin-bottom: 1.5rem;
}

#about p {
  font-size: 1.5rem;
  line-height: 1.5;
}

#about h3 {
  font-size: 1.8rem;
  margin-top: 3rem;
  margin-bottom: 1rem;
}


