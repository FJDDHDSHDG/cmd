<template>
  <view class="page">
    <view class="title">快帮网</view>
    <view class="s-title">干啥都行，干啥都快 </view>
    <view class="shouji">
      <view class="wrap">
        <image src="/static/shouji.png" class="icon" />
        <view class="btn">手机号码</view>
      </view>
    </view>
    <view class="yanzheng">
      <view class="wrap">
        <view class="left">
          <image src="/static/duanxin.png" class="icon" />
          <input type=" text" class="input" placeholder="短信验证码" />
        </view>
        <view class="btn">获取动态码</view>
      </view>
    </view>
    <view class="btn-dengru">
      <view class="btn">登入</view>
    </view>
    <view class="btn-zhuce">
      <view class="btn">立即注册</view>
    </view>
  </view>
</template>


<style lang="scss" scoped>
.page {
  .title {
    height: 70px;
    font-size: 24px;
    text-align: center;
    line-height: 87px;
    color: #ff552e;
	font-weight: bold;
  }
  .s-title {
    line-height: 5px;
    margin-top: 5px;
    text-align: center;
    color: #ff552e;
    font-weight: 400px;
  }
  .shouji {
    margin-top: 40px;
    .wrap {
      width: 80%;
      margin-left: auto;
      margin-right: auto;
      height: 44px;
      background: #ffffff;
      border-radius: 22px;
      display: flex;
      border: 3px solid #eeeeee;

      .icon {
        width: 12px;
        height: 18px;
        margin-top: 12px;
        margin-left: 24px;
      }
      .btn {
        margin-left: 10px;
        margin-top: 10px;
        border: none;
        font-size: 14px;
        color: #cccccc;
      }
    }
  }
  .yanzheng {
    margin-top: 16px;
    .wrap {
      width: 80%;
      margin-left: auto;
      margin-right: auto;
      height: 44px;
      background: #ffffff;
      border-radius: 22px;
      display: flex;
      justify-content: space-between;
      .left {
        width: 55%;
        height: 40px;
        border-radius: 22px;
        border: 3px solid #eeeeee;
        display: flex;

        .icon {
          width: 17px;
          height: 10px;
          margin-top: 14px;
          margin-left: 24px;
        }
        .input {
          font-size: 14px;
          color: #cccccc;
          margin-top: 10px;
          margin-left: 10px;
        }
      }
      .btn {
        width: 101px;
        height: 44px;
        font-size: 14px;
        background: #ffffff;
        border-radius: 22px;
        border: 3px solid #eeeeee;
        text-align: center;
        line-height: 44px;
        color: #0e8ed8;
        font-weight: bold;
      }
    }
  }
  .btn-dengru {
    .btn {
      width: 80%;
      margin-left: auto;
      margin-right: auto;
      height: 44px;
      background: #ff552e;
      border-radius: 22px;
      text-align: center;
      margin-top: 30px;
      font-weight: bold;
      line-height: 44px;
      color: #ffffff;
    }
  }
  .btn-zhuce {
    .btn {
      margin-left: 160px;
      margin-top: 30px;
      color: #0e8ed8;
      font-size: 14px;
      font-weight: bold;
    }
  }
}
</style>
