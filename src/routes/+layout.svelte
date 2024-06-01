<script>
    import "../app.css";
</script>

<div class="w-full min-h-screen flex flex-col justify-between items-center geist bg-black">
    <header class="h-36 md:h-60 w-full">
        <div class="w-full h-full bg-cover flex flex-col justify-end items-center" style="background-image: url('/deadlift.jpg')">
            <div class="w-full md:max-w-4xl lg:max-w-7xl text-green-600 text-5xl font-semibold p-2 flex flex-row">
                <div>RE</div>
                <div class="text-white">POWER FITNESS</div>
            </div>
        </div>
    </header>
    <content class="w-full md:max-w-4xl lg:max-w-7xl grow">
        <slot />
    </content>
    <footer class="w-full border-t border-white flex flex-col justify-center items-center">
        <div class="w-full md:max-w-4xl lg:max-w-7xl h-fit flex flex-col space-y-6 md:space-y-0 md:flex-row justify-evenly items-center py-4 text-white">
            <waitinglist class="w-1/3 md:w-2/3 h-full space-y-4 md:space-y-0 md:space-x-6 flex flex-col md:flex-row justify-center">
                <input type="email" placeholder="Inserisci la tua e-mail"
                class="w-full text-center md:text-start md:w-fit rounded-sm px-1 bg-black placeholder:text-white outline-none border-b border-b-white">
                <button class="w-full min-w-fit md:w-fit md:px-1 border-b border-b-white hover:border-b-green-700 hover:text-green-400 transition-all">Iscriviti alla waiting list</button>
            </waitinglist>
            <contacts class="w-2/3 pt-3 md:py-0 md:w-1/3 h-full flex flex-col px-4 border-t md:border-t-0 md:border-l border-white items-center justify-center transition-transform">
                <div>Schio, Via Luzio 4</div>
                <div class="">Galasso | Henstock | Stella</div>
                <div class="">RePower Gym & Fitness </div>
            </contacts>
        </div>
    </footer>
</div>