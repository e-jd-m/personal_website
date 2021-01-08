<template>
  <div>
    <div class="greeting">Hello👋</div>
    <h1 id="name">I'm Adam Žaloudek</h1>
    <div id="about">
      <div class="contact-box">
        <ul class="contacts">
          <li>mail@zaloudek.dev</li>
          <li><a href="https://github.com/e-jd-m">Github</a></li>
        </ul>
      </div>
      <div id="summary">
        <p>CS student, aspiring developer</p>
      </div>
      <div id="skills-box">
        <ul id="skills">
          <li>PHP (Nette)</li>
          <li>JS (Node, Vue)</li>
          <li>Java</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
};
</script>

<style scoped>
.contact-btn:hover {
  cursor: pointer;
}

.about {
  display: flex;
}

.contacts,
#skills {
  list-style: none;
  display: flex;
  align-items: center;
  justify-content: center;
}
.contacts li,
#skills li {
  margin-right: 0.5em;
}

#skills li:not(:first-child):before {
  content: "| ";
}

.greeting,
#name {
  text-align: center;
}
#summary {
  text-align: center;
}
</style>
