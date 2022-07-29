<template>
	<div class="container">
		<div class="container-body">
			<!-- <img src="@/assets/logos/logo_yard_sale.svg" alt="Logo" class="logo" /> -->

			<h1 class="title">My account</h1>

			<form action="/" class="form" style="height: 100% !important; justify-content: space-between !important">
				<!-- input name -->
				<label for="name" class="label">Name</label>
				<input type="text" id="name" placeholder="Enter your name" class="input input-name" />
				<!-- input email -->
				<label for="email" class="label">Email address</label>
				<input type="text" id="email" placeholder="Enter your e-mail" class="input input-email" />
				<!-- input new password -->
				<label for="pwd" class="label">Password</label>
				<input type="password" id="pwd" placeholder="Enter your password" class="input input-pwd" />

				<!-- btn submit -->
				<input type="submit" value="Create" class="primary-btn" />
			</form>
		</div>
	</div>
</template>

<style scoped>
.title {
	font-size: var(--lg);
	margin-bottom: 30px;
}

.input-name,
.input-email,
.input-pwd {
	margin-bottom: 20px;
}
@media (max-width: 640px) {
	.primary-btn {
		position: absolute;
		width: 315px;
		bottom: 0;
		margin-bottom: 24px;
	}
}
</style>
