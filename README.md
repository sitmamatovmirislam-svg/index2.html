<!-- Design System -->
<!DOCTYPE html>

<html class="light" lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;700;800&amp;family=Manrope:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "error-container": "#ffdad6",
                    "inverse-on-surface": "#eff1f4",
                    "secondary": "#006879",
                    "tertiary": "#006153",
                    "on-secondary-fixed-variant": "#004e5b",
                    "primary": "#183ce6",
                    "on-surface": "#191c1e",
                    "on-error": "#ffffff",
                    "on-primary-fixed": "#000f5d",
                    "on-surface-variant": "#444656",
                    "surface-container": "#eceef1",
                    "on-tertiary": "#ffffff",
                    "inverse-primary": "#bbc3ff",
                    "on-error-container": "#93000a",
                    "surface-container-lowest": "#ffffff",
                    "primary-container": "#3d5afe",
                    "background": "#f7f9fc",
                    "secondary-container": "#54e0fd",
                    "inverse-surface": "#2d3133",
                    "surface": "#f7f9fc",
                    "outline": "#757688",
                    "surface-variant": "#e0e3e6",
                    "on-primary-container": "#f1f0ff",
                    "on-secondary-container": "#006170",
                    "on-tertiary-fixed-variant": "#005045",
                    "tertiary-fixed": "#9bf3df",
                    "on-secondary": "#ffffff",
                    "tertiary-container": "#187b6b",
                    "error": "#ba1a1a",
                    "secondary-fixed": "#a8edff",
                    "on-primary-fixed-variant": "#002ccd",
                    "surface-bright": "#f7f9fc",
                    "surface-container-highest": "#e0e3e6",
                    "on-primary": "#ffffff",
                    "primary-fixed-dim": "#bbc3ff",
                    "surface-tint": "#2848ee",
                    "outline-variant": "#c5c5d9",
                    "surface-dim": "#d8dadd",
                    "on-tertiary-container": "#b8ffee",
                    "surface-container-high": "#e6e8eb",
                    "primary-fixed": "#dee0ff",
                    "on-background": "#191c1e",
                    "on-secondary-fixed": "#001f26",
                    "surface-container-low": "#f2f4f7",
                    "secondary-fixed-dim": "#49d7f4",
                    "tertiary-fixed-dim": "#7fd6c3",
                    "on-tertiary-fixed": "#00201b"
            },
            "borderRadius": {
                    "DEFAULT": "1rem",
                    "lg": "2rem",
                    "xl": "3rem",
                    "full": "9999px"
            },
            "fontFamily": {
                    "headline": ["Plus Jakarta Sans"],
                    "body": ["Manrope"],
                    "label": ["Manrope"]
            }
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .glass-card {
            background: rgba(255, 255, 255, 0.8);
            backdrop-filter: blur(24px);
        }
    </style>
</head>
<body class="bg-surface font-body text-on-surface">
<!-- TopAppBar -->
<nav class="fixed top-0 w-full z-50 bg-[#f7f9fc]/80 dark:bg-[#191c1e]/80 backdrop-blur-xl transition-all duration-300 ease-in-out">
<div class="flex justify-between items-center px-6 h-16 w-full max-w-7xl mx-auto">
<div class="flex items-center gap-4">
<button class="p-2 hover:bg-[#f2f4f7]/50 dark:hover:bg-[#e6e8eb]/10 rounded-full transition-all">
<span class="material-symbols-outlined text-[#183ce6] dark:text-[#3d5afe]">search</span>
</button>
</div>
<div class="font-['Plus_Jakarta_Sans'] font-bold tracking-tight text-2xl font-extrabold text-[#183ce6] dark:text-[#3d5afe]">
                Портал
            </div>
<div class="flex items-center">
<div class="w-10 h-10 rounded-full bg-primary-container flex items-center justify-center text-white font-bold overflow-hidden">
<img alt="User Avatar" class="w-full h-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBEMqudGP03UfqlFwy-WxWAbG4rTIF-gbzG3tAR5L3xcveCjhSpmk0lzqz29LSV7TYdJf647kKAzo5Oxb6r4xYhnV07wMifY9xFMqu5STp-4UwyUZMZfUPO9s4d7ZTUdAgglvNM0n6diGvdele507BJiuVfAXQHzY65Pyun6LTioo4in4SKsDzcloYh-nCiD0cW2f-oT5RhOXRrfl26jhhvOuIGdLAl-6K7SEA0_DizBUYboFcF_gOpsN8SgPVHLiK3GTqrT6LpnuKk"/>
</div>
</div>
</div>
</nav>
<main class="pt-24 pb-32 px-6 max-w-7xl mx-auto">
<!-- Hero Section -->
<header class="mb-12">
<h1 class="font-headline text-[3.5rem] font-extrabold tracking-tighter text-on-surface leading-none mb-4">
                Техно &amp; Игры
            </h1>
<p class="text-on-surface-variant text-lg max-w-2xl leading-relaxed">
                Свежие обзоры девайсов, которые делают жизнь проще, и игры, в которых хочется раствориться. Отдыхаем с умом.
            </p>
</header>
<!-- Bento Grid Layout -->
<div class="grid grid-cols-1 md:grid-cols-12 gap-6">
<!-- Featured Review: Asymmetric Span -->
<article class="md:col-span-8 group cursor-pointer">
<div class="relative overflow-hidden rounded-xl bg-surface-container-lowest transition-transform duration-300 hover:scale-[1.01]">
<div class="aspect-[16/9] w-full relative">
<img alt="Tech Review" class="w-full h-full object-cover" data-alt="Modern sleek workstation with minimalist mechanical keyboard and curved ultra-wide monitor in soft blue ambient lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBR2sSVYOru69ek0vd8JuOrqLX3qQ2eIFxGsCYGTRs8_dVMxpWtVXjHJKpkJwaDFwrsLk44nmsUlVnSzpCrIEqfC0bTWUWXznMsz7jpQ-XlUTsZuo4GiPo5JJHrp5puASludl8A1641fD-FxqRrjkMgX5UkK5m3OeZ0pudsBQObYHpp00Dk7TwnLKDTIJ6nA6CkDLdWdFknBiPY9K_uNzWu8aoSHWtqCKK3mwwzQjf6PFCs2xj5vAIWRrNZsTDD48_rQxwnrxG3Mydf"/>
<div class="absolute inset-0 bg-gradient-to-t from-black/60 via-transparent to-transparent"></div>
<div class="absolute top-6 left-6">
<span class="bg-secondary-container text-on-secondary-container px-4 py-1.5 rounded-full text-xs font-bold uppercase tracking-widest">
                                Обзор
                            </span>
</div>
</div>
<div class="p-8 glass-card absolute bottom-0 left-0 right-0 m-6 rounded-lg">
<h2 class="font-headline text-2xl font-bold mb-2 text-on-surface">Новый уровень продуктивности: Тестируем флагманский монитор</h2>
<p class="text-on-surface-variant line-clamp-2 mb-4">Почему 49 дюймов — это не роскошь, а идеальный инструмент для тех, кто ценит свой комфорт и время.</p>
<div class="flex items-center gap-4 text-sm font-semibold text-primary">
<span>Читать 8 мин</span>
<span class="material-symbols-outlined text-sm">arrow_forward</span>
</div>
</div>
</div>
</article>
<!-- Tech News Vertical Card -->
<article class="md:col-span-4 bg-surface-container-lowest rounded-xl p-6 flex flex-col justify-between">
<div>
<span class="text-tertiary font-bold text-xs uppercase tracking-widest mb-4 block">Тренды</span>
<h3 class="font-headline text-xl font-bold mb-4 leading-snug">AI больше не игрушка: Как нейросети меняют наше утро</h3>
<p class="text-on-surface-variant text-sm leading-relaxed mb-6">От умных кофеварок до персональных ассистентов, которые знают ваш график лучше вас.</p>
</div>
<div class="relative rounded-lg overflow-hidden h-48">
<img alt="AI Tech" class="w-full h-full object-cover" data-alt="Abstract visualization of neural networks glowing with cyan and deep blue light on a dark background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCVMMr_SX1hy26fRvv0CHF-nYAwiaa9WmAm7shA-6ASJCtbqhWOPzLZdvFqm0U227jL075IE4-UvOTkR4elWogMlLlAvSgWJwNaxxjASn69vObN32v7D2ITpW5Jj7QcJpwcgUUZgsMLrhSY9a3spslWLC-2Ww-Udxobtux2mbdAuYHO4bkAdGaXwPMJGz8pXTzIiucZg4PEEABjs0cORzSpkmB2jaPVpv1cIJDqfJYxeh47-mvRC2dFUBUP3wgCUZPXSfZzKeESIH2x"/>
</div>
</article>
<!-- Games Section: Masonry-style Grid -->
<div class="md:col-span-12 mt-12 mb-6">
<div class="flex justify-between items-end mb-8">
<h2 class="font-headline text-3xl font-bold tracking-tight">Релизы недели</h2>
<button class="flex items-center gap-2 text-primary font-bold hover:gap-3 transition-all">
                        Все игры <span class="material-symbols-outlined">chevron_right</span>
</button>
</div>
</div>
<!-- Game Card 1 -->
<article class="md:col-span-4 group">
<div class="bg-surface-container-low rounded-xl overflow-hidden hover:bg-surface-container-high transition-colors p-4">
<div class="rounded-lg overflow-hidden mb-4 aspect-square">
<img alt="Game Title" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500" data-alt="Cinematic shot of a mythical dragon soaring through a vibrant sunset sky over a fantasy mountain range" src="https://lh3.googleusercontent.com/aida-public/AB6AXuD2VhK7QMWGiDY_Ak5Bo1bo3XTa89cjvRiktB3VDBkxIWnKzrrOSsomKEZ9UYuGO488Bmv0Q5ZSA16ZNPJfOCG-_pS8YeaBYMcnWc1FPoGY8Rm6TnfaIyJa5MIG6XUE4C4_6KvqZL9hdBamggAfFwrDp89rhkDWFqFClIgCuVyL7P61aCyucKgYZriv4J1YX8zf4TFDlmD_nrtOkAUKIDTa9BMNgAFSclgwXtzP57QuQ-IXMfxeS8uZOr76eDx94p8gbGDI1haBa-S5"/>
</div>
<div class="flex justify-between items-start mb-2">
<h4 class="font-headline text-lg font-bold">Dragon's Wake</h4>
<span class="bg-primary/10 text-primary px-2 py-0.5 rounded text-[10px] font-bold">RPG</span>
</div>
<p class="text-on-surface-variant text-sm mb-4">Погружение в открытый мир, где каждое решение меняет климат планеты.</p>
<div class="flex items-center justify-between">
<span class="text-on-surface font-bold">9.2 / 10</span>
<button class="p-2 rounded-full bg-white text-primary shadow-sm">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">play_arrow</span>
</button>
</div>
</div>
</article>
<!-- Game Card 2 -->
<article class="md:col-span-4 group">
<div class="bg-surface-container-low rounded-xl overflow-hidden hover:bg-surface-container-high transition-colors p-4">
<div class="rounded-lg overflow-hidden mb-4 aspect-square">
<img alt="Game Title" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500" data-alt="Cyberpunk city street at night with neon signs reflecting in puddles and a sleek futuristic car" src="https://lh3.googleusercontent.com/aida-public/AB6AXuD7-xw38hiNUvd5SlvW4GhEW-VlfWI72607jTNW8GSWdZaCErFUIcYUUc-7eFqhqMW4EyekL-QlPI6V8baLr0i12TXTYieRp12oGHI_r2oHk0UZYUdf2nR--A1avmsCIhNCnbdO6E1axJYX32j9n3HoYJCnQvYMZqcQFXEFWujMmAa_2ZNz0FwCMYai_RIq7hRR5uOdYwNGQ0k-XRsj745DnWo5f5ZqRmhQkX38nvvpqiDJCHudd7l8f6IVIClbYsKwm2hfwqosCBTx"/>
</div>
<div class="flex justify-between items-start mb-2">
<h4 class="font-headline text-lg font-bold">Neon Pulse</h4>
<span class="bg-secondary/10 text-secondary px-2 py-0.5 rounded text-[10px] font-bold">Action</span>
</div>
<p class="text-on-surface-variant text-sm mb-4">Ритм-экшен в декорациях будущего, где музыка — ваше главное оружие.</p>
<div class="flex items-center justify-between">
<span class="text-on-surface font-bold">8.5 / 10</span>
<button class="p-2 rounded-full bg-white text-primary shadow-sm">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">play_arrow</span>
</button>
</div>
</div>
</article>
<!-- Game Card 3 -->
<article class="md:col-span-4 group">
<div class="bg-surface-container-low rounded-xl overflow-hidden hover:bg-surface-container-high transition-colors p-4">
<div class="rounded-lg overflow-hidden mb-4 aspect-square">
<img alt="Game Title" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500" data-alt="Collection of vintage 8-bit game consoles and colorful cartridges arranged on a wooden desk" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDrIlWThqd2mgkiTHs8fP1n0QfR3Da6hIrht2_m10nKnYrrWi-AVxAe31W9VbPY16LopuUuO323inhWF4LVy41rm-lH6tVuGDDMvIn-FolJHvgRXMX9D-K6t_HfLSpDf_J49HEwR02tV9cPC0fZZRd5Ylc1QHDYokCvaANj2pcL_HRxTkgrpXuIqvlAQUfb8JOTE2wuhpR2LRHj3fwR_bfK7PUEVUTmwOb3VC6TxyupIhxnMGsyQQmACu8D0jzzTWbp-Rsq6-Nsfwvb"/>
</div>
<div class="flex justify-between items-start mb-2">
<h4 class="font-headline text-lg font-bold">Retro Revival</h4>
<span class="bg-tertiary/10 text-tertiary px-2 py-0.5 rounded text-[10px] font-bold">Indie</span>
</div>
<p class="text-on-surface-variant text-sm mb-4">Пиксельная ностальгия, переосмысленная для современных консолей.</p>
<div class="flex items-center justify-between">
<span class="text-on-surface font-bold">8.8 / 10</span>
<button class="p-2 rounded-full bg-white text-primary shadow-sm">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">play_arrow</span>
</button>
</div>
</div>
</article>
</div>
</main>
<!-- FAB: Contextual to Tech/Games -->
<button class="fixed bottom-28 right-8 w-14 h-14 rounded-full bg-primary-container text-white shadow-xl flex items-center justify-center hover:scale-110 transition-transform z-40">
<span class="material-symbols-outlined">add</span>
</button>
<!-- BottomNavBar -->
<nav class="fixed bottom-0 left-0 w-full z-50 flex justify-around items-end px-4 pb-6 pt-2 bg-[#f7f9fc]/80 dark:bg-[#191c1e]/80 backdrop-blur-xl rounded-t-[3rem] shadow-[0_-12px_32px_rgba(25,28,30,0.06)]">
<div class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity cursor-pointer">
<span class="material-symbols-outlined mb-1">sports_soccer</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider">Спорт</span>
</div>
<div class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity cursor-pointer">
<span class="material-symbols-outlined mb-1">sports_esports</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider">Игры</span>
</div>
<!-- Active Tab: Techno (Using logic to map "Tech" to "Техно") -->
<div class="flex flex-col items-center justify-center bg-[#183ce6] text-white rounded-full p-3 scale-110 -translate-y-2 transition-transform cursor-pointer">
<span class="material-symbols-outlined mb-1">devices</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider">Техно</span>
</div>
<div class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity cursor-pointer">
<span class="material-symbols-outlined mb-1">music_note</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider">Музыка</span>
</div>
<div class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity cursor-pointer">
<span class="material-symbols-outlined mb-1">movie</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider">Кино</span>
</div>
</nav>
</body></html>

<!-- Техно и Игры -->
<!DOCTYPE html>

<html class="light" lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Спорт и Движение — Жизнь на чиле</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;700;800&amp;family=Manrope:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "error-container": "#ffdad6",
                        "inverse-on-surface": "#eff1f4",
                        "secondary": "#006879",
                        "tertiary": "#006153",
                        "on-secondary-fixed-variant": "#004e5b",
                        "primary": "#183ce6",
                        "on-surface": "#191c1e",
                        "on-error": "#ffffff",
                        "on-primary-fixed": "#000f5d",
                        "on-surface-variant": "#444656",
                        "surface-container": "#eceef1",
                        "on-tertiary": "#ffffff",
                        "inverse-primary": "#bbc3ff",
                        "on-error-container": "#93000a",
                        "surface-container-lowest": "#ffffff",
                        "primary-container": "#3d5afe",
                        "background": "#f7f9fc",
                        "secondary-container": "#54e0fd",
                        "inverse-surface": "#2d3133",
                        "surface": "#f7f9fc",
                        "outline": "#757688",
                        "surface-variant": "#e0e3e6",
                        "on-primary-container": "#f1f0ff",
                        "on-secondary-container": "#006170",
                        "on-tertiary-fixed-variant": "#005045",
                        "tertiary-fixed": "#9bf3df",
                        "on-secondary": "#ffffff",
                        "tertiary-container": "#187b6b",
                        "error": "#ba1a1a",
                        "secondary-fixed": "#a8edff",
                        "on-primary-fixed-variant": "#002ccd",
                        "surface-bright": "#f7f9fc",
                        "surface-container-highest": "#e0e3e6",
                        "on-primary": "#ffffff",
                        "primary-fixed-dim": "#bbc3ff",
                        "surface-tint": "#2848ee",
                        "outline-variant": "#c5c5d9",
                        "surface-dim": "#d8dadd",
                        "on-tertiary-container": "#b8ffee",
                        "surface-container-high": "#e6e8eb",
                        "primary-fixed": "#dee0ff",
                        "on-background": "#191c1e",
                        "on-secondary-fixed": "#001f26",
                        "surface-container-low": "#f2f4f7",
                        "secondary-fixed-dim": "#49d7f4",
                        "tertiary-fixed-dim": "#7fd6c3",
                        "on-tertiary-fixed": "#00201b"
                    },
                    "borderRadius": {
                        "DEFAULT": "1rem",
                        "lg": "2rem",
                        "xl": "3rem",
                        "full": "9999px"
                    },
                    "fontFamily": {
                        "headline": ["Plus Jakarta Sans"],
                        "body": ["Manrope"],
                        "label": ["Manrope"]
                    }
                }
            }
        }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        body { font-family: 'Manrope', sans-serif; background-color: #f7f9fc; color: #191c1e; overflow-x: hidden; }
        h1, h2, h3 { font-family: 'Plus Jakarta Sans', sans-serif; }
    </style>
</head>
<body class="bg-surface text-on-surface selection:bg-primary-container selection:text-on-primary-container">
<!-- TopAppBar -->
<header class="fixed top-0 w-full z-50 bg-[#f7f9fc]/80 dark:bg-[#191c1e]/80 backdrop-blur-xl">
<div class="flex justify-between items-center px-6 h-16 w-full max-w-7xl mx-auto">
<div class="flex items-center gap-4">
<button class="p-2 transition-all duration-300 ease-in-out hover:bg-[#f2f4f7]/50 dark:hover:bg-[#e6e8eb]/10 rounded-full">
<span class="material-symbols-outlined text-[#183ce6] dark:text-[#3d5afe]">search</span>
</button>
</div>
<div class="text-2xl font-extrabold text-[#183ce6] dark:text-[#3d5afe] font-['Plus_Jakarta_Sans'] tracking-tight">Портал</div>
<div class="flex items-center">
<div class="w-10 h-10 rounded-full bg-surface-container-highest flex items-center justify-center overflow-hidden border-2 border-primary/10">
<img class="w-full h-full object-cover" data-alt="Close up portrait of a smiling friendly person with natural lighting and soft blurred background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBSLRtq1LSWUF0jp2xFH4VoKUA5JYhqwScEttBgaS6LgdHcV2h8nGVvA01dIgGhGzIDGyQzUlo-cRS_3cWm7Z8ygGRx70zAA50GzixFjzcchYGZ3OFGDVjsEMkLysVX-BOzBuMXQ3Jd5e6rHVmwDoSKWtIXILvYgx6Ul11wAflz5fqkvIoc_hQI88w8qOcP0WdaAxvM9rEFqAhbFZxp4rRcW5EImQUxk1zmSmEHjTZcVVznj12ehoImHy3jWP3WZog-znhOyPSSp4g9"/>
</div>
</div>
</div>
</header>
<main class="pt-24 pb-32 px-4 max-w-7xl mx-auto">
<!-- Hero Section -->
<section class="relative mb-16 group">
<div class="bg-gradient-to-br from-primary to-primary-container rounded-xl overflow-hidden min-h-[500px] flex items-center relative p-8 md:p-16">
<div class="z-10 max-w-2xl">
<span class="inline-block px-4 py-1.5 bg-secondary-container text-on-secondary-container rounded-full text-xs font-bold uppercase tracking-widest mb-6">Lifestyle Focus</span>
<h1 class="text-white text-5xl md:text-7xl font-extrabold tracking-tight mb-6 leading-[1.1]">Спорт и Движение</h1>
<p class="text-on-primary-container text-lg md:text-xl leading-relaxed mb-10 opacity-90">
                        Забудьте про изнурительные тренировки. Мы здесь ради эндорфинов, прогулок в парке и радости от того, что тело просто живет. Жизнь на чиле — это когда спорт в удовольствие.
                    </p>
<div class="flex flex-wrap gap-4">
<button class="bg-white text-primary px-8 py-4 rounded-full font-bold transition-transform hover:scale-105">Начать легко</button>
<button class="bg-primary-container/20 text-white border border-white/20 backdrop-blur-md px-8 py-4 rounded-full font-bold hover:bg-white/10 transition-all">Узнать больше</button>
</div>
</div>
<div class="absolute right-0 bottom-0 top-0 w-1/2 hidden lg:block overflow-hidden rounded-l-xl">
<img class="w-full h-full object-cover opacity-80 mix-blend-lighten" data-alt="Athletic person in modern sportswear stretching in a sun-drenched studio with soft shadows and minimal aesthetic" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDswbVFZaFsyG-Z7y81w1gElsE6jjAsdgQKoYUdOUbSfGqe5uHo-e2IeQ6WlMpkgcz4f9rwfvFTm3hNQn_zyrvEyFYZHgW44hJLnmAehgg7P3RatxynsNUi1xv5xjRGuhY_iO6c5B47IzZQkDDVw75SzxPuzzJXfrG9EDAYmGAwIke7R8h4VOehD9v52vVpu2ZmO-cfvYwHSoC1rxZNPmIkYaXjX2yPo9LhCzjSQsjTEG5kCxDaqz3m3KOAZC70TZRNs7zRNXst5aCL"/>
</div>
</div>
</section>
<!-- Bento Grid Layout -->
<div class="grid grid-cols-1 md:grid-cols-12 gap-6 mb-16">
<!-- Card 1: Jogging -->
<div class="md:col-span-8 bg-surface-container-lowest rounded-xl p-8 flex flex-col md:flex-row gap-8 items-center group cursor-pointer hover:shadow-xl transition-all duration-300">
<div class="w-full md:w-1/2 aspect-video rounded-lg overflow-hidden">
<img class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-700" data-alt="Young person jogging through a scenic misty park at sunrise with soft golden rays filtering through trees" src="https://lh3.googleusercontent.com/aida-public/AB6AXuB_avTlmwImL1JbYH7Xm8bVCKGiwrWYaRoSYnfYocqIRYbqa6hXVgkHVD3oAwtLgXxrdU_CaAlW9ze12oJn6RnWYFAtVbglSicEgnbWCVnVW7gxc4q408cGEZDP9jxJE81peyaq9Da1FJeRw0RX7MfR2P7WJNAXqXlZrGFQnFMbynq3W8C-lTMBJ0JV7a9Ctk9eF6fcnnmKrUXhKGOTcqHgbSXhBLnYtcES29pfmUVIO1JYS5iznngZ7uhdGLvKgYndaepnNtM68vhn"/>
</div>
<div class="w-full md:w-1/2">
<h3 class="text-2xl font-bold mb-4 text-on-surface">Бег без одышки</h3>
<p class="text-on-surface-variant leading-relaxed mb-6">Как превратить утреннюю пробежку в медитацию, а не в пытку. Секреты темпа, который приносит радость.</p>
<div class="flex items-center gap-2 text-primary font-bold">
<span>Читать статью</span>
<span class="material-symbols-outlined">arrow_forward</span>
</div>
</div>
</div>
<!-- Card 2: Gym Vibes -->
<div class="md:col-span-4 bg-tertiary-container rounded-xl p-8 flex flex-col justify-between text-white relative overflow-hidden group">
<div class="absolute top-0 right-0 p-4 opacity-20">
<span class="material-symbols-outlined text-8xl" style="font-variation-settings: 'FILL' 1;">fitness_center</span>
</div>
<div class="relative z-10">
<h3 class="text-2xl font-bold mb-4">Тренажерка для души</h3>
<p class="opacity-80 mb-8">Почему 20 минут веса лучше часа кардио, если ваша цель — просто чувствовать себя бодро.</p>
</div>
<button class="bg-white/20 backdrop-blur-xl border border-white/30 p-4 rounded-full w-fit group-hover:bg-white group-hover:text-tertiary-container transition-all">
<span class="material-symbols-outlined">add</span>
</button>
</div>
<!-- Card 3: Well-being Chips/Tags -->
<div class="md:col-span-4 bg-surface-container-low rounded-xl p-8">
<h3 class="text-xl font-bold mb-6">Что сегодня?</h3>
<div class="flex flex-wrap gap-3">
<span class="px-6 py-3 bg-secondary-container text-on-secondary-container rounded-full text-sm font-semibold cursor-pointer hover:opacity-80 transition-opacity">Йога</span>
<span class="px-6 py-3 bg-white text-on-surface-variant rounded-full text-sm font-semibold border border-outline-variant/20 shadow-sm cursor-pointer hover:bg-secondary-container transition-all">Бадминтон</span>
<span class="px-6 py-3 bg-white text-on-surface-variant rounded-full text-sm font-semibold border border-outline-variant/20 shadow-sm cursor-pointer hover:bg-secondary-container transition-all">Плавание</span>
<span class="px-6 py-3 bg-white text-on-surface-variant rounded-full text-sm font-semibold border border-outline-variant/20 shadow-sm cursor-pointer hover:bg-secondary-container transition-all">Велосипед</span>
<span class="px-6 py-3 bg-white text-on-surface-variant rounded-full text-sm font-semibold border border-outline-variant/20 shadow-sm cursor-pointer hover:bg-secondary-container transition-all">Растяжка</span>
</div>
</div>
<!-- Card 4: Video Insight (Asymmetric) -->
<div class="md:col-span-8 relative rounded-xl overflow-hidden bg-on-surface">
<img class="w-full h-full object-cover opacity-50" data-alt="High angle view of a yoga mat and water bottle on a clean wooden floor in a bright minimalist studio" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAcqk7oIaZwaSCrGu3HsAnJ7GZnorAATaIlFYzt0XjPBGQ-lK17FNFnamEICh6XpaZ7pkFEA2d9brYgTfsuFYdeJhFJjA2qWwQekxPwqzBCGZcbQ2GJ62sgyQPPqm-uZeR4yf-QSNWonTyDv_fE1RrFAX-q6c4w4RfqBmq6wLiCnKQ7fv7cDZwmvIpdp8Bt9JsxjbfrRgT7L-gC0YrQw0N7K05OrsrBibrlCE1QZtzZSxLswTu6MgiHMaXRaKuesadc5v_g_EVCE6fJ"/>
<div class="absolute inset-0 p-8 flex flex-col justify-end">
<div class="flex items-center gap-4 mb-4">
<div class="w-16 h-16 bg-primary rounded-full flex items-center justify-center text-white shadow-lg cursor-pointer hover:scale-110 transition-transform">
<span class="material-symbols-outlined text-4xl" style="font-variation-settings: 'FILL' 1;">play_arrow</span>
</div>
<div>
<p class="text-white font-bold text-xl">5 минут для спины</p>
<p class="text-white/70 text-sm">Короткий комплекс для тех, кто много сидит</p>
</div>
</div>
</div>
</div>
</div>
<!-- Quote / Editorial Block -->
<section class="my-20 text-center max-w-3xl mx-auto">
<span class="material-symbols-outlined text-secondary text-5xl mb-6">format_quote</span>
<h2 class="text-3xl md:text-4xl font-bold text-on-surface leading-tight mb-8">
                «Движение — это не долг перед зеркалом, а подарок своему настроению».
            </h2>
<div class="h-1 w-20 bg-secondary mx-auto rounded-full"></div>
</section>
<!-- Newsletter / Community Section (Glassmorphism) -->
<section class="relative bg-surface-container-high rounded-xl p-8 md:p-12 overflow-hidden">
<div class="relative z-10 grid md:grid-cols-2 gap-12 items-center">
<div>
<h2 class="text-3xl font-bold mb-4">Присоединяйтесь к движению чилла</h2>
<p class="text-on-surface-variant text-lg">Получайте еженедельные подборки легких активностей и советы по восстановлению сил.</p>
</div>
<div class="flex flex-col sm:flex-row gap-4">
<input class="flex-grow bg-white border-none rounded-full px-6 py-4 focus:ring-2 focus:ring-primary text-on-surface" placeholder="Ваш e-mail" type="email"/>
<button class="bg-primary text-white font-bold px-8 py-4 rounded-full shadow-lg shadow-primary/20 hover:translate-y-[-2px] transition-all">Подписаться</button>
</div>
</div>
<!-- Decorative circle -->
<div class="absolute -top-24 -right-24 w-64 h-64 bg-secondary/10 rounded-full blur-3xl"></div>
</section>
</main>
<!-- BottomNavBar -->
<nav class="fixed bottom-0 left-0 w-full z-50 flex justify-around items-end px-4 pb-6 pt-2 bg-[#f7f9fc]/80 dark:bg-[#191c1e]/80 backdrop-blur-xl shadow-[0_-12px_32px_rgba(25,28,30,0.06)] rounded-t-[3rem]">
<a class="flex flex-col items-center justify-center bg-[#183ce6] text-white rounded-full p-3 scale-110 -translate-y-2 transition-transform" href="#">
<span class="material-symbols-outlined">sports_soccer</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Спорт</span>
</a>
<a class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity" href="#">
<span class="material-symbols-outlined">sports_esports</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Игры</span>
</a>
<a class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity" href="#">
<span class="material-symbols-outlined">devices</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Техно</span>
</a>
<a class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity" href="#">
<span class="material-symbols-outlined">music_note</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Музыка</span>
</a>
<a class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity" href="#">
<span class="material-symbols-outlined">movie</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Кино</span>
</a>
</nav>
</body></html>
<!-- Design System -->
<!DOCTYPE html>

<html class="light" lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@700;800&amp;family=Manrope:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "error-container": "#ffdad6",
                        "inverse-on-surface": "#eff1f4",
                        "secondary": "#006879",
                        "tertiary": "#006153",
                        "on-secondary-fixed-variant": "#004e5b",
                        "primary": "#183ce6",
                        "on-surface": "#191c1e",
                        "on-error": "#ffffff",
                        "on-primary-fixed": "#000f5d",
                        "on-surface-variant": "#444656",
                        "surface-container": "#eceef1",
                        "on-tertiary": "#ffffff",
                        "inverse-primary": "#bbc3ff",
                        "on-error-container": "#93000a",
                        "surface-container-lowest": "#ffffff",
                        "primary-container": "#3d5afe",
                        "background": "#f7f9fc",
                        "secondary-container": "#54e0fd",
                        "inverse-surface": "#2d3133",
                        "surface": "#f7f9fc",
                        "outline": "#757688",
                        "surface-variant": "#e0e3e6",
                        "on-primary-container": "#f1f0ff",
                        "on-secondary-container": "#006170",
                        "on-tertiary-fixed-variant": "#005045",
                        "tertiary-fixed": "#9bf3df",
                        "on-secondary": "#ffffff",
                        "tertiary-container": "#187b6b",
                        "error": "#ba1a1a",
                        "secondary-fixed": "#a8edff",
                        "on-primary-fixed-variant": "#002ccd",
                        "surface-bright": "#f7f9fc",
                        "surface-container-highest": "#e0e3e6",
                        "on-primary": "#ffffff",
                        "primary-fixed-dim": "#bbc3ff",
                        "surface-tint": "#2848ee",
                        "outline-variant": "#c5c5d9",
                        "surface-dim": "#d8dadd",
                        "on-tertiary-container": "#b8ffee",
                        "surface-container-high": "#e6e8eb",
                        "primary-fixed": "#dee0ff",
                        "on-background": "#191c1e",
                        "on-secondary-fixed": "#001f26",
                        "surface-container-low": "#f2f4f7",
                        "secondary-fixed-dim": "#49d7f4",
                        "tertiary-fixed-dim": "#7fd6c3",
                        "on-tertiary-fixed": "#00201b"
                    },
                    "borderRadius": {
                        "DEFAULT": "1rem",
                        "lg": "2rem",
                        "xl": "3rem",
                        "full": "9999px"
                    },
                    "fontFamily": {
                        "headline": ["Plus Jakarta Sans"],
                        "body": ["Manrope"],
                        "label": ["Manrope"]
                    }
                },
            },
        }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .hide-scrollbar::-webkit-scrollbar { display: none; }
        .hide-scrollbar { -ms-overflow-style: none; scrollbar-width: none; }
    </style>
