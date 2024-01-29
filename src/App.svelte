<script>
  import Typewriter from 'svelte-typewriter'

</script>

<style>
  div {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh; /* Set the height of the div to 100% of the viewport height */
  }

  h1 {
    --cursor-color: #ffffff;
    --cursor-width: 1rem;
    font-family: "Fira Code", monospace;
    justify-content: flex-start; /* Keep the text justified left */
  }
</style>

<div>
  <Typewriter mode="cascade" interval={80} keepCursorOnFinish={true} cursor={true}>
    <h1> Hello there, I'm Dawid </h1>
    <h1> and I'm... </h1>
  </Typewriter>
</div>

