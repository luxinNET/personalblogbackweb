<template>
  <div>
    <div class="leftmenudiv"><leftmenu /></div>
    <div class="rightcontentdiv">
      <ul class="homerightcontent-ul">
        <homerightcontent msg='123' />
      </ul>
    </div>
  </div>
</template>
<style>
.leftmenudiv {
  float: left;
  width: 20%;
}
.homerightcontent-ul {
  width: 50%;
  margin: 0 auto;
  margin-top: 100px;
  list-style: none;
}
.rightcontentdiv {
  width: 78%;
  float: left;
}
</style>
<script>
// @ is an alias to /src
import leftmenu from '@/components/leftmenu.vue'
import homerightcontent from '@/components/rightcontent/homerightcontent.vue'

export default {
  name: 'Home',
  components: {
    leftmenu,
    homerightcontent
  }
}
</script>