</head>
<body class="bg-surface font-body text-on-surface selection:bg-primary-container selection:text-on-primary-container">
<!-- TopAppBar -->
<header class="bg-[#f7f9fc]/80 dark:bg-[#191c1e]/80 backdrop-blur-xl fixed top-0 w-full z-50 transition-all duration-300 ease-in-out">
<div class="flex justify-between items-center px-6 h-16 w-full max-w-7xl mx-auto">
<div class="flex items-center gap-4">
<button class="p-2 text-[#191c1e] dark:text-[#f2f4f7] hover:bg-[#f2f4f7]/50 dark:hover:bg-[#e6e8eb]/10 rounded-full transition-all">
<span class="material-symbols-outlined" data-icon="search">search</span>
</button>
<h1 class="text-2xl font-extrabold text-[#183ce6] dark:text-[#3d5afe] font-['Plus_Jakarta_Sans'] tracking-tight">Портал</h1>
</div>
<nav class="hidden md:flex gap-8">
<a class="font-['Plus_Jakarta_Sans'] font-bold tracking-tight text-[#183ce6] dark:text-[#3d5afe] transition-all" href="#">Спорт</a>
<a class="font-['Plus_Jakarta_Sans'] font-bold tracking-tight text-[#191c1e] dark:text-[#f2f4f7] opacity-70 hover:opacity-100 transition-all" href="#">Игры</a>
<a class="font-['Plus_Jakarta_Sans'] font-bold tracking-tight text-[#191c1e] dark:text-[#f2f4f7] opacity-70 hover:opacity-100 transition-all" href="#">Техно</a>
<a class="font-['Plus_Jakarta_Sans'] font-bold tracking-tight text-[#191c1e] dark:text-[#f2f4f7] opacity-70 hover:opacity-100 transition-all" href="#">Музыка</a>
<a class="font-['Plus_Jakarta_Sans'] font-bold tracking-tight text-[#191c1e] dark:text-[#f2f4f7] opacity-70 hover:opacity-100 transition-all" href="#">Кино</a>
</nav>
<div class="flex items-center gap-2">
<div class="w-10 h-10 rounded-full bg-primary-container overflow-hidden ring-2 ring-surface">
<img alt="User" data-alt="close-up portrait of a young man with a friendly smile, natural lighting, soft urban background bokeh" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAKum0n9ounuJKQqHwd5LHIagTBqviqU-kZwmcznPFGIWINxEQIggylweQPvlDSVIJkySA-YA-S0C-kHpv2XBCimDvPgLr3vvLi_UZnhjr4IrwTXmoXpl33TBXfs5F4CnHkLDyTJaNQPl_u2BCB-QeAeQq7EgHt0O-yJEnn_rizDrHySeO3mfDxYYW-3GzZYEFzfn1H2WrN6QzYfqq_38xV0tLk9J_8JKVuWFMGtYwBbZtSCpqTroTjOeP95jUQvqx5qUhd8hHs7g28"/>
</div>
</div>
</div>
</header>
<main class="pt-24 pb-32 max-w-7xl mx-auto px-6">
<!-- Hero Section -->
<section class="mb-12">
<h2 class="text-[3.5rem] font-headline font-extrabold leading-[1.1] mb-8 tracking-tighter text-primary">Главная</h2>
<!-- Bento Grid Trends -->
<div class="grid grid-cols-1 md:grid-cols-4 grid-rows-2 gap-6 h-auto md:h-[600px]">
<!-- Main Featured Card -->
<div class="md:col-span-2 md:row-span-2 relative group overflow-hidden rounded-xl bg-surface-container-lowest transition-transform hover:scale-[1.01]">
<img class="absolute inset-0 w-full h-full object-cover" data-alt="serene person practicing yoga on a sunlit balcony overlooking a misty morning forest, peaceful atmosphere, soft sunlight" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAbp-c8PI8NSe6CDcrGQir8NIewujDFVtSIU2RW4i_cv9fwt94eO7NShRneOxOKxzTLfyb6tSw6GKOqG5jpTRudE95d4wsh1gpZ44B3Phipl6CXTkX1BQi2zqXUwtSqHrZxIn4McAegiqKE6PW9uPx6I6E_4hhG9nGTr-dx9BGxFu8OZE6m8WZh9V4d4k4cEAo-xbsb4wNg4Fp1pzjAUvqPQVYjO-_kllCRn4QbfwZ7kcXy5bmVHU9W_Dl19got2Tevwdnht-JPKlzH"/>
<div class="absolute inset-0 bg-gradient-to-t from-primary/80 via-transparent to-transparent"></div>
<div class="absolute bottom-0 p-8">
<span class="inline-block px-4 py-1 mb-4 rounded-full bg-secondary-container text-on-secondary-container font-label text-xs font-bold tracking-widest uppercase">Тренды</span>
<h3 class="text-3xl font-headline font-bold text-white mb-2 leading-tight">Искусство замедления: как найти свой дзен в мегаполисе</h3>
<p class="text-white/80 font-body text-sm max-w-md">Путеводитель по самым тихим местам и техникам осознанности для тех, кто устал от суеты.</p>
</div>
</div>
<!-- Secondary Trend 1 -->
<div class="md:col-span-2 md:row-span-1 relative group overflow-hidden rounded-xl bg-surface-container-lowest">
<img class="absolute inset-0 w-full h-full object-cover" data-alt="vibrant abstract close-up of a vinyl record spinning with colorful light reflections, retro-modern aesthetic, energetic mood" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCQ3JX_L9ESrCLFD5k0BrYiNrC7kPSZxmZ3_XdDvHSXf4kWFXDuHhOVg1gRHrIUcM2ckf-PIsHTnu34tEviTc4iFBeKl8KcDCKI9UKzVOG4YiHBSY8OcyUfW-TBe-aYUPFy0fgRIyskEvfKtAWSs-5NE2BJInDbkA_6oj2URE1II02ZhGxpqlhZmtarQY-F-NgrbMkJ2jwNZ8__Oz-yrUoWR1HeRHz5aCvEslw_u707AYLvitOpzOy1m1-08tfqUkX012pkrttZY6nX"/>
<div class="absolute inset-0 bg-gradient-to-r from-[#006153]/90 via-[#006153]/40 to-transparent"></div>
<div class="absolute inset-0 p-6 flex flex-col justify-end">
<h3 class="text-xl font-headline font-bold text-white">Виниловый ренессанс</h3>
</div>
</div>
<!-- Secondary Trend 2 -->
<div class="md:col-span-1 md:row-span-1 relative group overflow-hidden rounded-xl bg-surface-container-lowest">
<img class="absolute inset-0 w-full h-full object-cover" data-alt="high-tech gaming setup with glowing neon teal and indigo lights, sleek hardware, futuristic atmospheric lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDSX8f4i0M_VJrmJx6VHfVT7t5QpgNXh-qogJJYV0IqIqAP2RYcisOSFE4j0UH1SQDAw2MxxXr5V7jCCfufYBAM98li6y6mO4nzQzTYF0v7m0qBa4WT_FhzcJU0FApCaMqltPEB895HM2x3OsAiyZ9rJPxR-gMMbPOlTDpuT2yvZAz6MAHICGVObwM1jFM3xV6nhA50H9cNZ03woq6FbSKYqze_f7JJ0jFxk4mal4M2v7xGvq2-uVAUt7ntTwSOzkjgDyYb5TNvvlIY"/>
<div class="absolute inset-0 bg-gradient-to-t from-[#183ce6]/80 to-transparent"></div>
<div class="absolute bottom-0 p-6">
<h3 class="text-lg font-headline font-bold text-white">Киберспорт 2024</h3>
</div>
</div>
<!-- Secondary Trend 3 -->
<div class="md:col-span-1 md:row-span-1 relative group overflow-hidden rounded-xl bg-surface-container-lowest">
<img class="absolute inset-0 w-full h-full object-cover" data-alt="gourmet healthy breakfast spread on a white wooden table, bright morning light, fresh ingredients, minimalist aesthetic" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCHApM8hcJSMppt1AQWSZG4w7aC8G1gAASu4HssgDTiHHPb5S9WeD-DQxJQhQ7POrBSUaI3TSWKLBrVy6yVmUos-uJnA2EYEiJ3HNICFzd-G3pn_vDTyyZL5cfAm5flluZeWRqJqIaP4FQEAOXl5EBXXDk9LzxEboMRoZOcfxDqYIgZIdx0BfqfaTDtCAEUSUuvT5B0ThXWYuGZWBUqYwU4qIdKsZ8mx-T5RD0uWbKsEeskPnvafa72jvzxcT8T5gjc0LLv3cPyHcJu"/>
<div class="absolute inset-0 bg-gradient-to-t from-[#006879]/80 to-transparent"></div>
<div class="absolute bottom-0 p-6">
<h3 class="text-lg font-headline font-bold text-white">Завтраки будущего</h3>
</div>
</div>
</div>
</section>
<!-- New in Tech Section -->
<section class="mb-16">
<div class="flex justify-between items-end mb-8">
<div>
<h2 class="text-2xl font-headline font-bold text-on-surface">Новое в техно</h2>
<div class="h-1 w-12 bg-secondary mt-2 rounded-full"></div>
</div>
<button class="text-primary font-label text-sm font-bold flex items-center gap-1 hover:gap-2 transition-all">
                    Смотреть всё <span class="material-symbols-outlined text-sm">arrow_forward</span>
</button>
</div>
<div class="grid grid-cols-1 md:grid-cols-3 gap-8">
<article class="bg-surface-container-lowest rounded-xl p-4 transition-all hover:bg-surface-container-low group">
<div class="relative h-48 mb-4 overflow-hidden rounded-lg">
<img class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110" data-alt="close-up of a sleek minimalist smartphone with high-end camera lenses, reflections of soft studio lights, professional product photography" src="https://lh3.googleusercontent.com/aida-public/AB6AXuACzaLvWILkI-vopShSttB04Th1wNrQeKaGe0EtAibrsMEFkjKzhn_XwyVC0g6v4l-D7E9g0wqIYxK5Y1sQtO6O0-pErxGUxPjqCkkqidaOFauVacNqp1dqlNWep3w5zTpCxA3XmYM1YB_Z2xSQ2fg0wNKieKsD7y-wOE5oaCFaxTbYryNuPmSpDBdbHvTT0iuvOWm3QQkWz7QyY32XxJ6j2wbJ1uGA63jzlIh1VjIPyke5yWiiG4_fu9XVNxUU9frfj2szRLw5FBGu"/>
</div>
<div class="flex items-center gap-2 mb-2 text-on-surface-variant font-label text-xs font-semibold uppercase tracking-wider">
<span class="material-symbols-outlined text-sm">memory</span>
<span>Гаджеты</span>
</div>
<h4 class="text-xl font-headline font-bold mb-2">Почему ваш следующий смартфон будет прозрачным?</h4>
<p class="text-on-surface-variant font-body text-sm line-clamp-2">Разбираемся в новых технологиях дисплеев и материалах будущего.</p>
</article>
<article class="bg-surface-container-lowest rounded-xl p-4 transition-all hover:bg-surface-container-low group">
<div class="relative h-48 mb-4 overflow-hidden rounded-lg">
<img class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110" data-alt="abstract visualization of artificial intelligence neural networks, glowing cyan nodes and data streams, dark futuristic background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCgKQL9TutZDNByOTkzwag9zDtDqVrS0wIbJ1rAl0mxpfeeAGaxPBEGvvQM2CFvrGrevO2dKRgwmbbv0QPHYZJ3t9N6UjaMwudTpnqut-XcN1gCYYblijmP7DHa7HuZ28dWcR0n1rFKOx8p1cC7B2f6TFVR-oXNxiu9E4tLIsFestfFn3Bj4Xh9nk-yPGzWop9XLEMDQIWH3KyfDFo_MUS2nIpM_8t0jKVs6R6_OVY558-teQfoWtDTYF5j8dY9THvky991XDB-EvxM"/>
</div>
<div class="flex items-center gap-2 mb-2 text-on-surface-variant font-label text-xs font-semibold uppercase tracking-wider">
<span class="material-symbols-outlined text-sm">smart_toy</span>
<span>AI тренды</span>
</div>
<h4 class="text-xl font-headline font-bold mb-2">Нейросети на чиле: отдых с помощью ИИ</h4>
<p class="text-on-surface-variant font-body text-sm line-clamp-2">Как делегировать рутину алгоритмам и освободить время для жизни.</p>
</article>
<article class="bg-surface-container-lowest rounded-xl p-4 transition-all hover:bg-surface-container-low group">
<div class="relative h-48 mb-4 overflow-hidden rounded-lg">
<img class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110" data-alt="person using a digital tablet at a wooden cafe table, soft natural light, cozy atmosphere, productive yet relaxed mood" src="https://lh3.googleusercontent.com/aida-public/AB6AXuB42wxmv21nGnzxDGKukOyjhWBZs_CWz-H0oQEqha9BplnYiNpqxtkWZPAt0Z45DYu-4sqFU7mSl8c7_aHD4xJhc8GC2l02rf2MByAgaba3s0wpSAxeBcCBn6G6up1pkeB648fJV48HRMLmasmlXQ4bn_38rsZ3-eGzdKSGofaT9RhevfZIQ4l69eWdIJe9Z1xbAhffFcBB0gA0WLGc6mbLcFp4meTyUgKImTPAZDQalr_6NFsGoPl6MkDudJxIgtEgzRYFOxjjqLZO"/>
</div>
<div class="flex items-center gap-2 mb-2 text-on-surface-variant font-label text-xs font-semibold uppercase tracking-wider">
<span class="material-symbols-outlined text-sm">work_history</span>
<span>Продуктивность</span>
</div>
<h4 class="text-xl font-headline font-bold mb-2">Цифровой детокс без вреда для карьеры</h4>
<p class="text-on-surface-variant font-body text-sm line-clamp-2">Практические советы по ограничению экранного времени.</p>
</article>
</div>
</section>
<!-- What to Listen Section -->
<section class="mb-16">
<div class="bg-primary rounded-xl p-8 md:p-12 relative overflow-hidden">
<div class="absolute top-0 right-0 w-1/3 h-full bg-gradient-to-l from-primary-container/30 to-transparent pointer-events-none"></div>
<div class="relative z-10">
<h2 class="text-3xl font-headline font-bold text-white mb-2">Что послушать</h2>
<p class="text-white/70 mb-8 max-w-lg">Наши редакторы собрали плейлисты под любое настроение — от утреннего кофе до ночной поездки.</p>
<div class="flex gap-6 overflow-x-auto hide-scrollbar pb-4 -mx-4 px-4">
<!-- Music Card 1 -->
<div class="flex-none w-64 bg-white/10 backdrop-blur-md rounded-xl p-4 border border-white/5 group cursor-pointer hover:bg-white/20 transition-all">
<div class="aspect-square rounded-lg mb-4 overflow-hidden shadow-xl">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform" data-alt="close-up of a professional electric guitar against a dark moody stage background, purple and blue ambient lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCtQmT0DkvErf2yjC8L0z3Wx3GwfYvqx3DVrF4S64QB6cHxq0GsqsWOHUP1HWfXqqeUsrL3AF4g2z9ORURMtEgBzNHRN9jI6MI7YJk5Rw6uuAkn9Ni3hCz-X-JTDBgdBnGsjie6dEmDnBzIMSlBi6SfboRt_OqvE61ufA84yFGdHsff7jSFVyp4BP9SBgnpwvg5oCS97Syn_8XoCtlNWAU6HCDA9FIrQ8E9pA21nxbLzPL9WGpGGf6IILXPZnqi5TNCSggcUchgj1A1"/>
</div>
<h5 class="text-white font-bold mb-1">Инди-утро</h5>
<p class="text-white/60 text-xs font-label">24 ТРЕКА • 1 Ч 20 МИН</p>
</div>
<!-- Music Card 2 -->
<div class="flex-none w-64 bg-white/10 backdrop-blur-md rounded-xl p-4 border border-white/5 group cursor-pointer hover:bg-white/20 transition-all">
<div class="aspect-square rounded-lg mb-4 overflow-hidden shadow-xl">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform" data-alt="colorful concert lighting beams through a thin haze at a live music event, energetic atmosphere, blurred stage background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCFOvoXwiOEskY-5PcPptyebsNoAa2w86nuMWJvOW0Mt3wr-GuCWEweUM6bW9Gqgmd0l23giRRk_34fQZbMrZhyAFs1aMkVmBBTGOUHi1Ozvj2ZcusozqXAPw2BaDgDK-pHb2mPFcUvF1NL6SSwAw4_VnEwnGdT6oUKj3U87FBGLswJJjb0-COdr42aH0KK1MQv4A7wW4m9SycWQux4DX4XZv40CwGi21ZV3Tlr7vkTUJH7oj_FAH1qqi1kZNcvZAZI0JPNBoqZ069D"/>
</div>
<h5 class="text-white font-bold mb-1">Лоу-фай вайб</h5>
<p class="text-white/60 text-xs font-label">40 ТРЕКОВ • 2 Ч 15 МИН</p>
</div>
<!-- Music Card 3 -->
<div class="flex-none w-64 bg-white/10 backdrop-blur-md rounded-xl p-4 border border-white/5 group cursor-pointer hover:bg-white/20 transition-all">
<div class="aspect-square rounded-lg mb-4 overflow-hidden shadow-xl">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform" data-alt="professional DJ controller decks with glowing buttons in a dark club setting, vibrant red and blue accent lights" src="https://lh3.googleusercontent.com/aida-public/AB6AXuC29aVgmcgFLtTUZ2m2hVEDhTQ3JLyz5AG2By0Vahpy_FHxwA3a37XJ_fepMG7JEp7sPzafimcD8bfSYEECENIWBIV85B9zi7lYIljJfkFYKy2RRdwe9Z5ltGreZAvsZZz1kwdWdR-NtIlUQLMx8B6bhC9kkGzkiwIiVH6acFpfZykRJ_we30uFL1kT6KxzH6cOoXV6I4sUpR_RiZz8byzZn5L6-V6LCstjYXd_lEScRU00IVtHS9z2Bo0-j_b6SPEJuQaK_izFOWAr"/>
</div>
<h5 class="text-white font-bold mb-1">Ночной драйв</h5>
<p class="text-white/60 text-xs font-label">18 ТРЕКОВ • 55 МИН</p>
</div>
</div>
</div>
</div>
</section>
</main>
<!-- BottomNavBar -->
<nav class="fixed bottom-0 left-0 w-full z-50 flex justify-around items-end px-4 pb-6 pt-2 bg-[#f7f9fc]/80 dark:bg-[#191c1e]/80 backdrop-blur-xl shadow-[0_-12px_32px_rgba(25,28,30,0.06)] rounded-t-[3rem] md:hidden">
<div class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity">
<span class="material-symbols-outlined" data-icon="sports_soccer">sports_soccer</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Спорт</span>
</div>
<div class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity">
<span class="material-symbols-outlined" data-icon="sports_esports">sports_esports</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Игры</span>
</div>
<div class="flex flex-col items-center justify-center bg-[#183ce6] text-white rounded-full p-3 scale-110 -translate-y-2 transition-transform">
<span class="material-symbols-outlined" data-icon="devices">devices</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Техно</span>
</div>
<div class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity">
<span class="material-symbols-outlined" data-icon="music_note">music_note</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Музыка</span>
</div>
<div class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity">
<span class="material-symbols-outlined" data-icon="movie">movie</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Кино</span>
</div>
</nav>
<!-- FAB (Suppressed based on logic for feed, but optional for 'Create/Post') -->
<div class="fixed bottom-24 right-8 md:bottom-8 md:right-8 group">
<button class="bg-primary text-white w-14 h-14 rounded-full flex items-center justify-center shadow-xl transition-all duration-300 hover:scale-110 active:scale-95">
<span class="material-symbols-outlined" data-icon="add">add</span>
</button>
</div>
</body></html>

<!-- Главная лента -->
<!DOCTYPE html>

<html class="light" lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;700;800&amp;family=Manrope:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "error-container": "#ffdad6",
                    "inverse-on-surface": "#eff1f4",
                    "secondary": "#006879",
                    "tertiary": "#006153",
                    "on-secondary-fixed-variant": "#004e5b",
                    "primary": "#183ce6",
                    "on-surface": "#191c1e",
                    "on-error": "#ffffff",
                    "on-primary-fixed": "#000f5d",
                    "on-surface-variant": "#444656",
                    "surface-container": "#eceef1",
                    "on-tertiary": "#ffffff",
                    "inverse-primary": "#bbc3ff",
                    "on-error-container": "#93000a",
                    "surface-container-lowest": "#ffffff",
                    "primary-container": "#3d5afe",
                    "background": "#f7f9fc",
                    "secondary-container": "#54e0fd",
                    "inverse-surface": "#2d3133",
                    "surface": "#f7f9fc",
                    "outline": "#757688",
                    "surface-variant": "#e0e3e6",
                    "on-primary-container": "#f1f0ff",
                    "on-secondary-container": "#006170",
                    "on-tertiary-fixed-variant": "#005045",
                    "tertiary-fixed": "#9bf3df",
                    "on-secondary": "#ffffff",
                    "tertiary-container": "#187b6b",
                    "error": "#ba1a1a",
                    "secondary-fixed": "#a8edff",
                    "on-primary-fixed-variant": "#002ccd",
                    "surface-bright": "#f7f9fc",
                    "surface-container-highest": "#e0e3e6",
                    "on-primary": "#ffffff",
                    "primary-fixed-dim": "#bbc3ff",
                    "surface-tint": "#2848ee",
                    "outline-variant": "#c5c5d9",
                    "surface-dim": "#d8dadd",
                    "on-tertiary-container": "#b8ffee",
                    "surface-container-high": "#e6e8eb",
                    "primary-fixed": "#dee0ff",
                    "on-background": "#191c1e",
                    "on-secondary-fixed": "#001f26",
                    "surface-container-low": "#f2f4f7",
                    "secondary-fixed-dim": "#49d7f4",
                    "tertiary-fixed-dim": "#7fd6c3",
                    "on-tertiary-fixed": "#00201b"
            },
            "borderRadius": {
                    "DEFAULT": "1rem",
                    "lg": "2rem",
                    "xl": "3rem",
                    "full": "9999px"
            },
            "fontFamily": {
                    "headline": ["Plus Jakarta Sans"],
                    "body": ["Manrope"],
                    "label": ["Manrope"]
            }
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .glass-card {
            background: rgba(255, 255, 255, 0.8);
            backdrop-filter: blur(24px);
        }
    </style>
</head>
<body class="bg-surface font-body text-on-surface">
<!-- TopAppBar -->
<nav class="fixed top-0 w-full z-50 bg-[#f7f9fc]/80 dark:bg-[#191c1e]/80 backdrop-blur-xl transition-all duration-300 ease-in-out">
<div class="flex justify-between items-center px-6 h-16 w-full max-w-7xl mx-auto">
<div class="flex items-center gap-4">
<button class="p-2 hover:bg-[#f2f4f7]/50 dark:hover:bg-[#e6e8eb]/10 rounded-full transition-all">
<span class="material-symbols-outlined text-[#183ce6] dark:text-[#3d5afe]">search</span>
</button>
</div>
<div class="font-['Plus_Jakarta_Sans'] font-bold tracking-tight text-2xl font-extrabold text-[#183ce6] dark:text-[#3d5afe]">
                Портал
            </div>
<div class="flex items-center">
<div class="w-10 h-10 rounded-full bg-primary-container flex items-center justify-center text-white font-bold overflow-hidden">
<img alt="User Avatar" class="w-full h-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBEMqudGP03UfqlFwy-WxWAbG4rTIF-gbzG3tAR5L3xcveCjhSpmk0lzqz29LSV7TYdJf647kKAzo5Oxb6r4xYhnV07wMifY9xFMqu5STp-4UwyUZMZfUPO9s4d7ZTUdAgglvNM0n6diGvdele507BJiuVfAXQHzY65Pyun6LTioo4in4SKsDzcloYh-nCiD0cW2f-oT5RhOXRrfl26jhhvOuIGdLAl-6K7SEA0_DizBUYboFcF_gOpsN8SgPVHLiK3GTqrT6LpnuKk"/>
</div>
</div>
</div>
</nav>
<main class="pt-24 pb-32 px-6 max-w-7xl mx-auto">
<!-- Hero Section -->
<header class="mb-12">
<h1 class="font-headline text-[3.5rem] font-extrabold tracking-tighter text-on-surface leading-none mb-4">
                Техно &amp; Игры
            </h1>
<p class="text-on-surface-variant text-lg max-w-2xl leading-relaxed">
                Свежие обзоры девайсов, которые делают жизнь проще, и игры, в которых хочется раствориться. Отдыхаем с умом.
            </p>
</header>
<!-- Bento Grid Layout -->
<div class="grid grid-cols-1 md:grid-cols-12 gap-6">
<!-- Featured Review: Asymmetric Span -->
<article class="md:col-span-8 group cursor-pointer">
<div class="relative overflow-hidden rounded-xl bg-surface-container-lowest transition-transform duration-300 hover:scale-[1.01]">
<div class="aspect-[16/9] w-full relative">
<img alt="Tech Review" class="w-full h-full object-cover" data-alt="Modern sleek workstation with minimalist mechanical keyboard and curved ultra-wide monitor in soft blue ambient lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBR2sSVYOru69ek0vd8JuOrqLX3qQ2eIFxGsCYGTRs8_dVMxpWtVXjHJKpkJwaDFwrsLk44nmsUlVnSzpCrIEqfC0bTWUWXznMsz7jpQ-XlUTsZuo4GiPo5JJHrp5puASludl8A1641fD-FxqRrjkMgX5UkK5m3OeZ0pudsBQObYHpp00Dk7TwnLKDTIJ6nA6CkDLdWdFknBiPY9K_uNzWu8aoSHWtqCKK3mwwzQjf6PFCs2xj5vAIWRrNZsTDD48_rQxwnrxG3Mydf"/>
<div class="absolute inset-0 bg-gradient-to-t from-black/60 via-transparent to-transparent"></div>
<div class="absolute top-6 left-6">
<span class="bg-secondary-container text-on-secondary-container px-4 py-1.5 rounded-full text-xs font-bold uppercase tracking-widest">
                                Обзор
                            </span>
