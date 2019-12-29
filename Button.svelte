<script>
	let count = 0;

	function handleClick() {
	  count += 1;
	}
</script>

<style>
	button {
	  background: #666666;
	  color: white;
	  border: none;
	  padding: 8px 12px;
	  border-radius: 2px;
	}
	.counter {
	  padding: 12px;
	  color: gray;
	  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
	}
</style>

<button on:click={handleClick}>
  Clicked {count} {count === 1 ? 'time' : 'times'}
</button>

<div class="counter">{count}</div>