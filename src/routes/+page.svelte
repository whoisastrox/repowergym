<script>
    import { Canvas } from '@threlte/core'
    import B from './B.svelte'

</script>

<div class="w-full flex flex-col items-center justify-center text-white pt-12 space-y-8">
    <div class="w-full text-justify text-xl px-8">
        <span class="text-green-500 text-2xl">Re</span>Power Fitness is an innovative gym that converts energy generated during exercise into clean, renewable electricity. The gym uses cable machines equipped with generators and dynamos to collect and convert energy. Excess electricity is fed back into the grid to reduce environmental impact.
    </div>
    <div class="w-full flex flex-row items-center justify-center">
        <div id="threeloader" class="bg-gray-300 w-full h-96">
            <Canvas>
                <B />
            </Canvas>
        </div>
    </div>
    <div class="w-full flex flex-col space-y-4 border-t border-t-white pt-4">
        <div class="px-4 md:px-8">
            <div class="font-bold text-2xl py-2">Your Achievement Levels</div>
            <div class="w-full flex flex-row justify-evenly space-x-4">
                <div class="w-fit space-y-2">
                    <div class="font-semibold text-orange-600">Bronze Achiever Benefits</div>
                    <ul class="list-disc">
                        <li>Exclusive Bronze Badge</li>
                        <li>10% Discount on Merchandise</li>
                        <li>Priority Access to Sustainability Workshops</li>
                    </ul>
                </div>
                <div class="w-fit space-y-2">
                    <div class="font-semibold text-gray-400">Silver Achiever Benefits</div>
                    <ul class="list-disc">
                        <li>Distinct Silver Badge</li>
                        <li>15% Discount on Gym Memberships</li>
                        <li>Exclusive fitness classes</li>
                    </ul>
                </div>
                <div class="w-fit space-y-2">
                    <div class="font-semibold text-yellow-600">Gold Achiever Benefits</div>
                    <ul class="list-disc">
                        <li>Prestigious Gold Badge</li>
                        <li>20% Discount on Gym Memberships</li>
                        <li>Free Personal Training Session</li>
                        <li>Featured Spotlight on Gym Website</li>
                        <li>VIP Access to Gym Events</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
    <img src="/pointtable.png" alt="tabella dei punti" class="w-full py-8 border-t border-t-white">
    <div class="w-full flex flex-col space-y-6 py-12 border-t border-t-white px-4 md:px-8">
        <div class="text-center font-bold text-2xl">Membership Plans</div>
        <div class="flex flex-row justify-evenly space-x-4">
            <div class="flex flex-col w-1/3">
                <div class="space-x-1.5 font-semibold">
                    Starter Fit
                    <span class="font-semibold">€29.99/mese</span>
                </div>
                <ul class="list-disc">
                    <li>Access during regular operating hours</li>
                    <li>Standard fitness equipment</li>
                    <li>Initial fitness assessment</li>
                    <li>Access to group fitness classes</li>
                </ul>
            </div>
            <div class="flex flex-col w-1/3">
                <div class="space-x-1.5 font-semibold">
                    Fit Plus
                    <span class="font-semibold">€39.99/mese</span>
                </div>
                <ul class="list-disc">
                    <li>24/7 access to gym facilities</li>
                    <li>Priority access to advanced fitness equipment</li>
                    <li>Personalized workout plans from certified trainers</li>
                    <li>Exclusive fitness workshops and events</li>
                    <li>Complementary nutritional consultation.</li>
                </ul>
            </div>
            <div class="flex flex-col w-1/3">
                <div class="space-x-1.5 font-semibold">
                    Eco Warrior
                    <span class="font-semibold">€49.99/mese</span>
                </div>
                <ul class="list-disc">
                    <li>All the benefits from the "Fit Plus" membership</li>
                    <li>Recognition as a "Green Fitness Achiever"</li>
                    <li>Additional 10% discount on merchandise</li>
                    <li>Monthly sustainability workshops and green living tips</li>
                    <li>Option to participate in community eco-projects</li>
                </ul>
            </div>
        </div>

        <div class="flex flex-col justify-center items-center">
            <div class="font-semibold">Add ons</div>
            <ul class="list-disc">
                <li>Personal Training Add-On</li>
                <li>Family/Group Discount</li>
                <li>Student Discount</li>
                <li>On-demand nutritional plans</li>
            </ul>
        </div>
    </div>

    <div class="flex flex-col pl-2 md:pl-0 px-4 md:px-8 border-t border-t-white pt-12">
        <div class="text-center font-bold text-2xl pb-4">Our <span class="text-green-500">Green</span> Systems</div>
        <div class="border-b border-b-white pt-4">
            <div class="flex flex-row">
                <texts class="flex flex-col w-1/2 px-4 border-r border-r-white justify-center">
                    <div class="w-full md:w-2/3 text-justify place-self-center pb-4">
                        The dynamo generator works like this: a coil of wire that can spin is placed near a magnet. 
                        When you spin the coil, it cuts through the magnet's magnetic field. This cutting action makes electricity flow in the wire. This electricity can then be used to power things like lights or charge a battery. 
                        In simple terms, a dynamo turns movement into electricity using magnets and spinning wire.
                        <a href="/paper.pdf" class="text-blue-600">The research paper we took inspiration from.</a> 
                    </div>
                </texts>
                <imgs class="flex flex-col w-1/2 space-y-4 justify-center items-center px-4">
                    <img src="/dynamo/image1.png" alt="dynamo mechanism 1"
                    class="w-full md:w-2/3">
                    <img src="/dynamo/image2.png" alt="dynamo mechanism 2"
                    class="w-full md:w-2/3 pb-4">
                </imgs>
            </div>
        </div>
        <div class="">
            <div class="flex flex-row">
                <texts class="flex flex-col w-1/2 px-4 pt-4 border-r border-r-white justify-center">
                    <div class="w-full md:w-2/3 text-justify place-self-center pb-4">
                        Solar panels, also known as photovoltaic panels, operate on the principle of photovoltaic effect. Composed of photovoltaic cells, these panels harness sunlight to generate electricity. When photons from sunlight strike the semiconductor material within the cells, it initiates an electron flow, creating an electric current.
                    </div>
                </texts>
                <imgs class="flex flex-col w-1/2 space-y-4 pt-4 justify-center items-center px-4">
                    <img src="/solar/panels.png" alt="solar panels"
                    class="w-full md:w-2/3 pb-4">
                </imgs>
            </div>
        </div>
        
    </div>


</div>