</div>
</div>
<div class="p-8 glass-card absolute bottom-0 left-0 right-0 m-6 rounded-lg">
<h2 class="font-headline text-2xl font-bold mb-2 text-on-surface">Новый уровень продуктивности: Тестируем флагманский монитор</h2>
<p class="text-on-surface-variant line-clamp-2 mb-4">Почему 49 дюймов — это не роскошь, а идеальный инструмент для тех, кто ценит свой комфорт и время.</p>
<div class="flex items-center gap-4 text-sm font-semibold text-primary">
<span>Читать 8 мин</span>
<span class="material-symbols-outlined text-sm">arrow_forward</span>
</div>
</div>
</div>
</article>
<!-- Tech News Vertical Card -->
<article class="md:col-span-4 bg-surface-container-lowest rounded-xl p-6 flex flex-col justify-between">
<div>
<span class="text-tertiary font-bold text-xs uppercase tracking-widest mb-4 block">Тренды</span>
<h3 class="font-headline text-xl font-bold mb-4 leading-snug">AI больше не игрушка: Как нейросети меняют наше утро</h3>
<p class="text-on-surface-variant text-sm leading-relaxed mb-6">От умных кофеварок до персональных ассистентов, которые знают ваш график лучше вас.</p>
</div>
<div class="relative rounded-lg overflow-hidden h-48">
<img alt="AI Tech" class="w-full h-full object-cover" data-alt="Abstract visualization of neural networks glowing with cyan and deep blue light on a dark background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCVMMr_SX1hy26fRvv0CHF-nYAwiaa9WmAm7shA-6ASJCtbqhWOPzLZdvFqm0U227jL075IE4-UvOTkR4elWogMlLlAvSgWJwNaxxjASn69vObN32v7D2ITpW5Jj7QcJpwcgUUZgsMLrhSY9a3spslWLC-2Ww-Udxobtux2mbdAuYHO4bkAdGaXwPMJGz8pXTzIiucZg4PEEABjs0cORzSpkmB2jaPVpv1cIJDqfJYxeh47-mvRC2dFUBUP3wgCUZPXSfZzKeESIH2x"/>
</div>
</article>
<!-- Games Section: Masonry-style Grid -->
<div class="md:col-span-12 mt-12 mb-6">
<div class="flex justify-between items-end mb-8">
<h2 class="font-headline text-3xl font-bold tracking-tight">Релизы недели</h2>
<button class="flex items-center gap-2 text-primary font-bold hover:gap-3 transition-all">
                        Все игры <span class="material-symbols-outlined">chevron_right</span>
</button>
</div>
</div>
<!-- Game Card 1 -->
<article class="md:col-span-4 group">
<div class="bg-surface-container-low rounded-xl overflow-hidden hover:bg-surface-container-high transition-colors p-4">
<div class="rounded-lg overflow-hidden mb-4 aspect-square">
<img alt="Game Title" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500" data-alt="Cinematic shot of a mythical dragon soaring through a vibrant sunset sky over a fantasy mountain range" src="https://lh3.googleusercontent.com/aida-public/AB6AXuD2VhK7QMWGiDY_Ak5Bo1bo3XTa89cjvRiktB3VDBkxIWnKzrrOSsomKEZ9UYuGO488Bmv0Q5ZSA16ZNPJfOCG-_pS8YeaBYMcnWc1FPoGY8Rm6TnfaIyJa5MIG6XUE4C4_6KvqZL9hdBamggAfFwrDp89rhkDWFqFClIgCuVyL7P61aCyucKgYZriv4J1YX8zf4TFDlmD_nrtOkAUKIDTa9BMNgAFSclgwXtzP57QuQ-IXMfxeS8uZOr76eDx94p8gbGDI1haBa-S5"/>
</div>
<div class="flex justify-between items-start mb-2">
<h4 class="font-headline text-lg font-bold">Dragon's Wake</h4>
<span class="bg-primary/10 text-primary px-2 py-0.5 rounded text-[10px] font-bold">RPG</span>
</div>
<p class="text-on-surface-variant text-sm mb-4">Погружение в открытый мир, где каждое решение меняет климат планеты.</p>
<div class="flex items-center justify-between">
<span class="text-on-surface font-bold">9.2 / 10</span>
<button class="p-2 rounded-full bg-white text-primary shadow-sm">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">play_arrow</span>
</button>
</div>
</div>
</article>
<!-- Game Card 2 -->
<article class="md:col-span-4 group">
<div class="bg-surface-container-low rounded-xl overflow-hidden hover:bg-surface-container-high transition-colors p-4">
<div class="rounded-lg overflow-hidden mb-4 aspect-square">
<img alt="Game Title" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500" data-alt="Cyberpunk city street at night with neon signs reflecting in puddles and a sleek futuristic car" src="https://lh3.googleusercontent.com/aida-public/AB6AXuD7-xw38hiNUvd5SlvW4GhEW-VlfWI72607jTNW8GSWdZaCErFUIcYUUc-7eFqhqMW4EyekL-QlPI6V8baLr0i12TXTYieRp12oGHI_r2oHk0UZYUdf2nR--A1avmsCIhNCnbdO6E1axJYX32j9n3HoYJCnQvYMZqcQFXEFWujMmAa_2ZNz0FwCMYai_RIq7hRR5uOdYwNGQ0k-XRsj745DnWo5f5ZqRmhQkX38nvvpqiDJCHudd7l8f6IVIClbYsKwm2hfwqosCBTx"/>
</div>
<div class="flex justify-between items-start mb-2">
<h4 class="font-headline text-lg font-bold">Neon Pulse</h4>
<span class="bg-secondary/10 text-secondary px-2 py-0.5 rounded text-[10px] font-bold">Action</span>
</div>
<p class="text-on-surface-variant text-sm mb-4">Ритм-экшен в декорациях будущего, где музыка — ваше главное оружие.</p>
<div class="flex items-center justify-between">
<span class="text-on-surface font-bold">8.5 / 10</span>
<button class="p-2 rounded-full bg-white text-primary shadow-sm">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">play_arrow</span>
</button>
</div>
</div>
</article>
<!-- Game Card 3 -->
<article class="md:col-span-4 group">
<div class="bg-surface-container-low rounded-xl overflow-hidden hover:bg-surface-container-high transition-colors p-4">
<div class="rounded-lg overflow-hidden mb-4 aspect-square">
<img alt="Game Title" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500" data-alt="Collection of vintage 8-bit game consoles and colorful cartridges arranged on a wooden desk" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDrIlWThqd2mgkiTHs8fP1n0QfR3Da6hIrht2_m10nKnYrrWi-AVxAe31W9VbPY16LopuUuO323inhWF4LVy41rm-lH6tVuGDDMvIn-FolJHvgRXMX9D-K6t_HfLSpDf_J49HEwR02tV9cPC0fZZRd5Ylc1QHDYokCvaANj2pcL_HRxTkgrpXuIqvlAQUfb8JOTE2wuhpR2LRHj3fwR_bfK7PUEVUTmwOb3VC6TxyupIhxnMGsyQQmACu8D0jzzTWbp-Rsq6-Nsfwvb"/>
</div>
<div class="flex justify-between items-start mb-2">
<h4 class="font-headline text-lg font-bold">Retro Revival</h4>
<span class="bg-tertiary/10 text-tertiary px-2 py-0.5 rounded text-[10px] font-bold">Indie</span>
</div>
<p class="text-on-surface-variant text-sm mb-4">Пиксельная ностальгия, переосмысленная для современных консолей.</p>
<div class="flex items-center justify-between">
<span class="text-on-surface font-bold">8.8 / 10</span>
<button class="p-2 rounded-full bg-white text-primary shadow-sm">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">play_arrow</span>
</button>
</div>
</div>
</article>
</div>
</main>
<!-- FAB: Contextual to Tech/Games -->
<button class="fixed bottom-28 right-8 w-14 h-14 rounded-full bg-primary-container text-white shadow-xl flex items-center justify-center hover:scale-110 transition-transform z-40">
<span class="material-symbols-outlined">add</span>
</button>
<!-- BottomNavBar -->
<nav class="fixed bottom-0 left-0 w-full z-50 flex justify-around items-end px-4 pb-6 pt-2 bg-[#f7f9fc]/80 dark:bg-[#191c1e]/80 backdrop-blur-xl rounded-t-[3rem] shadow-[0_-12px_32px_rgba(25,28,30,0.06)]">
<div class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity cursor-pointer">
<span class="material-symbols-outlined mb-1">sports_soccer</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider">Спорт</span>
</div>
<div class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity cursor-pointer">
<span class="material-symbols-outlined mb-1">sports_esports</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider">Игры</span>
</div>
<!-- Active Tab: Techno (Using logic to map "Tech" to "Техно") -->
<div class="flex flex-col items-center justify-center bg-[#183ce6] text-white rounded-full p-3 scale-110 -translate-y-2 transition-transform cursor-pointer">
<span class="material-symbols-outlined mb-1">devices</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider">Техно</span>
</div>
<div class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity cursor-pointer">
<span class="material-symbols-outlined mb-1">music_note</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider">Музыка</span>
</div>
<div class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity cursor-pointer">
<span class="material-symbols-outlined mb-1">movie</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider">Кино</span>
</div>
</nav>
</body></html>

<!-- Техно и Игры -->
<!DOCTYPE html>

<html class="light" lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Спорт и Движение — Жизнь на чиле</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;700;800&amp;family=Manrope:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "error-container": "#ffdad6",
                        "inverse-on-surface": "#eff1f4",
                        "secondary": "#006879",
                        "tertiary": "#006153",
                        "on-secondary-fixed-variant": "#004e5b",
                        "primary": "#183ce6",
                        "on-surface": "#191c1e",
                        "on-error": "#ffffff",
                        "on-primary-fixed": "#000f5d",
                        "on-surface-variant": "#444656",
                        "surface-container": "#eceef1",
                        "on-tertiary": "#ffffff",
                        "inverse-primary": "#bbc3ff",
                        "on-error-container": "#93000a",
                        "surface-container-lowest": "#ffffff",
                        "primary-container": "#3d5afe",
                        "background": "#f7f9fc",
                        "secondary-container": "#54e0fd",
                        "inverse-surface": "#2d3133",
                        "surface": "#f7f9fc",
                        "outline": "#757688",
                        "surface-variant": "#e0e3e6",
                        "on-primary-container": "#f1f0ff",
                        "on-secondary-container": "#006170",
                        "on-tertiary-fixed-variant": "#005045",
                        "tertiary-fixed": "#9bf3df",
                        "on-secondary": "#ffffff",
                        "tertiary-container": "#187b6b",
                        "error": "#ba1a1a",
                        "secondary-fixed": "#a8edff",
                        "on-primary-fixed-variant": "#002ccd",
                        "surface-bright": "#f7f9fc",
                        "surface-container-highest": "#e0e3e6",
                        "on-primary": "#ffffff",
                        "primary-fixed-dim": "#bbc3ff",
                        "surface-tint": "#2848ee",
                        "outline-variant": "#c5c5d9",
                        "surface-dim": "#d8dadd",
                        "on-tertiary-container": "#b8ffee",
                        "surface-container-high": "#e6e8eb",
                        "primary-fixed": "#dee0ff",
                        "on-background": "#191c1e",
                        "on-secondary-fixed": "#001f26",
                        "surface-container-low": "#f2f4f7",
                        "secondary-fixed-dim": "#49d7f4",
                        "tertiary-fixed-dim": "#7fd6c3",
                        "on-tertiary-fixed": "#00201b"
                    },
                    "borderRadius": {
                        "DEFAULT": "1rem",
                        "lg": "2rem",
                        "xl": "3rem",
                        "full": "9999px"
                    },
                    "fontFamily": {
                        "headline": ["Plus Jakarta Sans"],
                        "body": ["Manrope"],
                        "label": ["Manrope"]
                    }
                }
            }
        }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        body { font-family: 'Manrope', sans-serif; background-color: #f7f9fc; color: #191c1e; overflow-x: hidden; }
        h1, h2, h3 { font-family: 'Plus Jakarta Sans', sans-serif; }
    </style>
</head>
<body class="bg-surface text-on-surface selection:bg-primary-container selection:text-on-primary-container">
<!-- TopAppBar -->
<header class="fixed top-0 w-full z-50 bg-[#f7f9fc]/80 dark:bg-[#191c1e]/80 backdrop-blur-xl">
<div class="flex justify-between items-center px-6 h-16 w-full max-w-7xl mx-auto">
<div class="flex items-center gap-4">
<button class="p-2 transition-all duration-300 ease-in-out hover:bg-[#f2f4f7]/50 dark:hover:bg-[#e6e8eb]/10 rounded-full">
<span class="material-symbols-outlined text-[#183ce6] dark:text-[#3d5afe]">search</span>
</button>
</div>
<div class="text-2xl font-extrabold text-[#183ce6] dark:text-[#3d5afe] font-['Plus_Jakarta_Sans'] tracking-tight">Портал</div>
<div class="flex items-center">
<div class="w-10 h-10 rounded-full bg-surface-container-highest flex items-center justify-center overflow-hidden border-2 border-primary/10">
<img class="w-full h-full object-cover" data-alt="Close up portrait of a smiling friendly person with natural lighting and soft blurred background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBSLRtq1LSWUF0jp2xFH4VoKUA5JYhqwScEttBgaS6LgdHcV2h8nGVvA01dIgGhGzIDGyQzUlo-cRS_3cWm7Z8ygGRx70zAA50GzixFjzcchYGZ3OFGDVjsEMkLysVX-BOzBuMXQ3Jd5e6rHVmwDoSKWtIXILvYgx6Ul11wAflz5fqkvIoc_hQI88w8qOcP0WdaAxvM9rEFqAhbFZxp4rRcW5EImQUxk1zmSmEHjTZcVVznj12ehoImHy3jWP3WZog-znhOyPSSp4g9"/>
</div>
</div>
</div>
</header>
<main class="pt-24 pb-32 px-4 max-w-7xl mx-auto">
<!-- Hero Section -->
<section class="relative mb-16 group">
<div class="bg-gradient-to-br from-primary to-primary-container rounded-xl overflow-hidden min-h-[500px] flex items-center relative p-8 md:p-16">
<div class="z-10 max-w-2xl">
<span class="inline-block px-4 py-1.5 bg-secondary-container text-on-secondary-container rounded-full text-xs font-bold uppercase tracking-widest mb-6">Lifestyle Focus</span>
<h1 class="text-white text-5xl md:text-7xl font-extrabold tracking-tight mb-6 leading-[1.1]">Спорт и Движение</h1>
<p class="text-on-primary-container text-lg md:text-xl leading-relaxed mb-10 opacity-90">
                        Забудьте про изнурительные тренировки. Мы здесь ради эндорфинов, прогулок в парке и радости от того, что тело просто живет. Жизнь на чиле — это когда спорт в удовольствие.
                    </p>
<div class="flex flex-wrap gap-4">
<button class="bg-white text-primary px-8 py-4 rounded-full font-bold transition-transform hover:scale-105">Начать легко</button>
<button class="bg-primary-container/20 text-white border border-white/20 backdrop-blur-md px-8 py-4 rounded-full font-bold hover:bg-white/10 transition-all">Узнать больше</button>
</div>
</div>
<div class="absolute right-0 bottom-0 top-0 w-1/2 hidden lg:block overflow-hidden rounded-l-xl">
<img class="w-full h-full object-cover opacity-80 mix-blend-lighten" data-alt="Athletic person in modern sportswear stretching in a sun-drenched studio with soft shadows and minimal aesthetic" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDswbVFZaFsyG-Z7y81w1gElsE6jjAsdgQKoYUdOUbSfGqe5uHo-e2IeQ6WlMpkgcz4f9rwfvFTm3hNQn_zyrvEyFYZHgW44hJLnmAehgg7P3RatxynsNUi1xv5xjRGuhY_iO6c5B47IzZQkDDVw75SzxPuzzJXfrG9EDAYmGAwIke7R8h4VOehD9v52vVpu2ZmO-cfvYwHSoC1rxZNPmIkYaXjX2yPo9LhCzjSQsjTEG5kCxDaqz3m3KOAZC70TZRNs7zRNXst5aCL"/>
</div>
</div>
</section>
<!-- Bento Grid Layout -->
<div class="grid grid-cols-1 md:grid-cols-12 gap-6 mb-16">
<!-- Card 1: Jogging -->
<div class="md:col-span-8 bg-surface-container-lowest rounded-xl p-8 flex flex-col md:flex-row gap-8 items-center group cursor-pointer hover:shadow-xl transition-all duration-300">
<div class="w-full md:w-1/2 aspect-video rounded-lg overflow-hidden">
<img class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-700" data-alt="Young person jogging through a scenic misty park at sunrise with soft golden rays filtering through trees" src="https://lh3.googleusercontent.com/aida-public/AB6AXuB_avTlmwImL1JbYH7Xm8bVCKGiwrWYaRoSYnfYocqIRYbqa6hXVgkHVD3oAwtLgXxrdU_CaAlW9ze12oJn6RnWYFAtVbglSicEgnbWCVnVW7gxc4q408cGEZDP9jxJE81peyaq9Da1FJeRw0RX7MfR2P7WJNAXqXlZrGFQnFMbynq3W8C-lTMBJ0JV7a9Ctk9eF6fcnnmKrUXhKGOTcqHgbSXhBLnYtcES29pfmUVIO1JYS5iznngZ7uhdGLvKgYndaepnNtM68vhn"/>
</div>
<div class="w-full md:w-1/2">
<h3 class="text-2xl font-bold mb-4 text-on-surface">Бег без одышки</h3>
<p class="text-on-surface-variant leading-relaxed mb-6">Как превратить утреннюю пробежку в медитацию, а не в пытку. Секреты темпа, который приносит радость.</p>
<div class="flex items-center gap-2 text-primary font-bold">
<span>Читать статью</span>
<span class="material-symbols-outlined">arrow_forward</span>
</div>
</div>
</div>
<!-- Card 2: Gym Vibes -->
<div class="md:col-span-4 bg-tertiary-container rounded-xl p-8 flex flex-col justify-between text-white relative overflow-hidden group">
<div class="absolute top-0 right-0 p-4 opacity-20">
<span class="material-symbols-outlined text-8xl" style="font-variation-settings: 'FILL' 1;">fitness_center</span>
</div>
<div class="relative z-10">
<h3 class="text-2xl font-bold mb-4">Тренажерка для души</h3>
<p class="opacity-80 mb-8">Почему 20 минут веса лучше часа кардио, если ваша цель — просто чувствовать себя бодро.</p>
</div>
<button class="bg-white/20 backdrop-blur-xl border border-white/30 p-4 rounded-full w-fit group-hover:bg-white group-hover:text-tertiary-container transition-all">
<span class="material-symbols-outlined">add</span>
</button>
</div>
<!-- Card 3: Well-being Chips/Tags -->
<div class="md:col-span-4 bg-surface-container-low rounded-xl p-8">
<h3 class="text-xl font-bold mb-6">Что сегодня?</h3>
<div class="flex flex-wrap gap-3">
<span class="px-6 py-3 bg-secondary-container text-on-secondary-container rounded-full text-sm font-semibold cursor-pointer hover:opacity-80 transition-opacity">Йога</span>
<span class="px-6 py-3 bg-white text-on-surface-variant rounded-full text-sm font-semibold border border-outline-variant/20 shadow-sm cursor-pointer hover:bg-secondary-container transition-all">Бадминтон</span>
<span class="px-6 py-3 bg-white text-on-surface-variant rounded-full text-sm font-semibold border border-outline-variant/20 shadow-sm cursor-pointer hover:bg-secondary-container transition-all">Плавание</span>
<span class="px-6 py-3 bg-white text-on-surface-variant rounded-full text-sm font-semibold border border-outline-variant/20 shadow-sm cursor-pointer hover:bg-secondary-container transition-all">Велосипед</span>
<span class="px-6 py-3 bg-white text-on-surface-variant rounded-full text-sm font-semibold border border-outline-variant/20 shadow-sm cursor-pointer hover:bg-secondary-container transition-all">Растяжка</span>
</div>
</div>
<!-- Card 4: Video Insight (Asymmetric) -->
<div class="md:col-span-8 relative rounded-xl overflow-hidden bg-on-surface">
<img class="w-full h-full object-cover opacity-50" data-alt="High angle view of a yoga mat and water bottle on a clean wooden floor in a bright minimalist studio" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAcqk7oIaZwaSCrGu3HsAnJ7GZnorAATaIlFYzt0XjPBGQ-lK17FNFnamEICh6XpaZ7pkFEA2d9brYgTfsuFYdeJhFJjA2qWwQekxPwqzBCGZcbQ2GJ62sgyQPPqm-uZeR4yf-QSNWonTyDv_fE1RrFAX-q6c4w4RfqBmq6wLiCnKQ7fv7cDZwmvIpdp8Bt9JsxjbfrRgT7L-gC0YrQw0N7K05OrsrBibrlCE1QZtzZSxLswTu6MgiHMaXRaKuesadc5v_g_EVCE6fJ"/>
<div class="absolute inset-0 p-8 flex flex-col justify-end">
<div class="flex items-center gap-4 mb-4">
<div class="w-16 h-16 bg-primary rounded-full flex items-center justify-center text-white shadow-lg cursor-pointer hover:scale-110 transition-transform">
<span class="material-symbols-outlined text-4xl" style="font-variation-settings: 'FILL' 1;">play_arrow</span>
</div>
<div>
<p class="text-white font-bold text-xl">5 минут для спины</p>
<p class="text-white/70 text-sm">Короткий комплекс для тех, кто много сидит</p>
</div>
</div>
</div>
</div>
</div>
<!-- Quote / Editorial Block -->
<section class="my-20 text-center max-w-3xl mx-auto">
<span class="material-symbols-outlined text-secondary text-5xl mb-6">format_quote</span>
<h2 class="text-3xl md:text-4xl font-bold text-on-surface leading-tight mb-8">
                «Движение — это не долг перед зеркалом, а подарок своему настроению».
            </h2>
<div class="h-1 w-20 bg-secondary mx-auto rounded-full"></div>
</section>
<!-- Newsletter / Community Section (Glassmorphism) -->
<section class="relative bg-surface-container-high rounded-xl p-8 md:p-12 overflow-hidden">
<div class="relative z-10 grid md:grid-cols-2 gap-12 items-center">
<div>
<h2 class="text-3xl font-bold mb-4">Присоединяйтесь к движению чилла</h2>
<p class="text-on-surface-variant text-lg">Получайте еженедельные подборки легких активностей и советы по восстановлению сил.</p>
</div>
<div class="flex flex-col sm:flex-row gap-4">
<input class="flex-grow bg-white border-none rounded-full px-6 py-4 focus:ring-2 focus:ring-primary text-on-surface" placeholder="Ваш e-mail" type="email"/>
<button class="bg-primary text-white font-bold px-8 py-4 rounded-full shadow-lg shadow-primary/20 hover:translate-y-[-2px] transition-all">Подписаться</button>
</div>
</div>
<!-- Decorative circle -->
<div class="absolute -top-24 -right-24 w-64 h-64 bg-secondary/10 rounded-full blur-3xl"></div>
</section>
</main>
<!-- BottomNavBar -->
<nav class="fixed bottom-0 left-0 w-full z-50 flex justify-around items-end px-4 pb-6 pt-2 bg-[#f7f9fc]/80 dark:bg-[#191c1e]/80 backdrop-blur-xl shadow-[0_-12px_32px_rgba(25,28,30,0.06)] rounded-t-[3rem]">
<a class="flex flex-col items-center justify-center bg-[#183ce6] text-white rounded-full p-3 scale-110 -translate-y-2 transition-transform" href="#">
<span class="material-symbols-outlined">sports_soccer</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Спорт</span>
</a>
<a class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity" href="#">
<span class="material-symbols-outlined">sports_esports</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Игры</span>
</a>
<a class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity" href="#">
<span class="material-symbols-outlined">devices</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Техно</span>
</a>
<a class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity" href="#">
<span class="material-symbols-outlined">music_note</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Музыка</span>
</a>
<a class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity" href="#">
<span class="material-symbols-outlined">movie</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Кино</span>
</a>
</nav>
</body></html>
<!-- Design System -->
<!DOCTYPE html>

<html class="light" lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@700;800&amp;family=Manrope:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "error-container": "#ffdad6",
                        "inverse-on-surface": "#eff1f4",
                        "secondary": "#006879",
                        "tertiary": "#006153",
                        "on-secondary-fixed-variant": "#004e5b",
                        "primary": "#183ce6",
                        "on-surface": "#191c1e",
                        "on-error": "#ffffff",
                        "on-primary-fixed": "#000f5d",
                        "on-surface-variant": "#444656",
                        "surface-container": "#eceef1",
                        "on-tertiary": "#ffffff",
                        "inverse-primary": "#bbc3ff",
                        "on-error-container": "#93000a",
                        "surface-container-lowest": "#ffffff",
                        "primary-container": "#3d5afe",
                        "background": "#f7f9fc",
                        "secondary-container": "#54e0fd",
                        "inverse-surface": "#2d3133",
                        "surface": "#f7f9fc",
                        "outline": "#757688",
                        "surface-variant": "#e0e3e6",
                        "on-primary-container": "#f1f0ff",
                        "on-secondary-container": "#006170",
                        "on-tertiary-fixed-variant": "#005045",
                        "tertiary-fixed": "#9bf3df",
                        "on-secondary": "#ffffff",
                        "tertiary-container": "#187b6b",
                        "error": "#ba1a1a",
                        "secondary-fixed": "#a8edff",
                        "on-primary-fixed-variant": "#002ccd",
                        "surface-bright": "#f7f9fc",
                        "surface-container-highest": "#e0e3e6",
                        "on-primary": "#ffffff",
                        "primary-fixed-dim": "#bbc3ff",
                        "surface-tint": "#2848ee",
                        "outline-variant": "#c5c5d9",
                        "surface-dim": "#d8dadd",
                        "on-tertiary-container": "#b8ffee",
                        "surface-container-high": "#e6e8eb",
                        "primary-fixed": "#dee0ff",
                        "on-background": "#191c1e",
                        "on-secondary-fixed": "#001f26",
                        "surface-container-low": "#f2f4f7",
                        "secondary-fixed-dim": "#49d7f4",
                        "tertiary-fixed-dim": "#7fd6c3",
                        "on-tertiary-fixed": "#00201b"
                    },
                    "borderRadius": {
                        "DEFAULT": "1rem",
                        "lg": "2rem",
                        "xl": "3rem",
                        "full": "9999px"
                    },
                    "fontFamily": {
                        "headline": ["Plus Jakarta Sans"],
                        "body": ["Manrope"],
                        "label": ["Manrope"]
                    }
                },
            },
        }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .hide-scrollbar::-webkit-scrollbar { display: none; }
        .hide-scrollbar { -ms-overflow-style: none; scrollbar-width: none; }
    </style>
