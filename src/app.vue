<template>
    <div id="app">
       <div id="cover">
           <Header></Header>
            <Todo></Todo>     
            <Counter></Counter>     
           <Footer></Footer>
       </div>
    </div>    
</template>
<script>
import Header from "./todo/header.vue";
import Footer from "./todo/footer.jsx";
import Todo from "./todo/todo.vue";
import Counter from "./counter/counter.vue";
export default {
  components: {
    Header,
    Footer,
    Todo,
    Counter
  },
  data() {
    return {
      text: "abcddd"
    };
  }
};
</script>

<style>
</style>
