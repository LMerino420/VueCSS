<template>
	<Suspense>
		<template #default>
			<!-- <createPassword /> -->
			<!-- <sendMail /> -->
			<!-- <logIn /> -->
			<!-- <createAccount /> -->
			<!-- <editAccount /> -->
			<!-- <mainHome /> -->
			<!-- <newOrder /> -->
			<myOrders />
		</template>
		<template #fallback>
			<splashHome />
		</template>
	</Suspense>
</template>

<script>
import splashHome from "./components/home/splashHome.vue";
import { defineAsyncComponent } from "vue";

export default {
	components: {
		splashHome,
		// createPassword: defineAsyncComponent(
		// 	() =>
		// 		new Promise((res) => {
		// 			setTimeout(() => {
		// 				res(import("./components/createPassword.vue"));
		// 			}, 2500);
		// 		}),
		// ),

		// sendMail: defineAsyncComponent(
		// 	() =>
		// 		new Promise((res) => {
		// 			setTimeout(() => {
		// 				res(import("./components/sendMail.vue"));
		// 			}, 2500);
		// 		}),
		// ),

		// logIn: defineAsyncComponent(
		// 	() =>
		// 		new Promise((res) => {
		// 			setTimeout(() => {
		// 				res(import("./components/logIn.vue"));
		// 			}, 2000);
		// 		}),
		// ),

		// createAccount: defineAsyncComponent(
		// 	() =>
		// 		new Promise((res) => {
		// 			setTimeout(() => {
		// 				res(import("./components/createAccount.vue"));
		// 			}, 2000);
		// 		}),
		// ),

		// editAccount: defineAsyncComponent(
		// 	() =>
		// 		new Promise((res) => {
		// 			setTimeout(() => {
		// 				res(import("./components/editAccount.vue"));
		// 			}, 2000);
		// 		}),
		// ),

		// mainHome: defineAsyncComponent(
		// 	() =>
		// 		new Promise((res) => {
		// 			setTimeout(() => {
		// 				res(import("./components/home/mainHome.vue"));
		// 			}, 2000);
		// 		}),
		// ),

		// newOrder: defineAsyncComponent(
		// 	() =>
		// 		new Promise((res) => {
		// 			setTimeout(() => {
		// 				res(import("./components/newOrder.vue"));
		// 			}, 2000);
		// 		}),
		// ),

		myOrders: defineAsyncComponent(
			() =>
				new Promise((res) => {
					setTimeout(() => {
						res(import("./components/myOrders.vue"));
					}, 2000);
				}),
		),
	},
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Quicksand:wght@300;500;700&display=swap");

:root {
	--very-light-pink: #c7c7c7;
	--text-input-field: #f7f7f7;
	--hospital-green: #acd9b2;
	--white: #fff;
	--black: #000;
	--sm: 14px;
	--md: 16px;
	--lg: 18px;
}
body {
	font-family: "Quicksand", sans-serif;
	margin: 0;
}
.container {
	width: 100%;
	height: 100vh;
	/* centrar contenido horizontal y vertical */
	display: grid;
	place-items: center;
}
.container-body {
	/* crear sistema de grillas o grid */
	display: grid;
	grid-template-rows: auto 1fr auto;
	width: 400px;
	justify-items: center;
}
.container-btn {
	display: grid;
	width: 400px;
	justify-items: center;
}
.logo {
	width: 150px;
	margin-bottom: 50px;
	justify-self: center;
	display: none;
}

@media (max-width: 640px) {
	.logo {
		display: block;
	}

	.secondary-btn {
		position: absolute;
		bottom: 0;
		margin-bottom: 24px;
	}
}
.form {
	display: flex;
	flex-direction: column;
}
.label {
	font-size: var(--sm);
	font-weight: bold;
	margin-bottom: 4px;
}
.input {
	background-color: var(--text-input-field);
	border: none;
	border-radius: 8px;
	height: 32px;
	font-size: var(--md);
	padding: 8px;
	margin-bottom: 20px;
	width: 300px;
}
.primary-btn {
	background-color: var(--hospital-green);
	border-radius: 8px;
	border: none;
	color: var(--white);
	width: 100%;
	cursor: pointer;
	font-size: var(--md);
	font-weight: bold;
	height: 50px;
}
</style>
