<template>
	<div class="container">
		<div class="container-body">
			<img src="@/assets/logos/logo_yard_sale.svg" alt="Logo" class="logo" />
			<h1 class="title">Email has been sent!</h1>
			<p class="subtitle">Please check your inbox for instructions on how to reset the password</p>
			<div class="email-img">
				<img src="@/assets/icons/email.svg" alt="email" />
			</div>
			<button class="primary-btn sendMail-btn">Login</button>
			<p class="resend">
				<span>Didn't receive the email?</span>
				<a href="/">Resend</a>
			</p>
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
.email-img {
	width: 132px;
	height: 132px;
	border-radius: 50%;
	background-color: var(--text-input-field);
	display: flex;
	justify-content: center;
	align-items: center;
	margin-bottom: 25px;
}
.email-img img {
	width: 70px;
}
.resend {
	font-size: var(--sm);
}
.resend span {
	color: var(--very-light-pink);
}
.resend a {
	color: var(--hospital-green);
}

.sendMail-btn {
	margin-top: 15px;
	margin-bottom: 30px;
	width: 300px;
}
</style>
