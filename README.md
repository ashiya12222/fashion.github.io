<!DOCTYPE html>
<html lang="en"><head>
<meta charset="utf-8"/>
<link crossorigin="" href="https://fonts.gstatic.com/" rel="preconnect"/>
<link as="style" href="https://fonts.googleapis.com/css2?display=swap&amp;family=Manrope:wght@400;500;700;800" onload="this.rel='stylesheet'" rel="stylesheet"/>
<title>Stitch Design</title>
<link href="data:image/x-icon;base64," rel="icon" type="image/x-icon"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script>
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              primary: "#1173d4",
              "background-light": "#f6f7f8",
              "background-dark": "#101922",
            },
            fontFamily: {
              display: ["Manrope"],
            },
            borderRadius: { DEFAULT: "0.25rem", lg: "0.5rem", xl: "0.75rem", full: "9999px" },
          },
        },
      };
    </script>
</head>
<body class="bg-background-light dark:bg-background-dark font-display">
<div class="relative flex min-h-screen w-full flex-col group/design-root overflow-x-hidden">
<div class="layout-container flex h-full grow flex-col">
<header class="flex items-center justify-between whitespace-nowrap border-b border-primary/20 dark:border-primary/30 px-10 py-4">
<div class="flex items-center gap-3 text-background-dark dark:text-background-light">
<svg class="h-6 w-6 text-primary" fill="none" viewBox="0 0 48 48" xmlns="http://www.w3.org/2000/svg">
<path clip-rule="evenodd" d="M24 4H42V17.3333V30.6667H24V44H6V30.6667V17.3333H24V4Z" fill="currentColor" fill-rule="evenodd"></path>
</svg>
<h2 class="text-xl font-bold">{Brand Name}</h2>
</div>
<nav class="hidden lg:flex items-center gap-8">
<a class="text-sm font-medium text-background-dark/80 dark:text-background-light/80 hover:text-primary" href="#">Home</a>
<a class="text-sm font-medium text-background-dark/80 dark:text-background-light/80 hover:text-primary" href="#">Product</a>
<a class="text-sm font-medium text-background-dark/80 dark:text-background-light/80 hover:text-primary" href="#">Pricing</a>
<a class="text-sm font-medium text-background-dark/80 dark:text-background-light/80 hover:text-primary" href="#">Blog</a>
<a class="text-sm font-medium text-background-dark/80 dark:text-background-light/80 hover:text-primary" href="#">Contact</a>
</nav>
<div class="flex items-center gap-2">
<button class="flex min-w-[84px] cursor-pointer items-center justify-center overflow-hidden rounded-lg h-10 px-4 bg-primary text-white text-sm font-bold tracking-wide hover:bg-primary/90 transition-colors">
<span class="truncate">Shop New Arrivals</span>
</button>
<button class="flex cursor-pointer items-center justify-center overflow-hidden rounded-lg h-10 w-10 bg-background-light dark:bg-background-dark border border-primary/20 dark:border-primary/30 text-background-dark dark:text-background-light hover:bg-primary/10 dark:hover:bg-primary/20 transition-colors">
<svg fill="currentColor" height="20px" viewBox="0 0 256 256" width="20px" xmlns="http://www.w3.org/2000/svg">
<path d="M229.66,218.34l-50.07-50.06a88.11,88.11,0,1,0-11.31,11.31l50.06,50.07a8,8,0,0,0,11.32-11.32ZM40,112a72,72,0,1,1,72,72A72.08,72.08,0,0,1,40,112Z"></path>
</svg>
</button>
</div>
</header>
<main class="flex-1 px-4 sm:px-6 lg:px-8">
<div class="mx-auto max-w-7xl">
<section class="my-12">
<div class="relative flex min-h-[500px] flex-col items-start justify-end rounded-xl bg-cover bg-center p-8 text-white shadow-lg" style='background-image: linear-gradient(rgba(0, 0, 0, 0.2) 0%, rgba(0, 0, 0, 0.5) 100%), url("https://lh3.googleusercontent.com/aida-public/AB6AXuAeX1kIBWYfedW6qvMxgDjOCWc2uFpdj2hhV2O-mB0vop7ljp-vg0Wz_JOIcZcskIKk-_XV2bZQuxBH1dOsb2FuQu9NZWA6YvijbqsN1o6QUAosTvzKxEtrOSMMPL0FBPjS4TWNl_bABGtNY7qU-CBZPcS7MorsdL93C4daI4pU5oShZ8jtXcQAEfnbTkk95jF6obvmf-2BkVJ-Ws-RessYmC5XD2fJ1amTWS8YhARF35Am1qBmy0H09HGmgP7oHy1zeAkEhpVvUSCz");'>
<div class="max-w-xl">
<h1 class="text-4xl font-extrabold tracking-tighter sm:text-5xl lg:text-6xl">Wear Your Future</h1>
<p class="mt-4 text-base sm:text-lg">Step into tomorrow's style with our latest collection. Designed for the modern individual, our pieces blend innovation with timeless elegance.</p>
</div>
<div class="mt-8 flex flex-wrap gap-4">
<button class="flex min-w-[120px] items-center justify-center rounded-lg bg-primary px-5 py-3 text-sm font-bold text-white transition-colors hover:bg-primary/90">Shop Women</button>
<button class="flex min-w-[120px] items-center justify-center rounded-lg bg-background-light px-5 py-3 text-sm font-bold text-background-dark transition-colors hover:bg-background-light/80">Shop Men</button>
</div>
</div>
</section>
<section class="my-16 text-center">
<h2 class="text-3xl font-bold tracking-tight text-background-dark dark:text-background-light">New Arrivals</h2>
<p class="mt-2 text-base text-background-dark/70 dark:text-background-light/70">Be the first to explore our latest collection.</p>
<div class="mt-8 grid grid-cols-2 gap-4 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5">
<div class="group relative">
<div class="w-full overflow-hidden rounded-lg bg-cover bg-center aspect-[3/4]" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuBbdHDGKl8ONm_ubX9zPObK6mRbjOMKPB774GCHpiV5t_Zu92kkpzISrOYhEpSDKjqWWjXAD2bWWBXzxCV6GP7meoiYcBF06U0DUJwKd5jdWeVm9DQY_Qe09TAxHST9-cbeTVTdYdGDCXTaOYoSFv1_jiZwvtnF1hUdIHD3dfYmzRAf-PLVAhg0m3r_X3rwzGToFAYU9qYQ_1bmtZxlsgLD5f2IPWv3fEFuxFt_R7E-dZ2A4QIRtsAx_7GHZCtD2GYESGqYEppBhudy");'></div>
<div class="absolute inset-0 flex items-center justify-center bg-black/40 opacity-0 group-hover:opacity-100 transition-opacity">
<button class="rounded-full bg-primary p-3 text-white"><svg fill="currentColor" height="24" viewBox="0 0 256 256" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M224,128a8,8,0,0,1-8,8H136v80a8,8,0,0,1-16,0V136H40a8,8,0,0,1,0-16h80V40a8,8,0,0,1,16,0v80h80A8,8,0,0,1,224,128Z"></path></svg></button>
</div>
</div>
<div class="group relative">
<div class="w-full overflow-hidden rounded-lg bg-cover bg-center aspect-[3/4]" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuA6a2_StNEDJ0wtgeh6h9l3QaXdg0UZlMB3-SI45IKs65WE5cHdd0VwGdawQxBvYgjvjuWNAz9NxDlDE8vSJku5IHp3l6hGGlTg03A8jB_YV7TRULlVAa1jXkr9HbbPyeW2S7PnmHJCdOx2raAaMa_TdYIUp57RQYy6WNt1_kB39nnfBRTjeleAKwZZfYnA5SeZxtBBkvmZTnaGO5TxSMRFWUAETLeIfWc1ZJqMG1pmJ-CEf7OHgLo2Pa3MWkLvjumeiAXS0w7R6A-b");'></div>
<div class="absolute inset-0 flex items-center justify-center bg-black/40 opacity-0 group-hover:opacity-100 transition-opacity">
<button class="rounded-full bg-primary p-3 text-white"><svg fill="currentColor" height="24" viewBox="0 0 256 256" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M224,128a8,8,0,0,1-8,8H136v80a8,8,0,0,1-16,0V136H40a8,8,0,0,1,0-16h80V40a8,8,0,0,1,16,0v80h80A8,8,0,0,1,224,128Z"></path></svg></button>
</div>
</div>
<div class="group relative">
<div class="w-full overflow-hidden rounded-lg bg-cover bg-center aspect-[3/4]" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuAlHbfcbFH8LbYq_S00IviWoCjHd3gj9jw2n-RMDT9gM2JJyN_NbRtnoWJqAL9CGZRatSUk4owxEmRa-ItAKTVo4tf6D2tRCylg1ecUKfohZXuSwrEeSKTCpMaSLwa66yMgTQrsFda_aTODPfY-rxvn3hesZqjhXSxOJMrujLyPmLWONUpzJAo2jDIqXGF0FSxDucZVaCPeGYRNiAVP1RBdtRT3rRB31l47Eo_Tg2bXQw1uMGuTMLvs7KD9_TfbkG6ePIyL0FCoFMSK");'></div>
<div class="absolute inset-0 flex items-center justify-center bg-black/40 opacity-0 group-hover:opacity-100 transition-opacity">
<button class="rounded-full bg-primary p-3 text-white"><svg fill="currentColor" height="24" viewBox="0 0 256 256" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M224,128a8,8,0,0,1-8,8H136v80a8,8,0,0,1-16,0V136H40a8,8,0,0,1,0-16h80V40a8,8,0,0,1,16,0v80h80A8,8,0,0,1,224,128Z"></path></svg></button>
</div>
</div>
<div class="group relative">
<div class="w-full overflow-hidden rounded-lg bg-cover bg-center aspect-[3/4]" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuDdqjIjwBMXlK4pOhE_qT1X3E0LEcnu6B3KkpFlAGaG-6pzPqbLUmrKtXKWkitO3piSHyS5pEjlHMP3JwmX1xnRAxFk0UcTzzUlnLKbE3kHZR3gPA1m-JEIFWprfbA1xKw2KPiA5ZfaIjIVmV7xOQiTKnifzt8mbsHBbdmcB4YlYpGmnxO85ZgvcygdVWNoPKSKdQBp3Kaz6yjhsgIILU_Z4m_xRzx1aDyV_u7XlTTAM-MBLae_ZRZnAltQbtT5MGBIP3OX6Du4hiM3");'></div>
<div class="absolute inset-0 flex items-center justify-center bg-black/40 opacity-0 group-hover:opacity-100 transition-opacity">
<button class="rounded-full bg-primary p-3 text-white"><svg fill="currentColor" height="24" viewBox="0 0 256 256" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M224,128a8,8,0,0,1-8,8H136v80a8,8,0,0,1-16,0V136H40a8,8,0,0,1,0-16h80V40a8,8,0,0,1,16,0v80h80A8,8,0,0,1,224,128Z"></path></svg></button>
</div>
</div>
<div class="group relative">
<div class="w-full overflow-hidden rounded-lg bg-cover bg-center aspect-[3/4]" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuCtOPKEBAMO9bjvPZQfW2ncApPgoxdyYbMCR-1JEfQ_bSrZXWqcrG0a3XzQKVu4flRr4jsKisF-IDmSR73Nw0D-2iLdydwAUBzCF15NiSsbPkBAJMIlu6hDIBSf27P04ODAeFVcdgBNeR_MIGe8MoQ4dJTskjKmkf9IjiPIRDwrJaK1dMEKzSWSROeF5Xd6hi3BJaMa1E6omNsOXelBJn8NP3MVdIPW_3YZfaQItPAYTTe0Dm35UMtiDr3LQYcT6-D85hlDmKx0KEc4");'></div>
<div class="absolute inset-0 flex items-center justify-center bg-black/40 opacity-0 group-hover:opacity-100 transition-opacity">
<button class="rounded-full bg-primary p-3 text-white"><svg fill="currentColor" height="24" viewBox="0 0 256 256" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M224,128a8,8,0,0,1-8,8H136v80a8,8,0,0,1-16,0V136H40a8,8,0,0,1,0-16h80V40a8,8,0,0,1,16,0v80h80A8,8,0,0,1,224,128Z"></path></svg></button>
</div>
</div>
<div class="group relative hidden sm:block">
<div class="w-full overflow-hidden rounded-lg bg-cover bg-center aspect-[3/4]" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuCzkdmnGckfWjba2-g2N5gSGYpy66-gyidU3cWyScSGZqCgz-1at9uUs5OXkRI6ZQGO6IPeVfNUR4Q_TV-JUJg-r-RttBvu0LLQH5-CK-yuykyU5pWwmoBpL4YJLBSrilOUEplzkslK_qEEaRBawQti11GvA5zjQqVO4ZBbdk8zRYG6HuEY0lESqZn0U5XjhMHINbP2W2mdLCOCbJH0po_SgY1riwljptDGaL5jFugl5t8Xn2ObXCTEyFZGNPE-l6OcHK2V1aaCelPc");'></div>
<div class="absolute inset-0 flex items-center justify-center bg-black/40 opacity-0 group-hover:opacity-100 transition-opacity">
<button class="rounded-full bg-primary p-3 text-white"><svg fill="currentColor" height="24" viewBox="0 0 256 256" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M224,128a8,8,0,0,1-8,8H136v80a8,8,0,0,1-16,0V136H40a8,8,0,0,1,0-16h80V40a8,8,0,0,1,16,0v80h80A8,8,0,0,1,224,128Z"></path></svg></button>
</div>
</div>
<div class="group relative hidden md:block">
<div class="w-full overflow-hidden rounded-lg bg-cover bg-center aspect-[3/4]" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuB6t6FsIaQ5HC19aMu3XSB9Sxh1Yu7eU_gse3I4mnvNFMiAEd5E935eeFc8T16Q4cA0tCw2cJRCCwH9o_6YdG7nRct0y2zbWzyy8UKZrIqi7IT_IGFYGjiutEJyz8ur3iVLPNb3lW2gWOEXYQKYJpjMCjhXHujTw6Hbp-7g_mSNu70LW5I-LmK9BrZmCJoCUxw34VTKJetbafFUT8w4xK3dMIB3MZ-yAgqunip4v981xpGr3uZgfc-d6Sr1x1YtrZ4AAUuTdz5SGHIr");'></div>
<div class="absolute inset-0 flex items-center justify-center bg-black/40 opacity-0 group-hover:opacity-100 transition-opacity">
<button class="rounded-full bg-primary p-3 text-white"><svg fill="currentColor" height="24" viewBox="0 0 256 256" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M224,128a8,8,0,0,1-8,8H136v80a8,8,0,0,1-16,0V136H40a8,8,0,0,1,0-16h80V40a8,8,0,0,1,16,0v80h80A8,8,0,0,1,224,128Z"></path></svg></button>
</div>
</div>
<div class="group relative hidden lg:block">
<div class="w-full overflow-hidden rounded-lg bg-cover bg-center aspect-[3/4]" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuCdCoyQAkNM_h_Wot9w4e2CpwnnBXywxnYe-DVQyLlXpRaRhA7aa7clJIrLpUoJCOLLE91fcUcBS0o1U7TVLaH0lBxCKIJz0DEAPkKcCR-J4SsdlshbkXob2wCGdz2LUI8GBy5ut76-J2UD4BMTVnLTqwlT9aRi3_uDgWSaWcwSTdrboJqvmTnZIlS7aKjZygqEk4naL_aZautE1M65ZJ-7DwAJtJgzo7QIRtq1OMOZir0rWlr0WwXF5GTY0sZERDjU3ApS0fGt1bJn");'></div>
<div class="absolute inset-0 flex items-center justify-center bg-black/40 opacity-0 group-hover:opacity-100 transition-opacity">
<button class="rounded-full bg-primary p-3 text-white"><svg fill="currentColor" height="24" viewBox="0 0 256 256" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M224,128a8,8,0,0,1-8,8H136v80a8,8,0,0,1-16,0V136H40a8,8,0,0,1,0-16h80V40a8,8,0,0,1,16,0v80h80A8,8,0,0,1,224,128Z"></path></svg></button>
</div>
</div>
</div>
</section>
<section class="my-16">
<h2 class="text-3xl font-bold tracking-tight text-center text-background-dark dark:text-background-light">Bestsellers</h2>
<p class="mt-2 text-base text-center text-background-dark/70 dark:text-background-light/70">Loved by you, for a reason.</p>
<div class="mt-8 flex overflow-x-auto gap-6 pb-4 [-ms-scrollbar-style:none] [scrollbar-width:none] [&amp;::-webkit-scrollbar]:hidden">
<div class="flex-shrink-0 w-64">
<div class="w-full bg-cover bg-center aspect-[3/4] rounded-lg" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuCj9Bwt-N536E1-di2jjg9IFghnjQWBVMl8LGAa5v0dwK_1WVXOJwDkdxljyuNKkR8x1ppXt8_pz47evZtBf-d1IXy85l-WpGA7WZw9uBfjj26bYracqpb7YSqsOA4KKx9WZRgWxAP8QEMJXaZTmra99o6wNbYgHLhVd3-bojQqZ_845jK33yUh89RY461IZYLnjrjAdXTaLtzmPdCOuwUEFgn0okrhr1DfBkPRyvyjMQlKlRE7ZiyKYyUalyIdxPFa7NMLP6YKwIi6");'></div>
<div class="mt-2">
<p class="font-semibold text-background-dark dark:text-background-light">The Urban Explorer</p>
<p class="text-sm text-background-dark/70 dark:text-background-light/70">Discover pieces that redefine city style.</p>
</div>
</div>
<div class="flex-shrink-0 w-64">
<div class="w-full bg-cover bg-center aspect-[3/4] rounded-lg" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuC1gQmWB_ppqvJH3qipUXp6HMZafkwCudIqW0ptpbeLLC4RaLbpPAy7O7xaZRmyb2IfReOd4chB_bOxE8gSYgCI9dA_1U2EW_DebDakpvc28Is7NojsxJESMeClT2oURT5k3XC9VNdKo4WG46hD3e0QnlCfdbGMrcibaICWSltXPxlzVl1JUuoUQorh_X-PjgBG7bk2aWIG4pjJNlYHi9PaH3BpSeJG6FPLaJiSIwYZXhBEGijClLWyUwjIq6Ou3eTcHvhZGTuPfkNT");'></div>
<div class="mt-2">
<p class="font-semibold text-background-dark dark:text-background-light">The Modern Minimalist</p>
<p class="text-sm text-background-dark/70 dark:text-background-light/70">Embrace simplicity with our curated collection.</p>
</div>
</div>
<div class="flex-shrink-0 w-64">
<div class="w-full bg-cover bg-center aspect-[3/4] rounded-lg" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuC6Gg7yUhxr1UwUIWxIn23ALVXIrmQL_IuxhQC2UEXtCWsZ_7r0wXkupxNwICZUsRbeJra_8qdGvWAu-xXAnvkSDZSeBURxOK9e2EtgLH-KjS9dMg50UNY-A8XlWFfStCYRCghDui6JPQ_g_4Ra_6SaH6ddper3Xb0ewcIoAv22XLMMcc214jmLxfHKIAAO9KRl8523zQmFiRzVCrPLN5qwnH-XSxcYGvejDrPBcSwnInueor48CN7eXwm7J6gx-z7bzkqcFZdlifuJ");'></div>
<div class="mt-2">
<p class="font-semibold text-background-dark dark:text-background-light">The Bold Statement</p>
<p class="text-sm text-background-dark/70 dark:text-background-light/70">Make an impact with our standout designs.</p>
</div>
</div>
<div class="flex-shrink-0 w-64">
<div class="w-full bg-cover bg-center aspect-[3/4] rounded-lg" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuA42s1yQ5n6qmqM2R3x0a8I2ZYdrbFJ2YDMQK19Rbb_CZ5Rr0ul0bmp5hS4ZZosQpydbHlRSHiYp8nkHVRYPqlC2okpWK9ryUx_LLsW6KvSGYK3gr_Qfe0EzwSy2UHakAVFbAIr7b6Gh357v6f82htm0hAz-_VketM7E2O8oMjv32D_D5x8u6sadUSGtEAd3pkAtOkXZyDlDMD64LygczL495cvZjnCkf0DDj1KgNqYGXU7KkmQBKMMxo6jycPfd0mKSCKbvi2KEktM");'></div>
<div class="mt-2">
<p class="font-semibold text-background-dark dark:text-background-light">The Casual Chic</p>
<p class="text-sm text-background-dark/70 dark:text-background-light/70">Effortless style for everyday wear.</p>
</div>
</div>
</div>
</section>
<section class="my-16">
<div class="relative flex min-h-[400px] items-end justify-start rounded-xl bg-cover bg-center p-8 text-white shadow-lg" style='background-image: linear-gradient(0deg, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0) 40%), url("https://lh3.googleusercontent.com/aida-public/AB6AXuCI_4ljaELiObIRvhtV2yIyGImAdieRzlrKzGudQ846KxDrRkYDKRF9GV0Ddi6lLERIBMUlTxoG1tkzOr2TgJxK4ldA6VjDYDLUOTcwxDEFdE1SHTDGr1HGmW5vWlUKKmK4NbdnLyRh_9OEzdY3uPgA6scbjUuLDcOPJWIkYR0GgJacIP5zy1jxB_jD-LH-smUGELpJx5ECBwTFJEygbroxLcnKyFefoioAlSN4bafSIGVv0Iv2BISIg6t8KISn6pqPw8NhVsRuhYlW");'>
<div class="max-w-md">
<h2 class="text-4xl font-bold tracking-tight">Crafted with Care</h2>
<p class="mt-2">Discover our commitment to sustainability and ethical craftsmanship.</p>
</div>
</div>
</section>
<section class="my-16">
<h2 class="text-3xl font-bold tracking-tight text-center text-background-dark dark:text-background-light">As Seen In</h2>
<div class="mt-8 grid grid-cols-2 md:grid-cols-4 gap-8 items-center justify-items-center grayscale">
<img alt="Vogue logo" class="h-8 object-contain" src="https://lh3.googleusercontent.com/aida-public/AB6AXuANDhkhDQxam49j4MnlZ606IpJZS2RNUOjKU1gkIXIHZWNJhqalhfWF4lNMGmicpWm1AaqiHXPoPXSIU8-aKf2O9o-5dft3hl0WFEkDLnFaLxohhrC6c3Di6GnC6_nXxQDBm8BEn_CfCQEWIMYv6SzU6RSVTKmYDPYsuU93k1ze827176jWKf1VcKT24wnHexmsRX078-k3UMO149kF0DvaiwDBN6GmMFKl94OTdl1yKwckJSqnquHhZ2eMQu69UgndtjIBhwgj3N7j"/>
<img alt="Elle logo" class="h-8 object-contain" src="https://lh3.googleusercontent.com/aida-public/AB6AXuA1-K_MHHALWbeGJ5jUNXUnOMSwDDU2NbgqyIT4zw1ES8Z5YYbdeheqPVCr6wd-gVwGR7Q6MFk2x8Uyxp9lv_CSzBGbwAWz0wwmAXzpxTa7cEoINfCVBgtck_wRJgXvZdHJnkAMDPyTRNAgF_onSdZjecGNEx3aWxcDMwuH4DwghQKPzkDigj_JLR6NMVYOKC1qbRECJR81Upg_0CKUbqhsWwLiHlAsoF_laD4feE4SBiiRmzqkctueO8ZAXQqjaBJfYD_-4fsH-Ues"/>
<img alt="GQ logo" class="h-8 object-contain" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAyl9EuLvuk_e2frqAmMPMlK8GhqU9eg8ITP3NNjDnGBwIBfw_RM8G2tEljyjKz7X0DcrtfXpv_qLjhVbXoMecqOF7O2mgdVzAQ0QRD5oUindrAguIeHJl94ZUgDytzJlKBjsGwJ61PsD0u5A3PToLzdsrItq46Pcy2INBnJKYXOz3hdcXPaZ5DlfUGj6zQa5EWAs8YSSEjU5-cCrCNqTMX6MaAS5_CdNo2kmY2J7LnxSvxsiXJllIWi-ILI6BA6KuPJmUwrgvWlL1W"/>
<img alt="Harper's Bazaar logo" class="h-8 object-contain" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCb8on9iIQTCdGMV4mtpCvhh23aueWuhJZAjPfWWxkQEavFq370ds6r-QzkBwH6e7_0Nm469mWVXO_4KDVoj3ZHJUmD9ddS6Vlzecrt1BJjVqwoYl7CN8tUqxWVuixedNwDygOnrYxMSllZsBtauHTPQb35GAf32reSXrTgaRohV-9mz5EUp0ZrKkgBpXuQiRBsUM7IngCbqL29EGgGMqBxMc3-Uji-up403YU2z6nFuwCsNbPGm-VTSHBwIgPCiPU3iPSJqqcVQncZ"/>
</div>
<div class="mt-12 space-y-8 max-w-2xl mx-auto">
<blockquote class="text-center">
<p class="text-lg italic text-background-dark dark:text-background-light">"This brand has completely transformed my wardrobe. The quality and design are unmatched, making every piece a staple in my daily wear."</p>
<footer class="mt-2 text-sm font-semibold text-background-dark/80 dark:text-background-light/80">- Sophia Carter</footer>
</blockquote>
<blockquote class="text-center">
<p class="text-lg italic text-background-dark dark:text-background-light">"I love the brand's commitment to sustainability and ethical practices. It's fashion I can feel good about wearing."</p>
<footer class="mt-2 text-sm font-semibold text-background-dark/80 dark:text-background-light/80">- Ethan Walker</footer>
</blockquote>
</div>
</section>
<section class="my-16 py-16 bg-primary/10 dark:bg-primary/20 rounded-xl">
<div class="flex flex-col items-center justify-center gap-6 px-4">
<div class="text-center">
<h2 class="text-3xl font-bold tracking-tight text-background-dark dark:text-background-light">Stay in the Loop</h2>
<p class="mt-2 text-base text-background-dark/70 dark:text-background-light/70 max-w-2xl mx-auto">Sign up for exclusive offers, style tips, and the latest news. We respect your privacy.</p>
</div>
<form class="flex w-full max-w-md">
<label class="sr-only" for="email-address">Email address</label>
<input autocomplete="email" class="form-input flex-auto min-w-0 rounded-l-lg border-primary/30 bg-background-light px-4 py-3 text-background-dark placeholder-background-dark/50 focus:ring-2 focus:ring-inset focus:ring-primary dark:bg-background-dark dark:text-background-light dark:placeholder-background-light/50" id="email-address" name="email" placeholder="Enter your email" required="" type="email"/>
<button class="flex-none rounded-r-lg bg-primary px-5 py-3 text-sm font-bold text-white hover:bg-primary/90" type="submit">
                    Subscribe
                  </button>
