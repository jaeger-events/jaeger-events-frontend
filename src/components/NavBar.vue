<template>
		<header class="header header--layout-4">
		
		
			<!-- Header Primary -->
			<div class="header__primary">
				<div class="container">
					<div class="header__primary-inner">
		
						<!-- Header Logo -->
						<div class="header-logo">
							<a href=""><img src="../assets/images/jaeger/OvO-sm.png" srcset="../assets/images/jaeger/OvO-sm.png" alt="JaegerEvents" class="header-logo__img"></a>
						</div>
						<!-- Header Logo / End -->
		
						<!-- Main Navigation -->
						<nav class="main-nav">
							<ul class="main-nav__list">
								<li class="active"><router-link to="/">Home</router-link>

								</li>
								<li class=""><router-link to="/">Events</router-link>

								</li>
								<li class=""><router-link to="/">Calendar</router-link>

								</li>
								<li class="">
									<router-link to="/">About</router-link>
								</li>
						
						
							</ul>
						</nav>
						<!-- Main Navigation / End -->
		
						<div class="header__primary-spacer"></div>
		
		
						<!-- Header Info Block -->
						<ul class="info-block info-block--header">
						
						<!-- Account Navigation -->
						<ul class="nav-account">
							<li class="nav-account__item"><a href="">Your Account</a></li>
							<li class="nav-account__item nav-account__item--login"><router-link to="/login">Login</router-link></li>
						</ul>
						<!-- Account Navigation / End -->
						</ul>
						<!-- Header Info Block / End -->
		
					</div>
				</div>
			</div>
			<!-- Header Primary / End -->
		
		</header>
</template>

<script>
export default {
  name: 'NavBar',
 
}
</script>

