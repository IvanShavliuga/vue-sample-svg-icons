<template>
  <div class="icons">
    <icon-base class="icons__image" icon-name="github" width="64" height="64" icon-color="#5434ad"><icon-github /></icon-base>
    <icon-base class="icons__image" icon-name="codepen" width="64" height="64" icon-color="#5434ad"><icon-codepen /></icon-base>
    <icon-base class="icons__image" icon-name="like" width="64" height="64" icon-color="#5434ad"><icon-like /></icon-base>
  </div>
</template>

<script>
import IconGithub from './social/IconGithub'
import IconCodepen from './social/IconCodepen'
import IconLike from './social/IconLike'
import IconBase from './IconBase'
export default {
  name: 'SocialIcons',
  components: {
    IconBase,
    IconGithub,
    IconCodepen,
    IconLike
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
