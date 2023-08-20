<template>
    <div>
        <center>
<button type="button" class="btn1" data-bs-toggle="modal" data-bs-target="#exampleModal">
    add a new user
  </button>
  
  <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h1 class="modal-title fs-5" id="exampleModalLabel">add a new user</h1>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
            <form class="form">
                <input placeholder="image" class="input" type="text">
                <input placeholder="name" class="input" type="text">
                <input placeholder="surname" class="input" type="text">
                <input placeholder="gender" class="input" type="text">
                <input placeholder="date of birth" class="input" type="text">
                <input placeholder="contact number" class="input" type="text">
                <input placeholder="email" class="input" type="text">
              </form>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn" data-bs-dismiss="modal">Close</button>
          <button type="button" class="btn">Save changes</button>
        </div>
      </div>
    </div>
  </div>
        </center>
        <table class="table">
            <thead>
                <tr>
                    <th>id</th>
                    <th>image</th>
                    <th>name</th>
                    <th>surname</th>
                    <th>gender</th>
                    <th>date of birth</th>
                    <th>contact number</th>
                    <th>email</th>
                    <th>Action</th>
                </tr>
            </thead>
            <tbody>
                <tr>

                </tr>
            </tbody>
        </table>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.table{
    background-color: #f7f4f1;
}

.btn1{
    border: 2px solid #f7f4f1;
    background-color: #f7f4f1;
    box-shadow: 4px 4px black;
    margin-bottom: 2rem;
  }

  .btn{
    border: 2px solid #f7f4f1;
    background-color: #f7f4f1;
  }
  
  .form input{
    display: flex;
    flex-direction: column;
    width: 50%;
    height: 3rem;
    margin-bottom: 1rem;
    border-radius: 2rem;
  }

  .modal-body{
    background-color: #f7f4f1;
  }
</style>