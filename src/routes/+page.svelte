<script>
	import FeedbackList from "../components/FeedbackList.svelte";
	import FeedbackStats from "../components/FeedbackStats.svelte";
	import FeedbackForm from "../components/FeedbackForm.svelte";







</script>

<svelte:head>
	<title>Video APP</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section class="container">
	<FeedbackForm  />
	<FeedbackStats />
	<FeedbackList   />
	
</section>

<style>

	/* section {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	} */
</style>
