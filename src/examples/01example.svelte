<!-- js -->

<!-- <script>
	let count = $state(0)
</script> -->

<!-- logic -->
<script>
// declare that the variabe is a rune state, in order to rerender
	let count = $state(0)


	// this is for example 2
	let title = "Maryam"

	// example 3

	let color ="orangered"


	let content = `<h1>I was here</h1>
	<p>I lived, I loved</p>`
</script>

<!-- markup -->

<button onclick={()=> count++}>
	{count}
</button>



<!-- example 2 -->
<h1>
	{title}
</h1>


<!-- exmample 3 -->

<h3 style:color>
	Yes
</h3>

<hgroup>
	{@html content}
</hgroup>



<!-- style -->
 <style>
	h1 {
		color: #EE402E;
	}

	/* global styling */

	hgroup :global {
		h1 {
			text-transform: lowercase;
			color: #885850;
		}
	}
 </style>







