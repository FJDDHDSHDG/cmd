<template>
  <view class="page">
    <view class="title">
      <view class="top">合肥</view>
      <image src="/static/icon/jiantou.png" class="tupian" />
      <view class="shuru">
        <image src="/static/icon/sousuo.png" class="jietu" />
        <view class="btn">找工作找房子</view>
      </view>
    </view>
    <view class="s-title">
      <view class="weng">
        <view class="shang">
          <image src="/static/icon/shang.png" class="tu" />
          <view class="btn"> 免费找店 </view>
        </view>
        <view class="shang">
          <image src="/static/icon/shang.png" class="tu" />
          <view class="btn"> 免费找店 </view>
        </view>
        <view class="shang">
          <image src="/static/icon/shang.png" class="tu" />
          <view class="btn"> 免费找店 </view>
        </view>
        <view class="shang">
          <image src="/static/icon/shang.png" class="tu" />
          <view class="btn"> 免费找店 </view>
        </view>
      </view>
      <view class="dian">
        <view class="yunde">
          <image src="/static/icon/shang.png" class="tu" />
          <view class="btn"> 免费找店 </view>
        </view>
        <view class="yunde">
          <image src="/static/icon/shang.png" class="tu" />
          <view class="btn"> 免费找店 </view>
        </view>
        <view class="yunde">
          <image src="/static/icon/shang.png" class="tu" />
          <view class="btn"> 免费找店 </view>
        </view>
        <view class="yunde">
          <image src="/static/icon/shang.png" class="tu" />
          <view class="btn"> 免费找店 </view>
        </view>
      </view>
      <view class="banzi">
        <view class="m-dian">
          <view class="s-dian"></view>
          <view class="s-dian"></view>
          <view class="s-dian"></view>
        </view>
      </view>
      <view class="fenlei">
        <view class="xiang">
          <view class="xian">生意转让</view>
          <view class="fang">房屋出租</view>
          <view class="fangzu">房屋求租</view>
        </view>
        <view class="duan">
          <view class="hong"></view>
        </view>
      </view>
      <view class="content">
        <image src="/static/icon/shitu.png" class="tu" />
        <view class="wenhao">
          <view class="wenzi-1">业主直转！淮河路步行街旺铺餐馆</view>
          <view class="wenzi-2">庐阳 - 淮河路步行街 | 经营中</view>
          <view class="wenzi-2">刘先生 张震牛面馆</view>
        </view>
      </view>
      <view class="shifu">
        <image src="/static/icon/shitu.png" class="tushi" />
        <view class="wang">
          <view class="wenzi-1">业主直转！淮河路步行街旺铺餐馆</view>
          <view class="wenzi-2">庐阳 - 淮河路步行街 | 经营中</view>
          <view class="wenzi-2">刘先生 张震牛面馆</view>
        </view>
      </view>
    </view>
  </view>
</template>

<style lang="scss" scoped>
.page {
  .title {
    margin-left: 18px;
    display: flex;
    .top {
      margin-top: 2px;
      width: 27px;
      height: 20px;
      font-size: 12px;
      color: #333333;
      line-height: 17px;
    }
    .tupian {
      width: 11px;
      height: 6px;
      margin-top: 7px;
      margin-left: 2px;
    }
    .shuru {
      display: flex;
      width: 242px;
      height: 30px;
      background: #f9f9f9;
      border-radius: 15px;
      margin-left: 80px;
      margin-top: 0px;
      margin-right: 11px;

      border-radius: 15px;
      .jietu {
        width: 16px;
        height: 16px;
        margin-top: 7px;
        margin-left: 23px;
      }
      .btn {
        width: 72px;
        height: 18px;
        font-size: 12px;
        line-height: 27px;
        margin-left: 3px;
        color: #cccccc;
      }
    }
  }
  .s-title {
    .weng {
      margin-top: 25px;
      display: flex;
      justify-content: space-around;
      .shang {
        .tu {
          width: 32px;
          height: 32px;
          margin-left: 8px;
        }
        .btn {
          width: 48px;
          height: 17px;
          font-size: 12px;
          color: #666666;
          line-height: 17px;
        }
      }
    }
    .dian {
      margin-top: 25px;
      display: flex;
      justify-content: space-around;
      .yunde {
        .tu {
          width: 32px;
          height: 32px;
          margin-left: 8px;
        }
        .btn {
          width: 48px;
          height: 17px;
          font-size: 12px;
          color: #666666;
          line-height: 17px;
        }
      }
    }
  }
  .banzi {
    margin-top: 20px;
    width: 337px;
    height: 80px;
    background: #f8e71c;
    border-radius: 40px;
    margin-left: 10px;
    .m-dian {
      margin-left: 37%;
      .s-dian {
        float: left;
        margin-top: 65px;
        margin-left: 15px;
        width: 8px;
        height: 8px;
        background: #ffffff;
        border-radius: 42px;
      }
    }
  }
  .fenlei {
    .xiang {
      display: flex;
      margin-top: 20px;
      margin-left: 30px;
      .xian {
        width: 48px;
        height: 17px;
        font-size: 12px;
        color: #ff552e;
        line-height: 17px;
      }
      .fang {
        width: 48px;
        height: 17px;
        font-size: 12px;
        color: #0e8ed8;
        line-height: 17px;
        margin-left: 15px;
      }
      .fangzu {
        width: 48px;
        height: 17px;
        font-size: 12px;
        color: #0e8ed8;
        line-height: 17px;
        margin-left: 15px;
      }
    }
    .duan {
      margin-top: 10px;
      width: 100%;
      height: 1px;
      background: #ffeeeeee;
      .hong {
        width: 66px;
        height: 1px;
        background: #ff552e;
        margin-left: 19px;
      }
    }
  }
  .content {
    margin-top: 10px;
    display: flex;
    .tu {
      width: 150px;
      height: 100px;
    }
    .wenhao {
      margin-top: 10px;
      .wenzi-1 {
        margin-left: 10px;
        width: 175px;
        height: 34px;
        font-size: 12px;
        font-weight: 500;
        color: #333333;
        line-height: 17px;
      }
      .wenzi-2 {
        margin-top: 3px;
        margin-left: 10px;
        width: 155px;
        height: 30px;
        font-size: 12px;
        color: #666666;
        line-height: 17px;
      }
    }
  }
  .shifu {
    margin-top: 10px;
    display: flex;
    .tushi {
      width: 150px;
      height: 100px;
    }
    .wang {
      margin-top: 10px;
      .wenzi-1 {
        margin-left: 10px;
        width: 175px;
        height: 34px;
        font-size: 12px;
        font-weight: 500;
        color: #333333;
        line-height: 17px;
      }
      .wenzi-2 {
        margin-top: 3px;
        margin-left: 10px;
        width: 155px;
        height: 30px;
        font-size: 12px;
        color: #666666;
        line-height: 17px;
      }
    }
  }
}
</style>