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
  //     データの置き場所
  //   }
  // },
  // props: {
  //   データの受け取り
  // },
  // computed: {
  //   データの算出
  // },
  // methods: {
  //   メソッドの組み込み
  // },
  // created: {
  //   インスタンスが作成された後に同期的に呼ばれるフック
  // },
  // mounted: {
  //   インスタンスがマウントされたちょうど後に呼ばれるフック
  // }
};
</script>
