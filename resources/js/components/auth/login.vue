<template>
    <div class="row justify-content-center">
      <div class="col-xl-10 col-lg-12 col-md-9">
        <div class="card shadow-sm my-5">
          <div class="card-body p-0">
            <div class="row">
              <div class="col-lg-12">
                <div class="login-form">
                  <div class="text-center">
                    <h1 class="h4 text-gray-900 mb-4">Login</h1>
                  </div>
                  <form class="user" @submit.prevent="signin">
                    <div class="form-group">
                      <input type="email" class="form-control" id="exampleInputEmail" aria-describedby="emailHelp"
                        placeholder="Enter Email Address" v_model="form.email">
                    </div>
                    <div class="form-group">
                      <input type="password" class="form-control" id="exampleInputPassword" placeholder="Password" v_model="form.password">
                    </div>
                    <div class="form-group">
                      <div class="custom-control custom-checkbox small" style="line-height: 1.5rem;">
                        <input type="checkbox" class="custom-control-input" id="customCheck">
                        <label class="custom-control-label" for="customCheck">Remember
                          Me</label>
                      </div>
                    </div>
                    <div class="form-group">
                      <router-link to="/" class="btn btn-primary btn-block">Login</router-link>
                    </div>
                  </form>
                  <hr>
                  <div class="d-grid gap-2">
                    <button type="submit" class="btn btn-lg btn-primary btn-block ">Sign In</button>
                    </div>
                     <hr>
                      <router-link to="/register">Create an Account!</router-link>
                      <P><router-link to="/forget">Forgot password ?</router-link></P>
                   
                  <div class="text-center">
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  
</template>

<script type="text/javascript">
	
  
</script>

<style type="text/css">

</style>>

</style>
