<template>
  <div id="container">
    <section id="containerTitle">
      <h2>Negotiators bring you</h2>
      <h1>Study Core</h1>
      <p>Study Core is a web app that helps you study for your exams.</p>
    </section>
    <section id="containerFeatures">
      <h2>Features</h2>
      <ul>
        <li>Flashcards</li>
        <li><NuxtLink to="/quiz">Quiz na pomoc vybrání školy a oboru</NuxtLink> </li>
        <li><NuxtLink to="/chat">Student forum</NuxtLink></li>
        <li>Study Groups</li>
      </ul>
    </section>
  </div>
</template>

<script setup>

</script>

<style scoped>

#container {
  width: 100%;
  height: 100%;
}

#containerTitle{
  width: 100%;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

#containerFeatures {
  width: 100%;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
</style>


