<template>
  <div>

    <p>Server status {{ status }}</p>
    <hr>
    <button @click="changeStatus">Change</button>
    </div>

</template>

<script>
export default {
  data: function() {
    return {
      status: "criticle"
    };
  },
  methods:{
    changeStatus(){
      this.status='normal'
    }
  }
};
</script>
