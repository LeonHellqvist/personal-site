<script>
</script>

<svelte:head>
	<title>Leon Hellqvist - Home</title>
	<html lang="en" />
	<meta name="description" content="Leon Hellqvist's personal website. Full-stack developer from Sweden. Here I write a little about myself and my projects!"/>
	<!-- Facebook Meta Tags -->
	<meta property="og:url" content="https://leonhellqvist.com/">
	<meta property="og:type" content="website">
	<meta property="og:title" content="Leon Hellqvist - Personal site">
	<meta property="og:description" content="Leon Hellqvist's personal website. Full-stack developer from Sweden. Here I write a little about myself and my projects!">
	<meta property="og:image" content="https://leonhellqvist.com/ogimage.png">

	<!-- Twitter Meta Tags -->
	<meta name="twitter:card" content="summary_large_image">
	<meta property="twitter:domain" content="leonhellqvist.com">
	<meta property="twitter:url" content="https://leonhellqvist.com/">
	<meta name="twitter:title" content="Leon Hellqvist - Personal site">
	<meta name="twitter:description" content="Leon Hellqvist's personal website. Full-stack developer from Sweden. Here I write a little about myself and my projects!">
	<meta name="twitter:image" content="https://leonhellqvist.com/ogimage.png">
</svelte:head>

