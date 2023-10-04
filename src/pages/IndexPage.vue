
<template>
  <div class="htmlClass">
    <h1>{{ title }}</h1>
    <InputPage/>
    <FunctionPage/>
  </div>
</template>


<script>
import FunctionPage from './FunctionPage.vue';
import InputPage from './InputPage.vue';

export default {
    name: 'HtmlComponent',
    data() {
        return {
            title: 'ศรายุทธ์ เอี่ยมอุไร',
        };
    },
    components: { InputPage, FunctionPage }
}
</script>

<style scoped></style>
