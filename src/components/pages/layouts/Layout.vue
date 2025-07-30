<script setup></script>
<template>
  <header></header>
  <main>
    <slot />
  </main>
  <footer>
    <small>Created by </small>
    <a href="https://www.github.com/whitehades" target="_blank"
      ><img
        alt="pfp"
        src="https://avatars.githubusercontent.com/u/44260523?v=4"
      />
      <p>whitehades</p>
    </a>
  </footer>
</template>
<style scoped>
header,
footer,
main {
  padding: 1rem;
  width: 100%;
  max-width: 650px;
  margin: 0 auto;
}

main {
  flex: 1;
}

footer {
  display: flex;
  flex-direction: column;
  gap: 0.5rem;
  align-items: center;
  padding: 3rem 0;
  padding-bottom: 4rem;
}
footer a {
  display: flex;
  align-items: center;
  gap: 0.5rem;
  padding: 0.3rem;
  padding-right: 0.5rem;
  background: var(--background-muted);
  border-radius: 4rem;
  border: 1px solid transparent;
  transition-duration: 200ms;
  text-decoration: none;
}

footer a:hover {
  border-color: var(--color-link);
}

footer a img {
  max-width: 30px;
  aspect-ration: 1 / 1;
  border-radius: 100%;
}
</style>
