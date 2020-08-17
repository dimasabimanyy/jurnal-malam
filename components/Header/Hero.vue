<template>
	<section id="hero">
		<div class="hero-wrapper container">
			<div class="hero-box">
				<div class="top-hero-box">
					<div class="author-image-hero">
						<img src="~/assets/images/primary.jpg" alt="Dimas Abimanyu Foto">
					</div>
					<div class="author-name-wrap">
						<h4 class="author-name-hero">Dimas Abimanyu</h4>
						<div class="publish-date-hero">14 Agustus 2020</div>
					</div>
				</div>
				<h1 class="hero-title">
					Cool and Beautiful Abandoned Railway in South America
				</h1>
				<a href="">
					<button>Read More</button>
				</a>
			</div>
		</div>
	</section>    
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
	#hero{
		width: 100%;
		height: 92vh;
		background: url('../../assets/images/hero-bg.jpg') no-repeat;
		background-size: cover;
		background-position: center center;
		display: flex;
		align-items: center;
		.hero-wrapper{
			.hero-box{
			width: 500px;
			background: $white;
			padding: 3em 3em;
			border-radius: 5px;
			.top-hero-box{
				margin-bottom: .8em;
				display: flex;
				.author-image-hero{
					width: 50px;
					border-radius: 25px;
					img{
						border-radius: 25px;
						width: 100%;
					}
				}
				.author-name-wrap{
					margin-left: 1em;
					// background: maroon;
					display: flex;
					flex-direction: column;
					// align-items: center;
					justify-content: center;
					.author-name-hero{
						font-family: $poppins;
						font-size: 15px;
					}
					.publish-date-hero{
						color: $gray;
						font-family: $poppins;
						font-size: 13px;
						font-weight: 500;
					}
				}
			}
			.hero-title{
				font-family: $poppins;
				margin-bottom: .8em;
				font-size: 20px;
				line-height: 30px;
			}
			a{
				button{
					padding: .6em 2em;
					background: $primary-color;
					border: none;
					font-weight: 500;
					color: $white;
					// text-transform: uppercase;
					font-family: $poppins;
					font-size: 13px;
					letter-spacing: 1px;
					border-radius: 3px;
				}
				}
			}
		}
	}
</style>
