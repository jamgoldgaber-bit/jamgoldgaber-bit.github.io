<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    #h2 heading
    <title>Noosphere LLC | Molecular Neuroscience Consulting</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
    <style>
        html { scroll-behavior: smooth; }
        body { font-family: 'Inter', sans-serif; background-color: #fcfcfc; }
        h1, h2, h3 { font-family: 'Playfair Display', serif; }
        
        .bg-neuro-deep { background-color: #0D1726; }
        .text-synapse-gold { color: #C5A059; }
        
        /* Glassmorphism Header */
        .nav-glass {
            background: rgba(255, 255, 255, 0.8);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
        }

        /* Hero Parallax */
        .hero-visual {
            background: linear-gradient(rgba(13, 23, 38, 0.8), rgba(13, 23, 38, 0.8)), 
                        url('https://images.unsplash.com/photo-1559757175-7b315e340659?q=80&w=2600&auto=format&fit=crop');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
        }

        /* Animated Highlight Bar */
        .scroll-reveal {
            opacity: 0;
            transform: translateY(20px);
            transition: all 0.8s ease-out;
        }
        .scroll-reveal.visible {
            opacity: 1;
            transform: translateY(0);
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
                <a href="#impact" class="hover:text-synapse-gold transition">The Impact</a>
                <a href="#services" class="hover:text-synapse-gold transition">Expertise</a>
                <a href="#contact" class="text-neuro-deep border-b-2 border-synapse-gold pb-1">Inquiry</a>
            </div>
        </div>
    </nav>

    <header class="hero-visual h-screen flex items-center px-6">
        <div class="max-w-5xl mx-auto w-full">
            <div class="border-l-2 border-synapse-gold pl-8">
                <p class="text-synapse-gold uppercase tracking-[0.4em] text-sm mb-4 font-semibold">Stony Brook, NY</p>
                <h1 class="text-5xl md:text-8xl text-white mb-8 leading-tight">Clarity in the <br><span class="italic font-light">Molecular</span> Sphere.</h1>
                <p class="text-xl text-gray-300 max-w-xl mb-10 font-light leading-relaxed">
                    Bridging foundational neuroscience with commercial strategy. Led by the pioneer who first cloned the APP gene.
                </p>
                <a href="#services" class="inline-block bg-synapse-gold text-white px-12 py-5 rounded-sm font-bold uppercase tracking-widest hover:bg-white hover:text-neuro-deep transition duration-500 shadow-2xl">
                    View Consulting Domains
                </a>
            </div>
        </div>
    </header>

    <section class="py-12 bg-white border-b border-gray-100">
        <div class="max-w-7xl mx-auto px-6">
            <p class="text-center text-[10px] uppercase tracking-[0.3em] text-gray-400 mb-8 font-bold">Featured Research In</p>
            <div class="flex flex-wrap justify-center items-center gap-12 md:gap-24 opacity-40 grayscale">
                <span class="text-2xl font-serif italic text-neuro-deep">Nature</span>
                <span class="text-2xl font-serif font-bold text-neuro-deep">SCIENCE</span>
                <span class="text-2xl font-serif text-neuro-deep underline">Cell</span>
                <span class="text-2xl font-serif text-neuro-deep">PNAS</span>
            </div>
        </div>
    </section>

    <section id="impact" class="py-32 bg-gray-50">
        <div class="max-w-7xl mx-auto px-6">
            <div class="grid md:grid-cols-2 gap-20 items-center">
                <div>
                    <h2 class="text-4xl md:text-5xl text-neuro-deep mb-8">The APP Legacy</h2>
                    <p class="text-lg text-gray-600 leading-relaxed mb-6 font-light">
                        The cloning of the Amyloid Precursor Protein (APP) gene redefined our understanding of Alzheimer's Disease. This work allows Noosphere LLC to offer a level of technical due diligence that few can match.
                    </p>
                    <ul class="space-y-4 text-neuro-deep font-semibold">
                        <li class="flex items-center"><span class="w-1.5 h-1.5 bg-synapse-gold rounded-full mr-3"></span> Enzyme Cleavage Mechanisms</li>
                        <li class="flex items-center"><span class="w-1.5 h-1.5 bg-synapse-gold rounded-full mr-3"></span> Amyloid-Beta Aggregation Strategy</li>
                        <li class="flex items-center"><span class="w-1.5 h-1.5 bg-synapse-gold rounded-full mr-3"></span> Genetic Pathway Mapping</li>
                    </ul>
                </div>
                <div class="relative group">
                    <div class="absolute -inset-4 bg-synapse-gold/20 rounded-lg blur-2xl opacity-0 group-hover:opacity-100 transition duration-1000"></div>
                    <div class="relative bg-white p-12 rounded-lg shadow-2xl border border-gray-100">
                        <h3 class="text-6xl font-bold text-neuro-deep mb-2">1987</h3>
                        <p class="text-synapse-gold font-bold tracking-widest uppercase mb-6">Discovery Milestone</p>
                        <p class="text-gray-500 font-light leading-relaxed">
                            Professor Goldgaber leads the landmark study identifying the sequence of the protein that forms the core of Alzheimer's plaques.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="py-32 bg-neuro-deep">
        <div class="max-w-4xl mx-auto px-6 text-center">
            <h2 class="text-4xl text-white mb-6">Consultation Inquiry</h2>
            <p class="text-gray-400 mb-16 font-light">Professional advisement for Biotech, VC, and Academia.</p>
            <form class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <input type="text" placeholder="Name" class="p-4 bg-white/5 border border-white/10 rounded-sm text-white focus:border-synapse-gold outline-none">
                <input type="email" placeholder="Email" class="p-4 bg-white/5 border border-white/10 rounded-sm text-white focus:border-synapse-gold outline-none">
                <textarea placeholder="How can we assist your research or venture?" class="md:col-span-2 p-4 bg-white/5 border border-white/10 rounded-sm text-white h-40 focus:border-synapse-gold outline-none"></textarea>
                <button class="md:col-span-2 bg-white text-neuro-deep py-5 font-bold uppercase tracking-widest hover:bg-synapse-gold hover:text-white transition duration-500">Submit Request</button>
            </form>
        </div>
    </section>

    <script>
        // Simple Intersection Observer for reveal animations
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        }, { threshold: 0.1 });

        document.querySelectorAll('.scroll-reveal').forEach(el => observer.observe(el));
    </script>
</body>
</html>
