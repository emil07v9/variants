<script>
  export let type = "default";
  export let mode;
</script>

<div class={type} class:inversed={mode === "inversed"}>
  <slot />
</div>

<style>
  div {
    color: var(--primary-font-color);
    background: var(--default-color);
    display: inline-block;
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

  .inversed {
    color: var(--default-color);
    background: var(--primary-font-color);
    border: solid;
  }
</style>
