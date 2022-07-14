<script setup>
import { watchLang } from '@varlet/cli/site/utils'
import BButton from '../Button'
import { pack, use } from './locale'

watchLang(use, 'pc')
</script>

<template>
  <b-button color="#2563EB">{{ pack.mainButton }}</b-button>
  <b-button color="#03A9F4">{{ pack.infoButton }}</b-button>
  <b-button color="#009688">{{ pack.successButton }}</b-button>
  <b-button color="#D97706">{{ pack.warnButton }}</b-button>
  <b-button color="#DC2626">{{ pack.dangerButton }}</b-button>
</template>
