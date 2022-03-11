<script>
  import Button from "./Button.svelte";
  import Badge from "./Badge.svelte";
  import Footer from "./Footer.svelte";
  import Card from "./Card.svelte";
  import ButtonBadge from "./ButtonBadge.svelte";
  import Avatar from "./Avatar.svelte";
</script>

<section>
  <article>
    <h1>Dokumentation</h1>
  </article>
  <article>
    <h2>Buttons</h2>
  </article>
  <div id="grid">
    <article>
      <h3>Default button</h3>
      <Button>DEFAULT</Button>
      <pre><code>{"<Button>DEFAULT</Button>"}</code></pre>
    </article>
    <article>
      <h3>Primary button</h3>
      <Button type="primary">PRIMARY</Button>
      <pre><code>{'<Button type="primary">PRIMARY</Button>'}</code></pre>
    </article>
    <article>
      <h3>Secondary button</h3>
      <Button type="secondary">SECONDARY</Button>
      <pre><code>{'<Button type="secondary">SECONDARY</Button>'}</code></pre>
    </article>
    <article>
      <h3>Accent button</h3>
      <Button type="accent">ACCENT</Button>
      <pre><code>{'<Button type="accent">ACCENT</Button>'}</code></pre>
    </article>
    <article>
      <h3>Ghost button</h3>
      <Button type="ghost">GHOST</Button>
      <pre><code>{'<Button type="ghost">GHOST</Button>'}</code></pre>
    </article>
    <article>
      <h3>Link button</h3>
      <Button type="link">LINK</Button>
      <pre><code>{'<Button type="link">LINK</Button>'}</code></pre>
    </article>
  </div>
</section>
<hr />
<section>
  <article>
    <h2>Badges</h2>
  </article>
  <div id="grid">
    <article>
      <h3>Default badge</h3>
      <Badge>default</Badge>
      <pre><code>{"<Badge>default</Badge>"}</code></pre>
    </article>
    <article>
      <h3>Primary badge</h3>
      <Badge type="primary">primary</Badge>
      <pre><code>{'<Badge type="primary">primary</Badge>'}</code></pre>
    </article>
    <article>
      <h3>Secondary badge</h3>
      <Badge type="secondary">secondary</Badge>
      <pre><code>{'<Badge type="secondary">secondary</Badge>'}</code></pre>
    </article>
    <article>
      <h3>Accent badge</h3>
      <Badge type="accent">accent</Badge>
      <pre><code>{'<Badge type="accent">accent</Badge>'}</code></pre>
    </article>
    <article>
      <h3>Ghost badge</h3>
      <Badge type="ghost">ghost</Badge>
      <pre><code>{'<Badge type="ghost">ghost</Badge>'}</code></pre>
    </article>
  </div>
</section>
<hr />
<section>
  <h2>Footer</h2>
</section>
<Footer />
<section>
  <pre><code>{"<Footer />"}</code></pre>
</section>
<hr />
<section>
  <h2>Card</h2>
  <Card />
  <pre><code>{"<Card />"}</code></pre>
</section>
<hr />
<section>
  <h2>Button Badge</h2>
  <ButtonBadge />
  <pre><code>{"<ButtonBadge />"}</code></pre>
</section>
<hr />
<section>
  <h2>Avatar</h2>
  <div id="grid">
    <article>
      <h3>Smallest avatar</h3>
      <Avatar type="smallest" image="false" mode="indicator">JK</Avatar>
      <pre><code
          >{'<Avatar type="smallest" image="false" mode="indicator">JK</Avatar>'}</code
        ></pre>
    </article>
    <article>
      <h3>Small avatar</h3>
      <Avatar type="small">JK</Avatar>
      <pre><code>{'<Avatar type="small">JK</Avatar>'}</code></pre>
    </article>
    <article>
      <h3>Medium avatar</h3>
      <Avatar type="medium" mode="indicator">JK</Avatar>
      <pre><code>{'<Avatar type="medium" mode="indicator">JK</Avatar>'}</code
        ></pre>
    </article>
    <article>
      <h3>Big avatar</h3>
      <Avatar type="big" image="false">JK</Avatar>
      <pre><code>{'<Avatar type="big" image="false">JK</Avatar>'}</code></pre>
    </article>
  </div>
</section>

<!-- <Button type="primary" mode="inversed">Primary inversed</Button>
<Button type="secondary" mode="inversed">secondary inversed</Button> -->
<style>
</style>
