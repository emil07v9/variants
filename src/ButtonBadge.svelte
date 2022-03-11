<script>
  import Button from "./Button.svelte";
  import Badge from "./Badge.svelte";
</script>

<article>
  <Button
    >INBOX <div><Badge type="secondary">99+</Badge></div></Button
  >
</article>

<style>
  article {
    position: relative;
    display: inline-block;
  }

  div {
    position: absolute;
    top: -16px;
    left: 40px;
  }
</style>
