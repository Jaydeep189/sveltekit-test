<script context="module">
import ApplyNow from "$lib/components/ApplyNow.svelte";
import Cources from "$lib/components/Cources.svelte";
import Facts from "$lib/components/Facts.svelte";
import Main from "$lib/components/Main.svelte";
import NewMeet from "$lib/components/NewMeet.svelte";
import Services from "$lib/components/Services.svelte";

	export const prerender = true;
</script>


<svelte:head>
	<title>Home</title>
</svelte:head>

<main>
	<Main />
	<!-- ***** Main Banner Area End ***** -->
  
	<Services/>
  
	<NewMeet />
  
	<ApplyNow />
  
	<Cources />
  
	<Facts />
</main>