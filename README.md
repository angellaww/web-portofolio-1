<!DOCTYPE html>

<html class="scroll-smooth" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Angella Merici - Portfolio</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com" rel="preconnect"/>
<link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&amp;family=Playfair+Display:wght@600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "tertiary": "#735c00",
                        "on-secondary-fixed-variant": "#34495e",
                        "tertiary-container": "#ffde80",
                        "surface-variant": "#e2e2e2",
                        "secondary": "#4b6076",
                        "surface-container-highest": "#e2e2e2",
                        "on-surface": "#1a1c1c",
                        "tertiary-fixed-dim": "#e9c349",
                        "surface-bright": "#f9f9f9",
                        "error-container": "#ffdad6",
                        "tertiary-fixed": "#ffe088",
                        "surface-container-high": "#e8e8e8",
                        "inverse-surface": "#2f3131",
                        "surface": "#f9f9f9",
                        "outline-variant": "#cfc5bc",
                        "inverse-primary": "#cdc5be",
                        "outline": "#7d766e",
                        "on-primary-container": "#68625d",
                        "surface-dim": "#dadada",
                        "on-error-container": "#93000a",
                        "inverse-on-surface": "#f0f1f1",
                        "secondary-fixed-dim": "#b3c9e2",
                        "on-primary-fixed-variant": "#4b4641",
                        "secondary-container": "#cce2fc",
                        "surface-container-low": "#f3f3f3",
                        "on-tertiary-container": "#796000",
                        "primary": "#635d58",
                        "on-background": "#1a1c1c",
                        "secondary-fixed": "#cfe5ff",
                        "background": "#f9f9f9",
                        "on-secondary-fixed": "#051d30",
                        "on-primary-fixed": "#1f1b17",
                        "primary-container": "#e8dfd8",
                        "surface-container": "#eeeeee",
                        "primary-fixed": "#eae1da",
                        "error": "#ba1a1a",
                        "on-secondary": "#ffffff",
                        "on-primary": "#ffffff",
                        "surface-container-lowest": "#ffffff",
                        "on-error": "#ffffff",
                        "on-secondary-container": "#50657b",
                        "on-tertiary-fixed-variant": "#574500",
                        "surface-tint": "#635d58",
                        "primary-fixed-dim": "#cdc5be",
                        "on-surface-variant": "#4c463f",
                        "on-tertiary-fixed": "#241a00",
                        "on-tertiary": "#ffffff"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.125rem",
                        "lg": "0.25rem",
                        "xl": "0.5rem",
                        "full": "0.75rem"
                    },
                    "spacing": {
                        "container-max": "1280px",
                        "base": "8px",
                        "margin-desktop": "64px",
                        "section-gap": "120px",
                        "gutter": "24px",
                        "margin-mobile": "16px"
                    },
                    "fontFamily": {
                        "display-lg-mobile": ["Playfair Display"],
                        "body-sm": ["Inter"],
                        "label-caps": ["Inter"],
                        "headline-md": ["Playfair Display"],
                        "body-md": ["Inter"],
                        "headline-sm": ["Playfair Display"],
                        "body-lg": ["Inter"],
                        "display-lg": ["Playfair Display"]
                    },
                    "fontSize": {
                        "display-lg-mobile": ["32px", { "lineHeight": "1.2", "fontWeight": "700" }],
                        "body-sm": ["14px", { "lineHeight": "1.5", "fontWeight": "400" }],
                        "label-caps": ["12px", { "lineHeight": "1", "letterSpacing": "0.1em", "fontWeight": "600" }],
                        "headline-md": ["32px", { "lineHeight": "1.3", "fontWeight": "600" }],
                        "body-md": ["16px", { "lineHeight": "1.6", "fontWeight": "400" }],
                        "headline-sm": ["24px", { "lineHeight": "1.4", "fontWeight": "600" }],
                        "body-lg": ["18px", { "lineHeight": "1.6", "fontWeight": "400" }],
                        "display-lg": ["48px", { "lineHeight": "1.1", "letterSpacing": "-0.02em", "fontWeight": "700" }]
                    }
                }
            }
        }
    </script>
