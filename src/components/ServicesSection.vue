<template>
  <section id="servicos">
    <!-- Service Info Cards -->
    <div class="bg-white py-16">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
          <!-- Card 1 -->
          <div class="bg-gray-50 p-8 rounded-lg text-center shadow-sm hover:shadow-md transition-shadow">
            <div class="mx-auto flex items-center justify-center h-16 w-16 rounded-full bg-moni-red bg-opacity-10 mb-6">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-moni-grey" fill="none" viewBox="0 0 24 24"
                stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                  d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z" />
              </svg>
            </div>
            <p class="text-gray-700 font-medium">Os atendimentos ocorrem uma vez por semana em um horário fixo</p>
          </div>

          <!-- Card 2 -->
          <div class="bg-gray-50 p-8 rounded-lg text-center shadow-sm hover:shadow-md transition-shadow">
            <div class="mx-auto flex items-center justify-center h-16 w-16 rounded-full bg-moni-red bg-opacity-10 mb-6">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-moni-grey" fill="none" viewBox="0 0 24 24"
                stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                  d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6v6l4 2" />
              </svg>
            </div>
            <p class="text-gray-700 font-medium">A sessão é agendada previamente e tem duração de 50 minutos</p>
          </div>

          <!-- Card 3 -->
          <div class="bg-gray-50 p-8 rounded-lg text-center shadow-sm hover:shadow-md transition-shadow">
            <div class="mx-auto flex items-center justify-center h-16 w-16 rounded-full bg-moni-red bg-opacity-10 mb-6">
              <svg xmlns="http://www.w3.org/2000/svg" class="ml-1 mt-1 h-8 w-8 text-moni-grey" fill="none"
                viewBox="0 0 24 24" stroke="currentColor" style="transform: translate(1px, 1px);">
                <!-- Larger laptop -->
                <rect x="2" y="4" width="14" height="9" rx="1" stroke-width="1.5" />
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"
                  d="M1 13h16v1a2 2 0 01-2 2H3a2 2 0 01-2-2v-1z" />
                <!-- Screen content -->
                <path stroke-linecap="round" stroke-width="1" d="M4 7h10M4 9h8M4 11h6" />

                <!-- Globe positioned to the side -->
                <circle cx="18" cy="7.5" r="3" stroke-width="1.5" />
                <path d="M18 4.5v6M15 7.5h6" stroke-width="1.2" />
                <path d="M15.5 5.5c2 1 3 1 5 0M15.5 9.5c2-1 3-1 5 0" stroke-width="1" />
              </svg>
            </div>
            <p class="text-gray-700 font-medium">Os atendimentos ocorrem via plataforma on-line de videochamada em
              qualquer lugar do mundo</p>
          </div>
        </div>
      </div>
    </div>
    <div class="bg-gray-100 mx-auto text-center py-10 md:py-20">
      <div class="w-24 h-2 bg-moni-red mb-4 mx-auto"></div>
      <h2 class="font-display font-semibold text-3xl md:text-4xl lg:text-5xl mb-0">Serviços</h2>
    </div>
    <div class="flex flex-wrap bg-black">
      <a href="/#servico-individual"
        class="bg-black relative w-full md:w-auto md:flex-1 flex items-center justify-center h-72 font-heading text-white uppercase tracking-widest hover:opacity-75">
        <div class="relative z-10">Terapia Individual</div><img src="../assets/individual.jpg"
          class="absolute inset-0 w-full h-full object-cover opacity-50">
      </a>
      <a href="/#servico-familiar"
        class="bg-black relative w-full md:w-auto md:flex-1 flex items-center justify-center h-72 font-heading text-white uppercase tracking-widest hover:opacity-75">
        <div class="relative z-10">Terapia Familiar</div><img src="../assets/familiar.jpg"
          class="absolute inset-0 w-full h-full object-cover opacity-50">
      </a>
      <a href="/#servico-casais"
        class="bg-black relative w-full md:w-auto md:flex-1 flex items-center justify-center h-72 font-heading text-white uppercase tracking-widest hover:opacity-75">
        <div class="relative z-10">Terapia de Casal</div><img src="../assets/casais.jpg"
          class="absolute inset-0 w-full h-full object-cover opacity-50">
      </a>
      <a href="/#servico-supervisao"
        class="bg-black relative w-full md:w-auto md:flex-1 flex items-center justify-center h-72 font-heading text-white uppercase tracking-widest hover:opacity-75">
        <div class="relative z-10">Supervisão de Psicólogos</div><img src="../assets/pratica.jpg"
          class="absolute inset-0 w-full h-full object-cover opacity-50">
      </a>
      <a href="/#servico-aulas"
        class="bg-black relative w-full md:w-auto md:flex-1 flex items-center justify-center h-72 font-heading text-white uppercase tracking-widest hover:opacity-75">
        <div class="relative z-10">Aulas Palestras e Workshops</div><img src="../assets/workshop.jpg"
          class="absolute inset-0 w-full h-full object-cover opacity-50">
      </a>
    </div>
  </section>
  <section id="servico-individual">
    <div class="grid grid-cols-1 md:grid-cols-2">
      <div class="md:order-first bg-gray-100 p-12 md:p-24 flex md:justify-center items-center">
        <div class="max-w-md">
          <div class="w-24 h-2 bg-moni-red mb-4"></div>
          <h2 class="font-display font-semibold text-2xl md:text-3xl lg:text-4xl mb-6">Terapia Individual</h2>
        </div>
      </div>
      <div class="bg-white p-12 md:p-24 flex justify-start">
        <p class="font-normal text-base md:text-[17px] text-gray-600 mb-6 leading-relaxed">
          A psicoterapia individual na abordagem sistêmica busca promover
          <b>autoconhecimento</b> e desenvolver formas mais saudáveis de lidar com os desafios
          da vida. O processo identifica padrões individuais e relacionais, ajudando o cliente a criar
          estratégias para enfrentar dificuldades emocionais, fortalecer vínculos e melhorar a
          qualidade de vida. A abordagem considera os diversos contextos do paciente — como
          família, relacionamentos, trabalho e estudos — para definir objetivos de mudança a partir de
          técnicas sistêmicas. É indicada para questões como <b>ansiedade, estresse, luto, baixa
            autoestima, dificuldades nos relacionamentos e tomadas de decisão</b>. Além de ajudar a
          superar desafios, oferece um espaço seguro para reflexão e crescimento pessoal,
          promovendo mudanças na forma como o indivíduo se relaciona consigo mesmo e com os
          outros. Além disso, a psicoterapia também é oferecida a brasileiros no exterior,
          considerando os desafios da experiência migratória e da adaptação cultural.
        </p>
      </div>
    </div>
  </section>
  <section id="servico-familiar">
    <div class="grid grid-cols-1 md:grid-cols-2">
      <div class="bg-gray-100 p-12 md:p-24 flex md:justify-center items-center">
        <div class="max-w-md">
          <div class="w-24 h-2 bg-moni-red mb-4"></div>
          <h2 class="font-display font-semibold text-2xl md:text-3xl lg:text-4xl mb-6">Terapia Familiar</h2>
        </div>
      </div>
      <div class="md:order-first bg-white p-12 md:p-24 flex justify-start">
        <p class="font-normal text-base md:text-[17px] text-gray-600 mb-6 leading-relaxed">
          A <b>psicoterapia familiar sistêmica</b> tem como objetivo fortalecer os vínculos e
          promover <b>relações mais saudáveis</b> entre os membros da família. Com todos os
          integrantes nas sessões, é possível identificar padrões disfuncionais, compreender suas
          origens e desenvolver estratégias conjuntas para lidar com os desafios. A terapia busca não
          só resolver conflitos, mas também criar um ambiente familiar mais harmonioso e funcional.
          É indicada para famílias com <b>conflitos recorrentes, distanciamento emocional,
            dificuldades na criação dos filhos, transições (como separações), adoecimento de um
            membro, entre outros</b>. Ao transformar as relações familiares, promove equilíbrio, bem-
          estar e maior autonomia para cada integrante.
        </p>
      </div>
    </div>
  </section>
  <section id="servico-casais">
    <div class="grid grid-cols-1 md:grid-cols-2">
      <div class="md:order-first bg-gray-100 p-12 md:p-24 flex md:justify-center items-center">
        <div class="max-w-md">
          <div class="w-24 h-2 bg-moni-red mb-4"></div>
          <h2 class="font-display font-semibold text-2xl md:text-3xl lg:text-4xl mb-6">Terapia de Casal</h2>
        </div>
      </div>
      <div class="bg-white p-12 md:p-24 flex justify-start">
        <p class="font-normal text-base md:text-[17px] text-gray-600 mb-6 leading-relaxed">
          A <b>psicoterapia de casal sistêmica</b> é indicada para casais de qualquer configuração
          ou gênero, incluindo casados, namorados, em união estável ou divorciados. O foco está em
          melhorar a dinâmica relacional, fortalecendo a comunicação, o vínculo afetivo e o
          reconhecimento das responsabilidades mútuas, sem buscar culpados. As sessões, com a
          <b>presença dos dois parceiros</b>, começam com a compreensão da história do casal e

          dos desafios enfrentados. A relação é o foco do atendimento, e não um indivíduo específico.
          Questões como <b>comunicação, conexão emocional e dinâmica conjugal ou sexual</b>
          são trabalhadas com base em técnicas fundamentadas na ciência psicológica, promovendo
          convivências mais saudáveis e satisfatórias. A terapia também acolhe casais interculturais,
          auxiliando-os a lidar com diferenças culturais, de adaptação e expectativas.
        </p>
      </div>
    </div>
  </section>
  <section id="servico-supervisao">
    <div class="grid grid-cols-1 md:grid-cols-2">
      <div class="bg-gray-100 p-12 md:p-24 flex md:justify-center items-center">
        <div class="max-w-md">
          <div class="w-24 h-2 bg-moni-red mb-4"></div>
          <h2 class="font-display font-semibold text-2xl md:text-3xl lg:text-4xl mb-6">Supervisão de Práticas
            profissionais</h2>
        </div>
      </div>
      <div class="md:order-first bg-white p-12 md:p-24 flex justify-start">
        <p class="font-normal text-base md:text-[17px] text-gray-600 mb-6 leading-relaxed">
          A <b>supervisão clínica na abordagem sistêmica</b> é fundamental para o
          desenvolvimento profissional de psicólogos. Pode ocorrer de forma pontual ou contínua,
          individualmente ou em pequenos grupos, com base em um <b>Protocolo de
            Supervisão</b> que oferece suporte teórico, técnico e emocional. Seu objetivo é apoiar o
          uso dos conceitos sistêmicos, aprimorar habilidades clínicas e fortalecer a identidade
          profissional, promovendo uma <b>prática mais segura e eficaz</b>. Além de aprofundar o
          conhecimento teórico-prático, a supervisão oferece acolhimento, previne o desgaste
          emocional e estimula a troca entre profissionais. Ao refletir sobre o self do terapeuta e
          discutir casos desafiadores, contribui para o crescimento contínuo na clínica.
        </p>
      </div>
    </div>
  </section>
  <section id="servico-aulas">
    <div class="grid grid-cols-1 md:grid-cols-2">
      <div class="md:order-first bg-gray-100 p-12 md:p-24 flex md:justify-center items-center">
        <div class="max-w-md">
          <div class="w-24 h-2 bg-moni-red mb-4"></div>
          <h2 class="font-display font-semibold text-2xl md:text-3xl lg:text-4xl mb-6">Aulas, palestras e workshops
          </h2>
        </div>
      </div>
      <div class="bg-white p-12 md:p-24 flex justify-start">
        <p class="font-normal text-base md:text-[17px] text-gray-600 mb-6 leading-relaxed">
          Aulas, palestras e workshops dinâmicos e interativos voltados para instituições de ensino e
          empresas, com temas como <b>Saúde Mental, Desenvolvimento Humano e Relações
            Familiares</b>. Utilizando <b>metodologias ativas</b>, os encontros incentivam a reflexão
          e a aplicação prática dos conteúdos no dia a dia. As atividades são personalizadas
          conforme o público, promovendo troca, aprendizado e crescimento. Ideais para capacitação,
          bem-estar no trabalho e fortalecimento das relações interpessoais, essas iniciativas visam
          gerar impacto positivo e mudanças significativas. Entre em contato e leve esse valioso
          conhecimento para sua equipe!
        </p>
      </div>
    </div>
  </section>
</template>