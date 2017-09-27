<template>
  <md-card>
    <md-card-media>
      <img :src="imageUrl" alt="">
    </md-card-media>
    <md-card-header>
      <div class="md-title">{{ full_name }}</div>
      <div class="md-subhead">@{{ username }}</div>
      <md-card-content>
        {{ contents }}
      </md-card-content>
    </md-card-header>
  </md-card>
</template>
<script>
export default {
  name: 'Feed',
  props: ['imageUrl', 'full_name', 'username', 'contents']
}
</script>
