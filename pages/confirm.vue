<script setup lang="ts">
import {useSupabaseUser} from "@nuxtjs/supabase/dist/runtime/composables/useSupabaseUser";

const user = useSupabaseUser()
watch(user, () => {
  if (user.value) {
    return navigateTo('/')
  }
}, { immediate: true })
</script>
<template>
  <div>Waiting for login...</div>
</template>