<style>
        body {
            background-color: #f9f9f9;
        }
    </style>
</head>
<body class="bg-background text-on-background font-body-md min-h-screen flex flex-col">
<!-- TopNavBar -->
<header class="bg-surface/80 dark:bg-surface-dim/80 backdrop-blur-md full-width top-0 sticky border-b border-outline-variant/30 z-50">
<nav class="flex justify-between items-center w-full px-margin-mobile md:px-margin-desktop py-4 max-w-container-max mx-auto">
<div class="font-headline-sm text-headline-sm font-bold text-secondary dark:text-secondary-fixed">
                Angella Merici
            </div>
<div class="hidden md:flex items-center gap-gutter">
<a class="text-secondary dark:text-secondary-fixed border-b-2 border-secondary dark:border-secondary-fixed pb-1 font-label-caps text-label-caps" href="#hero">Hero</a>
<a class="text-on-secondary-fixed-variant dark:text-on-secondary-fixed-variant/70 hover:text-secondary transition-colors font-label-caps text-label-caps" href="#business">Business</a>
<a class="text-on-secondary-fixed-variant dark:text-on-secondary-fixed-variant/70 hover:text-secondary transition-colors font-label-caps text-label-caps" href="#tech">Tech</a>
<a class="text-on-secondary-fixed-variant dark:text-on-secondary-fixed-variant/70 hover:text-secondary transition-colors font-label-caps text-label-caps" href="#academic">Academic</a>
<a class="text-on-secondary-fixed-variant dark:text-on-secondary-fixed-variant/70 hover:text-secondary transition-colors font-label-caps text-label-caps" href="#contact">Contact</a>
<a class="ml-4 px-6 py-2 bg-on-secondary-fixed-variant text-on-primary font-label-caps text-label-caps rounded hover:bg-secondary transition-colors" href="#contact">Connect</a>
</div>
</nav>
</header>
<main class="flex-grow">
<!-- Hero Section -->
<section class="py-section-gap px-margin-mobile md:px-margin-desktop max-w-container-max mx-auto flex flex-col items-center text-center" id="hero">
<h1 class="font-display-lg-mobile text-display-lg-mobile md:font-display-lg md:text-display-lg text-on-secondary-fixed-variant mb-6">
                Angella Merici Nodya Pramesti Djati
            </h1>
<p class="font-body-lg text-body-lg text-on-surface-variant max-w-2xl mb-12">
                Young Entrepreneur &amp; Tech Learner. Blending a passion for high-tier business with rigorous web development studies to craft exceptional digital and physical experiences.
            </p>
<div class="flex gap-4">
<a class="px-8 py-3 bg-on-secondary-fixed-variant text-on-primary font-label-caps text-label-caps rounded hover:bg-secondary transition-colors" href="#business">
                    Lihat Portofolio
                </a>
<a class="px-8 py-3 border border-on-secondary-fixed-variant text-on-secondary-fixed-variant font-label-caps text-label-caps rounded hover:bg-primary-container transition-colors" href="#tech">
                    Aktivitas Coding
                </a>
