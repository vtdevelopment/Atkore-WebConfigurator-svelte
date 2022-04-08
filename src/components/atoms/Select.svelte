<script lang="ts">
  import Select, { Option } from "@smui/select";

  export let options: string[];
  export let label: string;
  let value: string;
</script>

<Select bind:value {label}>
  {#each options as option}
    <Option value={option}>{option}</Option>
  {/each}
</Select>
