<template>
  <div class="my-form">
    <form class="ui form">
        <div class="fields">
            
            <div class="four wide field">
                <label for="">Nome</label>
                <input type="text" name="first_name" placeholder="Seu Nome"/>
            </div>

            <div class="four wide field">
                <label for="">Sobrenome</label>
                <input type="text" name="last_name" placeholder="Sobrenome"/>
            </div>

            <div class="six wide field">
                <label for="">E-mail</label>
                <input type="email" name="email" placeholder="joe@gmail.com"/>
            </div>

            <div class="two wide field">
                <button class="ui primary button submit-button">Salvar</button>
            </div>

        </div>
    </form>
  </div>
</template>

<script>
    export default {
        name: "MyForm" 
    }
</script>

<style scoped>

</style>
