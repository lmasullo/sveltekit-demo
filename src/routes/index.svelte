<!-- <script context="module" ✂prettier:content✂="CgkvLyBMb2FkIGZ1bmN0aW9uIHRvIGdldCB0aGUgZXZhbCB0ZW1wbGF0ZXMKCWV4cG9ydCBhc3luYyBmdW5jdGlvbiBsb2FkKHsgZmV0Y2ggfSkgewoJCWNvbnN0IHJlcyA9IGF3YWl0IGZldGNoKCcvYXBpL2dldFRlbXBsYXRlcycpOwoKCQlpZiAocmVzLm9rKSB7CgkJCWNvbnN0IGV2YWxUZW1wbGF0ZXMgPSBhd2FpdCByZXMuanNvbigpOwoKCQkJcmV0dXJuIHsKCQkJCXByb3BzOiB7IGV2YWxUZW1wbGF0ZXMgfQoJCQl9OwoJCX0KCgkJcmV0dXJuIHsKCQkJc3RhdHVzOiByZXMuc3RhdHVzLAoJCQllcnJvcjogbmV3IEVycm9yKCkKCQl9OwoJfQo=" ✂prettier:content✂="e30=" ✂prettier:content✂="e30=">{}</script> -->
<script>
  // // Dependencies
  // // import { onMount } from 'svelte';

  // // Prop from above context
  // export let evalTemplates;
  // console.log('Eval Templates: ', evalTemplates);

  // // Components
  // import Evaluation from '$lib/Evaluation.svelte';

  // // Variables
  // let visible = false;
  // let selected;
  // let unique = {};
  // let evalMessage = '';

  // // Get today's date and pull out the parts
  // const today = new Date();
  // let thisDay = today.getDate();
  // let thisMonth = today.getMonth() + 1;
  // const thisYear = today.getFullYear();

  // // Add a 0 if needed
  // if (thisDay.toString().length === 1) {
  // 	thisDay = `0${thisDay}`;
  // }
  // console.log('thisDay', thisDay);

  // // Add a 0 if needed
  // if (thisMonth.toString().length === 1) {
  // 	thisMonth = `0${thisMonth}`;
  // }
  // console.log('thisMonth', thisMonth);
  // console.log('thisYear', thisYear);

  // // Combine
  // const dateCombined = `${thisYear}-${thisMonth}-${thisDay}`;
  // console.log(dateCombined);

  // // Reset the eval template dropdown
  // $: if (evalMessage !== '') {
  // 	document.getElementById('template').selectedIndex = '0';
  // }

  // // Function to handle template choice
  // function handleSelect() {
  // 	console.log('In handleSelect', visible);

  // 	// Clear the message div
  // 	evalMessage = '';

  // 	unique = {}; // every {} is unique, {} === {} evaluates to false

  // 	if (selected) {
  // 		visible = true;
  // 	} else {
  // 		visible = false;
  // 	}
  // }

  // // onMount Lifecycle
  // // onMount(async () => {});
</script>

<title>Evaluations</title>

<!-- Main Container -->
<div class="containerEval">
  <!-- Jumbotron -->
  <div>
    <h1 class="display-4">Choose An Evaluation</h1>
    <!-- <h3 class="text-danger">**Testing**</h3>
			<h4 class="text-danger">Do Not Enter an Eval!</h4> -->
    <!-- Div to display the success message -->
    <!-- <p id="message" class="lead">
			*****Testing the Send Email to the Resident Function!!*****
		</p> -->
    <!-- End Jumbotron -->

    <!-- <select id="template" class="custom-select" bind:value={selected} on:change={handleSelect}>
			<option value="">Choose an Evaluation</option>
			{#each evalTemplates as item}
				<option value={item.id}>{item.templateName}</option>
			{/each}
		</select> -->
  </div>

  <!-- <h3 class="lead" bind:innerHTML={evalMessage} contenteditable /> -->

  <!-- End Main Container -->
</div>

<!-- {#if visible}
	{#key unique}
		<Evaluation templateId={selected} {dateCombined} bind:visible bind:evalMessage />
	{/key}
{/if} -->
<style>
  /* .lead {
		color: green;
		padding-top: 2rem;
	} */
</style>
