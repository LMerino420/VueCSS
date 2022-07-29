<template>
	<div class="container">
		<div class="container-body">
			<img src="@/assets/logos/logo_yard_sale.svg" alt="Logo" class="logo" />
			<h1 class="title">Create new password</h1>
			<p class="subtitle">Enter a new password for your account</p>

			<form action="/" class="form">
				<!-- input password -->
				<label for="pwd" class="label">Password</label>
				<input type="password" id="pwd" placeholder="Enter your password" class="input input-pwd" />
				<!-- input new password -->
				<label for="new-pwd" class="label">New password</label>
				<input type="password" id="new-pwd" placeholder="Enter your password" class="input input-pwd" />
				<!-- btn submit -->
				<input type="submit" value="Confirm" class="primary-btn login-btn" />
			</form>
		</div>
	</div>
</template>

<style scoped>
.title {
	font-size: var(--lg);
	margin-left: 12px;
	text-align: center;
}
.subtitle {
	color: var(--very-light-pink);
	font-size: var(--md);
	font-weight: 300;
	margin-top: 0;
	margin-bottom: 32px;
	text-align: center;
}
.login-btn {
	margin-top: 15px;
	margin-bottom: 30px;
}
</style>
