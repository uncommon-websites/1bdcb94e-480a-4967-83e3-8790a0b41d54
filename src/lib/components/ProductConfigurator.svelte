<script lang="ts">
  let selectedColor = 'white';
</script>

<section class="bg-[#f9f9f7] py-24 px-6">
  <div class="max-w-[1200px] mx-auto text-center">
    <h2 class="text-[40px] font-light text-gray-900 mb-16">
      Plusieurs styles. <span class="text-gray-400">Infinies possibilités.</span>
    </h2>

    <div class="mb-8">
      <h3 class="text-2xl font-normal mb-2">Rampes en aluminium</h3>
      <p class="text-gray-500 text-sm">Durables, élégantes et conformes aux normes.</p>
    </div>

    <!-- Product Image -->
    <div class="relative w-full h-[400px] bg-white rounded-xl mb-8 flex items-center justify-center overflow-hidden shadow-sm">
      <div class="absolute inset-0 flex items-center justify-between px-4">
        <button class="w-10 h-10 rounded-full bg-gray-100 flex items-center justify-center hover:bg-gray-200">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m15 18-6-6 6-6"/></svg>
        </button>
        <button class="w-10 h-10 rounded-full bg-gray-100 flex items-center justify-center hover:bg-gray-200">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m9 18 6-6-6-6"/></svg>
        </button>
      </div>
      <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?q=80&w=2070&auto=format&fit=crop" class="h-[80%] object-contain" alt="Rampe en aluminium" />
    </div>

    <!-- Controls -->
    <div class="flex justify-center gap-4 mb-8">
      <button class="w-8 h-8 rounded-full bg-[oklch(0.905_0.093_164.15)] border-2 border-[oklch(0.696_0.17_162.48)] ring-2 ring-offset-2 ring-[oklch(0.845_0.143_164.978)]"></button>
      <button class="w-8 h-8 rounded-full bg-[#f3f4f6]"></button>
      <button class="w-8 h-8 rounded-full bg-[#374151]"></button>
      <button class="w-8 h-8 rounded-full bg-[#78350f]"></button>
    </div>

    <div class="flex justify-center gap-8 text-sm text-gray-600 mb-4 border-b border-gray-200 pb-4 inline-flex mx-auto w-auto px-12">
      <span>Aluminium</span>
      <span>Conforme RBQ</span>
      <span>Garantie 10 ans</span>
    </div>

    <p class="text-xs text-gray-500 mb-8">
      À partir de <span class="font-bold text-gray-900">3 500$</span> installation incluse.<br>
      Options de financement disponibles. ⓘ
    </p>

    <div class="flex justify-center gap-4">
      <button class="px-6 py-3 bg-gray-100 hover:bg-gray-200 rounded-lg text-sm font-medium transition-colors text-left">
        <span class="block text-[10px] text-gray-500">Envie d'en voir plus?</span>
        <span class="text-[oklch(0.696_0.17_162.48)]">Explorer nos modèles</span>
      </button>
      <button class="px-6 py-3 bg-gray-100 hover:bg-gray-200 rounded-lg text-sm font-medium transition-colors flex items-center gap-2">
        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M3 9l9-7 9 7v11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"/><polyline points="9 22 9 12 15 12 15 22"/></svg>
        Soumission gratuite ->
      </button>
    </div>
  </div>
</section>
