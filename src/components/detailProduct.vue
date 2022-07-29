<template>
	<aside class="prod-detail">
		<div class="prod-close">
			<img src="@/assets/icons/icon_close.png" alt="Close" />
		</div>
		<img src="https://images.pexels.com/photos/100582/pexels-photo-100582.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="producto" />
		<div class="prod-info">
			<p>$420.00</p>
			<p>Bike</p>
			<p>
				Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quibusdam consectetur cum rem assumenda dolore deserunt veniam maxime tempora quis
				consequatur.
			</p>
			<button class="primary-btn add-to-cart-btn">
				<img src="@/assets/icons/bt_add_to_cart.svg" alt="Add to cart" />
				Add to cart
			</button>
		</div>
	</aside>
</template>

<style scoped>
.prod-detail {
	width: 360px;
	padding-bottom: 24px;
	position: absolute;
	right: 0;
}

.prod-close {
	display: flex;
	justify-content: center;
	align-items: center;
	top: 20px;
	left: 20px;
	position: absolute;
	background-color: var(--white);
	width: 16px;
	height: 16px;
	padding: 8px;
	border-radius: 50%;
	border: 1px solid var(--very-light-pink);
}

.prod-close img:hover {
	cursor: pointer;
}

.prod-detail > img:nth-child(2) {
	width: 100%;
	height: 360px;
	object-fit: cover;
	border-radius: 0 0 20px 20px;
}

.prod-info {
	margin: 24px 24px 0 24px;
}

.prod-info p:nth-child(1) {
	font-weight: bold;
	font-size: var(--md);
	margin-top: 0;
	margin-bottom: 5px;
}

.prod-info p:nth-child(2) {
	color: var(--very-light-pink);
	font-size: var(--md);
	margin-top: 0;
	margin-bottom: 35px;
}

.prod-info p:nth-child(3) {
	color: var(--very-light-pink);
	font-size: var(--sm);
	margin-top: 0;
	margin-bottom: 35px;
}

.add-to-cart-btn {
	display: flex;
	align-items: center;
	justify-content: center;
}

@media (max-width: 640px) {
	.prod-detail {
		width: 100%;
	}
}
</style>
