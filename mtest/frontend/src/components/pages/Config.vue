
<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "ConfigPage",
});

</script>

<template>
  <main>
    <div class="input-layer">
      <div class="text-layer">
        <div class="input-title">モデル</div>
        <input id="modelName" type="file" accept=".pmx" />
      </div>
      <div class="button-layer">
        <button>履歴</button>
      </div>
    </div>
  </main>
</template>
