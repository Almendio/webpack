<template>
  <div class="hello">
    <b-title>\{{ msg }}</b-title>
    <b-title class="is-2">Essential Links</b-title>
    <ul>
      <li><a href="https://vuejs.org" target="_blank">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank">Forum</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank">Twitter</a></li>
      <br>
      <li><a href="http://vuejs-templates.github.io/webpack/" target="_blank">Docs for This Template</a></li>
    </ul>
    <b-title class="is-2">Ecosystem</b-title>
    <ul>
      <li><a href="http://router.vuejs.org/" target="_blank">vue-router</a></li>
      <li><a href="http://vuex.vuejs.org/" target="_blank">vuex</a></li>
      <li><a href="http://vue-loader.vuejs.org/" target="_blank">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank">awesome-vue</a></li>
    </ul>
    <section class="section">
      <div class="container">
        <b-title>Hello World</b-title>
        <subtitle>My first website with <strong>Bulma</strong>!</subtitle>
        <columns is-mobile>
          <column is-half is-offset-one-quarter>
            <box>
              <media>
                <media-left>
                  <b-image class="is-64x64">
                    <img src="https://bulma.io/images/placeholders/128x128.png" alt="Image">
                  </b-image>
                </media-left>
                <media-content>
                  <b-content>
                    <p>
                      <strong>John Smith</strong> <small>@johnsmith</small> <small>31m</small>
                      <br>
                      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean efficitur sit amet massa fringilla egestas. Nullam condimentum luctus turpis.
                    </p>
                  </b-content>
                  <level class="is-mobile">
                    <level-left>
                      <a class="level-item">
                        <icon class="is-small"><fa name="reply"></fa></icon>
                      </a>
                      <a class="level-item">
                        <icon class="is-small"><fa name="retweet"></fa></icon>
                      </a>
                      <a class="level-item">
                        <icon class="is-small"><fa name="heart"></fa></icon>
                      </a>
                    </level-left>
                  </level>
                </media-content>
              </media>
            </box>
          </column>
        </columns>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
