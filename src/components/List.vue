<template lang="html">
  <div class="">
    <div class="block" flexcontainer>
      <div w-60-60 aspectratio >
        <div aspectratio-content>
          <img src="@/assets/images/icon-changgui.png" alt="">
        </div>
      </div>
      <div>
        <p>汽车之家</p>
        <div>
          ·进价中2   ·上传拆封照10
        </div>
      </div>
    </div>

    <div class="block" flexcontainer>
      <div w-60-60 aspectratio >
        <div aspectratio-content>
          <img src="@/assets/images/icon-dajiadia.png" alt="">
        </div>
      </div>
      <div>
        <p>瓜子二手车</p>
        <div>
          ·进价中2   ·上传拆封照10
        </div>
      </div>
    </div>

    <div class="block" flexcontainer>
      <div w-60-60 aspectratio >
        <div aspectratio-content>
          <img src="@/assets/images/icon-qudao.png" alt="">
        </div>
      </div>
      <div>
        <p>人人车</p>
        <div>
          ·进价中2   ·上传拆封照10
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>
@svg 1px-border {
  height: 2px;
  @rect {
    fill: var(--color, black);
    width: 100%;
    height: 50%;
  }
}
.block{
  width: 335px;
  margin: auto;
  border-bottom: 1px solid transparent;
  border-image: svg(1px-border param(--color #DEDEDE)) 2 2 stretch;
  padding-bottom: 10px
}
.block p{
  font-size: 16px;
  color: #333;
  font-family: PingFangSC-Regular;
}
.block div {
  color: #727c8d;
  font-size: 11px;
}
[w-60-60]{
  width: 60px;
  margin-right: 7px;
  margin-top: 13px;
}
[w-60-60] {
  aspect-ratio: '60:60';
}

[aspectratio-content] img {
  width: 60px;
}
</style>
