<script>
  export let titulo = "Menu";
</script>

<div class="">
  <span class="text-sm font-bold text-zinc-600 p-2">{titulo}</span>
  <ul class="flex flex-col">
    <slot></slot>
  </ul>
</div>
