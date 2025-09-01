<template>
  <div :class="{'dark': darkMode}">
    <div class="bg-white dark:bg-dim-900">
   
    <div class ="min-h-full">

      <div class ="grid grid-cols-12 mx-auto sm:px-6 lg:max-w-7xl lg:px-8 lg:gap-5">

        <!-- Left Sidebar   -->

        <div class ="hidden md:block xs-col-span-1 xl-col-span-2">
          <div class ="sticky top-0">
            <SidebarLeft/>
          </div>
          
        </div>

        <!-- Main content -->

        <!-- Right Sidebar-->
        </div>  

    

    </div>
    </div>

  </div>
</template>


<script setup>
//import SidebarLeft from '~/components/Sidebar/Left.vue' // Use this if your file is Left.vue
const darkMode = ref(false)


</script>
<style>
.logo {
  height: 10rem; /* h-10 */
  width: 10rem;  /* w-10 */
  border-radius: 9999px; /* rounded-full */
  color: #fff; /* dark:text-white fallback */
}
</style>