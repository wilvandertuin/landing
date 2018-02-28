<template>
  <article>
    <figure class="avatar"></figure>

    <h1>Jeroen van der Tuin</h1>
    <h2>Remote Front-end Web App Developer</h2>

    <p>
      Currently trending topics:  Vue.js, CSS Grid, VS Code
      <img src="@/assets/emoji-rock.png" class="emoji" alt=""/>
    </p>

    <p>
      <a class="email" href="mailto:jeroen@vandertuin.nl">jeroen@vandertuin.nl</a>
    </p>

    <ul class="social">
      <li>
        <a href="https://codepen.io/Jeromche">
          <img src="@/assets/icon-codepen.png" alt="CodePen" style="width: 24px; height: 24px"/>
        </a>
      </li>
      <li>
        <a href="https://github.com/jeromche">
          <img src="@/assets/icon-github.svg" alt="Github" style="width: 24px; height: 24px"/>
        </a>
      </li>
      <li>
        <a href="https://twitter.com/jeromche">
          <img src="@/assets/icon-twitter.svg" alt="Twitter" style="width: 24px; height: 24px"/>
        </a>
      </li>
      <li>
        <a href="https://www.linkedin.com/in/jeromche" title="LinkedIn">
          <img src="@/assets/icon-linkedin.png" alt="LinkedIn" style="width: 24px; height: 24px"/>
        </a>
      </li>
    </ul>
  </article>
</template>

<style scoped>
@keyframes article-appear {
  from {
    opacity: 0;
    margin-top: 40px;
  }

  to {
    opacity: 1;
    margin-top: 0;
  }
}

article {
  position: absolute;
  top: 50%;
  left: 50%;
  margin-top: 40px;
  transform: translate(-50%,-50%);
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  background-color: white;
  border-radius: 5px;
  width: 376px;
  max-width: 100%;
  max-height: 100%;
  overflow-y: auto;
  padding: 30px 45px;
  color: #4A4A4A;
  font-size: 18px;
  line-height: 1.5em;
  box-shadow: 0 40px 100px rgba(0,0,0,.4);
  animation: .5s article-appear ease-out;
  will-change: opacity, margin;
}

.avatar {
  width: 100px;
  height: 100px;
  border-radius: 100px;
  background-color: #eee;
  background-image: url('../../assets/avatar.png');
  background-size: cover;
  margin-bottom: 25px;
}

h1 {
  margin: 0;
  margin-bottom: 25px;
  font-size: 24px;
}

h2 {
  margin: 0;
  margin-bottom: 25px;
  font-weight: normal;
  font-size: 18px;
  max-width: 200px;
}

.trending-emoji {
  vertical-align: sub;
}

.email {
  color: inherit;
}

.social {
  margin: 0;
  padding: 0;
  display: flex;
  list-style-type: none;
}

.social a {
  display: inline-block;
  padding: 10px;
}
</style>
