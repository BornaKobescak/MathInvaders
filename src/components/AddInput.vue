<template>
    <section>
        <b-field label="Name">
            <b-input v-model="name"></b-input>
        </b-field>

        <b-field label="Email">
            <b-input type="email" maxlength="30">
            </b-input>
        </b-field>

        <b-field label="Username"
            type="is-success"
            message="This username is available">
            <b-input v-model="username"  maxlength="30"></b-input>
        </b-field>
        <div class="notification is-primary">
            <div class="buttons">
                <b-button type="is-primary" inverted outlined>Posalji</b-button>
            </div>
        </div>

        

        
    </section>
</template>

<script>
    export default {
        data() {
            return {
                name: 'Borna Kobešćak',
                username:'bkobescak'
            }
        }
    }
</script>


  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
      section{
          width: 25%;
          margin-left: 500px;

      }
      .buttons{
          margin-left: 120px;
      }
 
  </style>