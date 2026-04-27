<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Manuscript Pro | From Draft to Published</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300;400;500;600;700&family=Instrument+Serif&display=swap');

        body {
            font-family: 'Space+Grotesk', sans-serif;
            background-color: #fcfaf7; /* Ivory Paper Texture */
            color: #1a1a1a;
            scroll-behavior: smooth;
        }

        .serif-title {
            font-family: 'Instrument Serif', serif;
        }

        /* Bold Sketch Standard Brand Styling */
        .bold-sketch-border {
            border: 3px solid #1a1a1a;
            box-shadow: 8px 8px 0px 0px #1a1a1a;
            transition: all 0.2s ease;
        }

        .bold-sketch-border:hover {
            transform: translate(-2px, -2px);
            box-shadow: 12px 12px 0px 0px #1a1a1a;
        }

        .btn-primary {
            background-color: #1a1a1a;
            color: #ffffff;
            border: 3px solid #1a1a1a;
            padding: 0.75rem 1.5rem;
            font-weight: bold;
            display: inline-block;
            transition: all 0.2s ease;
            box-shadow: 4px 4px 0px 0px #1a1a1a;
        }

        .btn-primary:hover {
            background-color: #ffffff;
            color: #1a1a1a;
            transform: translate(-2px, -2px);
            box-shadow: 6px 6px 0px 0px #1a1a1a;
        }

        .whatsapp-float {
            position: fixed;
            bottom: 30px;
            right: 30px;
            background-color: #25d366;
            color: white;
            padding: 15px;
            border: 3px solid #1a1a1a;
            box-shadow: 6px 6px 0px 0px #1a1a1a;
            z-index: 100;
            transition: all 0.2s;
        }

        .whatsapp-float:hover {
            transform: scale(1.1) rotate(-3deg);
        }

        .gradient-mesh {
            background-color: #fcfaf7;
            background-image: radial-gradient(at 0% 0%, rgba(200, 200, 200, 0.2) 0, transparent 50%), 
                              radial-gradient(at 50% 0%, rgba(150, 150, 150, 0.1) 0, transparent 50%);
        }
    </style>
