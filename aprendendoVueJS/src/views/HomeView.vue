<script>

export default {
  name: "Home",
    data() {
        return {

        }
    },
    mounted(){
      console.log(window.location.search);
    }
}
</script>

<template>
  <base-layout>
    <div>
      <!-- <iframe scrolling="yes" style="width:100%; min-height: calc(961px - 40px); border: none;" src="https://launch.spribegaming.com/aviator?user=5213E4C2-9A00-4828-97A5-F8B63709884C&amp;token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJubUF1dGgiOiI1MjEzRTRDMi05QTAwLTQ4MjgtOTdBNS1GOEI2MzcwOTg4NEMiLCJpYXQiOjE2NjQ2NDAxOTIsImV4cCI6MTY2NDcyNjU5Mn0.5Mes8of5FudWooQRnWIg7hAu22OvCoYrnvqpxqmAM7k&amp;lang=pt-br&amp;currency=BRL&amp;operator=apostaganha"></iframe> -->
      <iframe style="width:100%; min-height: calc(961px - 40px); border: none;" src="https://demo.spribe.io/launch/aviator?currency=USD&amp;lang=pt-br"></iframe>
    </div>
  </base-layout>
</template>
