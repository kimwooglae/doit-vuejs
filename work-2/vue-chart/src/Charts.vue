<template>
    <div id="container" style="width:100%; height:400px"></div>
</template>

<script>
export default {
  mounted() {
    Highcharts.chart('container', {
      chart: {
        type: 'bar'
      },
      title: {
        text: 'Fruit Consumption'
      },
      xAxis: {
        categories: ['Apples', 'Bananas', 'Oranges']
      },
      yAxis: {
        title: {
          text: 'Fruit eaten'
        }
      },
      series: [{
        name: 'Jane',
        data: [1,2,5]
      }, {
        name: 'John',
        data: [4,3,7]
      }]
    })
  }    
}
</script>

<style scoped>
</style>