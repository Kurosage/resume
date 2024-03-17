<template>
  <div class="my-auto">
    <h2 class="mb-5">{{ $t('skills.title') }}</h2>

    <div class="subheading mb-3">{{ $t('skills.iconsTitle') }}</div>
    <ul class="list-inline list-icons" style="text-align:center">
      <!-- <li v-for="icon in title" :key="icon" class="list-inline-item">
          <div :class="icon"></div>
      </li> -->
      <li v-for="(icon,text) in $t('skills.devIcons')" :key="icon" >
        <!-- <p v-for="text in $t('skills.devIconsText')" :key="icon" class="list-inline-item"> -->
            <i style="display: inline-block" :class="icon">{{text}}</i>
        <!-- </p> -->
      </li>
    </ul>
  </div>
</template>

<script >

export default{
  setup(){
   
    return{
   
    }
  } 
}
</script>
