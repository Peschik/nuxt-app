<template>
  <div class="layout">
    <div class="relative flex transition-all justify-between max-w-4xl mx-auto mt-5">
      <div
        class="items-center transition-ease-in duration-800 absolute dark:bg-slate-800 flex gap-8"
      >
        <nuxt-link
          active-class="btn-primary"
          to="/admin/campaigns"
          class="transition duration-500 nav-item dark:text-white"
          >Кампании</nuxt-link
        >
        <nuxt-link
          active-class="btn-primary"
          to="/admin/statistics"
          class="transition duration-500 nav-item dark:text-white"
          >Статистика</nuxt-link
        >
        <nuxt-link
          active-class="btn-primary"
          to="/admin/advertizers"
          class="nav-item transition duration-500 dark:text-white"
          >Рекламодатели</nuxt-link
        >
        <nuxt-link
          active-class="btn-primary"
          to="/admin/event-list"
          class="transition duration-500 nav-item dark:text-white"
          >Лента Событий</nuxt-link
        >
        <nuxt-link
          active-class="btn-primary"
          to="/admin/control-panel"
          class="transition duration-500 nav-item dark:text-white"
        >
          Панель управления
        </nuxt-link>
      </div>
    </div>
    <div class="mx-auto pt-20 max-w-4xl dark:text-teal-100">
      <slot />
    </div>
  </div>
</template>

