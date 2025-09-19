<script lang="ts">
  import Header from "./lib/Header.svelte";
  import Title from "./lib/Title.svelte";
  import Search from "./lib/Search.svelte";
  import WeatherInfoContainer from "./lib/WeatherInfoContainer.svelte";
  import DailyForecast from "./lib/DailyForecast.svelte";
  import HourlyForecast from "./lib/HourlyForecast.svelte";
</script>

<Header />

<Title />

<main id="main-content">
  <Search />
  <WeatherInfoContainer />
  <DailyForecast />
  <HourlyForecast />
</main>
