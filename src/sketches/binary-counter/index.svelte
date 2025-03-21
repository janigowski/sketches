<script lang="ts">
  import BinaryCounter from "./BinaryCounter.svelte";
</script>

<main>
  <div class="binary-counters">
    <BinaryCounter intervalMs={100} delayMs={0} length={8} />
    <BinaryCounter intervalMs={100} delayMs={0} length={6} />
    <BinaryCounter intervalMs={100} delayMs={0} length={4} />
    <BinaryCounter intervalMs={100} delayMs={0} length={8} />
    <BinaryCounter intervalMs={80} delayMs={0} length={5} />
    <BinaryCounter intervalMs={2000} delayMs={0} length={4} />
    <BinaryCounter intervalMs={150} delayMs={0} length={8} />
    <BinaryCounter intervalMs={150} delayMs={0} length={8} />
    <BinaryCounter intervalMs={150} delayMs={0} length={8} />
    <BinaryCounter intervalMs={150} delayMs={0} length={8} />
    <BinaryCounter intervalMs={150} delayMs={150} length={8} />
    <BinaryCounter intervalMs={50} delayMs={0} length={8} />
    <BinaryCounter intervalMs={150} delayMs={0} length={8} />
    <BinaryCounter intervalMs={150} delayMs={0} length={8} />
    <BinaryCounter intervalMs={150} delayMs={0} length={8} />
    <BinaryCounter intervalMs={500} delayMs={0} length={8} />
    <BinaryCounter intervalMs={150} delayMs={0} length={10} />
    <BinaryCounter intervalMs={150} delayMs={0} length={3} />
    <BinaryCounter intervalMs={150} delayMs={0} length={8} />
    <BinaryCounter intervalMs={150} delayMs={0} length={8} />
    <BinaryCounter intervalMs={150} delayMs={0} length={8} />
    <BinaryCounter intervalMs={150} delayMs={0} length={8} />
    <BinaryCounter intervalMs={150} delayMs={0} length={8} />
    <BinaryCounter intervalMs={150} delayMs={180} length={4} />
    <BinaryCounter intervalMs={150} delayMs={0} length={8} />
    <BinaryCounter intervalMs={150} delayMs={0} length={8} />
    <BinaryCounter intervalMs={10} delayMs={0} length={8} />
    <BinaryCounter intervalMs={150} delayMs={0} length={8} />
    <BinaryCounter intervalMs={150} delayMs={0} length={8} />
    <BinaryCounter intervalMs={150} delayMs={0} length={8} />
    <BinaryCounter intervalMs={100} delayMs={0} length={8} />
    <BinaryCounter intervalMs={150} delayMs={0} length={8} />
    <BinaryCounter intervalMs={150} delayMs={0} length={8} />
    <BinaryCounter intervalMs={150} delayMs={0} length={8} />
    <BinaryCounter intervalMs={80} delayMs={240} length={8} />
    <BinaryCounter intervalMs={80} delayMs={0} length={8} />
    <BinaryCounter intervalMs={80} delayMs={0} length={8} />
    <BinaryCounter intervalMs={80} delayMs={0} length={8} />
    <BinaryCounter intervalMs={80} delayMs={0} length={8} />
    <BinaryCounter intervalMs={100} delayMs={2000} length={2} />
  </div>
</main>

<style>
  .binary-counters {
    display: flex;
    flex-wrap: wrap;
    flex-direction: row;
    justify-content: center;
  }
</style>
