<!-- <script>
    let count = $state(0)
</script>

<button
	class="bg-[#FFA23A] text-[#111111] px-4 py-2 rounded"
	onclick={() => count++}
>
	Clicked {count} times
</button> -->


<!-- logic -->

<script>
    // specifying that the count variable is reactive
    let count = $state(0)

</script>

<button
class = "bg-[#FFA23A] text-[#111111] px-4 py-2 rounded-lg"

 onclick={() => count += 1}>
This button was clicked {count} times    
</button>