<template>
  <div :class="cn('flex items-center justify-center [&>div]:w-full', $attrs.class ?? '')">
    <slot />
  </div>
</template>

<script setup lang="ts">
import { cn } from '@/lib/utils';
</script>
