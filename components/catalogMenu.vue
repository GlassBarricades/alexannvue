<template>
  <v-card outlined class="mb-6">
    <div class="subtitle font-weight-black text-uppercase text-center mt-4">
      Категории
    </div>
    <v-list dense>
      <v-list-item-group color="primary">
        <v-list-item v-for="(item, i) in items" :key="i">
          <v-list-item-content>
            <v-list-item-title v-text="item.text"></v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-list-item-group>
    </v-list>
  </v-card>
</template>
<script>
export default {
  data() {
    return {
      items: [
        { text: 'Ламинат' },
        { text: 'Линолеум' },
        { text: 'News' },
        { text: 'Виниловое покрытие' },
        { text: 'Межкомнатные двери' },
        { text: 'Входные двери' },
        { text: 'Водосточная система' },
        { text: 'Декоративный камень' },
      ],
    }
  },
}
</script>
