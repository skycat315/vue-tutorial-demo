<template>
  <!-- The root div of the Vue app -->
 <div id="app">
   <!-- Display a paragraph -->
   <p>Watch the magic happen!</p>
   <!-- A button that increments the count when clicked -->
   <button @click="count++">Count is: {{ count }}</button>
 </div>
</template>

<script>
import { ref } from "vue"; // Import the ref function from Vue

export default {
  // Setup function for reactive data
 setup() {
   const count = ref(0); // Reactive count variable
   return { count }; // Make count available to the template
 },
};
</script>