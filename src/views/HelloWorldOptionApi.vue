<script>
import HelloComponent from "@/components/HelloComponent.vue";

export default {
  name: 'HelloWorldOptionsApi',
  components: {HelloComponent},
  data() {
    return {test: "ma donnée de test"}
  },
  methods: {}
}
</script>

<template>
  <HelloComponent msg="TESTEST"/>
</template>