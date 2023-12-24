
<script lang="ts">
import { defineComponent } from "vue";
import { useI18n } from "vue-i18n";

export default defineComponent({
    name: "ConfigPage",
    setup() {
        const { t } = useI18n();
        return {
            t
        };
    }
});
</script>

<template>
    <main>
        <div class="input-layer">
            <div class="button-layer">
                <div>{{ t("model.title") }}</div>
                <button>履歴</button>
            </div>
            <div class="file-layer">
                <div>(未読み込み)</div>
                <input id="modelName" type="file" accept=".pmx" />
            </div>
        </div>
    </main>
</template>
