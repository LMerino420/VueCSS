<template>
	<nav>
		<img src="@/assets/icons/icon_menu.svg" alt="menu" class="menu" />
		<div class="nav-left">
			<img src="@/assets/logos/logo_yard_sale.svg" alt="logo" class="logo-nav" />
			<ul>
				<li>
					<a href="">All</a>
				</li>
				<li>
					<a href="">Clothes</a>
				</li>
				<li>
					<a href="">Electronics</a>
				</li>
				<li>
					<a href="">Furnitures</a>
				</li>
				<li>
					<a href="">Toys</a>
				</li>
				<li>
					<a href="">Others</a>
				</li>
			</ul>
		</div>
		<div class="nav-right">
			<ul>
				<li class="nav-email">merinolev96@gmail.com</li>
				<li class="nav-shopping">
					<img src="@/assets/icons/icon_shopping_cart.svg" alt="Shopping Cart" />
					<div>3</div>
				</li>
			</ul>
		</div>
	</nav>
</template>

<style scoped>
nav {
	display: flex;
	justify-content: space-between;
	padding: 0 25px;
	border-bottom: 1px solid var(--very-light-pink);
	margin-bottom: 20px;
}

.menu {
	display: none;
}

.logo-nav {
	width: 100px;
}

.nav-left {
	display: flex;
}

.nav-left ul {
	margin-left: 12px;
}

.nav-left ul li a,
.nav-right ul li a {
	text-decoration: none;
	color: var(--very-light-pink);
	border: 1px solid var(--white);
	padding: 8px;
	border-radius: 8px;
}

.nav-left ul li a:hover,
.nav-right ul li a:hover {
	text-decoration: none;
	color: var(--hospital-green);
	border: 1px solid var(--hospital-green);
}

.nav-left ul,
.nav-right ul {
	list-style: none;
	padding: 0;
	margin: 0;
	display: flex;
	align-items: center;
	height: 60px;
}

.nav-email {
	color: var(--very-light-pink);
	font-size: var(--sm);
	margin-right: 15px;
}

.nav-shopping {
	position: relative;
}

.nav-shopping div {
	width: 15px;
	height: 15px;
	background-color: var(--hospital-green);
	border-radius: 50%;
	font-size: var(--sm);
	font-weight: bold;
	position: absolute;
	top: -6px;
	right: -3px;
	display: flex;
	justify-content: center;
	align-items: center;
}

@media (max-width: 640px) {
	.menu {
		display: block;
	}
	.nav-left ul {
		display: none;
	}
	.nav-email {
		display: none;
	}
}
</style>
