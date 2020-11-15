<template>
	<div class="w-full lg:w-3/4 rounded overflow-hidden shadow-lg">
		<div class="px-6 py-4">
			<div class="text-2xl mb-2 text-center font-bold">
				Hi I'm Faisal Shaikh a Full Stack developer, From Mumbai, India
				🇮🇳.
			</div>
			<div
				class="m-2 p-2 text-base bg-yellow-orange rounded-lg tracking-wider"
			>
				<Row>Loves learning new things.</Row>
				<Row>Solving problems through code.</Row>
				<Row>
					Mostly working on backend and works with frontend whenever
					needed.
				</Row>
				<Row
					>I am a Bachelor’s degree holder in science with information
					technology (BscIT).
				</Row>
			</div>
		</div>
		<div class="px-6 py-4">
			<div class="text-center text-2xl mb-2 font-bold">EXPERIENCE</div>
			<div
				class="m-2 p-2 text-base bg-yellow-orange rounded-lg tracking-wider"
			>
				<div
					class="flex flex-wrap justify-between mx-4 my-2 text-xl font-medium"
				>
					<p>FULL STACK DEVELOPER</p>
					<a
						href="https://leadzpipe.com/"
						target="_blank"
						class="underline text-blue-600 hover:text-gray-900"
						>Leadzpipe</a
					>
					<p>July 2020 - Present</p>
				</div>
				<Row>
					Developing Lead Management System using Laravel, Vuejs,
					Javascript, jquery, MySQL, Bootstrap. Introduced Vuejs in
					the project. The system acts as a bridge between the lead
					source and destination.
				</Row>
				<Row>
					Integrating different CRM or destination for auto feeding
					lead data of users lead source to selected CRM or any
					destination using the REST API provided by destination.
				</Row>
				<Row>
					Developed a mail tracking service that tracks delivery,
					open, bounce, etc. using AWS SES (Simple Email Service) and
					SNS (Simple Notification Service).
				</Row>

				<div
					class="flex flex-wrap justify-between mx-4 my-2 text-xl mt-6 font-medium"
				>
					<p>FULL STACK DEVELOPER</p>
					<a
						href="https://neev.io/"
						target="_blank"
						class="underline text-blue-600 hover:text-gray-900"
						>Neev Labs</a
					>
					<p>April 2019 - April 2020</p>
				</div>
				<Row>
					I use to work mainly on two web applications Flowboard and
					Masterchef.
				</Row>
				<Row>
					Flowboard was a talent management system and Masterchef was
					a bakery management system.
				</Row>
				<Row>
					I was the main developer in the Masterchef designed
					database, defined relationships, and handled large datasets.
				</Row>
				<Row>
					Developed some complex forms using Vuejs and provided REST
					API endpoints to the frontend.
				</Row>
				<Row>
					Technologies used Ruby on Rails, Laravel, Vuejs, Javascript,
					Jquery, PostgreSQL, MySQL, Bootstrap, Tailwind CSS, Code
					versioning tools Github & Gitlab.
				</Row>
				<div
					class="flex flex-wrap justify-between mx-4 my-2 text-xl mt-6 font-medium"
				>
					<p>PHP WEB DEVELOPER</p>
					<a
						href="https://www.cepheisys.com/"
						target="_blank"
						class="underline text-blue-600 hover:text-gray-900"
						>Cepheisys Solution (Raj Computers)</a
					>
					<p>July 2016 - April 2019</p>
				</div>
				<Row>
					I was into web development. Use to develop, test, and debug
					custom websites and web applications to serve user needs.
				</Row>
				<Row>
					Involvement in troubleshooting, planning for new projects &
					database design. Client interaction was also involved.
				</Row>
				<Row>
					Technologies used Core PHP, Html, CSS, Bootstrap, MySQL,
					Javascript, Jquery.
				</Row>
			</div>
		</div>

		<div class="px-6 py-4">
			<div class="text-2xl mb-2 text-center font-bold">CONTACT</div>
			<div
				class="m-2 p-2 bg-yellow-orange rounded-lg text-xl tracking-wider"
			>
				<Row>
					<template #start>Email:</template>
					<a
						class="underline font-medium text-blue-600 hover:text-gray-900"
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
