<template>
  <div class="main">
    <p>
      <router-link tag="li" to="/user_login">
        <button type="button" class="btn btn-primary btn-block">ログインページ</button>
      </router-link>
    </p>
    <p>
      <router-link tag="li" to="/user_registration">
        <button type="button" class="btn btn-primary btn=block">ユーザ登録</button>
      </router-link>
    </p>
    <p>
      <router-link tag="li" to="/dashboard">
        <button type="button" class="btn btn-primary btn=block">ダッシュボード</button>
      </router-link>
    </p>
  </div>
</template>

<script>
export default {
  name: "Home",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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