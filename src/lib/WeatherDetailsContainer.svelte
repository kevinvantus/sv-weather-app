<script>
  import WeatherDetails from "./WeatherDetails.svelte";
</script>

<div class="weather-details-ctr">
  <WeatherDetails />
  <WeatherDetails />
  <WeatherDetails />
  <WeatherDetails />
</div>

<style>
  .weather-details-ctr {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: var(--size-200);
  }
</style>
