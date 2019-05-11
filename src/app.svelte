<script>
	import HeaderCmp from './components/header_component.svelte';
	import TrekkingListCmp from './components/trekking_list_component.svelte';
</script>

<style>
	h1 {
		color: purple;
	}
</style>

<div>
	<HeaderCmp />

	<main>
		<TrekkingListCmp />		
	</main>
</div>
