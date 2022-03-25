<template>
    <div class="row justify-content-center">
      <div class="col-xl-10 col-lg-12 col-md-9">
        <div class="card shadow-sm my-5">
          <div class="card-body p-0">
            <div class="row">
              <div class="col-lg-12">
                <div class="login-form">
                  <div class="text-center">
                    <h1 class="h4 text-gray-900 mb-4">Register</h1>
                  </div>
                  <form class="user" @submit.prevent="signup">
               <div class="form-group">
                  
                      <input type="text" class="form-control" id="exampleInputLastName" placeholder="Enter Full Name" v_model="form.name">
                    </div>
                    <div class="form-group">
                      
                      <input type="email" class="form-control" id="exampleInputEmail" aria-describedby="emailHelp"
                        placeholder="Enter Email Address" v_model="form.email">
                    </div>
                    <div class="form-group">
                      
                      <input type="password" class="form-control" id="exampleInputPassword" placeholder="Password" v_model="form.password">
                    </div>
                    <div class="form-group">
                     
                      <input type="password" class="form-control" id="exampleInputPasswordRepeat"
                        placeholder="Confirm Password" v_model="form.comfirm_password">
                    </div>
                    <hr>
                    <div class="d-grid gap-2">
                    <button type="submit" class="btn btn-lg btn-primary btn-block ">Sign Up</button>
                    </div>
                    <hr>
                    <router-link to="/">Alrealy have an Account!</router-link>
                     
                   
                  </form>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    
</template>

<script>

</script>

<style>

</style>

