<template>
  <div class="homepage">
    <div class="sign-desk" aspectratio aspect-ratio="375/215">
      <div aspectratio-content>
        <div w-335-64>
          <div w-44-44 >15</div>
          <div class="date">2018.5.6 星期三</div>
          <div aspectratio w-134-44>
            <div aspectratio-content>
              <img src="@/assets/images/button-daka.png" alt="">
            </div>
          </div>
        </div>

        <div class="morning">
          <img src="@/assets/images/icon-up.png" alt="">无
          <img src="@/assets/images/icon-que.png" alt="">
          <span>(今日未签到)</span>
        </div>
        <div class="morning afternoon">
          <img src="@/assets/images/icon-down.png" alt="">打卡时间17:55
          <img src="@/assets/images/icon-tui.png" alt="">
          <span>(今日已签退)</span>
        </div>

      </div>
    </div>
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
.homepage .sign-desk {
  width: 375px;
  background-image: linear-gradient(-180deg, #FB4A4A 0%, #FF3053 100%);
  margin-top: 20px;
}
.sign-desk {
  aspect-ratio:'375:215';
}
[w-335-64] {
  width: 335px;
  height: 64px;
  margin: 30px auto 20px;
  border-bottom: 0.5px solid #dedede;
}
[w-44-44] {
  float: left;
  width: 44px;
  height: 44px;
  border-radius: 3px;
  background-color: #F7F7F7;
  font-size: 32px;
  color: #fc424d;
  line-height: 44px;
  font-family: BrandonGrotesque-Bold;
  text-align: center;
}
.sign-desk .date {
  float: left;
  width: 111px;
  text-align: center;
  height: 44px;
  font-size: 14px;
  color: #fff6f7;
  font-family: PingFangSC-Regular;
  line-height: 44px;
  vertical-align: super;
  margin-right: 30px;
  margin-left: 16px;
}
[w-134-44] {
  float: left;
  width: 134px;
}
[w-134-44] {
  aspect-ratio:'134:44';
}
.morning{
  font-family: PingFangSC-Regular;
  font-size: 14px;
  color: #ffd6db;
}
.morning img{
  width: 20px;
  height: 20px;
}
.morning img:nth-child(1){
  margin-left: 33px;
  margin-right: 10px;
}
.morning img:nth-child(2){
  margin-left: 24px;
}
.morning span{
  display: inline-block;
  margin-left: 10px;
  width: 103px;
  line-height: 20px;
  text-align: center;
}
.afternoon{
  margin: 30px 0;
}
</style>
