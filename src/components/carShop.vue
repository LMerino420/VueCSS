<template>
	<aside class="prod-detail">
		<div class="title-cont">
			<img src="@/assets/icons/flechita.svg" alt="arrow" />
			<p class="title-shop">Shopping Car</p>
		</div>
		<div class="shopping-cart">
			<figure>
				<img src="https://images.pexels.com/photos/100582/pexels-photo-100582.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Bike" />
			</figure>
			<p>Bike BMX</p>
			<p>$250.00</p>
			<img src="@/assets/icons/icon_close.png" alt="" />
		</div>
		<div class="shopping-cart">
			<figure>
				<img src="https://images.pexels.com/photos/100582/pexels-photo-100582.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Bike" />
			</figure>
			<p>Bike BMX</p>
			<p>$250.00</p>
			<img src="@/assets/icons/icon_close.png" alt="" />
		</div>
		<div class="shopping-cart">
			<figure>
				<img src="https://images.pexels.com/photos/100582/pexels-photo-100582.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Bike" />
			</figure>
			<p>Bike BMX</p>
			<p>$250.00</p>
			<img src="@/assets/icons/icon_close.png" alt="" />
		</div>
		<div class="order">
			<p>
				<span>Total</span>
			</p>
			<p>$420.10</p>
		</div>
		<button class="primary-btn">Checkout</button>
	</aside>
</template>

<style scoped>
.prod-detail {
	width: 360px;
	padding: 24px;
	position: absolute;
	right: 0;
	box-sizing: border-box;
}
.title-cont {
	display: flex;
}
.title-cont img {
	transform: rotate(180deg);
	margin-right: 15px;
}
.title-shop {
	font-size: var(--lg);
	font-weight: bold;
}
.order {
	display: grid;
	grid-template-columns: auto 1fr;
	gap: 16px;
	align-items: center;
	background-color: var(--text-input-field);
	margin-bottom: 25px;
	border-radius: 8px;
	padding: 0 25px;
}
.order p:nth-child(1) {
	display: flex;
	flex-direction: column;
}
.order p span:nth-child(1) {
	font-size: var(--md);
	font-weight: bold;
}
.order p:nth-child(2) {
	text-align: end;
	font-weight: bold;
}
.shopping-cart {
	display: grid;
	grid-template-columns: auto 1fr auto auto;
	gap: 16px;
	margin-bottom: 25px;
	align-items: center;
}
.shopping-cart figure {
	margin: 0;
}
.shopping-cart figure img {
	width: 70px;
	height: 70px;
	border-radius: 20px;
	object-fit: cover;
}
.shopping-cart p:nth-child(2) {
	color: var(--very-light-pink);
}
.shopping-cart p:nth-child(3) {
	font-size: var(--md);
	font-weight: bold;
}
@media (max-width: 640px) {
	.prod-detail {
		width: 100%;
	}
}
</style>
