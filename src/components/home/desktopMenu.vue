<template>
	<div class="desktop-menu">
		<ul>
			<li>
				<a href="" class="title-menu">My orders</a>
			</li>
			<li>
				<a href="">My account</a>
			</li>
			<li>
				<a href="">Sing out</a>
			</li>
		</ul>
	</div>
</template>

<style scoped>
.desktop-menu {
	width: 100px;
	height: auto;
	border: 1px solid var(--very-light-pink);
	border-radius: 6px;
	padding: 20px 20px 0 20px;
}
.desktop-menu ul {
	list-style: none;
	padding: 0;
	margin: 0;
}
.desktop-menu ul li {
	text-align: end;
	font-weight: bold;
}
.desktop-menu ul li:last-child {
	padding-top: 20px;
	border-top: 1px solid var(--very-light-pink);
	color: var(--hospital-green);
	font-weight: normal;
}
.desktop-menu ul li a {
	color: var(--black);
	text-decoration: none;
	display: inline-block;
	margin-bottom: 15px;
	/* font-size: var(--sm); */
}
.desktop-menu ul li:last-child a {
	color: var(--hospital-green);
	font-size: var(--sm);
}
</style>
