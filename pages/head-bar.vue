<template>
    <div class="head-bar">
      <ul>
        <li>
          <a href="profil"></a>
          <img src="~/assets/icons/Artboards_Diversity_Avatars_by_Netguru-1.svg" alt="Photo de profil">
        </li>
      </ul>
      </div>

</template>

<script>
export default {

}
</script>

<style lang="postcss" scoped>

.head-bar {
  @apply fixed top-0 left-0 w-full bg-gray-600 p-1;
}

.head-bar > ul {
  @apply flex list-none flex-row-reverse mr-10;
}

.head-bar > ul > li > img {
  @apply h-12 cursor-pointer p-2 ;
}
.head-bar > ul > li > .PP > img {
  @apply h-12 cursor-pointer p-1 ;
}


</style>