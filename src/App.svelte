<script>
  import Gantt from "./Gantt.svelte";
  import { getData } from "./data.js";
</script>

<Gantt tasks={getData()} />
