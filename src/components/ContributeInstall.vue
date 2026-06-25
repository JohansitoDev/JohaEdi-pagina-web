<template>
  <div class="max-w-5xl mx-auto px-4 font-mono">
    <section id="contribute" class="py-16 border-t border-hacker-border/40">
      <div class="border border-hacker-border bg-hacker-card p-8 text-center md:text-left md:flex justify-between items-center gap-6">
        <div class="max-w-xl">
          <h2 class="text-xl font-bold text-white mb-3 flex items-center justify-center md:justify-start gap-2">
            <span class="text-hacker-neon">🚀</span> ¿QUIERES CONTRIBUIR AL CÓDIGO?
          </h2>
          <p class="text-sm text-gray-400 leading-relaxed mb-6 md:mb-0 text-hacker-text">
            JohaEdi es un proyecto de código abierto. Si quieres proponer nuevas funciones, optimizar el viewport o reportar algún bug, eres totalmente bienvenido a dejar tu marca en el repositorio oficial.
          </p>
        </div>
        <div class="flex flex-col sm:flex-row gap-4 shrink-0 justify-center">
          <a href="https://github.com/JohansitoDev/JohaEdi/issues" target="_blank" class="border border-hacker-border bg-black px-6 py-3 text-xs font-bold text-hacker-neon hover:bg-hacker-border hover:text-white transition-all text-center">
            Reportar Issue_
          </a>
          <a href="https://github.com/JohansitoDev/JohaEdi/pulls" target="_blank" class="bg-hacker-neon text-black px-6 py-3 text-xs font-bold hover:bg-white transition-all text-center">
            Enviar Pull Request
          </a>
        </div>
      </div>
    </section>

    <section id="install" class="max-w-4xl mx-auto py-16 mb-20 border border-hacker-neon bg-hacker-card/40 text-center relative">
      <div class="absolute -top-3 left-6 bg-hacker-bg px-2 text-xs text-hacker-neon font-bold">
        [ DISTRIBUCIÓN DE CONSOLA ]
      </div>
      <h2 class="text-2xl font-bold text-white mb-4">Instalación Directa</h2>
      <p class="text-sm text-gray-400 mb-8 max-w-xl mx-auto">
        Sin ventanas pesadas de instalación gráfica. Copia y pega las instrucciones oficiales o compila directamente usando el repositorio de GitHub.
      </p>

      <div class="max-w-2xl mx-auto text-left text-xs md:text-sm">
        <div>
          <span class="block text-gray-400 mb-2">> Compilar desde el repositorio oficial:</span>
          <div class="bg-black border border-hacker-border p-4 text-gray-400 space-y-1">
            <p class="text-hacker-neon">git clone https://github.com/JohansitoDev/JohaEdi.git</p>
            <p class="text-hacker-neon">cd JohaEdi</p>
            <p class="text-hacker-neon">go build -ldflags="-s -w" -o johaedi.exe .</p>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>