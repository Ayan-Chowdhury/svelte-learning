<script>
//   let count = $state(0);
//   let doublecount = $derived(count * 2);
//   $effect(() => {
//     console.log(`Count: ${count},Double Count:${doublecount}`);
//   });

//   function increment() {
//     count++;
//   }
//   function reset() {
//     count = 0;
//   }
let name="Jhon";
let age=25;
</script>

<div class="flex justify-center items-center h-screen">
<div class="tex-center">
<h2> Hello {name}!</h2>
<p> Next year, you'll be {age + 1} years old.</p>
</div>
  <!-- <button onclick={increment} class="btn btn-blue">Increment</button>
  <p>Count: {count}</p>
  <p>Double Count: {doublecount}</p>
  <button onclick={reset}>Reset All</button> -->
</div>

<style></style>
