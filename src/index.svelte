<script>
  let text = ""
</script>

<label>
  Write something:
  <input type="text" bind:value={text}>
</label>

<p>You said: {text}</p>