</head>
<body class="bg-surface font-body text-on-surface selection:bg-primary-container selection:text-on-primary-container">
<!-- TopAppBar -->
<header class="bg-[#f7f9fc]/80 dark:bg-[#191c1e]/80 backdrop-blur-xl fixed top-0 w-full z-50 transition-all duration-300 ease-in-out">
<div class="flex justify-between items-center px-6 h-16 w-full max-w-7xl mx-auto">
<div class="flex items-center gap-4">
<button class="p-2 text-[#191c1e] dark:text-[#f2f4f7] hover:bg-[#f2f4f7]/50 dark:hover:bg-[#e6e8eb]/10 rounded-full transition-all">
<span class="material-symbols-outlined" data-icon="search">search</span>
</button>
<h1 class="text-2xl font-extrabold text-[#183ce6] dark:text-[#3d5afe] font-['Plus_Jakarta_Sans'] tracking-tight">Портал</h1>
</div>
<nav class="hidden md:flex gap-8">
<a class="font-['Plus_Jakarta_Sans'] font-bold tracking-tight text-[#183ce6] dark:text-[#3d5afe] transition-all" href="#">Спорт</a>
<a class="font-['Plus_Jakarta_Sans'] font-bold tracking-tight text-[#191c1e] dark:text-[#f2f4f7] opacity-70 hover:opacity-100 transition-all" href="#">Игры</a>
<a class="font-['Plus_Jakarta_Sans'] font-bold tracking-tight text-[#191c1e] dark:text-[#f2f4f7] opacity-70 hover:opacity-100 transition-all" href="#">Техно</a>
<a class="font-['Plus_Jakarta_Sans'] font-bold tracking-tight text-[#191c1e] dark:text-[#f2f4f7] opacity-70 hover:opacity-100 transition-all" href="#">Музыка</a>
<a class="font-['Plus_Jakarta_Sans'] font-bold tracking-tight text-[#191c1e] dark:text-[#f2f4f7] opacity-70 hover:opacity-100 transition-all" href="#">Кино</a>
</nav>
<div class="flex items-center gap-2">
<div class="w-10 h-10 rounded-full bg-primary-container overflow-hidden ring-2 ring-surface">
<img alt="User" data-alt="close-up portrait of a young man with a friendly smile, natural lighting, soft urban background bokeh" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAKum0n9ounuJKQqHwd5LHIagTBqviqU-kZwmcznPFGIWINxEQIggylweQPvlDSVIJkySA-YA-S0C-kHpv2XBCimDvPgLr3vvLi_UZnhjr4IrwTXmoXpl33TBXfs5F4CnHkLDyTJaNQPl_u2BCB-QeAeQq7EgHt0O-yJEnn_rizDrHySeO3mfDxYYW-3GzZYEFzfn1H2WrN6QzYfqq_38xV0tLk9J_8JKVuWFMGtYwBbZtSCpqTroTjOeP95jUQvqx5qUhd8hHs7g28"/>
</div>
</div>
</div>
</header>
<main class="pt-24 pb-32 max-w-7xl mx-auto px-6">
<!-- Hero Section -->
<section class="mb-12">
<h2 class="text-[3.5rem] font-headline font-extrabold leading-[1.1] mb-8 tracking-tighter text-primary">Главная</h2>
<!-- Bento Grid Trends -->
<div class="grid grid-cols-1 md:grid-cols-4 grid-rows-2 gap-6 h-auto md:h-[600px]">
<!-- Main Featured Card -->
<div class="md:col-span-2 md:row-span-2 relative group overflow-hidden rounded-xl bg-surface-container-lowest transition-transform hover:scale-[1.01]">
<img class="absolute inset-0 w-full h-full object-cover" data-alt="serene person practicing yoga on a sunlit balcony overlooking a misty morning forest, peaceful atmosphere, soft sunlight" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAbp-c8PI8NSe6CDcrGQir8NIewujDFVtSIU2RW4i_cv9fwt94eO7NShRneOxOKxzTLfyb6tSw6GKOqG5jpTRudE95d4wsh1gpZ44B3Phipl6CXTkX1BQi2zqXUwtSqHrZxIn4McAegiqKE6PW9uPx6I6E_4hhG9nGTr-dx9BGxFu8OZE6m8WZh9V4d4k4cEAo-xbsb4wNg4Fp1pzjAUvqPQVYjO-_kllCRn4QbfwZ7kcXy5bmVHU9W_Dl19got2Tevwdnht-JPKlzH"/>
<div class="absolute inset-0 bg-gradient-to-t from-primary/80 via-transparent to-transparent"></div>
<div class="absolute bottom-0 p-8">
<span class="inline-block px-4 py-1 mb-4 rounded-full bg-secondary-container text-on-secondary-container font-label text-xs font-bold tracking-widest uppercase">Тренды</span>
<h3 class="text-3xl font-headline font-bold text-white mb-2 leading-tight">Искусство замедления: как найти свой дзен в мегаполисе</h3>
<p class="text-white/80 font-body text-sm max-w-md">Путеводитель по самым тихим местам и техникам осознанности для тех, кто устал от суеты.</p>
</div>
</div>
<!-- Secondary Trend 1 -->
<div class="md:col-span-2 md:row-span-1 relative group overflow-hidden rounded-xl bg-surface-container-lowest">
<img class="absolute inset-0 w-full h-full object-cover" data-alt="vibrant abstract close-up of a vinyl record spinning with colorful light reflections, retro-modern aesthetic, energetic mood" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCQ3JX_L9ESrCLFD5k0BrYiNrC7kPSZxmZ3_XdDvHSXf4kWFXDuHhOVg1gRHrIUcM2ckf-PIsHTnu34tEviTc4iFBeKl8KcDCKI9UKzVOG4YiHBSY8OcyUfW-TBe-aYUPFy0fgRIyskEvfKtAWSs-5NE2BJInDbkA_6oj2URE1II02ZhGxpqlhZmtarQY-F-NgrbMkJ2jwNZ8__Oz-yrUoWR1HeRHz5aCvEslw_u707AYLvitOpzOy1m1-08tfqUkX012pkrttZY6nX"/>
<div class="absolute inset-0 bg-gradient-to-r from-[#006153]/90 via-[#006153]/40 to-transparent"></div>
<div class="absolute inset-0 p-6 flex flex-col justify-end">
<h3 class="text-xl font-headline font-bold text-white">Виниловый ренессанс</h3>
</div>
</div>
<!-- Secondary Trend 2 -->
<div class="md:col-span-1 md:row-span-1 relative group overflow-hidden rounded-xl bg-surface-container-lowest">
<img class="absolute inset-0 w-full h-full object-cover" data-alt="high-tech gaming setup with glowing neon teal and indigo lights, sleek hardware, futuristic atmospheric lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDSX8f4i0M_VJrmJx6VHfVT7t5QpgNXh-qogJJYV0IqIqAP2RYcisOSFE4j0UH1SQDAw2MxxXr5V7jCCfufYBAM98li6y6mO4nzQzTYF0v7m0qBa4WT_FhzcJU0FApCaMqltPEB895HM2x3OsAiyZ9rJPxR-gMMbPOlTDpuT2yvZAz6MAHICGVObwM1jFM3xV6nhA50H9cNZ03woq6FbSKYqze_f7JJ0jFxk4mal4M2v7xGvq2-uVAUt7ntTwSOzkjgDyYb5TNvvlIY"/>
<div class="absolute inset-0 bg-gradient-to-t from-[#183ce6]/80 to-transparent"></div>
<div class="absolute bottom-0 p-6">
<h3 class="text-lg font-headline font-bold text-white">Киберспорт 2024</h3>
</div>
</div>
<!-- Secondary Trend 3 -->
<div class="md:col-span-1 md:row-span-1 relative group overflow-hidden rounded-xl bg-surface-container-lowest">
<img class="absolute inset-0 w-full h-full object-cover" data-alt="gourmet healthy breakfast spread on a white wooden table, bright morning light, fresh ingredients, minimalist aesthetic" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCHApM8hcJSMppt1AQWSZG4w7aC8G1gAASu4HssgDTiHHPb5S9WeD-DQxJQhQ7POrBSUaI3TSWKLBrVy6yVmUos-uJnA2EYEiJ3HNICFzd-G3pn_vDTyyZL5cfAm5flluZeWRqJqIaP4FQEAOXl5EBXXDk9LzxEboMRoZOcfxDqYIgZIdx0BfqfaTDtCAEUSUuvT5B0ThXWYuGZWBUqYwU4qIdKsZ8mx-T5RD0uWbKsEeskPnvafa72jvzxcT8T5gjc0LLv3cPyHcJu"/>
<div class="absolute inset-0 bg-gradient-to-t from-[#006879]/80 to-transparent"></div>
<div class="absolute bottom-0 p-6">
<h3 class="text-lg font-headline font-bold text-white">Завтраки будущего</h3>
</div>
</div>
</div>
</section>
<!-- New in Tech Section -->
<section class="mb-16">
<div class="flex justify-between items-end mb-8">
<div>
<h2 class="text-2xl font-headline font-bold text-on-surface">Новое в техно</h2>
<div class="h-1 w-12 bg-secondary mt-2 rounded-full"></div>
</div>
<button class="text-primary font-label text-sm font-bold flex items-center gap-1 hover:gap-2 transition-all">
                    Смотреть всё <span class="material-symbols-outlined text-sm">arrow_forward</span>
</button>
</div>
<div class="grid grid-cols-1 md:grid-cols-3 gap-8">
<article class="bg-surface-container-lowest rounded-xl p-4 transition-all hover:bg-surface-container-low group">
<div class="relative h-48 mb-4 overflow-hidden rounded-lg">
<img class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110" data-alt="close-up of a sleek minimalist smartphone with high-end camera lenses, reflections of soft studio lights, professional product photography" src="https://lh3.googleusercontent.com/aida-public/AB6AXuACzaLvWILkI-vopShSttB04Th1wNrQeKaGe0EtAibrsMEFkjKzhn_XwyVC0g6v4l-D7E9g0wqIYxK5Y1sQtO6O0-pErxGUxPjqCkkqidaOFauVacNqp1dqlNWep3w5zTpCxA3XmYM1YB_Z2xSQ2fg0wNKieKsD7y-wOE5oaCFaxTbYryNuPmSpDBdbHvTT0iuvOWm3QQkWz7QyY32XxJ6j2wbJ1uGA63jzlIh1VjIPyke5yWiiG4_fu9XVNxUU9frfj2szRLw5FBGu"/>
</div>
<div class="flex items-center gap-2 mb-2 text-on-surface-variant font-label text-xs font-semibold uppercase tracking-wider">
<span class="material-symbols-outlined text-sm">memory</span>
<span>Гаджеты</span>
</div>
<h4 class="text-xl font-headline font-bold mb-2">Почему ваш следующий смартфон будет прозрачным?</h4>
<p class="text-on-surface-variant font-body text-sm line-clamp-2">Разбираемся в новых технологиях дисплеев и материалах будущего.</p>
</article>
<article class="bg-surface-container-lowest rounded-xl p-4 transition-all hover:bg-surface-container-low group">
<div class="relative h-48 mb-4 overflow-hidden rounded-lg">
<img class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110" data-alt="abstract visualization of artificial intelligence neural networks, glowing cyan nodes and data streams, dark futuristic background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCgKQL9TutZDNByOTkzwag9zDtDqVrS0wIbJ1rAl0mxpfeeAGaxPBEGvvQM2CFvrGrevO2dKRgwmbbv0QPHYZJ3t9N6UjaMwudTpnqut-XcN1gCYYblijmP7DHa7HuZ28dWcR0n1rFKOx8p1cC7B2f6TFVR-oXNxiu9E4tLIsFestfFn3Bj4Xh9nk-yPGzWop9XLEMDQIWH3KyfDFo_MUS2nIpM_8t0jKVs6R6_OVY558-teQfoWtDTYF5j8dY9THvky991XDB-EvxM"/>
</div>
<div class="flex items-center gap-2 mb-2 text-on-surface-variant font-label text-xs font-semibold uppercase tracking-wider">
<span class="material-symbols-outlined text-sm">smart_toy</span>
<span>AI тренды</span>
</div>
<h4 class="text-xl font-headline font-bold mb-2">Нейросети на чиле: отдых с помощью ИИ</h4>
<p class="text-on-surface-variant font-body text-sm line-clamp-2">Как делегировать рутину алгоритмам и освободить время для жизни.</p>
</article>
<article class="bg-surface-container-lowest rounded-xl p-4 transition-all hover:bg-surface-container-low group">
<div class="relative h-48 mb-4 overflow-hidden rounded-lg">
<img class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110" data-alt="person using a digital tablet at a wooden cafe table, soft natural light, cozy atmosphere, productive yet relaxed mood" src="https://lh3.googleusercontent.com/aida-public/AB6AXuB42wxmv21nGnzxDGKukOyjhWBZs_CWz-H0oQEqha9BplnYiNpqxtkWZPAt0Z45DYu-4sqFU7mSl8c7_aHD4xJhc8GC2l02rf2MByAgaba3s0wpSAxeBcCBn6G6up1pkeB648fJV48HRMLmasmlXQ4bn_38rsZ3-eGzdKSGofaT9RhevfZIQ4l69eWdIJe9Z1xbAhffFcBB0gA0WLGc6mbLcFp4meTyUgKImTPAZDQalr_6NFsGoPl6MkDudJxIgtEgzRYFOxjjqLZO"/>
</div>
<div class="flex items-center gap-2 mb-2 text-on-surface-variant font-label text-xs font-semibold uppercase tracking-wider">
<span class="material-symbols-outlined text-sm">work_history</span>
<span>Продуктивность</span>
</div>
<h4 class="text-xl font-headline font-bold mb-2">Цифровой детокс без вреда для карьеры</h4>
<p class="text-on-surface-variant font-body text-sm line-clamp-2">Практические советы по ограничению экранного времени.</p>
</article>
</div>
</section>
<!-- What to Listen Section -->
<section class="mb-16">
<div class="bg-primary rounded-xl p-8 md:p-12 relative overflow-hidden">
<div class="absolute top-0 right-0 w-1/3 h-full bg-gradient-to-l from-primary-container/30 to-transparent pointer-events-none"></div>
<div class="relative z-10">
<h2 class="text-3xl font-headline font-bold text-white mb-2">Что послушать</h2>
<p class="text-white/70 mb-8 max-w-lg">Наши редакторы собрали плейлисты под любое настроение — от утреннего кофе до ночной поездки.</p>
<div class="flex gap-6 overflow-x-auto hide-scrollbar pb-4 -mx-4 px-4">
<!-- Music Card 1 -->
<div class="flex-none w-64 bg-white/10 backdrop-blur-md rounded-xl p-4 border border-white/5 group cursor-pointer hover:bg-white/20 transition-all">
<div class="aspect-square rounded-lg mb-4 overflow-hidden shadow-xl">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform" data-alt="close-up of a professional electric guitar against a dark moody stage background, purple and blue ambient lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCtQmT0DkvErf2yjC8L0z3Wx3GwfYvqx3DVrF4S64QB6cHxq0GsqsWOHUP1HWfXqqeUsrL3AF4g2z9ORURMtEgBzNHRN9jI6MI7YJk5Rw6uuAkn9Ni3hCz-X-JTDBgdBnGsjie6dEmDnBzIMSlBi6SfboRt_OqvE61ufA84yFGdHsff7jSFVyp4BP9SBgnpwvg5oCS97Syn_8XoCtlNWAU6HCDA9FIrQ8E9pA21nxbLzPL9WGpGGf6IILXPZnqi5TNCSggcUchgj1A1"/>
</div>
<h5 class="text-white font-bold mb-1">Инди-утро</h5>
<p class="text-white/60 text-xs font-label">24 ТРЕКА • 1 Ч 20 МИН</p>
</div>
<!-- Music Card 2 -->
<div class="flex-none w-64 bg-white/10 backdrop-blur-md rounded-xl p-4 border border-white/5 group cursor-pointer hover:bg-white/20 transition-all">
<div class="aspect-square rounded-lg mb-4 overflow-hidden shadow-xl">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform" data-alt="colorful concert lighting beams through a thin haze at a live music event, energetic atmosphere, blurred stage background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCFOvoXwiOEskY-5PcPptyebsNoAa2w86nuMWJvOW0Mt3wr-GuCWEweUM6bW9Gqgmd0l23giRRk_34fQZbMrZhyAFs1aMkVmBBTGOUHi1Ozvj2ZcusozqXAPw2BaDgDK-pHb2mPFcUvF1NL6SSwAw4_VnEwnGdT6oUKj3U87FBGLswJJjb0-COdr42aH0KK1MQv4A7wW4m9SycWQux4DX4XZv40CwGi21ZV3Tlr7vkTUJH7oj_FAH1qqi1kZNcvZAZI0JPNBoqZ069D"/>
</div>
<h5 class="text-white font-bold mb-1">Лоу-фай вайб</h5>
<p class="text-white/60 text-xs font-label">40 ТРЕКОВ • 2 Ч 15 МИН</p>
</div>
<!-- Music Card 3 -->
<div class="flex-none w-64 bg-white/10 backdrop-blur-md rounded-xl p-4 border border-white/5 group cursor-pointer hover:bg-white/20 transition-all">
<div class="aspect-square rounded-lg mb-4 overflow-hidden shadow-xl">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform" data-alt="professional DJ controller decks with glowing buttons in a dark club setting, vibrant red and blue accent lights" src="https://lh3.googleusercontent.com/aida-public/AB6AXuC29aVgmcgFLtTUZ2m2hVEDhTQ3JLyz5AG2By0Vahpy_FHxwA3a37XJ_fepMG7JEp7sPzafimcD8bfSYEECENIWBIV85B9zi7lYIljJfkFYKy2RRdwe9Z5ltGreZAvsZZz1kwdWdR-NtIlUQLMx8B6bhC9kkGzkiwIiVH6acFpfZykRJ_we30uFL1kT6KxzH6cOoXV6I4sUpR_RiZz8byzZn5L6-V6LCstjYXd_lEScRU00IVtHS9z2Bo0-j_b6SPEJuQaK_izFOWAr"/>
</div>
<h5 class="text-white font-bold mb-1">Ночной драйв</h5>
<p class="text-white/60 text-xs font-label">18 ТРЕКОВ • 55 МИН</p>
</div>
</div>
</div>
</div>
</section>
</main>
<!-- BottomNavBar -->
<nav class="fixed bottom-0 left-0 w-full z-50 flex justify-around items-end px-4 pb-6 pt-2 bg-[#f7f9fc]/80 dark:bg-[#191c1e]/80 backdrop-blur-xl shadow-[0_-12px_32px_rgba(25,28,30,0.06)] rounded-t-[3rem] md:hidden">
<div class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity">
<span class="material-symbols-outlined" data-icon="sports_soccer">sports_soccer</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Спорт</span>
</div>
<div class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity">
<span class="material-symbols-outlined" data-icon="sports_esports">sports_esports</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Игры</span>
</div>
<div class="flex flex-col items-center justify-center bg-[#183ce6] text-white rounded-full p-3 scale-110 -translate-y-2 transition-transform">
<span class="material-symbols-outlined" data-icon="devices">devices</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Техно</span>
</div>
<div class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity">
<span class="material-symbols-outlined" data-icon="music_note">music_note</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Музыка</span>
</div>
<div class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity">
<span class="material-symbols-outlined" data-icon="movie">movie</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Кино</span>
</div>
</nav>
<!-- FAB (Suppressed based on logic for feed, but optional for 'Create/Post') -->
<div class="fixed bottom-24 right-8 md:bottom-8 md:right-8 group">
<button class="bg-primary text-white w-14 h-14 rounded-full flex items-center justify-center shadow-xl transition-all duration-300 hover:scale-110 active:scale-95">
<span class="material-symbols-outlined" data-icon="add">add</span>
</button>
</div>
</body></html>

<!-- Главная лента -->
<!DOCTYPE html>

<html class="light" lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;700;800&amp;family=Manrope:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "error-container": "#ffdad6",
                    "inverse-on-surface": "#eff1f4",
                    "secondary": "#006879",
                    "tertiary": "#006153",
                    "on-secondary-fixed-variant": "#004e5b",
                    "primary": "#183ce6",
                    "on-surface": "#191c1e",
                    "on-error": "#ffffff",
                    "on-primary-fixed": "#000f5d",
                    "on-surface-variant": "#444656",
                    "surface-container": "#eceef1",
                    "on-tertiary": "#ffffff",
                    "inverse-primary": "#bbc3ff",
                    "on-error-container": "#93000a",
                    "surface-container-lowest": "#ffffff",
                    "primary-container": "#3d5afe",
                    "background": "#f7f9fc",
                    "secondary-container": "#54e0fd",
                    "inverse-surface": "#2d3133",
                    "surface": "#f7f9fc",
                    "outline": "#757688",
                    "surface-variant": "#e0e3e6",
                    "on-primary-container": "#f1f0ff",
                    "on-secondary-container": "#006170",
                    "on-tertiary-fixed-variant": "#005045",
                    "tertiary-fixed": "#9bf3df",
                    "on-secondary": "#ffffff",
                    "tertiary-container": "#187b6b",
                    "error": "#ba1a1a",
                    "secondary-fixed": "#a8edff",
                    "on-primary-fixed-variant": "#002ccd",
                    "surface-bright": "#f7f9fc",
                    "surface-container-highest": "#e0e3e6",
                    "on-primary": "#ffffff",
                    "primary-fixed-dim": "#bbc3ff",
                    "surface-tint": "#2848ee",
                    "outline-variant": "#c5c5d9",
                    "surface-dim": "#d8dadd",
                    "on-tertiary-container": "#b8ffee",
                    "surface-container-high": "#e6e8eb",
                    "primary-fixed": "#dee0ff",
                    "on-background": "#191c1e",
                    "on-secondary-fixed": "#001f26",
                    "surface-container-low": "#f2f4f7",
                    "secondary-fixed-dim": "#49d7f4",
                    "tertiary-fixed-dim": "#7fd6c3",
                    "on-tertiary-fixed": "#00201b"
            },
            "borderRadius": {
                    "DEFAULT": "1rem",
                    "lg": "2rem",
                    "xl": "3rem",
                    "full": "9999px"
            },
            "fontFamily": {
                    "headline": ["Plus Jakarta Sans"],
                    "body": ["Manrope"],
                    "label": ["Manrope"]
            }
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .glass-card {
            background: rgba(255, 255, 255, 0.8);
            backdrop-filter: blur(24px);
        }
    </style>
</head>
<body class="bg-surface font-body text-on-surface">
<!-- TopAppBar -->
<nav class="fixed top-0 w-full z-50 bg-[#f7f9fc]/80 dark:bg-[#191c1e]/80 backdrop-blur-xl transition-all duration-300 ease-in-out">
<div class="flex justify-between items-center px-6 h-16 w-full max-w-7xl mx-auto">
<div class="flex items-center gap-4">
<button class="p-2 hover:bg-[#f2f4f7]/50 dark:hover:bg-[#e6e8eb]/10 rounded-full transition-all">
<span class="material-symbols-outlined text-[#183ce6] dark:text-[#3d5afe]">search</span>
</button>
</div>
<div class="font-['Plus_Jakarta_Sans'] font-bold tracking-tight text-2xl font-extrabold text-[#183ce6] dark:text-[#3d5afe]">
                Портал
            </div>
<div class="flex items-center">
<div class="w-10 h-10 rounded-full bg-primary-container flex items-center justify-center text-white font-bold overflow-hidden">
<img alt="User Avatar" class="w-full h-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBEMqudGP03UfqlFwy-WxWAbG4rTIF-gbzG3tAR5L3xcveCjhSpmk0lzqz29LSV7TYdJf647kKAzo5Oxb6r4xYhnV07wMifY9xFMqu5STp-4UwyUZMZfUPO9s4d7ZTUdAgglvNM0n6diGvdele507BJiuVfAXQHzY65Pyun6LTioo4in4SKsDzcloYh-nCiD0cW2f-oT5RhOXRrfl26jhhvOuIGdLAl-6K7SEA0_DizBUYboFcF_gOpsN8SgPVHLiK3GTqrT6LpnuKk"/>
</div>
</div>
</div>
</nav>
<main class="pt-24 pb-32 px-6 max-w-7xl mx-auto">
<!-- Hero Section -->
<header class="mb-12">
<h1 class="font-headline text-[3.5rem] font-extrabold tracking-tighter text-on-surface leading-none mb-4">
                Техно &amp; Игры
            </h1>
<p class="text-on-surface-variant text-lg max-w-2xl leading-relaxed">
                Свежие обзоры девайсов, которые делают жизнь проще, и игры, в которых хочется раствориться. Отдыхаем с умом.
            </p>
</header>
<!-- Bento Grid Layout -->
<div class="grid grid-cols-1 md:grid-cols-12 gap-6">
<!-- Featured Review: Asymmetric Span -->
<article class="md:col-span-8 group cursor-pointer">
<div class="relative overflow-hidden rounded-xl bg-surface-container-lowest transition-transform duration-300 hover:scale-[1.01]">
<div class="aspect-[16/9] w-full relative">
<img alt="Tech Review" class="w-full h-full object-cover" data-alt="Modern sleek workstation with minimalist mechanical keyboard and curved ultra-wide monitor in soft blue ambient lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBR2sSVYOru69ek0vd8JuOrqLX3qQ2eIFxGsCYGTRs8_dVMxpWtVXjHJKpkJwaDFwrsLk44nmsUlVnSzpCrIEqfC0bTWUWXznMsz7jpQ-XlUTsZuo4GiPo5JJHrp5puASludl8A1641fD-FxqRrjkMgX5UkK5m3OeZ0pudsBQObYHpp00Dk7TwnLKDTIJ6nA6CkDLdWdFknBiPY9K_uNzWu8aoSHWtqCKK3mwwzQjf6PFCs2xj5vAIWRrNZsTDD48_rQxwnrxG3Mydf"/>
<div class="absolute inset-0 bg-gradient-to-t from-black/60 via-transparent to-transparent"></div>
<div class="absolute top-6 left-6">
<span class="bg-secondary-container text-on-secondary-container px-4 py-1.5 rounded-full text-xs font-bold uppercase tracking-widest">
                                Обзор
                            </span>
</div>
</div>
<div class="p-8 glass-card absolute bottom-0 left-0 right-0 m-6 rounded-lg">
<h2 class="font-headline text-2xl font-bold mb-2 text-on-surface">Новый уровень продуктивности: Тестируем флагманский монитор</h2>
<p class="text-on-surface-variant line-clamp-2 mb-4">Почему 49 дюймов — это не роскошь, а идеальный инструмент для тех, кто ценит свой комфорт и время.</p>
<div class="flex items-center gap-4 text-sm font-semibold text-primary">
<span>Читать 8 мин</span>
<span class="material-symbols-outlined text-sm">arrow_forward</span>
</div>
</div>
</div>
</article>
<!-- Tech News Vertical Card -->
<article class="md:col-span-4 bg-surface-container-lowest rounded-xl p-6 flex flex-col justify-between">
<div>
<span class="text-tertiary font-bold text-xs uppercase tracking-widest mb-4 block">Тренды</span>
<h3 class="font-headline text-xl font-bold mb-4 leading-snug">AI больше не игрушка: Как нейросети меняют наше утро</h3>
<p class="text-on-surface-variant text-sm leading-relaxed mb-6">От умных кофеварок до персональных ассистентов, которые знают ваш график лучше вас.</p>
</div>
<div class="relative rounded-lg overflow-hidden h-48">
<img alt="AI Tech" class="w-full h-full object-cover" data-alt="Abstract visualization of neural networks glowing with cyan and deep blue light on a dark background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCVMMr_SX1hy26fRvv0CHF-nYAwiaa9WmAm7shA-6ASJCtbqhWOPzLZdvFqm0U227jL075IE4-UvOTkR4elWogMlLlAvSgWJwNaxxjASn69vObN32v7D2ITpW5Jj7QcJpwcgUUZgsMLrhSY9a3spslWLC-2Ww-Udxobtux2mbdAuYHO4bkAdGaXwPMJGz8pXTzIiucZg4PEEABjs0cORzSpkmB2jaPVpv1cIJDqfJYxeh47-mvRC2dFUBUP3wgCUZPXSfZzKeESIH2x"/>
</div>
</article>
<!-- Games Section: Masonry-style Grid -->
<div class="md:col-span-12 mt-12 mb-6">
<div class="flex justify-between items-end mb-8">
<h2 class="font-headline text-3xl font-bold tracking-tight">Релизы недели</h2>
<button class="flex items-center gap-2 text-primary font-bold hover:gap-3 transition-all">
                        Все игры <span class="material-symbols-outlined">chevron_right</span>
</button>
</div>
</div>
<!-- Game Card 1 -->
<article class="md:col-span-4 group">
<div class="bg-surface-container-low rounded-xl overflow-hidden hover:bg-surface-container-high transition-colors p-4">
<div class="rounded-lg overflow-hidden mb-4 aspect-square">
<img alt="Game Title" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500" data-alt="Cinematic shot of a mythical dragon soaring through a vibrant sunset sky over a fantasy mountain range" src="https://lh3.googleusercontent.com/aida-public/AB6AXuD2VhK7QMWGiDY_Ak5Bo1bo3XTa89cjvRiktB3VDBkxIWnKzrrOSsomKEZ9UYuGO488Bmv0Q5ZSA16ZNPJfOCG-_pS8YeaBYMcnWc1FPoGY8Rm6TnfaIyJa5MIG6XUE4C4_6KvqZL9hdBamggAfFwrDp89rhkDWFqFClIgCuVyL7P61aCyucKgYZriv4J1YX8zf4TFDlmD_nrtOkAUKIDTa9BMNgAFSclgwXtzP57QuQ-IXMfxeS8uZOr76eDx94p8gbGDI1haBa-S5"/>
</div>
<div class="flex justify-between items-start mb-2">
<h4 class="font-headline text-lg font-bold">Dragon's Wake</h4>
<span class="bg-primary/10 text-primary px-2 py-0.5 rounded text-[10px] font-bold">RPG</span>
</div>
<p class="text-on-surface-variant text-sm mb-4">Погружение в открытый мир, где каждое решение меняет климат планеты.</p>
<div class="flex items-center justify-between">
<span class="text-on-surface font-bold">9.2 / 10</span>
<button class="p-2 rounded-full bg-white text-primary shadow-sm">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">play_arrow</span>
</button>
</div>
</div>
</article>
<!-- Game Card 2 -->
<article class="md:col-span-4 group">
<div class="bg-surface-container-low rounded-xl overflow-hidden hover:bg-surface-container-high transition-colors p-4">
<div class="rounded-lg overflow-hidden mb-4 aspect-square">
<img alt="Game Title" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500" data-alt="Cyberpunk city street at night with neon signs reflecting in puddles and a sleek futuristic car" src="https://lh3.googleusercontent.com/aida-public/AB6AXuD7-xw38hiNUvd5SlvW4GhEW-VlfWI72607jTNW8GSWdZaCErFUIcYUUc-7eFqhqMW4EyekL-QlPI6V8baLr0i12TXTYieRp12oGHI_r2oHk0UZYUdf2nR--A1avmsCIhNCnbdO6E1axJYX32j9n3HoYJCnQvYMZqcQFXEFWujMmAa_2ZNz0FwCMYai_RIq7hRR5uOdYwNGQ0k-XRsj745DnWo5f5ZqRmhQkX38nvvpqiDJCHudd7l8f6IVIClbYsKwm2hfwqosCBTx"/>
</div>
<div class="flex justify-between items-start mb-2">
<h4 class="font-headline text-lg font-bold">Neon Pulse</h4>
<span class="bg-secondary/10 text-secondary px-2 py-0.5 rounded text-[10px] font-bold">Action</span>
</div>
<p class="text-on-surface-variant text-sm mb-4">Ритм-экшен в декорациях будущего, где музыка — ваше главное оружие.</p>
<div class="flex items-center justify-between">
<span class="text-on-surface font-bold">8.5 / 10</span>
<button class="p-2 rounded-full bg-white text-primary shadow-sm">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">play_arrow</span>
</button>
</div>
</div>
</article>
<!-- Game Card 3 -->
<article class="md:col-span-4 group">
<div class="bg-surface-container-low rounded-xl overflow-hidden hover:bg-surface-container-high transition-colors p-4">
<div class="rounded-lg overflow-hidden mb-4 aspect-square">
<img alt="Game Title" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500" data-alt="Collection of vintage 8-bit game consoles and colorful cartridges arranged on a wooden desk" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDrIlWThqd2mgkiTHs8fP1n0QfR3Da6hIrht2_m10nKnYrrWi-AVxAe31W9VbPY16LopuUuO323inhWF4LVy41rm-lH6tVuGDDMvIn-FolJHvgRXMX9D-K6t_HfLSpDf_J49HEwR02tV9cPC0fZZRd5Ylc1QHDYokCvaANj2pcL_HRxTkgrpXuIqvlAQUfb8JOTE2wuhpR2LRHj3fwR_bfK7PUEVUTmwOb3VC6TxyupIhxnMGsyQQmACu8D0jzzTWbp-Rsq6-Nsfwvb"/>
</div>
<div class="flex justify-between items-start mb-2">
<h4 class="font-headline text-lg font-bold">Retro Revival</h4>
<span class="bg-tertiary/10 text-tertiary px-2 py-0.5 rounded text-[10px] font-bold">Indie</span>
</div>
<p class="text-on-surface-variant text-sm mb-4">Пиксельная ностальгия, переосмысленная для современных консолей.</p>
<div class="flex items-center justify-between">
<span class="text-on-surface font-bold">8.8 / 10</span>
<button class="p-2 rounded-full bg-white text-primary shadow-sm">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">play_arrow</span>
</button>
</div>
</div>
</article>
</div>
</main>
<!-- FAB: Contextual to Tech/Games -->
<button class="fixed bottom-28 right-8 w-14 h-14 rounded-full bg-primary-container text-white shadow-xl flex items-center justify-center hover:scale-110 transition-transform z-40">
<span class="material-symbols-outlined">add</span>
</button>
<!-- BottomNavBar -->
<nav class="fixed bottom-0 left-0 w-full z-50 flex justify-around items-end px-4 pb-6 pt-2 bg-[#f7f9fc]/80 dark:bg-[#191c1e]/80 backdrop-blur-xl rounded-t-[3rem] shadow-[0_-12px_32px_rgba(25,28,30,0.06)]">
<div class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity cursor-pointer">
<span class="material-symbols-outlined mb-1">sports_soccer</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider">Спорт</span>
</div>
<div class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity cursor-pointer">
<span class="material-symbols-outlined mb-1">sports_esports</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider">Игры</span>
</div>
<!-- Active Tab: Techno (Using logic to map "Tech" to "Техно") -->
<div class="flex flex-col items-center justify-center bg-[#183ce6] text-white rounded-full p-3 scale-110 -translate-y-2 transition-transform cursor-pointer">
<span class="material-symbols-outlined mb-1">devices</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider">Техно</span>
</div>
<div class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity cursor-pointer">
<span class="material-symbols-outlined mb-1">music_note</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider">Музыка</span>
</div>
<div class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity cursor-pointer">
<span class="material-symbols-outlined mb-1">movie</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider">Кино</span>
</div>
</nav>
</body></html>

