<template>
   <section>
      <h2>Animated Icons</h2>
      <p class="info">Icons purchased from <a href="https://creativemarket.com/dianahlevnjak/1607119-Styled-stock-photography-icons" target="_blank">Creative Market</a>, readied for animation with <a href="https://www.adobe.com/products/illustrator.html" target="_blank">Adobe Illustrator</a> and <a href="https://jakearchibald.github.io/svgomg/" target="_blank">SVGOMG</a></p>
      <p>Click on the icons below</p>
      <icon-scissors />
      <icon-heart-face />
      <icon-watch />
      <icon-palette />
      <icon-sun-key/>
      <icon-sun-key-login/>
    </section>
</template>

<script>
import IconWatch from './animatedicons/IconWatch.vue'
import IconPalette from './animatedicons/IconPalette.vue'
import IconScissors from './animatedicons/IconScissors.vue'
import IconHeartFace from './animatedicons/IconHeartFace.vue'
import IconSunKey from './animatedicons/IconSunKey'
import IconSunKeyLogin from './animatedicons/IconSunKeyLogin'

export default {
  components: {
    IconWatch,
    IconPalette,
    IconScissors,
    IconHeartFace,
    IconSunKey,
    IconSunKeyLogin
  }
}
</script>

<style scoped>
svg {
  cursor: pointer;
}
</style>
