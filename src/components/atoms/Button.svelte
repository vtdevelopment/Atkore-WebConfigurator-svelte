<script lang="ts">
  export let text: string;
  export let onClick: () => void;

  export let style: "text" | "full";
</script>

<div on:click={onClick} class={`button ${style}`}>
  {text}
</div>

<style>
</style>
