<template>
	<header
		id="nav"
		class="lg:px-16 px-6 bg-black flex flex-wrap items-center lg:py-0 py-2 shadow text-white"
	>
		<div class="flex flex-wrap items-center flex-1 font-bold font-mono">
			<nuxt-link to="/">
				<img
					class="rounded-full w-10 h-10 border-2 border-transparent hover:border-blue-200"
					src="~/assets/images/faisal_shaikh.jpg"
					alt="Faisal Shaikh"
				/>
			</nuxt-link>
			<nuxt-link
				to="/"
				class="hidden md:block ml-2 text-white text-xl hover:text-blue-200"
				>FAISAL SHAIKH</nuxt-link
			>
		</div>

		<button @click="toggle" class="pointer-cursor lg:hidden block">
			<svg
				class="fill-current"
				xmlns="http://www.w3.org/2000/svg"
				width="20"
				height="20"
				viewBox="0 0 20 20"
			>
				<title>menu</title>
				<path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
			</svg>
		</button>

		<div
			:class="isOpen ? 'block' : 'hidden'"
			class="lg:flex lg:items-center lg:w-auto w-full"
			id="menu"
		>
			<nav class="font-mono">
				<ul
					class="lg:flex items-center justify-between text-base text-gray-700 pt-4 lg:pt-0"
				>
					<li>
						<nuxt-link
							class="lg:p-4 py-3 px-0 block border-b-2 border-transparent hover:border-indigo-400 text-white"
							to="/projects"
							>Projects & Blogs</nuxt-link
						>
					</li>
					<li>
						<a
							class="lg:p-4 py-3 px-0 block border-b-2 border-transparent hover:border-indigo-400 text-white"
							href="https://docs.google.com/document/d/1lq6d0zT-mwTnAfYLOaWZZY-WrRch6-P9Rza9hkd6nRI/edit#heading=h.y7d3xdxnr44m"
							target="_blank"
							>Resume</a
						>
					</li>
				</ul>
			</nav>
		</div>
	</header>
</template>

<script>
export default {
	data: function () {
		return {
			isOpen: false,
		};
	},
	methods: {
		toggle() {
			this.isOpen = !this.isOpen;
		},
	},
};
</script>

<style lang="scss" scoped></style>
