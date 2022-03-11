<script>
  export let type = "default";
</script>

<button class={type}><slot /></button>

<!-- <button class:inversed={mode === "inversed"} class={type}><slot /></button> -->
<style>
  button {
    color: var(--primary-font-color);
    background: var(--default-color);
    font-weight: bold;
    display: block;
  }

  button:hover {
    opacity: var(--opacity-lightness);
  }

  .primary {
    background: var(--primary-color);
  }

  .secondary {
    background: var(--secondary-color);
  }

  .accent {
    background: var(--accent-color);
  }

  .ghost {
    color: var(--ghost-font-color);
    background: var(--link-color-none);
  }

  .link {
    color: var(--link-font-color);
    background: var(--link-color-none);
  }

  /* .primary.inversed {
    color: var(--primary-color);
    background: var(--primary-font-color);
  }

  .secondary.inversed {
    color: var(--secondary-color);
    background: var(--primary-font-color);
  } */
</style>
