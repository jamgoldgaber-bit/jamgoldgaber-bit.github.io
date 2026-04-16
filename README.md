<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Noosphere LLC | Molecular Neuroscience Consulting</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
    <style>
        html { scroll-behavior: smooth; }
        body { font-family: 'Inter', sans-serif; background-color: #fcfcfc; }
        h1, h2, h3 { font-family: 'Playfair Display', serif; }
        
        .bg-neuro-deep { background-color: #0D1726; }
        .text-synapse-gold { color: #C5A059; }
        .border-synapse-gold { border-color: #C5A059; }
        
        /* Glassmorphism Header Effect */
        .nav-glass {
            background: rgba(255, 255, 255, 0.8);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
        }

        /* Hero Parallax using the recommended Neural Network image */
        .hero-visual {
            background: linear-gradient(rgba(13, 23, 38, 0.8), rgba(13, 23, 38, 0.8)), 
                        url('http://googleusercontent.com/image_collection/image_retrieval/500533908182424173_0');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
        }

        /* Impact Section Background Watermark */
        .foundation-bg {
            background: linear-gradient(rgba(255, 255, 255, 0.95), rgba(255, 255, 255, 0.95)),
                        url('https://images.unsplash.com/photo-1614728894747-a83421e2b9c9?q=80&w=1000&auto=format&fit=crop');
            background-size: cover;
        }
    </style>
</head>
<body class="text-gray-900 overflow-x-hidden">

    <nav class="fixed w-full z-50 nav-glass border-b border-gray-100">
        <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
            <div class="text-xl font-bold tracking-tighter text-neuro-deep flex items-center">
                <span class="w-8 h-8 bg-neuro-deep text-white flex items-center justify-center rounded-sm mr-2 text-xs">N</span>
                NOOSPHERE LLC
            </div>
            <div class="hidden md:flex space-x-10 text-xs font-semibold uppercase tracking-widest text-gray-500">
                <a href="#impact" class="hover:text-synapse-gold transition">Scientific Legacy</a>
                <a href="#services" class="hover:text-synapse-gold transition">Expertise</a>
                <a href="#contact" class="px-4 py-2 bg-neuro-deep text-white rounded hover:bg-opacity-90 transition">Contact</a>
            </div>
        </div>
    </nav>

    <header class="hero-visual h-screen flex items-center px-6">
        <div class="max-w-5xl mx-auto w-full">
            <div class="border-l-2 border-synapse-gold pl-8">
                <p class="text-synapse-gold uppercase tracking-[0.4em] text-sm mb-4 font-semibold">Stony Brook, NY</p>
                <h1 class="text-5xl md:text-8xl text-white mb-8 leading-tight">Clarity in the <br><span class="italic font-light">Molecular</span> Sphere.</h1>
                <p class="text-xl text-gray-300 max-w-xl mb-10 font-light leading-relaxed">
                    Bridging foundational neuroscience with commercial strategy. Led by Professor Dmitry Goldgaber, the pioneer who first cloned the APP gene.
                </p>
                <div class="flex gap-4">
                    <a href="#services" class="inline-block bg-synapse-gold text-white px-8 py-4 rounded-sm font-bold uppercase tracking-widest hover:bg-white hover:text-neuro-deep transition duration-500 shadow-2xl">
                        Consulting Services
                    </a>
                </div>
            </div>
        </div>
    </header>

    <section class="py-12 bg-white border-b border-gray-100">
        <div class="max-w-7xl mx-auto px-6 text-center">
            <p class="text-[10px] uppercase tracking-[0.3em] text-gray-400 mb-8 font-bold">Featured Research In</p>
            <div class="flex flex-wrap justify-center items-center gap-12 md:gap-24 opacity-40 grayscale">
                <span class="text-2xl font-serif italic text-neuro-deep">Nature</span>
                <span class="text-2xl font-serif font-bold text-neuro-deep">SCIENCE</span>
                <span class="text-2xl font-serif text-neuro-deep underline">Cell</span>
                <span class="text-2xl font-serif text-neuro-deep">PNAS</span>
            </div>
        </div>
    </section>

    <section id="impact" class="py-32 foundation-bg relative overflow-hidden">
        <div class="max-w-7xl mx-auto px-6 relative z-10">
            <div class="grid md:grid-cols-2 gap-20 items-center">
                <div>
                    <h2 class="text-4xl md:text-5xl text-neuro-deep mb-8">The APP Gene Legacy</h2>
                    <p class="text-lg text-gray-600 leading-relaxed mb-6 font-light">
                        The cloning of the Amyloid Precursor Protein (APP) gene redefined modern understanding of Alzheimer's pathology[cite: 4]. This foundational expertise allows Noosphere LLC to provide unmatched technical due diligence and research advisory[cite: 18, 111].
                    </p>
                    <div class="p-6 border-l-4 border-synapse-gold bg-white shadow-sm italic text-gray-700">
                        "Our work provided the blueprint for understanding how enzyme cleavage produces the amyloid-beta peptides that accumulate in the brain"[cite: 4, 117].
                    </div>
                </div>
                <div class="relative group">
                    <div class="bg-neuro-deep p-12 rounded-lg shadow-2xl transform group-hover:-translate-y-2 transition duration-500">
                        <h3 class="text-6xl font-bold text-synapse-gold mb-2">1987</h3>
                        <p class="text-white font-bold tracking-widest uppercase mb-6 opacity-80">Historical Discovery</p>
                        <p class="text-gray-300 font-light leading-relaxed">
                            Professor Goldgaber leads the landmark research at Stony Brook University, successfully cloning the human APP gene[cite: 3, 4].
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="services" class="py-32 bg-gray-50 border-y border-gray-100">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center mb-20">
                <h2 class="text-4xl text-neuro-deep mb-4">Strategic Consulting</h2>
                <div class="w-24 h-1 bg-synapse-gold mx-auto"></div>
            </div>
            <div class="grid md:grid-cols-3 gap-10">
                <div class="bg-white p-10 shadow-lg border-t-4 border-neuro-deep hover:shadow-2xl transition">
                    <h3 class="text-xl font-bold mb-4 text-neuro-deep uppercase tracking-wider">Drug Strategy</h3>
                    <p class="text-gray-600 font-light">Expert navigation of the amyloid-beta pathway for pharmaceutical development and targeting[cite: 19].</p>
                </div>
                <div class="bg-white p-10 shadow-lg border-t-4 border-neuro-deep hover:shadow-2xl transition">
                    <h3 class="text-xl font-bold mb-4 text-neuro-deep uppercase tracking-wider">Research Advisory</h3>
                    <p class="text-gray-600 font-light">Mentorship for institutions and laboratories specializing in neurodegenerative disease research[cite: 20].</p>
                </div>
                <div class="bg-white p-10 shadow-lg border-t-4 border-neuro-deep hover:shadow-2xl transition">
                    <h3 class="text-xl font-bold mb-4 text-neuro-deep uppercase tracking-wider">Biotech Due Diligence</h3>
                    <p class="text-gray-600 font-light">Technical evaluation and risk assessment for investors looking at neuro-focused startups[cite: 21].</p>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="py-32 bg-neuro-deep">
        <div class="max-w-4xl mx-auto px-6 text-center">
            <h2 class="text-4xl text-white mb-8">Secure an Expert Perspective</h2>
            <p class="text-gray-400 mb-16 font-light">Inquire about bespoke consulting for industry, academia, or venture capital.</p>
            <form class="grid grid-cols-1 md:grid-cols-2 gap-6 text-left">
                <input type="text" placeholder="Full Name" class="p-4 bg-white/5 border border-white/10 rounded-sm text-white focus:border-synapse-gold outline-none transition">
                <input type="email" placeholder="Email Address" class="p-4 bg-white/5 border border-white/10 rounded-sm text-white focus:border-synapse-gold outline-none transition">
                <textarea placeholder="Briefly describe your inquiry..." class="md:col-span-2 p-4 bg-white/5 border border-white/10 rounded-sm text-white h-40 focus:border-synapse-gold outline-none transition"></textarea>
                <button type="submit" class="md:col-span-2 bg-synapse-gold text-white py-5 font-bold uppercase tracking-widest hover:brightness-110 transition shadow-xl">
                    Submit Inquiry
                </button>
            </form>
        </div>
    </section>

    <footer class="py-12 bg-white text-center text-xs text-gray-500 uppercase tracking-[0.3em]">
        &copy; 2026 Noosphere LLC. All rights reserved. | Stony Brook, New York [cite: 193]
    </footer>

</body>
</html>
