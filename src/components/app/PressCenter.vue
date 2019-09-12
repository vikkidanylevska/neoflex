<template>
	<section class="press-center">
		<h2>
			<a href="#" class="press-center__title">Пресс-центр</a>
		</h2>

		<div class="news-wrapper">
			<a href="#" class="press-center__news">Новости</a>
			<a href="#" class="press-center__publications">Публикации</a>
		</div>

	</section>
</template>

<script>
	import carousel from 'vue-owl-carousel'

	export default {
	    components: { carousel },
	}
</script>

<style lang="scss" scoped>

	.press-center__title h2{
		text-decoration: underline;
	}

	.press-center {
		padding-top: 80px;
		display: flex;
		flex-direction: column;
		-ms-align-items: center;
		align-items: center;

		&__title {
			display: inline-block;
			font-size: 22px;
			font-weight: 900;
			text-align: center;
			margin-bottom: 25px;
			background: -webkit-linear-gradient(180deg, #1A024F 0%, #570066 100%), #3C143D;
			background: -o-linear-gradient(180deg, #1A024F 0%, #570066 100%), #3C143D;
			background: linear-gradient(180deg, #1A024F 0%, #570066 100%), #3C143D;
			-webkit-background-clip: text;
			-moz-background-clip: text;
			background-clip: text;
			-webkit-text-fill-color: transparent;
			border-bottom: 2px solid transparent;

			&:hover {
				border-bottom: 2px solid #570066;
			}
		}

		&__circle {
			width: 130%;
			min-width: 477px;
			height: 432px;
			border-radius: 50%;
			background: linear-gradient(209.65deg, #1A024F 9.76%, #570066 68.02%), #3C143D no-repeat;
			text-align: center;
			overflow: hidden;
			margin: 0 -40px;
		}

		
	}

	@media all and (min-width: 992px) {

		.why-neoflex {

		}

	}


	@media all and (min-width: 1440px) and (max-width: 1919px) {

		.why-neoflex {

			&__title {
			font-size: 45px;
			margin-bottom: 25px;
			}
		}

	}

	/* @media all and (min-width: 1920px) {

		.why-neoflex {
			padding-top: 400px;

			&__title {
			font-size: 60px;
			margin-bottom: 25px;
			}
		}

	}
 */




</style>