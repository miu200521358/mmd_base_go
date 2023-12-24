
<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
    name: "ConfigPage",
});

</script>

<template>
    <main>
        <div class="input-layer">
            <div class="button-layer">
                <div>モデル</div>
                <button>履歴</button>
            </div>
            <div class="file-layer">
                <div>(未読み込み)</div>
                <input id="modelName" type="file" accept=".pmx" />
            </div>
        </div>
    </main>
</template>
