<template>
  <div class="container">
    <h1>About Me</h1>

    <div class="block">
      <div class="details">
        <p>
          Hello, i'm Sam. I've been a developer since 2019, working with digital
          marketing agencies and video games publishers. I took change in career
          from retail optics in 2019, and decided i want to spent more time on
          the internet. </p>
          
          <p>
          When studying I.T at college (way back when), i took a great liking to the website development side of things, and pursued a little in my spare time. But never having the confidence to push myself towards a career in it. A full time role at Specsavers came up, where i was working weekends, and i took it!
        </p>

        <p>
          I have spent a lot of time working in the world of <a href="https://developer.wordpress.org/" target="_blank" class="text-link">WordPress</a> during my employment. I initially studied with Python, using <a href="https://www.djangoproject.com/" target="_blank" class="text-link" >Django</a> as a backend solution, but i am always looking to work in new stacks.
        </p>

        <p>
          I am a huge video game junkie, and love playing and watching streaming when possible.
          My current games of choice are:

          <ul>
            <li><a href="https://store.steampowered.com/app/594650/Hunt_Showdown/" target="_blank" class="text-link">Hunt Showdown</a></li>
            
            <li><a href="https://store.steampowered.com/app/400750/Call_to_Arms__Gates_of_Hell_Ostfront/" target="_blank" class="text-link">Gates of Hell: Ostfront</a></li>

            <li><a href="https://store.steampowered.com/app/1144200/Ready_or_Not/" target="_blank" class="text-link">Ready or Not</a></li>
          </ul>
        </p>

        <p>
          I enjoy playing Airsoft regularly with friends, a great way to run about, make a fool of yourself and play dress up 😂! If you want to see what that looks like, i have some videos and images on my <a href="https://instagram.com/samuelwatson89/" target="_blank" class="text-link">instagram page</a>
        </p>
      </div>

      <div>
        <div class="portrait">
          <img src="/img/sam-watson.jpg" alt="Portrait image of me!" />
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped="scoped">
h1 {
  margin-bottom: 2rem;
}

ul {
  font-size: 1.4rem;
}

.details {
  position: relative;
  z-index: 2;
}

@media screen and (max-width: 600px) {
  .portrait {
    margin-bottom: -45%;
    position: relative;
  }

  .portrait:after {
    content: '';
    position: absolute;
    width: 100%;
    bottom: 0;
    height: 60%;
    background: var(--bg-blend);
  }
}
</style>
