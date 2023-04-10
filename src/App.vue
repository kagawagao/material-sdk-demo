<script setup lang="ts">
import MaterialSDK from '@wii/material-sdk'
const material = new MaterialSDK({
  url: '',
  skey: '',
  type: 1
})

const handleClick = () => {
  material.show({
    url: '',
    skey: ''
  })
}
</script>

<template>
  <div>
    <button @click="handleClick">打开选择器</button>
  </div>
</template>
