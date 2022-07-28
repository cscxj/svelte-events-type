<script lang="ts">
  import Container from "./Container.svelte";
</script>

<div>
  <Container
    on:hoverContainer={({ detail }) => {
      console.log(detail);
    }}
  />
</div>
