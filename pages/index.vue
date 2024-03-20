<template>
	<div class="w-full lg:w-3/4 rounded overflow-hidden shadow-lg">
		<div class="px-6 py-4">
			<div class="text-2xl mb-2 text-center font-bold">
				Hi I'm Faisal Shaikh a Full Stack developer, From Mumbai, India
				🇮🇳.
			</div>
			<div
				class="
					m-2
					p-2
					text-base
					bg-yellow-orange
					rounded-lg
					tracking-wider
				"
			>
				<Row
					>I am a highly motivated and skilled Full Stack Web
					Developer with a passion for solving problems through
					code.</Row
				>
				<Row
					>With a Bachelor's degree in Science with Information
					Technology and 7+ years of experience working on multiple
					web applications, I have honed my expertise in both backend
					and frontend development.</Row
				>
				<Row>
					I have led teams, developed products from scratch, and met
					crucial timelines. I am always eager to take on new
					challenges and contribute to exciting projects.
				</Row>
				<Row
					>If you are looking for a dedicated Tech guy who can lead,
					and deliver innovative solutions, please don't hesitate to
					contact me. Let's connect and discuss how we can work
					together.
				</Row>
			</div>
		</div>
		<div class="px-6 py-4">
			<div
				class="
					m-2
					p-2
					text-base
					bg-yellow-orange
					rounded-lg
					tracking-wider
				"
			>
				<Row
					>Currently working as a
					<strong>Lead Fullstack developer</strong> at
					<a
						class="
							underline
							font-medium
							text-blue-600
							hover:text-gray-900
						"
						href="https://praella.com/"
						target="_blank"
						>Praella
					</a></Row
				>
				<Row
					>I spearheaded the creation of a dynamic web page
					designer/editor from inception to execution, successfully
					integrating it with the leading e-commerce platform Shopify,
					with the potential for seamless integration with other CMS
					platforms. Managed the entire project lifecycle, I navigated
					development challenges to deliver a high-revenue generating
					solution. The product is profitable. Taking leadership roles
					and leading the team in other projects as well.</Row
				>
			</div>
		</div>

		<div class="px-6 py-4">
			<div class="text-2xl mb-2 text-center font-bold">CONTACT</div>
			<div
				class="
					m-2
					p-2
					bg-yellow-orange
					rounded-lg
					text-xl
					tracking-wider
				"
			>
				<Row>
					<template #start>Email:</template>
					<a
						class="
							underline
							font-medium
							text-blue-600
							hover:text-gray-900
						"
						href="mailto:faisalshaikh8433@gmail.com"
						target="_blank"
						>faisalshaikh8433@gmail.com
					</a>
				</Row>
				<Row>
					<template #start>Phone:</template>
					<span class="underline">+918433776085</span>
				</Row>
			</div>
		</div>
	</div>
</template>
<script>
import Row from "@/components/Row.vue";
export default {
	layout: "default",
	components: {
		Row,
	},
};
</script>
