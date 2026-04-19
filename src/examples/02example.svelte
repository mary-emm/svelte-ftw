<!-- logic -->

<script>
  // specifying that the count variable is reactive
  let count = $state(0);
</script>

<div class="flex flex-col gap-4 items-center">
  <p>Count is {count}</p>

  <div>
    <button
      class="bg-[#FFA23A] text-[#111111] px-4 py-2 rounded-lg"
      onclick={() => (count += 1)}
    >
      +
    </button>

    <button
      class="bg-[#FFA23A] text-[#111111] px-4 py-2 rounded-lg"
      onclick={() => (count -= 1)}
    >
      -
    </button>
  </div>
</div>

<!-- <div class="flex flex-col gap-4"></div> -->
