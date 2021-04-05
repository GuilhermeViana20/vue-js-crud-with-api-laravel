<template>
  <div id="app">
    <div class="ui fixed inverted menu vue-color">
      <div class="ui container">
        <a href="#" class="header item">Vue JS CRUD with Laravel API</a>
      </div>
    </div>

    <div class="ui main container">
      <MyForm />
      <CustomerList />
    </div>
  </div>
</template>

<script>

import axios from "axios";
import MyForm from "./components/MyForm";
import CustomerList from "./components/CustomerList";

export default {
  name: 'App',
  components: {
    MyForm,
    CustomerList
  },
  data() {
    return {
      url: "http://localhost/laravel-rest-api/public/api/customers",
      customers: []
    }
  }
}
</script>

<style>
  .vue-color {
    background: #41b883 !important;
  }

  .main.container {
    margin-top: 60px !important;
  }

  .submit-button {
    margin-top: 24px !important;
    float: right;
  }
</style>
