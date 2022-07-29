<template>
	<div class="container">
		<div class="container-body">
			<!-- <img src="@/assets/logos/logo_yard_sale.svg" alt="Logo" class="logo" /> -->

			<h1 class="title">My account</h1>

			<form action="/" class="form">
				<!-- input name -->
				<label for="name" class="label">Name</label>
				<p class="value">Lev Merino</p>
				<!-- input email -->
				<label for="email" class="label">Email address</label>
				<p class="value">merinolev96@gmail.com</p>
				<!-- input new password -->
				<label for="pwd" class="label">Password</label>
				<p class="value">********</p>
			</form>
			<div class="container-btn">
				<!-- btn submit -->
				<input type="submit" value="Edit" class="secondary-btn" />
			</div>
		</div>
	</div>
</template>

<style scoped>
.title {
	font-size: var(--lg);
	margin-bottom: 30px;
}
.value {
	color: var(--very-light-pink);
	font-size: var(--md);
	margin: 8px 0 32px 0;
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
