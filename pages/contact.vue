<template>
	<div>
		<app-title>{{ title }}</app-title>
		<div class="max-w-7xl mx-auto py-16 px-4 sm:py-24 sm:px-6 lg:px-8">
			<div class="relative bg-white shadow-xl border">
				<h2 class="sr-only">{{ title }}</h2>

				<div class="grid grid-cols-1 lg:grid-cols-3">
					<div
						class="relative overflow-hidden py-10 px-6 bg-ds-blue sm:px-10 xl:p-12"
					>
						<div
							class="absolute inset-0 pointer-events-none sm:hidden"
							aria-hidden="true"
						>
							<svg
								class="absolute inset-0 w-full h-full"
								width="343"
								height="388"
								viewBox="0 0 343 388"
								fill="none"
								preserveAspectRatio="xMidYMid slice"
								xmlns="http://www.w3.org/2000/svg"
							>
								<path
									d="M-99 461.107L608.107-246l707.103 707.107-707.103 707.103L-99 461.107z"
									fill="url(#linear1)"
									fill-opacity=".1"
								/>
								<defs>
									<linearGradient
										id="linear1"
										x1="254.553"
										y1="107.554"
										x2="961.66"
										y2="814.66"
										gradientUnits="userSpaceOnUse"
									>
										<stop stop-color="#fff"></stop>
										<stop offset="1" stop-color="#fff" stop-opacity="0"></stop>
									</linearGradient>
								</defs>
							</svg>
						</div>
						<div
							class="hidden absolute top-0 right-0 bottom-0 w-1/2 pointer-events-none sm:block lg:hidden"
							aria-hidden="true"
						>
							<svg
								class="absolute inset-0 w-full h-full"
								width="359"
								height="339"
								viewBox="0 0 359 339"
								fill="none"
								preserveAspectRatio="xMidYMid slice"
								xmlns="http://www.w3.org/2000/svg"
							>
								<path
									d="M-161 382.107L546.107-325l707.103 707.107-707.103 707.103L-161 382.107z"
									fill="url(#linear2)"
									fill-opacity=".1"
								/>
								<defs>
									<linearGradient
										id="linear2"
										x1="192.553"
										y1="28.553"
										x2="899.66"
										y2="735.66"
										gradientUnits="userSpaceOnUse"
									>
										<stop stop-color="#fff"></stop>
										<stop offset="1" stop-color="#fff" stop-opacity="0"></stop>
									</linearGradient>
								</defs>
							</svg>
						</div>
						<div
							class="hidden absolute top-0 right-0 bottom-0 w-1/2 pointer-events-none lg:block"
							aria-hidden="true"
						>
							<svg
								class="absolute inset-0 w-full h-full"
								width="160"
								height="678"
								viewBox="0 0 160 678"
								fill="none"
								preserveAspectRatio="xMidYMid slice"
								xmlns="http://www.w3.org/2000/svg"
							>
								<path
									d="M-161 679.107L546.107-28l707.103 707.107-707.103 707.103L-161 679.107z"
									fill="url(#linear3)"
									fill-opacity=".1"
								/>
								<defs>
									<linearGradient
										id="linear3"
										x1="192.553"
										y1="325.553"
										x2="899.66"
										y2="1032.66"
										gradientUnits="userSpaceOnUse"
									>
										<stop stop-color="#fff"></stop>
										<stop offset="1" stop-color="#fff" stop-opacity="0"></stop>
									</linearGradient>
								</defs>
							</svg>
						</div>
						<h3 class="text-lg font-medium text-white">Contact information</h3>
						<p class="mt-6 text-base text-ds-smokewhite max-w-3xl">
							Hey there. If you are looking to reach out to me you can use this
							form although in general you will probably reach me quicker on
							Twitter or LinkedIn.
						</p>
						<ul role="list" class="mt-8 flex flex-col space-y-4">
							<li>
								<a
									class="text-ds-smokewhite hover:text-indigo-100"
									href="tel:+351930538431"
								>
									<span class="sr-only">Phone</span>
									<div class="flex">
										<svg
											class="flex-shrink-0 w-6 h-6 text-indigo-200"
											xmlns="http://www.w3.org/2000/svg"
											fill="none"
											viewBox="0 0 24 24"
											stroke="currentColor"
											aria-hidden="true"
										>
											<path
												stroke-linecap="round"
												stroke-linejoin="round"
												stroke-width="2"
												d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"
											/>
										</svg>
										<span class="ml-3">+351 (930538431)</span>
									</div>
								</a>
							</li>
							<li>
								<a
									class="text-ds-smokewhite hover:text-indigo-100"
									href="mailto:damisparks@outlook.com"
									rel="noopener noreferrer"
								>
									<span class="sr-only">Email</span>
									<div class="flex">
										<svg
											xmlns="http://www.w3.org/2000/svg"
											class="h-6 w-6"
											fill="none"
											viewBox="0 0 24 24"
											stroke="currentColor"
										>
											<path
												stroke-linecap="round"
												stroke-linejoin="round"
												stroke-width="2"
												d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
											/>
										</svg>
										<span class="ml-3">damisparks@outlook.com</span>
									</div>
								</a>
							</li>
							<li>
								<a
									class="text-ds-smokewhite hover:text-indigo-100"
									href="//twitter.com/DamiSparks"
									rel="noopener noreferrer"
								>
									<span class="sr-only">Twitter</span>
									<div class="flex">
										<svg
											width="24"
											height="24"
											viewBox="0 0 24 24"
											fill="none"
											xmlns="http://www.w3.org/2000/svg"
											class="w-6 h-6"
											aria-hidden="true"
										>
											<path
												d="M7.548 22.501c9.056 0 14.01-7.503 14.01-14.01 0-.213 0-.425-.015-.636A10.02 10.02 0 0024 5.305a9.828 9.828 0 01-2.828.776 4.94 4.94 0 002.165-2.724 9.867 9.867 0 01-3.127 1.195 4.929 4.929 0 00-8.391 4.491A13.98 13.98 0 011.67 3.9a4.928 4.928 0 001.525 6.573A4.887 4.887 0 01.96 9.855v.063a4.926 4.926 0 003.95 4.827 4.917 4.917 0 01-2.223.084 4.93 4.93 0 004.6 3.42A9.88 9.88 0 010 20.289a13.941 13.941 0 007.548 2.209"
												fill="currentColor"
											/>
										</svg>
										<span class="ml-3">@damisparks</span>
									</div>
								</a>
							</li>
						</ul>
					</div>

					<!-- Contact form -->
					<div class="py-10 px-6 sm:px-10 lg:col-span-2 xl:p-12">
						<h3 class="text-lg font-medium text-ds-blue">Drop me a message</h3>
						<form
							id="contact_form"
							name="contact"
							method="POST"
							data-netlify="true"
							action="/thank-you/"
							netlify-honeypot="bot-field"
							class="mt-6 grid grid-cols-1 gap-y-6 sm:grid-cols-2 sm:gap-x-8"
						>
							<input type="hidden" name="form-name" value="contact" />

							<!--  spam prevention starts -->
							<p class="hidden">
								<label>
									Don’t fill this out if you’re human:
									<input name="bot-field" />
								</label>
							</p>
							<!--  spam prevention ends -->

							<div>
								<label
									for="your-name"
									class="block text-sm font-medium text-gray-900"
									>Your name</label
								>
								<div class="mt-1">
									<input
										id="your-name"
										required
										type="text"
										name="your-name"
										placeholder="Your name"
										autocomplete="given-name"
										class="py-3 px-4 block w-full shadow-sm text-gray-900 focus:ring-ds-blue border border-ds-gray rounded"
									/>
								</div>
							</div>
							<div>
								<label
									for="email"
									class="block text-sm font-medium text-gray-900"
									>Email</label
								>
								<div class="mt-1">
									<input
										id="email"
										required
										name="email"
										type="email"
										autocomplete="email"
										placeholder="Your email address"
										class="py-3 px-4 block w-full shadow-sm text-gray-900 focus:ring-ds-blue border border-ds-gray rounded"
									/>
								</div>
							</div>

							<div class="sm:col-span-2">
								<label
									for="subject"
									class="block text-sm font-medium text-gray-900"
									>Subject</label
								>
								<div class="mt-1">
									<input
										id="subject"
										required
										type="text"
										name="subject"
										class="py-3 px-4 block w-full shadow-sm text-gray-900 focus:ring-ds-blue border border-ds-gray rounded"
									/>
								</div>
							</div>
							<div class="sm:col-span-2">
								<div class="flex justify-between">
									<label
										for="message"
										class="block text-sm font-medium text-gray-900"
										>A message to me</label
									>
									<span id="message-max" class="text-sm text-gray-500"
										>Max. 500 characters</span
									>
								</div>
								<div class="mt-1">
									<textarea
										id="message"
										required
										name="message"
										rows="4"
										class="py-3 px-4 block w-full shadow-sm text-gray-900 focus:ring-ds-blue border border-ds-gray rounded"
										aria-describedby="message-max"
										placeholder="Write a message me"
									></textarea>
								</div>
							</div>
							<div class="sm:col-span-2 sm:flex sm:justify-end">
								<button
									type="submit"
									class="mt-2 w-full inline-flex items-center justify-center px-6 py-2 border border-transparent rounded shadow-sm text-base font-bold text-ds-smokewhite bg-ds-blue hover:bg-ds-teal hover:text-ds-blue focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-ds-blue sm:w-auto"
								>
									Send
								</button>
							</div>
						</form>
					</div>
				</div>
			</div>
		</div>
	</div>
	<!-- contact template ends -->
</template>

<script>
import AppTitle from '~/components/AppTitle.vue'
export default {
	name: 'ContactPage',
	components: { AppTitle },
	data: () => {
		return {
			title: 'Contact Me',
			description:
				'Contact DamiSparks using the form or via Twitter or LinkedIn',
		}
	},
	head() {
		return {
			title: `${this.title} - Dami Sparks`,
			meta: [
				{
					hid: 'description',
					name: 'description',
					content: this.description,
				},
			],
			link: [
				{
					hid: 'canonical',
					rel: 'canonical',
					href: `https://damisparks.com/contact`,
				},
			],
		}
	},
}
</script>
