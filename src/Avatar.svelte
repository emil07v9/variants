<script>
  export let type;
  export let image = true;
  export let mode;
</script>

<div class={type}>
  <div class:indicator={mode === "indicator"} />
  <div />
  {#if image == true}
    <img src="./sko.png" alt="" />
  {:else}
    <slot />
  {/if}
</div>

<style>
  div {
    background: var(--default-color);
    color: var(--primary-font-color);
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 0;
    position: relative;
  }

  .indicator {
    width: 15%;
    height: 15%;
    background-color: chartreuse;
    border-radius: 100%;
    position: absolute;
    right: 8%;
    top: 0%;
    border: solid 2px white;
  }

  img {
    height: 100%;
    width: 100%;
    border-radius: 100%;
  }

  .smallest {
    width: 2rem;
    height: 2rem;
    border-radius: 100%;
  }

  .small {
    width: 4rem;
    height: 4rem;
    border-radius: 100%;
  }

  .medium {
    width: 6rem;
    height: 6rem;
    border-radius: 100%;
    position: relative;
  }

  .big {
    width: 8rem;
    height: 8rem;
    border-radius: 100%;
  }
</style>
