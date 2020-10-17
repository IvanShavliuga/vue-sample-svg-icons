<template>
  <div class="iconbar">
    <icon-base class="iconbar__image" icon-name="facebook" width="64" height="64" icon-color="#5434ad"><socialfacebook/></icon-base>
    <icon-base class="iconbar__image" icon-name="instagram" width="64" height="64" icon-color="#5434ad"><socialinstagram/></icon-base>
    <icon-base class="icons__image" icon-name="linkedin" width="64" height="64" icon-color="#5434ad"><sociallinkedin/></icon-base>
    <icon-base class="icons__image" icon-name="odnolassniki" width="64" height="64" icon-color="#5434ad"><socialodnolassniki/></icon-base>
    <icon-base class="icons__image" icon-name="tumblr" width="64" height="64" icon-color="#5434ad"><socialtumblr/></icon-base>
    <icon-base class="icons__image" icon-name="twitter" width="64" height="64" icon-color="#5434ad"><socialtwitter/></icon-base>
    <icon-base class="icons__image" icon-name="vk" width="64" height="64" icon-color="#5434ad"><socialvk/></icon-base>
    <icon-base class="icons__image" icon-name="wechat" width="64" height="64" icon-color="#5434ad"><socialwechat/></icon-base>
  </div>
</template>
<script>
import IconBase from './IconBase'
import Socialfacebook from './social/facebook.vue'
import Socialinstagram from './social/instagram.vue'
import Sociallinkedin from './social/linkedin.vue'
import Socialodnolassniki from './social/odnolassniki.vue'
import Socialtumblr from './social/tumblr.vue'
import Socialtwitter from './social/twitter.vue'
import Socialvk from './social/vk.vue'
import Socialwechat from './social/wechat.vue'
export default {
  components: {
    IconBase,
    Socialfacebook,
    Socialinstagram,
    Sociallinkedin,
    Socialodnolassniki,
    Socialtumblr,
    Socialtwitter,
    Socialvk,
    Socialwechat
  }
}
</script>
