<script setup="">
	import {Head} from '@vueuse/head'
	import {useRoute} from 'vue-router'

	const {query: x} = useRoute()
</script>

<template>
	<Head>
		<link rel="preconnect" href="https://fonts.googleapis.com">
		<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
		<link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@500&display=swap" rel="stylesheet">
	</Head>
	<div class="bg-zink-100 p-10">
		<div class="text-center">
			<p class="khusus my-7 text-3xl">Undangan Pernikahan</p>
			<p><img src="/menikah.webp" class="mx-auto block" alt="" /></p>
			<p class="khusus my-3 text-xl">{{ x.i }} & {{ x.s }}</p>
			<p class="text-sm mb-3">Akan melangsungkan akad dan resepsi pada</p>
			<p class="font-bold">{{ x.ta }}</p>
		</div>

		<img src="/garis.webp" class="garis" alt="" />

		<div class="text-center text-sm bawah">
			<p>بسم الله الرحمن الرحيم</p>
			<p>السلام عليكم ورحمة الله وبركاته</p>
			<p>Segala puji hanya bagi Allah subhanahu wa taala</p>
			<p class="!mb-10">Dengan mengharap ridho-Nya, kami:</p>
			<p class="khusus !mb-0 text-3xl">{{ x.i }}</p>
			<p>Keluarga {{ x.ki }}</p>
			<p class="khusus">&</p>
			<p class="khusus !mb-0 text-3xl">{{ x.s }}</p>
			<p class="!mb-10">Keluarga {{ x.ks }}</p>
			<p>Berkeinginan mengikuti sunnah Rasulullah shallallahu alaihi wa sallam dalam membentuk keluarga sakinnah, mawaddah, wa rahmah.</p>
		</div>

		<img src="/garis.webp" class="garis" alt="" />

		<div class="text-center">
			<div class="mb-7">
				<p class="khusus mb-1 text-3xl">Akad</p>
				<p class="font-bold mb-1">{{ x.ta }} pukul {{ x.ja }}</p>
				<p class="text-sm">Di {{ x.la }}</p>
			</div>

			<div>
				<p class="khusus text-3xl mb-1">Resepsi</p>
				<p class="font-bold mb-1">{{ x.tr }} pukul {{ x.jr }}</p>
				<p class="text-sm">Di {{ x.lr }}</p>
			</div>
		</div>

		<img src="/garis.webp" class="garis" alt="" />

		<p class="text-center mb-1 font-bold uppercase text-sm">Harapan pengantin pria</p>
		<p class="mb-8 khusus text-2xl text-center">{{ x.hs }}</p>
		<p class="text-center mb-1 font-bold uppercase text-sm">Harapan pengantin wanita</p>
		<p class="khusus text-2xl text-center">{{ x.hi }}</p>

		<img src="/garis.webp" class="garis" alt="" />

		<div class="text-center">
			<p>Atas kehadirannya, kami ucapkan:</p>
			<p class="font-bold">Jazakumullah ahsanal jaza'</p>
			<p>Yang berbahagia:</p>
			<p class="khusus my-7 text-3xl">{{ x.i }} & {{ x.s }}</p>

			<p class="mb-4">
				<a href="https://play.google.com/store/apps/details?id=com.mzaini30.undanganonline" class='text-[.7rem] uppercase underline decoration-wavy font-bold text-slate-500'>Buat</a>
				&times;
				<router-link to="/kredit" class='text-[.7rem] uppercase underline decoration-wavy font-bold text-slate-500'>Kredit gambar</router-link>
			</p>
		</div>
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
	.garis {
		@apply w-[10rem] h-auto mx-auto block my-10
	}
</style>