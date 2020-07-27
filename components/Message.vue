<template>
  <section>
    <button class="button block" @click="isActive = !isActive">
      Toggle
    </button>
    <b-message title="Default" :active.sync="isActive" aria-close-label="Close message">
      {{ message }}
    </b-message>
  </section>
</template>

<script>
export default {
  props: {
    message: {
      type: String,
      required: true
    }
  },
  data () {
    return {
      isActive: true
    }
  }
}
</script>
