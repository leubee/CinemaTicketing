<template>
  <br/>
</template>

<script>
export default {
  name: "AsyncProgrammingTemplate",
  created() {
    this.addSecInOdd()
    this.addSecInEven()
  },
  data() {
    return {
      count : 0,
    }
  },
  methods: {
    async addSecInEven() {
      await setTimeout(()=>null, 1000)
      while (true) {
        await setTimeout(this.addCount, 1000)
      }
    },

    async addSecInOdd() {
      while (true) {
        await setTimeout(this.addCount, 1000)
      }
    },

    addCount() {
      this.count += 1
      console.log('Count is now '+ this.count)
    }

  }
}

export class name {
}
</script>

<style scoped>

</style>