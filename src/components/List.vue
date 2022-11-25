<template>
  <!-- titld, content, date-->
  <div>
    <h5>{{exampleData[0].title}}</h5>
    <p>{{exampleData[0].date}}</p>
  </div>
  <div>
    <h5>{{exampleData[1].title}}</h5>
    <p>{{exampleData[1].date}}</p>
  </div>
  <div>
    <h5>{{exampleData[2].title}}</h5>
    <p>{{exampleData[2].date}}</p>
  </div>
</template>

<script>
export default {
    name : "blogList",
    props : {
        exampleData : Array,
    }
}
</script>

<style>

</style>