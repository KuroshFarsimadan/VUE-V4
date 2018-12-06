<template>
<div>
  <b>
    Tester tests his testings before he wins 1.500 billoin lottery. Here we could use manual testing for methods, components, or others.
    It is highly recommended to use Jenkins or automated testing tools or custom built libraries.

    <div v-on:scroll.passive="onScroll">...</div>


    When listening for keyboard events, we often need to check for common key codes. Vue also allows adding key modifiers for v-on when listening for key events:

    <!-- only call `vm.submit()` when the `keyCode` is 13 -->
    <input v-on:keyup.13="submit">
    Remembering all the keyCodes is a hassle, so Vue provides aliases for the most commonly used keys:

    <!-- same as above -->
    <input v-on:keyup.enter="submit">

    <!-- also works for shorthand -->
    <input @keyup.enter="submit">
  </b>
</div>
</template>

<script>
import { bus } from "../main";

export default {
  name: "Test",
  data() {
    return {};
  },

  methods: {}
};
</script>


