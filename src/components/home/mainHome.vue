<template>
	<!-- <desktopMenu /> -->
	<!-- <mobileMenu /> -->
	<!-- <navDesktop /> -->
	<section class="main-container">
		<div class="card-container">
			<div class="product-card">
				<img src="https://images.pexels.com/photos/100582/pexels-photo-100582.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="producto" />
				<div class="product-info">
					<div>
						<p>$420,00</p>
						<p>Bike</p>
					</div>
					<figure>
						<img src="@/assets/icons/bt_add_to_cart.svg" alt="" />
					</figure>
				</div>
			</div>

			<div class="product-card">
				<img src="https://images.pexels.com/photos/100582/pexels-photo-100582.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="producto" />
				<div class="product-info">
					<div>
						<p>$420,00</p>
						<p>Bike</p>
					</div>
					<figure>
						<img src="@/assets/icons/bt_add_to_cart.svg" alt="" />
					</figure>
				</div>
			</div>

			<div class="product-card">
				<img src="https://images.pexels.com/photos/100582/pexels-photo-100582.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="producto" />
				<div class="product-info">
					<div>
						<p>$420,00</p>
						<p>Bike</p>
					</div>
					<figure>
						<img src="@/assets/icons/bt_add_to_cart.svg" alt="" />
					</figure>
				</div>
			</div>

			<div class="product-card">
				<img src="https://images.pexels.com/photos/100582/pexels-photo-100582.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="producto" />
				<div class="product-info">
					<div>
						<p>$420,00</p>
						<p>Bike</p>
					</div>
					<figure>
						<img src="@/assets/icons/bt_add_to_cart.svg" alt="" />
					</figure>
				</div>
			</div>

			<div class="product-card">
				<img src="https://images.pexels.com/photos/100582/pexels-photo-100582.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="producto" />
				<div class="product-info">
					<div>
						<p>$420,00</p>
						<p>Bike</p>
					</div>
					<figure>
						<img src="@/assets/icons/bt_add_to_cart.svg" alt="" />
					</figure>
				</div>
			</div>

			<div class="product-card">
				<img src="https://images.pexels.com/photos/100582/pexels-photo-100582.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="producto" />
				<div class="product-info">
					<div>
						<p>$420,00</p>
						<p>Bike</p>
					</div>
					<figure>
						<img src="@/assets/icons/bt_add_to_cart.svg" alt="" />
					</figure>
				</div>
			</div>

			<div class="product-card">
				<img src="https://images.pexels.com/photos/100582/pexels-photo-100582.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="producto" />
				<div class="product-info">
					<div>
						<p>$420,00</p>
						<p>Bike</p>
					</div>
					<figure>
						<img src="@/assets/icons/bt_add_to_cart.svg" alt="" />
					</figure>
				</div>
			</div>

			<div class="product-card">
				<img src="https://images.pexels.com/photos/100582/pexels-photo-100582.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="producto" />
				<div class="product-info">
					<div>
						<p>$420,00</p>
						<p>Bike</p>
					</div>
					<figure>
						<img src="@/assets/icons/bt_add_to_cart.svg" alt="" />
					</figure>
				</div>
			</div>
		</div>
	</section>
</template>

<script setup>
// import desktopMenu from "./desktopMenu.vue";
// import mobileMenu from "./mobileMenu.vue";
// import navDesktop from "./navDesktop.vue";
</script>

<style scoped>
.card-container {
	display: grid;
	grid-template-columns: repeat(auto-fill, 240px);
	gap: 25px;
	place-content: center;
}
.product-card {
	width: 240px;
}
.product-card img {
	width: 240px;
	height: 240px;
	border-radius: 20px;
	object-fit: cover;
}
.product-info {
	display: flex;
	justify-content: space-between;
	align-items: center;
	margin-top: 12px;
}
.product-info div p:nth-child(1) {
	font-weight: bold;
	font-size: var(--md);
	margin-top: 0;
	margin-bottom: 4px;
}
.product-info div p:nth-child(2) {
	font-size: var(--sm);
	margin-top: 0;
	margin-bottom: 0;
	color: var(--very-light-pink);
}
.product-info figure {
	margin: 0;
}
.product-info figure img {
	width: 35px;
	height: 35px;
}
@media (max-width: 640px) {
	.card-container {
		grid-template-columns: repeat(auto-fill, 140px);
	}
	.product-card {
		width: 140px;
	}
	.product-card img {
		width: 140px;
		height: 140px;
	}
}
</style>