</form>
</div>
</section>
</div>
</main>
<footer class="border-t border-primary/20 dark:border-primary/30 text-background-dark/70 dark:text-background-light/70">
<div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8 py-12">
<div class="flex flex-col md:flex-row justify-between items-center gap-8">
<p class="text-sm">© 2024 {Brand Name}. All rights reserved.</p>
<div class="flex gap-6">
<a class="hover:text-primary" href="#">Privacy Policy</a>
<a class="hover:text-primary" href="#">Terms of Service</a>
</div>
<div class="flex justify-center gap-6">
<a class="hover:text-primary" href="#"><svg fill="currentColor" height="24" viewBox="0 0 256 256" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M128,80a48,48,0,1,0,48,48A48.05,48.05,0,0,0,128,80Zm0,80a32,32,0,1,1,32-32A32,32,0,0,1,128,160ZM176,24H80A56.06,56.06,0,0,0,24,80v96a56.06,56.06,0,0,0,56,56h96a56.06,56.06,0,0,0,56-56V80A56.06,56.06,0,0,0,176,24Zm40,152a40,40,0,0,1-40,40H80a40,40,0,0,1-40-40V80A40,40,0,0,1,80,40h96a40,40,0,0,1,40,40ZM192,76a12,12,0,1,1-12-12A12,12,0,0,1,192,76Z"></path></svg></a>
<a class="hover:text-primary" href="#"><svg fill="currentColor" height="24" viewBox="0 0 256 256" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M247.39,68.94A8,8,0,0,0,240,64H209.57A48.66,48.66,0,0,0,168.1,40a46.91,46.91,0,0,0-33.75,13.7A47.9,47.9,0,0,0,120,88v6.09C79.74,83.47,46.81,50.72,46.46,50.37a8,8,0,0,0-13.65,4.92c-4.31,47.79,9.57,79.77,22,98.18a110.93,110.93,0,0,0,21.88,24.2c-15.23,17.53-39.21,26.74-39.47,26.84a8,8,0,0,0-3.85,11.93c.75,1.12,3.75,5.05,11.08,8.72C53.51,229.7,65.48,232,80,232c70.67,0,129.72-54.42,135.75-124.44l29.91-29.9A8,8,0,0,0,247.39,68.94Zm-45,29.41a8,8,0,0,0-2.32,5.14C196,166.58,143.28,216,80,216c-10.56,0-18-1.4-23.22-3.08,11.51-6.25,27.56-17,37.88-32.48A8,8,0,0,0,92,169.08c-.47-.27-43.91-26.34-44-96,16,13,45.25,33.17,78.67,38.79A8,8,0,0,0,136,104V88a32,32,0,0,1,9.6-22.92A30.94,30.94,0,0,1,167.9,56c12.66.16,24.49,7.88,29.44,19.21A8,8,0,0,0,204.67,80h16Z"></path></svg></a>
<a class="hover:text-primary" href="#"><svg fill="currentColor" height="24" viewBox="0 0 256 256" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M224,72a48.05,48.05,0,0,1-48-48,8,8,0,0,0-8-8H128a8,8,0,0,0-8,8V156a20,20,0,1,1-28.57-18.08A8,8,0,0,0,96,130.69V88a8,8,0,0,0-9.4-7.88C50.91,86.48,24,119.1,24,156a76,76,0,0,0,152,0V116.29A103.25,103.25,0,0,0,224,128a8,8,0,0,0,8-8V80A8,8,0,0,0,224,72Zm-8,39.64a87.19,87.19,0,0,1-43.33-16.15A8,8,0,0,0,160,102v54a60,60,0,0,1-120,0c0-25.9,16.64-49.13,40-57.6v27.67A36,36,0,1,0,136,156V32h24.5A64.14,64.14,0,0,0,216,87.5Z"></path></svg></a>
<a class="hover:text-primary" href="#"><svg fill="currentColor" height="24" viewBox="0 0 256 256" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M216,112c0,22.57-7.9,43.2-22.23,58.11C180.39,184,162.25,192,144,192c-17.88,0-29.82-5.86-37.43-12L95.79,225.83A8,8,0,0,1,88,232a8.24,8.24,0,0,1-1.84-.21,8,8,0,0,1-6-9.62l32-136a8,8,0,0,1,15.58,3.66l-16.9,71.8C114,166,123.3,176,144,176c27.53,0,56-23.94,56-64A72,72,0,1,0,65.63,148a8,8,0,0,1-13.85,8A88,88,0,1,1,216,112Z"></path></svg></a>
<a class="hover:text-primary" href="#"><svg fill="currentColor" height="24" viewBox="0 0 256 256" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M216,24H40A16,16,0,0,0,24,40V216a16,16,0,0,0,16,16H216a16,16,0,0,0,16-16V40A16,16,0,0,0,216,24Zm0,192H40V40H216V216ZM96,112v64a8,8,0,0,1-16,0V112a8,8,0,0,1,16,0Zm88,28v36a8,8,0,0,1-16,0V140a20,20,0,0,0-40,0v36a8,8,0,0,1-16,0V112a8,8,0,0,1,15.79-1.78A36,36,0,0,1,184,140ZM100,84A12,12,0,1,1,88,72,12,12,0,0,1,100,84Z"></path></svg></a>
</div>
</div>
</div>
</footer>
</div>
</div>

</body></html>
