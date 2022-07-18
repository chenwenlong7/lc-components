<script setup>
import AppType from '@varlet/cli/site/mobile/components/AppType'
import { watchLang } from '@varlet/cli/site/utils'
import BasicUse from './BasicUse'
import ModifyColor from './ModifyColor'
import { pack, use } from './locale'

watchLang(use)
</script>

<template>
  <app-type>{{ pack.basicUse }}</app-type>
  <basic-use/>
  <app-type>{{ pack.modifyColor }}</app-type>
  <modify-color/>
  <app-type>{{ pack.textButton }}</app-type>
  <app-type>{{ pack.disabledStatus }}</app-type>
  <app-type>{{ pack.loadingStatus }}</app-type>
  <app-type>{{ pack.buttonSize }}</app-type>
  <app-type>{{ pack.blockButton }}</app-type>
  <app-type>{{ pack.customColor }}</app-type>
  <app-type>{{ pack.roundButton }}</app-type>
  <app-type>{{ pack.event }}</app-type>
</template>
