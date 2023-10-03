<script setup lang="ts">
import { ElInput } from 'element-plus'
import { ContentWrap } from '@/components/ContentWrap'
import { useI18n } from '@/hooks/web/useI18n'
import { ref } from 'vue'

defineOptions({
  name: 'Menu2'
})

const { t } = useI18n()

const text = ref('')
</script>

<template>
  <ContentWrap>
    <div class="flex items-center">{{ t('levelDemo.welcome') }}</div>
  </ContentWrap>
</template>
