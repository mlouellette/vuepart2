<script>
  import flash from "@/mixins/flash";

  export default {
    mixins: [flash]
  };

</script>

<template>
  <div>
    <p>
      <button @click="flash('It works on the about page')">Click Me</button>
    </p>

  </div>
</template>

