<template>
  <div>hahahah
       <div class="close">关闭</div>
  </div>
 
</template>

<script>
export default {
     props: {

    layerid: {
      type: String,
      default: ""
    }

  },
methods: {
    close() {
        this.$layer.close(this.layerid);
    }
}
}
</script>

<style>

</style>