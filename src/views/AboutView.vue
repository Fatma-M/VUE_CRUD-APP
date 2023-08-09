<template>
  <div class="container about">
    <h1>Todoist</h1>
    <p>
      Vue Todos is a CRUD Todo tracking application created for a Vue 3 Crash
      Course by John Komarnicki.
    </p>

    <p>
      Track your daily task's using this todo tracker with abilities to save,
      complete, edit & delete todos.
    </p>
  </div>
</template>

<style lang="scss" scoped>
.about {
  margin: 3rem 20px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;

  h1 {
    margin-bottom: 20px;
  }

  p {
    margin: 10px;
  }
}
</style>
