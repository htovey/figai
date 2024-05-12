<template>
  <div :class="$style.mobileframeParent">
    <div :class="$style.mobileframe">
      <div :class="$style.rectangleParent">
        <div :class="$style.frameChild" />
        <div :class="$style.frameItem" />
        <div :class="$style.name">Name</div>
        <div :class="$style.frameInner" />
        <div :class="$style.rectangleDiv" />
        <div :class="$style.frameChild1" />
      </div>
      <div :class="$style.statusbarIphone678Se">
        <div :class="$style.time">9:41 AM</div>
        <div :class="$style.rightSide">
          <img :class="$style.batteryIcon" alt="" src="/battery@2x.png" />
          <div :class="$style.div">100%</div>
          <img :class="$style.alarmIcon" alt="" src="/alarm@2x.png" />
          <img :class="$style.bluetoothIcon" alt="" src="/bluetooth@2x.png" />
        </div>
        <div :class="$style.leftSide">
          <img
            :class="$style.mobileSignalIcon"
            alt=""
            src="/mobile-signal.svg"
          />
          <div :class="$style.carrier">Figma</div>
          <img :class="$style.wifiIcon" alt="" src="/wifi.svg" />
        </div>
      </div>
      <div :class="$style.button">
        <div :class="$style.post">Post</div>
      </div>
      <div :class="$style.rectangleGroup">
        <div :class="$style.frameChild" />
        <div :class="$style.frameItem" />
        <div :class="$style.name">Name</div>
        <div :class="$style.frameInner" />
        <div :class="$style.rectangleDiv" />
        <div :class="$style.frameChild1" />
      </div>
    </div>
  </div>
</template>
<script lang="ts">
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "Group",
  });
</script>
<style module>
  .frameChild {
    position: absolute;
    top: 55px;
    left: 2px;
    background-color: var(--color-yellowgreen);
    width: 282px;
    height: 226px;
  }
  .frameItem {
    position: absolute;
    top: 0px;
    left: 0px;
    border-radius: 50%;
    background-color: var(--color-yellowgreen);
    width: 37px;
    height: 36px;
  }
  .name {
    position: absolute;
    top: 14px;
    left: 110px;
  }
  .frameInner {
    position: absolute;
    top: 318px;
    left: 1px;
    background-color: var(--color-gainsboro);
    width: 30px;
    height: 29px;
  }
  .rectangleDiv {
    position: absolute;
    top: 318px;
    left: 53px;
    background-color: var(--color-gainsboro);
    width: 30px;
    height: 29px;
  }
  .frameChild1 {
    position: absolute;
    top: 318px;
    left: 105px;
    background-color: var(--color-gainsboro);
    width: 30px;
    height: 29px;
  }
  .rectangleParent {
    position: absolute;
    top: 27px;
    left: 44px;
    width: 284px;
    height: 347px;
    overflow: hidden;
  }
  .time {
    position: absolute;
    top: 15%;
    left: calc(50% + 35.5px);
    line-height: 16px;
    font-weight: 600;
  }
  .batteryIcon {
    position: absolute;
    top: 1.5px;
    right: 0px;
    width: 26.5px;
    height: 11.5px;
    object-fit: cover;
  }
  .div {
    position: absolute;
    top: 0.3px;
    right: 29.5px;
    line-height: 16px;
  }
  .alarmIcon {
    position: absolute;
    top: 0px;
    right: 76.5px;
    width: 14px;
    height: 14px;
    object-fit: cover;
  }
  .bluetoothIcon {
    position: absolute;
    top: 0px;
    right: 61.5px;
    width: 14px;
    height: 14px;
    object-fit: cover;
  }
  .rightSide {
    position: absolute;
    top: 3px;
    right: 5.5px;
    width: 90.5px;
    height: 16.3px;
    text-align: right;
  }
  .mobileSignalIcon {
    width: 21px;
    position: relative;
    height: 14px;
  }
  .carrier {
    position: relative;
    letter-spacing: -0.05px;
    line-height: 16px;
  }
  .wifiIcon {
    width: 15px;
    position: relative;
    height: 14px;
  }
  .leftSide {
    position: absolute;
    top: 3px;
    left: 4px;
    overflow: hidden;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-9xs);
    text-align: left;
  }
  .statusbarIphone678Se {
    position: absolute;
    top: 3px;
    left: 1px;
    width: 375px;
    height: 20px;
    overflow: hidden;
    text-align: center;
    font-family: var(--default-bold-body);
  }
  .post {
    position: relative;
    letter-spacing: -0.41px;
    line-height: 22px;
  }
  .button {
    position: absolute;
    right: 45px;
    bottom: 16px;
    border-radius: var(--br-3xs);
    background-color: var(--default-systemblue-light);
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    padding: var(--padding-smi) var(--padding-xl);
    text-align: center;
    font-size: var(--default-bold-body-size);
    color: var(--label-color-dark-primary);
    font-family: var(--font-acme);
  }
  .rectangleGroup {
    position: absolute;
    top: 422px;
    left: 45px;
    width: 284px;
    height: 347px;
    overflow: hidden;
  }
  .mobileframe {
    position: absolute;
    top: 0px;
    left: 0px;
    background-color: var(--label-color-dark-primary);
    width: 378px;
    height: 844px;
    overflow: hidden;
  }
  .mobileframeParent {
    width: 100%;
    position: relative;
    height: 844px;
    text-align: left;
    font-size: var(--font-size-xs);
    color: var(--label-color-light-primary);
    font-family: var(--font-inter);
  }
</style>
