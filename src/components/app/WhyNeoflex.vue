<template>
	<section class="why-neoflex">
		<h2 class="why-neoflex__title">Почему "Неофлекс"?</h2>

		<div class="why-neoflex__circle"></div>
	</section>
</template>
<script>
	
</script>

<style lang="scss" scoped>

	.why-neoflex {
		min-height: 100vh;
		background: #fff;
		width: 100%;
		display: flex;
		-webkit-flex-direction: column;
		-moz-flex-direction: column;
		-ms-flex-direction: column;
		-o-flex-direction: column;
		flex-direction: column;
		justify-content: center;
		-ms-align-items: center;
		align-items: center;
		padding-top: 1000px;

		&__title {
			font-size: 22px;
			font-weight: 900;
			text-align: center;
			margin-bottom: 25px;
			background: linear-gradient(180deg, #1A024F 0%, #570066 100%), #3C143D;
			-webkit-background-clip: text;
			-moz-background-clip: text;
			background-clip: text;
			-webkit-text-fill-color: transparent;
		}

		&__circle {
			width: 477px;
			height: 432px;
			border-radius: 50%;
			background: linear-gradient(209.65deg, #1A024F 9.76%, #570066 68.02%), #3C143D;

		}
	}

	@media all and (min-width: 992px) {

		.why-neoflex {
			padding-top: 350px;

		}

	}


	@media all and (min-width: 1440px) and (max-width: 1919px) {

		.why-neoflex {
			padding-top: 350px;

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