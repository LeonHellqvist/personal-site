<script>
</script>

<svelte:head>
	<title>Leon Hellqvist</title>
	<html lang="en" />
</svelte:head>

<nav class="bg-white border-gray-200 px-2 sm:px-4 py-2.5">
	<div class="container flex flex-wrap justify-between items-center mx-auto">
		<span class="self-center text-xl font-semibold whitespace-nowrap">Leon Hellqvist</span>
		<div class="flex md:order-2">
			<button
				type="button"
				class="text-white bg-red-600 hover:bg-red-700 focus:ring-4 focus:outline-none focus:ring-red-200 font-medium rounded-lg text-sm px-5 py-2.5 text-center mr-3 md:mr-0"
				>Contact</button
			>
			<button
				data-collapse-toggle="mobile-menu-4"
				type="button"
				class="inline-flex items-center p-2 text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200"
				aria-controls="mobile-menu-4"
				aria-expanded="false"
			>
				<span class="sr-only">Open main menu</span>
				<svg
					class="w-6 h-6"
					aria-hidden="true"
					fill="currentColor"
					viewBox="0 0 20 20"
					xmlns="http://www.w3.org/2000/svg"
					><path
						fill-rule="evenodd"
						d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z"
						clip-rule="evenodd"
					/></svg
				>
				<svg
					class="hidden w-6 h-6"
					aria-hidden="true"
					fill="currentColor"
					viewBox="0 0 20 20"
					xmlns="http://www.w3.org/2000/svg"
					><path
						fill-rule="evenodd"
						d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
						clip-rule="evenodd"
					/></svg
				>
			</button>
		</div>
		<div
			class="hidden justify-between items-center w-full md:flex md:w-auto md:order-1"
			id="mobile-menu-4"
		>
			<ul class="flex flex-col mt-4 md:flex-row md:space-x-8 md:mt-0 md:text-sm md:font-medium">
				<li>
					<a
						href="#"
						class="block py-2 pr-4 pl-3 text-white bg-red-500 rounded md:bg-transparent md:text-red-500 md:p-0"
						aria-current="page">Home</a
					>
				</li>
				<li>
					<a
						href="#"
						class="block py-2 pr-4 pl-3 text-gray-700 border-b border-gray-100 hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-red-500 md:p-0"
						>Competence</a
					>
				</li>
				<li>
					<a
						href="#"
						class="block py-2 pr-4 pl-3 text-gray-700 border-b border-gray-100 hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-red-500 md:p-0"
						>Experience</a
					>
				</li>
				<li>
					<a
						href="#"
						class="block py-2 pr-4 pl-3 text-gray-700 border-b border-gray-100 hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-red-500 md:p-0"
						>Contact</a
					>
				</li>
			</ul>
		</div>
	</div>
</nav>
<!-- End of Navbar -->
<section class="screen-h">
	<div class="pt-10 pb-24 lg:ml-16 lg:mt-16 xl:ml-40 xl:mt-40">
		<h1 class="font-mono text-center lg:text-left text-5xl lg:text-8xl xl:text-9xl text-red-500">
			Leon Hellqvist
		</h1>
		<p class="font-mono text-center lg:text-left text-4xl lg:text-4xl text-red-200 ml-3">
			Full-stack developer
		</p>
		<p class="font-mono text-center lg:text-left text-2xl lg:text-3xl text-red-200 ml-3">
			Currently 17 years old
		</p>
	</div>
	<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"
		><path
			fill="#EF4444"
			fill-opacity="1"
			d="M0,224L48,218.7C96,213,192,203,288,208C384,213,480,235,576,224C672,213,768,171,864,128C960,85,1056,43,1152,26.7C1248,11,1344,21,1392,26.7L1440,32L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"
		/></svg
	>
</section>
<section class="bg-white mt-[-1px]">
	<div class="bg-red-500">
		<h2
			class="text-center font-mono font-semibold text-4xl xl:text-5xl text-white xl:mt-[-50px] pb-10"
		>
			Competence
		</h2>
		<div
			class="container lg:w-5/6 xl:w-4/6 flex flex-wrap justify-center items-center mx-auto"
		>
			<div
				class="ml-5 mr-5 mb-6 lg:w-1/4 xl:w-sm xl:mb-0 block p-6 w-sm bg-white rounded-lg border border-gray-200 shadow-md hover:bg-gray-100"
			>
				<h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Programming languages</h5>
				<ol class="list-disc pl-4 font-normal text-gray-700">
					<li>TypeScript</li>
					<li>JavaScript</li>
					<li>Python</li>
					<li>C</li>
					<li>C#</li>
					<li>Java</li>
					<li>Rust</li>
				</ol>
			</div>
			<div
				class="ml-5 mr-5 mb-6 lg:w-1/3 xl:w-sm xl:mb-0 block p-6 min-w-sm bg-white rounded-lg border border-gray-200 shadow-md hover:bg-gray-100"
			>
				<h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Most used technologies</h5>
				<ol class="list-disc pl-4 font-normal text-gray-700">
					<li>
						React
						<ol class="list-disc pl-6">
							<li>NextJS</li>
							<li>Gatsby</li>
							<li>Material UI</li>
						</ol>
					</li>
					<li>HTML + CSS</li>
					<li>Git</li>
					<li>
						Linux
						<ol class="list-disc pl-6">
							<li>Fedora</li>
							<li>Debian</li>
						</ol>
					</li>
					<li>MongoDB</li>
					<li>NodeJS + Express</li>
				</ol>
			</div>
			<div
				class="ml-5 mr-5 block lg:w-1/4 xl:w-sm p-6 max-w-sm bg-white rounded-lg border border-gray-200 shadow-md hover:bg-gray-100"
			>
				<h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Less used technologies</h5>
				<ol class="list-disc pl-4 font-normal text-gray-700">
					<li>Tailwind</li>
					<li>Svelte</li>
					<li>MySQL</li>
					<li>Vue</li>
					<li>Three.js</li>
					<li>Discord.js</li>
					<li>Blender</li>
				</ol>
			</div>
		</div>
	</div>
	<svg class="mt-[-2px]" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"
		><path
			fill="#EF4444"
			fill-opacity="1"
			d="M0,128L48,144C96,160,192,192,288,197.3C384,203,480,181,576,154.7C672,128,768,96,864,85.3C960,75,1056,85,1152,96C1248,107,1344,117,1392,122.7L1440,128L1440,0L1392,0C1344,0,1248,0,1152,0C1056,0,960,0,864,0C768,0,672,0,576,0C480,0,384,0,288,0C192,0,96,0,48,0L0,0Z"
		/></svg
	>
