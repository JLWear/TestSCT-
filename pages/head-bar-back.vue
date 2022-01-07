<template>
      <div class="head-bar-back">
      <ul>
        <li>
          <img src="~/assets/icons/arrow_icon 180.svg" alt="Flèche retoure">
        </li>
        <li>
          <div class="PP">
            <a href="profil"></a>
          <img src="~/assets/icons/Artboards_Diversity_Avatars_by_Netguru-1.svg" alt="Photo de profil">
          </div>
        </li>
      </ul>
      </div>

</template>

<script>
export default {

}
</script>

<style lang="postcss" scoped>


.head-bar-back {
  @apply fixed top-0 left-0 w-full bg-gray-600 p-1;
}

.head-bar-back > ul {
  @apply flex list-none;
}

.head-bar-back > ul > li > img {
  @apply h-12 cursor-pointer p-2 ;
}

.head-bar-back > ul > li > .PP > img {
  @apply h-12 cursor-pointer p-1 fixed right-4;
}

</style>