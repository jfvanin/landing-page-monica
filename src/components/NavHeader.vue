<script setup>
    import { onMounted, ref } from 'vue';

    const windowScroll = ref(0);
    const showMenu = ref(false);

    onMounted(() => {
        window.addEventListener('scroll', () => {
            windowScroll.value = window.scrollY;
        });
    });
</script>

<template>
    <div v-if="showMenu" id="menu" class="fixed z-51 inset-0 w-full h-full bg-white text-moni-brown">
        <div
            class="container h-full mx-auto px-6 py-8 relative z-52 items-center justify-center text-2xl uppercase font-semibold tracking-widest space-y-6">
            <button @click="showMenu = false" class="absolute top-0 left-0 mt-8 ml-6">
                <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                        d="M10 14l2-2m0 0l2-2m-2 2l-2-2m2 2l2 2m7-2a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                </svg>
            </button>
            <a @click="showMenu = false" href="/#home"
                class="block text-center mt-32 border-b-4 border-transparent hover:moni-brown">Home</a>
            <a @click="showMenu = false" href="/#servicos"
                class="block text-center border-b-4 border-transparent hover:moni-brown">Serviços</a>
            <a @click="showMenu = false" href="/#sobre"
                class="block text-center border-b-4 border-transparent hover:moni-brown">Sobre</a>
            <a @click="showMenu = false" href="/#faq"
                class="block text-center border-b-4 border-transparent hover:moni-brown">Dúvidas</a>
            <a @click="showMenu = false" href="/#contato"
                class="block text-center border-b-4 border-transparent hover:moni-brown">Contato</a>
        </div>
    </div>
    <div class="h-36 z-50 px-[8%] w-full fixed top-0 left-0 grid grid-cols-2 bg-amber-50/0 transition-all ease-in-out duration-700"
        :class="{ 'bg-amber-50/60 !h-24': windowScroll > 100 }">
        <div class="flex items-center h-24 md:h-auto">
            <img class="w-28 special-sm:w-64 transition-all ease-in-out duration-700"
                :class="{ '!w-32 !md:w-36': windowScroll > 100 }" src="../assets/logo2.svg" />
            <span id="logo-text" :class="{ 'visible': windowScroll > 100 }"
                class="text-sm md:text-[17px] invisible ml-4 text-moni-brown mb-1">
                MÔNICA SPERB MACHADO
            </span>
        </div>
        <div class="flex items-center h-24 md:h-auto justify-end invisible md:visible font-medium">
            <div :class="{ 'text-white [text-shadow:_0_2px_4px_black]': windowScroll <= 100 }">
                <a href="/#home"
                    class="inline-block border-b-5 p-2 px-1 lg:p-4 lg:px-3 border-transparent hover:moni-brown">Home</a>
                <a href="/#servicos"
                    class="inline-block border-b-5 p-2 px-1 lg:p-4 lg:px-3 border-transparent hover:moni-brown">Serviços</a>
                <a href="/#sobre"
                    class="inline-block border-b-5 p-2 px-1 lg:p-4 lg:px-3 border-transparent hover:moni-brown">Sobre</a>
                <a href="/#faq"
                    class="inline-block border-b-5 p-2 px-1 lg:p-4 lg:px-3 border-transparent hover:moni-brown">Dúvidas</a>
                <a href="/#contato"
                    class="inline-block border-b-5 p-2 px-1 lg:p-4 lg:px-3 border-transparent hover:moni-brown">Contato</a>
            </div>
            <button class="visible md:invisible text-moni-brown" @click="showMenu = true">
                <svg class="-mt-5 w-8 h-8 drop-shadow-lg" fill="none" stroke="currentColor" viewBox="0 0 24 24"
                    :class="{ 'text-white': windowScroll <= 100 }" xmlns="http://www.w3.org/2000/svg">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16">
                    </path>
                </svg>
            </button>
        </div>
    </div>
</template>
