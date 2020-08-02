<template>
<svg
  @click="hiddenKey"
  xmlns="http://www.w3.org/2000/svg"
  width="160"
  height="160"
  viewBox="0 0 160 160"
  aria-labelledby="palette"
  role="presentation"
  >
  <g ref="radio">
    <line fill="#FFFFFF" x1="17.1" y1="30.8" x2="78.2" y2="91.9"></line>
    <path fill="#fbf615" d="M78.2,93.4c-0.4,0-0.8-0.1-1.1-0.4L16.1,31.9c-0.6-0.6-0.6-1.5,0-2.1c0.6-0.6,1.5-0.6,2.1,0l61.1,61.1
                  c0.6,0.6,0.6,1.5,0,2.1C78.9,93.2,78.6,93.4,78.2,93.4z"></path>
    <line fill="#FFFFFF" x1="78.2" y1="30.8" x2="17.1" y2="91.9"></line>
    <path fill="#fbf615" d="M17.1,93.4c-0.4,0-0.8-0.1-1.1-0.4c-0.6-0.6-0.6-1.5,0-2.1l61.1-61.1c0.6-0.6,1.5-0.6,2.1,0
    c0.6,0.6,0.6,1.5,0,2.1L18.2,92.9C17.9,93.2,17.5,93.4,17.1,93.4z"></path>
    <line fill="#FFFFFF" x1="47.7" y1="18.2" x2="47.7" y2="104.5"></line>
    <path fill="#fbf615" d="M47.7,106c-0.8,0-1.5-0.7-1.5-1.5V18.2c0-0.8,0.7-1.5,1.5-1.5s1.5,0.7,1.5,1.5v86.3
    C49.1,105.3,48.5,106,47.7,106z"></path>
    <line fill="#FFFFFF" x1="90.8" y1="61.3" x2="4.5" y2="61.3"></line>
    <path fill="#fbf615" d="M90.8,62.8H4.5c-0.8,0-1.5-0.7-1.5-1.5s0.7-1.5,1.5-1.5h86.3c0.8,0,1.5,0.7,1.5,1.5S91.7,62.8,90.8,62.8z"></path>
    <line fill="#FFFFFF" x1="7.8" y1="44.8" x2="87.5" y2="77.9"></line>
    <path fill="#fbf615" d="M87.5,79.4c-0.2,0-0.4,0-0.6-0.1l-79.8-33c-0.8-0.3-1.1-1.2-0.8-1.9c0.3-0.8,1.2-1.1,1.9-0.8l79.8,33
    c0.8,0.3,1.1,1.2,0.8,1.9C88.7,79,88.1,79.4,87.5,79.4z"></path>
    <line fill="#FFFFFF" x1="64.2" y1="21.5" x2="31.1" y2="101.2"></line>
    <path fill="#fbf615" d="M31.1,102.7c-0.2,0-0.4,0-0.6-0.1c-0.8-0.3-1.1-1.2-0.8-1.9l33-79.8c0.3-0.8,1.2-1.1,1.9-0.8
    c0.8,0.3,1.1,1.2,0.8,1.9l-33,79.8C32.3,102.4,31.7,102.7,31.1,102.7z"></path>
    <line fill="#FFFFFF" x1="31.1" y1="21.5" x2="64.2" y2="101.2"></line>
    <path fill="#fbf615" d="M64.2,102.7c-0.6,0-1.1-0.3-1.4-0.9L29.8,22c-0.3-0.8,0-1.6,0.8-1.9c0.8-0.3,1.6,0,1.9,0.8l33,79.8
    c0.3,0.8,0,1.6-0.8,1.9C64.6,102.7,64.4,102.7,64.2,102.7z"></path>
    <line fill="#FFFFFF" x1="87.5" y1="44.8" x2="7.8" y2="77.9"></line>
    <path fill="#fbf615" d="M7.8,79.4c-0.6,0-1.1-0.3-1.4-0.9c-0.3-0.8,0-1.6,0.8-1.9l79.8-33c0.8-0.3,1.6,0,1.9,0.8
    c0.3,0.8,0,1.6-0.8,1.9l-79.8,33C8.2,79.3,8,79.4,7.8,79.4z"></path>
  </g>
  <g ref="sun" fill="#fafa15">
    <path d="M80.6,61.3c0,18.2-14.8,33-33,33c-18.2,0-33-14.8-33-33c0-18.2,14.8-33,33-33
    C65.9,28.4,80.6,43.1,80.6,61.3"></path>
    <path d="M75.2,61.3c0,15.2-12.3,27.5-27.5,27.5S20.1,76.5,20.1,61.3c0-15.2,12.3-27.5,27.5-27.5
    S75.2,46.1,75.2,61.3"></path>
    <path d="M47.7,90.3c-16,0-29-13-29-29s13-29,29-29s29,13,29,29S63.7,90.3,47.7,90.3z M47.7,35.3
    c-14.4,0-26,11.7-26,26s11.7,26,26,26s26-11.7,26-26S62,35.3,47.7,35.3z"></path>
    <path d="M47.7,90.3c-16,0-29-13-29-29s13-29,29-29s29,13,29,29S63.7,90.3,47.7,90.3z M47.7,35.3
    c-14.44,0-26,11.7-26,26s11.7,26,26,26s26-11.7,26-26S62,35.3,47.7,35.3z"></path>
  </g>
  <g ref="key">
    <circle cx="48" cy="52" r="9" fill="#00D9B3"/>
    <circle cx="48" cy="50" r="2" fill="#fff"/>
    <rect x="45" y="60" width="2.3" height="20" fill="#00D9B3"/>
    <rect x="48" y="60" width="2" height="6" fill="#00D9B3"/>
    <rect x="48" y="66" width="3" height="2" fill="#00D9B3"/>
    <rect x="48" y="66" width="5" height="2" fill="#00D9B3"/>
    <rect x="48" y="68" width="3" height="2" fill="#00D9B3"/>
    <rect x="48" y="70" width="5" height="2" fill="#00D9B3"/>
    <rect x="48" y="72" width="3" height="2" fill="#00D9B3"/>
    <rect x="48" y="74" width="5" height="2" fill="#00D9B3"/>
    <rect x="48" y="76" width="3" height="2" fill="#00D9B3"/>
    <rect x="48" y="78" width="5" height="2" fill="#00D9B3"/>
  </g>
  <g ref="planet" style="opacity: 0;">
    <circle cx="23" cy="63" r="30" fill="#23233"/>
  </g>
