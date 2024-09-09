<script
  setup
  lang="ts"
>
import QRow from "./QRow.vue";
</script>

<template>
<div>
  <div class="border-b">
    <header>
      <slot name="header"></slot>
    </header>
  </div>

  <div>
    <QRow>
      <template #sidebar>
        <aside class="pr-8 border-r py-6 h-full">
          <slot name="sidebar"></slot>
        </aside>
      </template>

      <main class="py-6">
        <slot></slot>
      </main>
    </QRow>
  </div>

  <footer class="border-t">
    <slot name="footer"></slot>
  </footer>
</div>
</template>