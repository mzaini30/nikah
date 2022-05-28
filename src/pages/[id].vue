<script setup="">
	import {Head} from '@vueuse/head'
</script>

<template>
	<Head>
		<link rel="preconnect" href="https://fonts.googleapis.com">
		<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
		<link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@500&display=swap" rel="stylesheet">
	</Head>
	<div class="bg-zink-100 p-10">
		<div class="text-center mb-10">
			<p class="khusus my-7 text-3xl">Undangan Pernikahan</p>
			<p><img src="/menikah.webp" alt="" /></p>
			<p class="khusus my-3 text-xl">Istri & Suami</p>
			<p class="text-sm mb-3">Akan melangsungkan akad dan resepsi pada</p>
			<p class="font-bold">Minggu, 1 Januari 2021</p>
		</div>

		<div class="text-center text-sm bawah mb-10">
			<p>بسم الله الرحمن الرحيم</p>
			<p>السلام عليكم ورحمة الله وبركاته</p>
			<p>Segala puji hanya bagi Allah subhanahu wa taala</p>
			<p>Dengan mengharap ridho-Nya, kami:</p>
			<p>Istri</p>
			<p>Keluarga Pak Badru</p>
			<p>&</p>
			<p>Suami</p>
			<p>Keluarga Pak Hasan</p>
			<p>Berkeinginan mengikuti sunnah Rasulullah shallallahu alaihi wa sallam dalam membentuk keluarga sakinnah, mawaddah, wa rahmah.</p>
		</div>

		<p>Akad</p>
		<p>Minggu, 1 Januari 2021 pukul 08.00</p>
		<p>Masjid Raya Balikpapan</p>

		<p>Resepsi</p>
		<p>Senin, 2 Januari 2021 pukul 10.00 hingga selesai</p>
		<p>Rumah mempelai wanita</p>

		<p>Perjalanan cinta kami</p>
		<p>31 Desember 2020</p>
		<p>Siap nikah</p>
		<p>28 Desember 2020</p>
		<p>Bertemu di kafe</p>

		<p>Harapan pengantin pria</p>
		<p>Semoga dia menjadi bidadari</p>
		<p>Harapan pengantin wanita</p>
		<p>Semoga jadi malaikatku</p>

		<p>Atas kehadirannya, kami ucapkan:</p>
		<p>Jazakumullah ahsanal jaza'</p>
		<p>Yang berbahagia:</p>
		<p>Istri & Suami</p>
	</div>

	<img src="/bungaAtas.webp" class="fixed top-0 left-0 w-[10rem] h-auto" alt="" />
	<img src="/bungaBawah.webp" class="fixed w-[10rem] h-auto bottom-0 right-0" alt="" />
</template>

<style scoped="">
	.khusus {
		font-family: 'Dancing Script', cursive;
	}
	.bawah p {
		@apply mb-3
	}
</style>