</section>
<section class="w-screen bg-white lg:-mt-16 xl:-mt-32">
	<div class="container mx-auto -mt-1">
		<h2
			class="text-center font-mono font-semibold text-4xl xl:text-5xl text-black-800 xl:mt-[-50px] pb-10"
		>
			Experience
		</h2>
		<div class="flex flex-wrap justify-center items-center mx-auto">
			<div
				class="ml-5 mr-5 mb-6 xl:mb-0 block p-6 max-w-sm bg-white rounded-lg border border-gray-200 shadow-xl shadow-blue-500/20 hover:bg-gray-100"
			>
				<h5 class="text-2xl font-bold tracking-tight text-gray-900">Unikum Tools</h5>
				<p class="text-gray-700">
					The past I have been working on, and recently finished a web browser extension. I made the
					extension as a hobby project and to use for school. The extension adds bookmarks to
					Unikum.net and is able to show both the schedule and food menu.
					<br />
					<a href="https://github.com/LeonHellqvist/unikum-tools" class="text-blue-500"
						>View on Github</a
					>
				</p>
			</div>
			<div
				class="ml-5 mr-5 mb-6 xl:mb-0 block p-6 max-w-sm bg-white rounded-lg border border-gray-200 shadow-xl shadow-green-700/30 hover:bg-gray-100"
			>
				<h5 class="text-2xl font-bold tracking-tight text-gray-900">OpenMineBay</h5>
				<p class="text-gray-700">
					The past year I have been working on a marketplace that integrades directly with
					Minecraft. It has a full web interface build with React (NextJS) and a NodeJS backend. It
					allows you to sell and buy items from other players and works on 100% vanilla servers!
					<br />
					<a href="#" class="text-green-500">(Soon public)</a>
				</p>
			</div>
			<div
				class="ml-5 mr-5 mb-6 xl:mb-0 block p-6 max-w-sm bg-white rounded-lg border border-gray-200 shadow-xl shadow-pink-700/30 hover:bg-gray-100"
			>
				<h5 class="text-2xl font-bold tracking-tight text-gray-900">Hair Salon</h5>
				<p class="text-gray-700">
					When looking for hair salons for myself I stumbled upon a really poorly designed website
					from like 1999. I decided to make a new response website for them for free using React
					(Gatsby) and Tailwind. They never replied to my mail tho :(
					<br />
					<a href="https://github.com/LeonHellqvist/salon" class="text-pink-500">View on Github</a>
				</p>
			</div>
		</div>
	</div>
</section>
<section>
	<svg class="bg-white -mt-1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#111827" fill-opacity="1" d="M0,128L48,133.3C96,139,192,149,288,138.7C384,128,480,96,576,90.7C672,85,768,107,864,138.7C960,171,1056,213,1152,192C1248,171,1344,85,1392,42.7L1440,0L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"></path></svg>
	<div class="container mx-auto lg:-mt-2 xl:-mt-44">
		<h2
			class="text-center text-white font-mono font-semibold text-4xl xl:text-5xl text-black-800 xl:mt-[-50px] pb-10"
		>
			Contact
		</h2>
	</div>
</section>
<footer class="p-4 bg-white shadow-2xl md:flex md:items-center md:justify-between md:p-6">
	<span class="text-sm text-gray-500 sm:text-center"
		>© 2022 <a href="https://hellqvist.dev/" class="hover:underline">Leon Hellqvist</a>. All Rights
		Reserved.
	</span>
	<ul class="flex flex-wrap items-center mt-3 text-sm text-gray-500 sm:mt-0">
		<li>
			<a href="#" class="mr-4 hover:underline md:mr-6 ">About</a>
		</li>
		<li>
			<a href="#" class="mr-4 hover:underline md:mr-6">Privacy Policy</a>
		</li>
		<li>
			<a href="#" class="mr-4 hover:underline md:mr-6">Licensing</a>
		</li>
		<li>
			<a href="#" class="hover:underline">Contact</a>
		</li>
	</ul>
</footer>