<!-- Техно и Игры -->
<!DOCTYPE html>

<html class="light" lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Спорт и Движение — Жизнь на чиле</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;700;800&amp;family=Manrope:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "error-container": "#ffdad6",
                        "inverse-on-surface": "#eff1f4",
                        "secondary": "#006879",
                        "tertiary": "#006153",
                        "on-secondary-fixed-variant": "#004e5b",
                        "primary": "#183ce6",
                        "on-surface": "#191c1e",
                        "on-error": "#ffffff",
                        "on-primary-fixed": "#000f5d",
                        "on-surface-variant": "#444656",
                        "surface-container": "#eceef1",
                        "on-tertiary": "#ffffff",
                        "inverse-primary": "#bbc3ff",
                        "on-error-container": "#93000a",
                        "surface-container-lowest": "#ffffff",
                        "primary-container": "#3d5afe",
                        "background": "#f7f9fc",
                        "secondary-container": "#54e0fd",
                        "inverse-surface": "#2d3133",
                        "surface": "#f7f9fc",
                        "outline": "#757688",
                        "surface-variant": "#e0e3e6",
                        "on-primary-container": "#f1f0ff",
                        "on-secondary-container": "#006170",
                        "on-tertiary-fixed-variant": "#005045",
                        "tertiary-fixed": "#9bf3df",
                        "on-secondary": "#ffffff",
                        "tertiary-container": "#187b6b",
                        "error": "#ba1a1a",
                        "secondary-fixed": "#a8edff",
                        "on-primary-fixed-variant": "#002ccd",
                        "surface-bright": "#f7f9fc",
                        "surface-container-highest": "#e0e3e6",
                        "on-primary": "#ffffff",
                        "primary-fixed-dim": "#bbc3ff",
                        "surface-tint": "#2848ee",
                        "outline-variant": "#c5c5d9",
                        "surface-dim": "#d8dadd",
                        "on-tertiary-container": "#b8ffee",
                        "surface-container-high": "#e6e8eb",
                        "primary-fixed": "#dee0ff",
                        "on-background": "#191c1e",
                        "on-secondary-fixed": "#001f26",
                        "surface-container-low": "#f2f4f7",
                        "secondary-fixed-dim": "#49d7f4",
                        "tertiary-fixed-dim": "#7fd6c3",
                        "on-tertiary-fixed": "#00201b"
                    },
                    "borderRadius": {
                        "DEFAULT": "1rem",
                        "lg": "2rem",
                        "xl": "3rem",
                        "full": "9999px"
                    },
                    "fontFamily": {
                        "headline": ["Plus Jakarta Sans"],
                        "body": ["Manrope"],
                        "label": ["Manrope"]
                    }
                }
            }
        }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        body { font-family: 'Manrope', sans-serif; background-color: #f7f9fc; color: #191c1e; overflow-x: hidden; }
        h1, h2, h3 { font-family: 'Plus Jakarta Sans', sans-serif; }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="bg-surface text-on-surface selection:bg-primary-container selection:text-on-primary-container">
<!-- TopAppBar -->
<header class="fixed top-0 w-full z-50 bg-[#f7f9fc]/80 dark:bg-[#191c1e]/80 backdrop-blur-xl">
<div class="flex justify-between items-center px-6 h-16 w-full max-w-7xl mx-auto">
<div class="flex items-center gap-4">
<button class="p-2 transition-all duration-300 ease-in-out hover:bg-[#f2f4f7]/50 dark:hover:bg-[#e6e8eb]/10 rounded-full">
<span class="material-symbols-outlined text-[#183ce6] dark:text-[#3d5afe]">search</span>
</button>
</div>
<div class="text-2xl font-extrabold text-[#183ce6] dark:text-[#3d5afe] font-['Plus_Jakarta_Sans'] tracking-tight">Портал</div>
<div class="flex items-center">
<div class="w-10 h-10 rounded-full bg-surface-container-highest flex items-center justify-center overflow-hidden border-2 border-primary/10">
<img class="w-full h-full object-cover" data-alt="Close up portrait of a smiling friendly person with natural lighting and soft blurred background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBSLRtq1LSWUF0jp2xFH4VoKUA5JYhqwScEttBgaS6LgdHcV2h8nGVvA01dIgGhGzIDGyQzUlo-cRS_3cWm7Z8ygGRx70zAA50GzixFjzcchYGZ3OFGDVjsEMkLysVX-BOzBuMXQ3Jd5e6rHVmwDoSKWtIXILvYgx6Ul11wAflz5fqkvIoc_hQI88w8qOcP0WdaAxvM9rEFqAhbFZxp4rRcW5EImQUxk1zmSmEHjTZcVVznj12ehoImHy3jWP3WZog-znhOyPSSp4g9"/>
</div>
</div>
</div>
</header>
<main class="pt-24 pb-32 px-4 max-w-7xl mx-auto">
<!-- Hero Section -->
<section class="relative mb-16 group">
<div class="bg-gradient-to-br from-primary to-primary-container rounded-xl overflow-hidden min-h-[500px] flex items-center relative p-8 md:p-16">
<div class="z-10 max-w-2xl">
<span class="inline-block px-4 py-1.5 bg-secondary-container text-on-secondary-container rounded-full text-xs font-bold uppercase tracking-widest mb-6">Lifestyle Focus</span>
<h1 class="text-white text-5xl md:text-7xl font-extrabold tracking-tight mb-6 leading-[1.1]">Спорт и Движение</h1>
<p class="text-on-primary-container text-lg md:text-xl leading-relaxed mb-10 opacity-90">
                        Забудьте про изнурительные тренировки. Мы здесь ради эндорфинов, прогулок в парке и радости от того, что тело просто живет. Жизнь на чиле — это когда спорт в удовольствие.
                    </p>
<div class="flex flex-wrap gap-4">
<button class="bg-white text-primary px-8 py-4 rounded-full font-bold transition-transform hover:scale-105">Начать легко</button>
<button class="bg-primary-container/20 text-white border border-white/20 backdrop-blur-md px-8 py-4 rounded-full font-bold hover:bg-white/10 transition-all">Узнать больше</button>
</div>
</div>
<div class="absolute right-0 bottom-0 top-0 w-1/2 hidden lg:block overflow-hidden rounded-l-xl">
<img class="w-full h-full object-cover opacity-80 mix-blend-lighten" data-alt="Athletic person in modern sportswear stretching in a sun-drenched studio with soft shadows and minimal aesthetic" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDswbVFZaFsyG-Z7y81w1gElsE6jjAsdgQKoYUdOUbSfGqe5uHo-e2IeQ6WlMpkgcz4f9rwfvFTm3hNQn_zyrvEyFYZHgW44hJLnmAehgg7P3RatxynsNUi1xv5xjRGuhY_iO6c5B47IzZQkDDVw75SzxPuzzJXfrG9EDAYmGAwIke7R8h4VOehD9v52vVpu2ZmO-cfvYwHSoC1rxZNPmIkYaXjX2yPo9LhCzjSQsjTEG5kCxDaqz3m3KOAZC70TZRNs7zRNXst5aCL"/>
</div>
</div>
</section>
<!-- Bento Grid Layout -->
<div class="grid grid-cols-1 md:grid-cols-12 gap-6 mb-16">
<!-- Card 1: Jogging -->
<div class="md:col-span-8 bg-surface-container-lowest rounded-xl p-8 flex flex-col md:flex-row gap-8 items-center group cursor-pointer hover:shadow-xl transition-all duration-300">
<div class="w-full md:w-1/2 aspect-video rounded-lg overflow-hidden">
<img class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-700" data-alt="Young person jogging through a scenic misty park at sunrise with soft golden rays filtering through trees" src="https://lh3.googleusercontent.com/aida-public/AB6AXuB_avTlmwImL1JbYH7Xm8bVCKGiwrWYaRoSYnfYocqIRYbqa6hXVgkHVD3oAwtLgXxrdU_CaAlW9ze12oJn6RnWYFAtVbglSicEgnbWCVnVW7gxc4q408cGEZDP9jxJE81peyaq9Da1FJeRw0RX7MfR2P7WJNAXqXlZrGFQnFMbynq3W8C-lTMBJ0JV7a9Ctk9eF6fcnnmKrUXhKGOTcqHgbSXhBLnYtcES29pfmUVIO1JYS5iznngZ7uhdGLvKgYndaepnNtM68vhn"/>
</div>
<div class="w-full md:w-1/2">
<h3 class="text-2xl font-bold mb-4 text-on-surface">Бег без одышки</h3>
<p class="text-on-surface-variant leading-relaxed mb-6">Как превратить утреннюю пробежку в медитацию, а не в пытку. Секреты темпа, который приносит радость.</p>
<div class="flex items-center gap-2 text-primary font-bold">
<span>Читать статью</span>
<span class="material-symbols-outlined">arrow_forward</span>
</div>
</div>
</div>
<!-- Card 2: Gym Vibes -->
<div class="md:col-span-4 bg-tertiary-container rounded-xl p-8 flex flex-col justify-between text-white relative overflow-hidden group">
<div class="absolute top-0 right-0 p-4 opacity-20">
<span class="material-symbols-outlined text-8xl" style="font-variation-settings: 'FILL' 1;">fitness_center</span>
</div>
<div class="relative z-10">
<h3 class="text-2xl font-bold mb-4">Тренажерка для души</h3>
<p class="opacity-80 mb-8">Почему 20 минут веса лучше часа кардио, если ваша цель — просто чувствовать себя бодро.</p>
</div>
<button class="bg-white/20 backdrop-blur-xl border border-white/30 p-4 rounded-full w-fit group-hover:bg-white group-hover:text-tertiary-container transition-all">
<span class="material-symbols-outlined">add</span>
</button>
</div>
<!-- Card 3: Well-being Chips/Tags -->
<div class="md:col-span-4 bg-surface-container-low rounded-xl p-8">
<h3 class="text-xl font-bold mb-6">Что сегодня?</h3>
<div class="flex flex-wrap gap-3">
<span class="px-6 py-3 bg-secondary-container text-on-secondary-container rounded-full text-sm font-semibold cursor-pointer hover:opacity-80 transition-opacity">Йога</span>
<span class="px-6 py-3 bg-white text-on-surface-variant rounded-full text-sm font-semibold border border-outline-variant/20 shadow-sm cursor-pointer hover:bg-secondary-container transition-all">Бадминтон</span>
<span class="px-6 py-3 bg-white text-on-surface-variant rounded-full text-sm font-semibold border border-outline-variant/20 shadow-sm cursor-pointer hover:bg-secondary-container transition-all">Плавание</span>
<span class="px-6 py-3 bg-white text-on-surface-variant rounded-full text-sm font-semibold border border-outline-variant/20 shadow-sm cursor-pointer hover:bg-secondary-container transition-all">Велосипед</span>
<span class="px-6 py-3 bg-white text-on-surface-variant rounded-full text-sm font-semibold border border-outline-variant/20 shadow-sm cursor-pointer hover:bg-secondary-container transition-all">Растяжка</span>
</div>
</div>
<!-- Card 4: Video Insight (Asymmetric) -->
<div class="md:col-span-8 relative rounded-xl overflow-hidden bg-on-surface">
<img class="w-full h-full object-cover opacity-50" data-alt="High angle view of a yoga mat and water bottle on a clean wooden floor in a bright minimalist studio" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAcqk7oIaZwaSCrGu3HsAnJ7GZnorAATaIlFYzt0XjPBGQ-lK17FNFnamEICh6XpaZ7pkFEA2d9brYgTfsuFYdeJhFJjA2qWwQekxPwqzBCGZcbQ2GJ62sgyQPPqm-uZeR4yf-QSNWonTyDv_fE1RrFAX-q6c4w4RfqBmq6wLiCnKQ7fv7cDZwmvIpdp8Bt9JsxjbfrRgT7L-gC0YrQw0N7K05OrsrBibrlCE1QZtzZSxLswTu6MgiHMaXRaKuesadc5v_g_EVCE6fJ"/>
<div class="absolute inset-0 p-8 flex flex-col justify-end">
<div class="flex items-center gap-4 mb-4">
<div class="w-16 h-16 bg-primary rounded-full flex items-center justify-center text-white shadow-lg cursor-pointer hover:scale-110 transition-transform">
<span class="material-symbols-outlined text-4xl" style="font-variation-settings: 'FILL' 1;">play_arrow</span>
</div>
<div>
<p class="text-white font-bold text-xl">5 минут для спины</p>
<p class="text-white/70 text-sm">Короткий комплекс для тех, кто много сидит</p>
</div>
</div>
</div>
</div>
</div>
<!-- Quote / Editorial Block -->
<section class="my-20 text-center max-w-3xl mx-auto">
<span class="material-symbols-outlined text-secondary text-5xl mb-6">format_quote</span>
<h2 class="text-3xl md:text-4xl font-bold text-on-surface leading-tight mb-8">
                «Движение — это не долг перед зеркалом, а подарок своему настроению».
            </h2>
<div class="h-1 w-20 bg-secondary mx-auto rounded-full"></div>
</section>
<!-- Newsletter / Community Section (Glassmorphism) -->
<section class="relative bg-surface-container-high rounded-xl p-8 md:p-12 overflow-hidden">
<div class="relative z-10 grid md:grid-cols-2 gap-12 items-center">
<div>
<h2 class="text-3xl font-bold mb-4">Присоединяйтесь к движению чилла</h2>
<p class="text-on-surface-variant text-lg">Получайте еженедельные подборки легких активностей и советы по восстановлению сил.</p>
</div>
<div class="flex flex-col sm:flex-row gap-4">
<input class="flex-grow bg-white border-none rounded-full px-6 py-4 focus:ring-2 focus:ring-primary text-on-surface" placeholder="Ваш e-mail" type="email"/>
<button class="bg-primary text-white font-bold px-8 py-4 rounded-full shadow-lg shadow-primary/20 hover:translate-y-[-2px] transition-all">Подписаться</button>
</div>
</div>
<!-- Decorative circle -->
<div class="absolute -top-24 -right-24 w-64 h-64 bg-secondary/10 rounded-full blur-3xl"></div>
</section>
</main>
<!-- BottomNavBar -->
<nav class="fixed bottom-0 left-0 w-full z-50 flex justify-around items-end px-4 pb-6 pt-2 bg-[#f7f9fc]/80 dark:bg-[#191c1e]/80 backdrop-blur-xl shadow-[0_-12px_32px_rgba(25,28,30,0.06)] rounded-t-[3rem]">
<a class="flex flex-col items-center justify-center bg-[#183ce6] text-white rounded-full p-3 scale-110 -translate-y-2 transition-transform" href="#">
<span class="material-symbols-outlined">sports_soccer</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Спорт</span>
</a>
<a class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity" href="#">
<span class="material-symbols-outlined">sports_esports</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Игры</span>
</a>
<a class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity" href="#">
<span class="material-symbols-outlined">devices</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Техно</span>
</a>
<a class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity" href="#">
<span class="material-symbols-outlined">music_note</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Музыка</span>
</a>
<a class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity" href="#">
<span class="material-symbols-outlined">movie</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Кино</span>
</a>
</nav>
</body></html>

<!-- Спорт и Движение -->
<!DOCTYPE html>

<html class="light" lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600;700;800&amp;family=Manrope:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "error-container": "#ffdad6",
                    "inverse-on-surface": "#eff1f4",
                    "secondary": "#006879",
                    "tertiary": "#006153",
                    "on-secondary-fixed-variant": "#004e5b",
                    "primary": "#183ce6",
                    "on-surface": "#191c1e",
                    "on-error": "#ffffff",
                    "on-primary-fixed": "#000f5d",
                    "on-surface-variant": "#444656",
                    "surface-container": "#eceef1",
                    "on-tertiary": "#ffffff",
                    "inverse-primary": "#bbc3ff",
                    "on-error-container": "#93000a",
                    "surface-container-lowest": "#ffffff",
                    "primary-container": "#3d5afe",
                    "background": "#f7f9fc",
                    "secondary-container": "#54e0fd",
                    "inverse-surface": "#2d3133",
                    "surface": "#f7f9fc",
                    "outline": "#757688",
                    "surface-variant": "#e0e3e6",
                    "on-primary-container": "#f1f0ff",
                    "on-secondary-container": "#006170",
                    "on-tertiary-fixed-variant": "#005045",
                    "tertiary-fixed": "#9bf3df",
                    "on-secondary": "#ffffff",
                    "tertiary-container": "#187b6b",
                    "error": "#ba1a1a",
                    "secondary-fixed": "#a8edff",
                    "on-primary-fixed-variant": "#002ccd",
                    "surface-bright": "#f7f9fc",
                    "surface-container-highest": "#e0e3e6",
                    "on-primary": "#ffffff",
                    "primary-fixed-dim": "#bbc3ff",
                    "surface-tint": "#2848ee",
                    "outline-variant": "#c5c5d9",
                    "surface-dim": "#d8dadd",
                    "on-tertiary-container": "#b8ffee",
                    "surface-container-high": "#e6e8eb",
                    "primary-fixed": "#dee0ff",
                    "on-background": "#191c1e",
                    "on-secondary-fixed": "#001f26",
                    "surface-container-low": "#f2f4f7",
                    "secondary-fixed-dim": "#49d7f4",
                    "tertiary-fixed-dim": "#7fd6c3",
                    "on-tertiary-fixed": "#00201b"
            },
            "borderRadius": {
                    "DEFAULT": "1rem",
                    "lg": "2rem",
                    "xl": "3rem",
                    "full": "9999px"
            },
            "fontFamily": {
                    "headline": ["Plus Jakarta Sans"],
                    "body": ["Manrope"],
                    "label": ["Manrope"]
            }
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .bg-mesh {
            background-color: #f7f9fc;
            background-image: radial-gradient(at 0% 0%, rgba(24, 60, 230, 0.05) 0px, transparent 50%),
                              radial-gradient(at 100% 0%, rgba(0, 104, 121, 0.05) 0px, transparent 50%);
        }
    </style>
</head>
<body class="bg-surface font-body text-on-surface bg-mesh min-h-screen">
<!-- TopAppBar -->
<header class="bg-[#f7f9fc]/80 backdrop-blur-xl fixed top-0 w-full z-50 transition-all duration-300 ease-in-out">
<div class="flex justify-between items-center px-6 h-16 w-full max-w-7xl mx-auto">
<div class="flex items-center gap-4">
<button class="p-2 transition-all duration-300 ease-in-out hover:bg-[#f2f4f7]/50 rounded-full text-[#191c1e]">
<span class="material-symbols-outlined" data-icon="search">search</span>
</button>
<h1 class="text-2xl font-extrabold text-[#183ce6] font-['Plus_Jakarta_Sans'] tracking-tight">Портал</h1>
</div>
<nav class="hidden md:flex gap-8 items-center">
<a class="font-['Manrope'] font-semibold text-[#191c1e] hover:text-[#183ce6] transition-colors" href="#">Спорт</a>
<a class="font-['Manrope'] font-semibold text-[#191c1e] hover:text-[#183ce6] transition-colors" href="#">Игры</a>
<a class="font-['Manrope'] font-semibold text-[#191c1e] hover:text-[#183ce6] transition-colors" href="#">Техно</a>
<a class="font-['Manrope'] font-semibold text-[#183ce6] relative after:content-[''] after:absolute after:-bottom-1 after:left-0 after:w-full after:h-0.5 after:bg-[#183ce6] after:rounded-full" href="#">Медиа</a>
</nav>
<div class="flex items-center gap-3">
<div class="w-10 h-10 rounded-full bg-primary-container flex items-center justify-center text-on-primary-container overflow-hidden">
<img class="w-full h-full object-cover" data-alt="close-up portrait of a friendly man with a warm smile, professional studio lighting with soft bokeh background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCvetvQcAaArokpDMI8zLJM-WPhg5DRWszLRSMdSgxEV3ynDxXCBU_Q2RXiPX-OgL44nwXTt_rU-MGZ3NX5Zq6KVGzUZEY3K6Vxoy7NaK7KLJhp9KXmI3FoTXx08WEkRRkVkjuvokhdbsDZ3vz-GMdA8XMBe2BsTCPgI5iH_KX-nGTWH88KXfZJIhBeu-nyWvcPsFLyWFvysSPi9sUSvrzfJxRXQvVfqgv9gBFRuC7MQ840UUq-wpfwTufv5RgBcMV-qV4N4YSFOmDC"/>
</div>
</div>
</div>
</header>
<main class="pt-24 pb-32 px-6 max-w-7xl mx-auto">
<!-- Hero Section -->
<section class="relative mb-16 overflow-hidden rounded-xl h-[450px] flex items-center">
<div class="absolute inset-0 z-0">
<img class="w-full h-full object-cover" data-alt="vibrant concert atmosphere with silhouettes of crowd against colorful stage lights and soft purple haze" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBWZHJSGLgZay3GAhDck7J1v8h9PYpw5UiVO6B8rkg_0yMIESVwUyPlbZ8Wy15RxueeRnONAyRESaUdIuvY-_adsXi-7E9nf0nhj3S2McZvRboS0u2-ohOfUeohLVrIidb00ryw8YQJSvUcpCfjtKejGInoi9pqpLKRd4EavnzGh3ToEjSLzll8XOala8oaVdd_dKzVuRRynDLA6vbOZ3AllUiOT640PEe-Mz30V7_QzteJoWM_Vhlj3FdIdb-6B3aNpXSS-uoFjT3y"/>
<div class="absolute inset-0 bg-gradient-to-r from-on-surface via-on-surface/40 to-transparent"></div>
</div>
<div class="relative z-10 px-8 md:px-16 max-w-2xl">
<span class="inline-block px-4 py-1.5 rounded-full bg-secondary-container text-on-secondary-container text-xs font-bold uppercase tracking-widest mb-6">Lifestyle hub</span>
<h2 class="text-5xl md:text-7xl font-headline font-extrabold text-white leading-tight mb-6">Музыка &amp; Кино</h2>
<p class="text-lg text-surface-variant font-medium mb-8 leading-relaxed">Твое пространство для глубокого погружения. Лучшие плейлисты для чилла и рекомендации, которые попадут в самое сердце.</p>
<div class="flex flex-wrap gap-4">
<button class="bg-gradient-to-br from-primary to-primary-container text-white px-8 py-4 rounded-full font-bold hover:scale-105 transition-transform">Слушать сейчас</button>
<button class="bg-white/10 backdrop-blur-md text-white px-8 py-4 rounded-full font-bold border border-white/20 hover:bg-white/20 transition-all">Смотреть топ</button>
</div>
</div>
</section>
<!-- Bento Grid: Mood & Playlists -->
<div class="grid grid-cols-1 md:grid-cols-4 gap-6 mb-16">
<!-- Featured Playlist (Large) -->
<div class="md:col-span-2 md:row-span-2 bg-surface-container-lowest rounded-xl p-8 group overflow-hidden relative border border-outline-variant/10">
<div class="relative z-10 h-full flex flex-col justify-between">
<div>
<div class="flex justify-between items-start mb-12">
<h3 class="text-3xl font-headline font-bold text-on-surface max-w-[200px]">Плейлист для вечернего вайба</h3>
<span class="material-symbols-outlined text-primary text-4xl" data-icon="graphic_eq">graphic_eq</span>
</div>
<p class="text-on-surface-variant text-lg">Лоу-фай биты и мягкий джаз для тех, кто ценит спокойствие.</p>
</div>
<div class="flex items-center gap-4">
<button class="w-14 h-14 rounded-full bg-primary text-white flex items-center justify-center hover:scale-110 transition-transform shadow-lg">
<span class="material-symbols-outlined" data-icon="play_arrow" style="font-variation-settings: 'FILL' 1;">play_arrow</span>
</button>
<span class="font-bold text-on-surface">24 трека • 1ч 15мин</span>
</div>
</div>
<div class="absolute top-0 right-0 w-1/2 h-full opacity-10 group-hover:opacity-20 transition-opacity">
<img class="w-full h-full object-cover" data-alt="professional dj equipment close-up with neon blue and purple ambient lighting in a dark room" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDwZtWwG2jy-jPB_Vdlm-_ZdsZpmFY1Lnqj_RN17mJy9doybBlVtEOo0C8zMI66YxfTb8TcyhbrHisXYekjBRxSNslzROfqYZqWCW30ZowJklTeA54a2jiGdFCaZyOBW1pGzV5HMhUztGgnzaK_9hAp5HC2QoAslCUy6aFaPqW48nDZZK0Er4YeOPsCCUQw3GNhqByb738aqMJGeOnBhOaEE7NMt2R9SNaX-B7GQwWffZSHhbRhyEwwh_MFh3U801l2VcNt70bKFU74"/>
</div>
</div>
<!-- Recommendation 1 -->
<div class="md:col-span-2 bg-secondary-container/20 rounded-xl p-6 flex gap-6 items-center border border-secondary-container/30">
<div class="w-32 h-32 rounded-lg overflow-hidden flex-shrink-0">
<img class="w-full h-full object-cover" data-alt="cinematic shot of an old movie projector in a dark room with a beam of light hitting a screen" src="https://lh3.googleusercontent.com/aida-public/AB6AXuC09ShILbZ_hG59Pe4SS-zrocoNStVk5NR7nDPWM2_iDWMObPYQt8qdBcBosoQ_zwZO6q_B8GrNimHrHcdAGmuMOqCpS2sqGzoYfBZDBu9PphzeXN5hqDpbZXlGFMvmYDWT98lq6fUacbwx0FzTc_FZXWMnY0e7dOF8LpecCblvFwHEQSBGC9BOcM7ioOnTeIyxbR5PIhloBopYmz-BGCNCXoSXfde5sCSD8zLxUfS_cB8NI7v1I60hZePfAmuYQ-u6GiEjHq-IpLvl"/>
</div>
<div>
<span class="text-secondary font-bold text-xs uppercase tracking-wider">Кино недели</span>
<h4 class="text-xl font-bold mt-1">Эстетика минимализма</h4>
<p class="text-on-surface-variant text-sm mt-2">Разбор визуального стиля современного авторского кино.</p>
</div>
</div>
<!-- Recommendation 2 -->
<div class="md:col-span-1 bg-surface-container-low rounded-xl p-6 flex flex-col justify-between border border-outline-variant/10">
<span class="material-symbols-outlined text-tertiary" data-icon="podcasts">podcasts</span>
<div>
<h4 class="font-bold mt-4">Chill Cast</h4>
<p class="text-on-surface-variant text-xs mt-1">О музыке без лишних слов.</p>
</div>
</div>
<!-- Recommendation 3 -->
<div class="md:col-span-1 bg-primary-container text-on-primary-container rounded-xl p-6 flex flex-col justify-between overflow-hidden relative">
<div class="relative z-10">
<span class="material-symbols-outlined" data-icon="star" style="font-variation-settings: 'FILL' 1;">star</span>
<h4 class="font-bold mt-4">Топ Чарт</h4>
</div>
<span class="relative z-10 text-4xl font-black opacity-30">#1</span>
<div class="absolute -right-4 -bottom-4 opacity-10">
<span class="material-symbols-outlined text-9xl" data-icon="music_note">music_note</span>
</div>
</div>
</div>
<!-- Asymmetric Content Section -->
<section class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-start">
<div class="lg:col-span-7">
<div class="flex items-center justify-between mb-8">
<h3 class="text-3xl font-headline font-bold">Последние обзоры</h3>
<a class="text-primary font-bold flex items-center gap-2 hover:underline" href="#">
                        Все статьи <span class="material-symbols-outlined">arrow_forward</span>
