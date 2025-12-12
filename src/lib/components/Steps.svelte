<script lang="ts">
  const steps = [
    {
      num: "01",
      title: "Consultation gratuite",
      desc: "Nous évaluons votre balcon et vos besoins en sécurité. Nous vous proposons des solutions conformes adaptées à votre budget.",
      img: "https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?q=80&w=2070&auto=format&fit=crop"
    },
    {
      num: "02",
      title: "Soumission détaillée",
      desc: "Nous visitons votre propriété pour créer une proposition complète incluant matériaux, installation et garanties.",
      img: "https://images.unsplash.com/photo-1599619351208-3e6c839d6828?q=80&w=2072&auto=format&fit=crop"
    },
    {
      num: "03",
      title: "Installation certifiée",
      desc: "Notre équipe certifiée RBQ installe vos rampes selon les normes de sécurité. Vous pouvez vous détendre en toute confiance.",
      img: "https://images.unsplash.com/photo-1581094794329-cd8119608f84?q=80&w=2070&auto=format&fit=crop"
    },
    {
      num: "04",
      title: "Tranquillité d'esprit",
      desc: "En quelques jours seulement, profitez de votre balcon sécuritaire avec notre garantie complète de 10 ans.",
      img: "https://images.unsplash.com/photo-1600585154340-be6161a56a0c?q=80&w=1973&auto=format&fit=crop"
    }
  ];
</script>

<section class="bg-white py-24 px-6">
  <div class="max-w-[1200px] mx-auto">
    <h2 class="text-[40px] leading-tight font-light text-gray-900 mb-16 max-w-[600px]">
      Obtenez votre installation en quatre étapes simples. En quelques jours seulement.
    </h2>

    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 mb-16">
      {#each steps as step}
        <div class="flex flex-col">
          <div class="bg-black text-white text-xs font-bold w-8 h-8 flex items-center justify-center rounded mb-6">
            {step.num}
          </div>
          <h3 class="text-xl font-normal mb-2">{step.title}</h3>
          <p class="text-gray-500 text-sm leading-relaxed mb-6 min-h-[80px]">{step.desc}</p>
          <div class="rounded-xl overflow-hidden h-[200px] bg-gray-100">
            <img src={step.img} alt={step.title} class="w-full h-full object-cover grayscale hover:grayscale-0 transition-all duration-500" />
          </div>
        </div>
      {/each}
    </div>

    <div class="bg-[#f9f9f7] rounded-2xl p-12 flex flex-col md:flex-row items-center justify-between gap-8">
      <div>
        <h3 class="text-2xl font-light mb-2">Besoin de plus de détails?</h3>
        <p class="text-gray-500 text-sm">Découvrez notre processus d'installation rapide et professionnel.</p>
      </div>
      <div class="flex gap-4">
        <button class="px-6 py-3 bg-white border border-gray-200 hover:bg-gray-50 rounded-lg text-sm font-medium transition-colors">
          Comment ça marche
        </button>
        <button class="px-6 py-3 bg-[oklch(0.696_0.17_162.48)] hover:bg-[oklch(0.596_0.145_163.225)] text-white rounded-lg text-sm font-medium transition-colors flex items-center gap-2">
          <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
          Télécharger la brochure
        </button>
      </div>
    </div>
  </div>
</section>