</div>
</section>
<!-- Business Ventures -->
<section class="py-section-gap px-margin-mobile md:px-margin-desktop bg-surface-container-low" id="business">
<div class="max-w-container-max mx-auto">
<h2 class="font-headline-md text-headline-md text-on-secondary-fixed-variant mb-12 text-center">Business Ventures</h2>
<div class="mb-16">
<h3 class="font-headline-sm text-headline-sm text-on-surface-variant mb-8">Aviation Collection</h3>
<div class="grid grid-cols-1 md:grid-cols-2 gap-gutter">
<div class="bg-surface rounded-lg border border-outline-variant overflow-hidden">
<img class="w-full h-64 object-cover" data-alt="A sleek, modern private jet parked on a brightly lit tarmac at sunset. The lighting is soft and luxurious, casting long elegant shadows. The aircraft features a sophisticated white and deep slate blue livery, evoking high-end corporate travel and calm luxury." src="https://lh3.googleusercontent.com/aida-public/AB6AXuAcLF923yPVjEzFxX32h1JGv1FblfEtP720D4s1M5yJnc-a6tTcNyQBY0iToxKLHbk8wsASetsYAFUKUq0UTRTtARHSVMdCpXIGhGmKLNzLfZO2Dxr1AOYv2bx5kbvfdcpoToqu-nuFJSALmR_hbJsFfSlcMsFY0EO3vv7SgWDQieeX-MJgH1ltHQE_frtJoWi2PNmylyFFjdc2HzgXGMfpQABBuT_NRlENAmMMdkUgKZS0aAxEA55WXA"/>
<div class="p-6">
<h4 class="font-headline-sm text-headline-sm text-on-secondary-fixed-variant mb-2">Gulfstream G650ER</h4>
<p class="font-body-sm text-body-sm text-on-surface-variant">Ultra-long-range business jet featuring a custom minimalist interior with warm sand leather seats and slate blue accents. Designed for unparalleled comfort and efficiency.</p>
</div>
</div>
<div class="bg-surface rounded-lg border border-outline-variant overflow-hidden">
<img class="w-full h-64 object-cover" data-alt="The luxurious interior cabin of a private jet, featuring plush warm sand leather seats, subtle rose gold accents, and deep slate blue carpeting. The lighting is warm and inviting, highlighting the meticulous minimalist design and high-end materials." src="https://lh3.googleusercontent.com/aida-public/AB6AXuB6Q6MQMAs66pL7mR5k1UmRMlO7vTkCATEigWTz9xfg2YloDDy71rsI2v2tfgn69ad2i--pBLVXnlAucsd7y8c31xukfNqwEumoWx81CFSyNywVcWuFdXjrs2iVp6dL4ZcDHcB9l6kSCLok9NMsbExpWsL1iwr1sy8firvZlbUvDtk1DFlOYBWBxfkroZ3ToW9M6lrIZVpzTa_EISzdrG_GDqcj8ZFF5Yh1OXJGqJtAlTklPadr58PpdA"/>
<div class="p-6">
<h4 class="font-headline-sm text-headline-sm text-on-secondary-fixed-variant mb-2">Bombardier Global 7500</h4>
<p class="font-body-sm text-body-sm text-on-surface-variant">Spacious four-zone cabin configured for optimal productivity and relaxation. Incorporates advanced acoustic engineering for a tranquil in-flight experience.</p>
</div>
</div>
</div>
</div>
<div>
<h3 class="font-headline-sm text-headline-sm text-on-surface-variant mb-8">Property Portfolio</h3>
<div class="grid grid-cols-1 md:grid-cols-3 gap-gutter">
<div class="bg-surface rounded-lg border border-outline-variant overflow-hidden">
<img class="w-full h-48 object-cover" data-alt="A luxurious modern villa in Bali at twilight, featuring minimalist architecture, an infinity pool reflecting the sky, and warm ambient lighting. Surrounded by lush greenery, the property exudes calm luxury with subtle sand and slate blue tones." src="https://lh3.googleusercontent.com/aida-public/AB6AXuDz2ujxj1zUYeFyZluClbsEg5Lkdlfw5fitSeG86AyoE_tNQ314s3ZW0K8PywKw2FyASDr2ASC-hMMVd3IV6Oidjg9Le18-N2VnvAR4dmjzZvJVK5JENrW2Z9JHPHlpO9fJGtVOYrSqNwfJ05PQYTDTYcqJ0-TYuRdB4sMRDtXaBRnt0LaQREQh3qM3nS_KZbarEXZTSg3m_jSjS9Hs3J3UgvV7tFB89BJqY6h-S0_datF155QGeWenIw"/>
</div>
<div class="bg-surface rounded-lg border border-outline-variant overflow-hidden">
<img class="w-full h-48 object-cover" data-alt="An expansive living area of a high-end Bali villa, showcasing open-plan design, natural stone finishes, and minimalist furniture. The color palette focuses on warm sand, off-white, and slate blue accents, emphasizing serene sophistication." src="https://lh3.googleusercontent.com/aida-public/AB6AXuCeacAKi0sLSltzeuDfT60y7cd0Dp6-3Th4VTuMulLtkfxluAo2Gq2gPiQKSUXKumvI236DdtSoVY14L83s9cN_9eTpis2Vz7agtmAAfHLSwi8mK3Zm3JV_nmFXFcmGKnUpUGw7H8iHpX4txXiAV3Iz7MAvNiKYcA8nzBK21rY7GYFTLHZe6F7ipRwhqTqajs7eHxLZYGZD-SBw_qTVEtEZlymmo327WwGDtQoBKG_3W1mYaCyuFVTOJQ"/>
</div>
<div class="bg-surface rounded-lg border border-outline-variant overflow-hidden">
<img class="w-full h-48 object-cover" data-alt="A serene outdoor lounge area of a luxury villa, featuring elegant sunbeds beside a crystal-clear pool. The setting sun casts a soft, warm glow, highlighting the clean architectural lines and the premium, understated design aesthetic." src="https://lh3.googleusercontent.com/aida-public/AB6AXuBN7udLh1v2WD2wBwCPyxLN1kF65F4nGI39Cw3yMKjuCJA8orLrboSQRPBHNymlYlVQhhntg6lf36vTV9ePvV8-MHiQBEiqR7looMmhDT2IH1d5UuUmqpSdY5_Wn3X7sfkgpB6UW6PrgVnGeco-hokqv53ceBra0Pm39iCPRoaplu12b5CB0iRHUN2kX6k6ptNuuh1nw1uvHC2clUXqjwSwP63-Fkaro17HCzOU-ltOgVnhk317MKMdyA"/>
</div>
</div>
</div>
</div>
</section>
<!-- Tech Journey -->
<section class="py-section-gap px-margin-mobile md:px-margin-desktop max-w-container-max mx-auto" id="tech">
<h2 class="font-headline-md text-headline-md text-on-secondary-fixed-variant mb-12 text-center">Tech Journey</h2>
<div class="bg-surface rounded border border-outline-variant p-8 flex flex-col md:flex-row gap-8">
<div class="flex-1">
<h3 class="font-headline-sm text-headline-sm text-on-secondary-fixed-variant mb-4">Mastering Semantic HTML &amp; CSS</h3>
<p class="font-body-md text-body-md text-on-surface-variant mb-6">
                        Focusing on structural integrity and responsive design through fundamental web technologies. Emphasizing clean, accessible code architectures utilizing modern layout modules like Flexbox and CSS Grid.
                    </p>