</a>
</div>
<div class="space-y-12">
<!-- Article 1 -->
<article class="flex flex-col md:flex-row gap-8 items-center group">
<div class="w-full md:w-1/2 overflow-hidden rounded-lg">
<img class="w-full aspect-[4/3] object-cover group-hover:scale-105 transition-transform duration-500" data-alt="cool musician playing guitar in a hazy sunlit room with vintage furniture and warm mood" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDuP7Hu-d4OydxyRr_IieJZwkLnBBcE_wqqC4wl5zdEQtM7BsqYry9W-r0x4vqYxCh04Qo4Ohh-e-kGn6OTwMd4GuYcw5GXT3wuAkifQWAox7bwkRlFiFiUHiY5GB0r8EhHGVHLiQLn3uiCgtiasuvlmFN53qrbYNlQxmAFjx23PtCQDDQBXg7BQbci9tYamDzzTw7XxoDjatfIyBN-cweTMU_5PqwRNdDUtB1vpAlMMs8H4HZskort7lm8naQr8AxCJiAPpkbyKwdm"/>
</div>
<div class="w-full md:w-1/2">
<div class="flex items-center gap-4 mb-4">
<span class="text-tertiary font-bold text-xs uppercase">Музыка</span>
<span class="text-on-surface-variant text-xs">5 мин чтения</span>
</div>
<h4 class="text-2xl font-bold mb-4 leading-tight group-hover:text-primary transition-colors">Почему винил снова в моде: возвращение к истокам</h4>
<p class="text-on-surface-variant leading-relaxed mb-6">Исследуем магию аналогового звука и то, как физические носители меняют наше восприятие альбомов в цифровую эпоху.</p>
<div class="flex items-center gap-3">
<div class="w-8 h-8 rounded-full bg-surface-container-highest overflow-hidden">
<img class="w-full h-full object-cover" data-alt="close-up portrait of a man with glasses and a beard, soft natural daylight, minimalist background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCBaqjQEsqzvjQoyN1xAMtRzwIIF47T4KSS1Nq0Q4WJUSWgv1yXceKo7XpfXS700h9Ha8R8Br93sTjoEy0chdz8yJwUHTTUpE9UU3pEiD59b5bQLT5nkwyXIX5HrxDgisLnugzMeXcWBqz6aNcwKf6j-hUUfjSJxOrJmbfg7A__0Eeez7gJgjtwdww3jRvSONYeggiW9gIQHYOyxEiNTuCS3blV_aNBw6gBe4OMl4iZbUYlzy_e334OV-29sU2Dus0THV0iYOomL50D"/>
</div>
<span class="text-sm font-semibold">Алексей Громов</span>
</div>
</div>
</article>
<!-- Article 2 -->
<article class="flex flex-col md:flex-row-reverse gap-8 items-center group">
<div class="w-full md:w-1/2 overflow-hidden rounded-lg">
<img class="w-full aspect-[4/3] object-cover group-hover:scale-105 transition-transform duration-500" data-alt="close-up of a film reel and vintage cinema gear with dramatic lighting and deep shadows" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBI1P7f13NlnT-BZ8-AXG66whcV0ei8M6odOGiwHB90B0JjyTlApaopXL2MFqiDAD5mVr0pQUlYGVJZ_IGdpk0tfG8w3vKegk1ZUN4yI7EZWLnFolilx7Yj-Yi5Jls0I6nbWG04IZtl924YTsF7dWQ57leEFXhFum4O_7N4UTB5rcotK_awDD23a1-I9KXWyu-sUkTq_uvEyaBo6Auu3r5pFAz5YHhEsbcSRWn8OvGPplhcoUt-MvaCxJ_CsRhK0N7gJ8cuNrMHU1J_"/>
</div>
<div class="w-full md:w-1/2">
<div class="flex items-center gap-4 mb-4">
<span class="text-secondary font-bold text-xs uppercase">Кино</span>
<span class="text-on-surface-variant text-xs">8 мин чтения</span>
</div>
<h4 class="text-2xl font-bold mb-4 leading-tight group-hover:text-primary transition-colors">10 фильмов, которые заставят вас замедлиться</h4>
<p class="text-on-surface-variant leading-relaxed mb-6">Подборка картин в жанре «slow cinema», где каждый кадр — произведение искусства, требующее созерцания.</p>
<div class="flex items-center gap-3">
<div class="w-8 h-8 rounded-full bg-surface-container-highest overflow-hidden">
<img class="w-full h-full object-cover" data-alt="portrait of a young woman with a thoughtful expression, soft indoor lighting, natural tones" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAoYIuttcV3Kd8MMsqUeexfyfTq_7EtTZeF9jjcQFVizSncmR4T6-lZd6JHZtvfi5pquvI1gI2Z3yf3R8Y3n6-whn32Y88OQ746diQub5nAfFumCpIB4BiSUDOb_45le4e1frXblF2_6zFy0Ywu39EkSsb6OK2lnZZAjd4MSjt1Rd47gphXTlng13DWhBT8n8ngzUBGO21GfrsukKTx-kpsg_ypRlS536cxqYZn7IWql0Ze3JBSsCZggKanLEuf0TDTfIrGC017XGcX"/>
</div>
<span class="text-sm font-semibold">Марина Светлова</span>
</div>
</div>
</article>
</div>
</div>
<div class="lg:col-span-5 space-y-8">
<!-- Recommendations Sidebar -->
<div class="bg-white rounded-xl p-8 border border-outline-variant/10">
<h3 class="text-xl font-bold mb-6">Популярные жанры</h3>
<div class="flex flex-wrap gap-2">
<span class="px-4 py-2 bg-surface-container-low rounded-full text-sm font-medium hover:bg-primary hover:text-white cursor-pointer transition-colors">Ambient</span>
<span class="px-4 py-2 bg-surface-container-low rounded-full text-sm font-medium hover:bg-primary hover:text-white cursor-pointer transition-colors">Neo-Jazz</span>
<span class="px-4 py-2 bg-surface-container-low rounded-full text-sm font-medium hover:bg-primary hover:text-white cursor-pointer transition-colors">Indie Folk</span>
<span class="px-4 py-2 bg-surface-container-low rounded-full text-sm font-medium hover:bg-primary hover:text-white cursor-pointer transition-colors">Synthwave</span>
<span class="px-4 py-2 bg-surface-container-low rounded-full text-sm font-medium hover:bg-primary hover:text-white cursor-pointer transition-colors">Lo-Fi</span>
<span class="px-4 py-2 bg-surface-container-low rounded-full text-sm font-medium hover:bg-primary hover:text-white cursor-pointer transition-colors">Dream Pop</span>
</div>
<hr class="my-8 border-outline-variant/10"/>
<h3 class="text-xl font-bold mb-6">Сейчас слушают</h3>
<div class="space-y-4">
<div class="flex items-center gap-4 group cursor-pointer">
<div class="w-12 h-12 rounded bg-surface-container-highest overflow-hidden flex-shrink-0">
<img class="w-full h-full object-cover" data-alt="abstract album cover art with swirling liquid textures of blue and gold" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCobcdZCMNvx3rGrnWVEBNfuBFMmOK3Z1pGiCmdV17D4PGMRBCAkO7tG22Ajt_NVNPPsKe4XCmH9mx2tepUgh5Y2MWTdVKmz6FXEiisx-xZfLdBkOMq1sCdl4SJq2la9W7ZqcEefavBcS7fhiKelFIyBZl121010fIL_QvTK2mkVj8PImCAItw3t-oWFmkHFXMFEpa2af95tC6CfGyq8T0g6YJRijcIVg54XtrJLN5nRWUJVoG_FVcUZVT0ANIzvtxq2xUmgwnAskce"/>
</div>
<div class="flex-grow">
<p class="text-sm font-bold group-hover:text-primary transition-colors">Midnight City</p>
<p class="text-xs text-on-surface-variant">M83</p>
</div>
<span class="material-symbols-outlined text-outline" data-icon="more_vert">more_vert</span>
</div>
<div class="flex items-center gap-4 group cursor-pointer">
<div class="w-12 h-12 rounded bg-surface-container-highest overflow-hidden flex-shrink-0">
<img class="w-full h-full object-cover" data-alt="geometric minimal album cover with a single circle and clean lines on a cream background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCdm3i-ADSzP2JXagN-vCE_AbtVShlL4yBLbqTIj58YLfPjlBLqFM81viKDYqghtV83_b40GGlAbhUHevezkDFdW7Tkp11hECer0uQShEPEKAK8isc5s3wQFwTa0zjWaNlfz_YykjX8nQ_Hiucc3eHg5wqhVUWU35CUAt_FZ5j74ZB0KZMmFwVv-YBF6Rwh9WuRtGqaPxgPCxHAWfFedIoaZxXAbXpe70CxJERsB7kIjwcuEtWJ0Ll3eZD8oGLvAH8x4nkVSUUs4efC"/>
</div>
<div class="flex-grow">
<p class="text-sm font-bold group-hover:text-primary transition-colors">Ocean Drive</p>
<p class="text-xs text-on-surface-variant">Duke Dumont</p>
</div>
<span class="material-symbols-outlined text-outline" data-icon="more_vert">more_vert</span>
</div>
</div>
</div>
<!-- Ad/Promo Card -->
<div class="bg-tertiary-container text-on-tertiary-container rounded-xl p-8 relative overflow-hidden">
<div class="relative z-10">
<h4 class="text-2xl font-headline font-bold mb-4">Chill Premium</h4>
<p class="text-sm mb-6 opacity-90">Слушай без рекламы и в самом высоком качестве. Первая неделя бесплатно.</p>
<button class="bg-white text-tertiary-container px-6 py-3 rounded-full font-bold text-sm shadow-xl">Попробовать</button>
</div>
<div class="absolute -right-8 -bottom-8 opacity-20">
<span class="material-symbols-outlined text-[180px]" data-icon="auto_awesome">auto_awesome</span>
</div>
</div>
</div>
</section>
</main>
<!-- BottomNavBar -->
<nav class="fixed bottom-0 left-0 w-full z-50 flex justify-around items-end px-4 pb-6 pt-2 bg-[#f7f9fc]/80 backdrop-blur-xl md:hidden shadow-[0_-12px_32px_rgba(25,28,30,0.06)] rounded-t-[3rem]">
<a class="flex flex-col items-center justify-center text-[#191c1e] p-2 opacity-70 hover:opacity-100 transition-opacity" href="#">
<span class="material-symbols-outlined" data-icon="sports_soccer">sports_soccer</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Спорт</span>
</a>
<a class="flex flex-col items-center justify-center text-[#191c1e] p-2 opacity-70 hover:opacity-100 transition-opacity" href="#">
<span class="material-symbols-outlined" data-icon="sports_esports">sports_esports</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Игры</span>
</a>
<a class="flex flex-col items-center justify-center text-[#191c1e] p-2 opacity-70 hover:opacity-100 transition-opacity" href="#">
<span class="material-symbols-outlined" data-icon="devices">devices</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Техно</span>
</a>
<a class="flex flex-col items-center justify-center bg-[#183ce6] text-white rounded-full p-3 scale-110 -translate-y-2 transition-transform" href="#">
<span class="material-symbols-outlined" data-icon="music_note" style="font-variation-settings: 'FILL' 1;">music_note</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Музыка</span>
</a>
<a class="flex flex-col items-center justify-center text-[#191c1e] p-2 opacity-70 hover:opacity-100 transition-opacity" href="#">
<span class="material-symbols-outlined" data-icon="movie">movie</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Кино</span>
</a>
</nav>
<!-- Floating Action Button -->
<button class="fixed right-6 bottom-32 md:bottom-12 w-14 h-14 bg-primary-container text-on-primary-container rounded-full shadow-2xl flex items-center justify-center hover:scale-110 transition-transform z-40">
<span class="material-symbols-outlined" data-icon="add" style="font-variation-settings: 'wght' 600;">add</span>
</button>
</body></html>
<!-- Design System -->
<!DOCTYPE html>

<html class="light" lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@700;800&amp;family=Manrope:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "error-container": "#ffdad6",
                        "inverse-on-surface": "#eff1f4",
                        "secondary": "#006879",
                        "tertiary": "#006153",
                        "on-secondary-fixed-variant": "#004e5b",
                        "primary": "#183ce6",
                        "on-surface": "#191c1e",
                        "on-error": "#ffffff",
                        "on-primary-fixed": "#000f5d",
                        "on-surface-variant": "#444656",
                        "surface-container": "#eceef1",
                        "on-tertiary": "#ffffff",
                        "inverse-primary": "#bbc3ff",
                        "on-error-container": "#93000a",
                        "surface-container-lowest": "#ffffff",
                        "primary-container": "#3d5afe",
                        "background": "#f7f9fc",
                        "secondary-container": "#54e0fd",
                        "inverse-surface": "#2d3133",
                        "surface": "#f7f9fc",
                        "outline": "#757688",
                        "surface-variant": "#e0e3e6",
                        "on-primary-container": "#f1f0ff",
                        "on-secondary-container": "#006170",
                        "on-tertiary-fixed-variant": "#005045",
                        "tertiary-fixed": "#9bf3df",
                        "on-secondary": "#ffffff",
                        "tertiary-container": "#187b6b",
                        "error": "#ba1a1a",
                        "secondary-fixed": "#a8edff",
                        "on-primary-fixed-variant": "#002ccd",
                        "surface-bright": "#f7f9fc",
                        "surface-container-highest": "#e0e3e6",
                        "on-primary": "#ffffff",
                        "primary-fixed-dim": "#bbc3ff",
                        "surface-tint": "#2848ee",
                        "outline-variant": "#c5c5d9",
                        "surface-dim": "#d8dadd",
                        "on-tertiary-container": "#b8ffee",
                        "surface-container-high": "#e6e8eb",
                        "primary-fixed": "#dee0ff",
                        "on-background": "#191c1e",
                        "on-secondary-fixed": "#001f26",
                        "surface-container-low": "#f2f4f7",
                        "secondary-fixed-dim": "#49d7f4",
                        "tertiary-fixed-dim": "#7fd6c3",
                        "on-tertiary-fixed": "#00201b"
                    },
                    "borderRadius": {
                        "DEFAULT": "1rem",
                        "lg": "2rem",
                        "xl": "3rem",
                        "full": "9999px"
                    },
                    "fontFamily": {
                        "headline": ["Plus Jakarta Sans"],
                        "body": ["Manrope"],
                        "label": ["Manrope"]
                    }
                },
            },
        }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .hide-scrollbar::-webkit-scrollbar { display: none; }
        .hide-scrollbar { -ms-overflow-style: none; scrollbar-width: none; }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="bg-surface font-body text-on-surface selection:bg-primary-container selection:text-on-primary-container">
<!-- TopAppBar -->
<header class="bg-[#f7f9fc]/80 dark:bg-[#191c1e]/80 backdrop-blur-xl fixed top-0 w-full z-50 transition-all duration-300 ease-in-out">
<div class="flex justify-between items-center px-6 h-16 w-full max-w-7xl mx-auto">
<div class="flex items-center gap-4">
<button class="p-2 text-[#191c1e] dark:text-[#f2f4f7] hover:bg-[#f2f4f7]/50 dark:hover:bg-[#e6e8eb]/10 rounded-full transition-all">
<span class="material-symbols-outlined" data-icon="search">search</span>
</button>
<h1 class="text-2xl font-extrabold text-[#183ce6] dark:text-[#3d5afe] font-['Plus_Jakarta_Sans'] tracking-tight">Портал</h1>
</div>
<nav class="hidden md:flex gap-8">
<a class="font-['Plus_Jakarta_Sans'] font-bold tracking-tight text-[#183ce6] dark:text-[#3d5afe] transition-all" href="#">Спорт</a>
<a class="font-['Plus_Jakarta_Sans'] font-bold tracking-tight text-[#191c1e] dark:text-[#f2f4f7] opacity-70 hover:opacity-100 transition-all" href="#">Игры</a>
<a class="font-['Plus_Jakarta_Sans'] font-bold tracking-tight text-[#191c1e] dark:text-[#f2f4f7] opacity-70 hover:opacity-100 transition-all" href="#">Техно</a>
<a class="font-['Plus_Jakarta_Sans'] font-bold tracking-tight text-[#191c1e] dark:text-[#f2f4f7] opacity-70 hover:opacity-100 transition-all" href="#">Музыка</a>
<a class="font-['Plus_Jakarta_Sans'] font-bold tracking-tight text-[#191c1e] dark:text-[#f2f4f7] opacity-70 hover:opacity-100 transition-all" href="#">Кино</a>
</nav>
<div class="flex items-center gap-2">
<div class="w-10 h-10 rounded-full bg-primary-container overflow-hidden ring-2 ring-surface">
<img alt="User" data-alt="close-up portrait of a young man with a friendly smile, natural lighting, soft urban background bokeh" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAKum0n9ounuJKQqHwd5LHIagTBqviqU-kZwmcznPFGIWINxEQIggylweQPvlDSVIJkySA-YA-S0C-kHpv2XBCimDvPgLr3vvLi_UZnhjr4IrwTXmoXpl33TBXfs5F4CnHkLDyTJaNQPl_u2BCB-QeAeQq7EgHt0O-yJEnn_rizDrHySeO3mfDxYYW-3GzZYEFzfn1H2WrN6QzYfqq_38xV0tLk9J_8JKVuWFMGtYwBbZtSCpqTroTjOeP95jUQvqx5qUhd8hHs7g28"/>
</div>
</div>
</div>
</header>
<main class="pt-24 pb-32 max-w-7xl mx-auto px-6">
<!-- Hero Section -->
<section class="mb-12">
<h2 class="text-[3.5rem] font-headline font-extrabold leading-[1.1] mb-8 tracking-tighter text-primary">Главная</h2>
<!-- Bento Grid Trends -->
<div class="grid grid-cols-1 md:grid-cols-4 grid-rows-2 gap-6 h-auto md:h-[600px]">
<!-- Main Featured Card -->
<div class="md:col-span-2 md:row-span-2 relative group overflow-hidden rounded-xl bg-surface-container-lowest transition-transform hover:scale-[1.01]">
<img class="absolute inset-0 w-full h-full object-cover" data-alt="serene person practicing yoga on a sunlit balcony overlooking a misty morning forest, peaceful atmosphere, soft sunlight" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAbp-c8PI8NSe6CDcrGQir8NIewujDFVtSIU2RW4i_cv9fwt94eO7NShRneOxOKxzTLfyb6tSw6GKOqG5jpTRudE95d4wsh1gpZ44B3Phipl6CXTkX1BQi2zqXUwtSqHrZxIn4McAegiqKE6PW9uPx6I6E_4hhG9nGTr-dx9BGxFu8OZE6m8WZh9V4d4k4cEAo-xbsb4wNg4Fp1pzjAUvqPQVYjO-_kllCRn4QbfwZ7kcXy5bmVHU9W_Dl19got2Tevwdnht-JPKlzH"/>
<div class="absolute inset-0 bg-gradient-to-t from-primary/80 via-transparent to-transparent"></div>
<div class="absolute bottom-0 p-8">
<span class="inline-block px-4 py-1 mb-4 rounded-full bg-secondary-container text-on-secondary-container font-label text-xs font-bold tracking-widest uppercase">Тренды</span>
<h3 class="text-3xl font-headline font-bold text-white mb-2 leading-tight">Искусство замедления: как найти свой дзен в мегаполисе</h3>
<p class="text-white/80 font-body text-sm max-w-md">Путеводитель по самым тихим местам и техникам осознанности для тех, кто устал от суеты.</p>
</div>
</div>
<!-- Secondary Trend 1 -->
<div class="md:col-span-2 md:row-span-1 relative group overflow-hidden rounded-xl bg-surface-container-lowest">
<img class="absolute inset-0 w-full h-full object-cover" data-alt="vibrant abstract close-up of a vinyl record spinning with colorful light reflections, retro-modern aesthetic, energetic mood" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCQ3JX_L9ESrCLFD5k0BrYiNrC7kPSZxmZ3_XdDvHSXf4kWFXDuHhOVg1gRHrIUcM2ckf-PIsHTnu34tEviTc4iFBeKl8KcDCKI9UKzVOG4YiHBSY8OcyUfW-TBe-aYUPFy0fgRIyskEvfKtAWSs-5NE2BJInDbkA_6oj2URE1II02ZhGxpqlhZmtarQY-F-NgrbMkJ2jwNZ8__Oz-yrUoWR1HeRHz5aCvEslw_u707AYLvitOpzOy1m1-08tfqUkX012pkrttZY6nX"/>
<div class="absolute inset-0 bg-gradient-to-r from-[#006153]/90 via-[#006153]/40 to-transparent"></div>
<div class="absolute inset-0 p-6 flex flex-col justify-end">
<h3 class="text-xl font-headline font-bold text-white">Виниловый ренессанс</h3>
</div>
</div>
<!-- Secondary Trend 2 -->
<div class="md:col-span-1 md:row-span-1 relative group overflow-hidden rounded-xl bg-surface-container-lowest">
<img class="absolute inset-0 w-full h-full object-cover" data-alt="high-tech gaming setup with glowing neon teal and indigo lights, sleek hardware, futuristic atmospheric lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDSX8f4i0M_VJrmJx6VHfVT7t5QpgNXh-qogJJYV0IqIqAP2RYcisOSFE4j0UH1SQDAw2MxxXr5V7jCCfufYBAM98li6y6mO4nzQzTYF0v7m0qBa4WT_FhzcJU0FApCaMqltPEB895HM2x3OsAiyZ9rJPxR-gMMbPOlTDpuT2yvZAz6MAHICGVObwM1jFM3xV6nhA50H9cNZ03woq6FbSKYqze_f7JJ0jFxk4mal4M2v7xGvq2-uVAUt7ntTwSOzkjgDyYb5TNvvlIY"/>
<div class="absolute inset-0 bg-gradient-to-t from-[#183ce6]/80 to-transparent"></div>
<div class="absolute bottom-0 p-6">
<h3 class="text-lg font-headline font-bold text-white">Киберспорт 2024</h3>
</div>
</div>
<!-- Secondary Trend 3 -->
<div class="md:col-span-1 md:row-span-1 relative group overflow-hidden rounded-xl bg-surface-container-lowest">
<img class="absolute inset-0 w-full h-full object-cover" data-alt="gourmet healthy breakfast spread on a white wooden table, bright morning light, fresh ingredients, minimalist aesthetic" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCHApM8hcJSMppt1AQWSZG4w7aC8G1gAASu4HssgDTiHHPb5S9WeD-DQxJQhQ7POrBSUaI3TSWKLBrVy6yVmUos-uJnA2EYEiJ3HNICFzd-G3pn_vDTyyZL5cfAm5flluZeWRqJqIaP4FQEAOXl5EBXXDk9LzxEboMRoZOcfxDqYIgZIdx0BfqfaTDtCAEUSUuvT5B0ThXWYuGZWBUqYwU4qIdKsZ8mx-T5RD0uWbKsEeskPnvafa72jvzxcT8T5gjc0LLv3cPyHcJu"/>
<div class="absolute inset-0 bg-gradient-to-t from-[#006879]/80 to-transparent"></div>
<div class="absolute bottom-0 p-6">
<h3 class="text-lg font-headline font-bold text-white">Завтраки будущего</h3>
</div>
</div>
</div>
</section>
<!-- New in Tech Section -->
<section class="mb-16">
<div class="flex justify-between items-end mb-8">
<div>
<h2 class="text-2xl font-headline font-bold text-on-surface">Новое в техно</h2>
<div class="h-1 w-12 bg-secondary mt-2 rounded-full"></div>
</div>
<button class="text-primary font-label text-sm font-bold flex items-center gap-1 hover:gap-2 transition-all">
                    Смотреть всё <span class="material-symbols-outlined text-sm">arrow_forward</span>
</button>
</div>
<div class="grid grid-cols-1 md:grid-cols-3 gap-8">
<article class="bg-surface-container-lowest rounded-xl p-4 transition-all hover:bg-surface-container-low group">
<div class="relative h-48 mb-4 overflow-hidden rounded-lg">
<img class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110" data-alt="close-up of a sleek minimalist smartphone with high-end camera lenses, reflections of soft studio lights, professional product photography" src="https://lh3.googleusercontent.com/aida-public/AB6AXuACzaLvWILkI-vopShSttB04Th1wNrQeKaGe0EtAibrsMEFkjKzhn_XwyVC0g6v4l-D7E9g0wqIYxK5Y1sQtO6O0-pErxGUxPjqCkkqidaOFauVacNqp1dqlNWep3w5zTpCxA3XmYM1YB_Z2xSQ2fg0wNKieKsD7y-wOE5oaCFaxTbYryNuPmSpDBdbHvTT0iuvOWm3QQkWz7QyY32XxJ6j2wbJ1uGA63jzlIh1VjIPyke5yWiiG4_fu9XVNxUU9frfj2szRLw5FBGu"/>
</div>
<div class="flex items-center gap-2 mb-2 text-on-surface-variant font-label text-xs font-semibold uppercase tracking-wider">
<span class="material-symbols-outlined text-sm">memory</span>
<span>Гаджеты</span>
</div>
<h4 class="text-xl font-headline font-bold mb-2">Почему ваш следующий смартфон будет прозрачным?</h4>
<p class="text-on-surface-variant font-body text-sm line-clamp-2">Разбираемся в новых технологиях дисплеев и материалах будущего.</p>
</article>
<article class="bg-surface-container-lowest rounded-xl p-4 transition-all hover:bg-surface-container-low group">
<div class="relative h-48 mb-4 overflow-hidden rounded-lg">
<img class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110" data-alt="abstract visualization of artificial intelligence neural networks, glowing cyan nodes and data streams, dark futuristic background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCgKQL9TutZDNByOTkzwag9zDtDqVrS0wIbJ1rAl0mxpfeeAGaxPBEGvvQM2CFvrGrevO2dKRgwmbbv0QPHYZJ3t9N6UjaMwudTpnqut-XcN1gCYYblijmP7DHa7HuZ28dWcR0n1rFKOx8p1cC7B2f6TFVR-oXNxiu9E4tLIsFestfFn3Bj4Xh9nk-yPGzWop9XLEMDQIWH3KyfDFo_MUS2nIpM_8t0jKVs6R6_OVY558-teQfoWtDTYF5j8dY9THvky991XDB-EvxM"/>
</div>
<div class="flex items-center gap-2 mb-2 text-on-surface-variant font-label text-xs font-semibold uppercase tracking-wider">
<span class="material-symbols-outlined text-sm">smart_toy</span>
<span>AI тренды</span>
</div>
<h4 class="text-xl font-headline font-bold mb-2">Нейросети на чиле: отдых с помощью ИИ</h4>
<p class="text-on-surface-variant font-body text-sm line-clamp-2">Как делегировать рутину алгоритмам и освободить время для жизни.</p>
</article>
<article class="bg-surface-container-lowest rounded-xl p-4 transition-all hover:bg-surface-container-low group">
<div class="relative h-48 mb-4 overflow-hidden rounded-lg">
<img class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110" data-alt="person using a digital tablet at a wooden cafe table, soft natural light, cozy atmosphere, productive yet relaxed mood" src="https://lh3.googleusercontent.com/aida-public/AB6AXuB42wxmv21nGnzxDGKukOyjhWBZs_CWz-H0oQEqha9BplnYiNpqxtkWZPAt0Z45DYu-4sqFU7mSl8c7_aHD4xJhc8GC2l02rf2MByAgaba3s0wpSAxeBcCBn6G6up1pkeB648fJV48HRMLmasmlXQ4bn_38rsZ3-eGzdKSGofaT9RhevfZIQ4l69eWdIJe9Z1xbAhffFcBB0gA0WLGc6mbLcFp4meTyUgKImTPAZDQalr_6NFsGoPl6MkDudJxIgtEgzRYFOxjjqLZO"/>
</div>
<div class="flex items-center gap-2 mb-2 text-on-surface-variant font-label text-xs font-semibold uppercase tracking-wider">
<span class="material-symbols-outlined text-sm">work_history</span>
<span>Продуктивность</span>
</div>
<h4 class="text-xl font-headline font-bold mb-2">Цифровой детокс без вреда для карьеры</h4>
<p class="text-on-surface-variant font-body text-sm line-clamp-2">Практические советы по ограничению экранного времени.</p>
</article>
</div>
</section>
<!-- What to Listen Section -->
<section class="mb-16">
<div class="bg-primary rounded-xl p-8 md:p-12 relative overflow-hidden">
<div class="absolute top-0 right-0 w-1/3 h-full bg-gradient-to-l from-primary-container/30 to-transparent pointer-events-none"></div>
<div class="relative z-10">
<h2 class="text-3xl font-headline font-bold text-white mb-2">Что послушать</h2>
<p class="text-white/70 mb-8 max-w-lg">Наши редакторы собрали плейлисты под любое настроение — от утреннего кофе до ночной поездки.</p>
<div class="flex gap-6 overflow-x-auto hide-scrollbar pb-4 -mx-4 px-4">
<!-- Music Card 1 -->
<div class="flex-none w-64 bg-white/10 backdrop-blur-md rounded-xl p-4 border border-white/5 group cursor-pointer hover:bg-white/20 transition-all">
<div class="aspect-square rounded-lg mb-4 overflow-hidden shadow-xl">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform" data-alt="close-up of a professional electric guitar against a dark moody stage background, purple and blue ambient lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCtQmT0DkvErf2yjC8L0z3Wx3GwfYvqx3DVrF4S64QB6cHxq0GsqsWOHUP1HWfXqqeUsrL3AF4g2z9ORURMtEgBzNHRN9jI6MI7YJk5Rw6uuAkn9Ni3hCz-X-JTDBgdBnGsjie6dEmDnBzIMSlBi6SfboRt_OqvE61ufA84yFGdHsff7jSFVyp4BP9SBgnpwvg5oCS97Syn_8XoCtlNWAU6HCDA9FIrQ8E9pA21nxbLzPL9WGpGGf6IILXPZnqi5TNCSggcUchgj1A1"/>
</div>
<h5 class="text-white font-bold mb-1">Инди-утро</h5>
<p class="text-white/60 text-xs font-label">24 ТРЕКА • 1 Ч 20 МИН</p>
</div>
<!-- Music Card 2 -->
<div class="flex-none w-64 bg-white/10 backdrop-blur-md rounded-xl p-4 border border-white/5 group cursor-pointer hover:bg-white/20 transition-all">
<div class="aspect-square rounded-lg mb-4 overflow-hidden shadow-xl">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform" data-alt="colorful concert lighting beams through a thin haze at a live music event, energetic atmosphere, blurred stage background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCFOvoXwiOEskY-5PcPptyebsNoAa2w86nuMWJvOW0Mt3wr-GuCWEweUM6bW9Gqgmd0l23giRRk_34fQZbMrZhyAFs1aMkVmBBTGOUHi1Ozvj2ZcusozqXAPw2BaDgDK-pHb2mPFcUvF1NL6SSwAw4_VnEwnGdT6oUKj3U87FBGLswJJjb0-COdr42aH0KK1MQv4A7wW4m9SycWQux4DX4XZv40CwGi21ZV3Tlr7vkTUJH7oj_FAH1qqi1kZNcvZAZI0JPNBoqZ069D"/>
</div>
<h5 class="text-white font-bold mb-1">Лоу-фай вайб</h5>
<p class="text-white/60 text-xs font-label">40 ТРЕКОВ • 2 Ч 15 МИН</p>
</div>
<!-- Music Card 3 -->
<div class="flex-none w-64 bg-white/10 backdrop-blur-md rounded-xl p-4 border border-white/5 group cursor-pointer hover:bg-white/20 transition-all">
<div class="aspect-square rounded-lg mb-4 overflow-hidden shadow-xl">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform" data-alt="professional DJ controller decks with glowing buttons in a dark club setting, vibrant red and blue accent lights" src="https://lh3.googleusercontent.com/aida-public/AB6AXuC29aVgmcgFLtTUZ2m2hVEDhTQ3JLyz5AG2By0Vahpy_FHxwA3a37XJ_fepMG7JEp7sPzafimcD8bfSYEECENIWBIV85B9zi7lYIljJfkFYKy2RRdwe9Z5ltGreZAvsZZz1kwdWdR-NtIlUQLMx8B6bhC9kkGzkiwIiVH6acFpfZykRJ_we30uFL1kT6KxzH6cOoXV6I4sUpR_RiZz8byzZn5L6-V6LCstjYXd_lEScRU00IVtHS9z2Bo0-j_b6SPEJuQaK_izFOWAr"/>
</div>
<h5 class="text-white font-bold mb-1">Ночной драйв</h5>
<p class="text-white/60 text-xs font-label">18 ТРЕКОВ • 55 МИН</p>
</div>
</div>
</div>
</div>
</section>
</main>
<!-- BottomNavBar -->
<nav class="fixed bottom-0 left-0 w-full z-50 flex justify-around items-end px-4 pb-6 pt-2 bg-[#f7f9fc]/80 dark:bg-[#191c1e]/80 backdrop-blur-xl shadow-[0_-12px_32px_rgba(25,28,30,0.06)] rounded-t-[3rem] md:hidden">
<div class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity">
<span class="material-symbols-outlined" data-icon="sports_soccer">sports_soccer</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Спорт</span>
</div>
<div class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity">
<span class="material-symbols-outlined" data-icon="sports_esports">sports_esports</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Игры</span>
</div>
<div class="flex flex-col items-center justify-center bg-[#183ce6] text-white rounded-full p-3 scale-110 -translate-y-2 transition-transform">
<span class="material-symbols-outlined" data-icon="devices">devices</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Техно</span>
</div>
<div class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity">
<span class="material-symbols-outlined" data-icon="music_note">music_note</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Музыка</span>
</div>
<div class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity">
<span class="material-symbols-outlined" data-icon="movie">movie</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Кино</span>
</div>
</nav>
<!-- FAB (Suppressed based on logic for feed, but optional for 'Create/Post') -->
<div class="fixed bottom-24 right-8 md:bottom-8 md:right-8 group">
<button class="bg-primary text-white w-14 h-14 rounded-full flex items-center justify-center shadow-xl transition-all duration-300 hover:scale-110 active:scale-95">
<span class="material-symbols-outlined" data-icon="add">add</span>
</button>
</div>
</body></html>

