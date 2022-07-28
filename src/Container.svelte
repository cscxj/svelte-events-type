<script lang="ts">
  import { createEventDispatcher } from "svelte";

  type Events = {
    hoverContainer: { point: [number, number] };
  };

  const dispatch = createEventDispatcher<Events>();
</script>
