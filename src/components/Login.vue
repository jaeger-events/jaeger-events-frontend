<template>
						<!-- Login -->
						<div class="card">
							<div class="card__header">
								<h4>Login to your Account</h4>
							</div>
							<div class="card__content">
		
								<!-- Login Form -->
								<form action="#">
									<div class="form-group">
										<label for="login-name">Your Email</label>
										<input type="email" name="login-name" id="login-name" class="form-control" placeholder="Enter your email address...">
									</div>
									<div class="form-group">
										<label for="login-password">Your Password</label>
										<input type="password" name="login-password" id="login-password" class="form-control" placeholder="Enter your password...">
									</div>
									<div class="form-group form-group--password-forgot">
										<label class="checkbox checkbox-inline">
											<input type="checkbox" id="inlineCheckbox1" value="option1" checked> Remember Me
											<span class="checkbox-indicator"></span>
										</label>
										<span class="password-reminder">Forgot your password? <a href="#">Click Here</a></span>
									</div>
									<div class="form-group form-group--sm">
										<a href="_esports_shop-account.html" class="btn btn-primary-inverse btn-lg btn-block">Sign in to your account</a>
									</div>
									<div class="row">
										<div class="col-md-6">
											<button class="btn btn-facebook btn-icon btn-block"><i class="fa fa-facebook"></i> Sign In via Facebook</button>
										</div>
										<div class="col-md-6">
											<button class="btn btn-twitter btn-icon btn-block"><i class="fa fa-twitter"></i> Sign in via Twitter</button>
										</div>
									</div>
								</form>
								<!-- Login Form / End -->
		
							</div>
						</div>
						<!-- Login / End -->
</template>
<script>
export default {
  name: 'Login',
 
}
</script>