<!-- Главная лента -->
<!DOCTYPE html>

<html class="light" lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;700;800&amp;family=Manrope:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "error-container": "#ffdad6",
                    "inverse-on-surface": "#eff1f4",
                    "secondary": "#006879",
                    "tertiary": "#006153",
                    "on-secondary-fixed-variant": "#004e5b",
                    "primary": "#183ce6",
                    "on-surface": "#191c1e",
                    "on-error": "#ffffff",
                    "on-primary-fixed": "#000f5d",
                    "on-surface-variant": "#444656",
                    "surface-container": "#eceef1",
                    "on-tertiary": "#ffffff",
                    "inverse-primary": "#bbc3ff",
                    "on-error-container": "#93000a",
                    "surface-container-lowest": "#ffffff",
                    "primary-container": "#3d5afe",
                    "background": "#f7f9fc",
                    "secondary-container": "#54e0fd",
                    "inverse-surface": "#2d3133",
                    "surface": "#f7f9fc",
                    "outline": "#757688",
                    "surface-variant": "#e0e3e6",
                    "on-primary-container": "#f1f0ff",
                    "on-secondary-container": "#006170",
                    "on-tertiary-fixed-variant": "#005045",
                    "tertiary-fixed": "#9bf3df",
                    "on-secondary": "#ffffff",
                    "tertiary-container": "#187b6b",
                    "error": "#ba1a1a",
                    "secondary-fixed": "#a8edff",
                    "on-primary-fixed-variant": "#002ccd",
                    "surface-bright": "#f7f9fc",
                    "surface-container-highest": "#e0e3e6",
                    "on-primary": "#ffffff",
                    "primary-fixed-dim": "#bbc3ff",
                    "surface-tint": "#2848ee",
                    "outline-variant": "#c5c5d9",
                    "surface-dim": "#d8dadd",
                    "on-tertiary-container": "#b8ffee",
                    "surface-container-high": "#e6e8eb",
                    "primary-fixed": "#dee0ff",
                    "on-background": "#191c1e",
                    "on-secondary-fixed": "#001f26",
                    "surface-container-low": "#f2f4f7",
                    "secondary-fixed-dim": "#49d7f4",
                    "tertiary-fixed-dim": "#7fd6c3",
                    "on-tertiary-fixed": "#00201b"
            },
            "borderRadius": {
                    "DEFAULT": "1rem",
                    "lg": "2rem",
                    "xl": "3rem",
                    "full": "9999px"
            },
            "fontFamily": {
                    "headline": ["Plus Jakarta Sans"],
                    "body": ["Manrope"],
                    "label": ["Manrope"]
            }
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .glass-card {
            background: rgba(255, 255, 255, 0.8);
            backdrop-filter: blur(24px);
        }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="bg-surface font-body text-on-surface">
<!-- TopAppBar -->
<nav class="fixed top-0 w-full z-50 bg-[#f7f9fc]/80 dark:bg-[#191c1e]/80 backdrop-blur-xl transition-all duration-300 ease-in-out">
<div class="flex justify-between items-center px-6 h-16 w-full max-w-7xl mx-auto">
<div class="flex items-center gap-4">
<button class="p-2 hover:bg-[#f2f4f7]/50 dark:hover:bg-[#e6e8eb]/10 rounded-full transition-all">
<span class="material-symbols-outlined text-[#183ce6] dark:text-[#3d5afe]">search</span>
</button>
</div>
<div class="font-['Plus_Jakarta_Sans'] font-bold tracking-tight text-2xl font-extrabold text-[#183ce6] dark:text-[#3d5afe]">
                Портал
            </div>
<div class="flex items-center">
<div class="w-10 h-10 rounded-full bg-primary-container flex items-center justify-center text-white font-bold overflow-hidden">
<img alt="User Avatar" class="w-full h-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBEMqudGP03UfqlFwy-WxWAbG4rTIF-gbzG3tAR5L3xcveCjhSpmk0lzqz29LSV7TYdJf647kKAzo5Oxb6r4xYhnV07wMifY9xFMqu5STp-4UwyUZMZfUPO9s4d7ZTUdAgglvNM0n6diGvdele507BJiuVfAXQHzY65Pyun6LTioo4in4SKsDzcloYh-nCiD0cW2f-oT5RhOXRrfl26jhhvOuIGdLAl-6K7SEA0_DizBUYboFcF_gOpsN8SgPVHLiK3GTqrT6LpnuKk"/>
</div>
</div>
</div>
</nav>
<main class="pt-24 pb-32 px-6 max-w-7xl mx-auto">
<!-- Hero Section -->
<header class="mb-12">
<h1 class="font-headline text-[3.5rem] font-extrabold tracking-tighter text-on-surface leading-none mb-4">
                Техно &amp; Игры
            </h1>
<p class="text-on-surface-variant text-lg max-w-2xl leading-relaxed">
                Свежие обзоры девайсов, которые делают жизнь проще, и игры, в которых хочется раствориться. Отдыхаем с умом.
            </p>
</header>
<!-- Bento Grid Layout -->
<div class="grid grid-cols-1 md:grid-cols-12 gap-6">
<!-- Featured Review: Asymmetric Span -->
<article class="md:col-span-8 group cursor-pointer">
<div class="relative overflow-hidden rounded-xl bg-surface-container-lowest transition-transform duration-300 hover:scale-[1.01]">
<div class="aspect-[16/9] w-full relative">
<img alt="Tech Review" class="w-full h-full object-cover" data-alt="Modern sleek workstation with minimalist mechanical keyboard and curved ultra-wide monitor in soft blue ambient lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBR2sSVYOru69ek0vd8JuOrqLX3qQ2eIFxGsCYGTRs8_dVMxpWtVXjHJKpkJwaDFwrsLk44nmsUlVnSzpCrIEqfC0bTWUWXznMsz7jpQ-XlUTsZuo4GiPo5JJHrp5puASludl8A1641fD-FxqRrjkMgX5UkK5m3OeZ0pudsBQObYHpp00Dk7TwnLKDTIJ6nA6CkDLdWdFknBiPY9K_uNzWu8aoSHWtqCKK3mwwzQjf6PFCs2xj5vAIWRrNZsTDD48_rQxwnrxG3Mydf"/>
<div class="absolute inset-0 bg-gradient-to-t from-black/60 via-transparent to-transparent"></div>
<div class="absolute top-6 left-6">
<span class="bg-secondary-container text-on-secondary-container px-4 py-1.5 rounded-full text-xs font-bold uppercase tracking-widest">
                                Обзор
                            </span>
</div>
</div>
<div class="p-8 glass-card absolute bottom-0 left-0 right-0 m-6 rounded-lg">
<h2 class="font-headline text-2xl font-bold mb-2 text-on-surface">Новый уровень продуктивности: Тестируем флагманский монитор</h2>
<p class="text-on-surface-variant line-clamp-2 mb-4">Почему 49 дюймов — это не роскошь, а идеальный инструмент для тех, кто ценит свой комфорт и время.</p>
<div class="flex items-center gap-4 text-sm font-semibold text-primary">
<span>Читать 8 мин</span>
<span class="material-symbols-outlined text-sm">arrow_forward</span>
</div>
</div>
</div>
</article>
<!-- Tech News Vertical Card -->
<article class="md:col-span-4 bg-surface-container-lowest rounded-xl p-6 flex flex-col justify-between">
<div>
<span class="text-tertiary font-bold text-xs uppercase tracking-widest mb-4 block">Тренды</span>
<h3 class="font-headline text-xl font-bold mb-4 leading-snug">AI больше не игрушка: Как нейросети меняют наше утро</h3>
<p class="text-on-surface-variant text-sm leading-relaxed mb-6">От умных кофеварок до персональных ассистентов, которые знают ваш график лучше вас.</p>
</div>
<div class="relative rounded-lg overflow-hidden h-48">
<img alt="AI Tech" class="w-full h-full object-cover" data-alt="Abstract visualization of neural networks glowing with cyan and deep blue light on a dark background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCVMMr_SX1hy26fRvv0CHF-nYAwiaa9WmAm7shA-6ASJCtbqhWOPzLZdvFqm0U227jL075IE4-UvOTkR4elWogMlLlAvSgWJwNaxxjASn69vObN32v7D2ITpW5Jj7QcJpwcgUUZgsMLrhSY9a3spslWLC-2Ww-Udxobtux2mbdAuYHO4bkAdGaXwPMJGz8pXTzIiucZg4PEEABjs0cORzSpkmB2jaPVpv1cIJDqfJYxeh47-mvRC2dFUBUP3wgCUZPXSfZzKeESIH2x"/>
</div>
</article>
<!-- Games Section: Masonry-style Grid -->
<div class="md:col-span-12 mt-12 mb-6">
<div class="flex justify-between items-end mb-8">
<h2 class="font-headline text-3xl font-bold tracking-tight">Релизы недели</h2>
<button class="flex items-center gap-2 text-primary font-bold hover:gap-3 transition-all">
                        Все игры <span class="material-symbols-outlined">chevron_right</span>
</button>
</div>
</div>
<!-- Game Card 1 -->
<article class="md:col-span-4 group">
<div class="bg-surface-container-low rounded-xl overflow-hidden hover:bg-surface-container-high transition-colors p-4">
<div class="rounded-lg overflow-hidden mb-4 aspect-square">
<img alt="Game Title" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500" data-alt="Cinematic shot of a mythical dragon soaring through a vibrant sunset sky over a fantasy mountain range" src="https://lh3.googleusercontent.com/aida-public/AB6AXuD2VhK7QMWGiDY_Ak5Bo1bo3XTa89cjvRiktB3VDBkxIWnKzrrOSsomKEZ9UYuGO488Bmv0Q5ZSA16ZNPJfOCG-_pS8YeaBYMcnWc1FPoGY8Rm6TnfaIyJa5MIG6XUE4C4_6KvqZL9hdBamggAfFwrDp89rhkDWFqFClIgCuVyL7P61aCyucKgYZriv4J1YX8zf4TFDlmD_nrtOkAUKIDTa9BMNgAFSclgwXtzP57QuQ-IXMfxeS8uZOr76eDx94p8gbGDI1haBa-S5"/>
</div>
<div class="flex justify-between items-start mb-2">
<h4 class="font-headline text-lg font-bold">Dragon's Wake</h4>
<span class="bg-primary/10 text-primary px-2 py-0.5 rounded text-[10px] font-bold">RPG</span>
</div>
<p class="text-on-surface-variant text-sm mb-4">Погружение в открытый мир, где каждое решение меняет климат планеты.</p>
<div class="flex items-center justify-between">
<span class="text-on-surface font-bold">9.2 / 10</span>
<button class="p-2 rounded-full bg-white text-primary shadow-sm">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">play_arrow</span>
</button>
</div>
</div>
</article>
<!-- Game Card 2 -->
<article class="md:col-span-4 group">
<div class="bg-surface-container-low rounded-xl overflow-hidden hover:bg-surface-container-high transition-colors p-4">
<div class="rounded-lg overflow-hidden mb-4 aspect-square">
<img alt="Game Title" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500" data-alt="Cyberpunk city street at night with neon signs reflecting in puddles and a sleek futuristic car" src="https://lh3.googleusercontent.com/aida-public/AB6AXuD7-xw38hiNUvd5SlvW4GhEW-VlfWI72607jTNW8GSWdZaCErFUIcYUUc-7eFqhqMW4EyekL-QlPI6V8baLr0i12TXTYieRp12oGHI_r2oHk0UZYUdf2nR--A1avmsCIhNCnbdO6E1axJYX32j9n3HoYJCnQvYMZqcQFXEFWujMmAa_2ZNz0FwCMYai_RIq7hRR5uOdYwNGQ0k-XRsj745DnWo5f5ZqRmhQkX38nvvpqiDJCHudd7l8f6IVIClbYsKwm2hfwqosCBTx"/>
</div>
<div class="flex justify-between items-start mb-2">
<h4 class="font-headline text-lg font-bold">Neon Pulse</h4>
<span class="bg-secondary/10 text-secondary px-2 py-0.5 rounded text-[10px] font-bold">Action</span>
</div>
<p class="text-on-surface-variant text-sm mb-4">Ритм-экшен в декорациях будущего, где музыка — ваше главное оружие.</p>
<div class="flex items-center justify-between">
<span class="text-on-surface font-bold">8.5 / 10</span>
<button class="p-2 rounded-full bg-white text-primary shadow-sm">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">play_arrow</span>
</button>
</div>
</div>
</article>
<!-- Game Card 3 -->
<article class="md:col-span-4 group">
<div class="bg-surface-container-low rounded-xl overflow-hidden hover:bg-surface-container-high transition-colors p-4">
<div class="rounded-lg overflow-hidden mb-4 aspect-square">
<img alt="Game Title" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500" data-alt="Collection of vintage 8-bit game consoles and colorful cartridges arranged on a wooden desk" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDrIlWThqd2mgkiTHs8fP1n0QfR3Da6hIrht2_m10nKnYrrWi-AVxAe31W9VbPY16LopuUuO323inhWF4LVy41rm-lH6tVuGDDMvIn-FolJHvgRXMX9D-K6t_HfLSpDf_J49HEwR02tV9cPC0fZZRd5Ylc1QHDYokCvaANj2pcL_HRxTkgrpXuIqvlAQUfb8JOTE2wuhpR2LRHj3fwR_bfK7PUEVUTmwOb3VC6TxyupIhxnMGsyQQmACu8D0jzzTWbp-Rsq6-Nsfwvb"/>
</div>
<div class="flex justify-between items-start mb-2">
<h4 class="font-headline text-lg font-bold">Retro Revival</h4>
<span class="bg-tertiary/10 text-tertiary px-2 py-0.5 rounded text-[10px] font-bold">Indie</span>
</div>
<p class="text-on-surface-variant text-sm mb-4">Пиксельная ностальгия, переосмысленная для современных консолей.</p>
<div class="flex items-center justify-between">
<span class="text-on-surface font-bold">8.8 / 10</span>
<button class="p-2 rounded-full bg-white text-primary shadow-sm">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">play_arrow</span>
</button>
</div>
</div>
</article>
</div>
</main>
<!-- FAB: Contextual to Tech/Games -->
<button class="fixed bottom-28 right-8 w-14 h-14 rounded-full bg-primary-container text-white shadow-xl flex items-center justify-center hover:scale-110 transition-transform z-40">
<span class="material-symbols-outlined">add</span>
</button>
<!-- BottomNavBar -->
<nav class="fixed bottom-0 left-0 w-full z-50 flex justify-around items-end px-4 pb-6 pt-2 bg-[#f7f9fc]/80 dark:bg-[#191c1e]/80 backdrop-blur-xl rounded-t-[3rem] shadow-[0_-12px_32px_rgba(25,28,30,0.06)]">
<div class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity cursor-pointer">
<span class="material-symbols-outlined mb-1">sports_soccer</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider">Спорт</span>
</div>
<div class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity cursor-pointer">
<span class="material-symbols-outlined mb-1">sports_esports</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider">Игры</span>
</div>
<!-- Active Tab: Techno (Using logic to map "Tech" to "Техно") -->
<div class="flex flex-col items-center justify-center bg-[#183ce6] text-white rounded-full p-3 scale-110 -translate-y-2 transition-transform cursor-pointer">
<span class="material-symbols-outlined mb-1">devices</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider">Техно</span>
</div>
<div class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity cursor-pointer">
<span class="material-symbols-outlined mb-1">music_note</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider">Музыка</span>
</div>
<div class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity cursor-pointer">
<span class="material-symbols-outlined mb-1">movie</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider">Кино</span>
</div>
</nav>
</body></html>

<!-- Техно и Игры -->
<!DOCTYPE html>

<html class="light" lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Спорт и Движение — Жизнь на чиле</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;700;800&amp;family=Manrope:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "error-container": "#ffdad6",
                        "inverse-on-surface": "#eff1f4",
                        "secondary": "#006879",
                        "tertiary": "#006153",
                        "on-secondary-fixed-variant": "#004e5b",
                        "primary": "#183ce6",
                        "on-surface": "#191c1e",
                        "on-error": "#ffffff",
                        "on-primary-fixed": "#000f5d",
                        "on-surface-variant": "#444656",
                        "surface-container": "#eceef1",
                        "on-tertiary": "#ffffff",
                        "inverse-primary": "#bbc3ff",
                        "on-error-container": "#93000a",
                        "surface-container-lowest": "#ffffff",
                        "primary-container": "#3d5afe",
                        "background": "#f7f9fc",
                        "secondary-container": "#54e0fd",
                        "inverse-surface": "#2d3133",
                        "surface": "#f7f9fc",
                        "outline": "#757688",
                        "surface-variant": "#e0e3e6",
                        "on-primary-container": "#f1f0ff",
                        "on-secondary-container": "#006170",
                        "on-tertiary-fixed-variant": "#005045",
                        "tertiary-fixed": "#9bf3df",
                        "on-secondary": "#ffffff",
                        "tertiary-container": "#187b6b",
                        "error": "#ba1a1a",
                        "secondary-fixed": "#a8edff",
                        "on-primary-fixed-variant": "#002ccd",
                        "surface-bright": "#f7f9fc",
                        "surface-container-highest": "#e0e3e6",
                        "on-primary": "#ffffff",
                        "primary-fixed-dim": "#bbc3ff",
                        "surface-tint": "#2848ee",
                        "outline-variant": "#c5c5d9",
                        "surface-dim": "#d8dadd",
                        "on-tertiary-container": "#b8ffee",
                        "surface-container-high": "#e6e8eb",
                        "primary-fixed": "#dee0ff",
                        "on-background": "#191c1e",
                        "on-secondary-fixed": "#001f26",
                        "surface-container-low": "#f2f4f7",
                        "secondary-fixed-dim": "#49d7f4",
                        "tertiary-fixed-dim": "#7fd6c3",
                        "on-tertiary-fixed": "#00201b"
                    },
                    "borderRadius": {
                        "DEFAULT": "1rem",
                        "lg": "2rem",
                        "xl": "3rem",
                        "full": "9999px"
                    },
                    "fontFamily": {
                        "headline": ["Plus Jakarta Sans"],
                        "body": ["Manrope"],
                        "label": ["Manrope"]
                    }
                }
            }
        }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        body { font-family: 'Manrope', sans-serif; background-color: #f7f9fc; color: #191c1e; overflow-x: hidden; }
        h1, h2, h3 { font-family: 'Plus Jakarta Sans', sans-serif; }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="bg-surface text-on-surface selection:bg-primary-container selection:text-on-primary-container">
<!-- TopAppBar -->
<header class="fixed top-0 w-full z-50 bg-[#f7f9fc]/80 dark:bg-[#191c1e]/80 backdrop-blur-xl">
<div class="flex justify-between items-center px-6 h-16 w-full max-w-7xl mx-auto">
<div class="flex items-center gap-4">
<button class="p-2 transition-all duration-300 ease-in-out hover:bg-[#f2f4f7]/50 dark:hover:bg-[#e6e8eb]/10 rounded-full">
<span class="material-symbols-outlined text-[#183ce6] dark:text-[#3d5afe]">search</span>
</button>
</div>
<div class="text-2xl font-extrabold text-[#183ce6] dark:text-[#3d5afe] font-['Plus_Jakarta_Sans'] tracking-tight">Портал</div>
<div class="flex items-center">
<div class="w-10 h-10 rounded-full bg-surface-container-highest flex items-center justify-center overflow-hidden border-2 border-primary/10">
<img class="w-full h-full object-cover" data-alt="Close up portrait of a smiling friendly person with natural lighting and soft blurred background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBSLRtq1LSWUF0jp2xFH4VoKUA5JYhqwScEttBgaS6LgdHcV2h8nGVvA01dIgGhGzIDGyQzUlo-cRS_3cWm7Z8ygGRx70zAA50GzixFjzcchYGZ3OFGDVjsEMkLysVX-BOzBuMXQ3Jd5e6rHVmwDoSKWtIXILvYgx6Ul11wAflz5fqkvIoc_hQI88w8qOcP0WdaAxvM9rEFqAhbFZxp4rRcW5EImQUxk1zmSmEHjTZcVVznj12ehoImHy3jWP3WZog-znhOyPSSp4g9"/>
</div>
</div>
</div>
</header>
<main class="pt-24 pb-32 px-4 max-w-7xl mx-auto">
<!-- Hero Section -->
<section class="relative mb-16 group">
<div class="bg-gradient-to-br from-primary to-primary-container rounded-xl overflow-hidden min-h-[500px] flex items-center relative p-8 md:p-16">
<div class="z-10 max-w-2xl">
<span class="inline-block px-4 py-1.5 bg-secondary-container text-on-secondary-container rounded-full text-xs font-bold uppercase tracking-widest mb-6">Lifestyle Focus</span>
<h1 class="text-white text-5xl md:text-7xl font-extrabold tracking-tight mb-6 leading-[1.1]">Спорт и Движение</h1>
<p class="text-on-primary-container text-lg md:text-xl leading-relaxed mb-10 opacity-90">
                        Забудьте про изнурительные тренировки. Мы здесь ради эндорфинов, прогулок в парке и радости от того, что тело просто живет. Жизнь на чиле — это когда спорт в удовольствие.
                    </p>
<div class="flex flex-wrap gap-4">
<button class="bg-white text-primary px-8 py-4 rounded-full font-bold transition-transform hover:scale-105">Начать легко</button>
<button class="bg-primary-container/20 text-white border border-white/20 backdrop-blur-md px-8 py-4 rounded-full font-bold hover:bg-white/10 transition-all">Узнать больше</button>
</div>
</div>
<div class="absolute right-0 bottom-0 top-0 w-1/2 hidden lg:block overflow-hidden rounded-l-xl">
<img class="w-full h-full object-cover opacity-80 mix-blend-lighten" data-alt="Athletic person in modern sportswear stretching in a sun-drenched studio with soft shadows and minimal aesthetic" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDswbVFZaFsyG-Z7y81w1gElsE6jjAsdgQKoYUdOUbSfGqe5uHo-e2IeQ6WlMpkgcz4f9rwfvFTm3hNQn_zyrvEyFYZHgW44hJLnmAehgg7P3RatxynsNUi1xv5xjRGuhY_iO6c5B47IzZQkDDVw75SzxPuzzJXfrG9EDAYmGAwIke7R8h4VOehD9v52vVpu2ZmO-cfvYwHSoC1rxZNPmIkYaXjX2yPo9LhCzjSQsjTEG5kCxDaqz3m3KOAZC70TZRNs7zRNXst5aCL"/>
</div>
</div>
</section>
<!-- Bento Grid Layout -->
<div class="grid grid-cols-1 md:grid-cols-12 gap-6 mb-16">
<!-- Card 1: Jogging -->
<div class="md:col-span-8 bg-surface-container-lowest rounded-xl p-8 flex flex-col md:flex-row gap-8 items-center group cursor-pointer hover:shadow-xl transition-all duration-300">
<div class="w-full md:w-1/2 aspect-video rounded-lg overflow-hidden">
<img class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-700" data-alt="Young person jogging through a scenic misty park at sunrise with soft golden rays filtering through trees" src="https://lh3.googleusercontent.com/aida-public/AB6AXuB_avTlmwImL1JbYH7Xm8bVCKGiwrWYaRoSYnfYocqIRYbqa6hXVgkHVD3oAwtLgXxrdU_CaAlW9ze12oJn6RnWYFAtVbglSicEgnbWCVnVW7gxc4q408cGEZDP9jxJE81peyaq9Da1FJeRw0RX7MfR2P7WJNAXqXlZrGFQnFMbynq3W8C-lTMBJ0JV7a9Ctk9eF6fcnnmKrUXhKGOTcqHgbSXhBLnYtcES29pfmUVIO1JYS5iznngZ7uhdGLvKgYndaepnNtM68vhn"/>
</div>
<div class="w-full md:w-1/2">
<h3 class="text-2xl font-bold mb-4 text-on-surface">Бег без одышки</h3>
<p class="text-on-surface-variant leading-relaxed mb-6">Как превратить утреннюю пробежку в медитацию, а не в пытку. Секреты темпа, который приносит радость.</p>
<div class="flex items-center gap-2 text-primary font-bold">
<span>Читать статью</span>
<span class="material-symbols-outlined">arrow_forward</span>
</div>
</div>
</div>
<!-- Card 2: Gym Vibes -->
<div class="md:col-span-4 bg-tertiary-container rounded-xl p-8 flex flex-col justify-between text-white relative overflow-hidden group">
<div class="absolute top-0 right-0 p-4 opacity-20">
<span class="material-symbols-outlined text-8xl" style="font-variation-settings: 'FILL' 1;">fitness_center</span>
</div>
<div class="relative z-10">
<h3 class="text-2xl font-bold mb-4">Тренажерка для души</h3>
<p class="opacity-80 mb-8">Почему 20 минут веса лучше часа кардио, если ваша цель — просто чувствовать себя бодро.</p>
</div>
<button class="bg-white/20 backdrop-blur-xl border border-white/30 p-4 rounded-full w-fit group-hover:bg-white group-hover:text-tertiary-container transition-all">
<span class="material-symbols-outlined">add</span>
</button>
</div>
<!-- Card 3: Well-being Chips/Tags -->
<div class="md:col-span-4 bg-surface-container-low rounded-xl p-8">
<h3 class="text-xl font-bold mb-6">Что сегодня?</h3>
<div class="flex flex-wrap gap-3">
<span class="px-6 py-3 bg-secondary-container text-on-secondary-container rounded-full text-sm font-semibold cursor-pointer hover:opacity-80 transition-opacity">Йога</span>
<span class="px-6 py-3 bg-white text-on-surface-variant rounded-full text-sm font-semibold border border-outline-variant/20 shadow-sm cursor-pointer hover:bg-secondary-container transition-all">Бадминтон</span>
<span class="px-6 py-3 bg-white text-on-surface-variant rounded-full text-sm font-semibold border border-outline-variant/20 shadow-sm cursor-pointer hover:bg-secondary-container transition-all">Плавание</span>
<span class="px-6 py-3 bg-white text-on-surface-variant rounded-full text-sm font-semibold border border-outline-variant/20 shadow-sm cursor-pointer hover:bg-secondary-container transition-all">Велосипед</span>
<span class="px-6 py-3 bg-white text-on-surface-variant rounded-full text-sm font-semibold border border-outline-variant/20 shadow-sm cursor-pointer hover:bg-secondary-container transition-all">Растяжка</span>
</div>
</div>
<!-- Card 4: Video Insight (Asymmetric) -->
<div class="md:col-span-8 relative rounded-xl overflow-hidden bg-on-surface">
<img class="w-full h-full object-cover opacity-50" data-alt="High angle view of a yoga mat and water bottle on a clean wooden floor in a bright minimalist studio" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAcqk7oIaZwaSCrGu3HsAnJ7GZnorAATaIlFYzt0XjPBGQ-lK17FNFnamEICh6XpaZ7pkFEA2d9brYgTfsuFYdeJhFJjA2qWwQekxPwqzBCGZcbQ2GJ62sgyQPPqm-uZeR4yf-QSNWonTyDv_fE1RrFAX-q6c4w4RfqBmq6wLiCnKQ7fv7cDZwmvIpdp8Bt9JsxjbfrRgT7L-gC0YrQw0N7K05OrsrBibrlCE1QZtzZSxLswTu6MgiHMaXRaKuesadc5v_g_EVCE6fJ"/>
<div class="absolute inset-0 p-8 flex flex-col justify-end">
<div class="flex items-center gap-4 mb-4">
<div class="w-16 h-16 bg-primary rounded-full flex items-center justify-center text-white shadow-lg cursor-pointer hover:scale-110 transition-transform">
<span class="material-symbols-outlined text-4xl" style="font-variation-settings: 'FILL' 1;">play_arrow</span>
</div>
<div>
<p class="text-white font-bold text-xl">5 минут для спины</p>
<p class="text-white/70 text-sm">Короткий комплекс для тех, кто много сидит</p>
</div>
</div>
</div>
</div>
</div>
<!-- Quote / Editorial Block -->
<section class="my-20 text-center max-w-3xl mx-auto">
<span class="material-symbols-outlined text-secondary text-5xl mb-6">format_quote</span>
<h2 class="text-3xl md:text-4xl font-bold text-on-surface leading-tight mb-8">
                «Движение — это не долг перед зеркалом, а подарок своему настроению».
            </h2>
<div class="h-1 w-20 bg-secondary mx-auto rounded-full"></div>
</section>
<!-- Newsletter / Community Section (Glassmorphism) -->
<section class="relative bg-surface-container-high rounded-xl p-8 md:p-12 overflow-hidden">
<div class="relative z-10 grid md:grid-cols-2 gap-12 items-center">
<div>
<h2 class="text-3xl font-bold mb-4">Присоединяйтесь к движению чилла</h2>
<p class="text-on-surface-variant text-lg">Получайте еженедельные подборки легких активностей и советы по восстановлению сил.</p>
</div>
<div class="flex flex-col sm:flex-row gap-4">
<input class="flex-grow bg-white border-none rounded-full px-6 py-4 focus:ring-2 focus:ring-primary text-on-surface" placeholder="Ваш e-mail" type="email"/>
<button class="bg-primary text-white font-bold px-8 py-4 rounded-full shadow-lg shadow-primary/20 hover:translate-y-[-2px] transition-all">Подписаться</button>
</div>
</div>
<!-- Decorative circle -->
<div class="absolute -top-24 -right-24 w-64 h-64 bg-secondary/10 rounded-full blur-3xl"></div>
</section>
</main>
<!-- BottomNavBar -->
<nav class="fixed bottom-0 left-0 w-full z-50 flex justify-around items-end px-4 pb-6 pt-2 bg-[#f7f9fc]/80 dark:bg-[#191c1e]/80 backdrop-blur-xl shadow-[0_-12px_32px_rgba(25,28,30,0.06)] rounded-t-[3rem]">
<a class="flex flex-col items-center justify-center bg-[#183ce6] text-white rounded-full p-3 scale-110 -translate-y-2 transition-transform" href="#">
<span class="material-symbols-outlined">sports_soccer</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Спорт</span>
</a>
<a class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity" href="#">
<span class="material-symbols-outlined">sports_esports</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Игры</span>
</a>
<a class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity" href="#">
<span class="material-symbols-outlined">devices</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Техно</span>
</a>
<a class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity" href="#">
<span class="material-symbols-outlined">music_note</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Музыка</span>
</a>
<a class="flex flex-col items-center justify-center text-[#191c1e] dark:text-[#f2f4f7] p-2 opacity-70 hover:opacity-100 transition-opacity" href="#">
<span class="material-symbols-outlined">movie</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Кино</span>
</a>
</nav>
</body></html>

<!-- Спорт и Движение -->
<!DOCTYPE html>

<html class="light" lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600;700;800&amp;family=Manrope:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "error-container": "#ffdad6",
                    "inverse-on-surface": "#eff1f4",
                    "secondary": "#006879",
                    "tertiary": "#006153",
                    "on-secondary-fixed-variant": "#004e5b",
                    "primary": "#183ce6",
                    "on-surface": "#191c1e",
                    "on-error": "#ffffff",
                    "on-primary-fixed": "#000f5d",
                    "on-surface-variant": "#444656",
                    "surface-container": "#eceef1",
                    "on-tertiary": "#ffffff",
                    "inverse-primary": "#bbc3ff",
                    "on-error-container": "#93000a",
                    "surface-container-lowest": "#ffffff",
                    "primary-container": "#3d5afe",
                    "background": "#f7f9fc",
                    "secondary-container": "#54e0fd",
                    "inverse-surface": "#2d3133",
                    "surface": "#f7f9fc",
                    "outline": "#757688",
                    "surface-variant": "#e0e3e6",
                    "on-primary-container": "#f1f0ff",
                    "on-secondary-container": "#006170",
                    "on-tertiary-fixed-variant": "#005045",
                    "tertiary-fixed": "#9bf3df",
                    "on-secondary": "#ffffff",
                    "tertiary-container": "#187b6b",
                    "error": "#ba1a1a",
                    "secondary-fixed": "#a8edff",
                    "on-primary-fixed-variant": "#002ccd",
                    "surface-bright": "#f7f9fc",
                    "surface-container-highest": "#e0e3e6",
                    "on-primary": "#ffffff",
                    "primary-fixed-dim": "#bbc3ff",
                    "surface-tint": "#2848ee",
                    "outline-variant": "#c5c5d9",
                    "surface-dim": "#d8dadd",
                    "on-tertiary-container": "#b8ffee",
                    "surface-container-high": "#e6e8eb",
                    "primary-fixed": "#dee0ff",
                    "on-background": "#191c1e",
                    "on-secondary-fixed": "#001f26",
                    "surface-container-low": "#f2f4f7",
                    "secondary-fixed-dim": "#49d7f4",
                    "tertiary-fixed-dim": "#7fd6c3",
                    "on-tertiary-fixed": "#00201b"
            },
            "borderRadius": {
                    "DEFAULT": "1rem",
                    "lg": "2rem",
                    "xl": "3rem",
                    "full": "9999px"
            },
            "fontFamily": {
                    "headline": ["Plus Jakarta Sans"],
                    "body": ["Manrope"],
                    "label": ["Manrope"]
            }
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .bg-mesh {
            background-color: #f7f9fc;
            background-image: radial-gradient(at 0% 0%, rgba(24, 60, 230, 0.05) 0px, transparent 50%),
                              radial-gradient(at 100% 0%, rgba(0, 104, 121, 0.05) 0px, transparent 50%);
        }
    </style>
