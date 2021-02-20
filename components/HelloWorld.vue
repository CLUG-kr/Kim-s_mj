<template>
  <div class="jumbotron" >
     <b-jumbotron >
    <template #header >cAllI.cpp</template>

    <template #lead>
      글씨체 교정을 도와주는 나의 맞춤 AI 도우미_cAllI.cpp
    </template>

    <hr class="my-4">

    <p>
      글꼴을 선택하고 사진을 따라 직접 글씨를 써 업로드 해보세요! 
    </p>

    <p>
      예쁜 글씨체, 당신도 가질 수 있습니다.
    </p>
    
  </b-jumbotron>
  </div>
</template>

<script>
export default {
  name: 'jumbotron',
  props: {
    msg: String
  }
}
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
  color: #3c423f;
}
  .jumbotron {
            background: url("https://blog.kakaocdn.net/dn/sZ7ux/btqDSzwx1NN/c0FYKBDM9WacVK61NpYar1/img.jpg") center center / cover no-repeat;
        }
        
</style>
