<script>
	import HeaderSection from './HeaderSection.svelte';
	import InfoSection from './InfoSection.svelte';
	import PracticalInformationSection from './PracticalInformationSection.svelte';
	// import Spacer from './Spacer.svelte';
</script>

<svelte:head>
	<title>PyCon NL 2025</title>

	<meta name="title" property="og:title" content="PyCon NL 2025" />
	<meta name="description" property="og:description" content="PyCon NL 2025" />
	<meta name="type" property="og:type" content="website" />
	<meta name="url" property="og:url" content="https://pythonconferentie.nl/" />
	<meta
		name="image"
		property="og:image"
		content="https://pythonconferentie.nl/marketing/socials.png"
	/>
	<meta name="twitter:card" content="summary_large_image" />
</svelte:head>

<div>
	<HeaderSection />
	<InfoSection />
	<!-- <Spacer /> -->
	<PracticalInformationSection />
</div>
