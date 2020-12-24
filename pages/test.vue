<template>
  <div>{{array}}
  <v-btn @click="change()">  </v-btn>
  </div>
</template>


<script>
export default {
  data() {
    return {
      array:[1,1,1,1]
    };
  },
  
  methods: {
   change(){
       this.array[1] = 3
       console.log(this.array)
   }
  }
};
</script>

<style >
.container {
  width: 640px !important;
}
.arrnow {
  width: 80px !important ;
}
</style>