</svg>
</template>
<script>
import { TimelineMax, Back } from 'gsap'

export default {
  methods: {
    hiddenKey () {
      console.log('click')
      const tl = new TimelineMax()
      tl.to(this.$refs.key, 0.001, {
        opacity: 0.9,
        delay: 0.1,
        ease: Back.easeOut
      })
        .to(this.$refs.key, 0.001, {
          opacity: 0.1,
          delay: 0.1,
          ease: Back.easeOut
        })
        .to(this.$refs.radio, 0.01, {
          opacity: 0.2,
          ease: Back.easeOut
        })
        .to(this.$refs.planet, 0.1, {
          opacity: 1,
          delay: 0.05,
          ease: Back.easeOut
        })
        .to(this.$refs.sun, 0.1, {
          opacity: 1,
          delay: 0.05,
          fill: '#caca10',
          ease: Back.easeOut
        })
        .to(this.$refs.radio, 0.01, {
          opacity: 0.1,
          ease: Back.easeOut
        })
        .to(this.$refs.planet, 0.1, {
          x: 25,
          y: -0.3,
          ease: Back.easeOut
        })
        .to(this.$refs.radio, 0.01, {
          opacity: 0,
          ease: Back.easeOut
        })
        .to(this.$refs.planet, 0.1, {
          x: 35,
          y: 0.3,
          ease: Back.easeOut
        })
        .to(this.$refs.radio, 0.01, {
          opacity: 0.2,
          ease: Back.easeOut
        })
        .to(this.$refs.planet, 0.1, {
          x: 45,
          y: 0.3,
          ease: Back.easeOut
        })
        .to(this.$refs.radio, 0.01, {
          opacity: 0.8,
          ease: Back.easeOut
        })
        .to(this.$refs.radio, 0.1, {
          opacity: 1,
          ease: Back.easeOut
        })
        .to(this.$refs.planet, 0.1, {
          opacity: 0,
          ease: Back.easeOut
        })
        .to(this.$refs.key, 0.1, {
          opacity: 1,
          ease: Back.easeOut
        })
        .to(this.$refs.sun, 0.1, {
          opacity: 1,
          delay: 0.05,
          fill: '#fafa15',
          ease: Back.easeOut
        })
        .to(this.$refs.planet, 0.1, {
          x: 0,
          y: -0.3,
          ease: Back.easeOut
        })
    }
  }
}
</script>
