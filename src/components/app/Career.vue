<template>
	<section class="career">
		<h2 class="career__title">Карьера</h2>

		<div class="crr-block">
				<div class="crr-block__wrapper">
					<p class="crr-block__text"><span class="crr-block__number">26</span> открытых вакансий в Москве, Саратове и Воронеже</p>
					<p class="crr-block__text">«Неофлекс» — это не просто работа, это образ жизни</p>
					<p class="crr-block__join">Присоединяйся!</p>
				</div>
				<a href="#" class="crr-block__button">Все вакансии</a>
		</div>

	</section>
</template>

<script>
	
</script>

<style lang="scss" scoped>

	.career {
		padding-top: 75px;
		margin-bottom: 50px; /*delete */

		&__title {
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
		}
	}

	.crr-block {
		width: 813px;
		height: 555px;
		font-size: 22px;
		font-weight: 900;
		color: #fff;
		line-height: 1.2;
		border-radius: 50%;
		background: url('../../assets/img/bg-career.png') no-repeat;
		margin: 0 -160px;
		overflow: hidden;
		padding: 100px;

			p:first-child {
				width: 100%;
				max-width: 300px;
				margin-bottom: 20px;
			}

			p:nth-child(2) {
				width: 100%;
				max-width: 325px;
				margin-bottom: 35px;
			}

			&__wrapper {
				padding-left: 14%;
				margin: 0 auto 60px;
			}

			&__number {
				font-size: 34px;
			}

			&__join {
				font-size: 28px;
			}

			&__button {
				display: block;
				width: 100%;
				max-width: 250px;
				padding: 15px 0;
				border: 2px solid #fff;
				border-radius: 70px;
				font-size: 18px;
				font-weight: 700;
				text-align: center;
				color: #fff;
				margin-left: 21%;
			}
		}

	@media all and (min-width: 992px) {

		.career {
			padding-top: 160px;
			margin-bottom: 50px; /*delete */
			overflow: hidden;

			&__title {
				font-size: 45px;
			}
		}

	.crr-block {
		width: 100%;
		height: 1200px;
		display: flex;
		flex-direction: column;
		justify-content: center;
		font-size: 42px;
		border-radius: 0;
		background: url('../../assets/img/bg-career1440.png') no-repeat;
		-webkit-background-size: cover;
		background-size: cover;
		/* padding: 100px; */
		margin: 0;

			p:first-child {
				width: 100%;
				max-width: 900px;
				margin-bottom: 40px;
			}

			p:nth-child(2) {
				width: 100%;
				max-width: 850px;
				margin-bottom: 80px;
			}

			&__wrapper {
				margin: 0 auto 100px;
			}

			&__number {
				font-size: 80px;
			}

			&__join {
				font-size: 54px;
			}

			&__button {
				max-width: 390px;
				padding: 20px 0;
				border: 2px solid #fff;
				font-size: 30px;
			}
		}
	}

</style>