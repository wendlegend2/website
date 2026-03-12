<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adidas Heritage | Since 1949</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;700;900&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; }
        .stripe-bg {
            background: linear-gradient(90deg, transparent 0%, transparent 45%, #000 45%, #000 55%, transparent 55%, transparent 100%);
            background-size: 30px 100%;
        }
        .text-outline {
            -webkit-text-stroke: 1px #fff;
            color: transparent;
        }
    </style>
</head>
<body class="bg-[#f8f8f8] text-black antialiased">

    <nav class="fixed w-full z-50 mix-blend-difference py-6 px-10 flex justify-between items-center text-white">
        <div class="text-2xl font-black tracking-tighter uppercase italic">Adidas</div>
        <ul class="flex space-x-10 text-[10px] uppercase tracking-[0.3em] font-bold">
            <li><a href="#founder" class="hover:opacity-50 transition">Founder</a></li>
            <li><a href="#1949" class="hover:opacity-50 transition">The Origin</a></li>
            <li><a href="#timeline" class="hover:opacity-50 transition">Timeline</a></li>
        </ul>
    </nav>

    <section class="relative h-screen flex items-center justify-center bg-black overflow-hidden">
        <div class="absolute inset-0 z-0">
            <img src="https://images.unsplash.com/photo-1511746015038-4f519a7c0b63?q=80&w=2070&auto=format&fit=crop" 
                 class="w-full h-full object-cover opacity-50 grayscale" alt="Adidas Background">
        </div>
        <div class="relative z-10 text-center text-white">
            <h1 class="text-7xl md:text-[10rem] font-black uppercase leading-none tracking-tighter">
                Legacy In<br><span class="text-outline">Stripes</span>
            </h1>
            <p class="mt-8 text-sm md:text-lg font-light tracking-[0.2em] uppercase opacity-70">
                Established August 18, 1949
            </p>
        </div>
        <div class="absolute bottom-10 left-1/2 -translate-x-1/2 flex space-x-2 opacity-30">
            <div class="w-[1px] h-20 bg-white"></div>
            <div class="w-[1px] h-20 bg-white"></div>
            <div class="w-[1px] h-20 bg-white"></div>
        </div>
    </section>

    <section id="founder" class="py-32 px-6 md:px-20 max-w-7xl mx-auto">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-20 items-center">
            <div class="relative">
                <div class="absolute -top-10 -left-10 text-[12rem] font-black text-gray-200 -z-10">01</div>
                <h2 class="text-5xl font-black uppercase italic mb-8">The Visionary:<br>Adi Dassler</h2>
                <p class="text-lg text-gray-600 leading-relaxed mb-6">
                    Adolf Dassler’s obsession with sports performance began in his mother’s small laundry room in Bavaria. He didn't just make shoes; he crafted instruments for athletes.
                </p>
                <p class="text-lg text-gray-600 leading-relaxed">
                    By listening to sports legends and observing their movements, he pioneered the concept of specialized footwear, ensuring every athlete had the "best for the best."
                </p>
            </div>
            <div class="grayscale hover:grayscale-0 transition-all duration-1000">
                <img src="https://images.unsplash.com/photo-1491553895911-0055eca6402d?q=80&w=2080&auto=format&fit=crop" 
                     alt="Vintage Crafting" class="shadow-2xl">
            </div>
        </div>
    </section>

    <section id="1949" class="bg-black text-white py-32 relative overflow-hidden">
        <div class="max-w-5xl mx-auto px-6 text-center">
            <h2 class="text-sm font-bold tracking-[0.5em] text-gray-500 uppercase mb-4">The Milestone</h2>
            <h3 class="text-5xl md:text-7xl font-black uppercase mb-12 italic">August 18, 1949</h3>
            <div class="h-[2px] w-24 bg-white mx-auto mb-12"></div>
            <p class="text-xl md:text-2xl font-light text-gray-400 max-w-3xl mx-auto leading-relaxed">
                After parting ways with his brother, Adi registered <span class="text-white font-bold">"Adi Dassler adidas Sportschuhfabrik"</span>. On this day, the iconic three-stripes were officially patented, forever changing the visual language of sport.
            </p>
        </div>
    </section>

    <section id="timeline" class="py-32 px-6">
        <div class="max-w-6xl mx-auto">
            <h2 class="text-center text-4xl font-black uppercase mb-20 tracking-tighter">Historical Milestones</h2>
            <div class="space-y-24">
                <div class="flex flex-col md:flex-row justify-between items-start border-b border-gray-200 pb-10">
                    <span class="text-6xl font-black italic">1924</span>
                    <div class="md:max-w-md mt-4 md:mt-0">
                        <h4 class="font-bold uppercase tracking-widest mb-2">Dassler Brothers Shoe Factory</h4>
                        <p class="text-gray-500">The humble beginnings in Herzogenaurach where the passion for athletic shoes was born.</p>
                    </div>
                </div>
                <div class="flex flex-col md:flex-row justify-between items-start border-b border-gray-200 pb-10">
                    <span class="text-6xl font-black italic">1954</span>
                    <div class="md:max-w-md mt-4 md:mt-0">
                        <h4 class="font-bold uppercase tracking-widest mb-2">The Miracle of Bern</h4>
                        <p class="text-gray-500">Germany wins the World Cup using Adidas boots with revolutionary screw-in studs.</p>
                    </div>
                </div>
                <div class="flex flex-col md:flex-row justify-between items-start border-b border-gray-200 pb-10">
                    <span class="text-6xl font-black italic">1972</span>
                    <div class="md:max-w-md mt-4 md:mt-0">
                        <h4 class="font-bold uppercase tracking-widest mb-2">The Trefoil Debut</h4>
                        <p class="text-gray-500">The iconic Trefoil logo is introduced at the Munich Olympics, symbolizing performance and lifestyle.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-white py-20 border-t border-gray-100">
        <div class="max-w-7xl mx-auto px-6 flex flex-col items-center">
            <div class="flex space-x-1 mb-10">
                <div class="w-[6px] h-12 bg-black"></div>
                <div class="w-[6px] h-12 bg-black"></div>
                <div class="w-[6px] h-12 bg-black"></div>
            </div>
            <p class="text-[10px] font-bold uppercase tracking-[0.5em] text-gray-400">
                &copy; 2026 Adidas Heritage Digital Archive.
            </p>
        </div>
    </footer>

</body>
</html>

