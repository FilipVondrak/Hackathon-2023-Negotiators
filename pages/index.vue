<template>
  <div class="container">
    <section class="containerTitle">
      <h2>Negotiators bring you</h2>
      <h1>Study Core</h1>
      <p>Study Core is a web app that helps you study for your exams.</p>
    </section>
    <section class="main-menu">
      <el-row>
        <el-col span="6"><div class="grid-content ep-bg-purple" />
          <NuxtLink class="button-link" to="/onas"><p class="liner2"><el-button plain round>O Nás</el-button></p></NuxtLink>

        </el-col>
        <el-col span="6"><div class="grid-content ep-bg-purple" />
          <NuxtLink class="button-link" to="/schat"><el-button plain round>Školní chat</el-button></NuxtLink>

        </el-col>
        <el-col span="6"><div class="grid-content ep-bg-purple" />
          <NuxtLink class="button-link" to="/quiz"><p class="liner"><el-button plain round>Quiz</el-button></p></NuxtLink>

        </el-col>


      </el-row>

    </section>


    <section class="quiz-redirect">
      <h2>Nevíte, kam na školu?</h2>
      <el-row>
        <el-col span="6"><div class="grid-content ep-bg-purple" />
          <NuxtLink class="button-link" to="/onas"><p class="liner3"><el-button plain round>O Nás</el-button></p></NuxtLink>

        </el-col>



      </el-row>
    </section>

  </div>
</template>

<script setup>

</script>

<style scoped>

.container {
  width: 100%;
  height: 100%;

}

.containerTitle{
  width: 100%;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.containerFeatures {
  width: 100%;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.quiz-redirect{
  width: 100%;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.main-menu{
  width: 100%;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;

}
.button-link{
  text-decoration: none;
}
.el-button{
  text-decoration: none;
}


.el-row:last-child {
  margin-bottom: 0;
}
.el-col {
  border-radius: 4px;
  margin: 50px;
}
.grid-content {
  border-radius: 4px;
  min-height: 36px;
}
.liner {
  display: flex;
  align-items: flex-start;
  text-align: left;

  &:after {
    content: '';
    flex-grow: 1;
    height: 1px;
    background: purple;
    min-width: 100px;
    margin: auto;
  }

  &:after {
    margin-left: 10px;
  }
}
.liner2 {
  display: flex;
  align-items: flex-start;
  text-align: right;
  text-decoration: none;

  &:before {
    content: '';
    flex-grow: 1;
    height: 1px;
    background: purple;
    min-width: 100px;
    margin: auto;
  }

  &:before {
    margin-right: 10px;
  }
}
.liner3 {
  display: flex;
  align-items: flex-start;
  text-align: right;
  text-decoration: none;

  &:before {
    content: '';
    flex-grow: 1;
    height: 1px;
    background: purple;
    min-width: 100px;
    margin: auto;
  }

  &:before {
    margin-right: 10px;
  }
  &:after {
    content: '';
    flex-grow: 1;
    height: 1px;
    background: purple;
    min-width: 100px;
    margin: auto;
  }

  &:after {
    margin-left: 10px;
  }
}


</style>


