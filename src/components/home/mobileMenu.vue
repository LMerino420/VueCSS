<template>
	<div class="mobile-menu">
		<ul>
			<li>
				<a href="">CATEGORIES</a>
			</li>
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

		<ul>
			<li>
				<a href="">My orders</a>
			</li>
			<li>
				<a href="">My account</a>
			</li>
		</ul>

		<ul>
			<li>
				<a href="" class="email">merinolev96@gmail.com</a>
			</li>
			<li>
				<a href="" class="sing-out">Sing out</a>
			</li>
		</ul>
	</div>
</template>

<style scoped>
.mobile-menu {
	padding: 20px;
}
.mobile-menu a {
	text-decoration: none;
	color: var(--black);
	font-weight: bold;
	/* margin-bottom: 20px; */
}
.mobile-menu ul {
	padding: 0;
	margin: 20px 0 0;
	list-style: none;
}
.mobile-menu ul:nth-child(1) {
	border-bottom: 1px solid var(--very-light-pink);
}
.mobile-menu ul:nth-child(3) {
	position: absolute;
	bottom: 0;
}
.mobile-menu ul li {
	margin-bottom: 20px;
}
.email {
	font-size: var(--sm);
	font-weight: 300 !important;
}
.sing-out {
	font-size: var(--sm);
	color: var(--hospital-green) !important;
}
</style>
