<template>
    <article >
      <div class="flex">
        <div>
          <img :src="source" :alt="name" >
        </div>
        <div>
          <h2 class="name">{{name}}</h2>
          <p class="position">Verified Graduate</p>
        </div>
      </div>
      <p> {{ intro }} </p>
      <p> {{ pra }} </p>
    </article>
</template>

<script>
export default {
    name:'setion',
    props:{
       name:String,
       source:String,
       pra:String,
       intro:String
    }
}
</script>