<nav class="bg-white border-gray-200 px-2 sm:px-4 py-2.5">
	<div class="container flex flex-wrap justify-between items-center mx-auto">
		<span class="self-center text-xl font-semibold whitespace-nowrap">Leon Hellqvist</span>
		<div class="flex md:order-2">
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
						class="block py-2 pr-4 pl-3 text-white bg-red-800 rounded md:bg-transparent md:text-red-500 md:p-0"
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
				<h3 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Programming languages</h3>
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
				<h3 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Most used technologies</h3>
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
				<h3 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Less used technologies</h3>
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
				<h3 class="text-2xl font-bold tracking-tight text-gray-900">Unikum Tools</h3>
				<p class="text-gray-700">
					In the past I have been working on, and recently finished a web browser extension. I made the
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
				<h3 class="text-2xl font-bold tracking-tight text-gray-900">OpenMineBay</h3>
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
				<h3 class="text-2xl font-bold tracking-tight text-gray-900">Hair Salon</h3>
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
	<div class="bg-gray-900 w-screen mx-auto -mt-1 lg:-mt-20 xl:-mt-30 2xl:-mt-32">
		<h2
			class="text-center text-white font-mono font-semibold text-4xl xl:text-5xl text-black-800 xl:mt-[-50px] pb-10"
		>
			Contact
		</h2>
		<div class="flex justify-center -mt-4">
			<div>
				<a href="https://github.com/LeonHellqvist/">
					<button type="button" class="text-white bg-[#24292F] hover:bg-[#24292F]/90 focus:ring-4 focus:outline-none focus:ring-[#24292F]/50 font-medium rounded-lg text-sm px-5 py-2.5 text-center inline-flex items-center dark:focus:ring-gray-500 dark:hover:bg-[#050708]/30 mr-2 mb-2">
						<svg class="mr-2 -ml-1 w-4 h-4" aria-hidden="true" focusable="false" data-prefix="fab" data-icon="github" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 496 512"><path fill="currentColor" d="M165.9 397.4c0 2-2.3 3.6-5.2 3.6-3.3 .3-5.6-1.3-5.6-3.6 0-2 2.3-3.6 5.2-3.6 3-.3 5.6 1.3 5.6 3.6zm-31.1-4.5c-.7 2 1.3 4.3 4.3 4.9 2.6 1 5.6 0 6.2-2s-1.3-4.3-4.3-5.2c-2.6-.7-5.5 .3-6.2 2.3zm44.2-1.7c-2.9 .7-4.9 2.6-4.6 4.9 .3 2 2.9 3.3 5.9 2.6 2.9-.7 4.9-2.6 4.6-4.6-.3-1.9-3-3.2-5.9-2.9zM244.8 8C106.1 8 0 113.3 0 252c0 110.9 69.8 205.8 169.5 239.2 12.8 2.3 17.3-5.6 17.3-12.1 0-6.2-.3-40.4-.3-61.4 0 0-70 15-84.7-29.8 0 0-11.4-29.1-27.8-36.6 0 0-22.9-15.7 1.6-15.4 0 0 24.9 2 38.6 25.8 21.9 38.6 58.6 27.5 72.9 20.9 2.3-16 8.8-27.1 16-33.7-55.9-6.2-112.3-14.3-112.3-110.5 0-27.5 7.6-41.3 23.6-58.9-2.6-6.5-11.1-33.3 2.6-67.9 20.9-6.5 69 27 69 27 20-5.6 41.5-8.5 62.8-8.5s42.8 2.9 62.8 8.5c0 0 48.1-33.6 69-27 13.7 34.7 5.2 61.4 2.6 67.9 16 17.7 25.8 31.5 25.8 58.9 0 96.5-58.9 104.2-114.8 110.5 9.2 7.9 17 22.9 17 46.4 0 33.7-.3 75.4-.3 83.6 0 6.5 4.6 14.4 17.3 12.1C428.2 457.8 496 362.9 496 252 496 113.3 383.5 8 244.8 8zM97.2 352.9c-1.3 1-1 3.3 .7 5.2 1.6 1.6 3.9 2.3 5.2 1 1.3-1 1-3.3-.7-5.2-1.6-1.6-3.9-2.3-5.2-1zm-10.8-8.1c-.7 1.3 .3 2.9 2.3 3.9 1.6 1 3.6 .7 4.3-.7 .7-1.3-.3-2.9-2.3-3.9-2-.6-3.6-.3-4.3 .7zm32.4 35.6c-1.6 1.3-1 4.3 1.3 6.2 2.3 2.3 5.2 2.6 6.5 1 1.3-1.3 .7-4.3-1.3-6.2-2.2-2.3-5.2-2.6-6.5-1zm-11.4-14.7c-1.6 1-1.6 3.6 0 5.9 1.6 2.3 4.3 3.3 5.6 2.3 1.6-1.3 1.6-3.9 0-6.2-1.4-2.3-4-3.3-5.6-2z"></path></svg>
						Follow me on Github
					</button>
				</a>
				<a href="mailto:leon@leonhellqvist.com">
					<button type="button" class="text-white bg-[#24292F] hover:bg-[#24292F]/90 focus:ring-4 focus:outline-none focus:ring-[#24292F]/50 font-medium rounded-lg text-sm px-5 py-2.5 text-center inline-flex items-center dark:focus:ring-gray-500 dark:hover:bg-[#050708]/30 mr-2 mb-2">
						<svg class="mr-2 -ml-1 w-4 h-4" aria-hidden="true" focusable="false" data-prefix="fab" data-icon="github" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 496 512"><path fill="currentColor" d="M464 64C490.5 64 512 85.49 512 112C512 127.1 504.9 141.3 492.8 150.4L275.2 313.6C263.8 322.1 248.2 322.1 236.8 313.6L19.2 150.4C7.113 141.3 0 127.1 0 112C0 85.49 21.49 64 48 64H464zM217.6 339.2C240.4 356.3 271.6 356.3 294.4 339.2L512 176V384C512 419.3 483.3 448 448 448H64C28.65 448 0 419.3 0 384V176L217.6 339.2z"></path></svg>
						leon@leonhellqvist.com
					</button>
				</a>
				<button type="button" class="text-white bg-[#24292F] hover:bg-[#24292F]/90 focus:ring-4 focus:outline-none focus:ring-[#24292F]/50 font-medium rounded-lg text-sm px-5 py-2.5 text-center inline-flex items-center dark:focus:ring-gray-500 dark:hover:bg-[#050708]/30 mr-2 mb-2">
					<svg class="mr-2 -ml-1 w-6 h-4" aria-hidden="true" focusable="false" data-prefix="fab" data-icon="github" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 496 512"><path fill="currentColor" d="M524.531,69.836a1.5,1.5,0,0,0-.764-.7A485.065,485.065,0,0,0,404.081,32.03a1.816,1.816,0,0,0-1.923.91,337.461,337.461,0,0,0-14.9,30.6,447.848,447.848,0,0,0-134.426,0,309.541,309.541,0,0,0-15.135-30.6,1.89,1.89,0,0,0-1.924-.91A483.689,483.689,0,0,0,116.085,69.137a1.712,1.712,0,0,0-.788.676C39.068,183.651,18.186,294.69,28.43,404.354a2.016,2.016,0,0,0,.765,1.375A487.666,487.666,0,0,0,176.02,479.918a1.9,1.9,0,0,0,2.063-.676A348.2,348.2,0,0,0,208.12,430.4a1.86,1.86,0,0,0-1.019-2.588,321.173,321.173,0,0,1-45.868-21.853,1.885,1.885,0,0,1-.185-3.126c3.082-2.309,6.166-4.711,9.109-7.137a1.819,1.819,0,0,1,1.9-.256c96.229,43.917,200.41,43.917,295.5,0a1.812,1.812,0,0,1,1.924.233c2.944,2.426,6.027,4.851,9.132,7.16a1.884,1.884,0,0,1-.162,3.126,301.407,301.407,0,0,1-45.89,21.83,1.875,1.875,0,0,0-1,2.611,391.055,391.055,0,0,0,30.014,48.815,1.864,1.864,0,0,0,2.063.7A486.048,486.048,0,0,0,610.7,405.729a1.882,1.882,0,0,0,.765-1.352C623.729,277.594,590.933,167.465,524.531,69.836ZM222.491,337.58c-28.972,0-52.844-26.587-52.844-59.239S193.056,219.1,222.491,219.1c29.665,0,53.306,26.82,52.843,59.239C275.334,310.993,251.924,337.58,222.491,337.58Zm195.38,0c-28.971,0-52.843-26.587-52.843-59.239S388.437,219.1,417.871,219.1c29.667,0,53.307,26.82,52.844,59.239C470.715,310.993,447.538,337.58,417.871,337.58Z"></path></svg>
					NisseV2#6585
				</button>
			</div>
		</div>
	</div>
</section>
<footer class="p-4 bg-gray-900 shadow-2xl md:flex md:items-center md:justify-between md:p-6">
	<span class="text-sm text-gray-500 sm:text-center"
		>© 2022 <a href="https://leonhellqvist.com/" class="hover:underline">Leon Hellqvist</a>. All Rights
		Reserved.
	</span>
</footer>
