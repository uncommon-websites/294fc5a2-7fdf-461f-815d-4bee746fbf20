<script>
  const slides = [
    {
      image: "https://images.unsplash.com/photo-1556761175-5973dc0f32e7?q=80&w=1000&auto=format&fit=crop",
      caption: "Identifying inflection points",
      generating: true
    }
  ];
</script>

<section class="py-16 md:py-24">
  <div class="container mx-auto px-6 md:px-12">
    <div class="grid grid-cols-1 md:grid-cols-12 gap-12 items-end">
      <!-- Text Content -->
      <div class="md:col-span-5 mb-8 md:mb-0">
        <h2 class="font-display text-4xl md:text-6xl text-gray-900 mb-8 leading-tight">
          Series A/B through D.<br />
          Near inflection points.
        </h2>
        
        <div class="max-w-md">
          <p class="text-lg text-gray-600 font-light mb-6">
            We invest at the optimal balance of risk-return, targeting companies with clear paths to IPO. Our public market experience uniquely positions us to identify commercial inflection points.
          </p>
          <a href="/approach" class="text-sm text-gray-500 underline decoration-1 underline-offset-4 hover:text-black transition-colors">
            Learn our approach
          </a>
        </div>
      </div>

      <!-- Image Slider -->
      <div class="md:col-span-7">
        <div class="relative">
          <div class="aspect-[4/3] bg-gray-900 overflow-hidden">
             <img 
               src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?q=80&w=1200&auto=format&fit=crop" 
               alt="Data analysis and growth metrics"
               class="w-full h-full object-cover"
             />
             <div class="absolute bottom-4 right-4 text-xs text-white/80 font-light">
               Identifying inflection points
             </div>
          </div>
          
          <!-- Pagination Dots -->
          <div class="flex justify-center mt-6 space-x-3">
            <button class="w-1.5 h-1.5 rounded-full bg-black transition-colors" aria-label="Slide 1"></button>
            <button class="w-1.5 h-1.5 rounded-full bg-gray-300 hover:bg-gray-400 transition-colors" aria-label="Slide 2"></button>
            <button class="w-1.5 h-1.5 rounded-full bg-gray-300 hover:bg-gray-400 transition-colors" aria-label="Slide 3"></button>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
