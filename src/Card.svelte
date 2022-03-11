<script>
  import Badge from "./Badge.svelte";
  import Button from "./Button.svelte";
</script>

<section>
  <img src="./sko.png" alt="" />
  <article>
    <h3>Shoes! <Badge type="secondary">NEW</Badge></h3>
    <p>If a dog chews shoes whose shoes does it choose?</p>
    <div class="badge">
      <Badge mode="inversed">Fashion</Badge>
      <Badge mode="inversed">Products</Badge>
    </div>
    <div class="buy">
      <Button type="primary">BUY NOW</Button>
    </div>
  </article>
</section>

<style>
  section {
    width: 20rem;
    border-radius: 12px;
    box-shadow: 6px 6px 10px 2px #c7c7c7;
  }

  img {
    width: 20rem;
    border-radius: 10px 10px 0px 0px;
  }

  .badge {
    display: flex;
    gap: 1rem;
  }

  .buy {
    justify-self: end;
  }

  article {
    display: grid;
    margin: 0.3rem;
  }
</style>
