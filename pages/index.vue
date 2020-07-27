<template>
  <section class="section">
    <div class="columns is-mobile">
      <message
        message="İkinci el al ve sat
Kullanmadığın şeyleri sat ve harika fırsatlar bul."
      />
      <card
        title="Free"
        icon="github"
      >
        Open source on <a href="https://github.com/buefy/buefy">
          GitHub
        </a>
      </card>

      <card
        title="Responsive"
        icon="cellphone-link"
      >
        <b class="has-text-grey">
          Every
        </b> component is responsive
      </card>

      <card
        title="Modern"
        icon="alert-decagram"
      >
        Built with <a href="https://vuejs.org/">
          Vue.js
        </a> and <a href="http://bulma.io/">
          Bulma
        </a>
      </card>

      <card
        title="Lightweight"
        icon="arrange-bring-to-front"
      >
        No other internal dependency
      </card>
    </div>
  </section>
</template>

<script>
import Message from '../components/Message'
import Card from '~/components/Card'

export default {
  name: 'HomePage',

  components: {
    Message,
    Card
  }
}
</script>