</head>
<body class="bg-surface font-body text-on-surface bg-mesh min-h-screen">
<!-- TopAppBar -->
<header class="bg-[#f7f9fc]/80 backdrop-blur-xl fixed top-0 w-full z-50 transition-all duration-300 ease-in-out">
<div class="flex justify-between items-center px-6 h-16 w-full max-w-7xl mx-auto">
<div class="flex items-center gap-4">
<button class="p-2 transition-all duration-300 ease-in-out hover:bg-[#f2f4f7]/50 rounded-full text-[#191c1e]">
<span class="material-symbols-outlined" data-icon="search">search</span>
</button>
<h1 class="text-2xl font-extrabold text-[#183ce6] font-['Plus_Jakarta_Sans'] tracking-tight">Портал</h1>
</div>
<nav class="hidden md:flex gap-8 items-center">
<a class="font-['Manrope'] font-semibold text-[#191c1e] hover:text-[#183ce6] transition-colors" href="#">Спорт</a>
<a class="font-['Manrope'] font-semibold text-[#191c1e] hover:text-[#183ce6] transition-colors" href="#">Игры</a>
<a class="font-['Manrope'] font-semibold text-[#191c1e] hover:text-[#183ce6] transition-colors" href="#">Техно</a>
<a class="font-['Manrope'] font-semibold text-[#183ce6] relative after:content-[''] after:absolute after:-bottom-1 after:left-0 after:w-full after:h-0.5 after:bg-[#183ce6] after:rounded-full" href="#">Медиа</a>
</nav>
<div class="flex items-center gap-3">
<div class="w-10 h-10 rounded-full bg-primary-container flex items-center justify-center text-on-primary-container overflow-hidden">
<img class="w-full h-full object-cover" data-alt="close-up portrait of a friendly man with a warm smile, professional studio lighting with soft bokeh background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCvetvQcAaArokpDMI8zLJM-WPhg5DRWszLRSMdSgxEV3ynDxXCBU_Q2RXiPX-OgL44nwXTt_rU-MGZ3NX5Zq6KVGzUZEY3K6Vxoy7NaK7KLJhp9KXmI3FoTXx08WEkRRkVkjuvokhdbsDZ3vz-GMdA8XMBe2BsTCPgI5iH_KX-nGTWH88KXfZJIhBeu-nyWvcPsFLyWFvysSPi9sUSvrzfJxRXQvVfqgv9gBFRuC7MQ840UUq-wpfwTufv5RgBcMV-qV4N4YSFOmDC"/>
</div>
</div>
</div>
</header>
<main class="pt-24 pb-32 px-6 max-w-7xl mx-auto">
<!-- Hero Section -->
<section class="relative mb-16 overflow-hidden rounded-xl h-[450px] flex items-center">
<div class="absolute inset-0 z-0">
<img class="w-full h-full object-cover" data-alt="vibrant concert atmosphere with silhouettes of crowd against colorful stage lights and soft purple haze" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBWZHJSGLgZay3GAhDck7J1v8h9PYpw5UiVO6B8rkg_0yMIESVwUyPlbZ8Wy15RxueeRnONAyRESaUdIuvY-_adsXi-7E9nf0nhj3S2McZvRboS0u2-ohOfUeohLVrIidb00ryw8YQJSvUcpCfjtKejGInoi9pqpLKRd4EavnzGh3ToEjSLzll8XOala8oaVdd_dKzVuRRynDLA6vbOZ3AllUiOT640PEe-Mz30V7_QzteJoWM_Vhlj3FdIdb-6B3aNpXSS-uoFjT3y"/>
<div class="absolute inset-0 bg-gradient-to-r from-on-surface via-on-surface/40 to-transparent"></div>
</div>
<div class="relative z-10 px-8 md:px-16 max-w-2xl">
<span class="inline-block px-4 py-1.5 rounded-full bg-secondary-container text-on-secondary-container text-xs font-bold uppercase tracking-widest mb-6">Lifestyle hub</span>
<h2 class="text-5xl md:text-7xl font-headline font-extrabold text-white leading-tight mb-6">Музыка &amp; Кино</h2>
<p class="text-lg text-surface-variant font-medium mb-8 leading-relaxed">Твое пространство для глубокого погружения. Лучшие плейлисты для чилла и рекомендации, которые попадут в самое сердце.</p>
<div class="flex flex-wrap gap-4">
<button class="bg-gradient-to-br from-primary to-primary-container text-white px-8 py-4 rounded-full font-bold hover:scale-105 transition-transform">Слушать сейчас</button>
<button class="bg-white/10 backdrop-blur-md text-white px-8 py-4 rounded-full font-bold border border-white/20 hover:bg-white/20 transition-all">Смотреть топ</button>
</div>
</div>
</section>
<!-- Bento Grid: Mood & Playlists -->
<div class="grid grid-cols-1 md:grid-cols-4 gap-6 mb-16">
<!-- Featured Playlist (Large) -->
<div class="md:col-span-2 md:row-span-2 bg-surface-container-lowest rounded-xl p-8 group overflow-hidden relative border border-outline-variant/10">
<div class="relative z-10 h-full flex flex-col justify-between">
<div>
<div class="flex justify-between items-start mb-12">
<h3 class="text-3xl font-headline font-bold text-on-surface max-w-[200px]">Плейлист для вечернего вайба</h3>
<span class="material-symbols-outlined text-primary text-4xl" data-icon="graphic_eq">graphic_eq</span>
</div>
<p class="text-on-surface-variant text-lg">Лоу-фай биты и мягкий джаз для тех, кто ценит спокойствие.</p>
</div>
<div class="flex items-center gap-4">
<button class="w-14 h-14 rounded-full bg-primary text-white flex items-center justify-center hover:scale-110 transition-transform shadow-lg">
<span class="material-symbols-outlined" data-icon="play_arrow" style="font-variation-settings: 'FILL' 1;">play_arrow</span>
</button>
<span class="font-bold text-on-surface">24 трека • 1ч 15мин</span>
</div>
</div>
<div class="absolute top-0 right-0 w-1/2 h-full opacity-10 group-hover:opacity-20 transition-opacity">
<img class="w-full h-full object-cover" data-alt="professional dj equipment close-up with neon blue and purple ambient lighting in a dark room" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDwZtWwG2jy-jPB_Vdlm-_ZdsZpmFY1Lnqj_RN17mJy9doybBlVtEOo0C8zMI66YxfTb8TcyhbrHisXYekjBRxSNslzROfqYZqWCW30ZowJklTeA54a2jiGdFCaZyOBW1pGzV5HMhUztGgnzaK_9hAp5HC2QoAslCUy6aFaPqW48nDZZK0Er4YeOPsCCUQw3GNhqByb738aqMJGeOnBhOaEE7NMt2R9SNaX-B7GQwWffZSHhbRhyEwwh_MFh3U801l2VcNt70bKFU74"/>
</div>
</div>
<!-- Recommendation 1 -->
<div class="md:col-span-2 bg-secondary-container/20 rounded-xl p-6 flex gap-6 items-center border border-secondary-container/30">
<div class="w-32 h-32 rounded-lg overflow-hidden flex-shrink-0">
<img class="w-full h-full object-cover" data-alt="cinematic shot of an old movie projector in a dark room with a beam of light hitting a screen" src="https://lh3.googleusercontent.com/aida-public/AB6AXuC09ShILbZ_hG59Pe4SS-zrocoNStVk5NR7nDPWM2_iDWMObPYQt8qdBcBosoQ_zwZO6q_B8GrNimHrHcdAGmuMOqCpS2sqGzoYfBZDBu9PphzeXN5hqDpbZXlGFMvmYDWT98lq6fUacbwx0FzTc_FZXWMnY0e7dOF8LpecCblvFwHEQSBGC9BOcM7ioOnTeIyxbR5PIhloBopYmz-BGCNCXoSXfde5sCSD8zLxUfS_cB8NI7v1I60hZePfAmuYQ-u6GiEjHq-IpLvl"/>
</div>
<div>
<span class="text-secondary font-bold text-xs uppercase tracking-wider">Кино недели</span>
<h4 class="text-xl font-bold mt-1">Эстетика минимализма</h4>
<p class="text-on-surface-variant text-sm mt-2">Разбор визуального стиля современного авторского кино.</p>
</div>
</div>
<!-- Recommendation 2 -->
<div class="md:col-span-1 bg-surface-container-low rounded-xl p-6 flex flex-col justify-between border border-outline-variant/10">
<span class="material-symbols-outlined text-tertiary" data-icon="podcasts">podcasts</span>
<div>
<h4 class="font-bold mt-4">Chill Cast</h4>
<p class="text-on-surface-variant text-xs mt-1">О музыке без лишних слов.</p>
</div>
</div>
<!-- Recommendation 3 -->
<div class="md:col-span-1 bg-primary-container text-on-primary-container rounded-xl p-6 flex flex-col justify-between overflow-hidden relative">
<div class="relative z-10">
<span class="material-symbols-outlined" data-icon="star" style="font-variation-settings: 'FILL' 1;">star</span>
<h4 class="font-bold mt-4">Топ Чарт</h4>
</div>
<span class="relative z-10 text-4xl font-black opacity-30">#1</span>
<div class="absolute -right-4 -bottom-4 opacity-10">
<span class="material-symbols-outlined text-9xl" data-icon="music_note">music_note</span>
</div>
</div>
</div>
<!-- Asymmetric Content Section -->
<section class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-start">
<div class="lg:col-span-7">
<div class="flex items-center justify-between mb-8">
<h3 class="text-3xl font-headline font-bold">Последние обзоры</h3>
<a class="text-primary font-bold flex items-center gap-2 hover:underline" href="#">
                        Все статьи <span class="material-symbols-outlined">arrow_forward</span>
</a>
</div>
<div class="space-y-12">
<!-- Article 1 -->
<article class="flex flex-col md:flex-row gap-8 items-center group">
<div class="w-full md:w-1/2 overflow-hidden rounded-lg">
<img class="w-full aspect-[4/3] object-cover group-hover:scale-105 transition-transform duration-500" data-alt="cool musician playing guitar in a hazy sunlit room with vintage furniture and warm mood" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDuP7Hu-d4OydxyRr_IieJZwkLnBBcE_wqqC4wl5zdEQtM7BsqYry9W-r0x4vqYxCh04Qo4Ohh-e-kGn6OTwMd4GuYcw5GXT3wuAkifQWAox7bwkRlFiFiUHiY5GB0r8EhHGVHLiQLn3uiCgtiasuvlmFN53qrbYNlQxmAFjx23PtCQDDQBXg7BQbci9tYamDzzTw7XxoDjatfIyBN-cweTMU_5PqwRNdDUtB1vpAlMMs8H4HZskort7lm8naQr8AxCJiAPpkbyKwdm"/>
</div>
<div class="w-full md:w-1/2">
<div class="flex items-center gap-4 mb-4">
<span class="text-tertiary font-bold text-xs uppercase">Музыка</span>
<span class="text-on-surface-variant text-xs">5 мин чтения</span>
</div>
<h4 class="text-2xl font-bold mb-4 leading-tight group-hover:text-primary transition-colors">Почему винил снова в моде: возвращение к истокам</h4>
<p class="text-on-surface-variant leading-relaxed mb-6">Исследуем магию аналогового звука и то, как физические носители меняют наше восприятие альбомов в цифровую эпоху.</p>
<div class="flex items-center gap-3">
<div class="w-8 h-8 rounded-full bg-surface-container-highest overflow-hidden">
<img class="w-full h-full object-cover" data-alt="close-up portrait of a man with glasses and a beard, soft natural daylight, minimalist background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCBaqjQEsqzvjQoyN1xAMtRzwIIF47T4KSS1Nq0Q4WJUSWgv1yXceKo7XpfXS700h9Ha8R8Br93sTjoEy0chdz8yJwUHTTUpE9UU3pEiD59b5bQLT5nkwyXIX5HrxDgisLnugzMeXcWBqz6aNcwKf6j-hUUfjSJxOrJmbfg7A__0Eeez7gJgjtwdww3jRvSONYeggiW9gIQHYOyxEiNTuCS3blV_aNBw6gBe4OMl4iZbUYlzy_e334OV-29sU2Dus0THV0iYOomL50D"/>
</div>
<span class="text-sm font-semibold">Алексей Громов</span>
</div>
</div>
</article>
<!-- Article 2 -->
<article class="flex flex-col md:flex-row-reverse gap-8 items-center group">
<div class="w-full md:w-1/2 overflow-hidden rounded-lg">
<img class="w-full aspect-[4/3] object-cover group-hover:scale-105 transition-transform duration-500" data-alt="close-up of a film reel and vintage cinema gear with dramatic lighting and deep shadows" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBI1P7f13NlnT-BZ8-AXG66whcV0ei8M6odOGiwHB90B0JjyTlApaopXL2MFqiDAD5mVr0pQUlYGVJZ_IGdpk0tfG8w3vKegk1ZUN4yI7EZWLnFolilx7Yj-Yi5Jls0I6nbWG04IZtl924YTsF7dWQ57leEFXhFum4O_7N4UTB5rcotK_awDD23a1-I9KXWyu-sUkTq_uvEyaBo6Auu3r5pFAz5YHhEsbcSRWn8OvGPplhcoUt-MvaCxJ_CsRhK0N7gJ8cuNrMHU1J_"/>
</div>
<div class="w-full md:w-1/2">
<div class="flex items-center gap-4 mb-4">
<span class="text-secondary font-bold text-xs uppercase">Кино</span>
<span class="text-on-surface-variant text-xs">8 мин чтения</span>
</div>
<h4 class="text-2xl font-bold mb-4 leading-tight group-hover:text-primary transition-colors">10 фильмов, которые заставят вас замедлиться</h4>
<p class="text-on-surface-variant leading-relaxed mb-6">Подборка картин в жанре «slow cinema», где каждый кадр — произведение искусства, требующее созерцания.</p>
<div class="flex items-center gap-3">
<div class="w-8 h-8 rounded-full bg-surface-container-highest overflow-hidden">
<img class="w-full h-full object-cover" data-alt="portrait of a young woman with a thoughtful expression, soft indoor lighting, natural tones" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAoYIuttcV3Kd8MMsqUeexfyfTq_7EtTZeF9jjcQFVizSncmR4T6-lZd6JHZtvfi5pquvI1gI2Z3yf3R8Y3n6-whn32Y88OQ746diQub5nAfFumCpIB4BiSUDOb_45le4e1frXblF2_6zFy0Ywu39EkSsb6OK2lnZZAjd4MSjt1Rd47gphXTlng13DWhBT8n8ngzUBGO21GfrsukKTx-kpsg_ypRlS536cxqYZn7IWql0Ze3JBSsCZggKanLEuf0TDTfIrGC017XGcX"/>
</div>
<span class="text-sm font-semibold">Марина Светлова</span>
</div>
</div>
</article>
</div>
</div>
<div class="lg:col-span-5 space-y-8">
<!-- Recommendations Sidebar -->
<div class="bg-white rounded-xl p-8 border border-outline-variant/10">
<h3 class="text-xl font-bold mb-6">Популярные жанры</h3>
<div class="flex flex-wrap gap-2">
<span class="px-4 py-2 bg-surface-container-low rounded-full text-sm font-medium hover:bg-primary hover:text-white cursor-pointer transition-colors">Ambient</span>
<span class="px-4 py-2 bg-surface-container-low rounded-full text-sm font-medium hover:bg-primary hover:text-white cursor-pointer transition-colors">Neo-Jazz</span>
<span class="px-4 py-2 bg-surface-container-low rounded-full text-sm font-medium hover:bg-primary hover:text-white cursor-pointer transition-colors">Indie Folk</span>
<span class="px-4 py-2 bg-surface-container-low rounded-full text-sm font-medium hover:bg-primary hover:text-white cursor-pointer transition-colors">Synthwave</span>
<span class="px-4 py-2 bg-surface-container-low rounded-full text-sm font-medium hover:bg-primary hover:text-white cursor-pointer transition-colors">Lo-Fi</span>
<span class="px-4 py-2 bg-surface-container-low rounded-full text-sm font-medium hover:bg-primary hover:text-white cursor-pointer transition-colors">Dream Pop</span>
</div>
<hr class="my-8 border-outline-variant/10"/>
<h3 class="text-xl font-bold mb-6">Сейчас слушают</h3>
<div class="space-y-4">
<div class="flex items-center gap-4 group cursor-pointer">
<div class="w-12 h-12 rounded bg-surface-container-highest overflow-hidden flex-shrink-0">
<img class="w-full h-full object-cover" data-alt="abstract album cover art with swirling liquid textures of blue and gold" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCobcdZCMNvx3rGrnWVEBNfuBFMmOK3Z1pGiCmdV17D4PGMRBCAkO7tG22Ajt_NVNPPsKe4XCmH9mx2tepUgh5Y2MWTdVKmz6FXEiisx-xZfLdBkOMq1sCdl4SJq2la9W7ZqcEefavBcS7fhiKelFIyBZl121010fIL_QvTK2mkVj8PImCAItw3t-oWFmkHFXMFEpa2af95tC6CfGyq8T0g6YJRijcIVg54XtrJLN5nRWUJVoG_FVcUZVT0ANIzvtxq2xUmgwnAskce"/>
</div>
<div class="flex-grow">
<p class="text-sm font-bold group-hover:text-primary transition-colors">Midnight City</p>
<p class="text-xs text-on-surface-variant">M83</p>
</div>
<span class="material-symbols-outlined text-outline" data-icon="more_vert">more_vert</span>
</div>
<div class="flex items-center gap-4 group cursor-pointer">
<div class="w-12 h-12 rounded bg-surface-container-highest overflow-hidden flex-shrink-0">
<img class="w-full h-full object-cover" data-alt="geometric minimal album cover with a single circle and clean lines on a cream background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCdm3i-ADSzP2JXagN-vCE_AbtVShlL4yBLbqTIj58YLfPjlBLqFM81viKDYqghtV83_b40GGlAbhUHevezkDFdW7Tkp11hECer0uQShEPEKAK8isc5s3wQFwTa0zjWaNlfz_YykjX8nQ_Hiucc3eHg5wqhVUWU35CUAt_FZ5j74ZB0KZMmFwVv-YBF6Rwh9WuRtGqaPxgPCxHAWfFedIoaZxXAbXpe70CxJERsB7kIjwcuEtWJ0Ll3eZD8oGLvAH8x4nkVSUUs4efC"/>
</div>
<div class="flex-grow">
<p class="text-sm font-bold group-hover:text-primary transition-colors">Ocean Drive</p>
<p class="text-xs text-on-surface-variant">Duke Dumont</p>
</div>
<span class="material-symbols-outlined text-outline" data-icon="more_vert">more_vert</span>
</div>
</div>
</div>
<!-- Ad/Promo Card -->
<div class="bg-tertiary-container text-on-tertiary-container rounded-xl p-8 relative overflow-hidden">
<div class="relative z-10">
<h4 class="text-2xl font-headline font-bold mb-4">Chill Premium</h4>
<p class="text-sm mb-6 opacity-90">Слушай без рекламы и в самом высоком качестве. Первая неделя бесплатно.</p>
<button class="bg-white text-tertiary-container px-6 py-3 rounded-full font-bold text-sm shadow-xl">Попробовать</button>
</div>
<div class="absolute -right-8 -bottom-8 opacity-20">
<span class="material-symbols-outlined text-[180px]" data-icon="auto_awesome">auto_awesome</span>
</div>
</div>
</div>
</section>
</main>
<!-- BottomNavBar -->
<nav class="fixed bottom-0 left-0 w-full z-50 flex justify-around items-end px-4 pb-6 pt-2 bg-[#f7f9fc]/80 backdrop-blur-xl md:hidden shadow-[0_-12px_32px_rgba(25,28,30,0.06)] rounded-t-[3rem]">
<a class="flex flex-col items-center justify-center text-[#191c1e] p-2 opacity-70 hover:opacity-100 transition-opacity" href="#">
<span class="material-symbols-outlined" data-icon="sports_soccer">sports_soccer</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Спорт</span>
</a>
<a class="flex flex-col items-center justify-center text-[#191c1e] p-2 opacity-70 hover:opacity-100 transition-opacity" href="#">
<span class="material-symbols-outlined" data-icon="sports_esports">sports_esports</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Игры</span>
</a>
<a class="flex flex-col items-center justify-center text-[#191c1e] p-2 opacity-70 hover:opacity-100 transition-opacity" href="#">
<span class="material-symbols-outlined" data-icon="devices">devices</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Техно</span>
</a>
<a class="flex flex-col items-center justify-center bg-[#183ce6] text-white rounded-full p-3 scale-110 -translate-y-2 transition-transform" href="#">
<span class="material-symbols-outlined" data-icon="music_note" style="font-variation-settings: 'FILL' 1;">music_note</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Музыка</span>
</a>
<a class="flex flex-col items-center justify-center text-[#191c1e] p-2 opacity-70 hover:opacity-100 transition-opacity" href="#">
<span class="material-symbols-outlined" data-icon="movie">movie</span>
<span class="font-['Manrope'] text-[10px] font-semibold uppercase tracking-wider mt-1">Кино</span>
</a>
</nav>
<!-- Floating Action Button -->
<button class="fixed right-6 bottom-32 md:bottom-12 w-14 h-14 bg-primary-container text-on-primary-container rounded-full shadow-2xl flex items-center justify-center hover:scale-110 transition-transform z-40">
<span class="material-symbols-outlined" data-icon="add" style="font-variation-settings: 'wght' 600;">add</span>
</button>
</body></html>
