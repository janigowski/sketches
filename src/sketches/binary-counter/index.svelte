<script lang="ts">
  import BinaryCounter from "./BinaryCounter.svelte";
  import { range } from "canvas-sketch-util/random";

  const binaryCounters = Array(200).fill(0);
</script>

<main>
  <div class="inner">
    <div class="grid">
      {#each binaryCounters as delayMs}
        <div class="item">
          <BinaryCounter delayMs={range(1, 4000)} length={8} />
        </div>
      {/each}
    </div>
  </div>
</main>

<style>
  main {
    display: flex;
    background-image: url("/src/assets/andre-benz-JnB8Gio4GZo-unsplash.jpg");
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    width: 100%;
    height: 100vh;
    cursor: none;
  }

  .inner {
    background-color: #0e0e0e;
    display: flex;
    width: 100%;
    justify-content: space-evenly;
    mix-blend-mode: multiply;
  }

  .grid {
    display: grid;
    grid-template-columns: repeat(8, 1fr);
    gap: 10px;
    border: 1px dashed #130f0f;
    padding: 20px;
    color: #363636;
  }

  .item {
  }
</style>
