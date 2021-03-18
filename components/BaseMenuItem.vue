<template>
  <div
    v-click-outside="closeEvent"
    class="relative"
    @mouseover="showSubMenu = true"
  >
    <NuxtLink :to="item.to">{{ item.name }}</NuxtLink>
    <ul
      v-if="item.menu && showSubMenu"
      class="mt-5 p-4 text-gray-500 bg-white absolute w-48 rounded space-y-3"
    >
      <li
        v-for="(subItem, i) in item.menu"
        :key="`sub-item-${i}`"
        @click.stop="showSubMenu = false"
      >
        <NuxtLink v-if="subItem.name" :to="subItem.to">{{
          subItem.name
        }}</NuxtLink>
        <hr v-if="subItem.isDivider" />
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  props: {
    item: {
      type: Object,
      default() {
        return {}
      },
    },
  },
  data() {
    return {
      showSubMenu: false,
    }
  },
  methods: {
    show() {
      this.showSubMenu = true
    },
    hide() {
      this.showSubMenu = false
    },
    closeEvent() {
      this.hide()
    },
    navigateTo(to) {
      this.$router.push(to)
    },
  },
}
</script>
