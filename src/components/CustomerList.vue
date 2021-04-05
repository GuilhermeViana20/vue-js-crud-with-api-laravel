<template>
  <div class="customer-list">
    <div class="data">
        <table class="ui celled table">
            <thead>
                <tr>
                    <th style="width: 50px; text-align: center">#</th>
                    <th>Nome</th>
                    <th>E-mail</th>
                    <th style="width: 165px">Acao</th>
                </tr>
            </thead>

            <tbody>
                <Customer />
            </tbody>
        </table>
    </div>
  </div>
</template>

<script>

    import Customer from "./Customer"

    export default {
        name: "CustomerList",
        components: {
            Customer
        }
    }
</script>

<style scoped>

</style>
