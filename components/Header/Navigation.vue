<template>
	<nav>
		<div class="nav-wrapper container">
			<div class="logo">
				<a href="/">Jurnal Malam</a>
			</div>
			<ul class="nav-links">
				<nuxt-link class="nav-link" tag="li" to="/">
					<a>Beranda</a>
				</nuxt-link>
				<nuxt-link class="nav-link" tag="li" to="/post">
					<a>Post</a>
				</nuxt-link>
				<nuxt-link class="nav-link" tag="li" to="/tentang">
					<a>Tentang</a>
				</nuxt-link>
				<nuxt-link class="nav-link" tag="li" to="/kontak">
					<a>Kontak</a>
				</nuxt-link>
			</ul>
		</div>
	</nav>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
nav{
	width: 100%;
	height: 4em;
	.nav-wrapper{
		height: 100%;
		display: flex;
		justify-content: space-between;
		align-items: center;
		.logo{
			font-family: $poppins;
			font-size: 22px;
			line-height: 30px;
			a{
				text-decoration: none;
				color: $black;
				font-weight: 500;
			}
		}
		.nav-links{
			height: 100%;
			display: flex;
			align-items: center;
			list-style: none;
			li{
				margin-left: 3em;
				height: 100%;
				display: flex;
				align-items: center;
				a{
					text-transform: uppercase;
					font-size: 13px;
					line-height: 21px;
					color: $black;
					text-decoration: none;
					font-weight: 700;
					font-family: $poppins;
				}
			}
			.nuxt-link-exact-active{
				position: relative;
			}
			.nuxt-link-exact-active::after{
				content: '';
				position: absolute;
				bottom: 0;
				width: 100%;
				height: 3px;
				background: $primary-color;
			}
			.nav-link a:hover,
			.nav-link a:active,
			.nav-link.nuxt-link-exact-active a{
					color: $primary-color;
			}
		}
	}
}
</style>
