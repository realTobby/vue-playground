<template>
  <div class="hello">
    <h1>{{ msg1 }}</h1>
    <h2>{{ msg2 }}</h2>
    </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg1: String,
    msg2: String
  }
}
</script>
