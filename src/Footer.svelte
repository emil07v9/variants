<footer>
  <section>
    <h3>SERVICES</h3>
    <ul>
      <li>Branding</li>
      <li>Design</li>
      <li>Marketing</li>
      <li>Advertisement</li>
    </ul>
  </section>
  <section>
    <h3>COMPANY</h3>
    <ul>
      <li>About us</li>
      <li>Contact</li>
      <li>Jobs</li>
      <li>Press kit</li>
    </ul>
  </section>
  <section>
    <h3>LEGAL</h3>
    <ul>
      <li>Terms of use</li>
      <li>Privacy Policy</li>
      <li>Cookie Policy</li>
    </ul>
  </section>
</footer>

<style>
  footer {
    background: var(--footer-background);
    color: var(--primary-font-color);
    padding: 1rem;
  }

  li {
    list-style: none;
    padding-top: 0.5rem;
  }

  ul {
    padding: 0;
  }

  h3 {
    color: var(--footer-h3);
  }

  @media (min-width: 600px) {
    footer {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
    }

    section {
      justify-self: center;
    }
  }
</style>
