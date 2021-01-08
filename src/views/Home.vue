<template>
  <div>
    <div class="greeting">Hello👋</div>
    <h1>I'm Adam Žaloudek</h1>
    <div class="contact-box">
      <ul class="contacts">
        <li>mail@zaloudek.dev</li>
        <li><a href="https://github.com/e-jd-m">Github</a></li>
      </ul>
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

.contacts {
  list-style: none;
  display: flex;
  align-items: center;
  justify-content: center;
}
.contacts li {
  margin-right: 15px;
}
.greeting {
  text-align: center;
}
</style>
