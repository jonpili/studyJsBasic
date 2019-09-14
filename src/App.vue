<template>
  <v-app>
    <v-content>
      <router-view />
    </v-content>
  </v-app>
</template>

<script>
export default {
  name: 'App'
  // data () {
  //   return {
  //     xxx: データの置き場所
  //   }
  // },
  // props: {
  //   xxx: データの受け取り
  // },
  // computed: {
  //   xxx: function() {
  //     return データの自動算出
  //   }
  // },
  // watch: {
  //   xxx: function() {
  //     データ変更時にメソッドを実行
  //   }
  // },
  // methods: {
  //   xxx: function() {
  //     メソッドの組み込み
  //   }
  // },
  // created: function() {
  //   インスタンスが作成された後に同期的に呼ばれるフック
  // },
  // mounted: function() {
  //   インスタンスがマウントされたちょうど後に呼ばれるフック
  // }
};
</script>
