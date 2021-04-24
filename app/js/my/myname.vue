<template>     
    <Panel title="我的信息" :class="$style.panel">
        <section :class="$style.content">
            <img src="//img12.360buyimg.com/jrpmobile/jfs/t2644/238/1420176553/1442/96e2885/573d96deN06201af5.png" alt="">
            <p>会员福利 ></p>
        </section>
    </Panel>
</template>
<script>
import Panel from "../core/panel.vue"
export default {
    components: {
        Panel,
    },
}
</script>
<style lang="scss" module>
@import "../../css/element.scss";
  .panel{
    @include panel;
    >h4{
      display: none;
    }
    .content{
        @include flex(row);
        margin-top: 120px;
        height: 140px;
        line-height: 140px;
        text-align: center;
        position: relative;
        img{
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin: 20px 32px 0;
            display: block;
        }
        p {
            height: 60px;
            line-height: 60px;
            color: #999;
            float: right;
            margin-top: -15px;
            font-size: 28px;
            position: absolute;
            right: 32px;
            top: 50%;
        }
    }
  }
</style>