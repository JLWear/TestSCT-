<template>

      <div class="head-bar-searchinput">
        <div class="search">
          <input type="text" class="input" placeholder=" ">
          <label class="label">Search</label>
        </div>
        <div class="list">
          <li>
          <button>Prospect</button>
          <button>Client</button>
          <button>Archivé</button>
          <button>Supprimer</button>
        </li>
        </div>
        
      </div>
</template>

<script>
export default {

}
</script>

<style lang="postcss" scoped>

.head-bar-searchinput {
  @apply fixed top-0 left-0 w-full h-28 bg-gray-600 p-2 grid grid-rows-2 gap-4;
}

.head-bar-searchinput > .search{
  @apply relative w-56 ml-auto mr-auto;
}
.head-bar-searchinput > .search > .input{
  @apply absolute w-full h-6 rounded border-2 border-white font-sans outline-none p-5 bg-transparent text-white ;
}

.head-bar-searchinput > .search > .label{
  @apply absolute left-3 -top-3 pt-0 duration-200 ease-in bg-gray-600 text-white p-1;
}

.head-bar-searchinput > .list{
  @apply overflow-auto items-center justify-center
}
.head-bar-searchinput > .list > li{
  @apply list-none flex items-center justify-around
}
.head-bar-searchinput > .list > li > button{
  @apply rounded border-2 border-white text-white p-1 focus:bg-white focus:border-gray-600 focus:text-gray-600;
}


</style>