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
    <icon-base class="icons__image" icon-name="firefox" width="64" height="64" icon-color="#5434ad"><icon-firefox /></icon-base>
    <icon-base class="icons__image" icon-name="wiki" width="64" height="64" icon-color="#5434ad"><icon-wiki /></icon-base>
    <icon-base class="icons__image" icon-name="linux rosa" width="64" height="64" icon-color="#5434ad"><icon-linux-rosa /></icon-base>
    <icon-base class="icons__image" icon-name="icon radio" width="64" height="64" icon-color="#5434ad"><icon-radio /></icon-base>
    <icon-base class="icons__image" icon-name="icon web" width="64" height="64" icon-color="#5434ad"><icon-web /></icon-base>
    <icon-base class="icons__image" icon-name="icon aim" width="64" height="64" icon-color="#5434ad"><icon-aim /></icon-base>
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
import IconFirefox from './social/IconFirefox'
import IconWiki from './social/IconWiki'
import IconLinuxRosa from './social/IconLinuxRosa'
import IconRadio from './social/IconRadio'
import IconWeb from './social/IconWeb'
import IconAim from './social/IconAim'
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
    IconChrome,
    IconFirefox,
    IconWiki,
    IconLinuxRosa,
    IconRadio,
    IconWeb,
    IconAim
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
