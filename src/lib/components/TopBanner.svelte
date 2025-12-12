<script lang="ts">
  export let text = "En savoir plus";
  export let href = "#";
</script>

<div class="bg-black text-white text-[11px] font-medium py-3 px-4 flex justify-between items-center tracking-wide">
  <div class="flex-1 text-center">
    <span class="opacity-90">Installations conformes aux normes de sécurité du Québec • Garantie certifiée</span>
  </div>
  <a {href} class="bg-[oklch(0.696_0.17_162.48)] hover:bg-[oklch(0.596_0.145_163.225)] text-white px-3 py-1.5 rounded text-[10px] font-bold uppercase tracking-wider ml-4 transition-colors">
    {text}
  </a>
</div>