<div class="bg-primary-container p-4 rounded border border-outline-variant/50">
<pre class="font-body-sm text-body-sm text-on-secondary-fixed-variant overflow-x-auto"><code>&lt;article class="card"&gt;
  &lt;header class="card-header"&gt;
    &lt;h2&gt;Semantic Structure&lt;/h2&gt;
  &lt;/header&gt;
  &lt;div class="card-body"&gt;
    &lt;p&gt;Built with purposeful markup.&lt;/p&gt;
  &lt;/div&gt;
&lt;/article&gt;</code></pre>
</div>
</div>
<div class="flex-1 bg-surface-container-low rounded border border-outline-variant p-8 flex items-center justify-center">
<div class="bg-surface border border-outline-variant rounded p-6 shadow-sm w-full max-w-sm">
<div class="h-4 bg-primary-container rounded mb-4 w-3/4"></div>
<div class="h-4 bg-primary-container rounded mb-2"></div>
<div class="h-4 bg-primary-container rounded mb-2"></div>
<div class="h-4 bg-primary-container rounded w-1/2"></div>
</div>
</div>
</div>
</section>
<!-- Academic -->
<section class="py-section-gap px-margin-mobile md:px-margin-desktop bg-surface-container-low" id="academic">
<div class="max-w-container-max mx-auto">
<div class="flex flex-col md:flex-row items-center gap-12">
<div class="w-full md:w-1/2 flex justify-center">
<div class="relative">
<div class="absolute -inset-4 border border-outline-variant/30 rounded-lg -z-10"></div>
<img alt="Angella Merici Portrait" class="w-full max-w-sm rounded-lg shadow-sm object-cover border border-outline-variant/50" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCgH6DyhwuJjIvhR2PZPoF3YoRtfmH1s2xESs8Tzfybpx9esrO2PHkjmdyXfIw-eWX-fTdEe_dSKyUNHxwysTMUcPB0LOgT_2ZvzCmnsVkcVjSmb1SZONc9ZtD6NManfxccfUaCQtpYp-6dfVjYRjZ4MvfqIhRNzRJE6MvzAdUfbK6OvYCnGF0mFy89AEAmbk8FrACNCmjyDdBtST4m6nZzolQqfNxAzh11xWuwefedgaiwpZShjFpm9A"/>
</div>
</div>
<div class="w-full md:w-1/2 text-left">
<h2 class="font-headline-md text-headline-md text-on-secondary-fixed-variant mb-6">Academic Excellence &amp; Vision</h2>
<p class="font-body-lg text-body-lg text-on-surface-variant mb-6">
Currently pursuing studies at SMA Stella Duce 1, I am dedicated to academic rigor while simultaneously navigating the demands of entrepreneurial ventures. My journey is defined by a commitment to continuous self-education in modern web development frameworks.
</p>
<p class="font-body-md text-body-md text-on-surface-variant">
My vision is to bridge the gap between high-tier business strategy and technical execution. By mastering the digital tools of tomorrow, I aim to create physical and digital experiences that resonate with elegance and purpose, staying true to the Ethos &amp; Ivory aesthetic.
</p>
</div>
</div>
</div>
</section>
<!-- Contact -->
<section class="py-section-gap px-margin-mobile md:px-margin-desktop max-w-container-max mx-auto" id="contact">
<h2 class="font-headline-md text-headline-md text-on-secondary-fixed-variant mb-12 text-center">Get in Touch</h2>
<div class="max-w-xl mx-auto">
<form class="flex flex-col gap-6">
<div>
<label class="block font-label-caps text-label-caps text-on-surface-variant mb-2" for="name">Name</label>
<input class="w-full bg-surface-bright border-b border-on-secondary-fixed-variant px-4 py-3 focus:outline-none focus:border-tertiary-fixed-dim transition-colors" id="name" placeholder="Your Name" type="text"/>
</div>
<div>
<label class="block font-label-caps text-label-caps text-on-surface-variant mb-2" for="email">Email</label>
<input class="w-full bg-surface-bright border-b border-on-secondary-fixed-variant px-4 py-3 focus:outline-none focus:border-tertiary-fixed-dim transition-colors" id="email" placeholder="your@email.com" type="email"/>
</div>
<div>
<label class="block font-label-caps text-label-caps text-on-surface-variant mb-2" for="message">Message</label>
<textarea class="w-full bg-surface-bright border border-outline-variant px-4 py-3 rounded focus:outline-none focus:border-on-secondary-fixed-variant transition-colors" id="message" placeholder="How can we collaborate?" rows="4"></textarea>
</div>
<button class="self-start px-8 py-3 bg-on-secondary-fixed-variant text-on-primary font-label-caps text-label-caps rounded hover:bg-secondary transition-colors mt-4" type="submit">
                        Send Message
                    </button>
</form>
</div>
</section>
</main>
<!-- Footer -->
<footer class="bg-surface-container-low dark:bg-surface-dim">
<div class="flex flex-col md:flex-row justify-between items-center w-full px-margin-mobile md:px-margin-desktop py-12 max-w-container-max mx-auto gap-8 border-t border-primary-container/20 dark:border-surface-container-highest/10">
<div class="font-headline-sm text-headline-sm text-secondary dark:text-secondary-fixed">
                Angella Merici
            </div>
<div class="flex gap-6">
<a class="text-on-secondary-fixed-variant hover:text-tertiary transition-colors font-label-caps text-label-caps" href="#">Privacy Policy</a>
<a class="text-on-secondary-fixed-variant hover:text-tertiary transition-colors font-label-caps text-label-caps" href="#">Terms of Service</a>
<a class="text-on-secondary-fixed-variant hover:text-tertiary transition-colors font-label-caps text-label-caps" href="#">Contact</a>
</div>
<div class="font-body-sm text-body-sm text-on-surface-variant">
                © 2024 Angella Merici Nodya Pramesti Djati. All rights reserved.
            </div>
</div>
</footer>
</body></html>
