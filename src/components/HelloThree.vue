<template lang="html">
  <div w-335-75 flexcontainer>
    <ul w-167>
      <li>
        <img src="@/assets/images/icon-guest.png" alt="">客户数
      </li>
      <li>666人</li>
    </ul>
    <ul>
      <li>
        <img class="xuxian" src="@/assets/images/xuxian.png" alt="">
      </li>
    </ul>
    <ul w-167>
      <li>
        <img src="@/assets/images/icon-dangri.png" alt="">当日放款
      </li>
      <li>223,234,87.00元</li>
    </ul>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="css" scoped>
[w-335-75]{
  width: 335px;
  height: 75px;
  border-bottom: 0.5px solid #dedede;
  margin: auto;
  padding-top: 12.5px
}
[flexcontainer] img{
  width: 14px;
  height: 14px;
  position: relative;
  top: 3px;
  left: -2px;
}
[w-167] {
  width: 167px;
  text-align: center;
}
[w-167] li:nth-child(1) {
  font-family: PingFangSC-Regular;
  font-size: 14px;
  letter-spacing: 0;
  color: #999;
}
[w-167] li:nth-child(2) {
  font-family: PingFangSC-Regular;
  font-size: 18px;
  letter-spacing: 0;
  color: #333;
}
[flexcontainer] ul li .xuxian{
  height: 50px;
  width: 2px;
}
</style>
