<script lang="ts">
  import TextField from "@smui/textfield";
  export let value: string | null = null;
  export let label: string;
</script>

<TextField bind:value bind:label />

<style></style>
