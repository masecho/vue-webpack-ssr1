<template>
    <div id="app">
       <div id="cover">
           <Header></Header>
            <Todo></Todo>     
           <Footer></Footer>
       </div>
    </div>    
</template>
<script>
import Header from './todo/header.vue'
import Footer from './todo/footer.jsx'
import Todo from './todo/todo.vue'
export default {
    components:{    
        Header,Footer,Todo
    },
    data(){
        return {
            text:'abcddd'
        }
        
    }
}
</script>

<style>

</style>
