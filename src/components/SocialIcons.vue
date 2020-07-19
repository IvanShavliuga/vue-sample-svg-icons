<template>
  <div class="icons">
    <icon-base class="icons__image" icon-name="github" width="64" height="64" icon-color="#5434ad"><icon-github /></icon-base>
    <icon-base class="icons__image" icon-name="codepen" width="64" height="64" icon-color="#5434ad"><icon-codepen /></icon-base>
    <icon-base class="icons__image" icon-name="like" width="64" height="64" icon-color="#5434ad"><icon-like /></icon-base>
    <icon-base class="icons__image" icon-name="vk" width="64" height="64" icon-color="#5434ad"><icon-vk /></icon-base>
    <icon-base class="icons__image" icon-name="android" width="64" height="64" icon-color="#5434ad"><icon-android /></icon-base>
    <icon-base class="icons__image" icon-name="linux" width="64" height="64" icon-color="#5434ad"><icon-linux /></icon-base>
    <icon-base class="icons__image" icon-name="ubuntu" width="64" height="64" icon-color="#5434ad"><icon-ubuntu /></icon-base>
    <icon-base class="icons__image" icon-name="Windows" width="64" height="64" icon-color="#5434ad"><icon-Windows /></icon-base>
    <icon-base class="icons__image" icon-name="chrome" width="64" height="64" icon-color="#5434ad"><icon-chrome /></icon-base>
  </div>
</template>

<script>
import IconGithub from './social/IconGithub'
import IconCodepen from './social/IconCodepen'
import IconLike from './social/IconLike'
import IconVk from './social/IconVk'
import IconAndroid from './social/IconAndroid'
import IconLinux from './social/IconLinux'
import IconUbuntu from './social/IconUbuntu'
import IconWindows from './social/IconWindows'
import IconChrome from './social/IconChrome'
import IconBase from './IconBase'
export default {
  name: 'SocialIcons',
  components: {
    IconBase,
    IconGithub,
    IconCodepen,
    IconLike,
    IconVk,
    IconAndroid,
    IconLinux,
    IconUbuntu,
    IconWindows,
    IconChrome
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
.icons {
  border: 1px solid #5434ad;
  padding: 20px;
  &__image {
    margin: 20px;
  }
}
</style>
