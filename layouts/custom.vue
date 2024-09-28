<template>
	<Html>
			<!-- Head -->
			<Head>
					<Title>Super Sunday: Kulit Lebih Cerah dan Segar Setiap Saat</Title>
					<Meta name="description" :content="`Jadikan Super Sunday sebagai rahasia kulit sehat Anda. Produk ini diperkaya dengan bahan aktif yang menutrisi dan menjaga kelembapan kulit sepanjang hari. Rasakan sensasi kesegaran instan dan kulit yang lebih halus dengan Super Sunday, skincare pilihan untuk kulit yang selalu tampil prima.`" />
					<!-- <Link rel="preload" href="/test.txt" as="script" /> -->
					<!-- <Style type="text/css" :children="styleString" /> -->
			</Head>

			<!-- Header -->
			<nav-header />

			<!-- Content -->
			<slot />

			<!-- Footer -->
			<!-- <the-footer /> -->
	</Html>
</template>

<script>
definePageMeta({
  layout: "custom",
});

import NavHeader from '@/layouts/partials/NavHeader.vue'
import TheFooter from '@/layouts/partials/TheFooter.vue'

export default {
	components: {
		NavHeader,
		TheFooter,
	},
	setup() {
		return {
		}
	},
}
</script>

