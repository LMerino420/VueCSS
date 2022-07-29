<template>
	<div class="container">
		<div class="container-body">
			<img src="@/assets/logos/logo_yard_sale.svg" alt="Logo" class="logo" />

			<form action="/" class="form">
				<!-- input password -->
				<label for="email" class="label">Email address</label>
				<input type="text" id="email" placeholder="Enter your password" class="input input-email" />
				<!-- input new password -->
				<label for="pwd" class="label">Password</label>
				<input type="password" id="pwd" placeholder="Enter your password" class="input input-pwd" />
				<!-- btn submit -->
				<input type="submit" value="Log in" class="primary-btn login-btn" />
				<a href="/">Forgot my password</a>
			</form>
			<div class="container-btn">
				<button class="secondary-btn singup-btn">Sing Up</button>
			</div>
		</div>
	</div>
</template>

<style scoped>
.form a {
	color: var(--hospital-green);
	font-size: var(--sm);
	text-align: center;
	text-decoration: none;
	margin-bottom: 50px;
}

.secondary-btn {
	background-color: var(--white);
	border-radius: 8px;
	border: 1px solid var(--hospital-green);
	color: var(--hospital-green);
	width: 315px;
	cursor: pointer;
	font-size: var(--md);
	font-weight: bold;
	height: 50px;
}
</style>
