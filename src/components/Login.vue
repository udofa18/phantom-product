<template>
    <div class="w-100 background h-100 my-5 py-5">

  <section class="ftco-section">
		<div class="container">
			<div class="row justify-content-center">
				<div class="col-md-6 text-center mb-5">
					<h1 class="heading-section text-light">Welcome Back!!</h1>
				</div>
			</div>
			<div class="row justify-content-center">
				<div class="col-md-6 col-lg-4">
					<div class="login-wrap p-0">
		      	<h3 class="mb-4 text-center text-light">Login here:</h3>
		      	<form action="#" class="signin-form">
		      		<div class="form-group">
		      			<input type="text" class="form-control rounded-5   text-light bg-light bg-opacity-50  hover-change2"  placeholder="Username" required>
		      		</div>
	            <div class="form-group position-relative">
	              <input id="password-field" type="password" class="form-control text-light rounded-5 bg-light bg-opacity-50  hover-change2" placeholder="Password" required>
	              <span toggle="#password-field" class="fa fa-fw fa-eye field-icon toggle-password"></span>
                  <span toggle="#password-field" class="fa fa-fw field-icon toggle-password fa-eye-slash"></span>
	            </div>
	            <div class="form-group">
	            	<button type="submit" class="form-control  text-center rounded-5 btn submit  hvr-bob" style="background-color:#FF8700">Sign In</button>
	            </div>
	            <div class="form-group d-md-flex">
	            	<div class="w-50">
		            	<label class="checkbox-wrap checkbox-primary text-light">Remember Me
									  <input type="checkbox" checked>
									  <span class="checkmark"></span>
									</label>
								</div>
								<div class="w-50 text-md-right">
									<a href="#" style="color: #fff">Forgot Password</a>
								</div>
	            </div>
	          </form>
	          <p class="w-100 text-center text-light">&mdash; Or Sign In With &mdash;</p>
	          <div class="social d-flex text-center gap-2">
	          <button class=" text-center rounded btn form-control  bg-light hover-change  submit " style="transition: all .5s ease-in-out;">	<a href="#"  class="text-dark text-decoration-none hover-text"> Facebook</a></button>
	          <button class="text-center rounded btn form-control bg-light hover-change  submit " style="transition: all .5s ease-in-out;">	<a href="#"  class="text-dark text-decoration-none hover-text">Twitter</a></button>
	          </div>
		      </div>
				</div>
			</div>
		</div>
	</section>
</div>
</template>
<script>
import "@popperjs/core"
export default {
  name: "Login",

};

</script>
<style scoped lang="scss">
.background{
    background:linear-gradient(20deg, rgba(0, 0, 0, 0.825), rgba(68, 71, 2, 0.613)), url(../assets/bg.jpg);
    background-position: center;
    background-repeat: no-repeat;
    background-blend-mode: overlay;
}
.hover-change:hover{
    background-color: black !important;
    // color: white !important;
    .hover-text{
    color: whitesmoke !important;
    }
    
}

    ::placeholder { 
  color: rgba(245, 245, 245, 0.867) !important;
}
.hover-change2:hover{
    background-color: rgba(255, 255, 255, 0.109) !important;
    transition: 0.5s;
    ;

}
.hover-change2:focus{
    box-shadow: none !important;
    background-color: rgba(255, 255, 255, 0.109) !important;
}
.field-icon {
  position: absolute;
  top: 46%;
  right: 15px;
  -webkit-transform: translateY(-50%);
  -ms-transform: translateY(-50%);
  transform: translateY(-50%);
  color: rgba(255, 255, 255, 0.9);
  }
  .form-control {
    height: calc(-1.5em + 5.75rem - 18px) !important;
  }
  .checkbox-wrap input {
  position: absolute;
  opacity: 0;
  cursor: pointer;
  height: 0;
  width: 0;

}
.checkbox-primary {
  color: #fbceb5  !important;
}
.checkbox-wrap {
  display: block;
  position: relative;
  padding-left: 30px;
  margin-bottom: 12px;
  cursor: pointer;
  font-size: 16px;
  font-weight: 500;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;}

  .checkbox-wrap input:checked ~ .checkmark::after {
  display: block;
  content: "\f14a";
  font-family: "FontAwesome";
  }
  .checkmark::after {
  position: absolute;
  font-size: 20px;
  margin-top: -30px;
  margin-left: -30px;
  transition: 0.3s;
  }
</style>