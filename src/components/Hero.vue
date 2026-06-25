<template>
  <header class="max-w-4xl mx-auto px-4 pt-20 pb-16 text-center font-mono">
    <div class="inline-block border border-hacker-border px-3 py-1 text-xs text-hacker-neon bg-hacker-card mb-6">
      VERSION 1.0.0 // LIVE
    </div>
    <h1 class="text-3xl md:text-5xl font-extrabold text-white tracking-tight mb-6">
      El Editor de Texto e Identificador de Comandos <span class="text-hacker-neon">Asíncrono</span>
    </h1>
    <p class="text-base md:text-lg text-gray-400 max-w-2xl mx-auto mb-10 leading-relaxed">
      Construido en Go para ofrecer velocidad absoluta en la terminal. Edita archivos gigantes con scroll fluido y lanza procesos en segundo plano sin congelar tu entorno de trabajo.
    </p>
    <div class="flex flex-col sm:flex-row justify-center items-center gap-4 mb-16">
      <a href="#install" class="w-full sm:w-auto bg-hacker-neon text-black font-bold px-8 py-3 hover:bg-white transition-all text-center">
        [ Get_Started ]
      </a>
      <a href="https://github.com/JohansitoDev/JohaEdi" target="_blank" class="w-full sm:w-auto border border-hacker-border px-8 py-3 hover:bg-hacker-card hover:text-hacker-neon transition-all text-center text-gray-300">
        Ver en GitHub
      </a>
    </div>

    <div class="border border-hacker-border bg-black rounded shadow-2xl shadow-hacker-border/10 overflow-hidden text-left">
      <div class="bg-hacker-card border-b border-hacker-border px-4 py-2 flex items-center justify-between text-xs text-gray-500">
        <span>johan@mancebo: ~/Desktop/JohaEdit</span>
        <div class="flex space-x-1.5">
          <span class="w-2.5 h-2.5 rounded-full bg-hacker-border"></span>
          <span class="w-2.5 h-2.5 rounded-full bg-hacker-border"></span>
          <span class="w-2.5 h-2.5 rounded-full bg-hacker-neon"></span>
        </div>
      </div>
      <div class="p-4 md:p-6 text-xs md:text-sm leading-relaxed overflow-x-auto">
        <p class="text-gray-600">// El logo dinámico en bloques puros renderizado por tcell</p>
        <p class="text-hacker-neon">██████  ██████  ██   ██  ██████  ███████ ██████  ██</p>
        <p class="text-hacker-neon">    ██ ██    ██ ██   ██ ██    ██ ██      ██   ██ ██</p>
        <p class="text-hacker-neon">    ██ ██    ██ ███████ ████████ █████   ██   ██ ██</p>
        <p class="text-hacker-neon">██  ██ ██    ██ ██   ██ ██    ██ ██      ██   ██ ██</p>
        <p class="text-hacker-neon"> ████   ██████  ██   ██ ██    ██ ███████ ██████  ██</p>
        <p class="text-gray-500 mt-2"> ═╩═ JOHAEDI TERMINAL EDITOR ═╩═ </p>
        <p class="text-white mt-4"><span class="text-hacker-border">📁 src/</span> <span class="text-hacker-neon">📄 main.go</span> <span class="text-gray-500">[MODO EDICIÓN]</span></p>
        <p class="text-hacker-neon font-bold mt-2">🚀 Exec: python app.py</p>
        <p class="text-white">esta es una app python con el editor <span class="animate-ping">█</span></p>
      </div>
    </div>
  </header>
</template>