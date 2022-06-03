<template>
  <div class="contact">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-1 profile-image">
          <img src="../assets/profile.png" alt="Profile" width="100">
        </div>
        <div class="col-6 text-start">
          <h4>{{ firstName }} {{ lastName }}</h4>
          <p class="text-muted">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptates modi minima neque
            inventore totam tempora corrupti cupiditate a laudantium fuga, ipsum, dicta odio! Harum ullam, sunt tempora
            minima nesciunt odit?</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ContactView',
  data: function () {
    return {
      firstName: 'Muhammad Abdiel',
      lastName: 'Firjatullah',
    }
  }
}
</script>

<style scoped>
.profile-image {
  margin-right: 20px;
}
</style>