<template>
  <div align="center" justify="center">
    <table>
      <tr>
        <v-app>
          <div>
            <AddElecPeriodComponent style="margin-bottom: 30px" />
            <DisplayElecPeriodsComponent />
          </div>
        </v-app>
      </tr>
    </table>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

import AddElecPeriodComponent from "@/components/AddElecPeriodComponent.vue";
import DisplayElecPeriodsComponent from "@/components/DisplayElecPeriodsComponent.vue";

@Component({
  components: {
    AddElecPeriodComponent,
    DisplayElecPeriodsComponent,
  },
})
export default class MainComponent extends Vue {}
</script>

<style scoped></style>
