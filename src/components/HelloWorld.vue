<template>
  <h2>{{ msg }}</h2>
  <div class="Come-play"><p> Come play with me and all of my friends!</p>
  </div>
  <div class="First-sentence"><p>How many dinosaur friends does Adrian have?</p>
  </div>
  <button @click="count++">Dino friends: {{ count }}</button>
  <div class="Second-sentence">
  <p>Adrian, you currently have {{ count }} friends! Yay!</p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data() {
    return {
      count: 0
    }
  }
}
</script>

