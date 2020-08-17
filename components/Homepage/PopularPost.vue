<template>
	<section id="popular-post" class="container">
		<h1>Artikel Populer</h1>
		<div class="popular-wrapper container">
			<div class="popular-box">
				<div class="popular-img">
					<img src="~/assets/images/posts/1.jpg" alt="">
				</div>
				<h3 class="post-title">Japan - Improve Your Body and Mind While Escaping</h3>
				<div class="popular-author">
					<div class="img-author-popular">
						<img src="~/assets/images/primary.jpg" alt="">
					</div>
					<div class="author-name">
						<h4>Steve</h4>
						<div class="popular-date">
							21 Agustus 2020
						</div>
					</div>
				</div>
				<p class="popular-preview">
					Far far away from the mountain, behind the back of the sea. Lives a man named kratos.
				</p>
			</div>

			<div class="popular-box">
				<div class="popular-img">
					<img src="~/assets/images/posts/2.jpg" alt="">
				</div>
				<h3 class="post-title">Japan - Improve Your Body and Mind While Escaping</h3>
				<div class="popular-author">
					<div class="img-author-popular">
						<img src="~/assets/images/primary.jpg" alt="">
					</div>
					<div class="author-name">
						<h4>Steve</h4>
						<div class="popular-date">
							21 Agustus 2020
						</div>
					</div>
				</div>
				<p class="popular-preview">
					Far far away from the mountain, behind the back of the sea. Lives a man named kratos.
				</p>
			</div>

			<div class="popular-box">
				<div class="popular-img">
					<img src="~/assets/images/posts/3.jpg" alt="">
				</div>
				<h3 class="post-title">Japan - Improve Your Body and Mind While Escaping</h3>
				<div class="popular-author">
					<div class="img-author-popular">
						<img src="~/assets/images/primary.jpg" alt="">
					</div>
					<div class="author-name">
						<h4>Steve</h4>
						<div class="popular-date">
							21 Agustus 2020
						</div>
					</div>
				</div>
				<p class="popular-preview">
					Far far away from the mountain, behind the back of the sea. Lives a man named kratos.
				</p>
			</div>

			<div class="popular-box">
				<div class="popular-img">
					<img src="~/assets/images/posts/4.jpg" alt="">
				</div>
				<h3 class="post-title">Japan - Improve Your Body and Mind While Escaping</h3>
				<div class="popular-author">
					<div class="img-author-popular">
						<img src="~/assets/images/primary.jpg" alt="">
					</div>
					<div class="author-name">
						<h4>Steve</h4>
						<div class="popular-date">
							21 Agustus 2020
						</div>
					</div>
				</div>
				<p class="popular-preview">
					Far far away from the mountain, behind the back of the sea. Lives a man named kratos.
				</p>
			</div>
		</div>
	</section>    
</template>

<style lang="scss" scoped>
#popular-post{
	width: 100%;
	background: $blue-light;
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: center;
	padding: 6em 0;
	h1{
		font-size: 35px;
		line-height: 43px;
		margin-bottom: 2em;
	}
	.popular-wrapper{
		display: grid;
		grid-gap: 1.5em;
		grid-template-columns: 1fr 1fr 1fr 1fr;
		.popular-box{
			// background:$white;
			.popular-img{
				img{
					width: 100%;
					border-radius: 3px;
				}
			}
			.popular-author{
				margin-top: .5em;
				display: flex;
				.img-author-popular{
					width: 40px;
					border-radius: 50%;
					img{
						width: 100%;
						border-radius: 50%;
					}
				}
				.author-name{
					margin-left: 1em;
					h4{
						font-size: 16px;
						line-height: 21px;
						font-weight: 500;
					}
					.popular-date{
						font-size: 13px;
						line-height: 18px;
						font-family: $poppins;
					}
				}
			}
			.popular-preview{
				margin-top: 1em;
				font-family: $lora;
				font-size: 16px;
				line-height: 24px;
			}
		}
	}
}
</style>