</head>
<body class="gradient-mesh">

    <!-- WhatsApp Bot Link -->
    <a href="https://wa.me/2349155975173?text=Hello!%20I'm%20interested%20in%20the%20ManuscriptPro%20Founder's%20Deal." class="whatsapp-float flex items-center gap-2 font-bold" target="_blank">
        <i class="fa-brands fa-whatsapp text-2xl"></i>
        <span>Chat with Founder</span>
    </a>

    <!-- Navigation -->
    <nav class="max-w-7xl mx-auto px-6 py-8 flex justify-between items-center">
        <div class="text-2xl font-bold tracking-tighter flex items-center gap-2">
            <div class="w-8 h-8 bg-black flex items-center justify-center text-white rounded">M</div>
            MANUSCRIPTPRO
        </div>
        <div class="hidden md:flex gap-8 font-medium">
            <a href="https://manuscriptpro.online" target="_blank" class="hover:underline flex items-center gap-1">
                <i class="fa-solid fa-arrow-up-right-from-square text-xs"></i> View App
            </a>
            <a href="#features" class="hover:underline text-gray-500">How it works</a>
            <a href="#pricing" class="hover:underline font-bold">Lifetime Deal</a>
        </div>
        <a href="https://paystack.shop/pay/u6krvg7c2x" target="_blank" class="btn-primary">Secure License</a>
    </nav>

    <!-- Hero Section -->
    <header class="max-w-7xl mx-auto px-6 pt-12 pb-24 text-center">
        <span class="uppercase tracking-widest text-xs font-bold border-b-2 border-black pb-1">Built for Nigerian Authors & Coaches</span>
        <h1 class="serif-title text-6xl md:text-8xl mt-8 mb-6 leading-tight">
            From raw manuscript <br> to <span class="italic font-light text-gray-700">published perfection.</span>
        </h1>
        <p class="max-w-2xl mx-auto text-xl text-gray-600 mb-10 font-medium">
            Stop struggling with formatting. Use our intelligent <span class="text-black font-bold">Bold Sketching</span> technology to create professional, print-ready books in minutes.
        </p>
        <div class="flex flex-col md:flex-row gap-6 justify-center">
            <a href="https://paystack.shop/pay/u6krvg7c2x" target="_blank" class="btn-primary text-xl px-12 py-5">
                Join the Founding 20 — ₦37,500
            </a>
            <a href="https://manuscriptpro.online" target="_blank" class="border-3 border-black px-12 py-5 font-bold hover:bg-black hover:text-white transition-all shadow-[4px_4px_0px_0px_#1a1a1a]">
                Preview App Demo
            </a>
        </div>
        <p class="mt-6 text-sm font-bold text-gray-400 uppercase tracking-widest">Limited slots available at this launch price</p>
    </header>

    <!-- Visual Mockup Section -->
    <section id="demo" class="max-w-6xl mx-auto px-6 mb-32">
        <div class="bold-sketch-border bg-white overflow-hidden p-2">
            <div class="bg-gray-100 rounded border-2 border-black aspect-video flex items-center justify-center relative">
                <div class="text-center p-8">
                    <i class="fa-solid fa-book-open-reader text-6xl mb-4"></i>
                    <p class="font-bold text-2xl uppercase tracking-tighter">Automated Interior Design</p>
                    <p class="text-sm text-gray-500">PDF + EPUB + MOBI Export Ready</p>
                    <a href="https://manuscriptpro.online" target="_blank" class="mt-4 inline-block text-black font-bold underline">Visit Live Application</a>
                </div>
                <!-- Sketch Overlay Label -->
                <div class="absolute -top-4 -left-4 bg-black text-white p-3 font-bold transform -rotate-2 border-2 border-white">
                    PRE-LAUNCH VERSION
                </div>
                <div class="absolute -bottom-6 -right-6 bg-yellow-300 border-2 border-black p-4 font-bold transform rotate-3 shadow-lg">
                    90% DONE. FUNDING FINAL 10%
                </div>
            </div>
        </div>
    </section>

    <!-- Features -->
    <section id="features" class="bg-black text-white py-24">
        <div class="max-w-7xl mx-auto px-6 grid md:grid-cols-3 gap-12">
            <div class="border-l-2 border-gray-700 pl-6">
                <h3 class="text-2xl serif-title mb-4">The Cost Problem</h3>
                <p class="text-gray-400">Human formatters charge upwards of ₦150,000 per book. We give you that same quality for a fraction of the cost, instantly.</p>
            </div>
            <div class="border-l-2 border-gray-700 pl-6">
                <h3 class="text-2xl serif-title mb-4">Bold Architecture</h3>
                <p class="text-gray-400">Our engine uses "Bold Sketching" principles to ensure your typography, margins, and headers are perfectly balanced for print.</p>
            </div>
            <div class="border-l-2 border-gray-700 pl-6">
                <h3 class="text-2xl serif-title mb-4">Local Payments</h3>
                <p class="text-gray-400">Seamless integration with Paystack. Pay with Naira cards, Bank Transfer, or USSD to get your lifetime license.</p>
            </div>
        </div>
    </section>

    <!-- Fundraising Section -->
    <section id="pricing" class="max-w-7xl mx-auto px-6 py-32">
        <div class="grid md:grid-cols-2 gap-16 items-center">
            <div>
                <h2 class="text-5xl serif-title mb-6 leading-tight">Help us cross the <br> finish line.</h2>
                <p class="text-lg text-gray-600 mb-8">
                    We are raising ₦750,000 ($500) to finalize our cloud infrastructure. By becoming a Founding Member today, you secure <strong>Lifetime Access</strong> for a one-time payment.
                </p>
                <div class="space-y-6 mb-8">
                    <div class="flex gap-4">
                        <div class="flex-shrink-0 w-8 h-8 bg-black text-white flex items-center justify-center font-bold">1</div>
                        <p><strong>Unlimited Exports:</strong> Format as many books as you want, forever.</p>
                    </div>
                    <div class="flex gap-4">
                        <div class="flex-shrink-0 w-8 h-8 bg-black text-white flex items-center justify-center font-bold">2</div>
                        <p><strong>Priority Support:</strong> Direct WhatsApp access to the founding team.</p>
                    </div>
                    <div class="flex gap-4">
                        <div class="flex-shrink-0 w-8 h-8 bg-black text-white flex items-center justify-center font-bold">3</div>
                        <p><strong>Founder Badge:</strong> Your name listed as an early supporter in our credits.</p>
                    </div>
                </div>
            </div>
            <div class="bold-sketch-border bg-white p-10 text-center">
                <h4 class="uppercase font-black text-xs tracking-widest mb-2 text-gray-400">One-Time Founders Price</h4>
                <div class="text-7xl font-bold mb-4 tracking-tighter">₦37,500</div>
                <p class="text-sm text-gray-500 mb-8 font-bold uppercase tracking-tight">SAVE 90% OFF FUTURE SUBSCRIPTION PRICE</p>
                
                <a href="https://paystack.shop/pay/u6krvg7c2x" target="_blank" class="btn-primary w-full text-center text-xl py-5 mb-4">
                    Claim Lifetime Access <i class="fa-solid fa-arrow-right ml-2"></i>
                </a>
                
                <p class="text-xs text-gray-400 flex items-center justify-center gap-2 mt-4">
                    <i class="fa-solid fa-shield-halved"></i> Secured by Paystack
                </p>
                
                <!-- Campaign Progress -->
                <div class="mt-12 text-left border-t-2 border-black pt-8">
                    <div class="flex justify-between text-xs font-black uppercase mb-2">
                        <span>Fundraising Goal</span>
                        <span>₦187,500 / ₦750,000</span>
                    </div>
                    <div class="w-full h-6 bg-gray-100 border-2 border-black">
                        <div class="bg-black h-full" style="width: 25%"></div>
                    </div>
                    <p class="text-[10px] mt-2 font-bold uppercase text-gray-400 text-center tracking-widest italic">20 slots remaining at this price</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="border-t-[6px] border-black pt-20 pb-10 bg-white">
        <div class="max-w-7xl mx-auto px-6 grid md:grid-cols-4 gap-12 mb-20">
            <div class="col-span-2">
                <div class="text-3xl font-black tracking-tighter mb-4">MANUSCRIPTPRO</div>
                <p class="text-gray-500 max-w-xs uppercase text-[10px] font-black leading-relaxed tracking-widest">
                    Standardizing the art of the manuscript through bold sketching and architectural design. Made for authors, by authors.
                </p>
            </div>
            <div>
                <h5 class="font-bold mb-4 uppercase text-xs tracking-widest">Ecosystem</h5>
                <ul class="text-sm space-y-3 font-medium">
                    <li><a href="https://manuscriptpro.online" target="_blank" class="hover:underline">App Dashboard</a></li>
                    <li><a href="https://wa.me/2349155975173" target="_blank" class="hover:underline">WhatsApp Support</a></li>
                    <li><a href="https://paystack.shop/pay/u6krvg7c2x" target="_blank" class="hover:underline">Founder's License</a></li>
                </ul>
            </div>
            <div>
                <h5 class="font-bold mb-4 uppercase text-xs tracking-widest">Connect</h5>
                <div class="flex gap-4 text-2xl">
                    <a href="https://wa.me/2349155975173" target="_blank" class="hover:scale-110 transition-transform"><i class="fa-brands fa-whatsapp"></i></a>
                    <a href="#" class="hover:scale-110 transition-transform"><i class="fa-brands fa-linkedin-in"></i></a>
                    <a href="#" class="hover:scale-110 transition-transform"><i class="fa-brands fa-x-twitter"></i></a>
                </div>
            </div>
        </div>
        <div class="max-w-7xl mx-auto px-6 text-center text-[10px] font-black uppercase tracking-[0.3em] text-gray-400">
            &copy; 2024 ManuscriptPro Engine | Bold Sketch Standard Branding
        </div>
    </footer>

</body>
</html>
