  <template>
    <div class="hello">
      <h1>{{ msg }}</h1>
      <h2>Font Awesome</h2>
      <ul>
        <li><i class="fa fa-user"></i></li>
        <li><i class="fa fa-check"></i></li>
        <li><i class="fa fa-image"></i></li>
        <li><i class="fa fa-github"></i></li>
      </ul>
      <h2>Bootstrap Component</h2>
      <div class="row">
        <div class="col-md-6">
           <div class="alert alert-success">
            <a href="#" class="close" data-dismiss="alert">&times;</a>
            Alert Success
          </div>
        </div>

        <div class="col-md-6">
          <!-- Button trigger modal -->
          <button type="button" class="btn btn-primary btn-lg" data-toggle="modal" data-target="#myModal">
            Launch demo modal
          </button>
        </div>
      </div>

      <!-- Modal -->
      <div class="modal fade" id="myModal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
        <div class="modal-dialog" role="document">
          <div class="modal-content">
            <div class="modal-header">
              <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
              <h4 class="modal-title" id="myModalLabel">Modal title</h4>
            </div>
            <div class="modal-body">
              ...
            </div>
            <div class="modal-footer">
              <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
              <button type="button" class="btn btn-primary">Save changes</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>

  <script>
  export default {
    name: 'hello',
    data () {
      return {
        msg: 'Welcome to Your Vue.js App With Bootstrap & Font Awesome'
      }
    }
  }
  </script>

  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  h1, h2 {
    font-weight: normal;
  }

  ul {
    list-style-type: none;
    padding: 0;
  }

  li {
    display: inline-block;
    margin: 0 10px;
  }

  a {
    color: #42b983;
  }
  </style>
