# Desain UI/UX Bang Zul Egg Market

Dokumen ini berisi hasil salinan kode HTML dari desain UI/UX yang dibuat menggunakan Stitch AI. Kode dipertahankan apa adanya agar struktur, styling, dan komponen desain tetap dapat digunakan.

## Source Code HTML

```html
<!-- Katalog Belanja Pembeli -->
<!DOCTYPE html>

<html lang="id"><head><meta charset="utf-8"/><meta content="width=device-width, initial-scale=1.0" name="viewport"/><meta content="web_standard" name="shell-type"/><link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" rel="stylesheet"/><link href="https://fonts.googleapis.com" rel="preconnect"/><link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/><link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&amp;family=Plus+Jakarta+Sans:wght@700;800&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/><style>@layer base{html,body{margin:0;padding:0;}body{overscroll-behavior:none;}main>:first-child{margin-top:0!important;}main>:last-child{margin-bottom:0!important;}}::-webkit-scrollbar{display:none;}</style><script src="https://cdn.tailwindcss.com"></script><script id="tailwind-config">tailwind.config={darkMode:"class",theme:{extend:{colors:{"on-primary-container":"#644000","on-secondary-fixed-variant":"#005312","surface":"#fcf9f8","on-tertiary-fixed-variant":"#3e4a41","on-secondary":"#ffffff","surface-container-lowest":"#ffffff","on-primary-fixed-variant":"#633f00","on-primary":"#ffffff","primary-container":"#f5a623","error":"#ba1a1a","tertiary-fixed":"#d9e6da","on-primary-fixed":"#291800","tertiary-fixed-dim":"#bdcabe","surface-container-high":"#eae7e7","surface-dim":"#dcd9d9","on-error-container":"#93000a","tertiary":"#556158","outline-variant":"#d7c3ae","secondary-container":"#a0f399","inverse-on-surface":"#f3f0f0","on-secondary-container":"#217128","background":"#fcf9f8","on-surface-variant":"#524534","on-error":"#ffffff","surface-variant":"#e4e2e1","surface-bright":"#fcf9f8","error-container":"#ffdad6","primary":"#835500","secondary-fixed":"#a3f69c","primary-fixed-dim":"#ffb955","inverse-surface":"#303030","on-background":"#1b1c1c","on-tertiary":"#ffffff","surface-tint":"#835500","on-tertiary-container":"#3e4a41","inverse-primary":"#ffb955","surface-container-low":"#f6f3f2","secondary-fixed-dim":"#88d982","on-surface":"#1b1c1c","tertiary-container":"#acb9ae","secondary":"#1b6d24","surface-container-highest":"#e4e2e1","surface-container":"#f0eded","primary-fixed":"#ffddb4","outline":"#857462","on-secondary-fixed":"#002204","on-tertiary-fixed":"#131e17"},borderRadius:{"DEFAULT":"0.25rem","lg":"0.5rem","xl":"0.75rem","full":"9999px"},spacing:{"gutter-desktop":"1.5rem","margin-desktop":"2.5rem","gutter":"1rem","space-lg":"1.5rem","space-xl":"2rem","margin":"1rem","space-md":"1rem","space-xs":"0.25rem","space-sm":"0.5rem"},fontFamily:{"body-md":["Inter"],"headline-lg-mobile":["Plus Jakarta Sans"],"headline-sm":["Plus Jakarta Sans"],"label-lg":["Inter"],"display-lg-mobile":["Plus Jakarta Sans"],"display-lg":["Plus Jakarta Sans"],"label-sm":["Inter"],"headline-lg":["Plus Jakarta Sans"],"stock-counter":["Inter"],"label-md":["Inter"],"headline-md":["Plus Jakarta Sans"],"body-sm":["Inter"],"price-display":["Plus Jakarta Sans"],"body-lg":["Inter"]},fontSize:{"body-md":["14px",{"lineHeight":"22px","fontWeight":"400"}],"headline-lg-mobile":["22px",{"lineHeight":"30px","letterSpacing":"0em","fontWeight":"700"}],"headline-sm":["16px",{"lineHeight":"24px","fontWeight":"700"}],"label-lg":["14px",{"lineHeight":"20px","fontWeight":"600"}],"display-lg-mobile":["30px",{"lineHeight":"38px","letterSpacing":"-0.01em","fontWeight":"800"}],"display-lg":["40px",{"lineHeight":"48px","letterSpacing":"-0.02em","fontWeight":"800"}],"label-sm":["11px",{"lineHeight":"14px","letterSpacing":"0.02em","fontWeight":"600"}],"headline-lg":["28px",{"lineHeight":"36px","letterSpacing":"-0.01em","fontWeight":"700"}],"stock-counter":["18px",{"lineHeight":"24px","letterSpacing":"0.01em","fontWeight":"700"}],"label-md":["12px",{"lineHeight":"16px","fontWeight":"600"}],"headline-md":["20px",{"lineHeight":"28px","fontWeight":"700"}],"body-sm":["12px",{"lineHeight":"18px","fontWeight":"400"}],"price-display":["22px",{"lineHeight":"28px","letterSpacing":"-0.02em","fontWeight":"800"}],"body-lg":["16px",{"lineHeight":"26px","fontWeight":"400"}]}}}}</script></head><body class="bg-surface font-body-md text-body-md text-on-surface antialiased"><header class="fixed top-0 left-0 w-full z-50 bg-surface/95 backdrop-blur-md shadow-[0_4px_20px_-2px_rgba(245,166,35,0.12)]"><div class="bg-secondary text-on-secondary px-4 py-1.5"><div class="max-w-7xl mx-auto flex flex-col md:flex-row items-center justify-between gap-1 text-label-sm font-label-sm"><div class="flex items-center gap-2 text-center md:text-left"><span class="material-symbols-outlined text-secondary-fixed text-sm">local_shipping</span><span>Pengiriman Segar Hari Ini ke Wilayah Kota Agung, Gisting, Talang Padang, Wonosobo, Pringsewu sekitarnya | <strong class="text-secondary-fixed">Gratis Ongkir Min. 2 Karpet/Tray</strong></span></div><a class="flex items-center gap-1.5 hover:text-secondary-fixed transition-colors whitespace-nowrap" href="https://wa.me/6281278900000"><span class="material-symbols-outlined text-sm">chat</span><span>WhatsApp CS Hubungi Bang Zul: 0812-7890-XXXX</span></a></div></div><div class="max-w-7xl mx-auto px-4 lg:px-8 py-3 flex items-center justify-between gap-4"><div class="flex items-center gap-3 shrink-0"><img alt="Logo Bang Zul Egg Market" class="h-8 w-auto object-contain" src="https://lh3.googleusercontent.com/aida/ALJJyrAvuhgJbL1OqXYnorOpflEwk9ch2RB3i3nIpJf2khBHtFUraZYLjA49xnoYr5_XpY1inx_yvUKDG-f5ULodcAC4hoBl9QYWujU07wAAJsvNI88PefRZRNH2SgRzcvtvfP9LlMDgvobQRRrHxWwLlWY8MQoR1CS4kennwXqXJqn5PR3R5zkf-p4q0eleDblVHlCAtE__Wj8FbqU6db9zlBw02jnLdLpow_xGCN8RF4es"/><div class="flex flex-col"><span class="font-headline-md text-headline-md text-primary tracking-tight leading-none">Bang Zul</span><span class="font-label-sm text-label-sm text-secondary font-bold tracking-wider uppercase leading-none mt-0.5">Egg Market Tanggamus</span></div></div><div class="hidden lg:flex items-center gap-1.5 px-3 py-1.5 rounded-full bg-surface-container-low text-on-surface-variant font-label-sm text-label-sm shrink-0"><span class="material-symbols-outlined text-primary text-base">location_on</span><span class="max-w-[210px] truncate">Kab. Tanggamus (Gisting, Kota Agung &amp; Sekitarnya)</span></div><div class="hidden md:flex flex-1 max-w-md mx-2"><div class="relative w-full flex items-center"><span class="material-symbols-outlined absolute left-3 text-outline text-lg">search</span><input class="w-full pl-10 pr-4 py-2 rounded-full bg-surface-container-lowest text-body-sm font-body-sm text-on-surface placeholder:text-outline focus:outline-none focus:ring-2 focus:ring-primary-container shadow-[0_1px_4px_rgba(0,0,0,0.04)]" placeholder="Cari telur ayam ras, telur omega, telur bebek, puyuh..." type="text"/></div></div><div class="hidden xl:flex items-center p-1 rounded-xl bg-surface-container"><nav class="flex items-center gap-1" data-active-classes="bg-surface-container-lowest text-primary shadow-sm font-bold"><a aria-current="page" class="px-3 py-1 rounded-lg transition-all bg-surface-container-lowest text-primary shadow-sm font-bold" data-path="katalog-belanja" href="#">Belanja (Pembeli)</a><a class="px-3 py-1 rounded-lg text-label-sm font-label-sm text-on-surface-variant hover:text-on-surface transition-all" data-path="toko-bang-zul" href="#">Toko Bang Zul (Penjual)</a><a class="px-3 py-1 rounded-lg text-label-sm font-label-sm text-on-surface-variant hover:text-on-surface transition-all" data-path="kurir-tanggamus" href="#">Kurir Tanggamus</a><a class="px-3 py-1 rounded-lg text-label-sm font-label-sm text-on-surface-variant hover:text-on-surface transition-all" data-path="admin-pasar" href="#">Admin</a></nav></div><div class="flex items-center gap-2 md:gap-3 shrink-0"><button aria-label="Notifikasi Pesanan" class="p-2 rounded-full hover:bg-surface-container-high text-on-surface-variant relative" type="button"><span class="material-symbols-outlined text-xl">notifications</span><span class="absolute top-1.5 right-1.5 w-2 h-2 rounded-full bg-error"></span></button><a class="flex items-center gap-2 px-3 py-1.5 rounded-full bg-primary-container text-on-primary-container hover:bg-primary-fixed-dim transition-colors shadow-sm" data-path="keranjang-belanja" href="#"><span class="material-symbols-outlined text-lg">shopping_basket</span><span class="hidden sm:inline font-label-sm text-label-sm">Rp 84.000 (3 item)</span></a><div class="flex items-center gap-2 pl-1"><img alt="Profile" class="w-8 h-8 rounded-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBu4cCay1o-kcZkrepBjdwRhNkTeb5NSNF4V20H1AoEXr4ahIrRP9SktX37TUve3u7us_GHnlm1279EoAyYcFxqZTZV4CIOdstOTCqIMcitiPTCwpWm4m2okjdh9z8S2I2n0sK1hb3y3ohWU84Tu6ZWNoxKL7D1NVLhMsBA3C6eHNQmukclnmKpMzHXssx-xtkh1wF2y2OFEDgXUgTPjjAfLabaOsUrz91MId6by4k"/><span class="hidden 2xl:inline font-label-sm text-label-sm text-on-surface font-semibold">Bang Zul</span></div></div></div><div class="bg-surface-container-lowest shadow-[0_1px_4px_rgba(0,0,0,0.02)] overflow-x-auto"><div class="max-w-7xl mx-auto px-4 lg:px-8"><nav class="flex items-center gap-6 whitespace-nowrap py-2.5 text-label-sm font-label-sm" data-active-classes="text-primary font-bold border-b-2 border-primary"><a aria-current="page" class="transition-colors pb-1 text-primary font-bold border-b-2 border-primary" data-path="katalog-belanja" href="#">Semua Produk</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="telur-ayam-ras" href="#">Telur Ayam Ras (Kiloan &amp; Karpet)</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="telur-ayam-kampung-omega" href="#">Telur Ayam Kampung &amp; Omega</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="telur-bebek-asin-mentah" href="#">Telur Bebek Asin &amp; Mentah</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="telur-puyuh" href="#">Telur Puyuh</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="paket-grosir-rumah-makan" href="#">Paket Grosir &amp; Rumah Makan</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1 flex items-center gap-1.5" data-path="jadwal-panen-stok" href="#"><span class="w-2 h-2 rounded-full bg-secondary inline-block animate-pulse"></span>Jadwal Panen &amp; Stok Realtime</a></nav></div></div></header><main class="w-full pt-36 bg-surface min-h-screen"><div class="flex flex-col w-full">
<!-- Top Notification & Tanggamus Market Realtime Ticker -->
<section class="w-full bg-surface-container-low py-3 px-4 lg:px-8">
<div class="max-w-7xl mx-auto flex flex-col lg:flex-row items-center justify-between gap-3">
<div class="flex flex-wrap items-center gap-2">
<span class="inline-flex items-center gap-1.5 px-2.5 py-1 rounded-full bg-secondary-container text-on-secondary-container font-label-sm text-label-sm">
<span class="w-2 h-2 rounded-full bg-secondary inline-block animate-ping"></span>
          Harga Resmi Pasar Tanggamus Hari Ini
        </span>
<div class="flex items-center gap-3 overflow-x-auto text-body-sm font-body-sm text-on-surface-variant py-0.5">
<span class="whitespace-nowrap font-medium text-on-surface">Telur Ras: <strong class="text-primary font-headline-sm text-headline-sm">Rp 27.500</strong>/kg</span>
<span class="text-outline-variant">•</span>
<span class="whitespace-nowrap font-medium text-on-surface">1 Karpet (30 butir): <strong class="text-primary font-headline-sm text-headline-sm">Rp 52.000</strong></span>
<span class="text-outline-variant">•</span>
<span class="whitespace-nowrap font-medium text-on-surface">Telur Bebek Tambak: <strong class="text-primary font-headline-sm text-headline-sm">Rp 3.200</strong>/btr</span>
</div>
</div>
<div class="flex items-center gap-2 w-full lg:w-auto justify-end">
<span class="material-symbols-outlined text-secondary text-sm">schedule</span>
<span class="text-label-sm font-label-sm text-on-surface-variant">Update Panen: <strong>Pukul 06.15 WIB (Kandang Talang Padang)</strong></span>
</div>
</div>
</section>
<!-- Hero Visual & Guarantee Spotlight Section -->
<section class="w-full max-w-7xl mx-auto px-4 lg:px-8 py-8">
<div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-stretch">
<!-- Left Editorial Storytelling Card -->
<div class="lg:col-span-7 flex flex-col justify-between p-8 rounded-xl bg-surface-container-lowest shadow-md relative overflow-hidden">
<div class="absolute -right-16 -top-16 w-64 h-64 rounded-full bg-primary-fixed/25 pointer-events-none blur-3xl"></div>
<div class="space-y-4 relative z-10">
<div class="flex flex-wrap items-center gap-2">
<span class="px-3 py-1 rounded-full bg-primary-fixed text-on-primary-fixed font-label-sm text-label-sm font-bold flex items-center gap-1">
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">eco</span>
              Hasil Peternak Lokal Tanggamus
            </span>
<span class="px-3 py-1 rounded-full bg-secondary-container text-on-secondary-container font-label-sm text-label-sm flex items-center gap-1">
<span class="material-symbols-outlined text-sm">verified</span>
              100% Cangkang Bersih &amp; Utuh
            </span>
</div>
<h1 class="font-display-lg text-display-lg text-on-surface tracking-tight leading-tight">
            Telur Segar dari Peternakan Tanggamus, <span class="text-primary">Pagi Panen Siang Sampai!</span>
</h1>
<p class="font-body-lg text-body-lg text-on-surface-variant max-w-xl">
            "Kami sortir langsung dari kandang mitra di Talang Padang, Gisting, dan Wonosobo. Bebas bau apek, kuning telur oranye kental bergizi tinggi, dengan timbangan digital jujur tanpa kurang sebutir pun."
          </p>
<!-- Bang Zul Guarantee Badge -->
<div class="p-4 rounded-xl bg-surface-container-low flex flex-col sm:flex-row items-start sm:items-center justify-between gap-3">
<div class="flex items-center gap-3">
<div class="w-10 h-10 rounded-full bg-primary-container text-on-primary-container flex items-center justify-center shrink-0">
<span class="material-symbols-outlined">shield_with_heart</span>
</div>
<div>
<p class="font-headline-sm text-headline-sm text-on-surface">Garansi 100% Ganti Telur Pecah</p>
<p class="font-body-sm text-body-sm text-on-surface-variant">Pecah di jalan? Kurir ganti langsung atau saldo kembali utuh saat itu juga.</p>
</div>
</div>
<span class="inline-flex px-3 py-1 rounded-full bg-surface-container-lowest text-secondary font-label-sm text-label-sm font-bold shadow-sm whitespace-nowrap">
              Jaminan Bang Zul
            </span>
</div>
<!-- Feature Chips -->
<div class="grid grid-cols-2 sm:grid-cols-3 gap-3 pt-2">
<div class="p-3 rounded-lg bg-surface-container flex items-center gap-2">
<span class="material-symbols-outlined text-primary text-base">alarm_on</span>
<span class="font-label-md text-label-md text-on-surface">Panen Subuh Tadi</span>
</div>
<div class="p-3 rounded-lg bg-surface-container flex items-center gap-2">
<span class="material-symbols-outlined text-secondary text-base">health_and_safety</span>
<span class="font-label-md text-label-md text-on-surface">Bebas Antibiotik</span>
</div>
<div class="p-3 rounded-lg bg-surface-container flex items-center gap-2 col-span-2 sm:col-span-1">
<span class="material-symbols-outlined text-primary text-base">handshake</span>
<span class="font-label-md text-label-md text-on-surface">Bisa Bayar COD</span>
</div>
</div>
</div>
<!-- Quick CTA strip -->
<div class="pt-6 mt-6 flex flex-wrap items-center justify-between gap-4">
<div class="flex items-center gap-2">
<div class="flex -space-x-2">
<span class="w-8 h-8 rounded-full bg-secondary-fixed text-on-secondary-fixed flex items-center justify-center font-label-sm text-label-sm font-bold shadow-sm">GT</span>
<span class="w-8 h-8 rounded-full bg-primary-fixed text-on-primary-fixed flex items-center justify-center font-label-sm text-label-sm font-bold shadow-sm">KA</span>
<span class="w-8 h-8 rounded-full bg-tertiary-fixed text-on-tertiary-fixed flex items-center justify-center font-label-sm text-label-sm font-bold shadow-sm">TP</span>
</div>
<span class="font-body-sm text-body-sm text-on-surface-variant font-medium">Melayani 6 Kecamatan di Kab. Tanggamus</span>
</div>
<a class="px-5 py-2.5 rounded-full bg-primary-container text-on-primary-container font-label-lg text-label-lg font-bold hover:bg-primary-fixed-dim transition-all shadow-sm flex items-center gap-2" href="#katalog-produk">
<span>Pilih Telur Segar</span>
<span class="material-symbols-outlined text-base">arrow_downward</span>
</a>
</div>
</div>
<!-- Right Bento Visual Grid showcasing eggs in trays & nest -->
<div class="lg:col-span-5 grid grid-rows-2 gap-4">
<!-- Top Visual: Fresh Eggs in Traditional Tray Stack -->
<div class="relative rounded-xl overflow-hidden shadow-md group h-56 lg:h-auto">
<img alt="Telur ayam ras segar tersusun rapi di atas rak kayu pasar Tanggamus Lampung" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDsf2bARQyODKYx9i9iUVzMjXsL5YsDsqkCeFulA7kCQ8T-AvsUHfuV9ezMI6irF1B4qEZpgboxINK5ydCTN14dG7nyBnVBi8i_yvBp9W4k2G_76qGT0tNNIl1nmm2phddXvC0v_qRMqpHUMk0WvA2d_D0PiETltkcjnWoTw5KbGi_ycn7uGjDmE3HG1U8BaErLKrAckCrsk1IEyMPk20e5SbWKDvEm1Lj2ynLsVLw"/>
<div class="absolute inset-0 bg-gradient-to-t from-on-background/80 via-transparent to-transparent"></div>
<div class="absolute bottom-4 left-4 right-4 flex items-end justify-between">
<div class="text-surface">
<span class="inline-block px-2 py-0.5 rounded bg-primary-container text-on-primary-container font-label-sm text-label-sm font-bold uppercase tracking-wider mb-1">Stok Pagi Tersedia</span>
<h2 class="font-headline-sm text-headline-sm font-bold">Telur Ayam Ras Grade A</h2>
<p class="font-body-sm text-body-sm text-surface-container-high opacity-90">Karton tray kokoh, aman bawa motor berlubang</p>
</div>
<span class="px-3 py-1 rounded-full bg-surface-container-lowest text-on-surface font-price-display text-headline-sm shadow">
              Rp 52.000<span class="text-body-sm font-normal text-on-surface-variant">/tray</span>
</span>
</div>
</div>
<!-- Bottom Visual: Kampung & Duck Eggs in Country Basket -->
<div class="relative rounded-xl overflow-hidden shadow-md group h-56 lg:h-auto">
<img alt="Telur ayam kampung organik dalam anyaman bambu pedesaan Lampung" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" src="https://lh3.googleusercontent.com/aida-public/AB6AXuApm5RciuWJtQQo-QKC3WZgjodh0H08MR2Tgr493z9akwfCmyvULVprFsWIqJuKLp2L-ldUGURQ9r6lj7vXc9Ad5Um__b_Mi-cO_wX4FFqc51yRS3lcyJ5OnaBUbMCJrGOXvM9ZGiSZWd0IbZE4veI24UGVyFF6Tg2KtSRrsc2xOMwgvRs8ytzbxxs5qYP7lXBvk-DZXOv5lgnw_gE4PFt_DoVb-ga6BBs1GVdqqWI"/>
<div class="absolute inset-0 bg-gradient-to-t from-on-background/80 via-transparent to-transparent"></div>
<div class="absolute bottom-4 left-4 right-4 flex items-end justify-between">
<div class="text-surface">
<span class="inline-block px-2 py-0.5 rounded bg-secondary-fixed text-on-secondary-fixed font-label-sm text-label-sm font-bold uppercase tracking-wider mb-1">Pilihan Ibu Rumah Tangga</span>
<h2 class="font-headline-sm text-headline-sm font-bold">Telur Ayam Kampung &amp; Omega</h2>
<p class="font-body-sm text-body-sm text-surface-container-high opacity-90">Kuning pekat alami, pakan jagung giling lokal</p>
</div>
<span class="px-3 py-1 rounded-full bg-surface-container-lowest text-on-surface font-price-display text-headline-sm shadow">
              Rp 38.000<span class="text-body-sm font-normal text-on-surface-variant">/pack</span>
</span>
</div>
</div>
</div>
</div>
</section>
<!-- District Delivery Selector & Interactive Bar -->
<section class="w-full max-w-7xl mx-auto px-4 lg:px-8 py-2">
<div class="p-4 rounded-xl bg-surface-container-lowest shadow-sm flex flex-col md:flex-row items-center justify-between gap-4">
<div class="flex items-center gap-3 w-full md:w-auto">
<div class="w-10 h-10 rounded-full bg-secondary-container text-on-secondary-container flex items-center justify-center shrink-0">
<span class="material-symbols-outlined">two_wheeler</span>
</div>
<div>
<span class="font-label-sm text-label-sm text-on-surface-variant block">Lokasi Pengantaran Telur Anda:</span>
<div class="flex items-center gap-1 font-headline-sm text-headline-sm text-on-surface">
<span>Kecamatan</span>
<select class="bg-surface-container-low text-primary font-bold px-2 py-0.5 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary-container cursor-pointer text-headline-sm" id="kecamatan-selector">
<option selected="" value="Gisting">Gisting (Gratis Ongkir min 2 tray)</option>
<option value="Talang Padang">Talang Padang</option>
<option value="Kota Agung Timur">Kota Agung Timur</option>
<option value="Kota Agung Pusat">Kota Agung Pusat</option>
<option value="Sumberejo">Sumberejo</option>
<option value="Pugung">Pugung</option>
<option value="Wonosobo">Wonosobo</option>
</select>
</div>
</div>
</div>
<div class="flex flex-wrap items-center gap-4 text-body-sm font-body-sm text-on-surface-variant">
<div class="flex items-center gap-1.5">
<span class="material-symbols-outlined text-secondary text-base">multiple_airports</span>
<span>Jadwal Antar Terdekat: <strong>11.30 WIB Siang Ini</strong></span>
</div>
<div class="hidden sm:block text-outline-variant">•</div>
<div class="flex items-center gap-1.5">
<span class="material-symbols-outlined text-primary text-base">scale</span>
<span>Timbangan Presisi di Tempat</span>
</div>
</div>
</div>
</section>
<!-- Product Catalog Section with Sticky Cart Layout -->
<section class="w-full max-w-7xl mx-auto px-4 lg:px-8 py-8" id="katalog-produk">
<!-- Category Tabs Filter -->
<div class="flex flex-col sm:flex-row items-start sm:items-center justify-between gap-4 mb-6">
<div>
<h2 class="font-headline-lg text-headline-lg text-on-surface tracking-tight">Katalog Telur Segar Pilihan</h2>
<p class="font-body-md text-body-md text-on-surface-variant">Pilih varian telur segar langsung dari peternak terpercaya UD. Bang Zul Tanggamus</p>
</div>
<!-- Quick category pills -->
<div class="flex items-center gap-2 overflow-x-auto w-full sm:w-auto pb-2 sm:pb-0">
<button class="category-btn active px-3.5 py-1.5 rounded-full bg-primary text-on-primary font-label-sm text-label-sm whitespace-nowrap shadow-sm" type="button">Semua Telur</button>
<button class="category-btn px-3.5 py-1.5 rounded-full bg-surface-container-low text-on-surface-variant hover:text-on-surface font-label-sm text-label-sm whitespace-nowrap" type="button">Telur Ayam Ras</button>
<button class="category-btn px-3.5 py-1.5 rounded-full bg-surface-container-low text-on-surface-variant hover:text-on-surface font-label-sm text-label-sm whitespace-nowrap" type="button">Kampung &amp; Omega</button>
<button class="category-btn px-3.5 py-1.5 rounded-full bg-surface-container-low text-on-surface-variant hover:text-on-surface font-label-sm text-label-sm whitespace-nowrap" type="button">Telur Bebek</button>
<button class="category-btn px-3.5 py-1.5 rounded-full bg-surface-container-low text-on-surface-variant hover:text-on-surface font-label-sm text-label-sm whitespace-nowrap" type="button">Telur Puyuh</button>
<button class="category-btn px-3.5 py-1.5 rounded-full bg-surface-container-low text-on-surface-variant hover:text-on-surface font-label-sm text-label-sm whitespace-nowrap" type="button">Grosir Usaha</button>
</div>
</div>
<!-- Main Catalog Grid + Sticky Cart Sidebar Container -->
<div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-start">
<!-- 6-Product Cards Grid (lg:col-span-8) -->
<div class="lg:col-span-8 grid grid-cols-1 sm:grid-cols-2 gap-6">
<!-- Product 1: Telur Ayam Ras Karpet 30 Butir -->
<article class="flex flex-col justify-between rounded-xl bg-surface-container-lowest p-4 shadow-md transition-all duration-300 hover:shadow-xl relative overflow-hidden group">
<div class="relative w-full h-48 rounded-lg overflow-hidden mb-3 bg-surface-container">
<img alt="Satu karpet telur ayam ras cokelat bersih 30 butir tersusun rapi di wadah karton tebal" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" src="https://lh3.googleusercontent.com/aida-public/AB6AXuB6SLp12H_5U_c2wY4U4HzTb8_I1h2GjYt_5oahWtiAisy6xauWdZWNMRsst2MoQv_nmXZuK_ZxxxITAT0rMm_0j6vycqZmJd5TzzTpzD6SUCFntgcSQp89ppm6tSlUK3SlYWPmD14kjMBYQ_o5mqvCxoU8pHDLlpnZ0g19wk1SIaLHr6PP5_mO1zu0LYGdBcAGA88PK2L0TdJctx8aIOt-RF4nP3FDoiOyeffVrbA"/>
<span class="absolute top-2 left-2 px-2.5 py-0.5 rounded-full bg-primary-container text-on-primary-container font-label-sm text-label-sm font-bold shadow-sm">
              Grade A Super
            </span>
<span class="absolute bottom-2 left-2 px-2.5 py-0.5 rounded bg-surface/90 backdrop-blur text-secondary font-label-sm text-label-sm font-bold flex items-center gap-1 shadow-sm">
<span class="w-1.5 h-1.5 rounded-full bg-secondary"></span> Stok: 145 Karpet
            </span>
</div>
<div class="space-y-1.5 flex-1">
<div class="flex items-center justify-between text-body-sm font-body-sm text-on-surface-variant">
<span>Kemasan Karpet Tray</span>
<span>30 Butir (±1,85 Kg)</span>
</div>
<h3 class="font-headline-md text-headline-md text-on-surface group-hover:text-primary transition-colors">
              Telur Ayam Ras Segar Super (Karpet 30 Butir)
            </h3>
<p class="font-body-sm text-body-sm text-on-surface-variant line-clamp-2">
              Cangkang tebal warna cokelat tua alami. Kulit bersih tidak berbau, kuning telur menonjol segar panen pagi kandang Gisting.
            </p>
</div>
<div class="pt-4 mt-3 border-t-0 space-y-3">
<div class="flex items-baseline justify-between">
<div>
<span class="font-body-sm text-body-sm text-on-surface-variant block">Harga Spesial</span>
<span class="font-price-display text-price-display text-primary">Rp 52.000</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">/karpet</span>
</div>
<span class="text-label-sm font-label-sm text-secondary bg-secondary-container px-2 py-0.5 rounded">
                Hemat Rp 3.000
              </span>
</div>
<div class="grid grid-cols-2 gap-2">
<button class="w-full py-2.5 rounded-lg bg-surface-container text-on-surface hover:bg-surface-container-high transition-colors font-label-md text-label-md flex items-center justify-center gap-1" onclick="addToCart('Telur Ayam Ras (Karpet)', 52000, 1)" type="button">
<span class="material-symbols-outlined text-sm">add_shopping_cart</span>
<span>+ Keranjang</span>
</button>
<button class="w-full py-2.5 rounded-lg bg-primary-container text-on-primary-container hover:bg-primary-fixed-dim transition-colors font-label-md text-label-md font-bold flex items-center justify-center gap-1 shadow-sm" onclick="buyNow('Telur Ayam Ras (Karpet)', 52000)" type="button">
<span>Beli Langsung</span>
</button>
</div>
</div>
</article>
<!-- Product 2: Telur Ayam Kampung Asli & Omega-3 -->
<article class="flex flex-col justify-between rounded-xl bg-surface-container-lowest p-4 shadow-md transition-all duration-300 hover:shadow-xl relative overflow-hidden group">
<div class="relative w-full h-48 rounded-lg overflow-hidden mb-3 bg-surface-container">
<img alt="Telur ayam kampung asli di wadah jerami dan sendok kayu alami" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDq79z60HihvTkEQiRPxJkvbwtIplGsgc_2L1Tp59AjwE8GVw4bHAqnF1xpKPXvlOsscGostTcjV3HC-i7Kav9vmpGZZfqUBsUMbOb4NAXCdJJKY6p89H4ka2em31xFVcxyNLoB53rOPmpc2pB3emRmVv0_ef0ZwejKvd7UZfrNSvz9by13uXlWyhsdNzh42wzxDhkA0HT-3Tcoj4aEipOHZfXjfKVFGe5zUHn-vxY"/>
<span class="absolute top-2 left-2 px-2.5 py-0.5 rounded-full bg-secondary text-on-secondary font-label-sm text-label-sm font-bold shadow-sm">
              Paling Laris 🔥
            </span>
<span class="absolute bottom-2 left-2 px-2.5 py-0.5 rounded bg-surface/90 backdrop-blur text-secondary font-label-sm text-label-sm font-bold flex items-center gap-1 shadow-sm">
<span class="w-1.5 h-1.5 rounded-full bg-secondary"></span> Stok: 82 Mika
            </span>
</div>
<div class="space-y-1.5 flex-1">
<div class="flex items-center justify-between text-body-sm font-body-sm text-on-surface-variant">
<span>Mika Tebal Food-grade</span>
<span>10 Butir Pilihan</span>
</div>
<h3 class="font-headline-md text-headline-md text-on-surface group-hover:text-primary transition-colors">
              Telur Ayam Kampung Asli &amp; Omega-3
            </h3>
<p class="font-body-sm text-body-sm text-on-surface-variant line-clamp-2">
              Kaya Omega-3 &amp; DHA alami tanpa suntik kimia. Kuning oranye kemerahan padat, sangat bagus untuk jamu &amp; MPASI balita.
            </p>
</div>
<div class="pt-4 mt-3 space-y-3">
<div class="flex items-baseline justify-between">
<div>
<span class="font-body-sm text-body-sm text-on-surface-variant block">Harga Pack</span>
<span class="font-price-display text-price-display text-primary">Rp 38.000</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">/mika (10 butir)</span>
</div>
<span class="text-label-sm font-label-sm text-primary font-bold">
                Asli Desa Sumberejo
              </span>
</div>
<div class="grid grid-cols-2 gap-2">
<button class="w-full py-2.5 rounded-lg bg-surface-container text-on-surface hover:bg-surface-container-high transition-colors font-label-md text-label-md flex items-center justify-center gap-1" onclick="addToCart('Telur Ayam Kampung &amp; Omega-3 (10 btr)', 38000, 1)" type="button">
<span class="material-symbols-outlined text-sm">add_shopping_cart</span>
<span>+ Keranjang</span>
</button>
<button class="w-full py-2.5 rounded-lg bg-primary-container text-on-primary-container hover:bg-primary-fixed-dim transition-colors font-label-md text-label-md font-bold flex items-center justify-center gap-1 shadow-sm" onclick="buyNow('Telur Ayam Kampung &amp; Omega-3 (10 btr)', 38000)" type="button">
<span>Beli Langsung</span>
</button>
</div>
</div>
</article>
<!-- Product 3: Telur Bebek Tambak Segar / Asin Mentah -->
<article class="flex flex-col justify-between rounded-xl bg-surface-container-lowest p-4 shadow-md transition-all duration-300 hover:shadow-xl relative overflow-hidden group">
<div class="relative w-full h-48 rounded-lg overflow-hidden mb-3 bg-surface-container">
<img alt="Telur bebek tambak cangkang biru muda dan telur puyuh segar dalam wadah kayu desa" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" src="https://lh3.googleusercontent.com/aida-public/AB6AXuC2veu9_5D3yQDVz6PV9PwtaW8kkFE5Z-Qe2sSnuDTLf3qevw5TN_67_Dqd7YYPAyFm4uL8ovqvSK6MFHwreMGajOXHcbzerrHj0PyBQzwBjrvYi97-cnAUWFXnesPNGQ6QfzUfSO6VGOB2K_AtFznDEHyk3Ij5Klvs8lVT5wHp270kVVV6XLuBSdNYDkmLtHffkBn7ViCd6tImSons2dpUnYXJP8zTasaMLkm0R04"/>
<span class="absolute top-2 left-2 px-2.5 py-0.5 rounded-full bg-primary-fixed text-on-primary-fixed font-label-sm text-label-sm font-bold shadow-sm">
              Kuning Berminyak
            </span>
<span class="absolute bottom-2 left-2 px-2.5 py-0.5 rounded bg-surface/90 backdrop-blur text-secondary font-label-sm text-label-sm font-bold flex items-center gap-1 shadow-sm">
<span class="w-1.5 h-1.5 rounded-full bg-secondary"></span> Sisa Stok: 60 Pack
            </span>
</div>
<div class="space-y-1.5 flex-1">
<div class="flex items-center justify-between text-body-sm font-body-sm text-on-surface-variant">
<span>Kemasan Mika Karton</span>
<span>10 Butir Telur Bebek</span>
</div>
<h3 class="font-headline-md text-headline-md text-on-surface group-hover:text-primary transition-colors">
              Telur Bebek Tambak Segar / Asin Mentah
            </h3>
<p class="font-body-sm text-body-sm text-on-surface-variant line-clamp-2">
              Hasil bebek gembala pesisir Kota Agung. Cangkang biru mulus kebiruan, putih padat, kuning berminyak gurih untuk martabak/telur asin.
            </p>
</div>
<div class="pt-4 mt-3 space-y-3">
<div class="flex items-baseline justify-between">
<div>
<span class="font-body-sm text-body-sm text-on-surface-variant block">Harga</span>
<span class="font-price-display text-price-display text-primary">Rp 32.000</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">/pack (10 btr)</span>
</div>
<span class="text-label-sm font-label-sm text-on-surface-variant">
                Rp 3.200 / butir
              </span>
</div>
<div class="grid grid-cols-2 gap-2">
<button class="w-full py-2.5 rounded-lg bg-surface-container text-on-surface hover:bg-surface-container-high transition-colors font-label-md text-label-md flex items-center justify-center gap-1" onclick="addToCart('Telur Bebek Tambak Segar (10 btr)', 32000, 1)" type="button">
<span class="material-symbols-outlined text-sm">add_shopping_cart</span>
<span>+ Keranjang</span>
</button>
<button class="w-full py-2.5 rounded-lg bg-primary-container text-on-primary-container hover:bg-primary-fixed-dim transition-colors font-label-md text-label-md font-bold flex items-center justify-center gap-1 shadow-sm" onclick="buyNow('Telur Bebek Tambak Segar (10 btr)', 32000)" type="button">
<span>Beli Langsung</span>
</button>
</div>
</div>
</article>
<!-- Product 4: Telur Ayam Ras Kiloan Pilihan -->
<article class="flex flex-col justify-between rounded-xl bg-surface-container-lowest p-4 shadow-md transition-all duration-300 hover:shadow-xl relative overflow-hidden group">
<div class="relative w-full h-48 rounded-lg overflow-hidden mb-3 bg-surface-container">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" data-alt="Timbangan digital gantung dan mangkuk anyaman bambu berisi telur ayam ras timbangan kiloan segar di pasar tradisional Tanggamus Lampung dengan pencahayaan hangat alami" src="https://lh3.googleusercontent.com/aida-public/AB6AXuA4KLllaWhphf1p7yP7m1u1O59j3woV_GR07_vQyaVtjT5JmgHAtQaxNzuPD4F7ghqHw5J_-xMfGO_msJvKLQiiGNSl5eFSghOd1_JWLlaeJ1-D8WDK3WlmoWDvDy9--qAPR1Om1JZfh5YQochzwsHT1hsSQ_Xq1BpmYAouQFD7sV7BGHuYZqMim-kyQEPMesDw4KhJQ3AxGvYh2eBDR-QhzKWTBycNBQXfel_Sqek"/>
<span class="absolute top-2 left-2 px-2.5 py-0.5 rounded-full bg-surface-container-highest text-on-surface font-label-sm text-label-sm font-bold shadow-sm">
              Timbangan Presisi
            </span>
<span class="absolute bottom-2 left-2 px-2.5 py-0.5 rounded bg-surface/90 backdrop-blur text-secondary font-label-sm text-label-sm font-bold flex items-center gap-1 shadow-sm">
<span class="w-1.5 h-1.5 rounded-full bg-secondary"></span> Stok: 280 Kg
            </span>
</div>
<div class="space-y-1.5 flex-1">
<div class="flex items-center justify-between text-body-sm font-body-sm text-on-surface-variant">
<span>Plastik Tali &amp; Sekat Pelindung</span>
<span>16-17 Butir / Kg</span>
</div>
<h3 class="font-headline-md text-headline-md text-on-surface group-hover:text-primary transition-colors">
              Telur Ayam Ras Kiloan Pilihan
            </h3>
<p class="font-body-sm text-body-sm text-on-surface-variant line-clamp-2">
              Cocok untuk kebutuhan masak harian keluarga. Bebas pilih timbangan pas, sortir manual agar tidak ada telur retak mikro.
            </p>
</div>
<div class="pt-4 mt-3 space-y-3">
<div class="flex items-baseline justify-between">
<div>
<span class="font-body-sm text-body-sm text-on-surface-variant block">Harga Harian</span>
<span class="font-price-display text-price-display text-primary">Rp 27.500</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">/kg</span>
</div>
<span class="text-label-sm font-label-sm text-secondary bg-secondary-container px-2 py-0.5 rounded font-bold">
                Min. 1 Kg
              </span>
</div>
<div class="grid grid-cols-2 gap-2">
<button class="w-full py-2.5 rounded-lg bg-surface-container text-on-surface hover:bg-surface-container-high transition-colors font-label-md text-label-md flex items-center justify-center gap-1" onclick="addToCart('Telur Ayam Ras Kiloan (1 Kg)', 27500, 1)" type="button">
<span class="material-symbols-outlined text-sm">add_shopping_cart</span>
<span>+ Keranjang</span>
</button>
<button class="w-full py-2.5 rounded-lg bg-primary-container text-on-primary-container hover:bg-primary-fixed-dim transition-colors font-label-md text-label-md font-bold flex items-center justify-center gap-1 shadow-sm" onclick="buyNow('Telur Ayam Ras Kiloan (1 Kg)', 27500)" type="button">
<span>Beli Langsung</span>
</button>
</div>
</div>
</article>
<!-- Product 5: Telur Puyuh Segar Peternak Tanggamus -->
<article class="flex flex-col justify-between rounded-xl bg-surface-container-lowest p-4 shadow-md transition-all duration-300 hover:shadow-xl relative overflow-hidden group">
<div class="relative w-full h-48 rounded-lg overflow-hidden mb-3 bg-surface-container">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" data-alt="Telur puyuh segar bertutul hitam kecokelatan dalam wadah mika transparan rapi beralaskan jerami kering khas peternakan desa Gisting Tanggamus" src="https://lh3.googleusercontent.com/aida-public/AB6AXuB9zsA1SYge0k_HWuLZQe-ai4_wcfyZGrVinJbXkz5wYVCGrs_NCNxGfB7zU-1LT8qB14WmVnFPadPEkqQC63gCMqiACY2hdmd6N9tu7M7TBoP8Qx7GeqfVVKcZBQUNvWYy9W-ImGJx6GLirUI8fZcjddByCzBK1TjmEQAy7oVgnnw6w_vLOZ6QdQR87ue_YPRMUam5oE7ol-t_vOc8b9ZpsVV6G6BkI0HPJluv2nI"/>
<span class="absolute top-2 left-2 px-2.5 py-0.5 rounded-full bg-secondary-container text-on-secondary-container font-label-sm text-label-sm font-bold shadow-sm">
              Favorit Anak-anak
            </span>
<span class="absolute bottom-2 left-2 px-2.5 py-0.5 rounded bg-surface/90 backdrop-blur text-secondary font-label-sm text-label-sm font-bold flex items-center gap-1 shadow-sm">
<span class="w-1.5 h-1.5 rounded-full bg-secondary"></span> Stok: 95 Mika
            </span>
</div>
<div class="space-y-1.5 flex-1">
<div class="flex items-center justify-between text-body-sm font-body-sm text-on-surface-variant">
<span>Mika Khusus Telur Puyuh</span>
<span>Isi 50 Butir</span>
</div>
<h3 class="font-headline-md text-headline-md text-on-surface group-hover:text-primary transition-colors">
              Telur Puyuh Segar Peternak Tanggamus (50 Btr)
            </h3>
<p class="font-body-sm text-body-sm text-on-surface-variant line-clamp-2">
              Panen harian dari peternak puyuh Wonosobo. Kulit tebal, tidak amis, sangat lezat untuk sate telur puyuh, sup, dan bekal sekolah.
            </p>
</div>
<div class="pt-4 mt-3 space-y-3">
<div class="flex items-baseline justify-between">
<div>
<span class="font-body-sm text-body-sm text-on-surface-variant block">Harga Mika</span>
<span class="font-price-display text-price-display text-primary">Rp 22.000</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">/mika (50 btr)</span>
</div>
<span class="text-label-sm font-label-sm text-on-surface-variant">
                Rp 440 / btr
              </span>
</div>
<div class="grid grid-cols-2 gap-2">
<button class="w-full py-2.5 rounded-lg bg-surface-container text-on-surface hover:bg-surface-container-high transition-colors font-label-md text-label-md flex items-center justify-center gap-1" onclick="addToCart('Telur Puyuh Segar (50 butir)', 22000, 1)" type="button">
<span class="material-symbols-outlined text-sm">add_shopping_cart</span>
<span>+ Keranjang</span>
</button>
<button class="w-full py-2.5 rounded-lg bg-primary-container text-on-primary-container hover:bg-primary-fixed-dim transition-colors font-label-md text-label-md font-bold flex items-center justify-center gap-1 shadow-sm" onclick="buyNow('Telur Puyuh Segar (50 butir)', 22000)" type="button">
<span>Beli Langsung</span>
</button>
</div>
</div>
</article>
<!-- Product 6: Paket Grosir Martabak & Katering -->
<article class="flex flex-col justify-between rounded-xl bg-surface-container-lowest p-4 shadow-md transition-all duration-300 hover:shadow-xl relative overflow-hidden group">
<div class="relative w-full h-48 rounded-lg overflow-hidden mb-3 bg-surface-container">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" data-alt="Tumpukan lima karpet telur ayam dan bebek siap kirim diangkut motor pedagang keliling dengan latar pedesaan asri Tanggamus Lampung" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAsVV5_CxP0pG1Yjp0UFUMUeWnfkgaMxwr7Vhs6-ZXy3IAO4if20n34RkMuAyNxpSAmw7cipDoORcikUkuXa7HDSY-Qms_fDBUDRAiRvPQRQTUViOXCYpUS763yjUvPsJ0ryU7arPiqNbdgo9tGbSidUwyRXQNaE6kjt50bcBuNeRbGwMCaoW4zSLLKQncujRy39yrRUcLqT9XGcK2aVHGhpqZOvZSC8mnk6fdLuJc"/>
<span class="absolute top-2 left-2 px-2.5 py-0.5 rounded-full bg-primary-container text-on-primary-container font-label-sm text-label-sm font-bold shadow-sm">
              Paket Usaha Hemat
            </span>
<span class="absolute bottom-2 left-2 px-2.5 py-0.5 rounded bg-surface/90 backdrop-blur text-secondary font-label-sm text-label-sm font-bold flex items-center gap-1 shadow-sm">
<span class="w-1.5 h-1.5 rounded-full bg-secondary"></span> Siap Kirim Usaha
            </span>
</div>
<div class="space-y-1.5 flex-1">
<div class="flex items-center justify-between text-body-sm font-body-sm text-on-surface-variant">
<span>Bundling 5 Karpet</span>
<span>150 Butir Utuh Terikat</span>
</div>
<h3 class="font-headline-md text-headline-md text-on-surface group-hover:text-primary transition-colors">
              Paket Grosir Martabak &amp; Katering (5 Karpet)
            </h3>
<p class="font-body-sm text-body-sm text-on-surface-variant line-clamp-2">
              Khusus pengusaha kuliner di Gisting, Talang Padang &amp; Kota Agung. Diantar berkala subuh/sore langsung ke dapur usaha Anda.
            </p>
</div>
<div class="pt-4 mt-3 space-y-3">
<div class="flex items-baseline justify-between">
<div>
<span class="font-body-sm text-body-sm text-on-surface-variant block">Harga Grosir</span>
<span class="font-price-display text-price-display text-primary">Rp 250.000</span>
<span class="font-label-sm text-label-sm text-outline line-through ml-1">Rp 260.000</span>
</div>
<span class="text-label-sm font-label-sm text-secondary bg-secondary-container px-2 py-0.5 rounded font-bold">
                Hemat Rp 10.000
              </span>
</div>
<div class="grid grid-cols-2 gap-2">
<button class="w-full py-2.5 rounded-lg bg-surface-container text-on-surface hover:bg-surface-container-high transition-colors font-label-md text-label-md flex items-center justify-center gap-1" onclick="addToCart('Paket Grosir Katering (5 Karpet)', 250000, 1)" type="button">
<span class="material-symbols-outlined text-sm">add_shopping_cart</span>
<span>+ Keranjang</span>
</button>
<button class="w-full py-2.5 rounded-lg bg-primary-container text-on-primary-container hover:bg-primary-fixed-dim transition-colors font-label-md text-label-md font-bold flex items-center justify-center gap-1 shadow-sm" onclick="buyNow('Paket Grosir Katering (5 Karpet)', 250000)" type="button">
<span>Beli Langsung</span>
</button>
</div>
</div>
</article>
</div>
<!-- Right Column: Interactive Sticky Cart Preview & Local Checkout Summary (lg:col-span-4) -->
<aside class="lg:col-span-4 sticky top-40 space-y-4">
<div class="rounded-xl bg-surface-container-lowest p-6 shadow-md relative overflow-hidden">
<div class="flex items-center justify-between pb-3 border-b-0">
<div class="flex items-center gap-2">
<span class="material-symbols-outlined text-primary text-xl">shopping_basket</span>
<h3 class="font-headline-md text-headline-md text-on-surface">Keranjang Belanja</h3>
</div>
<span class="px-2.5 py-0.5 rounded-full bg-primary-fixed text-on-primary-fixed font-label-sm text-label-sm font-bold" id="cart-item-count-badge">3 Item</span>
</div>
<!-- Dynamic Item List Container -->
<div class="divide-y-0 space-y-3 py-3 max-h-72 overflow-y-auto" id="cart-items-container">
<!-- Item 1 -->
<div class="flex items-center justify-between gap-2 p-2 rounded-lg bg-surface-container-low">
<div class="min-w-0 flex-1">
<p class="font-headline-sm text-headline-sm text-on-surface truncate">Telur Ayam Ras (Karpet)</p>
<p class="font-body-sm text-body-sm text-on-surface-variant">1 Karpet (30 butir)</p>
<p class="font-label-sm text-label-sm text-primary font-bold">Rp 52.000</p>
</div>
<div class="flex items-center gap-1">
<button aria-label="Kurangi" class="w-7 h-7 rounded bg-surface-container-lowest flex items-center justify-center text-on-surface hover:bg-surface-container-high transition-colors font-bold text-sm" type="button">-</button>
<span class="font-label-sm text-label-sm font-bold px-1.5">1</span>
<button aria-label="Tambah" class="w-7 h-7 rounded bg-surface-container-lowest flex items-center justify-center text-on-surface hover:bg-surface-container-high transition-colors font-bold text-sm" type="button">+</button>
</div>
</div>
<!-- Item 2 -->
<div class="flex items-center justify-between gap-2 p-2 rounded-lg bg-surface-container-low">
<div class="min-w-0 flex-1">
<p class="font-headline-sm text-headline-sm text-on-surface truncate">Telur Bebek Tambak (Pack)</p>
<p class="font-body-sm text-body-sm text-on-surface-variant">1 Pack (10 butir)</p>
<p class="font-label-sm text-label-sm text-primary font-bold">Rp 32.000</p>
</div>
<div class="flex items-center gap-1">
<button aria-label="Kurangi" class="w-7 h-7 rounded bg-surface-container-lowest flex items-center justify-center text-on-surface hover:bg-surface-container-high transition-colors font-bold text-sm" type="button">-</button>
<span class="font-label-sm text-label-sm font-bold px-1.5">1</span>
<button aria-label="Tambah" class="w-7 h-7 rounded bg-surface-container-lowest flex items-center justify-center text-on-surface hover:bg-surface-container-high transition-colors font-bold text-sm" type="button">+</button>
</div>
</div>
</div>
<!-- Cost Calculation Breakdown -->
<div class="pt-3 space-y-2 text-body-sm font-body-sm">
<div class="flex items-center justify-between text-on-surface-variant">
<span>Subtotal Produk</span>
<span class="font-medium text-on-surface" id="summary-subtotal">Rp 84.000</span>
</div>
<div class="flex items-center justify-between text-on-surface-variant">
<span class="flex items-center gap-1">
                Ongkir Tanggamus (<span id="selected-kecamatan-label">Gisting</span>)
              </span>
<span class="font-bold text-secondary">GRATIS</span>
</div>
<div class="flex items-center justify-between text-on-surface-variant">
<span>Garansi Ganti Pecah</span>
<span class="text-secondary font-medium">Termasuk (Rp 0)</span>
</div>
<div class="pt-3 flex items-baseline justify-between font-headline-md text-headline-md text-on-surface">
<span>Total Bayar:</span>
<span class="text-price-display text-price-display text-primary" id="summary-total">Rp 84.000</span>
</div>
</div>
<!-- Checkout CTAs -->
<div class="pt-4 space-y-2.5">
<a class="w-full py-3 rounded-lg bg-secondary text-on-secondary hover:bg-secondary/90 transition-colors font-label-lg text-label-lg font-bold flex items-center justify-center gap-2 shadow-sm text-center" href="https://wa.me/6281278900000?text=Halo%20Bang%20Zul,%20saya%20mau%20pesan%20telur%20segar%20antar%20ke%20Gisting:%201%20Karpet%20Telur%20Ras%20+%201%20Pack%20Telur%20Bebek" rel="noopener" target="_blank">
<span class="material-symbols-outlined text-lg">chat</span>
<span>Pesan Cepat via WhatsApp</span>
</a>
<button class="w-full py-2.5 rounded-lg bg-primary-container text-on-primary-container hover:bg-primary-fixed-dim transition-colors font-label-md text-label-md font-bold flex items-center justify-center gap-2" onclick="openPaymentModal()" type="button">
<span class="material-symbols-outlined text-base">qr_code_scanner</span>
<span>Bayar QRIS / COD di Tempat</span>
</button>
</div>
<p class="font-label-sm text-label-sm text-on-surface-variant text-center pt-3 flex items-center justify-center gap-1">
<span class="material-symbols-outlined text-xs text-secondary">verified_user</span>
<span>Pembayaran aman &amp; bisa periksa telur sebelum kurir pamit</span>
</p>
</div>
<!-- Kurir Delivery Radius Card -->
<div class="p-4 rounded-xl bg-surface-container-low text-on-surface space-y-2">
<div class="flex items-center gap-2 text-primary font-headline-sm text-headline-sm">
<span class="material-symbols-outlined">map</span>
<span>Area Rute Kurir Motor UD. Bang Zul</span>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant">
            Armada motor dilengkapi keranjang busa anti getar khusus jalan menanjak &amp; berbatu di Tanggamus.
          </p>
<div class="flex flex-wrap gap-1.5 pt-1">
<span class="px-2 py-0.5 rounded bg-surface-container font-label-sm text-label-sm text-on-surface">Gisting Bawah &amp; Atas</span>
<span class="px-2 py-0.5 rounded bg-surface-container font-label-sm text-label-sm text-on-surface">Talang Padang</span>
<span class="px-2 py-0.5 rounded bg-surface-container font-label-sm text-label-sm text-on-surface">Kota Agung</span>
<span class="px-2 py-0.5 rounded bg-surface-container font-label-sm text-label-sm text-on-surface">Wonosobo</span>
</div>
</div>
</aside>
</div>
</section>
<!-- Local Tanggamus Customer Reviews / Testimonials -->
<section class="w-full max-w-7xl mx-auto px-4 lg:px-8 py-10">
<div class="p-8 rounded-xl bg-surface-container-low space-y-6">
<div class="flex flex-col sm:flex-row sm:items-end justify-between gap-2">
<div>
<span class="font-label-sm text-label-sm text-secondary font-bold uppercase tracking-wider">Kepercayaan Warga Tanggamus</span>
<h2 class="font-headline-lg text-headline-lg text-on-surface tracking-tight">Kata Pembeli Setia Bang Zul Egg Market</h2>
</div>
<div class="flex items-center gap-1 text-primary">
<span class="material-symbols-outlined text-lg" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-lg" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-lg" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-lg" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-lg" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="font-headline-sm text-headline-sm text-on-surface ml-1">4.9 / 5.0 (420+ Ulasan)</span>
</div>
</div>
<div class="grid grid-cols-1 md:grid-cols-3 gap-4">
<!-- Review 1 -->
<div class="p-5 rounded-lg bg-surface-container-lowest shadow-sm space-y-3">
<div class="flex items-center gap-1 text-primary">
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant italic">
            "Langganan telur untuk warung makan di Talang Padang. Timbangan selalu pas, telur besar-besar, dan cangkangnya bersih tidak ada kotoran kandang menempel. Kurir ramah!"
          </p>
<div class="flex items-center gap-2.5 pt-2">
<div class="w-8 h-8 rounded-full bg-primary-fixed text-on-primary-fixed flex items-center justify-center font-bold text-xs">BS</div>
<div>
<p class="font-headline-sm text-headline-sm text-on-surface leading-none">Ibu Sri Wahyuni</p>
<p class="font-label-sm text-label-sm text-on-surface-variant">Warung Nasi Talang Padang</p>
</div>
</div>
</div>
<!-- Review 2 -->
<div class="p-5 rounded-lg bg-surface-container-lowest shadow-sm space-y-3">
<div class="flex items-center gap-1 text-primary">
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant italic">
            "Telur bebeknya luar biasa mantap untuk martabak telur. Kuningnya oranye pekat, gurih berminyak. Dikirim 4 karpet ke Kota Agung tanpa ada satu pun yang pecah."
          </p>
<div class="flex items-center gap-2.5 pt-2">
<div class="w-8 h-8 rounded-full bg-secondary-fixed text-on-secondary-fixed flex items-center justify-center font-bold text-xs">MZ</div>
<div>
<p class="font-headline-sm text-headline-sm text-on-surface leading-none">Mas Zaki Martabak</p>
<p class="font-label-sm text-label-sm text-on-surface-variant">Kecamatan Kota Agung</p>
</div>
</div>
</div>
<!-- Review 3 -->
<div class="p-5 rounded-lg bg-surface-container-lowest shadow-sm space-y-3">
<div class="flex items-center gap-1 text-primary">
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant italic">
            "Sering beli telur ayam kampung omega untuk MPASI cucu. Terasa sekali beda segarnya telur yang baru dipanen subuh dibandingkan yang lama ngetem di toko umum."
          </p>
<div class="flex items-center gap-2.5 pt-2">
<div class="w-8 h-8 rounded-full bg-tertiary-fixed text-on-tertiary-fixed flex items-center justify-center font-bold text-xs">RT</div>
<div>
<p class="font-headline-sm text-headline-sm text-on-surface leading-none">Ibu Ratna</p>
<p class="font-label-sm text-label-sm text-on-surface-variant">Gisting Atas</p>
</div>
</div>
</div>
</div>
</div>
</section>
<!-- Educational Trust & Guarantee FAQ -->
<section class="w-full max-w-7xl mx-auto px-4 lg:px-8 pb-12">
<div class="grid grid-cols-1 md:grid-cols-2 gap-6">
<div class="p-6 rounded-xl bg-surface-container-lowest shadow-sm space-y-3">
<div class="flex items-center gap-2 text-primary font-headline-sm text-headline-sm">
<span class="material-symbols-outlined">help_outline</span>
<span>Bagaimana jika ada telur yang retak/pecah saat sampai?</span>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant">
          Jangan khawatir! Anda berhak langsung memeriksa telur saat kurir tiba. Jika ada 1 atau 2 butir retak, kurir kami akan mengganti telur baru seketika atau memotong tunai dari total nota belanja Anda saat itu juga.
        </p>
</div>
<div class="p-6 rounded-xl bg-surface-container-lowest shadow-sm space-y-3">
<div class="flex items-center gap-2 text-secondary font-headline-sm text-headline-sm">
<span class="material-symbols-outlined">local_shipping</span>
<span>Berapa minimal pembelian agar Gratis Ongkir?</span>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant">
          Untuk wilayah Gisting dan sekitarnya, cukup pesan minimal 2 karpet (tray) atau belanja senilai Rp 100.000, pengantaran kurir langsung gratis sampai depan pintu rumah atau warung Anda!
        </p>
</div>
</div>
</section>
<!-- Interactive JavaScript for Cart Operations and Local Feedback -->
<script>
    let cart = [
      { name: 'Telur Ayam Ras (Karpet)', price: 52000, qty: 1, unit: 'Karpet (30 btr)' },
      { name: 'Telur Bebek Tambak Segar (Pack)', price: 32000, qty: 1, unit: 'Pack (10 butir)' }
    ];

    function formatRupiah(num) {
      return 'Rp ' + num.toString().replace(/\B(?=(\d{3})+(?!\d))/g, ".");
    }

    function updateCartUI() {
      const container = document.getElementById('cart-items-container');
      const badge = document.getElementById('cart-item-count-badge');
      const subtotalEl = document.getElementById('summary-subtotal');
      const totalEl = document.getElementById('summary-total');

      if (!container) return;

      container.innerHTML = '';
      let subtotal = 0;
      let totalQty = 0;

      cart.forEach((item, index) => {
        subtotal += item.price * item.qty;
        totalQty += item.qty;

        const row = document.createElement('div');
        row.className = 'flex items-center justify-between gap-2 p-2 rounded-lg bg-surface-container-low';
        row.innerHTML = `
          <div class="min-w-0 flex-1">
            <p class="font-headline-sm text-headline-sm text-on-surface truncate">${item.name}</p>
            <p class="font-body-sm text-body-sm text-on-surface-variant">${item.qty} x ${formatRupiah(item.price)}</p>
            <p class="font-label-sm text-label-sm text-primary font-bold">${formatRupiah(item.price * item.qty)}</p>
          </div>
          <div class="flex items-center gap-1">
            <button type="button" onclick="modifyQty(${index}, -1)" aria-label="Kurangi" class="w-7 h-7 rounded bg-surface-container-lowest flex items-center justify-center text-on-surface hover:bg-surface-container-high font-bold text-sm">-</button>
            <span class="font-label-sm text-label-sm font-bold px-1.5">${item.qty}</span>
            <button type="button" onclick="modifyQty(${index}, 1)" aria-label="Tambah" class="w-7 h-7 rounded bg-surface-container-lowest flex items-center justify-center text-on-surface hover:bg-surface-container-high font-bold text-sm">+</button>
          </div>
        `;
        container.appendChild(row);
      });

      if (cart.length === 0) {
        container.innerHTML = '<p class="font-body-sm text-body-sm text-on-surface-variant text-center py-4">Keranjang masih kosong. Pilih telur segar di samping!</p>';
      }

      badge.textContent = `${totalQty} Item`;
      subtotalEl.textContent = formatRupiah(subtotal);
      totalEl.textContent = formatRupiah(subtotal);
    }

    function modifyQty(index, delta) {
      if (cart[index]) {
        cart[index].qty += delta;
        if (cart[index].qty <= 0) {
          cart.splice(index, 1);
        }
        updateCartUI();
      }
    }

    function addToCart(name, price, qty) {
      const existing = cart.find(item => item.name === name);
      if (existing) {
        existing.qty += qty;
      } else {
        cart.push({ name: name, price: price, qty: qty, unit: 'Pesanan' });
      }
      updateCartUI();

      // Quick visual feedback alert
      const toast = document.createElement('div');
      toast.className = 'fixed bottom-6 left-1/2 -translate-x-1/2 z-50 bg-on-background text-surface px-5 py-2.5 rounded-full font-label-md text-label-md shadow-xl flex items-center gap-2 transition-all';
      toast.innerHTML = `<span class="material-symbols-outlined text-secondary-fixed text-base">check_circle</span> <span>${name} berhasil masuk keranjang</span>`;
      document.body.appendChild(toast);
      setTimeout(() => { toast.remove(); }, 2200);
    }

    function buyNow(name, price) {
      addToCart(name, price, 1);
      const target = document.getElementById('kecamatan-selector');
      const kec = target ? target.value : 'Gisting';
      const waText = encodeURIComponent(`Halo Bang Zul, saya mau pesan telur segar segera:\n- ${name} (1x)\nAntar ke wilayah: ${kec}\nMohon infokan total & waktu kurir jalan.`);
      window.open(`https://wa.me/6281278900000?text=${waText}`, '_blank');
    }

    function openPaymentModal() {
      const target = document.getElementById('kecamatan-selector');
      const kec = target ? target.value : 'Gisting';
      alert(`Pesanan siap diproses ke wilayah ${kec}!\nSilakan siapkan uang pas untuk COD, atau scan kode QRIS saat kurir UD. Bang Zul tiba di lokasi.`);
    }

    // Kecamatan change handler
    const selectEl = document.getElementById('kecamatan-selector');
    if (selectEl) {
      selectEl.addEventListener('change', function() {
        const lbl = document.getElementById('selected-kecamatan-label');
        if (lbl) lbl.textContent = this.value;
      });
    }

    // Category Buttons Active Switcher
    const catBtns = document.querySelectorAll('.category-btn');
    catBtns.forEach(btn => {
      btn.addEventListener('click', () => {
        catBtns.forEach(b => {
          b.classList.remove('bg-primary', 'text-on-primary', 'shadow-sm');
          b.classList.add('bg-surface-container-low', 'text-on-surface-variant');
        });
        btn.classList.add('bg-primary', 'text-on-primary', 'shadow-sm');
        btn.classList.remove('bg-surface-container-low', 'text-on-surface-variant');
      });
    });

    // Initialize UI
    updateCartUI();
  </script>
</div></main><footer class="w-full bg-surface-container-low mt-16 pt-12 pb-8 text-on-surface-variant"><div class="max-w-7xl mx-auto px-4 lg:px-8 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8"><div class="space-y-3"><div class="flex items-center gap-2"><img alt="Logo Bang Zul Egg Market" class="h-7 w-auto object-contain" src="https://lh3.googleusercontent.com/aida/ALJJyrAvuhgJbL1OqXYnorOpflEwk9ch2RB3i3nIpJf2khBHtFUraZYLjA49xnoYr5_XpY1inx_yvUKDG-f5ULodcAC4hoBl9QYWujU07wAAJsvNI88PefRZRNH2SgRzcvtvfP9LlMDgvobQRRrHxWwLlWY8MQoR1CS4kennwXqXJqn5PR3R5zkf-p4q0eleDblVHlCAtE__Wj8FbqU6db9zlBw02jnLdLpow_xGCN8RF4es"/><span class="font-headline-sm text-headline-sm text-primary">UD. Bang Zul Egg Market</span></div><p class="font-body-sm text-body-sm">Pusat distribusi telur segar langsung dari peternak binaan lokal Tanggamus. Menjaga kualitas kesegaran cangkang utuh dan timbangan presisi terpercaya.</p><div class="flex items-center gap-2 text-secondary font-label-sm text-label-sm"><span class="material-symbols-outlined text-sm">verified</span><span>Garansi Ganti Telur Pecah 100%</span></div></div><div class="space-y-2"><h3 class="font-headline-sm text-headline-sm text-on-surface">Jam Operasional &amp; Panen</h3><p class="font-body-sm text-body-sm">Pengambilan Telur Kandang: 06.00 - 10.00 WIB</p><p class="font-body-sm text-body-sm">Jadwal Pengiriman Kurir: 08.00 - 18.00 WIB</p><p class="font-body-sm text-body-sm text-secondary font-semibold">Setiap Hari (Senin - Minggu Tetap Buka)</p><p class="font-label-sm text-label-sm text-on-surface-variant pt-1">Wilayah Gisting, Talang Padang, Wonosobo, Kota Agung &amp; Sekitarnya.</p></div><div class="space-y-2"><h3 class="font-headline-sm text-headline-sm text-on-surface">Metode Pembayaran</h3><div class="space-y-1 font-body-sm text-body-sm"><p class="flex items-center gap-1.5"><span class="material-symbols-outlined text-primary text-sm">qr_code_scanner</span>QRIS Seluruh Bank &amp; E-Wallet</p><p class="flex items-center gap-1.5"><span class="material-symbols-outlined text-primary text-sm">account_balance</span>Transfer Bank Lampung / BRI / BCA</p><p class="flex items-center gap-1.5"><span class="material-symbols-outlined text-primary text-sm">payments</span>COD (Bayar Tunai di Tempat saat Timbang)</p></div></div><div class="space-y-2"><h3 class="font-headline-sm text-headline-sm text-on-surface">Komitmen Peternak Lokal</h3><p class="font-body-sm text-body-sm">Mendukung keberlanjutan usaha peternak unggas pedesaan di Kabupaten Tanggamus, Lampung dengan harga adil, timbangan transparan, dan pakan alami bermutu.</p><div class="pt-2"><span class="inline-block px-3 py-1 bg-secondary-container text-on-secondary-container rounded-full font-label-sm text-label-sm">Asli Tanggamus, Segar Bergaransi</span></div></div></div><div class="max-w-7xl mx-auto px-4 lg:px-8 mt-10 pt-4 flex flex-col sm:flex-row items-center justify-between gap-2 font-label-sm text-label-sm text-on-surface-variant"><p>© 2024 UD. Bang Zul Egg Market Tanggamus Lampung. Hak Cipta Dilindungi.</p><p>Dibuat untuk ekosistem niaga agrikultur Kabupaten Tanggamus</p></div></footer></body></html>

<!-- Dashboard Penjual Bang Zul -->
<!DOCTYPE html>

<html lang="id"><head><meta charset="utf-8"/><meta content="width=device-width, initial-scale=1.0" name="viewport"/><meta content="web_dashboard" name="shell-type"/><link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" rel="stylesheet"/><link href="https://fonts.googleapis.com" rel="preconnect"/><link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/><link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&amp;family=Plus+Jakarta+Sans:wght@700;800&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/><style>@layer base{html,body{margin:0;padding:0;}body{overscroll-behavior:none;}main>:first-child{margin-top:0!important;}main>:last-child{margin-bottom:0!important;}}::-webkit-scrollbar{display:none;}</style><script src="https://cdn.tailwindcss.com"></script><script id="tailwind-config">tailwind.config={darkMode:"class",theme:{extend:{colors:{"on-primary-container":"#644000","on-secondary-fixed-variant":"#005312","surface":"#fcf9f8","on-tertiary-fixed-variant":"#3e4a41","on-secondary":"#ffffff","surface-container-lowest":"#ffffff","on-primary-fixed-variant":"#633f00","on-primary":"#ffffff","primary-container":"#f5a623","error":"#ba1a1a","tertiary-fixed":"#d9e6da","on-primary-fixed":"#291800","tertiary-fixed-dim":"#bdcabe","surface-container-high":"#eae7e7","surface-dim":"#dcd9d9","on-error-container":"#93000a","tertiary":"#556158","outline-variant":"#d7c3ae","secondary-container":"#a0f399","inverse-on-surface":"#f3f0f0","on-secondary-container":"#217128","background":"#fcf9f8","on-surface-variant":"#524534","on-error":"#ffffff","surface-variant":"#e4e2e1","surface-bright":"#fcf9f8","error-container":"#ffdad6","primary":"#835500","secondary-fixed":"#a3f69c","primary-fixed-dim":"#ffb955","inverse-surface":"#303030","on-background":"#1b1c1c","on-tertiary":"#ffffff","surface-tint":"#835500","on-tertiary-container":"#3e4a41","inverse-primary":"#ffb955","surface-container-low":"#f6f3f2","secondary-fixed-dim":"#88d982","on-surface":"#1b1c1c","tertiary-container":"#acb9ae","secondary":"#1b6d24","surface-container-highest":"#e4e2e1","surface-container":"#f0eded","primary-fixed":"#ffddb4","outline":"#857462","on-secondary-fixed":"#002204","on-tertiary-fixed":"#131e17"},borderRadius:{"DEFAULT":"0.25rem","lg":"0.5rem","xl":"0.75rem","full":"9999px"},spacing:{"gutter-desktop":"1.5rem","margin-desktop":"2.5rem","gutter":"1rem","space-lg":"1.5rem","space-xl":"2rem","margin":"1rem","space-md":"1rem","space-xs":"0.25rem","space-sm":"0.5rem"},fontFamily:{"body-md":["Inter"],"headline-lg-mobile":["Plus Jakarta Sans"],"headline-sm":["Plus Jakarta Sans"],"label-lg":["Inter"],"display-lg-mobile":["Plus Jakarta Sans"],"display-lg":["Plus Jakarta Sans"],"label-sm":["Inter"],"headline-lg":["Plus Jakarta Sans"],"stock-counter":["Inter"],"label-md":["Inter"],"headline-md":["Plus Jakarta Sans"],"body-sm":["Inter"],"price-display":["Plus Jakarta Sans"],"body-lg":["Inter"]},fontSize:{"body-md":["14px",{"lineHeight":"22px","fontWeight":"400"}],"headline-lg-mobile":["22px",{"lineHeight":"30px","letterSpacing":"0em","fontWeight":"700"}],"headline-sm":["16px",{"lineHeight":"24px","fontWeight":"700"}],"label-lg":["14px",{"lineHeight":"20px","fontWeight":"600"}],"display-lg-mobile":["30px",{"lineHeight":"38px","letterSpacing":"-0.01em","fontWeight":"800"}],"display-lg":["40px",{"lineHeight":"48px","letterSpacing":"-0.02em","fontWeight":"800"}],"label-sm":["11px",{"lineHeight":"14px","letterSpacing":"0.02em","fontWeight":"600"}],"headline-lg":["28px",{"lineHeight":"36px","letterSpacing":"-0.01em","fontWeight":"700"}],"stock-counter":["18px",{"lineHeight":"24px","letterSpacing":"0.01em","fontWeight":"700"}],"label-md":["12px",{"lineHeight":"16px","fontWeight":"600"}],"headline-md":["20px",{"lineHeight":"28px","fontWeight":"700"}],"body-sm":["12px",{"lineHeight":"18px","fontWeight":"400"}],"price-display":["22px",{"lineHeight":"28px","letterSpacing":"-0.02em","fontWeight":"800"}],"body-lg":["16px",{"lineHeight":"26px","fontWeight":"400"}]}}}}</script></head><body class="bg-surface font-body-md text-body-md text-on-surface antialiased"><aside class="fixed left-0 top-0 h-full w-64 bg-surface-container-low z-50 flex flex-col py-5 shadow-[0_4px_20px_-2px_rgba(245,166,35,0.08)]"><div class="px-5 mb-6 flex items-center gap-3"><img alt="Logo Bang Zul Egg Market" class="h-8 w-auto object-contain" src="https://lh3.googleusercontent.com/aida/ALJJyrAvuhgJbL1OqXYnorOpflEwk9ch2RB3i3nIpJf2khBHtFUraZYLjA49xnoYr5_XpY1inx_yvUKDG-f5ULodcAC4hoBl9QYWujU07wAAJsvNI88PefRZRNH2SgRzcvtvfP9LlMDgvobQRRrHxWwLlWY8MQoR1CS4kennwXqXJqn5PR3R5zkf-p4q0eleDblVHlCAtE__Wj8FbqU6db9zlBw02jnLdLpow_xGCN8RF4es"/><div class="flex flex-col"><span class="font-headline-sm text-headline-sm text-primary leading-tight">Bang Zul</span><span class="font-label-sm text-label-sm text-on-surface-variant">Sistem Operasional</span></div></div><div class="px-4 mb-4"><div class="p-2.5 rounded-xl bg-surface-container flex items-center gap-2"><span class="material-symbols-outlined text-secondary text-lg">pin_drop</span><div class="leading-none"><span class="font-label-sm text-label-sm font-bold block text-on-surface">Pos Tanggamus</span><span class="font-label-sm text-label-sm text-on-surface-variant">Gisting - Talang Padang</span></div></div></div><nav class="flex-1 px-3 space-y-1" data-active-classes="bg-primary-container text-on-primary-container font-bold"><a aria-current="page" class="flex items-center gap-3 px-3 py-2.5 rounded-xl transition-all bg-primary-container text-on-primary-container font-bold" data-path="toko-bang-zul" href="#"><span class="material-symbols-outlined text-lg">storefront</span>Toko &amp; Inventori Bang Zul</a><a class="flex items-center gap-3 px-3 py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface font-label-md text-label-md transition-all" data-path="kurir-tanggamus" href="#"><span class="material-symbols-outlined text-lg">two_wheeler</span>Pantau Kurir Lapangan</a><a class="flex items-center gap-3 px-3 py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface font-label-md text-label-md transition-all" data-path="admin-pasar" href="#"><span class="material-symbols-outlined text-lg">admin_panel_settings</span>Admin &amp; Kas Penjualan</a><a class="flex items-center gap-3 px-3 py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface font-label-md text-label-md transition-all" data-path="jadwal-panen-stok" href="#"><span class="material-symbols-outlined text-lg">egg</span>Timbangan &amp; Panen</a><a class="flex items-center gap-3 px-3 py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface font-label-md text-label-md transition-all" data-path="katalog-belanja" href="#"><span class="material-symbols-outlined text-lg">store</span>Lihat Toko Publik</a></nav><div class="px-4 pt-3 border-t border-surface-container-highest flex items-center justify-between"><div class="flex items-center gap-2"><img alt="Profile" class="w-8 h-8 rounded-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBu4cCay1o-kcZkrepBjdwRhNkTeb5NSNF4V20H1AoEXr4ahIrRP9SktX37TUve3u7us_GHnlm1279EoAyYcFxqZTZV4CIOdstOTCqIMcitiPTCwpWm4m2okjdh9z8S2I2n0sK1hb3y3ohWU84Tu6ZWNoxKL7D1NVLhMsBA3C6eHNQmukclnmKpMzHXssx-xtkh1wF2y2OFEDgXUgTPjjAfLabaOsUrz91MId6by4k"/><div class="leading-none"><span class="font-label-sm text-label-sm font-bold block text-on-surface">Bang Zul</span><span class="font-label-sm text-label-sm text-secondary">Owner &amp; Verifikator</span></div></div><a class="text-on-surface-variant hover:text-error" data-path="login-auth" href="#"><span class="material-symbols-outlined text-lg">logout</span></a></div></aside><div class="pl-64"><header class="fixed top-0 left-64 right-0 h-16 bg-surface/95 backdrop-blur-md shadow-[0_1px_8px_rgba(0,0,0,0.04)] z-40 px-6 flex items-center justify-between"><div class="flex items-center gap-3"><span class="inline-flex items-center px-2.5 py-1 rounded-full bg-secondary-container text-on-secondary-container font-label-sm text-label-sm font-semibold"><span class="w-1.5 h-1.5 rounded-full bg-secondary mr-1.5"></span>Sistem Operasional Aktif</span><span class="text-body-sm font-body-sm text-on-surface-variant hidden md:inline">Wilayah Gisting • Kota Agung • Talang Padang</span></div><div class="flex items-center gap-3"><a class="hidden sm:flex items-center gap-1 px-3 py-1.5 rounded-lg bg-surface-container text-on-surface font-label-sm text-label-sm hover:bg-surface-container-high" href="https://wa.me/6281278900000"><span class="material-symbols-outlined text-secondary text-sm">support_agent</span>CS Bang Zul</a><button class="p-2 rounded-full hover:bg-surface-container text-on-surface-variant" type="button"><span class="material-symbols-outlined text-xl">notifications</span></button><img alt="Profile" class="w-8 h-8 rounded-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBu4cCay1o-kcZkrepBjdwRhNkTeb5NSNF4V20H1AoEXr4ahIrRP9SktX37TUve3u7us_GHnlm1279EoAyYcFxqZTZV4CIOdstOTCqIMcitiPTCwpWm4m2okjdh9z8S2I2n0sK1hb3y3ohWU84Tu6ZWNoxKL7D1NVLhMsBA3C6eHNQmukclnmKpMzHXssx-xtkh1wF2y2OFEDgXUgTPjjAfLabaOsUrz91MId6by4k"/></div></header><main class="w-full pt-16 bg-surface px-6 py-6 min-h-screen"><div class="flex flex-col w-full space-y-6">
<!-- Role Switcher & Tanggamus Operational Quick Bar -->
<div class="flex flex-col md:flex-row items-stretch md:items-center justify-between gap-4">
<!-- Segmental Role Switcher -->
<div class="inline-flex p-1 bg-surface-container rounded-xl shadow-inner max-w-fit">
<button class="px-4 py-1.5 rounded-lg text-on-surface-variant font-label-md text-label-md hover:text-on-surface transition-colors">
        Pembeli
      </button>
<button class="px-4 py-1.5 rounded-lg bg-surface-container-lowest text-on-surface font-label-md text-label-md font-bold shadow-sm flex items-center gap-1.5">
<span class="w-2 h-2 rounded-full bg-secondary"></span>
        Penjual Bang Zul
      </button>
<button class="px-4 py-1.5 rounded-lg text-on-surface-variant font-label-md text-label-md hover:text-on-surface transition-colors">
        Kurir Tanggamus
      </button>
<button class="px-4 py-1.5 rounded-lg text-on-surface-variant font-label-md text-label-md hover:text-on-surface transition-colors">
        Admin Kas
      </button>
</div>
<!-- Quick Status Badge & Operational Date -->
<div class="flex items-center gap-3 self-end md:self-auto">
<span class="px-3 py-1.5 rounded-xl bg-surface-container-high text-on-surface-variant font-label-sm text-label-sm flex items-center gap-1.5">
<span class="material-symbols-outlined text-sm text-primary">calendar_today</span>
        Kamis, 24 Oktober 2024 • Sesi Pagi 07:30 WIB
      </span>
<span class="px-3 py-1.5 rounded-xl bg-tertiary-fixed text-on-tertiary-fixed-variant font-label-sm text-label-sm font-semibold flex items-center gap-1">
<span class="material-symbols-outlined text-sm">hub</span>
        Gudang Gisting Utama
      </span>
</div>
</div>
<!-- Header Banner & Store Status Toggle -->
<div class="rounded-xl bg-gradient-to-r from-primary/10 via-primary-container/15 to-surface-container-lowest p-6 shadow-sm flex flex-col lg:flex-row lg:items-center justify-between gap-6">
<div class="flex items-start gap-4">
<div class="w-14 h-14 rounded-xl bg-primary-container text-on-primary-container flex items-center justify-center shrink-0 shadow-md">
<span class="material-symbols-outlined text-3xl">egg_alt</span>
</div>
<div>
<div class="flex items-center gap-2 mb-1">
<span class="font-label-sm text-label-sm uppercase tracking-wider text-primary font-bold">UD. Bang Zul Telur Berkah Tanggamus</span>
<span class="w-1.5 h-1.5 rounded-full bg-secondary"></span>
<span class="font-label-sm text-label-sm text-secondary font-bold">Peternakan Terverifikasi</span>
</div>
<h1 class="font-headline-lg text-headline-lg text-on-surface tracking-tight leading-tight">
          Halo Bang Zul! Kelola Panen &amp; Pesanan Hari Ini
        </h1>
<p class="font-body-md text-body-md text-on-surface-variant mt-1">
          Pantau timbangan segar dari kandang Gisting &amp; Talang Padang, siap antar rute se-Tanggamus.
        </p>
</div>
</div>
<!-- Store Open / Close Switcher -->
<div class="bg-surface-container-lowest p-4 rounded-xl shadow-sm flex items-center justify-between sm:justify-start gap-4 shrink-0">
<div class="text-left">
<div class="flex items-center gap-1.5">
<span class="w-2.5 h-2.5 rounded-full bg-secondary animate-pulse"></span>
<span class="font-label-lg text-label-lg font-bold text-on-surface">Toko Buka</span>
</div>
<span class="font-body-sm text-body-sm text-on-surface-variant block mt-0.5">Menerima Pesanan &amp; Antar Hari Ini</span>
</div>
<label class="relative inline-flex items-center cursor-pointer">
<input checked="" class="sr-only peer" id="storeStatusToggle" type="checkbox"/>
<div class="w-12 h-6 bg-surface-container-highest peer-focus:outline-none rounded-full peer peer-checked:after:translate-x-full peer-checked:after:border-white after:content-[''] after:absolute after:top-[2px] after:start-[2px] after:bg-white after:rounded-full after:h-5 after:w-5 after:transition-all peer-checked:bg-secondary"></div>
</label>
</div>
</div>
<!-- KPI Cards Grid -->
<div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
<!-- Card 1: Total Pendapatan -->
<div class="bg-surface-container-lowest p-5 rounded-xl shadow-sm flex flex-col justify-between">
<div class="flex items-start justify-between">
<div>
<span class="font-label-sm text-label-sm text-on-surface-variant uppercase tracking-wider block font-semibold">Total Pendapatan Hari Ini</span>
<span class="font-price-display text-price-display text-on-surface block mt-2">Rp 4.850.000</span>
</div>
<div class="p-2.5 rounded-xl bg-primary/10 text-primary">
<span class="material-symbols-outlined text-xl">payments</span>
</div>
</div>
<div class="mt-4 pt-3 flex items-center justify-between text-body-sm font-body-sm">
<span class="inline-flex items-center text-secondary font-label-md text-label-md font-bold">
<span class="material-symbols-outlined text-base">trending_up</span> +14%
        </span>
<span class="text-on-surface-variant">vs kemarin (Rp 4.25jt)</span>
</div>
</div>
<!-- Card 2: Telur Terjual -->
<div class="bg-surface-container-lowest p-5 rounded-xl shadow-sm flex flex-col justify-between">
<div class="flex items-start justify-between">
<div>
<span class="font-label-sm text-label-sm text-on-surface-variant uppercase tracking-wider block font-semibold">Telur Terjual (Volume)</span>
<div class="flex items-baseline gap-1 mt-2">
<span class="font-headline-lg text-headline-lg text-on-surface">98</span>
<span class="font-label-md text-label-md text-on-surface-variant font-bold">Karpet</span>
<span class="font-body-sm text-body-sm text-on-surface-variant">/ 120 Kg</span>
</div>
</div>
<div class="p-2.5 rounded-xl bg-secondary-container text-on-secondary-container">
<span class="material-symbols-outlined text-xl">inventory_2</span>
</div>
</div>
<div class="mt-4 pt-3 flex items-center justify-between text-body-sm font-body-sm">
<span class="text-secondary font-bold font-label-md text-label-md">68% Target Harian</span>
<span class="text-on-surface-variant">Kapasitas 145 Kpt</span>
</div>
</div>
<!-- Card 3: Pesanan Masuk & Distribusi -->
<div class="bg-surface-container-lowest p-5 rounded-xl shadow-sm flex flex-col justify-between">
<div class="flex items-start justify-between">
<div>
<span class="font-label-sm text-label-sm text-on-surface-variant uppercase tracking-wider block font-semibold">Pesanan Masuk</span>
<span class="font-headline-lg text-headline-lg text-on-surface block mt-2">42 Pesanan</span>
</div>
<div class="p-2.5 rounded-xl bg-primary-container text-on-primary-container">
<span class="material-symbols-outlined text-xl">local_shipping</span>
</div>
</div>
<div class="mt-4 pt-3 flex items-center gap-2 font-label-sm text-label-sm text-on-surface-variant overflow-x-auto">
<span class="px-2 py-0.5 rounded-md bg-surface-container text-error font-bold">8 Konfirm</span>
<span class="px-2 py-0.5 rounded-md bg-surface-container text-primary font-bold">15 Kemas</span>
<span class="px-2 py-0.5 rounded-md bg-secondary-container text-on-secondary-container font-bold">19 Antar</span>
</div>
</div>
<!-- Card 4: Stok Siap Kirim -->
<div class="bg-surface-container-lowest p-5 rounded-xl shadow-sm flex flex-col justify-between">
<div class="flex items-start justify-between">
<div>
<span class="font-label-sm text-label-sm text-on-surface-variant uppercase tracking-wider block font-semibold">Stok Kandang Siap Kirim</span>
<div class="flex items-baseline gap-1.5 mt-2">
<span class="font-headline-lg text-headline-lg text-on-surface">310</span>
<span class="font-label-md text-label-md text-secondary font-bold">Karpet Ready</span>
</div>
</div>
<div class="p-2.5 rounded-xl bg-tertiary-fixed text-on-tertiary-fixed">
<span class="material-symbols-outlined text-xl">warehouse</span>
</div>
</div>
<div class="mt-4 pt-3 flex items-center justify-between font-label-sm text-label-sm text-on-surface-variant">
<span>Ras: <strong class="text-on-surface">210</strong></span>
<span>Bebek: <strong class="text-on-surface">65</strong></span>
<span>Kmpg: <strong class="text-on-surface">35</strong></span>
</div>
</div>
</div>
<!-- Bento Section: Quick Harvest Input & Price Trends / Alerts -->
<div class="grid grid-cols-1 lg:grid-cols-12 gap-6">
<!-- Kolom Kiri: Quick Harvest Input & Stock Updater (7 Cols) -->
<div class="lg:col-span-7 bg-surface-container-lowest p-6 rounded-xl shadow-sm flex flex-col justify-between">
<div>
<div class="flex items-center justify-between mb-4">
<div class="flex items-center gap-2">
<div class="w-8 h-8 rounded-lg bg-primary-container text-on-primary-container flex items-center justify-center">
<span class="material-symbols-outlined text-base">scale</span>
</div>
<div>
<h2 class="font-headline-sm text-headline-sm text-on-surface leading-snug">Input Panen Baru &amp; Perbarui Harga</h2>
<span class="font-body-sm text-body-sm text-on-surface-variant">Sinkronisasi langsung dengan katalog pembeli Tanggamus</span>
</div>
</div>
<span class="px-2.5 py-1 rounded-full bg-secondary-container text-on-secondary-container font-label-sm text-label-sm font-bold">
            Live POS Kandang
          </span>
</div>
<form class="space-y-4 pt-2" id="harvestForm">
<!-- Pilihan Jenis Telur (Radio Tiles) -->
<div>
<label class="font-label-sm text-label-sm text-on-surface-variant uppercase tracking-wider block mb-2 font-bold">
              1. Pilih Varietas Telur
            </label>
<div class="grid grid-cols-2 sm:grid-cols-4 gap-2.5">
<label class="relative flex flex-col p-3 rounded-xl bg-surface-container-low hover:bg-surface-container cursor-pointer transition-all has-[:checked]:bg-primary-container/20 has-[:checked]:text-on-primary-container">
<input checked="" class="sr-only" name="eggType" type="radio" value="ras"/>
<span class="font-label-md text-label-md font-bold">Ayam Ras</span>
<span class="font-body-sm text-body-sm text-on-surface-variant">Stok: 210 Kpt</span>
</label>
<label class="relative flex flex-col p-3 rounded-xl bg-surface-container-low hover:bg-surface-container cursor-pointer transition-all has-[:checked]:bg-primary-container/20 has-[:checked]:text-on-primary-container">
<input class="sr-only" name="eggType" type="radio" value="bebek"/>
<span class="font-label-md text-label-md font-bold">Bebek Asin</span>
<span class="font-body-sm text-body-sm text-on-surface-variant">Stok: 65 Kpt</span>
</label>
<label class="relative flex flex-col p-3 rounded-xl bg-surface-container-low hover:bg-surface-container cursor-pointer transition-all has-[:checked]:bg-primary-container/20 has-[:checked]:text-on-primary-container">
<input class="sr-only" name="eggType" type="radio" value="kampung"/>
<span class="font-label-md text-label-md font-bold">Kampung Liar</span>
<span class="font-body-sm text-body-sm text-on-surface-variant">Stok: 35 Kpt</span>
</label>
<label class="relative flex flex-col p-3 rounded-xl bg-surface-container-low hover:bg-surface-container cursor-pointer transition-all has-[:checked]:bg-primary-container/20 has-[:checked]:text-on-primary-container">
<input class="sr-only" name="eggType" type="radio" value="omega"/>
<span class="font-label-md text-label-md font-bold">Omega 3</span>
<span class="font-body-sm text-body-sm text-on-surface-variant">Stok: 40 Pack</span>
</label>
</div>
</div>
<div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
<!-- Jumlah Masuk -->
<div>
<label class="font-label-sm text-label-sm text-on-surface-variant uppercase tracking-wider block mb-1 font-bold">
                2. Volume Panen Masuk
              </label>
<div class="flex rounded-xl bg-surface-container-low p-1 focus-within:ring-2 focus-within:ring-primary-container">
<input class="w-full bg-transparent px-3 py-2 font-headline-sm text-headline-sm text-on-surface focus:outline-none" id="volumeInput" placeholder="Contoh: 30" type="number"/>
<select class="bg-surface-container rounded-lg px-2 text-label-sm font-label-sm text-on-surface focus:outline-none">
<option value="karpet">Karpet (30 Btr)</option>
<option value="kg">Kilogram (Kg)</option>
<option value="butir">Butir</option>
<option value="peti">Peti Kayu (15kg)</option>
</select>
</div>
<span class="font-body-sm text-body-sm text-on-surface-variant block mt-1">1 Karpet standar = 30 butir utuh</span>
</div>
<!-- Harga Jual Pasar Hari Ini -->
<div>
<label class="font-label-sm text-label-sm text-on-surface-variant uppercase tracking-wider block mb-1 font-bold">
                3. Harga Jual Pasar (Hari Ini)
              </label>
<div class="flex items-center rounded-xl bg-surface-container-low px-3 py-1 focus-within:ring-2 focus-within:ring-primary-container">
<span class="font-label-md text-label-md text-on-surface-variant mr-1.5 font-bold">Rp</span>
<input class="w-full bg-transparent py-2 font-headline-sm text-headline-sm text-on-surface focus:outline-none" id="priceInput" type="text" value="52.000"/>
<span class="font-body-sm text-body-sm text-on-surface-variant shrink-0">/ Karpet</span>
</div>
<span class="font-body-sm text-body-sm text-secondary block mt-1 font-semibold">• Rekomendasi Asosiasi Gisting: Rp 51.500 - 53.000</span>
</div>
</div>
<!-- Asal Kandang & Kualitas -->
<div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
<div>
<label class="font-label-sm text-label-sm text-on-surface-variant uppercase tracking-wider block mb-1 font-bold">
                Lokasi Kandang Pemasok
              </label>
<select class="w-full rounded-xl bg-surface-container-low p-2.5 font-label-md text-label-md text-on-surface focus:outline-none focus:ring-2 focus:ring-primary-container">
<option>Kandang Blok A (Gisting Atas - Suhu Sejuk)</option>
<option>Kandang Blok B (Talang Padang - Mandiri)</option>
<option>Mitra Peternak Rakyat Pugung</option>
</select>
</div>
<div>
<label class="font-label-sm text-label-sm text-on-surface-variant uppercase tracking-wider block mb-1 font-bold">
                Kondisi Sortir Fisik
              </label>
<div class="flex items-center gap-2 pt-2">
<span class="inline-flex items-center gap-1 px-2.5 py-1 rounded-lg bg-secondary-container text-on-secondary-container font-label-sm text-label-sm font-bold">
<span class="material-symbols-outlined text-sm">verified</span> Bersih &amp; Teropong OK
                </span>
<span class="font-body-sm text-body-sm text-on-surface-variant">Retak: 0%</span>
</div>
</div>
</div>
<div class="pt-2 flex items-center justify-end gap-3">
<button class="px-4 py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container font-label-md text-label-md transition-colors" type="reset">
              Reset Form
            </button>
<button class="px-5 py-2.5 rounded-xl bg-primary-container text-on-primary-container hover:bg-primary-fixed-dim font-label-md text-label-md font-bold shadow-md flex items-center gap-2 transition-transform active:scale-95" onclick="alert('Stok dan Harga Pasar Tanggamus Berhasil Diperbarui!');" type="button">
<span class="material-symbols-outlined text-lg">publish</span>
              Perbarui Harga Pasar &amp; Stok
            </button>
</div>
</form>
</div>
<!-- Quick Tips Lapangan Bang Zul -->
<div class="mt-4 pt-3 rounded-lg bg-surface-container-low p-3 flex items-center gap-3">
<span class="material-symbols-outlined text-primary text-xl">lightbulb</span>
<p class="font-body-sm text-body-sm text-on-surface-variant">
<strong class="text-on-surface">Tips Pengemasan:</strong> Untuk pengiriman rute tanjakan Gisting - Talang Padang, pastikan kurir mengikat maksimal 5 susun krat kayu agar tidak pecah di jalan bergelombang.
        </p>
</div>
</div>
<!-- Kolom Kanan: Tren Harga Pasar Tanggamus + Alert Stok (5 Cols) -->
<div class="lg:col-span-5 flex flex-col gap-6">
<!-- Chart Tren Harga 7 Hari -->
<div class="bg-surface-container-lowest p-6 rounded-xl shadow-sm flex flex-col justify-between flex-1">
<div>
<div class="flex items-center justify-between mb-2">
<div>
<span class="font-label-sm text-label-sm text-on-surface-variant uppercase tracking-wider block font-semibold">Dinamika Pasar Lokal</span>
<h3 class="font-headline-sm text-headline-sm text-on-surface">Tren Harga Telur Tanggamus (7 Hari)</h3>
</div>
<span class="px-2 py-1 rounded bg-secondary-container text-on-secondary-container font-label-sm text-label-sm font-bold">
              +4.2% Minggu Ini
            </span>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant mb-4">
            Rata-rata harga grosir per karpet (30 btr) di Pasar Talang Padang &amp; Gisting.
          </p>
<!-- Inline SVG Area Chart -->
<div class="relative w-full h-36">
<svg class="w-full h-full overflow-visible" preserveaspectratio="none" viewbox="0 0 320 120">
<defs>
<lineargradient id="priceGrad" x1="0" x2="0" y1="0" y2="1">
<stop offset="0%" stop-color="#f5a623" stop-opacity="0.35"></stop>
<stop offset="100%" stop-color="#f5a623" stop-opacity="0.0"></stop>
</lineargradient>
</defs>
<!-- Grid lines -->
<line stroke="#f0eded" stroke-dasharray="4" stroke-width="1" x1="0" x2="320" y1="20" y2="20"></line>
<line stroke="#f0eded" stroke-dasharray="4" stroke-width="1" x1="0" x2="320" y1="60" y2="60"></line>
<line stroke="#f0eded" stroke-dasharray="4" stroke-width="1" x1="0" x2="320" y1="100" y2="100"></line>
<!-- Area Fill -->
<path d="M 0,95 L 45,90 L 90,82 L 140,85 L 195,65 L 250,50 L 320,30 L 320,120 L 0,120 Z" fill="url(#priceGrad)"></path>
<!-- Price Curve -->
<path d="M 0,95 L 45,90 L 90,82 L 140,85 L 195,65 L 250,50 L 320,30" fill="none" stroke="#835500" stroke-linecap="round" stroke-linejoin="round" stroke-width="3"></path>
<!-- Data Dots -->
<circle cx="0" cy="95" fill="#ffffff" r="3.5" stroke="#835500" stroke-width="2"></circle>
<circle cx="90" cy="82" fill="#ffffff" r="3.5" stroke="#835500" stroke-width="2"></circle>
<circle cx="195" cy="65" fill="#ffffff" r="3.5" stroke="#835500" stroke-width="2"></circle>
<circle cx="250" cy="50" fill="#ffffff" r="3.5" stroke="#835500" stroke-width="2"></circle>
<circle cx="320" cy="30" fill="#1b6d24" r="4.5" stroke="#ffffff" stroke-width="2"></circle>
</svg>
</div>
<div class="flex justify-between font-label-sm text-label-sm text-on-surface-variant mt-2 pt-1">
<span>Jum (49k)</span>
<span>Sab (49.5k)</span>
<span>Min (50k)</span>
<span>Sen (50.5k)</span>
<span>Sel (51k)</span>
<span>Rab (51.5k)</span>
<span class="font-bold text-secondary">Hari Ini (52k)</span>
</div>
</div>
</div>
<!-- Critical Stock Alert Card -->
<div class="bg-surface-container-lowest p-5 rounded-xl shadow-sm flex flex-col justify-between">
<div class="flex items-start gap-3">
<div class="w-10 h-10 rounded-xl bg-error-container text-on-error-container flex items-center justify-center shrink-0">
<span class="material-symbols-outlined text-xl">warning</span>
</div>
<div class="flex-1">
<div class="flex items-center justify-between">
<h4 class="font-headline-sm text-headline-sm text-error">Peringatan Stok Menipis</h4>
<span class="px-2 py-0.5 rounded bg-error-container text-on-error-container font-label-sm text-label-sm font-bold">Segera Panen</span>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant mt-1">
<strong>Telur Bebek Angon</strong> tersisa <span class="text-error font-bold font-stock-counter text-stock-counter">12 Pack</span> di kandang Talang Padang. Ada 18 antrean pesanan martabak Kota Agung.
            </p>
</div>
</div>
<div class="mt-4 pt-3 flex items-center justify-between">
<a class="text-primary font-label-md text-label-md font-bold flex items-center gap-1 hover:underline" href="https://wa.me/6281278900000?text=Halo%20Peternak%20Bebek%20Talang%20Padang,%20mohon%20konfirmasi%20jadwal%20panen%20siang%20ini" target="_blank">
<span class="material-symbols-outlined text-base">call</span> Hubungi Peternak Bebek
          </a>
<button class="px-3 py-1.5 rounded-lg bg-surface-container-high hover:bg-surface-container-highest text-on-surface font-label-sm text-label-sm font-semibold transition-colors">
            Tutup Varian Sementara
          </button>
</div>
</div>
</div>
</div>
<!-- Real-World Farm Context Visual Banner -->
<div class="rounded-xl overflow-hidden shadow-sm relative bg-surface-container">
<div class="grid grid-cols-1 md:grid-cols-12 items-center">
<div class="md:col-span-7 p-6 z-10">
<div class="inline-flex items-center gap-1.5 px-2.5 py-1 rounded-full bg-surface-container-lowest text-on-surface font-label-sm text-label-sm font-bold mb-3 shadow-sm">
<span class="material-symbols-outlined text-secondary text-sm">agriculture</span> Kemitraan Peternak Tanggamus
        </div>
<h3 class="font-headline-lg text-headline-lg text-on-surface font-bold tracking-tight">
          Panen Telur Ayam Kampung &amp; Ras Pagi Hari Ini
        </h3>
<p class="font-body-md text-body-md text-on-surface-variant mt-2 max-w-xl">
          Setiap butir telur disortir higienis langsung dari kandang bertingkat bambu khas dataran tinggi Gisting. Telur utuh bercangkang cokelat pekat bebas antibiotik berbahaya siap dikirim ke dapur warga &amp; rumah makan.
        </p>
<div class="mt-4 flex flex-wrap items-center gap-4 text-label-sm font-label-sm text-on-surface-variant">
<span class="flex items-center gap-1"><span class="material-symbols-outlined text-secondary text-base">check_circle</span> Grade A Timbangan Presisi</span>
<span class="flex items-center gap-1"><span class="material-symbols-outlined text-secondary text-base">check_circle</span> Garansi Ganti Butir Pecah</span>
<span class="flex items-center gap-1"><span class="material-symbols-outlined text-secondary text-base">check_circle</span> Pengantaran Motor Keranjang Khusus</span>
</div>
</div>
<div class="md:col-span-5 h-64 md:h-full relative min-h-[220px]">
<img class="w-full h-full object-cover" data-alt="Close-up rustic photograph of stacked cardboard egg crates filled with fresh brown country chicken eggs at an Indonesian traditional open-air agricultural market in Tanggamus Lampung, warm natural morning sunlight casting soft golden shadows, wooden rustic tables and hand-chalked price signs in rupiah, authentic rural marketplace atmosphere." src="https://lh3.googleusercontent.com/aida-public/AB6AXuB4WyNfEs4mOCmiX4mY-eHeGr4BhHfZGgKbA7Oz6GdJCxZJS4ZG00gtCi28ySZOm0F40qwjDkHOcDSzq1tDKE6Xlc6AIwkCmfKKixxITpPL4YfFcZptMUsSa-Gmim9HxSME4uQymICYdKkL6SwwP57BcwK3nFan90hoKWamXX1VWakwwMTVyiyq6XwbD-aP8U9TvCsIFn7VqMRz0P33FqC1UmQVTuXqPrKq_3JeIyc"/>
</div>
</div>
</div>
<!-- Customer Orders Management Table -->
<div class="bg-surface-container-lowest rounded-xl shadow-sm p-6 flex flex-col space-y-4">
<!-- Table Header & Controls -->
<div class="flex flex-col sm:flex-row sm:items-center justify-between gap-4">
<div>
<div class="flex items-center gap-2">
<h2 class="font-headline-md text-headline-md text-on-surface">Daftar Pesanan Warga Tanggamus</h2>
<span class="px-2 py-0.5 rounded-full bg-primary-container text-on-primary-container font-label-sm text-label-sm font-bold">42 Aktif</span>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant">Kelola status penimbangan, kesiapan kurir, dan verifikasi pelunasan COD/Transfer.</p>
</div>
<!-- Search & Filters -->
<div class="flex items-center gap-2 flex-wrap">
<div class="relative">
<span class="material-symbols-outlined absolute left-3 top-2.5 text-on-surface-variant text-base">search</span>
<input class="pl-9 pr-3 py-1.5 rounded-xl bg-surface-container-low font-body-sm text-body-sm text-on-surface placeholder:text-on-surface-variant focus:outline-none focus:ring-2 focus:ring-primary-container" placeholder="Cari nama atau kecamatan..." type="text"/>
</div>
<select class="px-3 py-1.5 rounded-xl bg-surface-container-low font-label-sm text-label-sm text-on-surface focus:outline-none">
<option>Semua Wilayah (Gisting, Kota Agung, Pugung)</option>
<option>Gisting Bawah &amp; Atas</option>
<option>Kota Agung Barat &amp; Timur</option>
<option>Talang Padang</option>
</select>
<button class="p-2 rounded-xl bg-surface-container-low hover:bg-surface-container text-on-surface transition-colors" title="Export Rekap Penjualan">
<span class="material-symbols-outlined text-lg">download</span>
</button>
</div>
</div>
<!-- Responsive Table Wrapper -->
<div class="overflow-x-auto">
<table class="w-full text-left border-collapse">
<thead>
<tr class="bg-surface-container-low text-on-surface-variant font-label-sm text-label-sm uppercase tracking-wider">
<th class="p-3.5 rounded-l-lg">ID &amp; Waktu</th>
<th class="p-3.5">Nama Pembeli &amp; Lokasi</th>
<th class="p-3.5">Rincian Komoditas</th>
<th class="p-3.5">Total Bayar</th>
<th class="p-3.5">Metode Bayar</th>
<th class="p-3.5">Status Pesanan</th>
<th class="p-3.5 text-right rounded-r-lg">Aksi Pengelola</th>
</tr>
</thead>
<tbody class="divide-y divide-surface-container font-body-md text-body-md text-on-surface">
<!-- Row 1: Ibu Rina - Gisting Bawah -->
<tr class="hover:bg-surface-container-low/50 transition-colors">
<td class="p-3.5">
<span class="font-label-md text-label-md font-bold block text-on-surface">#TG-8821</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">07:12 WIB</span>
</td>
<td class="p-3.5">
<div class="flex items-start gap-2">
<div class="w-8 h-8 rounded-full bg-secondary-container text-on-secondary-container flex items-center justify-center font-bold text-label-sm shrink-0">
                  IR
                </div>
<div>
<span class="font-label-md text-label-md font-bold block text-on-surface">Ibu Rina (Rumah Kue)</span>
<span class="font-body-sm text-body-sm text-on-surface-variant flex items-center gap-1">
<span class="material-symbols-outlined text-xs text-primary">location_on</span>
                    Gisting Bawah, Jl. Raya Simpang
                  </span>
</div>
</div>
</td>
<td class="p-3.5">
<div class="font-body-sm text-body-sm">
<span class="font-bold text-on-surface">3 Karpet</span> Telur Ayam Ras
                <span class="block text-on-surface-variant">+ 1 Pack (10 butir) Bebek</span>
</div>
</td>
<td class="p-3.5">
<span class="font-label-lg text-label-lg font-bold text-on-surface block">Rp 188.000</span>
<span class="font-label-sm text-label-sm text-secondary font-medium">Bebas Ongkir Ring 1</span>
</td>
<td class="p-3.5">
<span class="inline-flex items-center gap-1 px-2.5 py-1 rounded-md bg-secondary-container text-on-secondary-container font-label-sm text-label-sm font-bold">
<span class="material-symbols-outlined text-xs">check</span> QRIS Lunas
              </span>
</td>
<td class="p-3.5">
<span class="inline-flex items-center gap-1.5 px-3 py-1 rounded-full bg-primary-container/20 text-on-primary-container font-label-sm text-label-sm font-bold">
<span class="w-1.5 h-1.5 rounded-full bg-primary animate-ping"></span>
                Sedang Dikemas
              </span>
</td>
<td class="p-3.5 text-right">
<div class="flex items-center justify-end gap-1.5">
<button class="p-1.5 rounded-lg bg-surface-container hover:bg-surface-container-high text-on-surface transition-colors" title="Cetak Nota">
<span class="material-symbols-outlined text-base">print</span>
</button>
<a class="p-1.5 rounded-lg bg-secondary-container text-on-secondary-container hover:bg-secondary-fixed transition-colors" href="https://wa.me/6281278900000?text=Halo%20Ibu%20Rina,%20pesanan%20telur%20TG-8821%20sedang%20kami%20kemas%20di%20Gudang%20Bang%20Zul" target="_blank" title="WhatsApp Pembeli">
<span class="material-symbols-outlined text-base">chat</span>
</a>
<button class="px-2.5 py-1.5 rounded-lg bg-primary-container text-on-primary-container font-label-sm text-label-sm font-bold shadow-sm hover:bg-primary-fixed-dim">
                  Siap Diambil
                </button>
</div>
</td>
</tr>
<!-- Row 2: Warung Barokah - Kota Agung -->
<tr class="hover:bg-surface-container-low/50 transition-colors">
<td class="p-3.5">
<span class="font-label-md text-label-md font-bold block text-on-surface">#TG-8820</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">06:55 WIB</span>
</td>
<td class="p-3.5">
<div class="flex items-start gap-2">
<div class="w-8 h-8 rounded-full bg-primary-fixed text-on-primary-fixed flex items-center justify-center font-bold text-label-sm shrink-0">
                  WB
                </div>
<div>
<span class="font-label-md text-label-md font-bold block text-on-surface">Warung Barokah (Grosir)</span>
<span class="font-body-sm text-body-sm text-on-surface-variant flex items-center gap-1">
<span class="material-symbols-outlined text-xs text-primary">location_on</span>
                    Kota Agung Pusat, Pasar Madang
                  </span>
</div>
</div>
</td>
<td class="p-3.5">
<div class="font-body-sm text-body-sm">
<span class="font-bold text-on-surface">15 Karpet</span> Telur Ayam Ras
                <span class="block text-on-surface-variant">Grosir Warung Kelontong</span>
</div>
</td>
<td class="p-3.5">
<span class="font-label-lg text-label-lg font-bold text-on-surface block">Rp 765.000</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">+ Rp 15rb Kurir Mobil</span>
</td>
<td class="p-3.5">
<span class="inline-flex items-center gap-1 px-2.5 py-1 rounded-md bg-surface-container text-on-surface font-label-sm text-label-sm font-semibold">
<span class="material-symbols-outlined text-xs">hourglass_empty</span> COD di Tempat
              </span>
</td>
<td class="p-3.5">
<span class="inline-flex items-center gap-1.5 px-3 py-1 rounded-full bg-secondary-container text-on-secondary-container font-label-sm text-label-sm font-bold">
<span class="material-symbols-outlined text-sm">two_wheeler</span>
                Diantar Kurir (Doni)
              </span>
</td>
<td class="p-3.5 text-right">
<div class="flex items-center justify-end gap-1.5">
<button class="p-1.5 rounded-lg bg-surface-container hover:bg-surface-container-high text-on-surface transition-colors" title="Cetak Nota">
<span class="material-symbols-outlined text-base">print</span>
</button>
<a class="p-1.5 rounded-lg bg-secondary-container text-on-secondary-container hover:bg-secondary-fixed transition-colors" href="https://wa.me/6281278900000?text=Halo%20Warung%20Barokah,%20Kurir%20Doni%20sedang%20menuju%20Kota%20Agung%20membawa%2015%20Karpet%20Telur." target="_blank" title="WhatsApp Pembeli">
<span class="material-symbols-outlined text-base">chat</span>
</a>
<button class="px-2.5 py-1.5 rounded-lg bg-surface-container-high text-on-surface font-label-sm text-label-sm font-bold hover:bg-surface-container-highest">
                  Lacak Rute
                </button>
</div>
</td>
</tr>
<!-- Row 3: Pakde Slamet - Talang Padang -->
<tr class="hover:bg-surface-container-low/50 transition-colors">
<td class="p-3.5">
<span class="font-label-md text-label-md font-bold block text-on-surface">#TG-8819</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">06:40 WIB</span>
</td>
<td class="p-3.5">
<div class="flex items-start gap-2">
<div class="w-8 h-8 rounded-full bg-tertiary-fixed text-on-tertiary-fixed flex items-center justify-center font-bold text-label-sm shrink-0">
                  PS
                </div>
<div>
<span class="font-label-md text-label-md font-bold block text-on-surface">Pakde Slamet (Martabak)</span>
<span class="font-body-sm text-body-sm text-on-surface-variant flex items-center gap-1">
<span class="material-symbols-outlined text-xs text-primary">location_on</span>
                    Talang Padang, Depan Kantor Pos
                  </span>
</div>
</div>
</td>
<td class="p-3.5">
<div class="font-body-sm text-body-sm">
<span class="font-bold text-on-surface">4 Pack (40 btr)</span> Telur Bebek Super
                <span class="block text-on-surface-variant">+ 1 Karpet Ras</span>
</div>
</td>
<td class="p-3.5">
<span class="font-label-lg text-label-lg font-bold text-on-surface block">Rp 172.000</span>
<span class="font-label-sm text-label-sm text-secondary font-medium">Pelanggan Harian</span>
</td>
<td class="p-3.5">
<span class="inline-flex items-center gap-1 px-2.5 py-1 rounded-md bg-secondary-container text-on-secondary-container font-label-sm text-label-sm font-bold">
<span class="material-symbols-outlined text-xs">account_balance</span> TF BRI Lunas
              </span>
</td>
<td class="p-3.5">
<span class="inline-flex items-center gap-1.5 px-3 py-1 rounded-full bg-surface-container-high text-on-surface-variant font-label-sm text-label-sm font-bold">
<span class="material-symbols-outlined text-sm">schedule</span>
                Menunggu Kurir
              </span>
</td>
<td class="p-3.5 text-right">
<div class="flex items-center justify-end gap-1.5">
<button class="p-1.5 rounded-lg bg-surface-container hover:bg-surface-container-high text-on-surface transition-colors" title="Cetak Nota">
<span class="material-symbols-outlined text-base">print</span>
</button>
<a class="p-1.5 rounded-lg bg-secondary-container text-on-secondary-container hover:bg-secondary-fixed transition-colors" href="https://wa.me/6281278900000" target="_blank" title="WhatsApp Pembeli">
<span class="material-symbols-outlined text-base">chat</span>
</a>
<button class="px-2.5 py-1.5 rounded-lg bg-primary-container text-on-primary-container font-label-sm text-label-sm font-bold shadow-sm hover:bg-primary-fixed-dim">
                  Panggil Kurir
                </button>
</div>
</td>
</tr>
<!-- Row 4: Ibu Maya - Pugung -->
<tr class="hover:bg-surface-container-low/50 transition-colors">
<td class="p-3.5">
<span class="font-label-md text-label-md font-bold block text-on-surface">#TG-8818</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">06:15 WIB</span>
</td>
<td class="p-3.5">
<div class="flex items-start gap-2">
<div class="w-8 h-8 rounded-full bg-secondary-container text-on-secondary-container flex items-center justify-center font-bold text-label-sm shrink-0">
                  IM
                </div>
<div>
<span class="font-label-md text-label-md font-bold block text-on-surface">Ibu Maya</span>
<span class="font-body-sm text-body-sm text-on-surface-variant flex items-center gap-1">
<span class="material-symbols-outlined text-xs text-primary">location_on</span>
                    Pugung, Dusun Way Halom
                  </span>
</div>
</div>
</td>
<td class="p-3.5">
<div class="font-body-sm text-body-sm">
<span class="font-bold text-on-surface">2 Karpet</span> Ayam Kampung Segar
                <span class="block text-on-surface-variant">Khusus Jamu &amp; Balita</span>
</div>
</td>
<td class="p-3.5">
<span class="font-label-lg text-label-lg font-bold text-on-surface block">Rp 140.000</span>
<span class="font-label-sm text-label-sm text-secondary font-medium">Bebas Ongkir</span>
</td>
<td class="p-3.5">
<span class="inline-flex items-center gap-1 px-2.5 py-1 rounded-md bg-secondary-container text-on-secondary-container font-label-sm text-label-sm font-bold">
<span class="material-symbols-outlined text-xs">check</span> QRIS Lunas
              </span>
</td>
<td class="p-3.5">
<span class="inline-flex items-center gap-1 px-3 py-1 rounded-full bg-secondary-container text-on-secondary-container font-label-sm text-label-sm font-bold">
<span class="material-symbols-outlined text-sm">task_alt</span>
                Terkirim &amp; Selesai
              </span>
</td>
<td class="p-3.5 text-right">
<div class="flex items-center justify-end gap-1.5">
<button class="p-1.5 rounded-lg bg-surface-container hover:bg-surface-container-high text-on-surface transition-colors" title="Cetak Nota">
<span class="material-symbols-outlined text-base">print</span>
</button>
<span class="font-label-sm text-label-sm text-secondary font-bold px-2">Bintang 5 • Sukses</span>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<!-- Table Footer / Pagination -->
<div class="flex flex-col sm:flex-row items-center justify-between gap-3 pt-3">
<span class="font-body-sm text-body-sm text-on-surface-variant">
        Menampilkan <strong>4</strong> dari <strong>42 pesanan</strong> hari ini di seputar Tanggamus
      </span>
<div class="flex items-center gap-1">
<button class="px-3 py-1.5 rounded-lg bg-surface-container-low text-on-surface-variant font-label-sm text-label-sm hover:bg-surface-container disabled:opacity-50" disabled="">
          Sebelumnya
        </button>
<button class="px-3 py-1.5 rounded-lg bg-primary-container text-on-primary-container font-label-sm text-label-sm font-bold">
          1
        </button>
<button class="px-3 py-1.5 rounded-lg bg-surface-container-low text-on-surface font-label-sm text-label-sm hover:bg-surface-container">
          2
        </button>
<button class="px-3 py-1.5 rounded-lg bg-surface-container-low text-on-surface font-label-sm text-label-sm hover:bg-surface-container">
          3
        </button>
<button class="px-3 py-1.5 rounded-lg bg-surface-container-low text-on-surface-variant font-label-sm text-label-sm hover:bg-surface-container">
          Selanjutnya
        </button>
</div>
</div>
</div>
<!-- Kurir Tanggamus Live Dispatch Map / Territory Overview -->
<div class="grid grid-cols-1 lg:grid-cols-12 gap-6">
<div class="lg:col-span-8 bg-surface-container-lowest p-6 rounded-xl shadow-sm flex flex-col justify-between">
<div class="flex items-center justify-between mb-4">
<div>
<span class="font-label-sm text-label-sm text-on-surface-variant uppercase tracking-wider block font-semibold">Distribusi Lapangan Hari Ini</span>
<h3 class="font-headline-sm text-headline-sm text-on-surface">Peta Jalur Antar Kurir (Wilayah Tanggamus)</h3>
</div>
<div class="flex items-center gap-2">
<span class="w-2.5 h-2.5 rounded-full bg-secondary animate-ping"></span>
<span class="font-label-sm text-label-sm font-bold text-on-surface">3 Armada Bergerak</span>
</div>
</div>
<!-- Real Map Location Component -->
<div class="w-full h-72 rounded-xl bg-cover bg-center relative overflow-hidden shadow-inner" data-location="Gisting, Tanggamus Regency, Lampung, Indonesia" style="background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuDS80RSTFSXhQrpsf9rdJjpuj-LMTFwPKU8KhiodTUOtwp-rOkXXJmLgjqtYkQVj4UuWxf8RPFwEOiR3ObMdN1IDJHxYxEWgU-J1qLG5CDu6NXiBaytP6E6x5v22nyao9EN07P09wGNK-JY8n8ruMZlW92xgv7fNKuLTABcpfFnAqiA1YNoP8AZphVREMmMTRehobwekwWH7FeBhDHKYJA2acYV1Jk6zzwCnjy4Fds')">
<div class="absolute bottom-3 left-3 bg-surface/90 backdrop-blur-md p-3 rounded-xl shadow-md max-w-xs">
<div class="flex items-center gap-2 mb-1">
<span class="material-symbols-outlined text-secondary text-base">near_me</span>
<span class="font-label-sm text-label-sm font-bold text-on-surface">Jalur Utama Jalan Lintas Barat</span>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant">Kurir Motor 01 saat ini melintasi Simpang Campang Gisting menuju Talang Padang.</p>
</div>
</div>
<div class="grid grid-cols-3 gap-3 mt-4 pt-1 font-label-sm text-label-sm">
<div class="p-2.5 rounded-lg bg-surface-container-low text-center">
<span class="block text-on-surface-variant">Rute 1 (Gisting - Kota Agung)</span>
<strong class="text-on-surface">19 Karpet Terantar</strong>
</div>
<div class="p-2.5 rounded-lg bg-surface-container-low text-center">
<span class="block text-on-surface-variant">Rute 2 (Talang Padang - Pugung)</span>
<strong class="text-on-surface">14 Karpet Terantar</strong>
</div>
<div class="p-2.5 rounded-lg bg-surface-container-low text-center">
<span class="block text-on-surface-variant">Pickup Langsung Toko</span>
<strong class="text-on-surface">9 Pembeli Ambil Sendiri</strong>
</div>
</div>
</div>
<!-- Quick Actions & Cetak Stiker Kasir -->
<div class="lg:col-span-4 bg-surface-container-lowest p-6 rounded-xl shadow-sm flex flex-col justify-between">
<div>
<div class="flex items-center gap-2 mb-3">
<div class="w-8 h-8 rounded-lg bg-secondary-container text-on-secondary-container flex items-center justify-center">
<span class="material-symbols-outlined text-base">receipt_long</span>
</div>
<h3 class="font-headline-sm text-headline-sm text-on-surface">Cetak Cepat Kasir</h3>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant mb-4">
          Cetak label thermal pengiriman karpet telur dengan stiker jaminan tidak pecah &amp; nota timbangan.
        </p>
<div class="space-y-2.5">
<button class="w-full p-3 rounded-xl bg-surface-container-low hover:bg-surface-container text-on-surface font-label-md text-label-md flex items-center justify-between transition-colors">
<span class="flex items-center gap-2">
<span class="material-symbols-outlined text-primary text-lg">label</span>
              Label Thermal 15 Pesanan Baru
            </span>
<span class="material-symbols-outlined text-sm">chevron_right</span>
</button>
<button class="w-full p-3 rounded-xl bg-surface-container-low hover:bg-surface-container text-on-surface font-label-md text-label-md flex items-center justify-between transition-colors">
<span class="flex items-center gap-2">
<span class="material-symbols-outlined text-secondary text-lg">description</span>
              Rekap Kas Penjualan Harian
            </span>
<span class="material-symbols-outlined text-sm">chevron_right</span>
</button>
<button class="w-full p-3 rounded-xl bg-surface-container-low hover:bg-surface-container text-on-surface font-label-md text-label-md flex items-center justify-between transition-colors">
<span class="flex items-center gap-2">
<span class="material-symbols-outlined text-on-surface-variant text-lg">share</span>
              Kirim Update Stok ke Grup WA Warga
            </span>
<span class="material-symbols-outlined text-sm">chevron_right</span>
</button>
</div>
</div>
<!-- Bang Zul Direct Hotline Card -->
<div class="mt-6 pt-4 rounded-xl bg-primary/10 p-4 flex items-center justify-between">
<div>
<span class="font-label-sm text-label-sm font-bold text-primary block">Bantuan Operasional Toko</span>
<span class="font-body-sm text-body-sm text-on-surface-variant">Admin Pasar: Kang Hendra (Gisting)</span>
</div>
<a class="w-9 h-9 rounded-full bg-primary-container text-on-primary-container flex items-center justify-center shadow hover:scale-105 transition-transform" href="https://wa.me/6281278900000" target="_blank">
<span class="material-symbols-outlined text-lg">support_agent</span>
</a>
</div>
</div>
</div>
</div></main></div></body></html>

<!-- Portal Kurir Tanggamus -->
<!DOCTYPE html>

<html lang="id"><head><meta charset="utf-8"/><meta content="width=device-width, initial-scale=1.0" name="viewport"/><meta content="web_dashboard" name="shell-type"/><link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" rel="stylesheet"/><link href="https://fonts.googleapis.com" rel="preconnect"/><link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/><link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&amp;family=Plus+Jakarta+Sans:wght@700;800&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/><style>@layer base{html,body{margin:0;padding:0;}body{overscroll-behavior:none;}main>:first-child{margin-top:0!important;}main>:last-child{margin-bottom:0!important;}}::-webkit-scrollbar{display:none;}</style><script src="https://cdn.tailwindcss.com"></script><script id="tailwind-config">tailwind.config={darkMode:"class",theme:{extend:{colors:{"on-primary-container":"#644000","on-secondary-fixed-variant":"#005312","surface":"#fcf9f8","on-tertiary-fixed-variant":"#3e4a41","on-secondary":"#ffffff","surface-container-lowest":"#ffffff","on-primary-fixed-variant":"#633f00","on-primary":"#ffffff","primary-container":"#f5a623","error":"#ba1a1a","tertiary-fixed":"#d9e6da","on-primary-fixed":"#291800","tertiary-fixed-dim":"#bdcabe","surface-container-high":"#eae7e7","surface-dim":"#dcd9d9","on-error-container":"#93000a","tertiary":"#556158","outline-variant":"#d7c3ae","secondary-container":"#a0f399","inverse-on-surface":"#f3f0f0","on-secondary-container":"#217128","background":"#fcf9f8","on-surface-variant":"#524534","on-error":"#ffffff","surface-variant":"#e4e2e1","surface-bright":"#fcf9f8","error-container":"#ffdad6","primary":"#835500","secondary-fixed":"#a3f69c","primary-fixed-dim":"#ffb955","inverse-surface":"#303030","on-background":"#1b1c1c","on-tertiary":"#ffffff","surface-tint":"#835500","on-tertiary-container":"#3e4a41","inverse-primary":"#ffb955","surface-container-low":"#f6f3f2","secondary-fixed-dim":"#88d982","on-surface":"#1b1c1c","tertiary-container":"#acb9ae","secondary":"#1b6d24","surface-container-highest":"#e4e2e1","surface-container":"#f0eded","primary-fixed":"#ffddb4","outline":"#857462","on-secondary-fixed":"#002204","on-tertiary-fixed":"#131e17"},borderRadius:{"DEFAULT":"0.25rem","lg":"0.5rem","xl":"0.75rem","full":"9999px"},spacing:{"gutter-desktop":"1.5rem","margin-desktop":"2.5rem","gutter":"1rem","space-lg":"1.5rem","space-xl":"2rem","margin":"1rem","space-md":"1rem","space-xs":"0.25rem","space-sm":"0.5rem"},fontFamily:{"body-md":["Inter"],"headline-lg-mobile":["Plus Jakarta Sans"],"headline-sm":["Plus Jakarta Sans"],"label-lg":["Inter"],"display-lg-mobile":["Plus Jakarta Sans"],"display-lg":["Plus Jakarta Sans"],"label-sm":["Inter"],"headline-lg":["Plus Jakarta Sans"],"stock-counter":["Inter"],"label-md":["Inter"],"headline-md":["Plus Jakarta Sans"],"body-sm":["Inter"],"price-display":["Plus Jakarta Sans"],"body-lg":["Inter"]},fontSize:{"body-md":["14px",{"lineHeight":"22px","fontWeight":"400"}],"headline-lg-mobile":["22px",{"lineHeight":"30px","letterSpacing":"0em","fontWeight":"700"}],"headline-sm":["16px",{"lineHeight":"24px","fontWeight":"700"}],"label-lg":["14px",{"lineHeight":"20px","fontWeight":"600"}],"display-lg-mobile":["30px",{"lineHeight":"38px","letterSpacing":"-0.01em","fontWeight":"800"}],"display-lg":["40px",{"lineHeight":"48px","letterSpacing":"-0.02em","fontWeight":"800"}],"label-sm":["11px",{"lineHeight":"14px","letterSpacing":"0.02em","fontWeight":"600"}],"headline-lg":["28px",{"lineHeight":"36px","letterSpacing":"-0.01em","fontWeight":"700"}],"stock-counter":["18px",{"lineHeight":"24px","letterSpacing":"0.01em","fontWeight":"700"}],"label-md":["12px",{"lineHeight":"16px","fontWeight":"600"}],"headline-md":["20px",{"lineHeight":"28px","fontWeight":"700"}],"body-sm":["12px",{"lineHeight":"18px","fontWeight":"400"}],"price-display":["22px",{"lineHeight":"28px","letterSpacing":"-0.02em","fontWeight":"800"}],"body-lg":["16px",{"lineHeight":"26px","fontWeight":"400"}]}}}}</script></head><body class="bg-surface font-body-md text-body-md text-on-surface antialiased"><aside class="fixed left-0 top-0 h-full w-64 bg-surface-container-low z-50 flex flex-col py-5 shadow-[0_4px_20px_-2px_rgba(245,166,35,0.08)]"><div class="px-5 mb-6 flex items-center gap-3"><img alt="Logo Bang Zul Egg Market" class="h-8 w-auto object-contain" src="https://lh3.googleusercontent.com/aida/ALJJyrAvuhgJbL1OqXYnorOpflEwk9ch2RB3i3nIpJf2khBHtFUraZYLjA49xnoYr5_XpY1inx_yvUKDG-f5ULodcAC4hoBl9QYWujU07wAAJsvNI88PefRZRNH2SgRzcvtvfP9LlMDgvobQRRrHxWwLlWY8MQoR1CS4kennwXqXJqn5PR3R5zkf-p4q0eleDblVHlCAtE__Wj8FbqU6db9zlBw02jnLdLpow_xGCN8RF4es"/><div class="flex flex-col"><span class="font-headline-sm text-headline-sm text-primary leading-tight">Bang Zul</span><span class="font-label-sm text-label-sm text-on-surface-variant">Sistem Operasional</span></div></div><div class="px-4 mb-4"><div class="p-2.5 rounded-xl bg-surface-container flex items-center gap-2"><span class="material-symbols-outlined text-secondary text-lg">pin_drop</span><div class="leading-none"><span class="font-label-sm text-label-sm font-bold block text-on-surface">Pos Tanggamus</span><span class="font-label-sm text-label-sm text-on-surface-variant">Gisting - Talang Padang</span></div></div></div><nav class="flex-1 px-3 space-y-1" data-active-classes="bg-primary-container text-on-primary-container font-bold"><a class="flex items-center gap-3 px-3 py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface font-label-md text-label-md transition-all" data-path="toko-bang-zul" href="#"><span class="material-symbols-outlined text-lg">storefront</span>Toko &amp; Inventori Bang Zul</a><a aria-current="page" class="flex items-center gap-3 px-3 py-2.5 rounded-xl transition-all bg-primary-container text-on-primary-container font-bold" data-path="kurir-tanggamus" href="#"><span class="material-symbols-outlined text-lg">two_wheeler</span>Pantau Kurir Lapangan</a><a class="flex items-center gap-3 px-3 py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface font-label-md text-label-md transition-all" data-path="admin-pasar" href="#"><span class="material-symbols-outlined text-lg">admin_panel_settings</span>Admin &amp; Kas Penjualan</a><a class="flex items-center gap-3 px-3 py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface font-label-md text-label-md transition-all" data-path="jadwal-panen-stok" href="#"><span class="material-symbols-outlined text-lg">egg</span>Timbangan &amp; Panen</a><a class="flex items-center gap-3 px-3 py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface font-label-md text-label-md transition-all" data-path="katalog-belanja" href="#"><span class="material-symbols-outlined text-lg">store</span>Lihat Toko Publik</a></nav><div class="px-4 pt-3 border-t border-surface-container-highest flex items-center justify-between"><div class="flex items-center gap-2"><img alt="Profile" class="w-8 h-8 rounded-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBu4cCay1o-kcZkrepBjdwRhNkTeb5NSNF4V20H1AoEXr4ahIrRP9SktX37TUve3u7us_GHnlm1279EoAyYcFxqZTZV4CIOdstOTCqIMcitiPTCwpWm4m2okjdh9z8S2I2n0sK1hb3y3ohWU84Tu6ZWNoxKL7D1NVLhMsBA3C6eHNQmukclnmKpMzHXssx-xtkh1wF2y2OFEDgXUgTPjjAfLabaOsUrz91MId6by4k"/><div class="leading-none"><span class="font-label-sm text-label-sm font-bold block text-on-surface">Bang Zul</span><span class="font-label-sm text-label-sm text-secondary">Owner &amp; Verifikator</span></div></div><a class="text-on-surface-variant hover:text-error" data-path="login-auth" href="#"><span class="material-symbols-outlined text-lg">logout</span></a></div></aside><div class="pl-64"><header class="fixed top-0 left-64 right-0 h-16 bg-surface/95 backdrop-blur-md shadow-[0_1px_8px_rgba(0,0,0,0.04)] z-40 px-6 flex items-center justify-between"><div class="flex items-center gap-3"><span class="inline-flex items-center px-2.5 py-1 rounded-full bg-secondary-container text-on-secondary-container font-label-sm text-label-sm font-semibold"><span class="w-1.5 h-1.5 rounded-full bg-secondary mr-1.5"></span>Sistem Operasional Aktif</span><span class="text-body-sm font-body-sm text-on-surface-variant hidden md:inline">Wilayah Gisting • Kota Agung • Talang Padang</span></div><div class="flex items-center gap-3"><a class="hidden sm:flex items-center gap-1 px-3 py-1.5 rounded-lg bg-surface-container text-on-surface font-label-sm text-label-sm hover:bg-surface-container-high" href="https://wa.me/6281278900000"><span class="material-symbols-outlined text-secondary text-sm">support_agent</span>CS Bang Zul</a><button class="p-2 rounded-full hover:bg-surface-container text-on-surface-variant" type="button"><span class="material-symbols-outlined text-xl">notifications</span></button><img alt="Profile" class="w-8 h-8 rounded-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBu4cCay1o-kcZkrepBjdwRhNkTeb5NSNF4V20H1AoEXr4ahIrRP9SktX37TUve3u7us_GHnlm1279EoAyYcFxqZTZV4CIOdstOTCqIMcitiPTCwpWm4m2okjdh9z8S2I2n0sK1hb3y3ohWU84Tu6ZWNoxKL7D1NVLhMsBA3C6eHNQmukclnmKpMzHXssx-xtkh1wF2y2OFEDgXUgTPjjAfLabaOsUrz91MId6by4k"/></div></header><main class="w-full pt-16 bg-surface px-6 py-6 min-h-screen"><div class="flex flex-col w-full pb-16 space-y-6">
<!-- TOP CONTEXT BAR: Driver Dispatch Status -->
<div class="bg-surface-container-lowest rounded-xl p-5 shadow-sm flex flex-col lg:flex-row lg:items-center lg:justify-between gap-4">
<div class="flex items-center gap-4">
<div class="relative">
<img class="w-14 h-14 rounded-full object-cover shadow-sm" data-alt="Potret wajah ramah kurir motor Indonesia memakai rompi hijau tua dan helm pengaman di daerah pedesaan perbukitan Gisting Tanggamus Lampung dengan cahaya pagi cerah" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCrwp37dmYiW0lmGnMGZBP6MMzUcfYzAc18ktAeTDcryGBEf3_TxJ2bA4ZNCR9Of_zL3T_dnnmb7wuxNRCiswIGXTb-lrRfhYe9vzHy3OXLn4U0ya8IFT8D5uWEE0bgBh3jOukZabJ_viW2DF1aSSz2f5qTOoM-kiIo7YIFoXpA9fGv4PlAb67sXvAMDEJj7CCmqNIUUZjHrvvwy44p7W6g9I2dSDq1WBRVyDl272c"/>
<span class="absolute bottom-0 right-0 w-4 h-4 bg-secondary rounded-full ring-2 ring-surface-container-lowest"></span>
</div>
<div class="flex flex-col">
<div class="flex items-center gap-2">
<h2 class="font-headline-md text-headline-md text-on-surface">Kang Asep Supriatna</h2>
<span class="inline-flex items-center px-2 py-0.5 rounded-full bg-secondary-container text-on-secondary-container font-label-sm text-label-sm font-bold">Armada 02 Telur Aman</span>
</div>
<div class="flex items-center gap-2 mt-0.5 text-on-surface-variant font-body-sm text-body-sm">
<span class="material-symbols-outlined text-sm text-primary">two_wheeler</span>
<span>Motor Box Suspensi Busa • Kloter Pagi (Gisting • Talang Padang • Kota Agung)</span>
</div>
</div>
</div>
<!-- Quick Stats Pill Ribbon -->
<div class="grid grid-cols-3 sm:flex sm:items-center gap-2 bg-surface-container-low p-1.5 rounded-xl">
<div class="bg-surface-container-lowest px-3.5 py-2 rounded-lg text-center sm:text-left shadow-sm">
<span class="block font-label-sm text-label-sm text-on-surface-variant uppercase tracking-wide">Target Hari Ini</span>
<span class="font-stock-counter text-stock-counter text-on-surface">6 <span class="font-body-sm text-body-sm font-normal text-on-surface-variant">Titik</span></span>
</div>
<div class="bg-surface-container-lowest px-3.5 py-2 rounded-lg text-center sm:text-left shadow-sm">
<span class="block font-label-sm text-label-sm text-on-surface-variant uppercase tracking-wide">Selesai Antar</span>
<span class="font-stock-counter text-stock-counter text-secondary">4 <span class="font-body-sm text-body-sm font-normal text-on-secondary-container">Aman</span></span>
</div>
<div class="bg-surface-container-lowest px-3.5 py-2 rounded-lg text-center sm:text-left shadow-sm">
<span class="block font-label-sm text-label-sm text-on-surface-variant uppercase tracking-wide">Garansi Pecah</span>
<span class="font-stock-counter text-stock-counter text-primary">0 <span class="font-body-sm text-body-sm font-normal text-on-surface-variant">Butir</span></span>
</div>
</div>
</div>
<!-- ROUTE MAP & LIVE ACTIVE DELIVERY BENTO -->
<div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-start">
<!-- LEFT 7 COLS: Active Priority Delivery & Queue -->
<div class="lg:col-span-7 space-y-6">
<!-- CURRENT ACTIVE DELIVERY CARD (Touch-Friendly Big UI) -->
<div class="bg-surface-container-lowest rounded-xl shadow-md overflow-hidden relative">
<div class="bg-primary-container px-5 py-3 flex items-center justify-between text-on-primary-container">
<div class="flex items-center gap-2">
<span class="animate-pulse w-2.5 h-2.5 rounded-full bg-error"></span>
<span class="font-label-lg text-label-lg font-bold tracking-tight">SEDANG DIANTAR SEKARANG</span>
</div>
<span class="font-label-md text-label-md bg-surface-container-lowest/80 px-2 py-0.5 rounded-md font-bold">Urutan #05</span>
</div>
<div class="p-5 sm:p-6 space-y-5">
<!-- Buyer Identity & Note -->
<div class="flex flex-col sm:flex-row sm:items-start justify-between gap-3">
<div>
<div class="flex items-center gap-2">
<span class="font-headline-sm text-headline-sm text-on-surface">Ibu Mega Lestari</span>
<span class="font-label-sm text-label-sm text-on-surface-variant bg-surface-container-high px-2 py-0.5 rounded">#BZ-8821</span>
</div>
<p class="font-body-md text-body-md text-on-surface-variant mt-1 flex items-start gap-1.5">
<span class="material-symbols-outlined text-base text-primary shrink-0 mt-0.5">location_on</span>
<span>Perumahan Gisting Permai Blok B No. 14, Gisting Bawah, Tanggamus (Pagar Cokelat samping pohon mangga)</span>
</p>
</div>
<div class="shrink-0">
<span class="inline-flex items-center gap-1 px-3 py-1.5 rounded-lg bg-surface-container-high font-label-md text-label-md text-primary font-bold">
<span class="material-symbols-outlined text-sm">schedule</span> Est. 7 Menit
              </span>
</div>
</div>
<!-- Product Manifest with Tactile Pill Items -->
<div class="bg-surface-container-low p-4 rounded-xl space-y-2">
<span class="font-label-sm text-label-sm text-on-surface-variant uppercase tracking-wider block">Muatan Telur di Box Motor:</span>
<div class="grid grid-cols-1 sm:grid-cols-2 gap-2">
<div class="flex items-center gap-2 bg-surface-container-lowest p-2 rounded-lg">
<span class="material-symbols-outlined text-primary text-xl">egg</span>
<div class="leading-tight">
<span class="font-label-md text-label-md font-bold block text-on-surface">2 Karpet Telur Ras Super</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">Grade A Segar Peternak</span>
</div>
</div>
<div class="flex items-center gap-2 bg-surface-container-lowest p-2 rounded-lg">
<span class="material-symbols-outlined text-secondary text-xl">egg_alt</span>
<div class="leading-tight">
<span class="font-label-md text-label-md font-bold block text-on-surface">1 Pack Telur Asin Masir</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">Isi 10 Butir Asli Gisting</span>
</div>
</div>
</div>
</div>
<!-- Payment Notice Box: High Contrast Callout -->
<div class="p-4 rounded-xl bg-amber-50 flex items-center justify-between flex-wrap gap-2 shadow-sm">
<div class="flex items-center gap-3">
<div class="w-10 h-10 rounded-full bg-primary-container text-on-primary-container flex items-center justify-center shrink-0">
<span class="material-symbols-outlined text-lg">payments</span>
</div>
<div>
<span class="font-label-sm text-label-sm text-on-surface-variant block uppercase tracking-wide">Tagihan COD (Bayar Tunai)</span>
<span class="font-price-display text-price-display text-on-surface">Rp 136.000</span>
</div>
</div>
<div class="bg-surface-container-lowest px-3 py-1.5 rounded-lg text-right">
<span class="font-label-sm text-label-sm text-error font-semibold block">Uang Pembeli: Rp 150.000</span>
<span class="font-label-sm text-label-sm text-secondary font-bold">Siapkan Kembalian: Rp 14.000</span>
</div>
</div>
<!-- Large Touch Actions for Couriers on Motorbike -->
<div class="grid grid-cols-1 sm:grid-cols-2 gap-3 pt-1">
<a class="h-12 flex items-center justify-center gap-2 rounded-xl bg-surface-container-high hover:bg-surface-container-highest text-on-surface font-label-lg text-label-lg shadow-sm transition-all active:scale-[0.98]" href="https://maps.google.com" target="_blank">
<span class="material-symbols-outlined text-secondary">near_me</span>
<span>Buka Google Maps</span>
</a>
<a class="h-12 flex items-center justify-center gap-2 rounded-xl bg-surface-container-high hover:bg-surface-container-highest text-on-surface font-label-lg text-label-lg shadow-sm transition-all active:scale-[0.98]" href="https://wa.me/6281234567890" target="_blank">
<span class="material-symbols-outlined text-secondary">chat</span>
<span>WhatsApp Ibu Mega</span>
</a>
</div>
<button class="w-full h-14 flex items-center justify-center gap-2 rounded-xl bg-primary-container hover:bg-on-primary-fixed-variant hover:text-on-primary text-on-primary-container font-label-lg text-label-lg shadow-md transition-all active:scale-[0.99]" onclick="document.getElementById('modal-selesai').classList.remove('hidden')" type="button">
<span class="material-symbols-outlined text-xl">photo_camera</span>
<span>Konfirmasi Selesai &amp; Ambil Foto Bukti Telur</span>
</button>
</div>
</div>
<!-- UPCOMING QUEUE LIST -->
<div class="space-y-3">
<div class="flex items-center justify-between px-1">
<h3 class="font-headline-sm text-headline-sm text-on-surface">Antrean Pengantaran Berikutnya</h3>
<span class="font-label-sm text-label-sm text-on-surface-variant font-semibold">1 Tujuan Tersisa Hari Ini</span>
</div>
<!-- Queue Item 2: Martabak Bang Ali -->
<div class="bg-surface-container-lowest p-5 rounded-xl shadow-sm hover:shadow-md transition-all space-y-3">
<div class="flex items-start justify-between gap-2">
<div class="space-y-1">
<div class="flex items-center gap-2">
<span class="w-6 h-6 rounded-full bg-surface-container-high text-on-surface font-label-sm text-label-sm flex items-center justify-center font-bold">06</span>
<span class="font-headline-sm text-headline-sm text-on-surface">Martabak Bang Ali</span>
<span class="font-label-sm text-label-sm bg-secondary-container text-on-secondary-container px-2 py-0.5 rounded-full font-bold">QRIS LUNAS</span>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant flex items-center gap-1">
<span class="material-symbols-outlined text-sm text-secondary">location_on</span>
                Ruko Depan Pasar Talang Padang (Sebelah Toko Emas Singgalang)
              </p>
</div>
<span class="font-label-sm text-label-sm text-on-surface-variant bg-surface-container px-2 py-1 rounded">#BZ-8824</span>
</div>
<div class="flex items-center justify-between text-body-sm text-body-sm bg-surface-container-low px-3 py-2 rounded-lg">
<div class="flex items-center gap-1.5">
<span class="material-symbols-outlined text-primary text-base">inventory_2</span>
<span class="font-semibold text-on-surface">5 Karpet (150 Butir) Telur Ayam Ras</span>
</div>
<span class="font-label-sm text-label-sm text-secondary font-bold">Bebas Ongkir Kloter</span>
</div>
<div class="flex items-center gap-2 pt-1">
<a class="flex-1 py-2 px-3 rounded-lg bg-surface-container-high text-center font-label-sm text-label-sm font-semibold hover:bg-surface-container-highest transition-colors" href="https://maps.google.com" target="_blank">
              Rute Talang Padang
            </a>
<button class="flex-1 py-2 px-3 rounded-lg bg-surface-container text-on-surface-variant text-center font-label-sm text-label-sm font-semibold hover:bg-surface-container-high transition-colors" type="button">
              Pindahkan Jadi Prioritas
            </button>
</div>
</div>
<!-- Completed Item Collapsed: Dapur Bunda Ani -->
<div class="bg-surface-container-low p-4 rounded-xl opacity-80 flex items-center justify-between">
<div class="flex items-center gap-3">
<span class="w-7 h-7 rounded-full bg-secondary-container text-secondary flex items-center justify-center shrink-0">
<span class="material-symbols-outlined text-base">check</span>
</span>
<div>
<div class="flex items-center gap-2">
<span class="font-label-md text-label-md font-bold text-on-surface">Dapur Bunda Ani</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">#BZ-8819</span>
</div>
<span class="font-body-sm text-body-sm text-on-surface-variant">Jl. Samudra, Kota Agung • Terkirim 08:45 WIB</span>
</div>
</div>
<span class="font-label-sm text-label-sm text-secondary font-bold">2 Mika Omega • Telur Utuh</span>
</div>
</div>
</div>
<!-- RIGHT 5 COLS: COD Cash Counter, Quick Claim & Map Overview -->
<div class="lg:col-span-5 space-y-6">
<!-- Tanggamus Visual Route Map Card -->
<div class="bg-surface-container-lowest rounded-xl shadow-sm overflow-hidden">
<div class="p-4 flex items-center justify-between bg-surface-container-low">
<div class="flex items-center gap-2">
<span class="material-symbols-outlined text-secondary text-base">map</span>
<span class="font-label-md text-label-md font-bold text-on-surface">Radar Posisi Kurir • Jalur Lintas Gisting</span>
</div>
<span class="font-label-sm text-label-sm text-on-surface-variant font-mono">GPS AKURAT (3m)</span>
</div>
<div class="w-full h-48 bg-cover bg-center relative" data-location="Gisting, Tanggamus, Lampung, Indonesia" style="">
<div class="absolute inset-0 bg-gradient-to-t from-on-surface/60 via-transparent to-transparent"></div>
<div class="absolute bottom-3 left-3 right-3 flex items-center justify-between text-surface-container-lowest">
<div class="flex items-center gap-1.5">
<span class="material-symbols-outlined text-primary-container text-sm">speed</span>
<span class="font-label-sm text-label-sm font-semibold drop-shadow">Kondisi Jalan: Lancar Kering</span>
</div>
<span class="bg-surface-container-lowest/90 text-on-surface font-label-sm text-label-sm px-2 py-0.5 rounded shadow">Pos Pantau Simpang Gisting</span>
</div>
</div>
</div>
<!-- KAS COD HARIAN: Rekapitulasi Kasir Lapangan -->
<div class="bg-surface-container-lowest rounded-xl shadow-sm p-5 space-y-4">
<div class="flex items-center justify-between">
<div class="flex items-center gap-2">
<div class="w-8 h-8 rounded-lg bg-surface-container-high flex items-center justify-center text-primary">
<span class="material-symbols-outlined text-lg">account_balance_wallet</span>
</div>
<h3 class="font-headline-sm text-headline-sm text-on-surface">Dompet Kas COD</h3>
</div>
<span class="font-label-sm text-label-sm bg-surface-container-high px-2 py-1 rounded text-on-surface font-mono">Wajib Setor Sore</span>
</div>
<div class="bg-surface-container-low p-4 rounded-xl space-y-1">
<span class="font-label-sm text-label-sm text-on-surface-variant block uppercase tracking-wide">Total Uang Tunai di Tas Pinggang:</span>
<div class="flex items-baseline justify-between">
<span class="font-display-lg text-display-lg text-secondary">Rp 842.000</span>
<span class="font-label-sm text-label-sm text-secondary font-bold">4 Nota Selesai</span>
</div>
</div>
<div class="space-y-2 text-body-sm text-body-sm">
<div class="flex justify-between text-on-surface-variant">
<span>+ Setoran #BZ-8812 (Pasar Talang Padang)</span>
<span class="font-mono text-on-surface font-semibold">Rp 310.000</span>
</div>
<div class="flex justify-between text-on-surface-variant">
<span>+ Setoran #BZ-8815 (Warung Bu RT 03)</span>
<span class="font-mono text-on-surface font-semibold">Rp 260.000</span>
</div>
<div class="flex justify-between text-on-surface-variant">
<span>+ Setoran #BZ-8818 (Kedai Kopi Tanggamus)</span>
<span class="font-mono text-on-surface font-semibold">Rp 272.000</span>
</div>
<div class="flex justify-between font-bold pt-2 text-on-surface">
<span>Tertagih Berikutnya (#BZ-8821)</span>
<span class="text-primary font-mono">+ Rp 136.000</span>
</div>
</div>
<button class="w-full py-2.5 rounded-lg bg-surface-container-high hover:bg-surface-container-highest text-on-surface font-label-md text-label-md flex items-center justify-center gap-1.5 transition-colors" type="button">
<span class="material-symbols-outlined text-base">receipt_long</span>
<span>Buka Rincian Nota Setor Kasir Bang Zul</span>
</button>
</div>
<!-- FITUR KLAIM TELUR RETAK / PECAH INSTAN -->
<div class="bg-surface-container-lowest rounded-xl shadow-sm p-5 space-y-4">
<div class="flex items-start justify-between">
<div class="flex items-center gap-2">
<div class="w-8 h-8 rounded-lg bg-error-container text-on-error-container flex items-center justify-center">
<span class="material-symbols-outlined text-lg">verified</span>
</div>
<div>
<h3 class="font-headline-sm text-headline-sm text-on-surface">Garansi Telur Utuh di Tempat</h3>
<p class="font-body-sm text-body-sm text-on-surface-variant">Pembeli menemukan retak? Klaim langsung!</p>
</div>
</div>
</div>
<div class="p-3.5 rounded-lg bg-surface-container-low text-on-surface-variant font-body-sm text-body-sm space-y-1">
<div class="flex items-center gap-2 text-on-surface font-semibold">
<span class="material-symbols-outlined text-secondary text-sm">inventory</span>
<span>Stok Cadangan Motor: 1 Karpet Busa Telur Telah Disiapkan</span>
</div>
<p>Jika pembeli komplain ada telur retak di perjalanan, kurir berhak mengganti langsung dari boks cadangan atau potong harga Rp 2.000/butir.</p>
</div>
<form class="space-y-3" onsubmit="event.preventDefault(); alert('Klaim retak berhasil dicatat! Otomatis disinkronkan ke pembukuan Toko Bang Zul.');">
<div class="grid grid-cols-2 gap-2">
<div>
<label class="font-label-sm text-label-sm text-on-surface-variant block mb-1">Jumlah Butir Retak</label>
<select class="w-full px-3 py-2 rounded-lg bg-surface-container-high text-on-surface font-label-md text-label-md focus:outline-none">
<option>1 Butir (-Rp 2.000)</option>
<option>2 Butir (-Rp 4.000)</option>
<option>3 Butir (-Rp 6.000)</option>
<option>Ganti Butir Baru dari Box</option>
</select>
</div>
<div>
<label class="font-label-sm text-label-sm text-on-surface-variant block mb-1">No. Nota Tujuan</label>
<select class="w-full px-3 py-2 rounded-lg bg-surface-container-high text-on-surface font-label-md text-label-md focus:outline-none">
<option>#BZ-8821 (Ibu Mega)</option>
<option>#BZ-8824 (Bang Ali)</option>
</select>
</div>
</div>
<button class="w-full py-2.5 rounded-lg bg-surface-container hover:bg-surface-container-high text-on-surface font-label-md text-label-md font-semibold flex items-center justify-center gap-1.5 transition-colors" type="submit">
<span class="material-symbols-outlined text-base text-primary">add_a_photo</span>
<span>Kirim Foto &amp; Potong Tagihan Instan</span>
</button>
</form>
</div>
</div>
</div>
<!-- MODAL / POPUP: KONFIRMASI TERIMA & FOTO BUKTI (Hidden by default, triggered by button) -->
<div class="hidden fixed inset-0 z-50 bg-inverse-surface/60 backdrop-blur-sm flex items-center justify-center p-4" id="modal-selesai">
<div class="bg-surface-container-lowest max-w-md w-full rounded-2xl p-6 shadow-xl space-y-5 animate-in fade-in zoom-in duration-150">
<div class="flex items-center justify-between">
<div class="flex items-center gap-2">
<span class="material-symbols-outlined text-secondary text-2xl">check_circle</span>
<h3 class="font-headline-sm text-headline-sm text-on-surface">Selesaikan Pesanan #BZ-8821</h3>
</div>
<button class="p-1 rounded-full hover:bg-surface-container text-on-surface-variant" onclick="document.getElementById('modal-selesai').classList.add('hidden')" type="button">
<span class="material-symbols-outlined">close</span>
</button>
</div>
<p class="font-body-md text-body-md text-on-surface-variant">
        Pastikan Ibu Mega Lestari telah memeriksa kondisi telur dan uang tunai <strong>Rp 136.000</strong> telah diterima dengan tepat.
      </p>
<div class="p-4 rounded-xl bg-surface-container-low text-center space-y-2">
<div class="w-16 h-16 mx-auto rounded-full bg-surface-container flex items-center justify-center text-primary cursor-pointer hover:bg-surface-container-high transition-colors">
<span class="material-symbols-outlined text-3xl">photo_camera</span>
</div>
<span class="font-label-md text-label-md font-bold block text-on-surface">Ambil Foto Telur di Tangan Pembeli</span>
<span class="font-body-sm text-body-sm text-on-surface-variant">Wajib foto telur dalam karpet sebagai jaminan mutu</span>
</div>
<div class="flex gap-2">
<button class="flex-1 py-3 rounded-xl bg-surface-container text-on-surface font-label-md text-label-md font-semibold" onclick="document.getElementById('modal-selesai').classList.add('hidden')" type="button">
          Batal
        </button>
<button class="flex-1 py-3 rounded-xl bg-primary-container text-on-primary-container font-label-md text-label-md font-bold shadow-md" onclick="alert('Pesanan #BZ-8821 Berhasil Diselesaikan! Lanjut ke Martabak Bang Ali.'); document.getElementById('modal-selesai').classList.add('hidden');" type="button">
          Simpan &amp; Selesai
        </button>
</div>
</div>
</div>
</div></main></div></body></html>

<!-- Beranda Bang Zul Egg Market -->
<!DOCTYPE html>

<html lang="id"><head><meta charset="utf-8"/><meta content="width=device-width, initial-scale=1.0" name="viewport"/><meta content="web_standard" name="shell-type"/><link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" rel="stylesheet"/><link href="https://fonts.googleapis.com" rel="preconnect"/><link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/><link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&amp;family=Plus+Jakarta+Sans:wght@700;800&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/><style>@layer base{html,body{margin:0;padding:0;}body{overscroll-behavior:none;}main>:first-child{margin-top:0!important;}main>:last-child{margin-bottom:0!important;}}::-webkit-scrollbar{display:none;}</style><script src="https://cdn.tailwindcss.com"></script><script id="tailwind-config">tailwind.config={darkMode:"class",theme:{extend:{colors:{"on-primary-container":"#644000","on-secondary-fixed-variant":"#005312","surface":"#fcf9f8","on-tertiary-fixed-variant":"#3e4a41","on-secondary":"#ffffff","surface-container-lowest":"#ffffff","on-primary-fixed-variant":"#633f00","on-primary":"#ffffff","primary-container":"#f5a623","error":"#ba1a1a","tertiary-fixed":"#d9e6da","on-primary-fixed":"#291800","tertiary-fixed-dim":"#bdcabe","surface-container-high":"#eae7e7","surface-dim":"#dcd9d9","on-error-container":"#93000a","tertiary":"#556158","outline-variant":"#d7c3ae","secondary-container":"#a0f399","inverse-on-surface":"#f3f0f0","on-secondary-container":"#217128","background":"#fcf9f8","on-surface-variant":"#524534","on-error":"#ffffff","surface-variant":"#e4e2e1","surface-bright":"#fcf9f8","error-container":"#ffdad6","primary":"#835500","secondary-fixed":"#a3f69c","primary-fixed-dim":"#ffb955","inverse-surface":"#303030","on-background":"#1b1c1c","on-tertiary":"#ffffff","surface-tint":"#835500","on-tertiary-container":"#3e4a41","inverse-primary":"#ffb955","surface-container-low":"#f6f3f2","secondary-fixed-dim":"#88d982","on-surface":"#1b1c1c","tertiary-container":"#acb9ae","secondary":"#1b6d24","surface-container-highest":"#e4e2e1","surface-container":"#f0eded","primary-fixed":"#ffddb4","outline":"#857462","on-secondary-fixed":"#002204","on-tertiary-fixed":"#131e17"},borderRadius:{"DEFAULT":"0.25rem","lg":"0.5rem","xl":"0.75rem","full":"9999px"},spacing:{"gutter-desktop":"1.5rem","margin-desktop":"2.5rem","gutter":"1rem","space-lg":"1.5rem","space-xl":"2rem","margin":"1rem","space-md":"1rem","space-xs":"0.25rem","space-sm":"0.5rem"},fontFamily:{"body-md":["Inter"],"headline-lg-mobile":["Plus Jakarta Sans"],"headline-sm":["Plus Jakarta Sans"],"label-lg":["Inter"],"display-lg-mobile":["Plus Jakarta Sans"],"display-lg":["Plus Jakarta Sans"],"label-sm":["Inter"],"headline-lg":["Plus Jakarta Sans"],"stock-counter":["Inter"],"label-md":["Inter"],"headline-md":["Plus Jakarta Sans"],"body-sm":["Inter"],"price-display":["Plus Jakarta Sans"],"body-lg":["Inter"]},fontSize:{"body-md":["14px",{"lineHeight":"22px","fontWeight":"400"}],"headline-lg-mobile":["22px",{"lineHeight":"30px","letterSpacing":"0em","fontWeight":"700"}],"headline-sm":["16px",{"lineHeight":"24px","fontWeight":"700"}],"label-lg":["14px",{"lineHeight":"20px","fontWeight":"600"}],"display-lg-mobile":["30px",{"lineHeight":"38px","letterSpacing":"-0.01em","fontWeight":"800"}],"display-lg":["40px",{"lineHeight":"48px","letterSpacing":"-0.02em","fontWeight":"800"}],"label-sm":["11px",{"lineHeight":"14px","letterSpacing":"0.02em","fontWeight":"600"}],"headline-lg":["28px",{"lineHeight":"36px","letterSpacing":"-0.01em","fontWeight":"700"}],"stock-counter":["18px",{"lineHeight":"24px","letterSpacing":"0.01em","fontWeight":"700"}],"label-md":["12px",{"lineHeight":"16px","fontWeight":"600"}],"headline-md":["20px",{"lineHeight":"28px","fontWeight":"700"}],"body-sm":["12px",{"lineHeight":"18px","fontWeight":"400"}],"price-display":["22px",{"lineHeight":"28px","letterSpacing":"-0.02em","fontWeight":"800"}],"body-lg":["16px",{"lineHeight":"26px","fontWeight":"400"}]}}}}</script></head><body class="bg-surface font-body-md text-body-md text-on-surface antialiased"><header class="fixed top-0 left-0 w-full z-50 bg-surface/95 backdrop-blur-md shadow-[0_4px_20px_-2px_rgba(245,166,35,0.12)]"><div class="bg-secondary text-on-secondary px-4 py-1.5"><div class="max-w-7xl mx-auto flex flex-col md:flex-row items-center justify-between gap-1 text-label-sm font-label-sm"><div class="flex items-center gap-2 text-center md:text-left"><span class="material-symbols-outlined text-secondary-fixed text-sm">local_shipping</span><span>Pengiriman Segar Hari Ini ke Wilayah Kota Agung, Gisting, Talang Padang, Wonosobo, Pringsewu sekitarnya | <strong class="text-secondary-fixed">Gratis Ongkir Min. 2 Karpet/Tray</strong></span></div><a class="flex items-center gap-1.5 hover:text-secondary-fixed transition-colors whitespace-nowrap" href="https://wa.me/6281278900000"><span class="material-symbols-outlined text-sm">chat</span><span>WhatsApp CS Hubungi Bang Zul: 0812-7890-XXXX</span></a></div></div><div class="max-w-7xl mx-auto px-4 lg:px-8 py-3 flex items-center justify-between gap-4"><div class="flex items-center gap-3 shrink-0"><img alt="Logo Bang Zul Egg Market" class="h-8 w-auto object-contain" src="https://lh3.googleusercontent.com/aida/ALJJyrAvuhgJbL1OqXYnorOpflEwk9ch2RB3i3nIpJf2khBHtFUraZYLjA49xnoYr5_XpY1inx_yvUKDG-f5ULodcAC4hoBl9QYWujU07wAAJsvNI88PefRZRNH2SgRzcvtvfP9LlMDgvobQRRrHxWwLlWY8MQoR1CS4kennwXqXJqn5PR3R5zkf-p4q0eleDblVHlCAtE__Wj8FbqU6db9zlBw02jnLdLpow_xGCN8RF4es"/><div class="flex flex-col"><span class="font-headline-md text-headline-md text-primary tracking-tight leading-none">Bang Zul</span><span class="font-label-sm text-label-sm text-secondary font-bold tracking-wider uppercase leading-none mt-0.5">Egg Market Tanggamus</span></div></div><div class="hidden lg:flex items-center gap-1.5 px-3 py-1.5 rounded-full bg-surface-container-low text-on-surface-variant font-label-sm text-label-sm shrink-0"><span class="material-symbols-outlined text-primary text-base">location_on</span><span class="max-w-[210px] truncate">Kab. Tanggamus (Gisting, Kota Agung &amp; Sekitarnya)</span></div><div class="hidden md:flex flex-1 max-w-md mx-2"><div class="relative w-full flex items-center"><span class="material-symbols-outlined absolute left-3 text-outline text-lg">search</span><input class="w-full pl-10 pr-4 py-2 rounded-full bg-surface-container-lowest text-body-sm font-body-sm text-on-surface placeholder:text-outline focus:outline-none focus:ring-2 focus:ring-primary-container shadow-[0_1px_4px_rgba(0,0,0,0.04)]" placeholder="Cari telur ayam ras, telur omega, telur bebek, puyuh..." type="text"/></div></div><div class="hidden xl:flex items-center p-1 rounded-xl bg-surface-container"><nav class="flex items-center gap-1" data-active-classes="bg-surface-container-lowest text-primary shadow-sm font-bold"><a class="px-3 py-1 rounded-lg text-label-sm font-label-sm text-on-surface-variant hover:text-on-surface transition-all" data-path="katalog-belanja" href="#">Belanja (Pembeli)</a><a class="px-3 py-1 rounded-lg text-label-sm font-label-sm text-on-surface-variant hover:text-on-surface transition-all" data-path="toko-bang-zul" href="#">Toko Bang Zul (Penjual)</a><a class="px-3 py-1 rounded-lg text-label-sm font-label-sm text-on-surface-variant hover:text-on-surface transition-all" data-path="kurir-tanggamus" href="#">Kurir Tanggamus</a><a class="px-3 py-1 rounded-lg text-label-sm font-label-sm text-on-surface-variant hover:text-on-surface transition-all" data-path="admin-pasar" href="#">Admin</a></nav></div><div class="flex items-center gap-2 md:gap-3 shrink-0"><button aria-label="Notifikasi Pesanan" class="p-2 rounded-full hover:bg-surface-container-high text-on-surface-variant relative" type="button"><span class="material-symbols-outlined text-xl">notifications</span><span class="absolute top-1.5 right-1.5 w-2 h-2 rounded-full bg-error"></span></button><a class="flex items-center gap-2 px-3 py-1.5 rounded-full bg-primary-container text-on-primary-container hover:bg-primary-fixed-dim transition-colors shadow-sm" data-path="keranjang-belanja" href="#"><span class="material-symbols-outlined text-lg">shopping_basket</span><span class="hidden sm:inline font-label-sm text-label-sm">Rp 84.000 (3 item)</span></a><div class="flex items-center gap-2 pl-1"><img alt="Profile" class="w-8 h-8 rounded-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBu4cCay1o-kcZkrepBjdwRhNkTeb5NSNF4V20H1AoEXr4ahIrRP9SktX37TUve3u7us_GHnlm1279EoAyYcFxqZTZV4CIOdstOTCqIMcitiPTCwpWm4m2okjdh9z8S2I2n0sK1hb3y3ohWU84Tu6ZWNoxKL7D1NVLhMsBA3C6eHNQmukclnmKpMzHXssx-xtkh1wF2y2OFEDgXUgTPjjAfLabaOsUrz91MId6by4k"/><span class="hidden 2xl:inline font-label-sm text-label-sm text-on-surface font-semibold">Bang Zul</span></div></div></div><div class="bg-surface-container-lowest shadow-[0_1px_4px_rgba(0,0,0,0.02)] overflow-x-auto"><div class="max-w-7xl mx-auto px-4 lg:px-8"><nav class="flex items-center gap-6 whitespace-nowrap py-2.5 text-label-sm font-label-sm" data-active-classes="text-primary font-bold border-b-2 border-primary"><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="katalog-belanja" href="#">Semua Produk</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="telur-ayam-ras" href="#">Telur Ayam Ras (Kiloan &amp; Karpet)</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="telur-ayam-kampung-omega" href="#">Telur Ayam Kampung &amp; Omega</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="telur-bebek-asin-mentah" href="#">Telur Bebek Asin &amp; Mentah</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="telur-puyuh" href="#">Telur Puyuh</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="paket-grosir-rumah-makan" href="#">Paket Grosir &amp; Rumah Makan</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1 flex items-center gap-1.5" data-path="jadwal-panen-stok" href="#"><span class="w-2 h-2 rounded-full bg-secondary inline-block animate-pulse"></span>Jadwal Panen &amp; Stok Realtime</a></nav></div></div></header><main class="w-full pt-36 bg-surface min-h-screen"><div class="flex flex-col w-full">
<!-- Announcement Banner -->
<section class="w-full bg-secondary text-on-secondary px-4 py-3 shadow-sm">
<div class="max-w-7xl mx-auto flex flex-col md:flex-row items-center justify-between gap-3 text-center md:text-left">
<div class="flex items-center gap-2">
<span class="material-symbols-outlined text-secondary-fixed text-xl animate-bounce">local_shipping</span>
<p class="font-label-md text-label-md">
<span class="font-bold text-secondary-fixed">Gratis Ongkir</span> ke Gisting, Talang Padang, Kota Agung, &amp; Wonosobo (Min. 2 Karpet/Tray) • <span class="font-bold underline">Garansi 100% Ganti Pecah di Tempat!</span>
</p>
</div>
<a class="inline-flex items-center gap-1.5 px-3 py-1 rounded-full bg-surface-container-lowest/15 hover:bg-surface-container-lowest/25 text-on-secondary text-label-sm font-label-sm transition-colors" href="https://wa.me/6281278900000">
<span class="material-symbols-outlined text-sm">chat</span>
<span>CS Bang Zul: <strong>0812-7890-XXXX</strong></span>
</a>
</div>
</section>
<!-- Local Status & Navigation Breadth -->
<section class="w-full bg-surface-container-lowest shadow-sm py-4 px-4 lg:px-8">
<div class="max-w-7xl mx-auto flex flex-wrap items-center justify-between gap-4">
<div class="flex items-center gap-3">
<div class="p-2 rounded-xl bg-primary-container/20 text-primary">
<span class="material-symbols-outlined text-2xl">switch_account</span>
</div>
<div>
<h2 class="font-headline-sm text-headline-sm text-on-surface leading-tight">Pasar Telur Segar Tanggamus</h2>
<p class="font-body-sm text-body-sm text-on-surface-variant flex items-center gap-1.5">
<span class="w-2 h-2 rounded-full bg-secondary inline-block"></span>
            Stok Panen Subuh 06.00 WIB Siap Diantar
          </p>
</div>
</div>
<div class="flex items-center flex-wrap gap-2.5">
<span class="px-3 py-1 rounded-full bg-secondary-container text-on-secondary-container font-label-sm text-label-sm flex items-center gap-1">
<span class="material-symbols-outlined text-sm">verified_user</span> Mitra Peternak Gisting
        </span>
<span class="px-3 py-1 rounded-full bg-surface-container-high text-on-surface-variant font-label-sm text-label-sm">
          ⚖️ Timbangan Digital Pas
        </span>
<span class="px-3 py-1 rounded-full bg-surface-container-high text-on-surface-variant font-label-sm text-label-sm">
          ⚡ Sameday Delivery
        </span>
</div>
</div>
</section>
<!-- Hero Section -->
<section class="relative w-full overflow-hidden bg-gradient-to-b from-surface via-surface-container-low to-surface py-12 lg:py-20 px-4 lg:px-8">
<div class="max-w-7xl mx-auto grid grid-cols-1 lg:grid-cols-12 gap-10 items-center">
<!-- Left Content -->
<div class="lg:col-span-7 flex flex-col space-y-6">
<div class="inline-flex items-center gap-2 self-start px-3.5 py-1.5 rounded-full bg-primary-fixed text-on-primary-fixed font-label-sm text-label-sm">
<span class="material-symbols-outlined text-base">sunny</span>
<span>Panen Segar Lereng Gunung Tanggamus</span>
</div>
<h1 class="font-display-lg text-display-lg text-on-surface font-extrabold tracking-tight">
          Telur Segar Langsung dari <span class="text-primary underline decoration-primary-container decoration-wavy decoration-2">Peternak Tanggamus</span>
</h1>
<p class="font-body-lg text-body-lg text-on-surface-variant max-w-2xl">
          Dipanen setiap subuh dari peternakan binaan lokal di lereng sejuk Gisting &amp; Talang Padang. Kuning telur oranye alami pekat, bebas bau apek, dan diantar kurir armada motor berperedam guncang hari ini juga.
        </p>
<!-- USP Badges -->
<div class="flex flex-wrap gap-2.5 pt-2">
<div class="flex items-center gap-1.5 px-3 py-2 rounded-xl bg-surface-container-lowest shadow-sm text-on-surface text-label-sm font-label-sm">
<span class="material-symbols-outlined text-secondary text-base">eco</span>
<span>Pakan Herbal Alami</span>
</div>
<div class="flex items-center gap-1.5 px-3 py-2 rounded-xl bg-surface-container-lowest shadow-sm text-on-surface text-label-sm font-label-sm">
<span class="material-symbols-outlined text-primary-container text-base">security</span>
<span>Garansi Ganti Pecah 100%</span>
</div>
<div class="flex items-center gap-1.5 px-3 py-2 rounded-xl bg-surface-container-lowest shadow-sm text-on-surface text-label-sm font-label-sm">
<span class="material-symbols-outlined text-secondary text-base">bolt</span>
<span>Pagi Panen Siang Tiba</span>
</div>
</div>
<!-- CTA Buttons -->
<div class="flex flex-col sm:flex-row items-stretch sm:items-center gap-3.5 pt-4">
<a class="px-6 py-3.5 rounded-xl bg-primary-container hover:bg-primary-fixed-dim text-on-primary-container font-headline-sm text-headline-sm flex items-center justify-center gap-2 shadow-md transition-all active:scale-95" href="#katalog-produk">
<span class="material-symbols-outlined">shopping_basket</span>
<span>Belanja Sekarang</span>
</a>
<a class="px-6 py-3.5 rounded-xl bg-surface-container-high hover:bg-surface-variant text-on-surface font-headline-sm text-headline-sm flex items-center justify-center gap-2 shadow-sm transition-all" href="#harga-pasar">
<span class="material-symbols-outlined">trending_up</span>
<span>Lihat Harga Harian Pasar</span>
</a>
</div>
<!-- Rating & Social Trust -->
<div class="flex items-center gap-4 pt-4 text-on-surface-variant text-body-sm font-body-sm">
<div class="flex -space-x-2">
<span class="inline-flex items-center justify-center w-8 h-8 rounded-full bg-secondary text-on-secondary font-bold text-xs">P</span>
<span class="inline-flex items-center justify-center w-8 h-8 rounded-full bg-primary-container text-on-primary font-bold text-xs">T</span>
<span class="inline-flex items-center justify-center w-8 h-8 rounded-full bg-surface-container-highest text-on-surface font-bold text-xs">G</span>
</div>
<div>
<div class="flex items-center text-primary-container">
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="ml-1 font-bold text-on-surface text-label-sm font-label-sm">4.9 / 5</span>
</div>
<p>Dipercaya 850+ ibu rumah tangga, warung &amp; pedagang martabak</p>
</div>
</div>
</div>
<!-- Right Visual Showcase -->
<div class="lg:col-span-5 relative">
<div class="relative mx-auto rounded-3xl overflow-hidden shadow-2xl bg-surface-container-lowest p-3">
<img class="w-full h-[420px] object-cover rounded-2xl" data-alt="A warm, atmospheric high quality photograph of stacks of fresh brown farm eggs arranged neatly in rustic cardboard egg trays on an authentic wooden market table in rural Tanggamus Lampung Indonesia, morning sunlight spilling over the smooth speckled shells, rustic chalkboard price tag nearby, farm fresh organic produce mood." src="https://lh3.googleusercontent.com/aida-public/AB6AXuDW4PDVK8joEh3cuAy6C4V09U5tfSSwyqUTpEJ_6xnoJxonajab9vTCHl8AG1KkJG7Vo81BCwDCo6wRDjspk28rKrhNwSsOfn3xYJtDFIh2i6qYLH7bmZZ-pD1ICLdDHL_QCps0uFsRuJ5M-_mgC8LCQqN0Etu1wMhVEgGz3t5BeXFKeutpKzTtjmSGAymTNxjpQWWg9g4mULji--aGUjhudd8q6w-6SoXNM-pWxKw"/>
<!-- Live Floating Card 1 -->
<div class="absolute top-6 left-6 max-w-[220px] p-3 rounded-2xl bg-surface-container-lowest/95 backdrop-blur-md shadow-lg text-on-surface space-y-1">
<div class="flex items-center gap-1.5 text-secondary font-label-sm text-label-sm">
<span class="w-2 h-2 rounded-full bg-secondary animate-ping"></span>
<span>Harga Update 07:00</span>
</div>
<p class="font-headline-sm text-headline-sm text-primary leading-tight">Rp 52.000</p>
<p class="text-body-sm font-body-sm text-on-surface-variant">/ Karpet (Isi 30 Butir)</p>
</div>
<!-- Live Floating Card 2 -->
<div class="absolute bottom-6 right-6 p-3.5 rounded-2xl bg-surface-container-lowest/95 backdrop-blur-md shadow-lg text-on-surface flex items-center gap-3">
<div class="w-10 h-10 rounded-xl bg-secondary-container flex items-center justify-center text-on-secondary-container">
<span class="material-symbols-outlined">motorcycle</span>
</div>
<div>
<p class="font-label-sm text-label-sm font-bold text-on-surface">Kurir Standby</p>
<p class="text-body-sm font-body-sm text-secondary">Rute Gisting &amp; Sekitar</p>
</div>
</div>
</div>
</div>
</div>
</section>
<!-- Section: Kategori Pilihan -->
<section class="w-full py-14 px-4 lg:px-8 bg-surface">
<div class="max-w-7xl mx-auto space-y-8">
<div class="flex flex-col md:flex-row md:items-end justify-between gap-4">
<div>
<span class="font-label-sm text-label-sm font-bold uppercase tracking-wider text-secondary">Kategori Pilihan</span>
<h2 class="font-headline-lg text-headline-lg text-on-surface mt-1">Pilihan Jenis Telur Peternakan</h2>
<p class="font-body-md text-body-md text-on-surface-variant max-w-xl">Pilih kategori telur bermutu tinggi untuk konsumsi harian keluarga, toko kelontong, maupun usaha kuliner lokal.</p>
</div>
<a class="inline-flex items-center gap-1 text-primary hover:text-primary-container font-label-lg text-label-lg transition-colors" href="#katalog-produk">
<span>Lihat Semua Katalog</span>
<span class="material-symbols-outlined text-sm">arrow_forward</span>
</a>
</div>
<div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-5">
<!-- Category 1 -->
<div class="p-5 rounded-2xl bg-surface-container-lowest shadow-sm hover:shadow-md transition-all group cursor-pointer flex flex-col justify-between">
<div class="space-y-3">
<div class="w-12 h-12 rounded-xl bg-primary-fixed flex items-center justify-center text-primary group-hover:scale-110 transition-transform">
<span class="material-symbols-outlined text-2xl">egg</span>
</div>
<h3 class="font-headline-sm text-headline-sm text-on-surface">Telur Ayam Ras</h3>
<p class="font-body-sm text-body-sm text-on-surface-variant">Paling laris untuk masak harian &amp; usaha kuliner martabak. Tersedia kiloan maupun tray karpet 30 butir.</p>
</div>
<div class="mt-4 pt-3 flex items-center justify-between text-secondary font-label-sm text-label-sm">
<span>Stok: 140 Karpet</span>
<span class="material-symbols-outlined text-base">chevron_right</span>
</div>
</div>
<!-- Category 2 -->
<div class="p-5 rounded-2xl bg-surface-container-lowest shadow-sm hover:shadow-md transition-all group cursor-pointer flex flex-col justify-between">
<div class="space-y-3">
<div class="w-12 h-12 rounded-xl bg-secondary-fixed flex items-center justify-center text-secondary group-hover:scale-110 transition-transform">
<span class="material-symbols-outlined text-2xl">health_and_safety</span>
</div>
<h3 class="font-headline-sm text-headline-sm text-on-surface">Telur Ayam Kampung</h3>
<p class="font-body-sm text-body-sm text-on-surface-variant">Asli pakan liar &amp; semi-intensif. Kuning pekat tinggi nutrisi untuk MPASI balita, stamina, dan seduhan jamu.</p>
</div>
<div class="mt-4 pt-3 flex items-center justify-between text-secondary font-label-sm text-label-sm">
<span>Stok: 85 Pack</span>
<span class="material-symbols-outlined text-base">chevron_right</span>
</div>
</div>
<!-- Category 3 -->
<div class="p-5 rounded-2xl bg-surface-container-lowest shadow-sm hover:shadow-md transition-all group cursor-pointer flex flex-col justify-between">
<div class="space-y-3">
<div class="w-12 h-12 rounded-xl bg-tertiary-fixed flex items-center justify-center text-tertiary group-hover:scale-110 transition-transform">
<span class="material-symbols-outlined text-2xl">water_drop</span>
</div>
<h3 class="font-headline-sm text-headline-sm text-on-surface">Telur Bebek Tambak</h3>
<p class="font-body-sm text-body-sm text-on-surface-variant">Cangkang hijau toska khas pesisir Kota Agung. Kuning berminyak gurih, pas untuk telur asin dan adonan martabak.</p>
</div>
<div class="mt-4 pt-3 flex items-center justify-between text-secondary font-label-sm text-label-sm">
<span>Stok: 60 Pack</span>
<span class="material-symbols-outlined text-base">chevron_right</span>
</div>
</div>
<!-- Category 4 -->
<div class="p-5 rounded-2xl bg-surface-container-lowest shadow-sm hover:shadow-md transition-all group cursor-pointer flex flex-col justify-between">
<div class="space-y-3">
<div class="w-12 h-12 rounded-xl bg-surface-container-high flex items-center justify-center text-on-surface-variant group-hover:scale-110 transition-transform">
<span class="material-symbols-outlined text-2xl">grain</span>
</div>
<h3 class="font-headline-sm text-headline-sm text-on-surface">Telur Puyuh</h3>
<p class="font-body-sm text-body-sm text-on-surface-variant">Butir corak bersih, padat gizi, dan segar gurih. Cocok untuk hidangan sup, balado, sate angkringan, dan cemilan.</p>
</div>
<div class="mt-4 pt-3 flex items-center justify-between text-secondary font-label-sm text-label-sm">
<span>Stok: 95 Mika</span>
<span class="material-symbols-outlined text-base">chevron_right</span>
</div>
</div>
</div>
</div>
</section>
<!-- Section: Produk Unggulan -->
<section class="w-full py-16 px-4 lg:px-8 bg-surface-container-low" id="katalog-produk">
<div class="max-w-7xl mx-auto space-y-8">
<div class="flex flex-col md:flex-row md:items-end justify-between gap-4">
<div>
<div class="inline-flex items-center gap-1.5 px-3 py-1 rounded-full bg-secondary-container text-on-secondary-container font-label-sm text-label-sm mb-2">
<span class="w-2 h-2 rounded-full bg-secondary animate-pulse"></span>
<span>Stok Segar Baru Tiba Pagi Ini (06.00 WIB)</span>
</div>
<h2 class="font-headline-lg text-headline-lg text-on-surface">Produk Telur Unggulan Hari Ini</h2>
<p class="font-body-md text-body-md text-on-surface-variant">Timbangan presisi digital, garansi cangkang utuh tanpa retak sampai pintu Anda.</p>
</div>
<!-- Filter Pill Chips -->
<div class="flex items-center gap-2 overflow-x-auto pb-1">
<button class="px-4 py-1.5 rounded-full bg-primary-container text-on-primary-container font-label-sm text-label-sm shadow-sm font-bold">Semua</button>
<button class="px-4 py-1.5 rounded-full bg-surface-container-lowest hover:bg-surface-container text-on-surface-variant font-label-sm text-label-sm">Karpet / Krat</button>
<button class="px-4 py-1.5 rounded-full bg-surface-container-lowest hover:bg-surface-container text-on-surface-variant font-label-sm text-label-sm">Pack Mika</button>
<button class="px-4 py-1.5 rounded-full bg-surface-container-lowest hover:bg-surface-container text-on-surface-variant font-label-sm text-label-sm">Grosir Warung</button>
</div>
</div>
<!-- Product Cards Grid -->
<div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
<!-- Card 1 -->
<div class="rounded-2xl bg-surface-container-lowest overflow-hidden shadow-sm hover:shadow-lg transition-all flex flex-col justify-between group">
<div>
<div class="relative w-full h-48 overflow-hidden bg-surface-container">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" data-alt="Close up shot of stacked cardboard egg trays loaded with fresh speckled brown chicken eggs at an Indonesian village egg depot, warm golden natural lighting, clean presentation, soft organic farm aesthetic." src="https://lh3.googleusercontent.com/aida-public/AB6AXuCzy2TvlNjGHc7DdIMZ8MbqGhCPwsUb26X2jytNt8BZOe1DVJS-_8yh3t06_gJpl5XPTTJw-fWh-tAUJtgmITeVJ3w1AB-jAF9g_tCsxL1KTio5KKpk5zjDGYhOh51Q9nPHwMrc_8uCilL6nCzRv2YXOGw-CpcztGnbVcuNAOzv7mlzMCzwrw9c41y0ekkKOAZ5ntkgvRj0icZlFxxXeAXGiXiOXCaxhopAh4BU9rs"/>
<span class="absolute top-3 left-3 px-2.5 py-1 rounded-lg bg-primary-container text-on-primary-container font-label-sm text-label-sm font-bold shadow-sm">
                Paling Laris 🔥
              </span>
<span class="absolute bottom-3 right-3 px-2 py-0.5 rounded-md bg-inverse-surface/80 text-inverse-on-surface font-label-sm text-label-sm">
                ±1.85 kg / tray
              </span>
</div>
<div class="p-4 space-y-2">
<h3 class="font-headline-sm text-headline-sm text-on-surface leading-snug">Telur Ayam Ras Super (Karpet 30 Butir)</h3>
<p class="font-body-sm text-body-sm text-on-surface-variant">Cangkang tebal kecokelatan, kuning telur padat tidak mudah pecah.</p>
<div class="flex items-center gap-1.5 text-secondary font-label-sm text-label-sm pt-1">
<span class="material-symbols-outlined text-sm">inventory_2</span>
<span>Tersedia 140 Karpet</span>
</div>
<div class="pt-2">
<p class="font-price-display text-price-display text-primary">Rp 52.000 <span class="font-body-sm text-body-sm text-on-surface-variant font-normal">/ karpet</span></p>
</div>
</div>
</div>
<div class="p-4 pt-0 space-y-3">
<!-- Stepper -->
<div class="flex items-center justify-between p-1.5 rounded-xl bg-surface-container-low">
<button class="w-8 h-8 rounded-lg bg-surface-container-lowest flex items-center justify-center text-on-surface hover:bg-surface-container-high transition-colors text-sm font-bold" onclick="decrement('qty-1')">-</button>
<span class="font-stock-counter text-stock-counter text-on-surface" id="qty-1">1</span>
<button class="w-8 h-8 rounded-lg bg-surface-container-lowest flex items-center justify-center text-on-surface hover:bg-surface-container-high transition-colors text-sm font-bold" onclick="increment('qty-1')">+</button>
</div>
<button class="w-full py-2.5 rounded-xl bg-primary-container hover:bg-primary-fixed-dim text-on-primary-container font-label-lg text-label-lg flex items-center justify-center gap-2 shadow-sm transition-all active:scale-95">
<span class="material-symbols-outlined text-lg">add_shopping_cart</span>
<span>Tambah ke Keranjang</span>
</button>
</div>
</div>
<!-- Card 2 -->
<div class="rounded-2xl bg-surface-container-lowest overflow-hidden shadow-sm hover:shadow-lg transition-all flex flex-col justify-between group">
<div>
<div class="relative w-full h-48 overflow-hidden bg-surface-container">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" data-alt="Beautiful organic farm scene showing a woven bamboo basket filled with fresh speckled free range village chicken eggs cushioned in dry golden straw on an old rustic wooden table, peaceful tropical greenery in background." src="https://lh3.googleusercontent.com/aida-public/AB6AXuA0bLZvYWVWt5eAv3HY7J5WhrjzBes9dAsTkQlUBjkSR7KCG6XCN2xqcuuHsdfXiKgFT6Zc8YRmbMraafNWIzHFiWHJZmwjnHPS3e8Tby4TNQZvGGwEvdSo8RP2DTgbpe2NYHMplnFB1AsnJgAlFijiCCkiWeO5Z7u8S4Slzyc1rAZ9MxStmVfK8xvY8zZcmDPtoZk2oXdCNEwX8h3xydsJdtEAByXOYwb_kQMtnBI"/>
<span class="absolute top-3 left-3 px-2.5 py-1 rounded-lg bg-secondary text-on-secondary font-label-sm text-label-sm font-bold shadow-sm">
                Nutrisi Tinggi 🌱
              </span>
<span class="absolute bottom-3 right-3 px-2 py-0.5 rounded-md bg-inverse-surface/80 text-inverse-on-surface font-label-sm text-label-sm">
                Pack Mika 10 Btr
              </span>
</div>
<div class="p-4 space-y-2">
<h3 class="font-headline-sm text-headline-sm text-on-surface leading-snug">Telur Ayam Kampung Asli &amp; Omega-3</h3>
<p class="font-body-sm text-body-sm text-on-surface-variant">Kuning telur oranye cerah alami. Ideal untuk minuman jamu &amp; kesehatan.</p>
<div class="flex items-center gap-1.5 text-secondary font-label-sm text-label-sm pt-1">
<span class="material-symbols-outlined text-sm">inventory_2</span>
<span>Tersedia 85 Pack</span>
</div>
<div class="pt-2">
<p class="font-price-display text-price-display text-primary">Rp 38.000 <span class="font-body-sm text-body-sm text-on-surface-variant font-normal">/ pack</span></p>
</div>
</div>
</div>
<div class="p-4 pt-0 space-y-3">
<div class="flex items-center justify-between p-1.5 rounded-xl bg-surface-container-low">
<button class="w-8 h-8 rounded-lg bg-surface-container-lowest flex items-center justify-center text-on-surface hover:bg-surface-container-high transition-colors text-sm font-bold" onclick="decrement('qty-2')">-</button>
<span class="font-stock-counter text-stock-counter text-on-surface" id="qty-2">1</span>
<button class="w-8 h-8 rounded-lg bg-surface-container-lowest flex items-center justify-center text-on-surface hover:bg-surface-container-high transition-colors text-sm font-bold" onclick="increment('qty-2')">+</button>
</div>
<button class="w-full py-2.5 rounded-xl bg-primary-container hover:bg-primary-fixed-dim text-on-primary-container font-label-lg text-label-lg flex items-center justify-center gap-2 shadow-sm transition-all active:scale-95">
<span class="material-symbols-outlined text-lg">add_shopping_cart</span>
<span>Tambah ke Keranjang</span>
</button>
</div>
</div>
<!-- Card 3 -->
<div class="rounded-2xl bg-surface-container-lowest overflow-hidden shadow-sm hover:shadow-lg transition-all flex flex-col justify-between group">
<div>
<div class="relative w-full h-48 overflow-hidden bg-surface-container">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" data-alt="Rustic wooden crates lined with dry straw displaying smooth pale teal duck eggs alongside speckled quail eggs at an open air market in Indonesia, hand-written wooden price signage, authentic warm morning light." src="https://lh3.googleusercontent.com/aida-public/AB6AXuBFtmDgxcqzzcow4x5Xa7-IwXuRtfXT9OpcNacMKQKYCkUZrESSuoPHLYENtvrTM-6Q_Z50p7WezL-3DnIBpu3e_M13HzvBNrLkYa_SQec24Pf-NIZiKZqhHxxNjGn2moWQVNpcsv2TQbuYIbg74TdOLKrH7YI8_IefxuGjVAr9THINRc3_bBmUeI-rdmrSpCgSuMT6dSAXSWxOBDk1LNKzvHjIWVOVZK9rC7RRMAc"/>
<span class="absolute top-3 left-3 px-2.5 py-1 rounded-lg bg-tertiary text-on-tertiary font-label-sm text-label-sm font-bold shadow-sm">
                Kuning Berminyak 🥚
              </span>
<span class="absolute bottom-3 right-3 px-2 py-0.5 rounded-md bg-inverse-surface/80 text-inverse-on-surface font-label-sm text-label-sm">
                Pack Mika 10 Btr
              </span>
</div>
<div class="p-4 space-y-2">
<h3 class="font-headline-sm text-headline-sm text-on-surface leading-snug">Telur Bebek Tambak Segar / Mentah</h3>
<p class="font-body-sm text-body-sm text-on-surface-variant">Dari peternak bebek air tawar Kota Agung. Gurih &amp; pulen pekat.</p>
<div class="flex items-center gap-1.5 text-secondary font-label-sm text-label-sm pt-1">
<span class="material-symbols-outlined text-sm">inventory_2</span>
<span>Tersedia 60 Pack</span>
</div>
<div class="pt-2">
<p class="font-price-display text-price-display text-primary">Rp 32.000 <span class="font-body-sm text-body-sm text-on-surface-variant font-normal">/ pack</span></p>
</div>
</div>
</div>
<div class="p-4 pt-0 space-y-3">
<div class="flex items-center justify-between p-1.5 rounded-xl bg-surface-container-low">
<button class="w-8 h-8 rounded-lg bg-surface-container-lowest flex items-center justify-center text-on-surface hover:bg-surface-container-high transition-colors text-sm font-bold" onclick="decrement('qty-3')">-</button>
<span class="font-stock-counter text-stock-counter text-on-surface" id="qty-3">1</span>
<button class="w-8 h-8 rounded-lg bg-surface-container-lowest flex items-center justify-center text-on-surface hover:bg-surface-container-high transition-colors text-sm font-bold" onclick="increment('qty-3')">+</button>
</div>
<button class="w-full py-2.5 rounded-xl bg-primary-container hover:bg-primary-fixed-dim text-on-primary-container font-label-lg text-label-lg flex items-center justify-center gap-2 shadow-sm transition-all active:scale-95">
<span class="material-symbols-outlined text-lg">add_shopping_cart</span>
<span>Tambah ke Keranjang</span>
</button>
</div>
</div>
<!-- Card 4 -->
<div class="rounded-2xl bg-surface-container-lowest overflow-hidden shadow-sm hover:shadow-lg transition-all flex flex-col justify-between group">
<div>
<div class="relative w-full h-48 overflow-hidden bg-surface-container">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" data-alt="Dozens of small speckled fresh quail eggs resting in a rustic handcrafted shallow wooden bowl and wooden crate over burlap cloth, clean bright morning lighting, country kitchen egg market feel." src="https://lh3.googleusercontent.com/aida-public/AB6AXuDLQKDMxOiGqw5b0Ph_Y-XIr483KaUQybfvMCtM0Eqsl3iP-sv4zfvfHH0uFUs4j8-e9GSDOA69q8KfZv32a6Owl1mVxG4dQyC9T3Xx8CrM_Hc9K2DANfog8I_6E4A-s2YevVs-gxff2QByX_noV9XU6NnB8C33gCxAhUmHxLt6UyffNB20Ybq8AytEcjySJz0jr0FkujoqHvixPWhxgBASTaVlE9PufRv32bjEd6w"/>
<span class="absolute top-3 left-3 px-2.5 py-1 rounded-lg bg-surface-container-highest text-on-surface font-label-sm text-label-sm font-bold shadow-sm">
                Segar Gurih 🥣
              </span>
<span class="absolute bottom-3 right-3 px-2 py-0.5 rounded-md bg-inverse-surface/80 text-inverse-on-surface font-label-sm text-label-sm">
                Mika 50 Butir
              </span>
</div>
<div class="p-4 space-y-2">
<h3 class="font-headline-sm text-headline-sm text-on-surface leading-snug">Telur Puyuh Peternak Wonosobo</h3>
<p class="font-body-sm text-body-sm text-on-surface-variant">Dipanen bersih bebas kotoran cangkang. Sangat cocok untuk lauk sup keluarga.</p>
<div class="flex items-center gap-1.5 text-secondary font-label-sm text-label-sm pt-1">
<span class="material-symbols-outlined text-sm">inventory_2</span>
<span>Tersedia 95 Mika</span>
</div>
<div class="pt-2">
<p class="font-price-display text-price-display text-primary">Rp 22.000 <span class="font-body-sm text-body-sm text-on-surface-variant font-normal">/ mika</span></p>
</div>
</div>
</div>
<div class="p-4 pt-0 space-y-3">
<div class="flex items-center justify-between p-1.5 rounded-xl bg-surface-container-low">
<button class="w-8 h-8 rounded-lg bg-surface-container-lowest flex items-center justify-center text-on-surface hover:bg-surface-container-high transition-colors text-sm font-bold" onclick="decrement('qty-4')">-</button>
<span class="font-stock-counter text-stock-counter text-on-surface" id="qty-4">1</span>
<button class="w-8 h-8 rounded-lg bg-surface-container-lowest flex items-center justify-center text-on-surface hover:bg-surface-container-high transition-colors text-sm font-bold" onclick="increment('qty-4')">+</button>
</div>
<button class="w-full py-2.5 rounded-xl bg-primary-container hover:bg-primary-fixed-dim text-on-primary-container font-label-lg text-label-lg flex items-center justify-center gap-2 shadow-sm transition-all active:scale-95">
<span class="material-symbols-outlined text-lg">add_shopping_cart</span>
<span>Tambah ke Keranjang</span>
</button>
</div>
</div>
</div>
</div>
</section>
<!-- Section: Live Timbangan & Bukti Panen Interaktif -->
<section class="w-full py-14 px-4 lg:px-8 bg-surface" id="harga-pasar">
<div class="max-w-7xl mx-auto">
<div class="p-8 rounded-3xl bg-surface-container-lowest shadow-md grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
<div class="lg:col-span-7 space-y-4">
<div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-secondary-container text-on-secondary-container font-label-sm text-label-sm">
<span class="material-symbols-outlined text-sm">scale</span>
<span>Transparansi Timbangan Digital Bang Zul</span>
</div>
<h2 class="font-headline-lg text-headline-lg text-on-surface">Timbang Ulang Bebas di Depan Kurir</h2>
<p class="font-body-md text-body-md text-on-surface-variant">
            Setiap kurir Bang Zul dibekali timbangan digital bersertifikasi. Jika berat telur kurang dari spesifikasi atau ada cangkang yang retak saat diperiksa, kurir langsung mengganti butir telur baru di tempat tanpa ribet!
          </p>
<div class="grid grid-cols-1 sm:grid-cols-3 gap-3 pt-2">
<div class="p-3 rounded-xl bg-surface-container-low">
<span class="font-headline-sm text-headline-sm text-primary">100%</span>
<p class="font-body-sm text-body-sm text-on-surface-variant">Garansi Anti Retak</p>
</div>
<div class="p-3 rounded-xl bg-surface-container-low">
<span class="font-headline-sm text-headline-sm text-secondary">&lt; 3 Jam</span>
<p class="font-body-sm text-body-sm text-on-surface-variant">Estimasi Tiba Wilayah Inti</p>
</div>
<div class="p-3 rounded-xl bg-surface-container-low">
<span class="font-headline-sm text-headline-sm text-on-surface">COD / QRIS</span>
<p class="font-body-sm text-body-sm text-on-surface-variant">Bayar Setelah Periksa</p>
</div>
</div>
</div>
<div class="lg:col-span-5 p-6 rounded-2xl bg-surface-container-low flex flex-col justify-between space-y-4">
<div class="flex items-center justify-between">
<span class="font-label-md text-label-md text-on-surface-variant">Pantauan Harga Hari Ini (Tanggamus)</span>
<span class="font-label-sm text-label-sm text-secondary font-bold">Stabil</span>
</div>
<div class="space-y-2.5">
<div class="flex items-center justify-between p-2.5 rounded-xl bg-surface-container-lowest text-body-sm font-body-sm">
<span class="text-on-surface font-semibold">Telur Ayam Ras (1 Kg)</span>
<span class="text-primary font-bold">Rp 28.000 / kg</span>
</div>
<div class="flex items-center justify-between p-2.5 rounded-xl bg-surface-container-lowest text-body-sm font-body-sm">
<span class="text-on-surface font-semibold">Telur Ayam Ras (1 Karpet / 30 Btr)</span>
<span class="text-primary font-bold">Rp 52.000 / krat</span>
</div>
<div class="flex items-center justify-between p-2.5 rounded-xl bg-surface-container-lowest text-body-sm font-body-sm">
<span class="text-on-surface font-semibold">Grosir Karpet (Min. 10 Karpet)</span>
<span class="text-secondary font-bold">Rp 50.500 / krat</span>
</div>
</div>
<a class="w-full py-2.5 rounded-xl bg-secondary text-on-secondary hover:bg-secondary/90 font-label-md text-label-md flex items-center justify-center gap-2 shadow-sm transition-all" href="https://wa.me/6281278900000?text=Halo%20Bang%20Zul,%20mau%20order%20grosir%20telur">
<span class="material-symbols-outlined text-sm">storefront</span>
<span>Ajukan Harga Grosir Warung</span>
</a>
</div>
</div>
</div>
</section>
<!-- Section: Cara Pesan di Bang Zul (4 Langkah) -->
<section class="w-full py-16 px-4 lg:px-8 bg-surface-container-low">
<div class="max-w-7xl mx-auto space-y-12">
<div class="text-center max-w-2xl mx-auto space-y-2">
<span class="font-label-sm text-label-sm font-bold uppercase tracking-wider text-secondary">Praktis &amp; Cepat</span>
<h2 class="font-headline-lg text-headline-lg text-on-surface">Cara Mudah Pesan Telur Segar</h2>
<p class="font-body-md text-body-md text-on-surface-variant">Belanja telur praktis tanpa repot ke pasar becek, telur aman terjamin utuh sampai ke dapur Anda.</p>
</div>
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
<!-- Step 1 -->
<div class="relative p-6 rounded-2xl bg-surface-container-lowest shadow-sm hover:shadow-md transition-all flex flex-col justify-between">
<div class="space-y-4">
<div class="flex items-center justify-between">
<div class="w-12 h-12 rounded-xl bg-primary-fixed flex items-center justify-center text-primary">
<span class="material-symbols-outlined text-2xl">format_list_bulleted</span>
</div>
<span class="font-headline-lg text-headline-lg font-extrabold text-surface-dim">01</span>
</div>
<h3 class="font-headline-sm text-headline-sm text-on-surface">Pilih Jenis Telur &amp; Kuantitas</h3>
<p class="font-body-sm text-body-sm text-on-surface-variant">Tentukan butiran, pack mika higienis, kiloan, atau grosir karpet sesuai stok dapur dan warung.</p>
</div>
<div class="pt-4 text-primary font-label-sm text-label-sm font-bold">Langkah 1</div>
</div>
<!-- Step 2 -->
<div class="relative p-6 rounded-2xl bg-surface-container-lowest shadow-sm hover:shadow-md transition-all flex flex-col justify-between">
<div class="space-y-4">
<div class="flex items-center justify-between">
<div class="w-12 h-12 rounded-xl bg-secondary-fixed flex items-center justify-center text-secondary">
<span class="material-symbols-outlined text-2xl">pin_drop</span>
</div>
<span class="font-headline-lg text-headline-lg font-extrabold text-surface-dim">02</span>
</div>
<h3 class="font-headline-sm text-headline-sm text-on-surface">Tentukan Titik Alamat Antar</h3>
<p class="font-body-sm text-body-sm text-on-surface-variant">Ketik alamat rumah, kantin, katering, atau kios warung di wilayah Kabupaten Tanggamus.</p>
</div>
<div class="pt-4 text-secondary font-label-sm text-label-sm font-bold">Langkah 2</div>
</div>
<!-- Step 3 -->
<div class="relative p-6 rounded-2xl bg-surface-container-lowest shadow-sm hover:shadow-md transition-all flex flex-col justify-between">
<div class="space-y-4">
<div class="flex items-center justify-between">
<div class="w-12 h-12 rounded-xl bg-primary-container/20 flex items-center justify-center text-primary">
<span class="material-symbols-outlined text-2xl">two_wheeler</span>
</div>
<span class="font-headline-lg text-headline-lg font-extrabold text-surface-dim">03</span>
</div>
<h3 class="font-headline-sm text-headline-sm text-on-surface">Kurir Meluncur dengan Box Khusus</h3>
<p class="font-body-sm text-body-sm text-on-surface-variant">Armada motor terlatih mengantar dengan box berbusa peredam getaran jalanan Tanggamus.</p>
</div>
<div class="pt-4 text-primary font-label-sm text-label-sm font-bold">Langkah 3</div>
</div>
<!-- Step 4 -->
<div class="relative p-6 rounded-2xl bg-surface-container-lowest shadow-sm hover:shadow-md transition-all flex flex-col justify-between">
<div class="space-y-4">
<div class="flex items-center justify-between">
<div class="w-12 h-12 rounded-xl bg-secondary-container flex items-center justify-center text-on-secondary-container">
<span class="material-symbols-outlined text-2xl">verified</span>
</div>
<span class="font-headline-lg text-headline-lg font-extrabold text-surface-dim">04</span>
</div>
<h3 class="font-headline-sm text-headline-sm text-on-surface">Periksa &amp; Bayar di Tempat</h3>
<p class="font-body-sm text-body-sm text-on-surface-variant">Buka dan cek telur di depan kurir. Telur retak langsung diganti seketika! Bayar tunai atau QRIS.</p>
</div>
<div class="pt-4 text-secondary font-label-sm text-label-sm font-bold">Langkah 4</div>
</div>
</div>
</div>
</section>
<!-- Section: Testimonial & Social Proof Banner -->
<section class="w-full py-16 px-4 lg:px-8 bg-surface">
<div class="max-w-7xl mx-auto">
<div class="rounded-3xl bg-gradient-to-r from-secondary to-on-secondary-fixed-variant text-on-secondary p-8 lg:p-12 shadow-xl relative overflow-hidden">
<div class="relative z-10 max-w-3xl space-y-6">
<span class="px-3.5 py-1 rounded-full bg-secondary-fixed text-on-secondary-fixed font-label-sm text-label-sm font-bold">
            Komitmen Pelayanan Peternak Tanggamus
          </span>
<h2 class="font-headline-lg text-headline-lg leading-tight font-extrabold">
            Dipercaya 120+ Warung Kelontong, Pedagang Martabak &amp; Katering Rumahan
          </h2>
<p class="font-body-lg text-body-lg text-surface-container-low opacity-95">
            "Sejak langganan telur ayam ras Bang Zul, adonan martabak kami mengembang sempurna dan kuningnya cantik. Timbangan pas, diantar sampai ke kios tepat waktu setiap sore tanpa ada telur yang pecah."
          </p>
<div class="flex flex-wrap items-center gap-4 pt-2">
<div class="flex items-center gap-2">
<span class="material-symbols-outlined text-secondary-fixed">store</span>
<span class="font-label-md text-label-md">Pak Hendra (Martabak Bangka Gisting)</span>
</div>
<div class="flex items-center gap-2">
<span class="material-symbols-outlined text-secondary-fixed">restaurant</span>
<span class="font-label-md text-label-md">Bu Siti (Katering Berkah Wonosobo)</span>
</div>
</div>
</div>
<!-- Decorative background circles -->
<div class="absolute -right-10 -bottom-10 w-72 h-72 rounded-full bg-secondary-fixed/10 pointer-events-none"></div>
</div>
</div>
</section>
<!-- Interactive JavaScript Stepper micro-interaction -->
<script>
    function increment(elementId) {
      const el = document.getElementById(elementId);
      if (el) {
        let val = parseInt(el.textContent) || 1;
        el.textContent = val + 1;
      }
    }
    function decrement(elementId) {
      const el = document.getElementById(elementId);
      if (el) {
        let val = parseInt(el.textContent) || 1;
        if (val > 1) {
          el.textContent = val - 1;
        }
      }
    }
  </script>
</div></main><footer class="w-full bg-surface-container-low mt-16 pt-12 pb-8 text-on-surface-variant"><div class="max-w-7xl mx-auto px-4 lg:px-8 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8"><div class="space-y-3"><div class="flex items-center gap-2"><img alt="Logo Bang Zul Egg Market" class="h-7 w-auto object-contain" src="https://lh3.googleusercontent.com/aida/ALJJyrAvuhgJbL1OqXYnorOpflEwk9ch2RB3i3nIpJf2khBHtFUraZYLjA49xnoYr5_XpY1inx_yvUKDG-f5ULodcAC4hoBl9QYWujU07wAAJsvNI88PefRZRNH2SgRzcvtvfP9LlMDgvobQRRrHxWwLlWY8MQoR1CS4kennwXqXJqn5PR3R5zkf-p4q0eleDblVHlCAtE__Wj8FbqU6db9zlBw02jnLdLpow_xGCN8RF4es"/><span class="font-headline-sm text-headline-sm text-primary">UD. Bang Zul Egg Market</span></div><p class="font-body-sm text-body-sm">Pusat distribusi telur segar langsung dari peternak binaan lokal Tanggamus. Menjaga kualitas kesegaran cangkang utuh dan timbangan presisi terpercaya.</p><div class="flex items-center gap-2 text-secondary font-label-sm text-label-sm"><span class="material-symbols-outlined text-sm">verified</span><span>Garansi Ganti Telur Pecah 100%</span></div></div><div class="space-y-2"><h3 class="font-headline-sm text-headline-sm text-on-surface">Jam Operasional &amp; Panen</h3><p class="font-body-sm text-body-sm">Pengambilan Telur Kandang: 06.00 - 10.00 WIB</p><p class="font-body-sm text-body-sm">Jadwal Pengiriman Kurir: 08.00 - 18.00 WIB</p><p class="font-body-sm text-body-sm text-secondary font-semibold">Setiap Hari (Senin - Minggu Tetap Buka)</p><p class="font-label-sm text-label-sm text-on-surface-variant pt-1">Wilayah Gisting, Talang Padang, Wonosobo, Kota Agung &amp; Sekitarnya.</p></div><div class="space-y-2"><h3 class="font-headline-sm text-headline-sm text-on-surface">Metode Pembayaran</h3><div class="space-y-1 font-body-sm text-body-sm"><p class="flex items-center gap-1.5"><span class="material-symbols-outlined text-primary text-sm">qr_code_scanner</span>QRIS Seluruh Bank &amp; E-Wallet</p><p class="flex items-center gap-1.5"><span class="material-symbols-outlined text-primary text-sm">account_balance</span>Transfer Bank Lampung / BRI / BCA</p><p class="flex items-center gap-1.5"><span class="material-symbols-outlined text-primary text-sm">payments</span>COD (Bayar Tunai di Tempat saat Timbang)</p></div></div><div class="space-y-2"><h3 class="font-headline-sm text-headline-sm text-on-surface">Komitmen Peternak Lokal</h3><p class="font-body-sm text-body-sm">Mendukung keberlanjutan usaha peternak unggas pedesaan di Kabupaten Tanggamus, Lampung dengan harga adil, timbangan transparan, dan pakan alami bermutu.</p><div class="pt-2"><span class="inline-block px-3 py-1 bg-secondary-container text-on-secondary-container rounded-full font-label-sm text-label-sm">Asli Tanggamus, Segar Bergaransi</span></div></div></div><div class="max-w-7xl mx-auto px-4 lg:px-8 mt-10 pt-4 flex flex-col sm:flex-row items-center justify-between gap-2 font-label-sm text-label-sm text-on-surface-variant"><p>© 2024 UD. Bang Zul Egg Market Tanggamus Lampung. Hak Cipta Dilindungi.</p><p>Dibuat untuk ekosistem niaga agrikultur Kabupaten Tanggamus</p></div></footer></body></html>

<!-- Panel Admin Pasar Telur -->
<!DOCTYPE html>

<html lang="id"><head><meta charset="utf-8"/><meta content="width=device-width, initial-scale=1.0" name="viewport"/><meta content="web_dashboard" name="shell-type"/><link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" rel="stylesheet"/><link href="https://fonts.googleapis.com" rel="preconnect"/><link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/><link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&amp;family=Plus+Jakarta+Sans:wght@700;800&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/><style>@layer base{html,body{margin:0;padding:0;}body{overscroll-behavior:none;}main>:first-child{margin-top:0!important;}main>:last-child{margin-bottom:0!important;}}::-webkit-scrollbar{display:none;}</style><script src="https://cdn.tailwindcss.com"></script><script id="tailwind-config">tailwind.config={darkMode:"class",theme:{extend:{colors:{"on-primary-container":"#644000","on-secondary-fixed-variant":"#005312","surface":"#fcf9f8","on-tertiary-fixed-variant":"#3e4a41","on-secondary":"#ffffff","surface-container-lowest":"#ffffff","on-primary-fixed-variant":"#633f00","on-primary":"#ffffff","primary-container":"#f5a623","error":"#ba1a1a","tertiary-fixed":"#d9e6da","on-primary-fixed":"#291800","tertiary-fixed-dim":"#bdcabe","surface-container-high":"#eae7e7","surface-dim":"#dcd9d9","on-error-container":"#93000a","tertiary":"#556158","outline-variant":"#d7c3ae","secondary-container":"#a0f399","inverse-on-surface":"#f3f0f0","on-secondary-container":"#217128","background":"#fcf9f8","on-surface-variant":"#524534","on-error":"#ffffff","surface-variant":"#e4e2e1","surface-bright":"#fcf9f8","error-container":"#ffdad6","primary":"#835500","secondary-fixed":"#a3f69c","primary-fixed-dim":"#ffb955","inverse-surface":"#303030","on-background":"#1b1c1c","on-tertiary":"#ffffff","surface-tint":"#835500","on-tertiary-container":"#3e4a41","inverse-primary":"#ffb955","surface-container-low":"#f6f3f2","secondary-fixed-dim":"#88d982","on-surface":"#1b1c1c","tertiary-container":"#acb9ae","secondary":"#1b6d24","surface-container-highest":"#e4e2e1","surface-container":"#f0eded","primary-fixed":"#ffddb4","outline":"#857462","on-secondary-fixed":"#002204","on-tertiary-fixed":"#131e17"},borderRadius:{"DEFAULT":"0.25rem","lg":"0.5rem","xl":"0.75rem","full":"9999px"},spacing:{"gutter-desktop":"1.5rem","margin-desktop":"2.5rem","gutter":"1rem","space-lg":"1.5rem","space-xl":"2rem","margin":"1rem","space-md":"1rem","space-xs":"0.25rem","space-sm":"0.5rem"},fontFamily:{"body-md":["Inter"],"headline-lg-mobile":["Plus Jakarta Sans"],"headline-sm":["Plus Jakarta Sans"],"label-lg":["Inter"],"display-lg-mobile":["Plus Jakarta Sans"],"display-lg":["Plus Jakarta Sans"],"label-sm":["Inter"],"headline-lg":["Plus Jakarta Sans"],"stock-counter":["Inter"],"label-md":["Inter"],"headline-md":["Plus Jakarta Sans"],"body-sm":["Inter"],"price-display":["Plus Jakarta Sans"],"body-lg":["Inter"]},fontSize:{"body-md":["14px",{"lineHeight":"22px","fontWeight":"400"}],"headline-lg-mobile":["22px",{"lineHeight":"30px","letterSpacing":"0em","fontWeight":"700"}],"headline-sm":["16px",{"lineHeight":"24px","fontWeight":"700"}],"label-lg":["14px",{"lineHeight":"20px","fontWeight":"600"}],"display-lg-mobile":["30px",{"lineHeight":"38px","letterSpacing":"-0.01em","fontWeight":"800"}],"display-lg":["40px",{"lineHeight":"48px","letterSpacing":"-0.02em","fontWeight":"800"}],"label-sm":["11px",{"lineHeight":"14px","letterSpacing":"0.02em","fontWeight":"600"}],"headline-lg":["28px",{"lineHeight":"36px","letterSpacing":"-0.01em","fontWeight":"700"}],"stock-counter":["18px",{"lineHeight":"24px","letterSpacing":"0.01em","fontWeight":"700"}],"label-md":["12px",{"lineHeight":"16px","fontWeight":"600"}],"headline-md":["20px",{"lineHeight":"28px","fontWeight":"700"}],"body-sm":["12px",{"lineHeight":"18px","fontWeight":"400"}],"price-display":["22px",{"lineHeight":"28px","letterSpacing":"-0.02em","fontWeight":"800"}],"body-lg":["16px",{"lineHeight":"26px","fontWeight":"400"}]}}}}</script></head><body class="bg-surface font-body-md text-body-md text-on-surface antialiased"><aside class="fixed left-0 top-0 h-full w-64 bg-surface-container-low z-50 flex flex-col py-5 shadow-[0_4px_20px_-2px_rgba(245,166,35,0.08)]"><div class="px-5 mb-6 flex items-center gap-3"><img alt="Logo Bang Zul Egg Market" class="h-8 w-auto object-contain" src="https://lh3.googleusercontent.com/aida/ALJJyrAvuhgJbL1OqXYnorOpflEwk9ch2RB3i3nIpJf2khBHtFUraZYLjA49xnoYr5_XpY1inx_yvUKDG-f5ULodcAC4hoBl9QYWujU07wAAJsvNI88PefRZRNH2SgRzcvtvfP9LlMDgvobQRRrHxWwLlWY8MQoR1CS4kennwXqXJqn5PR3R5zkf-p4q0eleDblVHlCAtE__Wj8FbqU6db9zlBw02jnLdLpow_xGCN8RF4es"/><div class="flex flex-col"><span class="font-headline-sm text-headline-sm text-primary leading-tight">Bang Zul</span><span class="font-label-sm text-label-sm text-on-surface-variant">Sistem Operasional</span></div></div><div class="px-4 mb-4"><div class="p-2.5 rounded-xl bg-surface-container flex items-center gap-2"><span class="material-symbols-outlined text-secondary text-lg">pin_drop</span><div class="leading-none"><span class="font-label-sm text-label-sm font-bold block text-on-surface">Pos Tanggamus</span><span class="font-label-sm text-label-sm text-on-surface-variant">Gisting - Talang Padang</span></div></div></div><nav class="flex-1 px-3 space-y-1" data-active-classes="bg-primary-container text-on-primary-container font-bold"><a class="flex items-center gap-3 px-3 py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface font-label-md text-label-md transition-all" data-path="toko-bang-zul" href="#"><span class="material-symbols-outlined text-lg">storefront</span>Toko &amp; Inventori Bang Zul</a><a class="flex items-center gap-3 px-3 py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface font-label-md text-label-md transition-all" data-path="kurir-tanggamus" href="#"><span class="material-symbols-outlined text-lg">two_wheeler</span>Pantau Kurir Lapangan</a><a aria-current="page" class="flex items-center gap-3 px-3 py-2.5 rounded-xl transition-all bg-primary-container text-on-primary-container font-bold" data-path="admin-pasar" href="#"><span class="material-symbols-outlined text-lg">admin_panel_settings</span>Admin &amp; Kas Penjualan</a><a class="flex items-center gap-3 px-3 py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface font-label-md text-label-md transition-all" data-path="jadwal-panen-stok" href="#"><span class="material-symbols-outlined text-lg">egg</span>Timbangan &amp; Panen</a><a class="flex items-center gap-3 px-3 py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface font-label-md text-label-md transition-all" data-path="katalog-belanja" href="#"><span class="material-symbols-outlined text-lg">store</span>Lihat Toko Publik</a></nav><div class="px-4 pt-3 border-t border-surface-container-highest flex items-center justify-between"><div class="flex items-center gap-2"><img alt="Profile" class="w-8 h-8 rounded-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBu4cCay1o-kcZkrepBjdwRhNkTeb5NSNF4V20H1AoEXr4ahIrRP9SktX37TUve3u7us_GHnlm1279EoAyYcFxqZTZV4CIOdstOTCqIMcitiPTCwpWm4m2okjdh9z8S2I2n0sK1hb3y3ohWU84Tu6ZWNoxKL7D1NVLhMsBA3C6eHNQmukclnmKpMzHXssx-xtkh1wF2y2OFEDgXUgTPjjAfLabaOsUrz91MId6by4k"/><div class="leading-none"><span class="font-label-sm text-label-sm font-bold block text-on-surface">Bang Zul</span><span class="font-label-sm text-label-sm text-secondary">Owner &amp; Verifikator</span></div></div><a class="text-on-surface-variant hover:text-error" data-path="login-auth" href="#"><span class="material-symbols-outlined text-lg">logout</span></a></div></aside><div class="pl-64"><header class="fixed top-0 left-64 right-0 h-16 bg-surface/95 backdrop-blur-md shadow-[0_1px_8px_rgba(0,0,0,0.04)] z-40 px-6 flex items-center justify-between"><div class="flex items-center gap-3"><span class="inline-flex items-center px-2.5 py-1 rounded-full bg-secondary-container text-on-secondary-container font-label-sm text-label-sm font-semibold"><span class="w-1.5 h-1.5 rounded-full bg-secondary mr-1.5"></span>Sistem Operasional Aktif</span><span class="text-body-sm font-body-sm text-on-surface-variant hidden md:inline">Wilayah Gisting • Kota Agung • Talang Padang</span></div><div class="flex items-center gap-3"><a class="hidden sm:flex items-center gap-1 px-3 py-1.5 rounded-lg bg-surface-container text-on-surface font-label-sm text-label-sm hover:bg-surface-container-high" href="https://wa.me/6281278900000"><span class="material-symbols-outlined text-secondary text-sm">support_agent</span>CS Bang Zul</a><button class="p-2 rounded-full hover:bg-surface-container text-on-surface-variant" type="button"><span class="material-symbols-outlined text-xl">notifications</span></button><img alt="Profile" class="w-8 h-8 rounded-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBu4cCay1o-kcZkrepBjdwRhNkTeb5NSNF4V20H1AoEXr4ahIrRP9SktX37TUve3u7us_GHnlm1279EoAyYcFxqZTZV4CIOdstOTCqIMcitiPTCwpWm4m2okjdh9z8S2I2n0sK1hb3y3ohWU84Tu6ZWNoxKL7D1NVLhMsBA3C6eHNQmukclnmKpMzHXssx-xtkh1wF2y2OFEDgXUgTPjjAfLabaOsUrz91MId6by4k"/></div></header><main class="w-full pt-16 bg-surface px-6 py-6 min-h-screen"><div class="flex flex-col w-full space-y-8">
<!-- Top Command Center Banner -->
<section class="relative rounded-2xl bg-surface-container-low p-6 lg:p-8 shadow-sm overflow-hidden">
<div class="absolute -right-16 -top-16 w-64 h-64 rounded-full bg-primary-container/10 blur-2xl pointer-events-none"></div>
<div class="flex flex-col lg:flex-row lg:items-center justify-between gap-6 relative z-10">
<div class="space-y-2">
<div class="flex flex-wrap items-center gap-2">
<span class="inline-flex items-center gap-1.5 px-3 py-1 rounded-full bg-secondary-container text-on-secondary-container font-label-sm text-label-sm font-semibold">
<span class="w-2 h-2 rounded-full bg-secondary animate-pulse"></span>
            Server Timbangan &amp; Pasar Terhubung
          </span>
<span class="px-2.5 py-1 rounded-full bg-surface-container-high text-on-surface-variant font-label-sm text-label-sm">
            Node: Gisting Sentral #TG-01
          </span>
<span class="text-body-sm font-body-sm text-on-surface-variant">
            Pembaruan terakhir: <strong class="text-on-surface">14:42 WIB</strong>
</span>
</div>
<h1 class="font-headline-lg text-headline-lg text-on-surface tracking-tight">
          Pusat Kendali Pasar Telur Bang Zul
        </h1>
<p class="font-body-md text-body-md text-on-surface-variant max-w-2xl">
          Monitoring terpusat rantai pasok unggas, transaksi mitra warung sembako, dan armada ekspedisi telur segar se-Kabupaten Tanggamus.
        </p>
</div>
<!-- Quick Action Pill Group -->
<div class="flex flex-wrap items-center gap-3">
<button class="inline-flex items-center gap-2 px-4 py-2.5 rounded-xl bg-surface-container-highest hover:bg-surface-container-high text-on-surface font-label-md text-label-md transition shadow-sm" type="button">
<span class="material-symbols-outlined text-base text-primary">download</span>
          Ekspor Rekap Harian (.CSV)
        </button>
<button class="inline-flex items-center gap-2 px-4 py-2.5 rounded-xl bg-primary-container text-on-primary-container hover:bg-primary-fixed-dim font-label-md text-label-md transition shadow-md" type="button">
<span class="material-symbols-outlined text-base">sync</span>
          Sinkronisasi Timbangan Kandang
        </button>
</div>
</div>
</section>
<!-- Key Metrics & Visual Analytics -->
<section class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-5">
<!-- Stat 1: Volume Distribusi Harian -->
<div class="rounded-2xl bg-surface-container-lowest p-5 shadow-sm flex flex-col justify-between relative overflow-hidden group hover:shadow-md transition">
<div class="flex items-center justify-between">
<span class="font-label-md text-label-md text-on-surface-variant uppercase tracking-wider">Distribusi Hari Ini</span>
<span class="w-9 h-9 rounded-xl bg-primary-fixed flex items-center justify-center text-on-primary-fixed">
<span class="material-symbols-outlined text-lg">egg</span>
</span>
</div>
<div class="mt-4">
<div class="flex items-baseline gap-2">
<span class="font-display-lg text-display-lg text-on-surface">2.400</span>
<span class="font-label-md text-label-md text-on-surface-variant">Butir</span>
</div>
<div class="flex items-center gap-2 mt-2">
<span class="inline-flex items-center text-secondary font-label-sm text-label-sm">
<span class="material-symbols-outlined text-sm">trending_up</span> +14.2%
          </span>
<span class="font-body-sm text-body-sm text-on-surface-variant">vs kemarin (80 krat)</span>
</div>
</div>
<!-- Inline Progress Bar -->
<div class="mt-4 pt-3 border-t border-surface-container-high">
<div class="flex justify-between font-label-sm text-label-sm mb-1 text-on-surface-variant">
<span>Target Panen Tanggamus</span>
<span class="font-bold text-on-surface">80% Tercapai</span>
</div>
<div class="w-full bg-surface-container-high rounded-full h-1.5 overflow-hidden">
<div class="bg-primary-container h-1.5 rounded-full" style="width: 80%"></div>
</div>
</div>
</div>
<!-- Stat 2: Transaksi Berjalan Wilayah -->
<div class="rounded-2xl bg-surface-container-lowest p-5 shadow-sm flex flex-col justify-between group hover:shadow-md transition">
<div class="flex items-center justify-between">
<span class="font-label-md text-label-md text-on-surface-variant uppercase tracking-wider">Sebaran Kecamatan</span>
<span class="w-9 h-9 rounded-xl bg-secondary-fixed flex items-center justify-center text-on-secondary-fixed">
<span class="material-symbols-outlined text-lg">map</span>
</span>
</div>
<div class="mt-3">
<div class="flex items-center gap-4">
<!-- Donut SVG representation -->
<div class="relative w-16 h-16 flex-shrink-0">
<svg class="w-16 h-16 transform -rotate-90" viewbox="0 0 36 36">
<circle cx="18" cy="18" fill="none" r="14" stroke="#f0eded" stroke-width="4"></circle>
<!-- Gisting 38% -->
<circle cx="18" cy="18" fill="none" r="14" stroke="#f5a623" stroke-dasharray="33.4 54.6" stroke-dashoffset="0" stroke-width="4"></circle>
<!-- Kota Agung 32% -->
<circle cx="18" cy="18" fill="none" r="14" stroke="#1b6d24" stroke-dasharray="28.1 59.9" stroke-dashoffset="-33.4" stroke-width="4"></circle>
<!-- Talang Padang 20% -->
<circle cx="18" cy="18" fill="none" r="14" stroke="#556158" stroke-dasharray="17.6 70.4" stroke-dashoffset="-61.5" stroke-width="4"></circle>
</svg>
<div class="absolute inset-0 flex items-center justify-center font-label-sm text-label-sm font-bold text-on-surface">
              100%
            </div>
</div>
<div class="flex-1 space-y-1 font-label-sm text-label-sm">
<div class="flex justify-between items-center">
<span class="flex items-center gap-1.5"><span class="w-2 h-2 rounded-full bg-primary-container"></span>Gisting</span>
<span class="font-bold text-on-surface">38%</span>
</div>
<div class="flex justify-between items-center">
<span class="flex items-center gap-1.5"><span class="w-2 h-2 rounded-full bg-secondary"></span>Kota Agung</span>
<span class="font-bold text-on-surface">32%</span>
</div>
<div class="flex justify-between items-center">
<span class="flex items-center gap-1.5"><span class="w-2 h-2 rounded-full bg-tertiary"></span>T. Padang</span>
<span class="font-bold text-on-surface">20%</span>
</div>
</div>
</div>
</div>
<div class="mt-3 pt-3 border-t border-surface-container-high flex justify-between items-center">
<span class="font-body-sm text-body-sm text-on-surface-variant">Lainnya (Pugung dkk.)</span>
<span class="font-label-sm text-label-sm font-semibold text-on-surface">10%</span>
</div>
</div>
<!-- Stat 3: Garansi Telur Pecah & Integritas -->
<div class="rounded-2xl bg-surface-container-lowest p-5 shadow-sm flex flex-col justify-between group hover:shadow-md transition">
<div class="flex items-center justify-between">
<span class="font-label-md text-label-md text-on-surface-variant uppercase tracking-wider">Garansi Utuh Lapangan</span>
<span class="w-9 h-9 rounded-xl bg-secondary-container flex items-center justify-center text-on-secondary-container">
<span class="material-symbols-outlined text-lg">verified_user</span>
</span>
</div>
<div class="mt-4">
<div class="flex items-baseline gap-2">
<span class="font-display-lg text-display-lg text-secondary">99.4%</span>
<span class="font-label-sm text-label-sm text-secondary font-bold">Lolos Timbang</span>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant mt-1">
          Hanya <strong>3 butir</strong> retak diganti instan di lokasi via garansi Bang Zul.
        </p>
</div>
<div class="mt-4 pt-3 border-t border-surface-container-high flex items-center justify-between">
<span class="font-label-sm text-label-sm text-on-surface-variant">Klaim Terbuka</span>
<span class="inline-flex items-center gap-1 px-2 py-0.5 rounded-full bg-surface-container-high text-on-surface font-label-sm text-label-sm font-semibold">
          0 Antrean
        </span>
</div>
</div>
<!-- Stat 4: Armada Kurir Tanggamus -->
<div class="rounded-2xl bg-surface-container-lowest p-5 shadow-sm flex flex-col justify-between group hover:shadow-md transition">
<div class="flex items-center justify-between">
<span class="font-label-md text-label-md text-on-surface-variant uppercase tracking-wider">Armada Bertugas</span>
<span class="w-9 h-9 rounded-xl bg-primary-fixed-dim flex items-center justify-center text-on-primary-fixed-variant">
<span class="material-symbols-outlined text-lg">local_shipping</span>
</span>
</div>
<div class="mt-4 space-y-2">
<div class="flex items-center justify-between">
<div class="flex items-center gap-2">
<span class="material-symbols-outlined text-primary text-base">two_wheeler</span>
<span class="font-label-md text-label-md text-on-surface">Motor Box Krat</span>
</div>
<span class="font-headline-sm text-headline-sm text-on-surface">5 <span class="font-body-sm text-body-sm font-normal text-on-surface-variant">Unit</span></span>
</div>
<div class="flex items-center justify-between">
<div class="flex items-center gap-2">
<span class="material-symbols-outlined text-secondary text-base">rv_hookup</span>
<span class="font-label-md text-label-md text-on-surface">Pick-up L300 Gisting</span>
</div>
<span class="font-headline-sm text-headline-sm text-on-surface">1 <span class="font-body-sm text-body-sm font-normal text-on-surface-variant">Unit</span></span>
</div>
</div>
<div class="mt-4 pt-3 border-t border-surface-container-high flex items-center justify-between font-label-sm text-label-sm">
<span class="text-secondary font-semibold flex items-center gap-1">
<span class="w-1.5 h-1.5 rounded-full bg-secondary"></span> Semua Aktif di Jalur
        </span>
<a class="text-primary hover:underline font-semibold" data-path="kurir-tanggamus" href="#">Pantau GPS →</a>
</div>
</div>
</section>
<!-- Live Operation Visual + Market Snapshot Grid -->
<section class="grid grid-cols-1 lg:grid-cols-3 gap-6">
<!-- Visual Feature: Market & Egg Sorting Station Snapshot -->
<div class="lg:col-span-1 rounded-2xl bg-surface-container-lowest p-6 shadow-sm flex flex-col justify-between">
<div>
<div class="flex items-center justify-between mb-4">
<h2 class="font-headline-sm text-headline-sm text-on-surface">Sentra Sortir Pasar</h2>
<span class="px-2 py-0.5 rounded-md bg-primary/10 text-primary font-label-sm text-label-sm font-semibold">Gudang Utama</span>
</div>
<div class="relative rounded-xl overflow-hidden mb-4 group h-52">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" data-alt="A warm, rustic poultry farm egg packaging warehouse in Tanggamus Sumatra with stacks of pressed cardboard egg trays filled with fresh brown eggs, soft natural sunlight entering through timber shutters, a local worker weighing eggs on a mechanical scale with precision and care, authentic Indonesian agricultural market ambiance." src="https://lh3.googleusercontent.com/aida-public/AB6AXuA48WF8rBbJbCtJo5iXsJfTnmxvBaNX5h-kq2vb-TbKaKWio1ILO18c2V30WDq97ih0snDeA2HknRM86WGRRrrZb-nFZ4vvwfSXsOJ54JA3ULjdvn2uraMM4-uCvArfSeBzTQPF3AzFW2wtern-c0iN_sYt4l-ntZ_VwjjY3zVCezGq5XO6llQF7fVneRuFC0bGX4xeUyKQOARmz4LVU7kw4pTvMurSac4s-oDaJBs"/>
<div class="absolute inset-0 bg-gradient-to-t from-black/70 via-black/20 to-transparent"></div>
<div class="absolute bottom-3 left-3 right-3 text-white">
<span class="text-xs uppercase tracking-wider font-semibold opacity-80">Grade Ras A Segar</span>
<p class="font-headline-sm text-headline-sm text-white leading-tight">Sortir Batch Pagi #B39</p>
</div>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant leading-relaxed">
          Kualitas butir dicek manual dengan peneropongan candling light sebelum disusun ke dalam peti kayu dan krat kurir.
        </p>
</div>
<div class="mt-5 p-3 rounded-xl bg-surface-container flex items-center justify-between">
<div class="flex items-center gap-2">
<span class="material-symbols-outlined text-primary text-xl">inventory_2</span>
<div>
<div class="font-label-md text-label-md font-semibold text-on-surface">Kapasitas Gudang</div>
<div class="font-body-sm text-body-sm text-on-surface-variant">Tersedia 340 krat (10.200 butir)</div>
</div>
</div>
<span class="font-label-sm text-label-sm text-secondary font-bold">Aman</span>
</div>
</div>
<!-- Realtime Delivery Heatmap / Route Tracker -->
<div class="lg:col-span-2 rounded-2xl bg-surface-container-lowest p-6 shadow-sm flex flex-col justify-between">
<div class="flex flex-col sm:flex-row sm:items-center justify-between gap-4 mb-4">
<div>
<h2 class="font-headline-sm text-headline-sm text-on-surface">Jalur Pengantaran Tanggamus Hari Ini</h2>
<p class="font-body-sm text-body-sm text-on-surface-variant">Peta titik pos singgah kurir dan warung pemesan prioritas</p>
</div>
<div class="flex items-center gap-2">
<span class="inline-flex items-center gap-1.5 px-3 py-1 rounded-full bg-surface-container text-on-surface-variant font-label-sm text-label-sm">
<span class="w-2 h-2 rounded-full bg-secondary"></span> 6 Pengantaran Berlangsung
          </span>
</div>
</div>
<!-- Map Container with Data-Location -->
<div class="w-full h-64 rounded-xl relative overflow-hidden bg-surface-container shadow-inner mb-4" data-location="Gisting, Tanggamus Regency, Lampung, Indonesia" style="background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuDS80RSTFSXhQrpsf9rdJjpuj-LMTFwPKU8KhiodTUOtwp-rOkXXJmLgjqtYkQVj4UuWxf8RPFwEOiR3ObMdN1IDJHxYxEWgU-J1qLG5CDu6NXiBaytP6E6x5v22nyao9EN07P09wGNK-JY8n8ruMZlW92xgv7fNKuLTABcpfFnAqiA1YNoP8AZphVREMmMTRehobwekwWH7FeBhDHKYJA2acYV1Jk6zzwCnjy4Fds')">
<div class="absolute inset-0 bg-gradient-to-t from-surface-container-lowest/80 via-transparent to-black/30 pointer-events-none"></div>
<div class="absolute top-3 left-3 bg-surface-container-lowest/90 backdrop-blur-md px-3 py-1.5 rounded-lg shadow-sm">
<span class="font-label-sm text-label-sm font-bold text-on-surface">Jalur Lintas Barat Sumatera - Tanggamus</span>
</div>
<div class="absolute bottom-3 left-3 right-3 flex flex-wrap gap-2">
<span class="bg-surface-container-lowest/95 backdrop-blur-md px-3 py-1 rounded-md shadow-sm font-label-sm text-label-sm flex items-center gap-1 text-on-surface">
<span class="material-symbols-outlined text-secondary text-sm">check_circle</span> Pos 1: Gisting Atas (Terkirim 12 Krat)
          </span>
<span class="bg-surface-container-lowest/95 backdrop-blur-md px-3 py-1 rounded-md shadow-sm font-label-sm text-label-sm flex items-center gap-1 text-on-surface">
<span class="material-symbols-outlined text-primary text-sm">schedule</span> Pos 2: Pasar Talang Padang (Menuju Lokasi)
          </span>
</div>
</div>
<!-- Live Log Chips -->
<div class="grid grid-cols-1 sm:grid-cols-3 gap-3">
<div class="p-3 rounded-xl bg-surface-container-low flex items-center gap-2">
<span class="material-symbols-outlined text-primary text-base">speed</span>
<div class="leading-tight">
<span class="font-label-sm text-label-sm text-on-surface-variant block">Rata-rata Waktu Kirim</span>
<span class="font-headline-sm text-headline-sm text-on-surface">26 Menit</span>
</div>
</div>
<div class="p-3 rounded-xl bg-surface-container-low flex items-center gap-2">
<span class="material-symbols-outlined text-secondary text-base">battery_charging_full</span>
<div class="leading-tight">
<span class="font-label-sm text-label-sm text-on-surface-variant block">Ketepatan Jadwal</span>
<span class="font-headline-sm text-headline-sm text-on-surface">97.8%</span>
</div>
</div>
<div class="p-3 rounded-xl bg-surface-container-low flex items-center gap-2">
<span class="material-symbols-outlined text-tertiary text-base">payments</span>
<div class="leading-tight">
<span class="font-label-sm text-label-sm text-on-surface-variant block">Kas Masuk Lapangan</span>
<span class="font-headline-sm text-headline-sm text-on-surface">Rp 5.280.000</span>
</div>
</div>
</div>
</div>
</section>
<!-- User & Role Management Table -->
<section class="rounded-2xl bg-surface-container-lowest p-6 shadow-sm">
<div class="flex flex-col md:flex-row md:items-center justify-between gap-4 mb-6">
<div>
<h2 class="font-headline-md text-headline-md text-on-surface">Manajemen Pengguna &amp; Mitra Wilayah</h2>
<p class="font-body-sm text-body-sm text-on-surface-variant">Kelola izin peran, verifikasi mitra warung kelontong, dan hak akses transaksi.</p>
</div>
<div class="flex items-center gap-3">
<div class="relative">
<span class="material-symbols-outlined absolute left-3 top-2.5 text-on-surface-variant text-base">search</span>
<input class="pl-9 pr-4 py-2 rounded-xl bg-surface-container-low text-on-surface placeholder:text-on-surface-variant font-body-sm text-body-sm focus:outline-none focus:bg-surface-container-lowest shadow-sm" placeholder="Cari nama warung, kurir, HP..." type="text"/>
</div>
<button class="inline-flex items-center gap-1.5 px-4 py-2 rounded-xl bg-primary-container text-on-primary-container font-label-md text-label-md shadow-sm hover:bg-primary-fixed-dim transition" type="button">
<span class="material-symbols-outlined text-base">person_add</span>
          Tambah Akun
        </button>
</div>
</div>
<!-- Role Filter Tabs Segmental -->
<div class="flex items-center gap-2 overflow-x-auto pb-3 mb-4 text-nowrap">
<button class="px-3.5 py-1.5 rounded-lg bg-surface-container-highest text-on-surface font-label-md text-label-md font-bold shadow-sm" type="button">
        Semua (1.240)
      </button>
<button class="px-3.5 py-1.5 rounded-lg text-on-surface-variant hover:bg-surface-container-low font-label-md text-label-md transition" type="button">
        Mitra Warung / Reseller (45)
        <span class="ml-1.5 px-1.5 py-0.2 rounded-full bg-secondary-container text-on-secondary-container text-xs">3 Verifikasi Baru</span>
</button>
<button class="px-3.5 py-1.5 rounded-lg text-on-surface-variant hover:bg-surface-container-low font-label-md text-label-md transition" type="button">
        Pembeli Terdaftar (1.180)
      </button>
<button class="px-3.5 py-1.5 rounded-lg text-on-surface-variant hover:bg-surface-container-low font-label-md text-label-md transition" type="button">
        Armada Kurir (6)
      </button>
<button class="px-3.5 py-1.5 rounded-lg text-on-surface-variant hover:bg-surface-container-low font-label-md text-label-md transition" type="button">
        Pengelola Toko (3)
      </button>
</div>
<!-- Data Table -->
<div class="overflow-x-auto">
<table class="w-full text-left font-body-sm text-body-sm">
<thead>
<tr class="bg-surface-container-low text-on-surface-variant font-label-sm text-label-sm uppercase tracking-wider">
<th class="py-3 px-4 rounded-l-xl">Nama / Identitas</th>
<th class="py-3 px-4">Peran &amp; Wilayah</th>
<th class="py-3 px-4">Jenis Transaksi &amp; Kuota</th>
<th class="py-3 px-4">Status Akun</th>
<th class="py-3 px-4">Aktivitas Terakhir</th>
<th class="py-3 px-4 text-right rounded-r-xl">Tindakan</th>
</tr>
</thead>
<tbody class="divide-y divide-surface-container-high">
<!-- Row 1: Mitra Warung Pending Verification -->
<tr class="hover:bg-surface-container-low/50 transition">
<td class="py-4 px-4">
<div class="flex items-center gap-3">
<div class="w-10 h-10 rounded-full bg-primary-fixed flex items-center justify-center text-primary font-bold">
                  WS
                </div>
<div>
<span class="font-headline-sm text-headline-sm text-on-surface block leading-tight">Toko Sembako Bu Nanik</span>
<span class="font-body-sm text-body-sm text-on-surface-variant">+62 821-8891-3401</span>
</div>
</div>
</td>
<td class="py-4 px-4">
<div class="space-y-0.5">
<span class="inline-flex items-center px-2 py-0.5 rounded-md bg-primary-fixed-dim text-on-primary-fixed-variant font-label-sm text-label-sm font-semibold">
                  Mitra Warung (Grosir)
                </span>
<div class="text-on-surface-variant font-body-sm text-body-sm">Kec. Gisting (Dekat Pasar Induk)</div>
</div>
</td>
<td class="py-4 px-4">
<div class="font-label-md text-label-md text-on-surface">15 Krat / Minggu</div>
<span class="text-on-surface-variant font-body-sm text-body-sm">Pengajuan Diskon Rp 1.500/kg</span>
</td>
<td class="py-4 px-4">
<span class="inline-flex items-center gap-1.5 px-2.5 py-1 rounded-full bg-primary-fixed text-on-primary-fixed-variant font-label-sm text-label-sm font-semibold">
<span class="w-1.5 h-1.5 rounded-full bg-primary animate-ping"></span> Menunggu Verifikasi
              </span>
</td>
<td class="py-4 px-4 text-on-surface-variant">
              10 Menit lalu (Kirim KTP &amp; Foto Warung)
            </td>
<td class="py-4 px-4 text-right">
<div class="flex items-center justify-end gap-2">
<button class="px-3 py-1.5 rounded-lg bg-secondary text-on-secondary font-label-sm text-label-sm font-semibold hover:opacity-95 transition shadow-sm" type="button">
                  Verifikasi Mitra
                </button>
<button class="p-1.5 rounded-lg hover:bg-surface-container text-on-surface-variant" type="button">
<span class="material-symbols-outlined text-base">more_vert</span>
</button>
</div>
</td>
</tr>
<!-- Row 2: Active Courier -->
<tr class="hover:bg-surface-container-low/50 transition">
<td class="py-4 px-4">
<div class="flex items-center gap-3">
<div class="w-10 h-10 rounded-full bg-secondary-container flex items-center justify-center text-on-secondary-container font-bold">
                  AY
                </div>
<div>
<span class="font-headline-sm text-headline-sm text-on-surface block leading-tight">Ahmad Yani</span>
<span class="font-body-sm text-body-sm text-on-surface-variant">+62 813-7729-1090</span>
</div>
</div>
</td>
<td class="py-4 px-4">
<div class="space-y-0.5">
<span class="inline-flex items-center px-2 py-0.5 rounded-md bg-secondary-container text-on-secondary-container font-label-sm text-label-sm font-semibold">
                  Armada Kurir Lapangan
                </span>
<div class="text-on-surface-variant font-body-sm text-body-sm">Zona Rute: Talang Padang - Gisting</div>
</div>
</td>
<td class="py-4 px-4">
<div class="font-label-md text-label-md text-on-surface">Motor Box #KR-02</div>
<span class="text-secondary font-semibold font-body-sm text-body-sm">Membawa 18 Krat Aktif</span>
</td>
<td class="py-4 px-4">
<span class="inline-flex items-center gap-1.5 px-2.5 py-1 rounded-full bg-secondary-container text-on-secondary-container font-label-sm text-label-sm font-semibold">
<span class="w-1.5 h-1.5 rounded-full bg-secondary"></span> Sedang Mengantar
              </span>
</td>
<td class="py-4 px-4 text-on-surface-variant">
              Tiba di Talang Padang (2 mnt lalu)
            </td>
<td class="py-4 px-4 text-right">
<div class="flex items-center justify-end gap-2">
<a class="p-1.5 rounded-lg bg-surface-container hover:bg-surface-container-high text-secondary" href="https://wa.me/6281377291090" title="WhatsApp Kurir">
<span class="material-symbols-outlined text-base">chat</span>
</a>
<button class="p-1.5 rounded-lg hover:bg-surface-container text-on-surface-variant" type="button">
<span class="material-symbols-outlined text-base">more_vert</span>
</button>
</div>
</td>
</tr>
<!-- Row 3: Regular Buyer Household -->
<tr class="hover:bg-surface-container-low/50 transition">
<td class="py-4 px-4">
<div class="flex items-center gap-3">
<div class="w-10 h-10 rounded-full bg-surface-container-highest flex items-center justify-center text-on-surface-variant font-bold">
                  SK
                </div>
<div>
<span class="font-headline-sm text-headline-sm text-on-surface block leading-tight">Siti Khadijah</span>
<span class="font-body-sm text-body-sm text-on-surface-variant">+62 852-6901-2244</span>
</div>
</div>
</td>
<td class="py-4 px-4">
<div class="space-y-0.5">
<span class="inline-flex items-center px-2 py-0.5 rounded-md bg-surface-container-high text-on-surface font-label-sm text-label-sm font-semibold">
                  Pelanggan Rumah Tangga
                </span>
<div class="text-on-surface-variant font-body-sm text-body-sm">Kota Agung Barat</div>
</div>
</td>
<td class="py-4 px-4">
<div class="font-label-md text-label-md text-on-surface">Eceran (2 Kg / Pesanan)</div>
<span class="text-on-surface-variant font-body-sm text-body-sm">Total 12x Transaksi Selesai</span>
</td>
<td class="py-4 px-4">
<span class="inline-flex items-center gap-1.5 px-2.5 py-1 rounded-full bg-surface-container-high text-on-surface-variant font-label-sm text-label-sm font-semibold">
                Aktif
              </span>
</td>
<td class="py-4 px-4 text-on-surface-variant">
              Kemarin, 16:30 WIB
            </td>
<td class="py-4 px-4 text-right">
<div class="flex items-center justify-end gap-2">
<button class="p-1.5 rounded-lg hover:bg-surface-container text-on-surface-variant" type="button">
<span class="material-symbols-outlined text-base">manage_accounts</span>
</button>
</div>
</td>
</tr>
<!-- Row 4: Mitra Warung Verified -->
<tr class="hover:bg-surface-container-low/50 transition">
<td class="py-4 px-4">
<div class="flex items-center gap-3">
<div class="w-10 h-10 rounded-full bg-primary-container/20 flex items-center justify-center text-primary font-bold">
                  MB
                </div>
<div>
<span class="font-headline-sm text-headline-sm text-on-surface block leading-tight">Warung Barokah Pak Slamet</span>
<span class="font-body-sm text-body-sm text-on-surface-variant">+62 812-9901-5582</span>
</div>
</div>
</td>
<td class="py-4 px-4">
<div class="space-y-0.5">
<span class="inline-flex items-center px-2 py-0.5 rounded-md bg-secondary-container text-on-secondary-container font-label-sm text-label-sm font-semibold">
                  Mitra Warung (Terverifikasi)
                </span>
<div class="text-on-surface-variant font-body-sm text-body-sm">Kec. Pugung</div>
</div>
</td>
<td class="py-4 px-4">
<div class="font-label-md text-label-md text-on-surface">30 Krat / Bulan</div>
<span class="text-secondary font-semibold font-body-sm text-body-sm">Harga Reseller Aktif</span>
</td>
<td class="py-4 px-4">
<span class="inline-flex items-center gap-1.5 px-2.5 py-1 rounded-full bg-secondary-container text-on-secondary-container font-label-sm text-label-sm font-semibold">
                Mitra Prioritas
              </span>
</td>
<td class="py-4 px-4 text-on-surface-variant">
              Hari ini, 09:15 WIB (Pesan 5 Krat)
            </td>
<td class="py-4 px-4 text-right">
<div class="flex items-center justify-end gap-2">
<button class="p-1.5 rounded-lg hover:bg-surface-container text-on-surface-variant" type="button">
<span class="material-symbols-outlined text-base">receipt_long</span>
</button>
<button class="p-1.5 rounded-lg hover:bg-surface-container text-on-surface-variant" type="button">
<span class="material-symbols-outlined text-base">more_vert</span>
</button>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<!-- Table Pagination -->
<div class="mt-4 pt-4 border-t border-surface-container-high flex flex-col sm:flex-row items-center justify-between gap-3 font-label-sm text-label-sm text-on-surface-variant">
<span>Menampilkan <strong>1-4</strong> dari <strong>1.240</strong> akun se-Tanggamus</span>
<div class="flex items-center gap-1">
<button class="p-1.5 rounded-md bg-surface-container hover:bg-surface-container-high text-on-surface disabled:opacity-50" disabled="" type="button">
<span class="material-symbols-outlined text-sm">chevron_left</span>
</button>
<span class="px-3 py-1 rounded-md bg-primary-container text-on-primary-container font-bold">1</span>
<button class="px-3 py-1 rounded-md hover:bg-surface-container" type="button">2</button>
<button class="px-3 py-1 rounded-md hover:bg-surface-container" type="button">3</button>
<span class="px-1">...</span>
<button class="px-3 py-1 rounded-md hover:bg-surface-container" type="button">48</button>
<button class="p-1.5 rounded-md bg-surface-container hover:bg-surface-container-high text-on-surface" type="button">
<span class="material-symbols-outlined text-sm">chevron_right</span>
</button>
</div>
</div>
</section>
<!-- Distribution Area Configuration & WhatsApp Gateway Grid -->
<section class="grid grid-cols-1 lg:grid-cols-12 gap-6">
<!-- Ongkir & Logistics Area Configuration (8 cols) -->
<div class="lg:col-span-7 rounded-2xl bg-surface-container-lowest p-6 shadow-sm flex flex-col justify-between">
<div>
<div class="flex items-center justify-between mb-4">
<div>
<h2 class="font-headline-sm text-headline-sm text-on-surface">Matriks Tarif &amp; Rute Distribusi Tanggamus</h2>
<p class="font-body-sm text-body-sm text-on-surface-variant">Pengaturan ambang ongkos kirim dan interval waktu kirim kurir</p>
</div>
<button class="px-3 py-1.5 rounded-xl bg-surface-container-high hover:bg-surface-container-highest text-on-surface font-label-sm text-label-sm font-semibold transition" type="button">
            + Tambah Kecamatan
          </button>
</div>
<div class="space-y-3">
<!-- District 1 -->
<div class="p-4 rounded-xl bg-surface-container-low flex flex-col sm:flex-row sm:items-center justify-between gap-3">
<div class="space-y-0.5">
<div class="flex items-center gap-2">
<span class="font-headline-sm text-headline-sm text-on-surface">Kecamatan Gisting</span>
<span class="px-2 py-0.5 rounded-full bg-secondary-container text-on-secondary-container font-label-sm text-label-sm font-bold">Ring 1 (Pusat)</span>
</div>
<span class="font-body-sm text-body-sm text-on-surface-variant">Radius 0 - 8 Km • Estimasi tiba: 20-30 Menit</span>
</div>
<div class="flex items-center gap-4 text-right">
<div>
<span class="font-headline-sm text-headline-sm text-secondary block">Gratis Ongkir</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">Min. Order Rp 50.000</span>
</div>
<button class="p-2 rounded-lg bg-surface-container-highest hover:bg-surface-container-high text-on-surface" type="button">
<span class="material-symbols-outlined text-base">tune</span>
</button>
</div>
</div>
<!-- District 2 -->
<div class="p-4 rounded-xl bg-surface-container-low flex flex-col sm:flex-row sm:items-center justify-between gap-3">
<div class="space-y-0.5">
<div class="flex items-center gap-2">
<span class="font-headline-sm text-headline-sm text-on-surface">Kecamatan Talang Padang</span>
<span class="px-2 py-0.5 rounded-full bg-primary-fixed-dim text-on-primary-fixed-variant font-label-sm text-label-sm font-bold">Ring 2</span>
</div>
<span class="font-body-sm text-body-sm text-on-surface-variant">Radius 8 - 18 Km • Rute Pagi Subuh (06:00 WIB)</span>
</div>
<div class="flex items-center gap-4 text-right">
<div>
<span class="font-headline-sm text-headline-sm text-on-surface block">Rp 5.000</span>
<span class="font-label-sm text-label-sm text-secondary font-semibold">Gratis Min. 2 Krat</span>
</div>
<button class="p-2 rounded-lg bg-surface-container-highest hover:bg-surface-container-high text-on-surface" type="button">
<span class="material-symbols-outlined text-base">tune</span>
</button>
</div>
</div>
<!-- District 3 -->
<div class="p-4 rounded-xl bg-surface-container-low flex flex-col sm:flex-row sm:items-center justify-between gap-3">
<div class="space-y-0.5">
<div class="flex items-center gap-2">
<span class="font-headline-sm text-headline-sm text-on-surface">Kecamatan Kota Agung (Pesisir)</span>
<span class="px-2 py-0.5 rounded-full bg-tertiary-fixed text-on-tertiary-fixed font-label-sm text-label-sm font-bold">Ring 3</span>
</div>
<span class="font-body-sm text-body-sm text-on-surface-variant">Radius 20 - 35 Km • Armada Mobil Pick-up L300</span>
</div>
<div class="flex items-center gap-4 text-right">
<div>
<span class="font-headline-sm text-headline-sm text-on-surface block">Rp 12.000</span>
<span class="font-label-sm text-label-sm text-secondary font-semibold">Gratis Min. 5 Krat</span>
</div>
<button class="p-2 rounded-lg bg-surface-container-highest hover:bg-surface-container-high text-on-surface" type="button">
<span class="material-symbols-outlined text-base">tune</span>
</button>
</div>
</div>
</div>
</div>
<div class="mt-4 pt-3 flex items-center justify-between font-body-sm text-body-sm text-on-surface-variant">
<span>Pengaturan jadwal: <strong class="text-on-surface">Pengiriman Kloter Pagi (06:30) &amp; Sore (15:30)</strong></span>
<button class="text-primary hover:underline font-label-sm text-label-sm font-bold" type="button">Simpan Penyesuaian</button>
</div>
</div>
<!-- WhatsApp Gateway & Live Audit Logs (5 cols) -->
<div class="lg:col-span-5 rounded-2xl bg-surface-container-lowest p-6 shadow-sm flex flex-col justify-between">
<div>
<div class="flex items-center justify-between mb-4">
<div class="flex items-center gap-2">
<span class="w-3 h-3 rounded-full bg-secondary"></span>
<h2 class="font-headline-sm text-headline-sm text-on-surface">WhatsApp Gateway Notifikasi</h2>
</div>
<span class="font-label-sm text-label-sm font-bold text-secondary bg-secondary-container px-2 py-0.5 rounded">Aktif</span>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant mb-4">
          Pengiriman nota otomatis timbangan, resi foto telur utuh, dan konfirmasi transfer kurir via nomor resmi Bang Zul.
        </p>
<!-- Live Audit Activity Feed -->
<div class="space-y-3 font-body-sm text-body-sm">
<div class="p-3 rounded-xl bg-surface-container-low flex items-start gap-3">
<span class="material-symbols-outlined text-secondary text-base mt-0.5">mark_chat_read</span>
<div class="flex-1">
<div class="flex items-center justify-between">
<span class="font-label-md text-label-md font-bold text-on-surface">Nota Otomatis #BZ-9021</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">14:41</span>
</div>
<p class="text-on-surface-variant text-xs mt-0.5">Terkirim ke Warung Bu Nanik (Bukti timbang 15 kg bersih).</p>
</div>
</div>
<div class="p-3 rounded-xl bg-surface-container-low flex items-start gap-3">
<span class="material-symbols-outlined text-primary text-base mt-0.5">send</span>
<div class="flex-1">
<div class="flex items-center justify-between">
<span class="font-label-md text-label-md font-bold text-on-surface">Peringatan Stok Menipis</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">14:15</span>
</div>
<p class="text-on-surface-variant text-xs mt-0.5">Notifikasi kirim ke Kandang Mitra 3 (Telur Bebek sisa 2 krat).</p>
</div>
</div>
<div class="p-3 rounded-xl bg-surface-container-low flex items-start gap-3">
<span class="material-symbols-outlined text-tertiary text-base mt-0.5">receipt</span>
<div class="flex-1">
<div class="flex items-center justify-between">
<span class="font-label-md text-label-md font-bold text-on-surface">Garansi Penggantian</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">13:50</span>
</div>
<p class="text-on-surface-variant text-xs mt-0.5">Kompensasi 3 butir retak disetujui kurir Ahmad Yani.</p>
</div>
</div>
</div>
</div>
<!-- Quick Broadcast Trigger -->
<div class="mt-4 pt-4 border-t border-surface-container-high">
<button class="w-full py-2.5 px-4 rounded-xl bg-surface-container hover:bg-surface-container-high text-on-surface font-label-md text-label-md font-semibold flex items-center justify-center gap-2 transition" type="button">
<span class="material-symbols-outlined text-base text-secondary">campaign</span>
          Kirim Pengumuman Harga Telur Hari Ini ke Semua Mitra
        </button>
</div>
</div>
</section>
</div></main></div></body></html>

<!-- Katalog Produk Bang Zul Egg Market -->
<!DOCTYPE html>

<html lang="id"><head><meta charset="utf-8"/><meta content="width=device-width, initial-scale=1.0" name="viewport"/><meta content="web_standard" name="shell-type"/><link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" rel="stylesheet"/><link href="https://fonts.googleapis.com" rel="preconnect"/><link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/><link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&amp;family=Plus+Jakarta+Sans:wght@700;800&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/><style>@layer base{html,body{margin:0;padding:0;}body{overscroll-behavior:none;}main>:first-child{margin-top:0!important;}main>:last-child{margin-bottom:0!important;}}::-webkit-scrollbar{display:none;}</style><script src="https://cdn.tailwindcss.com"></script><script id="tailwind-config">tailwind.config={darkMode:"class",theme:{extend:{colors:{"on-primary-container":"#644000","on-secondary-fixed-variant":"#005312","surface":"#fcf9f8","on-tertiary-fixed-variant":"#3e4a41","on-secondary":"#ffffff","surface-container-lowest":"#ffffff","on-primary-fixed-variant":"#633f00","on-primary":"#ffffff","primary-container":"#f5a623","error":"#ba1a1a","tertiary-fixed":"#d9e6da","on-primary-fixed":"#291800","tertiary-fixed-dim":"#bdcabe","surface-container-high":"#eae7e7","surface-dim":"#dcd9d9","on-error-container":"#93000a","tertiary":"#556158","outline-variant":"#d7c3ae","secondary-container":"#a0f399","inverse-on-surface":"#f3f0f0","on-secondary-container":"#217128","background":"#fcf9f8","on-surface-variant":"#524534","on-error":"#ffffff","surface-variant":"#e4e2e1","surface-bright":"#fcf9f8","error-container":"#ffdad6","primary":"#835500","secondary-fixed":"#a3f69c","primary-fixed-dim":"#ffb955","inverse-surface":"#303030","on-background":"#1b1c1c","on-tertiary":"#ffffff","surface-tint":"#835500","on-tertiary-container":"#3e4a41","inverse-primary":"#ffb955","surface-container-low":"#f6f3f2","secondary-fixed-dim":"#88d982","on-surface":"#1b1c1c","tertiary-container":"#acb9ae","secondary":"#1b6d24","surface-container-highest":"#e4e2e1","surface-container":"#f0eded","primary-fixed":"#ffddb4","outline":"#857462","on-secondary-fixed":"#002204","on-tertiary-fixed":"#131e17"},borderRadius:{"DEFAULT":"0.25rem","lg":"0.5rem","xl":"0.75rem","full":"9999px"},spacing:{"gutter-desktop":"1.5rem","margin-desktop":"2.5rem","gutter":"1rem","space-lg":"1.5rem","space-xl":"2rem","margin":"1rem","space-md":"1rem","space-xs":"0.25rem","space-sm":"0.5rem"},fontFamily:{"body-md":["Inter"],"headline-lg-mobile":["Plus Jakarta Sans"],"headline-sm":["Plus Jakarta Sans"],"label-lg":["Inter"],"display-lg-mobile":["Plus Jakarta Sans"],"display-lg":["Plus Jakarta Sans"],"label-sm":["Inter"],"headline-lg":["Plus Jakarta Sans"],"stock-counter":["Inter"],"label-md":["Inter"],"headline-md":["Plus Jakarta Sans"],"body-sm":["Inter"],"price-display":["Plus Jakarta Sans"],"body-lg":["Inter"]},fontSize:{"body-md":["14px",{"lineHeight":"22px","fontWeight":"400"}],"headline-lg-mobile":["22px",{"lineHeight":"30px","letterSpacing":"0em","fontWeight":"700"}],"headline-sm":["16px",{"lineHeight":"24px","fontWeight":"700"}],"label-lg":["14px",{"lineHeight":"20px","fontWeight":"600"}],"display-lg-mobile":["30px",{"lineHeight":"38px","letterSpacing":"-0.01em","fontWeight":"800"}],"display-lg":["40px",{"lineHeight":"48px","letterSpacing":"-0.02em","fontWeight":"800"}],"label-sm":["11px",{"lineHeight":"14px","letterSpacing":"0.02em","fontWeight":"600"}],"headline-lg":["28px",{"lineHeight":"36px","letterSpacing":"-0.01em","fontWeight":"700"}],"stock-counter":["18px",{"lineHeight":"24px","letterSpacing":"0.01em","fontWeight":"700"}],"label-md":["12px",{"lineHeight":"16px","fontWeight":"600"}],"headline-md":["20px",{"lineHeight":"28px","fontWeight":"700"}],"body-sm":["12px",{"lineHeight":"18px","fontWeight":"400"}],"price-display":["22px",{"lineHeight":"28px","letterSpacing":"-0.02em","fontWeight":"800"}],"body-lg":["16px",{"lineHeight":"26px","fontWeight":"400"}]}}}}</script></head><body class="bg-surface font-body-md text-body-md text-on-surface antialiased"><header class="fixed top-0 left-0 w-full z-50 bg-surface/95 backdrop-blur-md shadow-[0_4px_20px_-2px_rgba(245,166,35,0.12)]"><div class="bg-secondary text-on-secondary px-4 py-1.5"><div class="max-w-7xl mx-auto flex flex-col md:flex-row items-center justify-between gap-1 text-label-sm font-label-sm"><div class="flex items-center gap-2 text-center md:text-left"><span class="material-symbols-outlined text-secondary-fixed text-sm">local_shipping</span><span>Pengiriman Segar Hari Ini ke Wilayah Kota Agung, Gisting, Talang Padang, Wonosobo, Pringsewu sekitarnya | <strong class="text-secondary-fixed">Gratis Ongkir Min. 2 Karpet/Tray</strong></span></div><a class="flex items-center gap-1.5 hover:text-secondary-fixed transition-colors whitespace-nowrap" href="https://wa.me/6281278900000"><span class="material-symbols-outlined text-sm">chat</span><span>WhatsApp CS Hubungi Bang Zul: 0812-7890-XXXX</span></a></div></div><div class="max-w-7xl mx-auto px-4 lg:px-8 py-3 flex items-center justify-between gap-4"><div class="flex items-center gap-3 shrink-0"><img alt="Logo Bang Zul Egg Market" class="h-8 w-auto object-contain" src="https://lh3.googleusercontent.com/aida/ALJJyrAvuhgJbL1OqXYnorOpflEwk9ch2RB3i3nIpJf2khBHtFUraZYLjA49xnoYr5_XpY1inx_yvUKDG-f5ULodcAC4hoBl9QYWujU07wAAJsvNI88PefRZRNH2SgRzcvtvfP9LlMDgvobQRRrHxWwLlWY8MQoR1CS4kennwXqXJqn5PR3R5zkf-p4q0eleDblVHlCAtE__Wj8FbqU6db9zlBw02jnLdLpow_xGCN8RF4es"/><div class="flex flex-col"><span class="font-headline-md text-headline-md text-primary tracking-tight leading-none">Bang Zul</span><span class="font-label-sm text-label-sm text-secondary font-bold tracking-wider uppercase leading-none mt-0.5">Egg Market Tanggamus</span></div></div><div class="hidden lg:flex items-center gap-1.5 px-3 py-1.5 rounded-full bg-surface-container-low text-on-surface-variant font-label-sm text-label-sm shrink-0"><span class="material-symbols-outlined text-primary text-base">location_on</span><span class="max-w-[210px] truncate">Kab. Tanggamus (Gisting, Kota Agung &amp; Sekitarnya)</span></div><div class="hidden md:flex flex-1 max-w-md mx-2"><div class="relative w-full flex items-center"><span class="material-symbols-outlined absolute left-3 text-outline text-lg">search</span><input class="w-full pl-10 pr-4 py-2 rounded-full bg-surface-container-lowest text-body-sm font-body-sm text-on-surface placeholder:text-outline focus:outline-none focus:ring-2 focus:ring-primary-container shadow-[0_1px_4px_rgba(0,0,0,0.04)]" placeholder="Cari telur ayam ras, telur omega, telur bebek, puyuh..." type="text"/></div></div><div class="hidden xl:flex items-center p-1 rounded-xl bg-surface-container"><nav class="flex items-center gap-1" data-active-classes="bg-surface-container-lowest text-primary shadow-sm font-bold"><a class="px-3 py-1 rounded-lg text-label-sm font-label-sm text-on-surface-variant hover:text-on-surface transition-all" data-path="katalog-belanja" href="#">Belanja (Pembeli)</a><a class="px-3 py-1 rounded-lg text-label-sm font-label-sm text-on-surface-variant hover:text-on-surface transition-all" data-path="toko-bang-zul" href="#">Toko Bang Zul (Penjual)</a><a class="px-3 py-1 rounded-lg text-label-sm font-label-sm text-on-surface-variant hover:text-on-surface transition-all" data-path="kurir-tanggamus" href="#">Kurir Tanggamus</a><a class="px-3 py-1 rounded-lg text-label-sm font-label-sm text-on-surface-variant hover:text-on-surface transition-all" data-path="admin-pasar" href="#">Admin</a></nav></div><div class="flex items-center gap-2 md:gap-3 shrink-0"><button aria-label="Notifikasi Pesanan" class="p-2 rounded-full hover:bg-surface-container-high text-on-surface-variant relative" type="button"><span class="material-symbols-outlined text-xl">notifications</span><span class="absolute top-1.5 right-1.5 w-2 h-2 rounded-full bg-error"></span></button><a class="flex items-center gap-2 px-3 py-1.5 rounded-full bg-primary-container text-on-primary-container hover:bg-primary-fixed-dim transition-colors shadow-sm" data-path="keranjang-belanja" href="#"><span class="material-symbols-outlined text-lg">shopping_basket</span><span class="hidden sm:inline font-label-sm text-label-sm">Rp 84.000 (3 item)</span></a><div class="flex items-center gap-2 pl-1"><img alt="Profile" class="w-8 h-8 rounded-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBu4cCay1o-kcZkrepBjdwRhNkTeb5NSNF4V20H1AoEXr4ahIrRP9SktX37TUve3u7us_GHnlm1279EoAyYcFxqZTZV4CIOdstOTCqIMcitiPTCwpWm4m2okjdh9z8S2I2n0sK1hb3y3ohWU84Tu6ZWNoxKL7D1NVLhMsBA3C6eHNQmukclnmKpMzHXssx-xtkh1wF2y2OFEDgXUgTPjjAfLabaOsUrz91MId6by4k"/><span class="hidden 2xl:inline font-label-sm text-label-sm text-on-surface font-semibold">Bang Zul</span></div></div></div><div class="bg-surface-container-lowest shadow-[0_1px_4px_rgba(0,0,0,0.02)] overflow-x-auto"><div class="max-w-7xl mx-auto px-4 lg:px-8"><nav class="flex items-center gap-6 whitespace-nowrap py-2.5 text-label-sm font-label-sm" data-active-classes="text-primary font-bold border-b-2 border-primary"><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="katalog-belanja" href="#">Semua Produk</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="telur-ayam-ras" href="#">Telur Ayam Ras (Kiloan &amp; Karpet)</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="telur-ayam-kampung-omega" href="#">Telur Ayam Kampung &amp; Omega</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="telur-bebek-asin-mentah" href="#">Telur Bebek Asin &amp; Mentah</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="telur-puyuh" href="#">Telur Puyuh</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="paket-grosir-rumah-makan" href="#">Paket Grosir &amp; Rumah Makan</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1 flex items-center gap-1.5" data-path="jadwal-panen-stok" href="#"><span class="w-2 h-2 rounded-full bg-secondary inline-block animate-pulse"></span>Jadwal Panen &amp; Stok Realtime</a></nav></div></div></header><main class="w-full pt-36 bg-surface min-h-screen"><div class="flex flex-col w-full">
<!-- Top Notice & Realtime Harvest Banner -->
<div class="w-full bg-surface-container-low py-2.5 px-4 lg:px-8">
<div class="max-w-7xl mx-auto flex flex-wrap items-center justify-between gap-3 text-label-sm font-label-sm">
<nav class="flex items-center gap-1.5 text-on-surface-variant">
<a class="hover:text-primary transition-colors flex items-center gap-1" href="#">
<span class="material-symbols-outlined text-sm">home</span>
<span>Beranda</span>
</a>
<span class="text-outline-variant">/</span>
<span class="text-primary font-bold">Katalog Telur Segar Tanggamus</span>
</nav>
<div class="flex items-center gap-2 bg-surface-container-lowest px-3 py-1 rounded-full shadow-sm">
<span class="w-2 h-2 rounded-full bg-secondary animate-pulse"></span>
<span class="text-secondary font-bold">Pembaruan Stok &amp; Harga Panen:</span>
<span class="text-on-surface-variant font-medium">Hari ini 06.00 WIB (Kandang Mitra Gisting &amp; Wonosobo)</span>
</div>
</div>
</div>
<!-- Header Section with Assurance Strip -->
<section class="w-full bg-surface-container-lowest py-8 px-4 lg:px-8 shadow-sm">
<div class="max-w-7xl mx-auto flex flex-col md:flex-row md:items-end justify-between gap-6">
<div class="max-w-3xl">
<div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-secondary-container text-on-secondary-container font-label-sm text-label-sm mb-3">
<span class="material-symbols-outlined text-base">verified</span>
<span>100% Telur Baru Dipanen • Garansi Timbangan Presisi</span>
</div>
<h1 class="font-headline-lg text-headline-lg text-on-surface tracking-tight">
          Katalog Lengkap Telur Segar Peternakan
        </h1>
<p class="font-body-md text-body-md text-on-surface-variant mt-2">
          Dipanen pagi hari dari mitra kandang Gisting &amp; Talang Padang. Bebas timbangan kurang, garansi ganti telur retak seketika tanpa ribet langsung oleh kurir Bang Zul.
        </p>
</div>
<!-- Quick Trust Badges -->
<div class="flex items-center gap-3 shrink-0">
<div class="flex items-center gap-2 p-3 bg-surface-container-low rounded-xl">
<span class="material-symbols-outlined text-primary text-2xl">scale</span>
<div class="flex flex-col">
<span class="font-label-sm text-label-sm text-on-surface font-bold">Timbangan Digital</span>
<span class="font-body-sm text-body-sm text-on-surface-variant">Tera Ulang Harian</span>
</div>
</div>
<div class="flex items-center gap-2 p-3 bg-surface-container-low rounded-xl">
<span class="material-symbols-outlined text-secondary text-2xl">egg</span>
<div class="flex flex-col">
<span class="font-label-sm text-label-sm text-on-surface font-bold">Garansi Retak</span>
<span class="font-body-sm text-body-sm text-on-surface-variant">Diganti Di Tempat</span>
</div>
</div>
</div>
</div>
</section>
<!-- Main Catalog Content Container -->
<div class="w-full max-w-7xl mx-auto px-4 lg:px-8 py-8">
<!-- Top Control Bar (Search, Sorting, Views) -->
<div class="w-full bg-surface-container-lowest p-4 rounded-2xl shadow-sm mb-6 flex flex-col lg:flex-row items-stretch lg:items-center justify-between gap-4">
<!-- Search Input -->
<div class="relative flex-1 max-w-xl">
<span class="material-symbols-outlined absolute left-3.5 top-1/2 -translate-y-1/2 text-outline text-xl">search</span>
<input class="w-full pl-11 pr-4 py-2.5 bg-surface-container-low rounded-xl text-body-md font-body-md text-on-surface placeholder:text-outline focus:outline-none focus:bg-surface-container-lowest focus:ring-2 focus:ring-primary-container shadow-inner transition-all" id="productSearchInput" placeholder="Cari jenis telur, mika, tray/karpet, atau grosir warung..." type="text"/>
</div>
<!-- Control Right (Result Count, Filter Button for Mobile, Sort, Toggle Grid) -->
<div class="flex flex-wrap items-center justify-between lg:justify-end gap-3">
<!-- Mobile Filter Toggle Button -->
<button class="lg:hidden flex items-center gap-2 px-3.5 py-2 bg-primary-container text-on-primary-container font-label-md text-label-md rounded-xl shadow-sm hover:bg-primary-fixed-dim transition-colors" id="mobileFilterOpenBtn" type="button">
<span class="material-symbols-outlined text-base">tune</span>
<span>Filter Produk (3)</span>
</button>
<span class="hidden sm:inline font-body-sm text-body-sm text-on-surface-variant whitespace-nowrap">
          Menampilkan <strong class="text-on-surface font-bold">9</strong> dari <strong class="text-on-surface font-bold">12</strong> varian
        </span>
<!-- Sorting Dropdown -->
<div class="relative flex items-center bg-surface-container-low rounded-xl px-3 py-1.5">
<span class="material-symbols-outlined text-outline text-base mr-1.5">sort</span>
<label class="sr-only" for="catalogSort">Urutkan</label>
<select class="bg-transparent text-label-md font-label-md text-on-surface focus:outline-none cursor-pointer pr-4" id="catalogSort">
<option value="populer">Paling Laris</option>
<option value="termurah">Harga Termurah</option>
<option value="termahal">Harga Termahal</option>
<option value="terbaru">Panen Terbaru</option>
</select>
</div>
<!-- View Grid/List Switcher -->
<div class="hidden md:flex items-center p-1 bg-surface-container-low rounded-xl">
<button aria-label="Tampilan Grid" class="p-1.5 rounded-lg bg-surface-container-lowest text-primary shadow-sm" id="viewGridBtn" type="button">
<span class="material-symbols-outlined text-base">grid_view</span>
</button>
<button aria-label="Tampilan Baris" class="p-1.5 rounded-lg text-outline hover:text-on-surface transition-colors" id="viewListBtn" type="button">
<span class="material-symbols-outlined text-base">view_list</span>
</button>
</div>
</div>
</div>
<!-- Layout Columns: Sticky Filter Sidebar + Product Grid -->
<div class="flex flex-col lg:flex-row items-start gap-8">
<!-- Left Sidebar Filter (Desktop) -->
<aside class="hidden lg:block w-72 shrink-0 sticky top-40 space-y-6">
<div class="bg-surface-container-lowest p-5 rounded-2xl shadow-sm space-y-6">
<div class="flex items-center justify-between pb-3 border-b-0">
<div class="flex items-center gap-2">
<span class="material-symbols-outlined text-primary text-xl">filter_alt</span>
<h2 class="font-headline-sm text-headline-sm text-on-surface">Filter Belanja</h2>
</div>
<button class="text-label-sm font-label-sm text-primary hover:underline" type="button">Reset</button>
</div>
<!-- Kategori Filter -->
<div class="space-y-3">
<h3 class="font-label-md text-label-md text-on-surface uppercase tracking-wider font-bold">Kategori Telur</h3>
<div class="space-y-2 text-body-sm font-body-sm text-on-surface-variant">
<label class="flex items-center justify-between cursor-pointer hover:text-on-surface">
<span class="flex items-center gap-2">
<input checked="" class="w-4 h-4 rounded text-primary focus:ring-primary accent-primary" type="checkbox"/>
<span>Semua Kategori</span>
</span>
<span class="text-label-sm font-label-sm text-outline">12</span>
</label>
<label class="flex items-center justify-between cursor-pointer hover:text-on-surface">
<span class="flex items-center gap-2">
<input checked="" class="w-4 h-4 rounded text-primary focus:ring-primary accent-primary" type="checkbox"/>
<span>Telur Ayam Ras / Harian</span>
</span>
<span class="text-label-sm font-label-sm text-outline">4</span>
</label>
<label class="flex items-center justify-between cursor-pointer hover:text-on-surface">
<span class="flex items-center gap-2">
<input checked="" class="w-4 h-4 rounded text-primary focus:ring-primary accent-primary" type="checkbox"/>
<span>Ayam Kampung &amp; Omega-3</span>
</span>
<span class="text-label-sm font-label-sm text-outline">3</span>
</label>
<label class="flex items-center justify-between cursor-pointer hover:text-on-surface">
<span class="flex items-center gap-2">
<input checked="" class="w-4 h-4 rounded text-primary focus:ring-primary accent-primary" type="checkbox"/>
<span>Telur Bebek Tambak &amp; Asin</span>
</span>
<span class="text-label-sm font-label-sm text-outline">3</span>
</label>
<label class="flex items-center justify-between cursor-pointer hover:text-on-surface">
<span class="flex items-center gap-2">
<input class="w-4 h-4 rounded text-primary focus:ring-primary accent-primary" type="checkbox"/>
<span>Telur Puyuh Gurih</span>
</span>
<span class="text-label-sm font-label-sm text-outline">2</span>
</label>
<label class="flex items-center justify-between cursor-pointer hover:text-on-surface">
<span class="flex items-center gap-2">
<input class="w-4 h-4 rounded text-primary focus:ring-primary accent-primary" type="checkbox"/>
<span>Paket Grosir &amp; Warung</span>
</span>
<span class="text-label-sm font-label-sm text-outline">2</span>
</label>
</div>
</div>
<div class="h-px bg-surface-container"></div>
<!-- Rentang Harga Filter -->
<div class="space-y-3">
<h3 class="font-label-md text-label-md text-on-surface uppercase tracking-wider font-bold">Rentang Harga (Rp)</h3>
<div class="grid grid-cols-2 gap-2 text-label-sm font-label-sm">
<div>
<span class="text-outline text-[10px] block uppercase">Min</span>
<div class="bg-surface-container-low px-2 py-1.5 rounded-lg text-on-surface font-semibold">20.000</div>
</div>
<div>
<span class="text-outline text-[10px] block uppercase">Maks</span>
<div class="bg-surface-container-low px-2 py-1.5 rounded-lg text-on-surface font-semibold">300.000</div>
</div>
</div>
<input class="w-full h-1.5 bg-surface-container rounded-lg appearance-none cursor-pointer accent-primary" max="300000" min="20000" step="5000" type="range" value="250000"/>
<div class="flex flex-wrap gap-1.5 pt-1">
<button class="px-2 py-1 bg-surface-container-low hover:bg-surface-container text-on-surface-variant font-label-sm text-[11px] rounded-md transition-colors" type="button">&lt; 30rb</button>
<button class="px-2 py-1 bg-primary-fixed text-on-primary-fixed font-label-sm text-[11px] rounded-md font-bold" type="button">30rb - 60rb</button>
<button class="px-2 py-1 bg-surface-container-low hover:bg-surface-container text-on-surface-variant font-label-sm text-[11px] rounded-md transition-colors" type="button">&gt; 60rb</button>
</div>
</div>
<div class="h-px bg-surface-container"></div>
<!-- Ketersediaan Stok -->
<div class="space-y-3">
<h3 class="font-label-md text-label-md text-on-surface uppercase tracking-wider font-bold">Status Stok Panen</h3>
<div class="space-y-2 text-body-sm font-body-sm text-on-surface-variant">
<label class="flex items-center justify-between cursor-pointer hover:text-on-surface">
<span class="flex items-center gap-2">
<input checked="" class="w-4 h-4 rounded text-secondary focus:ring-secondary accent-secondary" type="checkbox"/>
<span class="flex items-center gap-1.5">
<span class="w-2 h-2 rounded-full bg-secondary"></span>
<span>Ready Kandang</span>
</span>
</span>
<span class="text-label-sm font-label-sm text-outline">8</span>
</label>
<label class="flex items-center justify-between cursor-pointer hover:text-on-surface">
<span class="flex items-center gap-2">
<input checked="" class="w-4 h-4 rounded text-primary focus:ring-primary accent-primary" type="checkbox"/>
<span class="flex items-center gap-1.5">
<span class="w-2 h-2 rounded-full bg-primary-container"></span>
<span>Stok Menipis</span>
</span>
</span>
<span class="text-label-sm font-label-sm text-outline">3</span>
</label>
<label class="flex items-center justify-between cursor-pointer hover:text-on-surface">
<span class="flex items-center gap-2">
<input class="w-4 h-4 rounded text-outline focus:ring-outline accent-outline" type="checkbox"/>
<span class="flex items-center gap-1.5">
<span class="w-2 h-2 rounded-full bg-outline"></span>
<span>Pre-order Panen Besok</span>
</span>
</span>
<span class="text-label-sm font-label-sm text-outline">1</span>
</label>
</div>
</div>
<div class="h-px bg-surface-container"></div>
<!-- Kemasan / Satuan -->
<div class="space-y-3">
<h3 class="font-label-md text-label-md text-on-surface uppercase tracking-wider font-bold">Pilihan Kemasan</h3>
<div class="space-y-2 text-body-sm font-body-sm text-on-surface-variant">
<label class="flex items-center gap-2 cursor-pointer hover:text-on-surface">
<input checked="" class="w-4 h-4 rounded text-primary accent-primary" type="checkbox"/>
<span>Karpet / Tray Karton (30 Btr)</span>
</label>
<label class="flex items-center gap-2 cursor-pointer hover:text-on-surface">
<input checked="" class="w-4 h-4 rounded text-primary accent-primary" type="checkbox"/>
<span>Mika Higienis (10-15 Btr)</span>
</label>
<label class="flex items-center gap-2 cursor-pointer hover:text-on-surface">
<input class="w-4 h-4 rounded text-primary accent-primary" type="checkbox"/>
<span>Kiloan Timbangan Digital</span>
</label>
<label class="flex items-center gap-2 cursor-pointer hover:text-on-surface">
<input class="w-4 h-4 rounded text-primary accent-primary" type="checkbox"/>
<span>Peti Kayu Grosir (10-15 Kg)</span>
</label>
</div>
</div>
<button class="w-full py-2.5 bg-primary text-on-primary font-label-md text-label-md rounded-xl hover:opacity-90 transition-opacity shadow-sm" type="button">
            Terapkan Filter
          </button>
</div>
<!-- Info Garansi Card -->
<div class="bg-surface-container p-4 rounded-2xl flex items-start gap-3">
<span class="material-symbols-outlined text-secondary text-2xl shrink-0">local_police</span>
<div class="flex flex-col text-on-surface">
<span class="font-headline-sm text-headline-sm">Komitmen Bang Zul</span>
<p class="font-body-sm text-body-sm text-on-surface-variant mt-1">
              Telur pecah atau timbangan susut saat sampai? Kami ganti seketika di tempat saat kurir menyerahkan pesanan.
            </p>
</div>
</div>
</aside>
<!-- Right Main: Product Grid Area -->
<section class="flex-1 w-full">
<!-- Active Filter Pills -->
<div class="flex flex-wrap items-center gap-2 mb-6">
<span class="font-label-sm text-label-sm text-on-surface-variant">Filter Aktif:</span>
<span class="inline-flex items-center gap-1.5 px-3 py-1 bg-surface-container-lowest text-on-surface rounded-full text-label-sm font-label-sm shadow-sm">
<span>Ayam Ras, Kampung, Bebek</span>
<button aria-label="Hapus filter" class="material-symbols-outlined text-xs hover:text-error" type="button">close</button>
</span>
<span class="inline-flex items-center gap-1.5 px-3 py-1 bg-surface-container-lowest text-on-surface rounded-full text-label-sm font-label-sm shadow-sm">
<span>Ready &amp; Menipis</span>
<button aria-label="Hapus filter" class="material-symbols-outlined text-xs hover:text-error" type="button">close</button>
</span>
<span class="inline-flex items-center gap-1.5 px-3 py-1 bg-surface-container-lowest text-on-surface rounded-full text-label-sm font-label-sm shadow-sm">
<span>Rp 20.000 - Rp 250.000</span>
<button aria-label="Hapus filter" class="material-symbols-outlined text-xs hover:text-error" type="button">close</button>
</span>
<button class="text-label-sm font-label-sm text-primary hover:underline ml-1" type="button">
            Hapus Semua
          </button>
</div>
<!-- 9 Comprehensive Product Cards Grid -->
<div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6" id="productGridContainer">
<!-- Card 1: Telur Ayam Ras Super Karpet -->
<div class="group bg-surface-container-lowest rounded-2xl shadow-[0_4px_20px_-2px_rgba(245,166,35,0.12)] overflow-hidden flex flex-col justify-between hover:-translate-y-1 transition-transform duration-200">
<div>
<div class="relative w-full h-48 overflow-hidden bg-surface-container">
<img alt="Telur Ayam Ras Super Karpet 30 butir di atas tray karton cokelat pedesaan Tanggamus" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" src="https://lh3.googleusercontent.com/aida/ALJJyrBzqMYG7Kl3hKy_p8nmJCwyUDMb9FuoWxtyPnCVshW0vlklRkQ8Xy7vFl0RvF3bpisL0Irwd7esKCjJEmLHvESjfIo6_VPaZAlZ6m9_14CJcBrhht5Bbrm30ZAyGvbSK2DPqWbJsn5e7j1AyP1gbHXHFsDh2tdRCD2f8QSQqGGP6lzamocq3RE1dYp9UUjEsXptiGyYrh-H6-yMG2qkynIwtxDdxzKakoydZ5XL-_lp"/>
<div class="absolute top-3 left-3 flex flex-col gap-1.5">
<span class="px-2.5 py-1 bg-primary text-on-primary font-label-sm text-label-sm rounded-lg font-bold shadow-sm">
                    Ayam Ras
                  </span>
<span class="px-2 py-0.5 bg-surface-container-lowest/90 backdrop-blur-sm text-on-surface font-label-sm text-[11px] rounded-md shadow-sm">
                    Tray 30 Butir
                  </span>
</div>
<div class="absolute top-3 right-3">
<span class="inline-flex items-center gap-1 px-2.5 py-1 bg-secondary-container text-on-secondary-container font-label-sm text-label-sm rounded-full shadow-sm font-bold">
<span class="w-1.5 h-1.5 rounded-full bg-secondary"></span>
                    Tersedia 140 Krat
                  </span>
</div>
</div>
<div class="p-4 space-y-2">
<div class="flex items-center justify-between text-label-sm font-label-sm text-on-surface-variant">
<span class="flex items-center gap-1 text-primary">
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<strong class="text-on-surface">4.9</strong> (182 ulasan)
                  </span>
<span>Peternak Gisting</span>
</div>
<h3 class="font-headline-sm text-headline-sm text-on-surface line-clamp-1 group-hover:text-primary transition-colors">
                  Telur Ayam Ras Super Karpet (30 Butir)
                </h3>
<p class="font-body-sm text-body-sm text-on-surface-variant line-clamp-2">
                  Cangkang cokelat tebal tidak mudah pecah, kuning telur jingga cerah kaya nutrisi, dipanen pagi hari langsung.
                </p>
<div class="pt-2 flex items-baseline gap-1.5">
<span class="font-price-display text-price-display text-primary font-extrabold">Rp 52.000</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">/ karpet</span>
</div>
</div>
</div>
<!-- Footer Actions -->
<div class="p-4 pt-0 mt-2 flex items-center gap-2">
<div class="flex items-center bg-surface-container-low rounded-xl p-1 shrink-0">
<button aria-label="Kurang satu" class="w-7 h-7 flex items-center justify-center rounded-lg bg-surface-container-lowest text-on-surface hover:text-primary font-bold text-sm shadow-sm" type="button">-</button>
<span class="w-8 text-center font-stock-counter text-stock-counter text-on-surface text-sm">1</span>
<button aria-label="Tambah satu" class="w-7 h-7 flex items-center justify-center rounded-lg bg-surface-container-lowest text-on-surface hover:text-primary font-bold text-sm shadow-sm" type="button">+</button>
</div>
<button class="flex-1 flex items-center justify-center gap-1.5 py-2.5 px-3 bg-primary-container text-on-primary-container hover:bg-primary-fixed-dim font-label-md text-label-md rounded-xl shadow-sm transition-colors" type="button">
<span class="material-symbols-outlined text-lg">add_shopping_cart</span>
<span>Beli</span>
</button>
</div>
</div>
<!-- Card 2: Telur Ayam Kampung Asli & Omega-3 -->
<div class="group bg-surface-container-lowest rounded-2xl shadow-[0_4px_20px_-2px_rgba(245,166,35,0.12)] overflow-hidden flex flex-col justify-between hover:-translate-y-1 transition-transform duration-200">
<div>
<div class="relative w-full h-48 overflow-hidden bg-surface-container">
<img alt="Telur ayam kampung organik ditata dalam mangkuk anyaman bambu dengan jerami alami pedesaan" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" src="https://lh3.googleusercontent.com/aida/ALJJyrC1SGftVAYQef-pQHbHgfQLSDiRN-Kl6-t0MQpnRpN_Eyc7YJ_zSRzdh2VMfvw6WZCcDYP0dZcn8A_3ViAAwIT5niDoPYnsh0k4uD1eu1zLx1_km8KNzZXu1KIuF8DXWTcZw4opzPR-ngEThaz1RQXxc4BuVzj4G5GT1BdRzZDneycOBwixJ5CszSwACq8vbrUlNioxOMU1jXfl0vXSymjM4CJLA_CYasKmLKkUTZ4r"/>
<div class="absolute top-3 left-3 flex flex-col gap-1.5">
<span class="px-2.5 py-1 bg-secondary text-on-secondary font-label-sm text-label-sm rounded-lg font-bold shadow-sm">
                    Ayam Kampung
                  </span>
<span class="px-2 py-0.5 bg-surface-container-lowest/90 backdrop-blur-sm text-on-surface font-label-sm text-[11px] rounded-md shadow-sm">
                    Mika 10 Butir
                  </span>
</div>
<div class="absolute top-3 right-3">
<span class="inline-flex items-center gap-1 px-2.5 py-1 bg-secondary-container text-on-secondary-container font-label-sm text-label-sm rounded-full shadow-sm font-bold">
<span class="w-1.5 h-1.5 rounded-full bg-secondary"></span>
                    Tersedia 45 Pack
                  </span>
</div>
</div>
<div class="p-4 space-y-2">
<div class="flex items-center justify-between text-label-sm font-label-sm text-on-surface-variant">
<span class="flex items-center gap-1 text-primary">
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<strong class="text-on-surface">5.0</strong> (94 ulasan)
                  </span>
<span>Peternak Talang Padang</span>
</div>
<h3 class="font-headline-sm text-headline-sm text-on-surface line-clamp-1 group-hover:text-primary transition-colors">
                  Telur Ayam Kampung Asli &amp; Omega-3
                </h3>
<p class="font-body-sm text-body-sm text-on-surface-variant line-clamp-2">
                  Dihasilkan dari ayam liar umbaran dengan pakan jagung giling dan minyak ikan. Sangat cocok untuk jamu dan MPASI.
                </p>
<div class="pt-2 flex items-baseline gap-1.5">
<span class="font-price-display text-price-display text-primary font-extrabold">Rp 38.000</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">/ pack (10 btr)</span>
</div>
</div>
</div>
<!-- Footer Actions -->
<div class="p-4 pt-0 mt-2 flex items-center gap-2">
<div class="flex items-center bg-surface-container-low rounded-xl p-1 shrink-0">
<button aria-label="Kurang satu" class="w-7 h-7 flex items-center justify-center rounded-lg bg-surface-container-lowest text-on-surface hover:text-primary font-bold text-sm shadow-sm" type="button">-</button>
<span class="w-8 text-center font-stock-counter text-stock-counter text-on-surface text-sm">1</span>
<button aria-label="Tambah satu" class="w-7 h-7 flex items-center justify-center rounded-lg bg-surface-container-lowest text-on-surface hover:text-primary font-bold text-sm shadow-sm" type="button">+</button>
</div>
<button class="flex-1 flex items-center justify-center gap-1.5 py-2.5 px-3 bg-primary-container text-on-primary-container hover:bg-primary-fixed-dim font-label-md text-label-md rounded-xl shadow-sm transition-colors" type="button">
<span class="material-symbols-outlined text-lg">add_shopping_cart</span>
<span>Beli</span>
</button>
</div>
</div>
<!-- Card 3: Telur Bebek Tambak Segar -->
<div class="group bg-surface-container-lowest rounded-2xl shadow-[0_4px_20px_-2px_rgba(245,166,35,0.12)] overflow-hidden flex flex-col justify-between hover:-translate-y-1 transition-transform duration-200">
<div>
<div class="relative w-full h-48 overflow-hidden bg-surface-container">
<img alt="Telur bebek tambak cangkang hijau kebiruan segar dan telur puyuh di kotak kayu pasar tradisional" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" src="https://lh3.googleusercontent.com/aida/ALJJyrBKCKpIVcWaQCmMaCGIR-JnYlS7flXYZP0d1ynbnZ7n-BHPxjb47g5yPlKh3JwUiCJF4NeX18yvHr85xF_wtioxtaraCp5fYzhGpyOTF_u3GgHWn5rYJaYifGhNEXtai5szKMlDDX5QyKA58bLxu92uwdrcTOkqPvcVqEjMyEQ5dz9aeZZYd3xAKlU-TeSwrD1H4AJgNnSObJuJKwlvwOtz9ZmwNvqvFCQ7q37iP7Dy"/>
<div class="absolute top-3 left-3 flex flex-col gap-1.5">
<span class="px-2.5 py-1 bg-tertiary text-on-tertiary font-label-sm text-label-sm rounded-lg font-bold shadow-sm">
                    Bebek Tambak
                  </span>
<span class="px-2 py-0.5 bg-surface-container-lowest/90 backdrop-blur-sm text-on-surface font-label-sm text-[11px] rounded-md shadow-sm">
                    Pack 10 Butir
                  </span>
</div>
<div class="absolute top-3 right-3">
<span class="inline-flex items-center gap-1 px-2.5 py-1 bg-secondary-container text-on-secondary-container font-label-sm text-label-sm rounded-full shadow-sm font-bold">
<span class="w-1.5 h-1.5 rounded-full bg-secondary"></span>
                    Tersedia 60 Pack
                  </span>
</div>
</div>
<div class="p-4 space-y-2">
<div class="flex items-center justify-between text-label-sm font-label-sm text-on-surface-variant">
<span class="flex items-center gap-1 text-primary">
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<strong class="text-on-surface">4.8</strong> (76 ulasan)
                  </span>
<span>Mitra Rawa Wonosobo</span>
</div>
<h3 class="font-headline-sm text-headline-sm text-on-surface line-clamp-1 group-hover:text-primary transition-colors">
                  Telur Bebek Tambak Segar (Pack 10 Btr)
                </h3>
<p class="font-body-sm text-body-sm text-on-surface-variant line-clamp-2">
                  Cangkang hijau kebiruan bersih, butiran besar padat, siap dimasak martabak telur atau olahan gulai gurih.
                </p>
<div class="pt-2 flex items-baseline gap-1.5">
<span class="font-price-display text-price-display text-primary font-extrabold">Rp 32.000</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">/ pack</span>
</div>
</div>
</div>
<!-- Footer Actions -->
<div class="p-4 pt-0 mt-2 flex items-center gap-2">
<div class="flex items-center bg-surface-container-low rounded-xl p-1 shrink-0">
<button aria-label="Kurang satu" class="w-7 h-7 flex items-center justify-center rounded-lg bg-surface-container-lowest text-on-surface hover:text-primary font-bold text-sm shadow-sm" type="button">-</button>
<span class="w-8 text-center font-stock-counter text-stock-counter text-on-surface text-sm">1</span>
<button aria-label="Tambah satu" class="w-7 h-7 flex items-center justify-center rounded-lg bg-surface-container-lowest text-on-surface hover:text-primary font-bold text-sm shadow-sm" type="button">+</button>
</div>
<button class="flex-1 flex items-center justify-center gap-1.5 py-2.5 px-3 bg-primary-container text-on-primary-container hover:bg-primary-fixed-dim font-label-md text-label-md rounded-xl shadow-sm transition-colors" type="button">
<span class="material-symbols-outlined text-lg">add_shopping_cart</span>
<span>Beli</span>
</button>
</div>
</div>
<!-- Card 4: Telur Puyuh Segar Peternak Wonosobo -->
<div class="group bg-surface-container-lowest rounded-2xl shadow-[0_4px_20px_-2px_rgba(245,166,35,0.12)] overflow-hidden flex flex-col justify-between hover:-translate-y-1 transition-transform duration-200">
<div>
<div class="relative w-full h-48 overflow-hidden bg-surface-container">
<img alt="Detail tumpukan telur puyuh berbintik hitam alami dalam wadah kayu higienis" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" src="https://lh3.googleusercontent.com/aida/ALJJyrBKCKpIVcWaQCmMaCGIR-JnYlS7flXYZP0d1ynbnZ7n-BHPxjb47g5yPlKh3JwUiCJF4NeX18yvHr85xF_wtioxtaraCp5fYzhGpyOTF_u3GgHWn5rYJaYifGhNEXtai5szKMlDDX5QyKA58bLxu92uwdrcTOkqPvcVqEjMyEQ5dz9aeZZYd3xAKlU-TeSwrD1H4AJgNnSObJuJKwlvwOtz9ZmwNvqvFCQ7q37iP7Dy"/>
<div class="absolute top-3 left-3 flex flex-col gap-1.5">
<span class="px-2.5 py-1 bg-on-tertiary-container text-on-tertiary font-label-sm text-label-sm rounded-lg font-bold shadow-sm">
                    Telur Puyuh
                  </span>
<span class="px-2 py-0.5 bg-surface-container-lowest/90 backdrop-blur-sm text-on-surface font-label-sm text-[11px] rounded-md shadow-sm">
                    Mika 50 Butir
                  </span>
</div>
<div class="absolute top-3 right-3">
<span class="inline-flex items-center gap-1 px-2.5 py-1 bg-secondary-container text-on-secondary-container font-label-sm text-label-sm rounded-full shadow-sm font-bold">
<span class="w-1.5 h-1.5 rounded-full bg-secondary"></span>
                    Tersedia 30 Mika
                  </span>
</div>
</div>
<div class="p-4 space-y-2">
<div class="flex items-center justify-between text-label-sm font-label-sm text-on-surface-variant">
<span class="flex items-center gap-1 text-primary">
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<strong class="text-on-surface">4.9</strong> (52 ulasan)
                  </span>
<span>Wonosobo Tanggamus</span>
</div>
<h3 class="font-headline-sm text-headline-sm text-on-surface line-clamp-1 group-hover:text-primary transition-colors">
                  Telur Puyuh Segar Peternak Wonosobo (Mika 50 Btr)
                </h3>
<p class="font-body-sm text-body-sm text-on-surface-variant line-clamp-2">
                  Gurih dan manis alami untuk sop, sate telur puyuh, dan bekal anak sekolah. Bebas bau amis menyengat.
                </p>
<div class="pt-2 flex items-baseline gap-1.5">
<span class="font-price-display text-price-display text-primary font-extrabold">Rp 22.000</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">/ mika (50 btr)</span>
</div>
</div>
</div>
<!-- Footer Actions -->
<div class="p-4 pt-0 mt-2 flex items-center gap-2">
<div class="flex items-center bg-surface-container-low rounded-xl p-1 shrink-0">
<button aria-label="Kurang satu" class="w-7 h-7 flex items-center justify-center rounded-lg bg-surface-container-lowest text-on-surface hover:text-primary font-bold text-sm shadow-sm" type="button">-</button>
<span class="w-8 text-center font-stock-counter text-stock-counter text-on-surface text-sm">1</span>
<button aria-label="Tambah satu" class="w-7 h-7 flex items-center justify-center rounded-lg bg-surface-container-lowest text-on-surface hover:text-primary font-bold text-sm shadow-sm" type="button">+</button>
</div>
<button class="flex-1 flex items-center justify-center gap-1.5 py-2.5 px-3 bg-primary-container text-on-primary-container hover:bg-primary-fixed-dim font-label-md text-label-md rounded-xl shadow-sm transition-colors" type="button">
<span class="material-symbols-outlined text-lg">add_shopping_cart</span>
<span>Beli</span>
</button>
</div>
</div>
<!-- Card 5: Telur Ayam Ras Kiloan Pilihan -->
<div class="group bg-surface-container-lowest rounded-2xl shadow-[0_4px_20px_-2px_rgba(245,166,35,0.12)] overflow-hidden flex flex-col justify-between hover:-translate-y-1 transition-transform duration-200">
<div>
<div class="relative w-full h-48 overflow-hidden bg-surface-container">
<img alt="Tumpukan telur ayam ras cokelat bersih siap timbang di atas meja kayu toko Bang Zul" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" src="https://lh3.googleusercontent.com/aida/ALJJyrBzqMYG7Kl3hKy_p8nmJCwyUDMb9FuoWxtyPnCVshW0vlklRkQ8Xy7vFl0RvF3bpisL0Irwd7esKCjJEmLHvESjfIo6_VPaZAlZ6m9_14CJcBrhht5Bbrm30ZAyGvbSK2DPqWbJsn5e7j1AyP1gbHXHFsDh2tdRCD2f8QSQqGGP6lzamocq3RE1dYp9UUjEsXptiGyYrh-H6-yMG2qkynIwtxDdxzKakoydZ5XL-_lp"/>
<div class="absolute top-3 left-3 flex flex-col gap-1.5">
<span class="px-2.5 py-1 bg-primary text-on-primary font-label-sm text-label-sm rounded-lg font-bold shadow-sm">
                    Ayam Ras
                  </span>
<span class="px-2 py-0.5 bg-surface-container-lowest/90 backdrop-blur-sm text-on-surface font-label-sm text-[11px] rounded-md shadow-sm">
                    Timbang 1 Kg (16-17 Btr)
                  </span>
</div>
<div class="absolute top-3 right-3">
<span class="inline-flex items-center gap-1 px-2.5 py-1 bg-secondary-container text-on-secondary-container font-label-sm text-label-sm rounded-full shadow-sm font-bold">
<span class="w-1.5 h-1.5 rounded-full bg-secondary"></span>
                    Tersedia 210 Kg
                  </span>
</div>
</div>
<div class="p-4 space-y-2">
<div class="flex items-center justify-between text-label-sm font-label-sm text-on-surface-variant">
<span class="flex items-center gap-1 text-primary">
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<strong class="text-on-surface">4.9</strong> (310 ulasan)
                  </span>
<span>Toko Bang Zul</span>
</div>
<h3 class="font-headline-sm text-headline-sm text-on-surface line-clamp-1 group-hover:text-primary transition-colors">
                  Telur Ayam Ras Kiloan Pilihan Super (1 Kg)
                </h3>
<p class="font-body-sm text-body-sm text-on-surface-variant line-clamp-2">
                  Ditimbang pas menggunakan timbangan bersertifikat dinas. Cangkang bersih tanpa kotoran menempel.
                </p>
<div class="pt-2 flex items-baseline gap-1.5">
<span class="font-price-display text-price-display text-primary font-extrabold">Rp 28.000</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">/ kg</span>
</div>
</div>
</div>
<!-- Footer Actions -->
<div class="p-4 pt-0 mt-2 flex items-center gap-2">
<div class="flex items-center bg-surface-container-low rounded-xl p-1 shrink-0">
<button aria-label="Kurang satu" class="w-7 h-7 flex items-center justify-center rounded-lg bg-surface-container-lowest text-on-surface hover:text-primary font-bold text-sm shadow-sm" type="button">-</button>
<span class="w-8 text-center font-stock-counter text-stock-counter text-on-surface text-sm">1</span>
<button aria-label="Tambah satu" class="w-7 h-7 flex items-center justify-center rounded-lg bg-surface-container-lowest text-on-surface hover:text-primary font-bold text-sm shadow-sm" type="button">+</button>
</div>
<button class="flex-1 flex items-center justify-center gap-1.5 py-2.5 px-3 bg-primary-container text-on-primary-container hover:bg-primary-fixed-dim font-label-md text-label-md rounded-xl shadow-sm transition-colors" type="button">
<span class="material-symbols-outlined text-lg">add_shopping_cart</span>
<span>Beli</span>
</button>
</div>
</div>
<!-- Card 6: Telur Asin Asli Masir Gisting (Stok Menipis) -->
<div class="group bg-surface-container-lowest rounded-2xl shadow-[0_4px_20px_-2px_rgba(245,166,35,0.12)] overflow-hidden flex flex-col justify-between hover:-translate-y-1 transition-transform duration-200">
<div>
<div class="relative w-full h-48 overflow-hidden bg-surface-container">
<img alt="Koleksi telur asin matang berminyak dan masir dengan cangkang biru toska lembut" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" src="https://lh3.googleusercontent.com/aida/ALJJyrBKCKpIVcWaQCmMaCGIR-JnYlS7flXYZP0d1ynbnZ7n-BHPxjb47g5yPlKh3JwUiCJF4NeX18yvHr85xF_wtioxtaraCp5fYzhGpyOTF_u3GgHWn5rYJaYifGhNEXtai5szKMlDDX5QyKA58bLxu92uwdrcTOkqPvcVqEjMyEQ5dz9aeZZYd3xAKlU-TeSwrD1H4AJgNnSObJuJKwlvwOtz9ZmwNvqvFCQ7q37iP7Dy"/>
<div class="absolute top-3 left-3 flex flex-col gap-1.5">
<span class="px-2.5 py-1 bg-tertiary text-on-tertiary font-label-sm text-label-sm rounded-lg font-bold shadow-sm">
                    Telur Asin
                  </span>
<span class="px-2 py-0.5 bg-surface-container-lowest/90 backdrop-blur-sm text-on-surface font-label-sm text-[11px] rounded-md shadow-sm">
                    Box Isi 10 Btr
                  </span>
</div>
<div class="absolute top-3 right-3">
<span class="inline-flex items-center gap-1 px-2.5 py-1 bg-primary-fixed text-on-primary-fixed font-label-sm text-label-sm rounded-full shadow-sm font-bold animate-pulse">
<span class="w-1.5 h-1.5 rounded-full bg-primary"></span>
                    Sisa 5 Box!
                  </span>
</div>
</div>
<div class="p-4 space-y-2">
<div class="flex items-center justify-between text-label-sm font-label-sm text-on-surface-variant">
<span class="flex items-center gap-1 text-primary">
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<strong class="text-on-surface">5.0</strong> (143 ulasan)
                  </span>
<span>Oleh-oleh Gisting</span>
</div>
<h3 class="font-headline-sm text-headline-sm text-on-surface line-clamp-1 group-hover:text-primary transition-colors">
                  Telur Asin Asli Masir Gisting (Isi 10 Butir)
                </h3>
<p class="font-body-sm text-body-sm text-on-surface-variant line-clamp-2">
                  Dibuat dengan balutan serbuk bata merah rempah 14 hari. Kuning telur berminyak oranye pekat, masir lumer di lidah.
                </p>
<div class="pt-2 flex items-baseline gap-1.5">
<span class="font-price-display text-price-display text-primary font-extrabold">Rp 36.000</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">/ box</span>
</div>
</div>
</div>
<!-- Footer Actions -->
<div class="p-4 pt-0 mt-2 flex items-center gap-2">
<div class="flex items-center bg-surface-container-low rounded-xl p-1 shrink-0">
<button aria-label="Kurang satu" class="w-7 h-7 flex items-center justify-center rounded-lg bg-surface-container-lowest text-on-surface hover:text-primary font-bold text-sm shadow-sm" type="button">-</button>
<span class="w-8 text-center font-stock-counter text-stock-counter text-on-surface text-sm">1</span>
<button aria-label="Tambah satu" class="w-7 h-7 flex items-center justify-center rounded-lg bg-surface-container-lowest text-on-surface hover:text-primary font-bold text-sm shadow-sm" type="button">+</button>
</div>
<button class="flex-1 flex items-center justify-center gap-1.5 py-2.5 px-3 bg-primary-container text-on-primary-container hover:bg-primary-fixed-dim font-label-md text-label-md rounded-xl shadow-sm transition-colors" type="button">
<span class="material-symbols-outlined text-lg">add_shopping_cart</span>
<span>Beli</span>
</button>
</div>
</div>
<!-- Card 7: Telur Ayam Kampung Herbal MPASI (Stok Menipis) -->
<div class="group bg-surface-container-lowest rounded-2xl shadow-[0_4px_20px_-2px_rgba(245,166,35,0.12)] overflow-hidden flex flex-col justify-between hover:-translate-y-1 transition-transform duration-200">
<div>
<div class="relative w-full h-48 overflow-hidden bg-surface-container">
<img alt="Telur kampung putih kecokelatan di wadah beralas jerami bersih dengan cahaya pagi hangat" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" src="https://lh3.googleusercontent.com/aida/ALJJyrC1SGftVAYQef-pQHbHgfQLSDiRN-Kl6-t0MQpnRpN_Eyc7YJ_zSRzdh2VMfvw6WZCcDYP0dZcn8A_3ViAAwIT5niDoPYnsh0k4uD1eu1zLx1_km8KNzZXu1KIuF8DXWTcZw4opzPR-ngEThaz1RQXxc4BuVzj4G5GT1BdRzZDneycOBwixJ5CszSwACq8vbrUlNioxOMU1jXfl0vXSymjM4CJLA_CYasKmLKkUTZ4r"/>
<div class="absolute top-3 left-3 flex flex-col gap-1.5">
<span class="px-2.5 py-1 bg-secondary text-on-secondary font-label-sm text-label-sm rounded-lg font-bold shadow-sm">
                    MPASI Sehat
                  </span>
<span class="px-2 py-0.5 bg-surface-container-lowest/90 backdrop-blur-sm text-on-surface font-label-sm text-[11px] rounded-md shadow-sm">
                    Pack Higienis 6 Butir
                  </span>
</div>
<div class="absolute top-3 right-3">
<span class="inline-flex items-center gap-1 px-2.5 py-1 bg-primary-fixed text-on-primary-fixed font-label-sm text-label-sm rounded-full shadow-sm font-bold animate-pulse">
<span class="w-1.5 h-1.5 rounded-full bg-primary"></span>
                    Sisa 4 Pack!
                  </span>
</div>
</div>
<div class="p-4 space-y-2">
<div class="flex items-center justify-between text-label-sm font-label-sm text-on-surface-variant">
<span class="flex items-center gap-1 text-primary">
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<strong class="text-on-surface">4.9</strong> (68 ulasan)
                  </span>
<span>Peternak Herbal Gisting</span>
</div>
<h3 class="font-headline-sm text-headline-sm text-on-surface line-clamp-1 group-hover:text-primary transition-colors">
                  Telur Ayam Kampung Herbal MPASI (Pack 6 Butir)
                </h3>
<p class="font-body-sm text-body-sm text-on-surface-variant line-clamp-2">
                  Diberi ransum temulawak &amp; kunyit. Bebas residu antibiotik kimia, sangat ramah untuk pencernaan balita dan lansia.
                </p>
<div class="pt-2 flex items-baseline gap-1.5">
<span class="font-price-display text-price-display text-primary font-extrabold">Rp 25.000</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">/ pack</span>
</div>
</div>
</div>
<!-- Footer Actions -->
<div class="p-4 pt-0 mt-2 flex items-center gap-2">
<div class="flex items-center bg-surface-container-low rounded-xl p-1 shrink-0">
<button aria-label="Kurang satu" class="w-7 h-7 flex items-center justify-center rounded-lg bg-surface-container-lowest text-on-surface hover:text-primary font-bold text-sm shadow-sm" type="button">-</button>
<span class="w-8 text-center font-stock-counter text-stock-counter text-on-surface text-sm">1</span>
<button aria-label="Tambah satu" class="w-7 h-7 flex items-center justify-center rounded-lg bg-surface-container-lowest text-on-surface hover:text-primary font-bold text-sm shadow-sm" type="button">+</button>
</div>
<button class="flex-1 flex items-center justify-center gap-1.5 py-2.5 px-3 bg-primary-container text-on-primary-container hover:bg-primary-fixed-dim font-label-md text-label-md rounded-xl shadow-sm transition-colors" type="button">
<span class="material-symbols-outlined text-lg">add_shopping_cart</span>
<span>Beli</span>
</button>
</div>
</div>
<!-- Card 8: Paket Grosir Telur Ras 5 Karpet -->
<div class="group bg-surface-container-lowest rounded-2xl shadow-[0_4px_20px_-2px_rgba(245,166,35,0.12)] overflow-hidden flex flex-col justify-between hover:-translate-y-1 transition-transform duration-200">
<div>
<div class="relative w-full h-48 overflow-hidden bg-surface-container">
<img alt="Tumpukan tinggi karpet telur karton paket grosir untuk warung makan dan pedagang di Tanggamus" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" src="https://lh3.googleusercontent.com/aida/ALJJyrBzqMYG7Kl3hKy_p8nmJCwyUDMb9FuoWxtyPnCVshW0vlklRkQ8Xy7vFl0RvF3bpisL0Irwd7esKCjJEmLHvESjfIo6_VPaZAlZ6m9_14CJcBrhht5Bbrm30ZAyGvbSK2DPqWbJsn5e7j1AyP1gbHXHFsDh2tdRCD2f8QSQqGGP6lzamocq3RE1dYp9UUjEsXptiGyYrh-H6-yMG2qkynIwtxDdxzKakoydZ5XL-_lp"/>
<div class="absolute top-3 left-3 flex flex-col gap-1.5">
<span class="px-2.5 py-1 bg-on-surface text-surface font-label-sm text-label-sm rounded-lg font-bold shadow-sm">
                    Grosir Warung
                  </span>
<span class="px-2 py-0.5 bg-surface-container-lowest/90 backdrop-blur-sm text-on-surface font-label-sm text-[11px] rounded-md shadow-sm">
                    5 Karpet (150 Butir)
                  </span>
</div>
<div class="absolute top-3 right-3">
<span class="inline-flex items-center gap-1 px-2.5 py-1 bg-secondary-container text-on-secondary-container font-label-sm text-label-sm rounded-full shadow-sm font-bold">
<span class="w-1.5 h-1.5 rounded-full bg-secondary"></span>
                    Tersedia 25 Paket
                  </span>
</div>
</div>
<div class="p-4 space-y-2">
<div class="flex items-center justify-between text-label-sm font-label-sm text-on-surface-variant">
<span class="flex items-center gap-1 text-primary">
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<strong class="text-on-surface">4.8</strong> (41 ulasan)
                  </span>
<span>Distribusi Kota Agung</span>
</div>
<h3 class="font-headline-sm text-headline-sm text-on-surface line-clamp-1 group-hover:text-primary transition-colors">
                  Paket Grosir Telur Ras 5 Karpet (150 Butir)
                </h3>
<p class="font-body-sm text-body-sm text-on-surface-variant line-clamp-2">
                  Paket hemat khusus rumah makan padang, katering hajatan, dan warung kelontong. Bonus antar kurir langsung ke dapur.
                </p>
<div class="pt-2 flex items-baseline gap-1.5">
<span class="font-price-display text-price-display text-primary font-extrabold">Rp 250.000</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">/ paket</span>
</div>
</div>
</div>
<!-- Footer Actions -->
<div class="p-4 pt-0 mt-2 flex items-center gap-2">
<div class="flex items-center bg-surface-container-low rounded-xl p-1 shrink-0">
<button aria-label="Kurang satu" class="w-7 h-7 flex items-center justify-center rounded-lg bg-surface-container-lowest text-on-surface hover:text-primary font-bold text-sm shadow-sm" type="button">-</button>
<span class="w-8 text-center font-stock-counter text-stock-counter text-on-surface text-sm">1</span>
<button aria-label="Tambah satu" class="w-7 h-7 flex items-center justify-center rounded-lg bg-surface-container-lowest text-on-surface hover:text-primary font-bold text-sm shadow-sm" type="button">+</button>
</div>
<button class="flex-1 flex items-center justify-center gap-1.5 py-2.5 px-3 bg-primary-container text-on-primary-container hover:bg-primary-fixed-dim font-label-md text-label-md rounded-xl shadow-sm transition-colors" type="button">
<span class="material-symbols-outlined text-lg">add_shopping_cart</span>
<span>Beli</span>
</button>
</div>
</div>
<!-- Card 9: Telur Bebek Angon Organik Pesisir (Habis - Pre-Order) -->
<div class="group bg-surface-container-lowest rounded-2xl shadow-[0_4px_20px_-2px_rgba(245,166,35,0.12)] overflow-hidden flex flex-col justify-between opacity-80 hover:opacity-100 transition-opacity">
<div>
<div class="relative w-full h-48 overflow-hidden bg-surface-container">
<img alt="Wadah kayu telur bebek mentah dengan alas jerami dan label telur bebek tambak kualitas super" class="w-full h-full object-cover grayscale-[30%]" src="https://lh3.googleusercontent.com/aida/ALJJyrBKCKpIVcWaQCmMaCGIR-JnYlS7flXYZP0d1ynbnZ7n-BHPxjb47g5yPlKh3JwUiCJF4NeX18yvHr85xF_wtioxtaraCp5fYzhGpyOTF_u3GgHWn5rYJaYifGhNEXtai5szKMlDDX5QyKA58bLxu92uwdrcTOkqPvcVqEjMyEQ5dz9aeZZYd3xAKlU-TeSwrD1H4AJgNnSObJuJKwlvwOtz9ZmwNvqvFCQ7q37iP7Dy"/>
<div class="absolute inset-0 bg-surface-dim/40 backdrop-blur-[1px] flex items-center justify-center">
<span class="px-3.5 py-1.5 bg-surface-container-highest/90 text-on-surface font-label-sm text-label-sm rounded-xl font-bold shadow-md">
                    Panen Berikutnya Besok 06:00
                  </span>
</div>
<div class="absolute top-3 left-3 flex flex-col gap-1.5">
<span class="px-2.5 py-1 bg-tertiary text-on-tertiary font-label-sm text-label-sm rounded-lg font-bold shadow-sm">
                    Bebek Angon
                  </span>
<span class="px-2 py-0.5 bg-surface-container-lowest/90 backdrop-blur-sm text-on-surface font-label-sm text-[11px] rounded-md shadow-sm">
                    Tray 30 Butir
                  </span>
</div>
<div class="absolute top-3 right-3">
<span class="inline-flex items-center gap-1 px-2.5 py-1 bg-surface-container-high text-on-surface-variant font-label-sm text-label-sm rounded-full shadow-sm font-bold">
<span class="w-1.5 h-1.5 rounded-full bg-outline"></span>
                    Habis Hari Ini
                  </span>
</div>
</div>
<div class="p-4 space-y-2">
<div class="flex items-center justify-between text-label-sm font-label-sm text-on-surface-variant">
<span class="flex items-center gap-1 text-primary">
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<strong class="text-on-surface">4.7</strong> (33 ulasan)
                  </span>
<span>Pesisir Teluk Semaka</span>
</div>
<h3 class="font-headline-sm text-headline-sm text-on-surface line-clamp-1">
                  Telur Bebek Angon Organik Pesisir (Tray 30 Butir)
                </h3>
<p class="font-body-sm text-body-sm text-on-surface-variant line-clamp-2">
                  Dihasilkan dari bebek gembala di sawah alami dan pesisir. Kuning telur tebal kemerahan alami tanpa suntik vitamin.
                </p>
<div class="pt-2 flex items-baseline gap-1.5">
<span class="font-price-display text-price-display text-outline font-extrabold">Rp 95.000</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">/ tray</span>
</div>
</div>
</div>
<!-- Footer Actions (Pre-order / Ingatkan) -->
<div class="p-4 pt-0 mt-2 flex items-center gap-2">
<button class="w-full flex items-center justify-center gap-2 py-2.5 px-3 bg-surface-container-high text-on-surface-variant hover:text-on-surface font-label-md text-label-md rounded-xl transition-colors" type="button">
<span class="material-symbols-outlined text-base">notifications_active</span>
<span>Pre-Order Panen Besok</span>
</button>
</div>
</div>
</div>
<!-- Pagination & Page Controls -->
<div class="w-full bg-surface-container-lowest mt-10 p-5 rounded-2xl shadow-sm flex flex-col md:flex-row items-center justify-between gap-4">
<div class="font-body-sm text-body-sm text-on-surface-variant text-center md:text-left">
            Menampilkan <strong class="text-on-surface font-bold">1 - 9</strong> dari <strong class="text-on-surface font-bold">12</strong> Produk Telur Segar Tanggamus
          </div>
<div class="flex items-center gap-1.5">
<button class="flex items-center gap-1 px-3 py-1.5 rounded-lg bg-surface-container-low text-outline cursor-not-allowed text-label-sm font-label-sm" disabled="" type="button">
<span class="material-symbols-outlined text-sm">chevron_left</span>
<span class="hidden sm:inline">Sebelumnya</span>
</button>
<button class="w-8 h-8 rounded-lg bg-primary text-on-primary font-bold text-label-sm font-label-sm" type="button">1</button>
<button class="w-8 h-8 rounded-lg hover:bg-surface-container text-on-surface font-semibold text-label-sm font-label-sm transition-colors" type="button">2</button>
<button class="w-8 h-8 rounded-lg hover:bg-surface-container text-on-surface font-semibold text-label-sm font-label-sm transition-colors" type="button">3</button>
<button class="flex-1 sm:flex-none flex items-center gap-1 px-3 py-1.5 rounded-lg bg-surface-container-low hover:bg-surface-container-high text-on-surface text-label-sm font-label-sm transition-colors" type="button">
<span class="hidden sm:inline">Selanjutnya</span>
<span class="material-symbols-outlined text-sm">chevron_right</span>
</button>
</div>
<div class="hidden lg:flex items-center gap-2 text-label-sm font-label-sm text-on-surface-variant">
<span>Tampilkan per halaman:</span>
<select class="bg-surface-container-low rounded-lg px-2 py-1 text-on-surface font-bold focus:outline-none">
<option value="9">9 Butir/Tray</option>
<option value="18">18 Produk</option>
<option value="36">36 Produk</option>
</select>
</div>
</div>
</section>
</div>
</div>
<!-- Bottom Farm Assurance Callout (Lokalitas Tanggamus) -->
<section class="w-full bg-surface-container-lowest mt-12 py-10 px-4 lg:px-8 shadow-sm">
<div class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-3 gap-6">
<div class="flex items-start gap-4 p-4 rounded-xl bg-surface-container-low">
<div class="p-3 rounded-full bg-secondary-container text-on-secondary-container shrink-0">
<span class="material-symbols-outlined text-2xl">downloading</span>
</div>
<div>
<h4 class="font-headline-sm text-headline-sm text-on-surface">Pakan Alami Bebas Residu</h4>
<p class="font-body-sm text-body-sm text-on-surface-variant mt-1">
            Ayam petelur dan bebek dibudidayakan mitra peternak Tanggamus dengan formula jagung giling serta dedak lokal pilihan.
          </p>
</div>
</div>
<div class="flex items-start gap-4 p-4 rounded-xl bg-surface-container-low">
<div class="p-3 rounded-full bg-primary-container text-on-primary-container shrink-0">
<span class="material-symbols-outlined text-2xl">two_wheeler</span>
</div>
<div>
<h4 class="font-headline-sm text-headline-sm text-on-surface">Kurir Motor Spasial Tanggamus</h4>
<p class="font-body-sm text-body-sm text-on-surface-variant mt-1">
            Pengantaran cepat menggunakan rak peredam getaran ke Gisting, Talang Padang, Kota Agung hingga pelosok desa.
          </p>
</div>
</div>
<div class="flex items-start gap-4 p-4 rounded-xl bg-surface-container-low">
<div class="p-3 rounded-full bg-tertiary-container text-on-tertiary-container shrink-0">
<span class="material-symbols-outlined text-2xl">handshake</span>
</div>
<div>
<h4 class="font-headline-sm text-headline-sm text-on-surface">Harga Adil Peternak</h4>
<p class="font-body-sm text-body-sm text-on-surface-variant mt-1">
            Tanpa perantara tengkulak berbelit. Margin keuntungan dibagikan adil agar peternak unggas pedesaan terus berkembang.
          </p>
</div>
</div>
</div>
</section>
<!-- Mobile Bottom Sheet Filter Simulator (Hidden by default, triggered on mobile) -->
<div class="hidden fixed inset-0 z-50 bg-black/40 backdrop-blur-sm flex justify-end flex-col" id="mobileFilterDrawer">
<div class="bg-surface-container-lowest rounded-t-3xl max-h-[85vh] overflow-y-auto p-6 space-y-6 shadow-2xl">
<div class="flex items-center justify-between pb-3 border-b-0">
<div class="flex items-center gap-2">
<span class="material-symbols-outlined text-primary text-xl">tune</span>
<h3 class="font-headline-md text-headline-md text-on-surface">Filter Telur Segar</h3>
</div>
<button class="w-8 h-8 flex items-center justify-center rounded-full bg-surface-container text-on-surface" id="mobileFilterCloseBtn" type="button">
<span class="material-symbols-outlined text-lg">close</span>
</button>
</div>
<!-- Quick category in drawer -->
<div class="space-y-2">
<span class="font-label-md text-label-md text-on-surface uppercase font-bold">Kategori</span>
<div class="grid grid-cols-2 gap-2 text-label-sm font-label-sm">
<button class="p-2.5 rounded-xl bg-primary text-on-primary font-bold text-left" type="button">Semua Telur</button>
<button class="p-2.5 rounded-xl bg-surface-container text-on-surface text-left" type="button">Ayam Ras (4)</button>
<button class="p-2.5 rounded-xl bg-surface-container text-on-surface text-left" type="button">Ayam Kampung (3)</button>
<button class="p-2.5 rounded-xl bg-surface-container text-on-surface text-left" type="button">Bebek &amp; Asin (3)</button>
</div>
</div>
<!-- Quick Status -->
<div class="space-y-2">
<span class="font-label-md text-label-md text-on-surface uppercase font-bold">Ketersediaan Stok</span>
<div class="flex flex-col gap-2 text-body-sm font-body-sm">
<label class="flex items-center gap-2">
<input checked="" class="w-4 h-4 rounded text-secondary accent-secondary" type="checkbox"/>
<span>Ready Stok Kandang</span>
</label>
<label class="flex items-center gap-2">
<input checked="" class="w-4 h-4 rounded text-primary accent-primary" type="checkbox"/>
<span>Stok Menipis</span>
</label>
</div>
</div>
<!-- Actions -->
<div class="pt-4 flex items-center gap-3">
<button class="flex-1 py-3 bg-surface-container-high text-on-surface font-label-md text-label-md rounded-xl" id="mobileFilterResetBtn" type="button">
          Reset
        </button>
<button class="flex-1 py-3 bg-primary text-on-primary font-label-md text-label-md rounded-xl font-bold shadow-md" id="mobileFilterApplyBtn" type="button">
          Terapkan (9 Produk)
        </button>
</div>
</div>
</div>
<script>
    // Micro-interactions for Quantity Steppers and Mobile Filter Drawer
    document.addEventListener('DOMContentLoaded', () => {
      // Steppers
      document.querySelectorAll('#productGridContainer > div').forEach(card => {
        const minusBtn = card.querySelector('button[aria-label="Kurang satu"]');
        const plusBtn = card.querySelector('button[aria-label="Tambah satu"]');
        const countSpan = card.querySelector('.font-stock-counter');

        if (minusBtn && plusBtn && countSpan) {
          minusBtn.addEventListener('click', () => {
            let val = parseInt(countSpan.textContent, 10) || 1;
            if (val > 1) countSpan.textContent = val - 1;
          });

          plusBtn.addEventListener('click', () => {
            let val = parseInt(countSpan.textContent, 10) || 1;
            countSpan.textContent = val + 1;
          });
        }
      });

      // Mobile Drawer Toggle
      const openBtn = document.getElementById('mobileFilterOpenBtn');
      const closeBtn = document.getElementById('mobileFilterCloseBtn');
      const applyBtn = document.getElementById('mobileFilterApplyBtn');
      const drawer = document.getElementById('mobileFilterDrawer');

      const toggleDrawer = (show) => {
        if (!drawer) return;
        if (show) {
          drawer.classList.remove('hidden');
          document.body.style.overflow = 'hidden';
        } else {
          drawer.classList.add('hidden');
          document.body.style.overflow = '';
        }
      };

      if (openBtn) openBtn.addEventListener('click', () => toggleDrawer(true));
      if (closeBtn) closeBtn.addEventListener('click', () => toggleDrawer(false));
      if (applyBtn) applyBtn.addEventListener('click', () => toggleDrawer(false));

      // Close when clicking outside of the bottom sheet
      if (drawer) {
        drawer.addEventListener('click', (e) => {
          if (e.target === drawer) toggleDrawer(false);
        });
      }

      // Grid / List view toggle
      const gridBtn = document.getElementById('viewGridBtn');
      const listBtn = document.getElementById('viewListBtn');
      const gridContainer = document.getElementById('productGridContainer');

      if (gridBtn && listBtn && gridContainer) {
        listBtn.addEventListener('click', () => {
          listBtn.classList.add('bg-surface-container-lowest', 'text-primary', 'shadow-sm');
          listBtn.classList.remove('text-outline');
          gridBtn.classList.remove('bg-surface-container-lowest', 'text-primary', 'shadow-sm');
          gridBtn.classList.add('text-outline');
          
          gridContainer.classList.remove('sm:grid-cols-2', 'lg:grid-cols-3');
          gridContainer.classList.add('grid-cols-1');
        });

        gridBtn.addEventListener('click', () => {
          gridBtn.classList.add('bg-surface-container-lowest', 'text-primary', 'shadow-sm');
          gridBtn.classList.remove('text-outline');
          listBtn.classList.remove('bg-surface-container-lowest', 'text-primary', 'shadow-sm');
          listBtn.classList.add('text-outline');

          gridContainer.classList.remove('grid-cols-1');
          gridContainer.classList.add('sm:grid-cols-2', 'lg:grid-cols-3');
        });
      }
    });
  </script>
</div></main><footer class="w-full bg-surface-container-low mt-16 pt-12 pb-8 text-on-surface-variant"><div class="max-w-7xl mx-auto px-4 lg:px-8 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8"><div class="space-y-3"><div class="flex items-center gap-2"><img alt="Logo Bang Zul Egg Market" class="h-7 w-auto object-contain" src="https://lh3.googleusercontent.com/aida/ALJJyrAvuhgJbL1OqXYnorOpflEwk9ch2RB3i3nIpJf2khBHtFUraZYLjA49xnoYr5_XpY1inx_yvUKDG-f5ULodcAC4hoBl9QYWujU07wAAJsvNI88PefRZRNH2SgRzcvtvfP9LlMDgvobQRRrHxWwLlWY8MQoR1CS4kennwXqXJqn5PR3R5zkf-p4q0eleDblVHlCAtE__Wj8FbqU6db9zlBw02jnLdLpow_xGCN8RF4es"/><span class="font-headline-sm text-headline-sm text-primary">UD. Bang Zul Egg Market</span></div><p class="font-body-sm text-body-sm">Pusat distribusi telur segar langsung dari peternak binaan lokal Tanggamus. Menjaga kualitas kesegaran cangkang utuh dan timbangan presisi terpercaya.</p><div class="flex items-center gap-2 text-secondary font-label-sm text-label-sm"><span class="material-symbols-outlined text-sm">verified</span><span>Garansi Ganti Telur Pecah 100%</span></div></div><div class="space-y-2"><h3 class="font-headline-sm text-headline-sm text-on-surface">Jam Operasional &amp; Panen</h3><p class="font-body-sm text-body-sm">Pengambilan Telur Kandang: 06.00 - 10.00 WIB</p><p class="font-body-sm text-body-sm">Jadwal Pengiriman Kurir: 08.00 - 18.00 WIB</p><p class="font-body-sm text-body-sm text-secondary font-semibold">Setiap Hari (Senin - Minggu Tetap Buka)</p><p class="font-label-sm text-label-sm text-on-surface-variant pt-1">Wilayah Gisting, Talang Padang, Wonosobo, Kota Agung &amp; Sekitarnya.</p></div><div class="space-y-2"><h3 class="font-headline-sm text-headline-sm text-on-surface">Metode Pembayaran</h3><div class="space-y-1 font-body-sm text-body-sm"><p class="flex items-center gap-1.5"><span class="material-symbols-outlined text-primary text-sm">qr_code_scanner</span>QRIS Seluruh Bank &amp; E-Wallet</p><p class="flex items-center gap-1.5"><span class="material-symbols-outlined text-primary text-sm">account_balance</span>Transfer Bank Lampung / BRI / BCA</p><p class="flex items-center gap-1.5"><span class="material-symbols-outlined text-primary text-sm">payments</span>COD (Bayar Tunai di Tempat saat Timbang)</p></div></div><div class="space-y-2"><h3 class="font-headline-sm text-headline-sm text-on-surface">Komitmen Peternak Lokal</h3><p class="font-body-sm text-body-sm">Mendukung keberlanjutan usaha peternak unggas pedesaan di Kabupaten Tanggamus, Lampung dengan harga adil, timbangan transparan, dan pakan alami bermutu.</p><div class="pt-2"><span class="inline-block px-3 py-1 bg-secondary-container text-on-secondary-container rounded-full font-label-sm text-label-sm">Asli Tanggamus, Segar Bergaransi</span></div></div></div><div class="max-w-7xl mx-auto px-4 lg:px-8 mt-10 pt-4 flex flex-col sm:flex-row items-center justify-between gap-2 font-label-sm text-label-sm text-on-surface-variant"><p>© 2024 UD. Bang Zul Egg Market Tanggamus Lampung. Hak Cipta Dilindungi.</p><p>Dibuat untuk ekosistem niaga agrikultur Kabupaten Tanggamus</p></div></footer></body></html>

<!-- Masuk dan Daftar Akun Pembeli -->
<!DOCTYPE html>

<html lang="id"><head><meta charset="utf-8"/><meta content="width=device-width, initial-scale=1.0" name="viewport"/><meta content="web_standard" name="shell-type"/><link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" rel="stylesheet"/><link href="https://fonts.googleapis.com" rel="preconnect"/><link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/><link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&amp;family=Plus+Jakarta+Sans:wght@700;800&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/><style>@layer base{html,body{margin:0;padding:0;}body{overscroll-behavior:none;}main>:first-child{margin-top:0!important;}main>:last-child{margin-bottom:0!important;}}::-webkit-scrollbar{display:none;}</style><script src="https://cdn.tailwindcss.com"></script><script id="tailwind-config">tailwind.config={darkMode:"class",theme:{extend:{colors:{"secondary-container":"#a0f399","on-tertiary-fixed-variant":"#3e4a41","on-background":"#1b1c1c","on-error":"#ffffff","on-primary":"#ffffff","primary":"#835500","surface-container-highest":"#e4e2e1","on-secondary-fixed-variant":"#005312","surface-container-low":"#f6f3f2","background":"#fcf9f8","surface":"#fcf9f8","on-tertiary-fixed":"#131e17","on-secondary-container":"#217128","outline-variant":"#d7c3ae","inverse-surface":"#303030","surface-container":"#f0eded","on-secondary-fixed":"#002204","surface-bright":"#fcf9f8","primary-fixed":"#ffddb4","surface-dim":"#dcd9d9","surface-container-lowest":"#ffffff","tertiary":"#556158","on-primary-fixed":"#291800","secondary-fixed":"#a3f69c","tertiary-container":"#acb9ae","on-primary-container":"#644000","on-primary-fixed-variant":"#633f00","on-tertiary":"#ffffff","surface-variant":"#e4e2e1","on-tertiary-container":"#3e4a41","on-secondary":"#ffffff","inverse-on-surface":"#f3f0f0","surface-tint":"#835500","primary-fixed-dim":"#ffb955","on-surface-variant":"#524534","on-error-container":"#93000a","surface-container-high":"#eae7e7","error":"#ba1a1a","primary-container":"#f5a623","inverse-primary":"#ffb955","outline":"#857462","tertiary-fixed":"#d9e6da","tertiary-fixed-dim":"#bdcabe","error-container":"#ffdad6","secondary":"#1b6d24","on-surface":"#1b1c1c","secondary-fixed-dim":"#88d982"},borderRadius:{"DEFAULT":"0.25rem","lg":"0.5rem","xl":"0.75rem","full":"9999px"},spacing:{"space-md":"1rem","gutter":"1rem","space-lg":"1.5rem","space-xl":"2rem","gutter-desktop":"1.5rem","space-xs":"0.25rem","space-sm":"0.5rem","margin":"1rem","margin-desktop":"2.5rem"},fontFamily:{"body-md":["Inter"],"label-sm":["Inter"],"price-display":["Plus Jakarta Sans"],"stock-counter":["Inter"],"headline-md":["Plus Jakarta Sans"],"body-lg":["Inter"],"label-md":["Inter"],"headline-sm":["Plus Jakarta Sans"],"display-lg":["Plus Jakarta Sans"],"label-lg":["Inter"],"headline-lg-mobile":["Plus Jakarta Sans"],"headline-lg":["Plus Jakarta Sans"],"body-sm":["Inter"],"display-lg-mobile":["Plus Jakarta Sans"]},fontSize:{"body-md":["14px",{"lineHeight":"22px","fontWeight":"400"}],"label-sm":["11px",{"lineHeight":"14px","letterSpacing":"0.02em","fontWeight":"600"}],"price-display":["22px",{"lineHeight":"28px","letterSpacing":"-0.02em","fontWeight":"800"}],"stock-counter":["18px",{"lineHeight":"24px","letterSpacing":"0.01em","fontWeight":"700"}],"headline-md":["20px",{"lineHeight":"28px","fontWeight":"700"}],"body-lg":["16px",{"lineHeight":"26px","fontWeight":"400"}],"label-md":["12px",{"lineHeight":"16px","fontWeight":"600"}],"headline-sm":["16px",{"lineHeight":"24px","fontWeight":"700"}],"display-lg":["40px",{"lineHeight":"48px","letterSpacing":"-0.02em","fontWeight":"800"}],"label-lg":["14px",{"lineHeight":"20px","fontWeight":"600"}],"headline-lg-mobile":["22px",{"lineHeight":"30px","letterSpacing":"0em","fontWeight":"700"}],"headline-lg":["28px",{"lineHeight":"36px","letterSpacing":"-0.01em","fontWeight":"700"}],"body-sm":["12px",{"lineHeight":"18px","fontWeight":"400"}],"display-lg-mobile":["30px",{"lineHeight":"38px","letterSpacing":"-0.01em","fontWeight":"800"}]}}}}</script></head><body class="bg-surface font-body-md text-body-md text-on-surface antialiased"><header class="fixed top-0 left-0 w-full z-50 bg-surface/95 backdrop-blur-md shadow-[0_4px_20px_-2px_rgba(245,166,35,0.12)]"><div class="bg-secondary text-on-secondary px-4 py-1.5"><div class="max-w-7xl mx-auto flex flex-col md:flex-row items-center justify-between gap-1 text-label-sm font-label-sm"><div class="flex items-center gap-2 text-center md:text-left"><span class="material-symbols-outlined text-secondary-fixed text-sm">local_shipping</span><span>Pengiriman Segar Hari Ini ke Wilayah Kota Agung, Gisting, Talang Padang, Wonosobo, Pringsewu sekitarnya | <strong class="text-secondary-fixed">Garansi Telur Pecah Diganti 100%</strong></span></div><a class="flex items-center gap-1.5 hover:text-secondary-fixed transition-colors whitespace-nowrap" href="https://wa.me/6281278900000"><span class="material-symbols-outlined text-sm">chat</span><span>WhatsApp CS Hubungi Bang Zul: 0812-7890-XXXX</span></a></div></div><div class="max-w-7xl mx-auto px-4 lg:px-8 py-3 flex items-center justify-between gap-4"><a class="flex items-center gap-3 shrink-0" data-path="katalog-belanja-pembeli" href="#"><img alt="Logo Bang Zul Egg Market" class="h-8 w-auto object-contain" src="https://lh3.googleusercontent.com/aida/ALJJyrAvuhgJbL1OqXYnorOpflEwk9ch2RB3i3nIpJf2khBHtFUraZYLjA49xnoYr5_XpY1inx_yvUKDG-f5ULodcAC4hoBl9QYWujU07wAAJsvNI88PefRZRNH2SgRzcvtvfP9LlMDgvobQRRrHxWwLlWY8MQoR1CS4kennwXqXJqn5PR3R5zkf-p4q0eleDblVHlCAtE__Wj8FbqU6db9zlBw02jnLdLpow_xGCN8RF4es"/><div class="flex flex-col"><span class="font-headline-md text-headline-md text-primary tracking-tight leading-none">Bang Zul</span><span class="font-label-sm text-label-sm text-secondary font-bold tracking-wider uppercase leading-none mt-0.5">Egg Market Tanggamus</span></div></a><div class="hidden lg:flex items-center gap-1.5 px-3 py-1.5 rounded-full bg-surface-container-low text-on-surface-variant font-label-sm text-label-sm shrink-0"><span class="material-symbols-outlined text-primary text-base">location_on</span><span class="max-w-[210px] truncate">Kab. Tanggamus (Gisting, Kota Agung &amp; Sekitarnya)</span></div><div class="hidden md:flex flex-1 max-w-md mx-2"><div class="relative w-full flex items-center"><span class="material-symbols-outlined absolute left-3 text-outline text-lg">search</span><input class="w-full pl-10 pr-4 py-2 rounded-full bg-surface-container-lowest text-body-sm font-body-sm text-on-surface placeholder:text-outline focus:outline-none focus:ring-2 focus:ring-primary-container shadow-[0_1px_4px_rgba(0,0,0,0.04)]" placeholder="Cari telur ayam ras, telur omega, telur bebek, puyuh..." type="text"/></div></div><div class="flex items-center gap-2 md:gap-3 shrink-0"><a class="flex items-center gap-2 px-3 py-1.5 rounded-full bg-primary-container text-on-primary-container hover:bg-primary-fixed-dim transition-colors shadow-sm" data-path="keranjang-belanja-pembeli" href="#"><span class="material-symbols-outlined text-lg">shopping_basket</span><span class="hidden sm:inline font-label-sm text-label-sm">Keranjang (3 Item)</span></a><div class="hidden sm:flex items-center gap-1.5 pl-1"><a class="px-3 py-1.5 rounded-full bg-surface-container text-on-surface hover:bg-surface-container-high transition-colors font-label-sm text-label-sm" data-path="masuk-akun-pembeli" href="#">Masuk</a><a class="px-3 py-1.5 rounded-full bg-primary text-on-primary hover:bg-on-primary-container transition-colors font-label-sm text-label-sm" data-path="daftar-akun-pembeli" href="#">Daftar</a></div><a class="flex items-center gap-1.5 p-1.5 rounded-full hover:bg-surface-container-high text-on-surface-variant" data-path="profil-akun-pembeli" href="#"><img alt="Foto Akun Pembeli" class="w-8 h-8 rounded-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBu4cCay1o-kcZkrepBjdwRhNkTeb5NSNF4V20H1AoEXr4ahIrRP9SktX37TUve3u7us_GHnlm1279EoAyYcFxqZTZV4CIOdstOTCqIMcitiPTCwpWm4m2okjdh9z8S2I2n0sK1hb3y3ohWU84Tu6ZWNoxKL7D1NVLhMsBA3C6eHNQmukclnmKpMzHXssx-xtkh1wF2y2OFEDgXUgTPjjAfLabaOsUrz91MId6by4k"/></a></div></div><div class="bg-surface-container-lowest shadow-[0_1px_4px_rgba(0,0,0,0.02)] overflow-x-auto"><div class="max-w-7xl mx-auto px-4 lg:px-8"><nav class="flex items-center gap-6 whitespace-nowrap py-2.5 text-label-sm font-label-sm" data-active-classes="text-primary font-bold border-b-2 border-primary"><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="katalog-belanja-pembeli" href="#">Katalog Telur Segar</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="detail-produk-telur" href="#">Detail Produk Telur</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="keranjang-belanja-pembeli" href="#">Keranjang Belanja</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="checkout-pembayaran-pembeli" href="#">Checkout Pembayaran</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="profil-akun-pembeli" href="#">Profil Saya</a><a aria-current="page" class="transition-colors pb-1 text-primary font-bold border-b-2 border-primary" data-path="masuk-akun-pembeli" href="#">Masuk Akun</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="daftar-akun-pembeli" href="#">Daftar Akun Baru</a></nav></div></div></header><main class="w-full pt-36 bg-surface min-h-screen"><div class="flex flex-col w-full">
<div class="w-full max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4 sm:py-8">
<!-- Top Breadcrumb & Trust Micro-Bar -->
<div class="flex flex-wrap items-center justify-between gap-3 mb-6 pb-2 text-label-sm font-label-sm text-on-surface-variant">
<div class="flex items-center gap-2">
<a class="hover:text-primary transition-colors flex items-center gap-1" href="#">
<span class="material-symbols-outlined text-sm">home</span>
<span>Beranda</span>
</a>
<span>/</span>
<span class="text-primary font-bold">Autentikasi Akun Pembeli</span>
</div>
<div class="flex items-center gap-4 text-xs font-semibold">
<span class="inline-flex items-center gap-1 text-secondary">
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">verified</span>
          100% Telur Segar Peternak Tanggamus
        </span>
<span class="hidden sm:inline-flex items-center gap-1 text-primary">
<span class="material-symbols-outlined text-sm">shield</span>
          Privasi Data Terenkripsi
        </span>
</div>
</div>
<!-- Main Split Layout Container -->
<div class="w-full rounded-2xl bg-surface-container-lowest shadow-xl overflow-hidden grid grid-cols-1 lg:grid-cols-12 min-h-[740px]">
<!-- LEFT COLUMN: Visual Hero & Local Farmer Trust (Hidden on small mobile, visible lg:col-span-5 xl:col-span-5) -->
<div class="relative hidden lg:flex lg:col-span-5 xl:col-span-5 flex-col justify-between p-8 xl:p-10 bg-primary-container/20 text-on-surface overflow-hidden">
<!-- Background Imagery with Agricultural Gradients -->
<div class="absolute inset-0 z-0">
<div class="w-full h-full bg-cover bg-center scale-105 transform hover:scale-100 transition-transform duration-1000 ease-out" data-alt="Peternakan ayam petelur modern dan bersih di lereng Gunung Tanggamus Gisting Lampung di pagi hari yang cerah dengan sinar matahari keemasan dan telur segar tertata rapi" style="background-image: url('https://lh3.googleusercontent.com/aida/ALJJyrC1SGftVAYQef-pQHbHgfQLSDiRN-Kl6-t0MQpnRpN_Eyc7YJ_zSRzdh2VMfvw6WZCcDYP0dZcn8A_3ViAAwIT5niDoPYnsh0k4uD1eu1zLx1_km8KNzZXu1KIuF8DXWTcZw4opzPR-ngEThaz1RQXxc4BuVzj4G5GT1BdRzZDneycOBwixJ5CszSwACq8vbrUlNioxOMU1jXfl0vXSymjM4CJLA_CYasKmLKkUTZ4r')"></div>
<!-- Rich Gradient Overlay with Amber & Fresh Green Tints -->
<div class="absolute inset-0 bg-gradient-to-t from-on-background via-on-background/80 to-primary/60 mix-blend-multiply"></div>
<div class="absolute inset-0 bg-gradient-to-b from-primary/30 via-transparent to-secondary/40 pointer-events-none"></div>
</div>
<!-- Left Content Layer (Elevated Above Gradients) -->
<div class="relative z-10 space-y-6">
<!-- Local Badge -->
<div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-surface-container-lowest/20 backdrop-blur-md text-surface-container-lowest text-label-sm font-label-sm">
<span class="w-2 h-2 rounded-full bg-secondary-fixed animate-pulse"></span>
<span>Panen Pagi Ini • Segar dari Gisting &amp; Sekitarnya</span>
</div>
<!-- Hero Headline -->
<div class="space-y-2">
<div class="flex items-center gap-3">
<span class="material-symbols-outlined text-primary-fixed text-3xl" style="font-variation-settings: 'FILL' 1;">egg</span>
<span class="font-headline-md text-headline-md text-surface-container-lowest font-black tracking-tight">UD. Bang Zul</span>
</div>
<h2 class="font-headline-lg text-headline-lg text-surface-container-lowest leading-tight">
              Pusat Distribusi &amp; Belanja Telur Segar Terpercaya Tanggamus
            </h2>
<p class="font-body-md text-body-md text-surface-container-highest/90">
              Menghubungkan dapur keluarga, warung makan, hingga usaha katering langsung dengan kandang peternak binaan lokal berkadar nutrisi terjaga.
            </p>
</div>
<!-- Value Propositions -->
<div class="space-y-3 pt-2">
<!-- Item 1 -->
<div class="flex items-start gap-3 p-3 rounded-xl bg-surface-container-lowest/10 backdrop-blur-sm hover:bg-surface-container-lowest/15 transition-colors">
<div class="w-9 h-9 rounded-lg bg-primary-fixed text-on-primary-fixed flex items-center justify-center shrink-0 shadow-sm">
<span class="material-symbols-outlined text-lg">trending_down</span>
</div>
<div>
<h4 class="font-label-lg text-label-lg text-surface-container-lowest font-bold">Harga Kandang Harian</h4>
<p class="font-body-sm text-body-sm text-surface-container-highest/80 leading-relaxed">
                  Update harga transparan langsung dari peternak lokal tanpa perantara berlapis.
                </p>
</div>
</div>
<!-- Item 2 -->
<div class="flex items-start gap-3 p-3 rounded-xl bg-surface-container-lowest/10 backdrop-blur-sm hover:bg-surface-container-lowest/15 transition-colors">
<div class="w-9 h-9 rounded-lg bg-secondary-fixed text-on-secondary-fixed flex items-center justify-center shrink-0 shadow-sm">
<span class="material-symbols-outlined text-lg" style="font-variation-settings: 'FILL' 1;">verified_user</span>
</div>
<div>
<h4 class="font-label-lg text-label-lg text-surface-container-lowest font-bold">Garansi Pecah Ganti 100%</h4>
<p class="font-body-sm text-body-sm text-surface-container-highest/80 leading-relaxed">
                  Cek langsung saat kurir tiba. Ada retak atau pecah? Diganti gratis saat itu juga.
                </p>
</div>
</div>
<!-- Item 3 -->
<div class="flex items-start gap-3 p-3 rounded-xl bg-surface-container-lowest/10 backdrop-blur-sm hover:bg-surface-container-lowest/15 transition-colors">
<div class="w-9 h-9 rounded-lg bg-primary-container text-on-primary-container flex items-center justify-center shrink-0 shadow-sm">
<span class="material-symbols-outlined text-lg">calendar_month</span>
</div>
<div>
<h4 class="font-label-lg text-label-lg text-surface-container-lowest font-bold">Langganan Rutin Mudah</h4>
<p class="font-body-sm text-body-sm text-surface-container-highest/80 leading-relaxed">
                  Jadwal pengiriman otomatis mingguan untuk stok warung bakso, rumah makan, atau katering.
                </p>
</div>
</div>
<!-- Item 4 -->
<div class="flex items-start gap-3 p-3 rounded-xl bg-surface-container-lowest/10 backdrop-blur-sm hover:bg-surface-container-lowest/15 transition-colors">
<div class="w-9 h-9 rounded-lg bg-surface-container-lowest text-primary flex items-center justify-center shrink-0 shadow-sm">
<span class="material-symbols-outlined text-lg">two_wheeler</span>
</div>
<div>
<h4 class="font-label-lg text-label-lg text-surface-container-lowest font-bold">Kurir Tanggamus Suspensi Busa</h4>
<p class="font-body-sm text-body-sm text-surface-container-highest/80 leading-relaxed">
                  Box angkut khusus anti-getar menjaga integritas cangkang di jalan berbukit.
                </p>
</div>
</div>
</div>
</div>
<!-- Left Bottom Testimonial Card -->
<div class="relative z-10 pt-6 mt-6 border-t border-surface-container-highest/20">
<div class="p-4 rounded-xl bg-surface-container-lowest/15 backdrop-blur-md">
<div class="flex items-center gap-1 text-primary-fixed mb-1.5">
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="text-xs text-surface-container-lowest ml-2 font-bold">5.0 / 5.0</span>
</div>
<p class="font-body-sm text-body-sm text-surface-container-lowest italic leading-relaxed">
              "Kuning telurnya oranye pekat dan kental sekali. Timbangannya pas, kurirnya ramah nungguin saya periksa per krat. Langganan terbaik di Talang Padang!"
            </p>
<div class="flex items-center justify-between mt-3 text-xs text-surface-container-highest">
<span class="font-bold text-surface-container-lowest">Ibu Heni Novita</span>
<span class="text-secondary-fixed">Usaha Kue Rumahan, Talang Padang</span>
</div>
</div>
</div>
</div>
<!-- RIGHT COLUMN: Authentication Form (Login & Register Panels) -->
<div class="lg:col-span-7 xl:col-span-7 p-6 sm:p-8 md:p-10 flex flex-col justify-between bg-surface-container-lowest">
<div class="w-full max-w-xl mx-auto space-y-6">
<!-- Welcoming Header -->
<div class="space-y-1.5 text-left">
<div class="inline-flex items-center gap-2 px-2.5 py-1 rounded-md bg-secondary-container text-on-secondary-container text-label-sm font-label-sm">
<span class="material-symbols-outlined text-sm">storefront</span>
<span>Portal Pembeli Tanggamus</span>
</div>
<h1 class="font-headline-lg text-headline-lg text-on-surface tracking-tight">
              Selamat Datang di Pasar Telur Bang Zul!
            </h1>
<p class="font-body-md text-body-md text-on-surface-variant">
              Masuk atau buat akun baru untuk kemudahan belanja telur segar berkualitas super dengan harga peternak.
            </p>
</div>
<!-- Role / Tab Segmented Control -->
<div class="w-full bg-surface-container p-1 rounded-xl flex items-center gap-1 shadow-inner" id="authSegmentControl">
<button class="flex-1 py-2.5 px-4 rounded-lg font-label-lg text-label-lg transition-all duration-200 flex items-center justify-center gap-2 bg-surface-container-lowest text-primary shadow-sm font-bold" id="tabBtnLogin" onclick="switchAuthTab('login')" type="button">
<span class="material-symbols-outlined text-lg">login</span>
<span>Masuk ke Akun</span>
</button>
<button class="flex-1 py-2.5 px-4 rounded-lg font-label-lg text-label-lg transition-all duration-200 flex items-center justify-center gap-2 text-on-surface-variant hover:text-on-surface font-semibold" id="tabBtnRegister" onclick="switchAuthTab('register')" type="button">
<span class="material-symbols-outlined text-lg">person_add</span>
<span>Daftar Akun Baru</span>
</button>
</div>
<!-- TAB PANEL 1: LOGIN FORM -->
<div class="space-y-5 transition-opacity duration-300" id="panelLogin">
<form class="space-y-4" onsubmit="handleLoginSubmit(event)">
<!-- Identifier Input -->
<div class="space-y-1">
<label class="block font-label-md text-label-md text-on-surface font-semibold" for="loginIdentifier">
                  Nomor WhatsApp atau Email
                </label>
<div class="relative flex items-center">
<span class="material-symbols-outlined absolute left-3.5 text-outline text-lg pointer-events-none">phone_iphone</span>
<input class="w-full pl-11 pr-4 py-3 rounded-xl bg-surface-container-low text-body-md font-body-md text-on-surface placeholder:text-outline focus:bg-surface-container-lowest focus:outline-none focus:ring-2 focus:ring-primary-container transition-all" id="loginIdentifier" placeholder="0812-xxxx-xxxx atau nama@email.com" required="" type="text"/>
</div>
<p class="text-xs text-on-surface-variant">Gunakan nomor WhatsApp aktif untuk terima nota timbangan digital.</p>
</div>
<!-- Password Input -->
<div class="space-y-1">
<div class="flex items-center justify-between">
<label class="block font-label-md text-label-md text-on-surface font-semibold" for="loginPassword">
                    Kata Sandi
                  </label>
<a class="font-label-sm text-label-sm text-primary hover:underline" href="#" onclick="alert('Fitur Reset Sandi via WhatsApp: Silakan hubungi CS Bang Zul di 0812-7890-XXXX dengan menyertakan nomor terdaftar.'); return false;">
                    Lupa Kata Sandi?
                  </a>
</div>
<div class="relative flex items-center">
<span class="material-symbols-outlined absolute left-3.5 text-outline text-lg pointer-events-none">lock</span>
<input class="w-full pl-11 pr-12 py-3 rounded-xl bg-surface-container-low text-body-md font-body-md text-on-surface placeholder:text-outline focus:bg-surface-container-lowest focus:outline-none focus:ring-2 focus:ring-primary-container transition-all" id="loginPassword" placeholder="Masukkan kata sandi akun Anda" required="" type="password"/>
<button class="absolute right-3.5 p-1 rounded-md text-outline hover:text-on-surface focus:outline-none" onclick="togglePasswordVisibility('loginPassword', 'eyeIconLogin')" type="button">
<span class="material-symbols-outlined text-lg" id="eyeIconLogin">visibility</span>
</button>
</div>
</div>
<!-- Remember & Security Options -->
<div class="flex items-center justify-between pt-1">
<label class="flex items-center gap-2 cursor-pointer select-none">
<input checked="" class="w-4 h-4 rounded text-primary focus:ring-primary-container accent-primary" type="checkbox"/>
<span class="font-body-sm text-body-sm text-on-surface">Ingat Saya di Perangkat Ini</span>
</label>
<span class="hidden sm:inline-flex items-center gap-1 text-xs text-secondary font-medium">
<span class="material-symbols-outlined text-xs">lock</span>
                  Koneksi Aman SSL
                </span>
</div>
<!-- Primary Submit CTA -->
<button class="w-full py-3.5 px-6 rounded-xl bg-primary-container text-on-primary-container hover:bg-primary-fixed-dim active:scale-[0.99] font-label-lg text-label-lg font-bold flex items-center justify-center gap-2 shadow-md hover:shadow-lg transition-all duration-150" type="submit">
<span class="material-symbols-outlined text-lg">login</span>
<span>Masuk Sekarang</span>
</button>
</form>
<!-- Divider -->
<div class="relative flex items-center justify-center py-2">
<div class="w-full h-px bg-surface-container-highest"></div>
<span class="absolute bg-surface-container-lowest px-3 font-label-sm text-label-sm text-outline">atau cara instan</span>
</div>
<!-- Fast WhatsApp OTP Login Option -->
<button class="w-full py-3 px-4 rounded-xl bg-secondary-container/50 text-on-secondary-container hover:bg-secondary-container active:scale-[0.99] font-label-md text-label-md font-bold flex items-center justify-center gap-2.5 transition-all" onclick="sendWhatsAppOtp()" type="button">
<span class="material-symbols-outlined text-secondary text-xl">chat</span>
<span>Masuk Cepat dengan Kode OTP WhatsApp</span>
</button>
<div class="p-3.5 rounded-xl bg-surface-container-low flex items-start gap-3">
<span class="material-symbols-outlined text-primary text-xl shrink-0 mt-0.5">info</span>
<p class="font-body-sm text-body-sm text-on-surface-variant">
                Belum punya akun? Klik tab <strong class="text-primary cursor-pointer hover:underline" onclick="switchAuthTab('register')">Daftar Akun Baru</strong> di atas untuk mendapatkan voucer gratis ongkir perdana se-wilayah Tanggamus.
              </p>
</div>
</div>
<!-- TAB PANEL 2: REGISTER FORM -->
<div class="space-y-5 hidden transition-opacity duration-300" id="panelRegister">
<form class="space-y-3.5" onsubmit="handleRegisterSubmit(event)">
<!-- Full Name -->
<div class="space-y-1">
<label class="block font-label-md text-label-md text-on-surface font-semibold" for="regFullName">
                  Nama Lengkap <span class="text-error">*</span>
</label>
<div class="relative flex items-center">
<span class="material-symbols-outlined absolute left-3.5 text-outline text-lg pointer-events-none">person</span>
<input class="w-full pl-11 pr-4 py-2.5 rounded-xl bg-surface-container-low text-body-md font-body-md text-on-surface placeholder:text-outline focus:bg-surface-container-lowest focus:outline-none focus:ring-2 focus:ring-primary-container transition-all" id="regFullName" placeholder="Contoh: Bpk. Sugeng / Ibu Rahmawati" required="" type="text"/>
</div>
<span class="text-[11px] text-on-surface-variant">Nama penerima paket untuk memudahkan kurir saat pengantaran.</span>
</div>
<!-- WhatsApp Number -->
<div class="space-y-1">
<label class="block font-label-md text-label-md text-on-surface font-semibold" for="regWhatsapp">
                  Nomor WhatsApp Aktif <span class="text-error">*</span>
</label>
<div class="relative flex items-center">
<span class="material-symbols-outlined absolute left-3.5 text-outline text-lg pointer-events-none">chat</span>
<input class="w-full pl-11 pr-4 py-2.5 rounded-xl bg-surface-container-low text-body-md font-body-md text-on-surface placeholder:text-outline focus:bg-surface-container-lowest focus:outline-none focus:ring-2 focus:ring-primary-container transition-all" id="regWhatsapp" placeholder="08xxxxxxxxxx" required="" type="tel"/>
</div>
<span class="text-[11px] text-secondary font-medium">Wajib aktif: Kurir akan kirim bukti foto timbangan &amp; koordinat GPS via WA.</span>
</div>
<!-- Two Column Fields: Email & Tanggamus District -->
<div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
<!-- Email (Optional) -->
<div class="space-y-1">
<label class="block font-label-md text-label-md text-on-surface font-semibold" for="regEmail">
                    Email <span class="text-xs text-outline font-normal">(Opsional)</span>
</label>
<div class="relative flex items-center">
<span class="material-symbols-outlined absolute left-3.5 text-outline text-lg pointer-events-none">mail</span>
<input class="w-full pl-11 pr-4 py-2.5 rounded-xl bg-surface-container-low text-body-md font-body-md text-on-surface placeholder:text-outline focus:bg-surface-container-lowest focus:outline-none focus:ring-2 focus:ring-primary-container transition-all" id="regEmail" placeholder="nama@email.com" type="email"/>
</div>
</div>
<!-- Tanggamus District Selector -->
<div class="space-y-1">
<label class="block font-label-md text-label-md text-on-surface font-semibold" for="regDistrict">
                    Kecamatan Domisili <span class="text-error">*</span>
</label>
<div class="relative flex items-center">
<span class="material-symbols-outlined absolute left-3.5 text-outline text-lg pointer-events-none">location_on</span>
<select class="w-full pl-11 pr-8 py-2.5 rounded-xl bg-surface-container-low text-body-md font-body-md text-on-surface focus:bg-surface-container-lowest focus:outline-none focus:ring-2 focus:ring-primary-container transition-all appearance-none cursor-pointer" id="regDistrict" required="">
<option disabled="" selected="" value="">Pilih Kecamatan Anda</option>
<option value="Gisting">Kec. Gisting (Dekat Peternakan)</option>
<option value="Talang Padang">Kec. Talang Padang</option>
<option value="Kota Agung">Kec. Kota Agung (Pusat Kota)</option>
<option value="Kota Agung Barat">Kec. Kota Agung Barat</option>
<option value="Kota Agung Timur">Kec. Kota Agung Timur</option>
<option value="Wonosobo">Kec. Wonosobo</option>
<option value="Pugung">Kec. Pugung</option>
<option value="Sumberejo">Kec. Sumberejo</option>
<option value="Pulau Panggung">Kec. Pulau Panggung</option>
<option value="Semaka">Kec. Semaka</option>
<option value="Air Naningan">Kec. Air Naningan</option>
<option value="Ulu Belu">Kec. Ulu Belu</option>
<option value="Gunung Alip">Kec. Gunung Alip</option>
<option value="Bulok">Kec. Bulok</option>
<option value="Limau">Kec. Limau</option>
<option value="Cukuh Balak">Kec. Cukuh Balak</option>
<option value="Kelumbayan">Kec. Kelumbayan</option>
<option value="Pringsewu Sekitarnya">Perbatasan Kab. Pringsewu</option>
</select>
<span class="material-symbols-outlined absolute right-3 text-outline text-lg pointer-events-none">expand_more</span>
</div>
</div>
</div>
<!-- Password & Password Confirm -->
<div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
<!-- Password -->
<div class="space-y-1">
<label class="block font-label-md text-label-md text-on-surface font-semibold" for="regPassword">
                    Kata Sandi <span class="text-error">*</span>
</label>
<div class="relative flex items-center">
<span class="material-symbols-outlined absolute left-3 text-outline text-base pointer-events-none">key</span>
<input class="w-full pl-9 pr-9 py-2.5 rounded-xl bg-surface-container-low text-body-md font-body-md text-on-surface placeholder:text-outline focus:bg-surface-container-lowest focus:outline-none focus:ring-2 focus:ring-primary-container transition-all" id="regPassword" oninput="checkPasswordStrength(this.value)" placeholder="Minimal 6 karakter" required="" type="password"/>
<button class="absolute right-2.5 p-1 text-outline hover:text-on-surface" onclick="togglePasswordVisibility('regPassword', 'eyeIconReg1')" type="button">
<span class="material-symbols-outlined text-base" id="eyeIconReg1">visibility</span>
</button>
</div>
</div>
<!-- Confirm Password -->
<div class="space-y-1">
<label class="block font-label-md text-label-md text-on-surface font-semibold" for="regPasswordConfirm">
                    Ulangi Kata Sandi <span class="text-error">*</span>
</label>
<div class="relative flex items-center">
<span class="material-symbols-outlined absolute left-3 text-outline text-base pointer-events-none">lock_reset</span>
<input class="w-full pl-9 pr-9 py-2.5 rounded-xl bg-surface-container-low text-body-md font-body-md text-on-surface placeholder:text-outline focus:bg-surface-container-lowest focus:outline-none focus:ring-2 focus:ring-primary-container transition-all" id="regPasswordConfirm" placeholder="Sama dengan kata sandi" required="" type="password"/>
<button class="absolute right-2.5 p-1 text-outline hover:text-on-surface" onclick="togglePasswordVisibility('regPasswordConfirm', 'eyeIconReg2')" type="button">
<span class="material-symbols-outlined text-base" id="eyeIconReg2">visibility</span>
</button>
</div>
</div>
</div>
<!-- Password Strength Meter -->
<div class="space-y-1 pt-0.5">
<div class="flex items-center justify-between text-[11px]">
<span class="text-on-surface-variant font-medium">Kekuatan Sandi:</span>
<span class="text-outline font-semibold" id="strengthLabel">Belum diisi</span>
</div>
<div class="w-full h-1.5 bg-surface-container rounded-full overflow-hidden flex gap-1">
<div class="h-full w-1/3 bg-surface-container-highest transition-colors" id="bar1"></div>
<div class="h-full w-1/3 bg-surface-container-highest transition-colors" id="bar2"></div>
<div class="h-full w-1/3 bg-surface-container-highest transition-colors" id="bar3"></div>
</div>
</div>
<!-- Terms & Agreement Checkbox -->
<div class="pt-2">
<label class="flex items-start gap-2.5 cursor-pointer select-none">
<input class="mt-1 w-4 h-4 rounded text-primary focus:ring-primary-container accent-primary shrink-0" required="" type="checkbox"/>
<span class="font-body-sm text-body-sm text-on-surface-variant">
                    Saya menyetujui <a class="text-primary font-semibold hover:underline" href="#">Ketentuan Layanan</a> &amp; <a class="text-primary font-semibold hover:underline" href="#">Kebijakan Privasi</a> Bang Zul Egg Market Tanggamus.
                  </span>
</label>
</div>
<!-- Submit Button -->
<button class="w-full mt-2 py-3.5 px-6 rounded-xl bg-secondary text-on-secondary hover:bg-secondary-fixed-variant active:scale-[0.99] font-label-lg text-label-lg font-bold flex items-center justify-center gap-2 shadow-md hover:shadow-lg transition-all duration-150" type="submit">
<span class="material-symbols-outlined text-lg">how_to_reg</span>
<span>Buat Akun Sekarang</span>
</button>
</form>
</div>
</div>
<!-- Form Footer / Offline & Quick WhatsApp Support -->
<div class="w-full max-w-xl mx-auto pt-6 mt-6 border-t border-surface-container-highest">
<div class="flex flex-col sm:flex-row items-center justify-between gap-3 text-center sm:text-left">
<div class="space-y-0.5">
<p class="font-label-md text-label-md text-on-surface font-bold flex items-center justify-center sm:justify-start gap-1.5">
<span class="material-symbols-outlined text-secondary text-base">support_agent</span>
<span>Pesan Cepat Tanpa Akun?</span>
</p>
<p class="font-body-sm text-body-sm text-on-surface-variant">
                Langsung kirim daftar pesanan krat/ikat ke Bang Zul via WhatsApp.
              </p>
</div>
<a class="shrink-0 px-4 py-2 rounded-xl bg-surface-container text-on-surface hover:bg-surface-container-high transition-colors font-label-sm text-label-sm font-bold flex items-center gap-1.5 shadow-sm" href="https://wa.me/6281278900000?text=Halo%20Bang%20Zul,%20saya%20mau%20pesan%20telur%20segar%20langsung" rel="noopener noreferrer" target="_blank">
<span class="material-symbols-outlined text-secondary text-base">chat</span>
<span>0812-7890-XXXX</span>
</a>
</div>
</div>
</div>
</div>
<!-- Bottom Feature Highlights for Market Trust -->
<div class="grid grid-cols-2 md:grid-cols-4 gap-4 mt-8">
<div class="p-4 rounded-xl bg-surface-container-low flex items-center gap-3">
<span class="material-symbols-outlined text-primary text-2xl shrink-0">scale</span>
<div>
<h4 class="font-label-md text-label-md text-on-surface font-bold">Timbangan Presisi</h4>
<p class="font-body-sm text-body-sm text-on-surface-variant">Tera digital akurat per gram</p>
</div>
</div>
<div class="p-4 rounded-xl bg-surface-container-low flex items-center gap-3">
<span class="material-symbols-outlined text-secondary text-2xl shrink-0">alarm_on</span>
<div>
<h4 class="font-label-md text-label-md text-on-surface font-bold">Panen H-0</h4>
<p class="font-body-sm text-body-sm text-on-surface-variant">Maksimal 24 jam dari kandang</p>
</div>
</div>
<div class="p-4 rounded-xl bg-surface-container-low flex items-center gap-3">
<span class="material-symbols-outlined text-primary text-2xl shrink-0">pin_drop</span>
<div>
<h4 class="font-label-md text-label-md text-on-surface font-bold">Cakupan Luas</h4>
<p class="font-body-sm text-body-sm text-on-surface-variant">17 Kecamatan se-Tanggamus</p>
</div>
</div>
<div class="p-4 rounded-xl bg-surface-container-low flex items-center gap-3">
<span class="material-symbols-outlined text-secondary text-2xl shrink-0">payments</span>
<div>
<h4 class="font-label-md text-label-md text-on-surface font-bold">Bisa Bayar COD</h4>
<p class="font-body-sm text-body-sm text-on-surface-variant">Cek telur dulu, baru bayar</p>
</div>
</div>
</div>
</div>
</div>
<script>
  // Tab Switcher Logic
  function switchAuthTab(tab) {
    const tabBtnLogin = document.getElementById('tabBtnLogin');
    const tabBtnRegister = document.getElementById('tabBtnRegister');
    const panelLogin = document.getElementById('panelLogin');
    const panelRegister = document.getElementById('panelRegister');

    if (tab === 'login') {
      // Buttons state
      tabBtnLogin.className = "flex-1 py-2.5 px-4 rounded-lg font-label-lg text-label-lg transition-all duration-200 flex items-center justify-center gap-2 bg-surface-container-lowest text-primary shadow-sm font-bold";
      tabBtnRegister.className = "flex-1 py-2.5 px-4 rounded-lg font-label-lg text-label-lg transition-all duration-200 flex items-center justify-center gap-2 text-on-surface-variant hover:text-on-surface font-semibold";
      
      // Panels state
      panelLogin.classList.remove('hidden');
      panelRegister.classList.add('hidden');
    } else {
      // Buttons state
      tabBtnRegister.className = "flex-1 py-2.5 px-4 rounded-lg font-label-lg text-label-lg transition-all duration-200 flex items-center justify-center gap-2 bg-surface-container-lowest text-secondary shadow-sm font-bold";
      tabBtnLogin.className = "flex-1 py-2.5 px-4 rounded-lg font-label-lg text-label-lg transition-all duration-200 flex items-center justify-center gap-2 text-on-surface-variant hover:text-on-surface font-semibold";
      
      // Panels state
      panelLogin.classList.add('hidden');
      panelRegister.classList.remove('hidden');
    }
  }

  // Password Visibility Toggle
  function togglePasswordVisibility(inputId, iconId) {
    const input = document.getElementById(inputId);
    const icon = document.getElementById(iconId);
    if (!input || !icon) return;

    if (input.type === 'password') {
      input.type = 'text';
      icon.textContent = 'visibility_off';
    } else {
      input.type = 'password';
      icon.textContent = 'visibility';
    }
  }

  // Password Strength Validator
  function checkPasswordStrength(val) {
    const bar1 = document.getElementById('bar1');
    const bar2 = document.getElementById('bar2');
    const bar3 = document.getElementById('bar3');
    const label = document.getElementById('strengthLabel');

    // Reset bars
    bar1.className = 'h-full w-1/3 bg-surface-container-highest transition-colors';
    bar2.className = 'h-full w-1/3 bg-surface-container-highest transition-colors';
    bar3.className = 'h-full w-1/3 bg-surface-container-highest transition-colors';

    if (!val || val.length === 0) {
      label.textContent = 'Belum diisi';
      label.className = 'text-outline font-semibold';
      return;
    }

    if (val.length < 6) {
      bar1.className = 'h-full w-1/3 bg-error transition-colors';
      label.textContent = 'Kurang (Min. 6 Karakter)';
      label.className = 'text-error font-semibold';
    } else if (val.length >= 6 && val.length < 9) {
      bar1.className = 'h-full w-1/3 bg-primary-container transition-colors';
      bar2.className = 'h-full w-1/3 bg-primary-container transition-colors';
      label.textContent = 'Cukup Baik';
      label.className = 'text-on-primary-container font-semibold';
    } else {
      bar1.className = 'h-full w-1/3 bg-secondary transition-colors';
      bar2.className = 'h-full w-1/3 bg-secondary transition-colors';
      bar3.className = 'h-full w-1/3 bg-secondary transition-colors';
      label.textContent = 'Kuat & Aman';
      label.className = 'text-secondary font-bold';
    }
  }

  // Fast WhatsApp OTP Handler
  function sendWhatsAppOtp() {
    const input = document.getElementById('loginIdentifier');
    const val = input.value.trim();
    if (!val) {
      alert('Silakan ketik nomor WhatsApp aktif Anda pada kolom input di atas terlebih dahulu.');
      input.focus();
      return;
    }
    alert('Kode OTP Masuk Instan berhasil dikirim ke nomor WhatsApp: ' + val + '\n\nSilakan periksa pesan chat Anda dari "Bang Zul Market Bot".');
  }

  // Form Submit Interactivity
  function handleLoginSubmit(e) {
    e.preventDefault();
    const ident = document.getElementById('loginIdentifier').value;
    alert('Berhasil masuk! Selamat berbelanja telur segar, ' + ident);
  }

  function handleRegisterSubmit(e) {
    e.preventDefault();
    const name = document.getElementById('regFullName').value;
    const district = document.getElementById('regDistrict').value;
    const p1 = document.getElementById('regPassword').value;
    const p2 = document.getElementById('regPasswordConfirm').value;

    if (p1 !== p2) {
      alert('Perhatian: Kata Sandi dan Konfirmasi Kata Sandi tidak cocok. Mohon periksa kembali.');
      return;
    }

    alert('Selamat ' + name + '! Pendaftaran akun pembeli wilayah Kec. ' + district + ' berhasil dibuat. Voucer belanja perdana telah ditambahkan ke akun Anda.');
    switchAuthTab('login');
  }
</script></main><footer class="w-full bg-surface-container-low mt-16 pt-12 pb-8 text-on-surface-variant"><div class="max-w-7xl mx-auto px-4 lg:px-8 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8"><div class="space-y-3"><div class="flex items-center gap-2"><img alt="Logo Bang Zul Egg Market" class="h-7 w-auto object-contain" src="https://lh3.googleusercontent.com/aida/ALJJyrAvuhgJbL1OqXYnorOpflEwk9ch2RB3i3nIpJf2khBHtFUraZYLjA49xnoYr5_XpY1inx_yvUKDG-f5ULodcAC4hoBl9QYWujU07wAAJsvNI88PefRZRNH2SgRzcvtvfP9LlMDgvobQRRrHxWwLlWY8MQoR1CS4kennwXqXJqn5PR3R5zkf-p4q0eleDblVHlCAtE__Wj8FbqU6db9zlBw02jnLdLpow_xGCN8RF4es"/><span class="font-headline-sm text-headline-sm text-primary">UD. Bang Zul Egg Market</span></div><p class="font-body-sm text-body-sm">Pusat distribusi telur segar langsung dari peternak binaan lokal Tanggamus. Menjaga kualitas kesegaran cangkang utuh dan timbangan presisi terpercaya.</p><div class="flex items-center gap-2 text-secondary font-label-sm text-label-sm"><span class="material-symbols-outlined text-sm">verified</span><span>Garansi Ganti Telur Pecah 100% Langsung di Tempat</span></div></div><div class="space-y-2"><h3 class="font-headline-sm text-headline-sm text-on-surface">Jam Operasional &amp; Panen</h3><p class="font-body-sm text-body-sm">Pengambilan Telur Kandang: 06.00 - 10.00 WIB</p><p class="font-body-sm text-body-sm">Jadwal Pengiriman Kurir: 08.00 - 18.00 WIB</p><p class="font-body-sm text-body-sm text-secondary font-semibold">Setiap Hari (Senin - Minggu Tetap Buka)</p><p class="font-label-sm text-label-sm text-on-surface-variant pt-1">Wilayah Gisting, Talang Padang, Wonosobo, Kota Agung &amp; Sekitarnya.</p></div><div class="space-y-2"><h3 class="font-headline-sm text-headline-sm text-on-surface">Metode Pembayaran</h3><div class="space-y-1 font-body-sm text-body-sm"><p class="flex items-center gap-1.5"><span class="material-symbols-outlined text-primary text-sm">qr_code_scanner</span>QRIS Seluruh Bank &amp; E-Wallet</p><p class="flex items-center gap-1.5"><span class="material-symbols-outlined text-primary text-sm">account_balance</span>Transfer Bank Lampung / BRI / BCA</p><p class="flex items-center gap-1.5"><span class="material-symbols-outlined text-primary text-sm">payments</span>COD (Bayar Tunai di Tempat saat Timbang)</p></div></div><div class="space-y-2"><h3 class="font-headline-sm text-headline-sm text-on-surface">Komitmen Peternak Lokal</h3><p class="font-body-sm text-body-sm">Mendukung keberlanjutan usaha peternak unggas pedesaan di Kabupaten Tanggamus, Lampung dengan harga adil, timbangan transparan, dan pakan alami bermutu.</p><div class="pt-2"><span class="inline-block px-3 py-1 bg-secondary-container text-on-secondary-container rounded-full font-label-sm text-label-sm">Asli Tanggamus, Segar Bergaransi</span></div></div></div><div class="max-w-7xl mx-auto px-4 lg:px-8 mt-10 pt-4 flex flex-col sm:flex-row items-center justify-between gap-2 font-label-sm text-label-sm text-on-surface-variant"><p>© 2024 UD. Bang Zul Egg Market Tanggamus Lampung. Hak Cipta Dilindungi.</p><p>Dibuat untuk ekosistem niaga agrikultur Kabupaten Tanggamus</p></div></footer></body></html>

<!-- Checkout Pembayaran Pembeli -->
<!DOCTYPE html>

<html lang="id"><head><meta charset="utf-8"/><meta content="width=device-width, initial-scale=1.0" name="viewport"/><meta content="web_standard" name="shell-type"/><link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" rel="stylesheet"/><link href="https://fonts.googleapis.com" rel="preconnect"/><link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/><link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&amp;family=Plus+Jakarta+Sans:wght@700;800&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/><style>@layer base{html,body{margin:0;padding:0;}body{overscroll-behavior:none;}main>:first-child{margin-top:0!important;}main>:last-child{margin-bottom:0!important;}}::-webkit-scrollbar{display:none;}</style><script src="https://cdn.tailwindcss.com"></script><script id="tailwind-config">tailwind.config={darkMode:"class",theme:{extend:{colors:{"secondary-container":"#a0f399","on-tertiary-fixed-variant":"#3e4a41","on-background":"#1b1c1c","on-error":"#ffffff","on-primary":"#ffffff","primary":"#835500","surface-container-highest":"#e4e2e1","on-secondary-fixed-variant":"#005312","surface-container-low":"#f6f3f2","background":"#fcf9f8","surface":"#fcf9f8","on-tertiary-fixed":"#131e17","on-secondary-container":"#217128","outline-variant":"#d7c3ae","inverse-surface":"#303030","surface-container":"#f0eded","on-secondary-fixed":"#002204","surface-bright":"#fcf9f8","primary-fixed":"#ffddb4","surface-dim":"#dcd9d9","surface-container-lowest":"#ffffff","tertiary":"#556158","on-primary-fixed":"#291800","secondary-fixed":"#a3f69c","tertiary-container":"#acb9ae","on-primary-container":"#644000","on-primary-fixed-variant":"#633f00","on-tertiary":"#ffffff","surface-variant":"#e4e2e1","on-tertiary-container":"#3e4a41","on-secondary":"#ffffff","inverse-on-surface":"#f3f0f0","surface-tint":"#835500","primary-fixed-dim":"#ffb955","on-surface-variant":"#524534","on-error-container":"#93000a","surface-container-high":"#eae7e7","error":"#ba1a1a","primary-container":"#f5a623","inverse-primary":"#ffb955","outline":"#857462","tertiary-fixed":"#d9e6da","tertiary-fixed-dim":"#bdcabe","error-container":"#ffdad6","secondary":"#1b6d24","on-surface":"#1b1c1c","secondary-fixed-dim":"#88d982"},borderRadius:{"DEFAULT":"0.25rem","lg":"0.5rem","xl":"0.75rem","full":"9999px"},spacing:{"space-md":"1rem","gutter":"1rem","space-lg":"1.5rem","space-xl":"2rem","gutter-desktop":"1.5rem","space-xs":"0.25rem","space-sm":"0.5rem","margin":"1rem","margin-desktop":"2.5rem"},fontFamily:{"body-md":["Inter"],"label-sm":["Inter"],"price-display":["Plus Jakarta Sans"],"stock-counter":["Inter"],"headline-md":["Plus Jakarta Sans"],"body-lg":["Inter"],"label-md":["Inter"],"headline-sm":["Plus Jakarta Sans"],"display-lg":["Plus Jakarta Sans"],"label-lg":["Inter"],"headline-lg-mobile":["Plus Jakarta Sans"],"headline-lg":["Plus Jakarta Sans"],"body-sm":["Inter"],"display-lg-mobile":["Plus Jakarta Sans"]},fontSize:{"body-md":["14px",{"lineHeight":"22px","fontWeight":"400"}],"label-sm":["11px",{"lineHeight":"14px","letterSpacing":"0.02em","fontWeight":"600"}],"price-display":["22px",{"lineHeight":"28px","letterSpacing":"-0.02em","fontWeight":"800"}],"stock-counter":["18px",{"lineHeight":"24px","letterSpacing":"0.01em","fontWeight":"700"}],"headline-md":["20px",{"lineHeight":"28px","fontWeight":"700"}],"body-lg":["16px",{"lineHeight":"26px","fontWeight":"400"}],"label-md":["12px",{"lineHeight":"16px","fontWeight":"600"}],"headline-sm":["16px",{"lineHeight":"24px","fontWeight":"700"}],"display-lg":["40px",{"lineHeight":"48px","letterSpacing":"-0.02em","fontWeight":"800"}],"label-lg":["14px",{"lineHeight":"20px","fontWeight":"600"}],"headline-lg-mobile":["22px",{"lineHeight":"30px","letterSpacing":"0em","fontWeight":"700"}],"headline-lg":["28px",{"lineHeight":"36px","letterSpacing":"-0.01em","fontWeight":"700"}],"body-sm":["12px",{"lineHeight":"18px","fontWeight":"400"}],"display-lg-mobile":["30px",{"lineHeight":"38px","letterSpacing":"-0.01em","fontWeight":"800"}]}}}}</script></head><body class="bg-surface font-body-md text-body-md text-on-surface antialiased"><header class="fixed top-0 left-0 w-full z-50 bg-surface/95 backdrop-blur-md shadow-[0_4px_20px_-2px_rgba(245,166,35,0.12)]"><div class="bg-secondary text-on-secondary px-4 py-1.5"><div class="max-w-7xl mx-auto flex flex-col md:flex-row items-center justify-between gap-1 text-label-sm font-label-sm"><div class="flex items-center gap-2 text-center md:text-left"><span class="material-symbols-outlined text-secondary-fixed text-sm">local_shipping</span><span>Pengiriman Segar Hari Ini ke Wilayah Kota Agung, Gisting, Talang Padang, Wonosobo, Pringsewu sekitarnya | <strong class="text-secondary-fixed">Garansi Telur Pecah Diganti 100%</strong></span></div><a class="flex items-center gap-1.5 hover:text-secondary-fixed transition-colors whitespace-nowrap" href="https://wa.me/6281278900000"><span class="material-symbols-outlined text-sm">chat</span><span>WhatsApp CS Hubungi Bang Zul: 0812-7890-XXXX</span></a></div></div><div class="max-w-7xl mx-auto px-4 lg:px-8 py-3 flex items-center justify-between gap-4"><a class="flex items-center gap-3 shrink-0" data-path="katalog-belanja-pembeli" href="#"><img alt="Logo Bang Zul Egg Market" class="h-8 w-auto object-contain" src="https://lh3.googleusercontent.com/aida/ALJJyrAvuhgJbL1OqXYnorOpflEwk9ch2RB3i3nIpJf2khBHtFUraZYLjA49xnoYr5_XpY1inx_yvUKDG-f5ULodcAC4hoBl9QYWujU07wAAJsvNI88PefRZRNH2SgRzcvtvfP9LlMDgvobQRRrHxWwLlWY8MQoR1CS4kennwXqXJqn5PR3R5zkf-p4q0eleDblVHlCAtE__Wj8FbqU6db9zlBw02jnLdLpow_xGCN8RF4es"/><div class="flex flex-col"><span class="font-headline-md text-headline-md text-primary tracking-tight leading-none">Bang Zul</span><span class="font-label-sm text-label-sm text-secondary font-bold tracking-wider uppercase leading-none mt-0.5">Egg Market Tanggamus</span></div></a><div class="hidden lg:flex items-center gap-1.5 px-3 py-1.5 rounded-full bg-surface-container-low text-on-surface-variant font-label-sm text-label-sm shrink-0"><span class="material-symbols-outlined text-primary text-base">location_on</span><span class="max-w-[210px] truncate">Kab. Tanggamus (Gisting, Kota Agung &amp; Sekitarnya)</span></div><div class="hidden md:flex flex-1 max-w-md mx-2"><div class="relative w-full flex items-center"><span class="material-symbols-outlined absolute left-3 text-outline text-lg">search</span><input class="w-full pl-10 pr-4 py-2 rounded-full bg-surface-container-lowest text-body-sm font-body-sm text-on-surface placeholder:text-outline focus:outline-none focus:ring-2 focus:ring-primary-container shadow-[0_1px_4px_rgba(0,0,0,0.04)]" placeholder="Cari telur ayam ras, telur omega, telur bebek, puyuh..." type="text"/></div></div><div class="flex items-center gap-2 md:gap-3 shrink-0"><a class="flex items-center gap-2 px-3 py-1.5 rounded-full bg-primary-container text-on-primary-container hover:bg-primary-fixed-dim transition-colors shadow-sm" data-path="keranjang-belanja-pembeli" href="#"><span class="material-symbols-outlined text-lg">shopping_basket</span><span class="hidden sm:inline font-label-sm text-label-sm">Keranjang (3 Item)</span></a><div class="hidden sm:flex items-center gap-1.5 pl-1"><a class="px-3 py-1.5 rounded-full bg-surface-container text-on-surface hover:bg-surface-container-high transition-colors font-label-sm text-label-sm" data-path="masuk-akun-pembeli" href="#">Masuk</a><a class="px-3 py-1.5 rounded-full bg-primary text-on-primary hover:bg-on-primary-container transition-colors font-label-sm text-label-sm" data-path="daftar-akun-pembeli" href="#">Daftar</a></div><a class="flex items-center gap-1.5 p-1.5 rounded-full hover:bg-surface-container-high text-on-surface-variant" data-path="profil-akun-pembeli" href="#"><img alt="Foto Akun Pembeli" class="w-8 h-8 rounded-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBu4cCay1o-kcZkrepBjdwRhNkTeb5NSNF4V20H1AoEXr4ahIrRP9SktX37TUve3u7us_GHnlm1279EoAyYcFxqZTZV4CIOdstOTCqIMcitiPTCwpWm4m2okjdh9z8S2I2n0sK1hb3y3ohWU84Tu6ZWNoxKL7D1NVLhMsBA3C6eHNQmukclnmKpMzHXssx-xtkh1wF2y2OFEDgXUgTPjjAfLabaOsUrz91MId6by4k"/></a></div></div><div class="bg-surface-container-lowest shadow-[0_1px_4px_rgba(0,0,0,0.02)] overflow-x-auto"><div class="max-w-7xl mx-auto px-4 lg:px-8"><nav class="flex items-center gap-6 whitespace-nowrap py-2.5 text-label-sm font-label-sm" data-active-classes="text-primary font-bold border-b-2 border-primary"><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="katalog-belanja-pembeli" href="#">Katalog Telur Segar</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="detail-produk-telur" href="#">Detail Produk Telur</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="keranjang-belanja-pembeli" href="#">Keranjang Belanja</a><a aria-current="page" class="transition-colors pb-1 text-primary font-bold border-b-2 border-primary" data-path="checkout-pembayaran-pembeli" href="#">Checkout Pembayaran</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="profil-akun-pembeli" href="#">Profil Saya</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="masuk-akun-pembeli" href="#">Masuk Akun</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="daftar-akun-pembeli" href="#">Daftar Akun Baru</a></nav></div></div></header><main class="w-full pt-36 bg-surface min-h-screen"><div class="flex flex-col w-full">
<!-- Top Stepper Progress Bar -->
<section class="w-full bg-surface-container-lowest shadow-sm mb-6">
<div class="max-w-7xl mx-auto px-4 lg:px-8 py-5">
<div class="flex items-center justify-between max-w-3xl mx-auto relative">
<div class="absolute left-6 right-6 top-1/2 -translate-y-1/2 h-1 bg-surface-container-highest -z-0">
<div class="h-full bg-secondary w-1/2 transition-all duration-300"></div>
</div>
<!-- Step 1: Selesai -->
<div class="relative z-10 flex flex-col items-center gap-1.5 bg-surface-container-lowest px-2">
<div class="w-9 h-9 rounded-full bg-secondary text-on-secondary flex items-center justify-center shadow-md">
<span class="material-symbols-outlined text-lg">check</span>
</div>
<span class="font-label-md text-label-md text-secondary font-bold">1. Alamat Kirim</span>
<span class="font-label-sm text-label-sm text-on-surface-variant hidden sm:inline">Tanggamus Lengkap</span>
</div>
<!-- Step 2: Aktif Sekarang -->
<div class="relative z-10 flex flex-col items-center gap-1.5 bg-surface-container-lowest px-2">
<div class="w-9 h-9 rounded-full bg-primary-container text-on-primary-container ring-4 ring-primary-fixed/40 flex items-center justify-center font-headline-sm text-headline-sm shadow-md animate-pulse">
            2
          </div>
<span class="font-label-md text-label-md text-primary font-bold">2. Metode Bayar</span>
<span class="font-label-sm text-label-sm text-on-surface-variant hidden sm:inline">Pilihan &amp; Rekening</span>
</div>
<!-- Step 3: Pending -->
<div class="relative z-10 flex flex-col items-center gap-1.5 bg-surface-container-lowest px-2">
<div class="w-9 h-9 rounded-full bg-surface-container-high text-on-surface-variant flex items-center justify-center font-headline-sm text-headline-sm">
            3
          </div>
<span class="font-label-md text-label-md text-on-surface-variant font-medium">3. Konfirmasi</span>
<span class="font-label-sm text-label-sm text-on-surface-variant hidden sm:inline">Instruksi Kasir</span>
</div>
</div>
</div>
</section>
<!-- Main Grid Content -->
<div class="max-w-7xl mx-auto px-4 lg:px-8 w-full pb-16">
<!-- Guarantee Banner Note -->
<div class="mb-6 p-4 rounded-xl bg-secondary-container/40 text-on-secondary-container flex items-start sm:items-center gap-3">
<span class="material-symbols-outlined text-secondary text-2xl shrink-0 mt-0.5 sm:mt-0">verified_user</span>
<div class="flex-1">
<p class="font-label-lg text-label-lg text-secondary font-bold">Jaminan Segar Dari Kandang Tanggamus Langsung</p>
<p class="font-body-sm text-body-sm text-on-surface-variant">Kurir membawa timbangan digital kalibrasi. Anda berhak periksa cangkang sebelum serah terima.</p>
</div>
<span class="hidden md:inline-flex items-center px-2.5 py-1 rounded-full bg-surface-container-lowest text-secondary font-label-sm text-label-sm font-bold shadow-sm">Garansi 100% Pecah Diganti</span>
</div>
<div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-start">
<!-- Sisi Kiri: Formulir Checkout & Opsi Pembayaran (8 Kolom Desktop) -->
<div class="lg:col-span-7 xl:col-span-8 space-y-6">
<!-- 1. Alamat Pengantaran Tanggamus -->
<div class="bg-surface-container-lowest rounded-xl p-5 sm:p-6 shadow-[0_4px_20px_-2px_rgba(245,166,35,0.08)]">
<div class="flex items-center justify-between pb-4 mb-4 bg-gradient-to-r from-transparent via-surface-container to-transparent bg-[length:100%_1px] bg-bottom bg-no-repeat">
<div class="flex items-center gap-2.5">
<span class="material-symbols-outlined text-primary text-2xl">home_pin</span>
<h2 class="font-headline-md text-headline-md text-on-surface">Alamat Pengantaran</h2>
</div>
<button class="px-3 py-1.5 rounded-full bg-surface-container-high hover:bg-surface-container-highest text-primary font-label-sm text-label-sm font-semibold transition-colors flex items-center gap-1" id="btn-toggle-address" type="button">
<span class="material-symbols-outlined text-base">edit_location</span>
              Ubah / Ganti
            </button>
</div>
<!-- Alamat Terpilih Default Card -->
<div class="bg-surface-container-low rounded-xl p-4 relative overflow-hidden transition-all" id="selected-address-card">
<div class="flex flex-col sm:flex-row sm:items-start justify-between gap-3">
<div class="space-y-1.5">
<div class="flex items-center gap-2">
<span class="px-2 py-0.5 rounded-md bg-secondary-container text-on-secondary-container font-label-sm text-label-sm font-bold">Rumah Utama</span>
<span class="font-label-lg text-label-lg text-on-surface font-bold">Ibu Mega Lestari</span>
<span class="font-body-sm text-body-sm text-on-surface-variant">(0812-7890-8821)</span>
</div>
<p class="font-body-md text-body-md text-on-surface">Jl. Raya Gisting Blok B No. 14, Pekon Gisting Bawah, Kec. Gisting, Kab. Tanggamus, Lampung 35378</p>
<div class="flex items-center gap-2 text-primary font-body-sm text-body-sm pt-1">
<span class="material-symbols-outlined text-base shrink-0">signpost</span>
<span>Patokan: Pagar cokelat depan Pos Ronda RT 04, samping pohon mangga arumanis</span>
</div>
</div>
<span class="inline-flex items-center gap-1 px-3 py-1 rounded-full bg-secondary/10 text-secondary font-label-sm text-label-sm font-semibold whitespace-nowrap self-start">
<span class="material-symbols-outlined text-sm">check_circle</span> Terverifikasi Kurir
              </span>
</div>
</div>
<!-- Collapsible Form Ganti Alamat -->
<form class="mt-4 pt-4 space-y-4 hidden bg-surface-container-lowest" id="address-form">
<div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
<div>
<label class="block font-label-sm text-label-sm text-on-surface-variant mb-1 font-semibold">Nama Penerima</label>
<input class="w-full px-3.5 py-2.5 rounded-lg bg-surface-container-lowest text-body-md text-on-surface outline-none ring-1 ring-outline-variant focus:ring-2 focus:ring-primary-container transition-all" placeholder="Nama lengkap penerima" type="text" value="Ibu Mega Lestari"/>
</div>
<div>
<label class="block font-label-sm text-label-sm text-on-surface-variant mb-1 font-semibold">No. WhatsApp (Aktif Notif Timbang)</label>
<input class="w-full px-3.5 py-2.5 rounded-lg bg-surface-container-lowest text-body-md text-on-surface outline-none ring-1 ring-outline-variant focus:ring-2 focus:ring-primary-container transition-all" placeholder="Contoh: 08127890xxxx" type="tel" value="0812-7890-8821"/>
</div>
</div>
<div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
<div>
<label class="block font-label-sm text-label-sm text-on-surface-variant mb-1 font-semibold">Kecamatan di Tanggamus</label>
<select class="w-full px-3.5 py-2.5 rounded-lg bg-surface-container-lowest text-body-md text-on-surface outline-none ring-1 ring-outline-variant focus:ring-2 focus:ring-primary-container transition-all">
<option selected="" value="gisting">Kec. Gisting (Free Ongkir Panen)</option>
<option value="talang-padang">Kec. Talang Padang</option>
<option value="kota-agung-pusat">Kec. Kota Agung Pusat</option>
<option value="kota-agung-barat">Kec. Kota Agung Barat</option>
<option value="kota-agung-timur">Kec. Kota Agung Timur</option>
<option value="wonosobo">Kec. Wonosobo</option>
<option value="pugung">Kec. Pugung</option>
<option value="sumberejo">Kec. Sumberejo</option>
</select>
</div>
<div>
<label class="block font-label-sm text-label-sm text-on-surface-variant mb-1 font-semibold">Patokan Gerbang / Pos / Ciri Rumah</label>
<input class="w-full px-3.5 py-2.5 rounded-lg bg-surface-container-lowest text-body-md text-on-surface outline-none ring-1 ring-outline-variant focus:ring-2 focus:ring-primary-container transition-all" placeholder="Contoh: Belakang Musholla Nurul Iman" type="text" value="Pagar cokelat samping pohon mangga arumanis"/>
</div>
</div>
<div>
<label class="block font-label-sm text-label-sm text-on-surface-variant mb-1 font-semibold">Alamat Lengkap Pekon / Dusun / RT-RW</label>
<textarea class="w-full px-3.5 py-2 rounded-lg bg-surface-container-lowest text-body-md text-on-surface outline-none ring-1 ring-outline-variant focus:ring-2 focus:ring-primary-container transition-all" placeholder="Tuliskan nama jalan, nomor rumah, RT/RW, dan nama pekon..." rows="2">Jl. Raya Gisting Blok B No. 14, Pekon Gisting Bawah</textarea>
</div>
<div>
<label class="block font-label-sm text-label-sm text-on-surface-variant mb-1 font-semibold">Instruksi Khusus untuk Kurir Motor Telur</label>
<input class="w-full px-3.5 py-2 rounded-lg bg-surface-container-lowest text-body-md text-on-surface outline-none ring-1 ring-outline-variant focus:ring-2 focus:ring-primary-container transition-all" placeholder="Contoh: Klakson 2 kali atau titip tetangga jika pagar tertutup" type="text" value="Titipkan di meja teras samping jika sedang belanja warung, minta nota basah."/>
</div>
<div class="flex justify-end gap-2 pt-2">
<button class="px-4 py-2 rounded-full bg-surface-container text-on-surface font-label-sm text-label-sm" id="btn-cancel-address" type="button">Batal</button>
<button class="px-5 py-2 rounded-full bg-primary text-on-primary font-label-sm text-label-sm font-bold shadow-sm hover:bg-on-primary-container transition-colors" id="btn-save-address" type="button">Simpan Alamat Ini</button>
</div>
</form>
</div>
<!-- 2. Jadwal Pengiriman Pagi/Sore -->
<div class="bg-surface-container-lowest rounded-xl p-5 sm:p-6 shadow-[0_4px_20px_-2px_rgba(245,166,35,0.08)]">
<div class="flex items-center gap-2.5 pb-4 mb-4 bg-gradient-to-r from-transparent via-surface-container to-transparent bg-[length:100%_1px] bg-bottom bg-no-repeat">
<span class="material-symbols-outlined text-primary text-2xl">schedule</span>
<div class="flex-1">
<h2 class="font-headline-md text-headline-md text-on-surface">Pilih Kloter Pengiriman Tanggamus</h2>
<p class="font-body-sm text-body-sm text-on-surface-variant">Telur dipacking langsung di krat berbusa peredam guncangan jalanan perbukitan</p>
</div>
</div>
<div class="grid grid-cols-1 md:grid-cols-2 gap-4" id="slot-container">
<!-- Slot 1 (Selected) -->
<label class="delivery-slot cursor-pointer relative p-4 rounded-xl bg-surface-container-low transition-all duration-200 block shadow-sm ring-2 ring-primary-container">
<div class="flex items-start gap-3">
<input checked="" class="mt-1 text-primary focus:ring-primary-container h-4 w-4" name="shipping_slot" type="radio" value="morning"/>
<div class="flex-1">
<div class="flex items-center justify-between gap-1 mb-1">
<span class="font-label-lg text-label-lg font-bold text-on-surface">Kloter 1: Pagi Segar</span>
<span class="px-2 py-0.5 rounded-full bg-secondary-container text-on-secondary-container font-label-sm text-label-sm font-bold">Panen Subuh</span>
</div>
<p class="font-headline-sm text-headline-sm text-primary font-bold">08.30 - 11.30 WIB</p>
<p class="font-body-sm text-body-sm text-on-surface-variant mt-1.5">Telur diambil langsung dari kandang jam 06.00 WIB, cangkang masih berbedak alami.</p>
</div>
</div>
</label>
<!-- Slot 2 -->
<label class="delivery-slot cursor-pointer relative p-4 rounded-xl bg-surface-container-low hover:bg-surface-container transition-all duration-200 block">
<div class="flex items-start gap-3">
<input class="mt-1 text-primary focus:ring-primary-container h-4 w-4" name="shipping_slot" type="radio" value="afternoon"/>
<div class="flex-1">
<div class="flex items-center justify-between gap-1 mb-1">
<span class="font-label-lg text-label-lg font-bold text-on-surface">Kloter 2: Sore Santai</span>
<span class="px-2 py-0.5 rounded-full bg-surface-container-highest text-on-surface-variant font-label-sm text-label-sm">Siap Masak</span>
</div>
<p class="font-headline-sm text-headline-sm text-on-surface font-bold">14.00 - 17.00 WIB</p>
<p class="font-body-sm text-body-sm text-on-surface-variant mt-1.5">Cocok untuk persiapan warung makan malam, martabak, atau bekal esok hari.</p>
</div>
</div>
</label>
</div>
</div>
<!-- 3. Metode Pembayaran -->
<div class="bg-surface-container-lowest rounded-xl p-5 sm:p-6 shadow-[0_4px_20px_-2px_rgba(245,166,35,0.08)]">
<div class="flex items-center justify-between pb-4 mb-4 bg-gradient-to-r from-transparent via-surface-container to-transparent bg-[length:100%_1px] bg-bottom bg-no-repeat">
<div class="flex items-center gap-2.5">
<span class="material-symbols-outlined text-primary text-2xl">account_balance_wallet</span>
<div>
<h2 class="font-headline-md text-headline-md text-on-surface">Metode Pembayaran</h2>
<p class="font-body-sm text-body-sm text-on-surface-variant">Pilih metode yang paling nyaman untuk Anda</p>
</div>
</div>
<span class="font-label-sm text-label-sm text-secondary font-bold flex items-center gap-1">
<span class="material-symbols-outlined text-sm">lock</span> Transaksi Aman
            </span>
</div>
<div class="space-y-3" id="payment-methods-list">
<!-- Opsi 1: Transfer Bank (Default Active) -->
<label class="payment-card cursor-pointer block p-4 rounded-xl bg-surface-container-low ring-2 ring-primary-container transition-all">
<div class="flex items-start gap-3.5">
<input checked="" class="mt-1 text-primary focus:ring-primary h-4 w-4" name="payment_method" type="radio" value="bank_transfer"/>
<div class="flex-1">
<div class="flex flex-col sm:flex-row sm:items-center justify-between gap-1">
<span class="font-label-lg text-label-lg font-bold text-on-surface">Transfer Bank (Verifikasi Manual / Cepat)</span>
<span class="font-label-sm text-label-sm text-secondary font-semibold">BRI, Bank Lampung, Mandiri, BCA</span>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant mt-0.5">Kirim bukti struk transfer/m-banking ke aplikasi. Dicek kasir Bang Zul &lt;10 menit.</p>
<div class="flex items-center gap-2 mt-2 pt-2 border-t-0 flex-wrap">
<span class="px-2 py-0.5 rounded bg-surface-container-highest text-on-surface font-label-sm text-label-sm font-bold">BRI</span>
<span class="px-2 py-0.5 rounded bg-surface-container-highest text-on-surface font-label-sm text-label-sm font-bold">Bank Lampung</span>
<span class="px-2 py-0.5 rounded bg-surface-container-highest text-on-surface font-label-sm text-label-sm font-bold">BCA</span>
<span class="px-2 py-0.5 rounded bg-surface-container-highest text-on-surface font-label-sm text-label-sm font-bold">Mandiri</span>
</div>
</div>
</div>
</label>
<!-- Opsi 2: QRIS / E-Wallet -->
<label class="payment-card cursor-pointer block p-4 rounded-xl bg-surface-container-low hover:bg-surface-container transition-all">
<div class="flex items-start gap-3.5">
<input class="mt-1 text-primary focus:ring-primary h-4 w-4" name="payment_method" type="radio" value="qris"/>
<div class="flex-1">
<div class="flex flex-col sm:flex-row sm:items-center justify-between gap-1">
<span class="font-label-lg text-label-lg font-bold text-on-surface">QRIS / E-Wallet Instan (Scan Langsung)</span>
<span class="font-label-sm text-label-sm text-secondary font-bold">Bebas Biaya Admin</span>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant mt-0.5">Dukung Dana, OVO, GoPay, ShopeePay, LinkAja, &amp; Semua M-Banking ber-QRIS.</p>
</div>
</div>
</label>
<!-- Opsi 3: COD Bayar di Tempat -->
<label class="payment-card cursor-pointer block p-4 rounded-xl bg-surface-container-low hover:bg-surface-container transition-all">
<div class="flex items-start gap-3.5">
<input class="mt-1 text-primary focus:ring-primary h-4 w-4" name="payment_method" type="radio" value="cod"/>
<div class="flex-1">
<div class="flex flex-col sm:flex-row sm:items-center justify-between gap-1">
<span class="font-label-lg text-label-lg font-bold text-on-surface">Bayar di Tempat / COD (Tunai ke Kurir)</span>
<span class="px-2 py-0.5 rounded-full bg-secondary-container text-on-secondary-container font-label-sm text-label-sm font-bold">Bisa Cek Telur Dulu</span>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant mt-0.5">Timbang ulang di depan Anda, periksa keutuhan cangkang telur, lalu bayar tunai pas ke kurir.</p>
</div>
</div>
</label>
</div>
</div>
<!-- 4. Section Instruksi Pembayaran Bank & Upload Bukti Transfer -->
<div class="bg-surface-container-lowest rounded-xl p-5 sm:p-6 shadow-[0_4px_20px_-2px_rgba(245,166,35,0.08)] space-y-6" id="bank-instruction-box">
<div class="flex items-center gap-2 pb-3 bg-gradient-to-r from-transparent via-surface-container to-transparent bg-[length:100%_1px] bg-bottom bg-no-repeat">
<span class="material-symbols-outlined text-primary text-xl">receipt_long</span>
<h3 class="font-headline-sm text-headline-sm text-on-surface">Instruksi Transfer Bank Rekening Resmi</h3>
</div>
<!-- Card Info Rekening Bang Zul -->
<div class="p-4 sm:p-5 rounded-xl bg-primary-fixed/20 space-y-3">
<div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2">
<div class="flex items-center gap-2.5">
<div class="w-10 h-10 rounded-lg bg-surface-container-lowest flex items-center justify-center font-headline-sm text-primary font-extrabold shadow-sm">
                  BRI
                </div>
<div>
<p class="font-label-sm text-label-sm text-on-surface-variant">Nama Bank &amp; Rekening Penerima</p>
<p class="font-label-lg text-label-lg text-on-surface font-bold">BANK RAKYAT INDONESIA (BRI)</p>
</div>
</div>
<span class="px-2.5 py-1 rounded bg-secondary-container text-on-secondary-container font-label-sm text-label-sm font-bold self-start sm:self-center">Kantor Kas Kota Agung</span>
</div>
<div class="bg-surface-container-lowest rounded-lg p-3 sm:p-4 flex flex-col sm:flex-row sm:items-center justify-between gap-3 shadow-sm">
<div>
<p class="font-label-sm text-label-sm text-on-surface-variant">Nomor Rekening Resmi UD Bang Zul:</p>
<p class="font-price-display text-price-display text-primary tracking-wider font-extrabold" id="rekening-number">0142-01-002938-53-1</p>
<p class="font-body-sm text-body-sm text-on-surface font-semibold">a/n UD BANG ZUL PASAR TELUR TANGGAMUS</p>
</div>
<button class="px-4 py-2 rounded-full bg-primary-container hover:bg-primary-fixed-dim text-on-primary-container font-label-md text-label-md font-bold transition-all flex items-center gap-1.5 self-start sm:self-center shadow-sm" id="btn-copy-rek" type="button">
<span class="material-symbols-outlined text-base">content_copy</span>
<span>Salin Nomor</span>
</button>
</div>
<!-- Total Nominal Transfer Presisi Dengan Kode Unik -->
<div class="bg-surface-container-lowest rounded-lg p-3 sm:p-4 flex flex-col sm:flex-row sm:items-center justify-between gap-2 shadow-sm">
<div>
<span class="font-label-sm text-label-sm text-on-surface-variant">Total Transfer Presisi (Termasuk 3 Digit Kode Unik):</span>
<p class="font-price-display text-price-display text-primary font-extrabold">Rp 206.188</p>
<p class="font-body-sm text-body-sm text-error font-medium">*Wajib transfer tepat 3 angka terakhir agar kasir langsung mengenali pesanan Anda.</p>
</div>
<button class="px-4 py-2 rounded-full bg-surface-container-high hover:bg-surface-container-highest text-on-surface font-label-md text-label-md font-semibold transition-all flex items-center gap-1.5 self-start sm:self-center" id="btn-copy-nominal" type="button">
<span class="material-symbols-outlined text-base">copy_all</span>
<span>Salin Nominal</span>
</button>
</div>
</div>
<!-- Area Upload Bukti Transfer Interaktif -->
<div class="space-y-3">
<div class="flex items-center justify-between">
<label class="font-label-lg text-label-lg font-bold text-on-surface flex items-center gap-1.5">
<span class="material-symbols-outlined text-primary text-base">cloud_upload</span>
                Unggah Bukti Transfer / Struk ATM
              </label>
<span class="font-label-sm text-label-sm text-on-surface-variant">Format: JPG, PNG, PDF (Maks 5MB)</span>
</div>
<div class="rounded-xl p-6 text-center cursor-pointer transition-all bg-surface-container-low hover:bg-surface-container group" id="drop-area">
<input accept="image/*,.pdf" class="hidden" id="file-bukti" type="file"/>
<div class="flex flex-col items-center justify-center space-y-2" id="upload-placeholder-content">
<div class="w-12 h-12 rounded-full bg-primary-fixed/40 text-primary flex items-center justify-center group-hover:scale-110 transition-transform">
<span class="material-symbols-outlined text-2xl">add_photo_alternate</span>
</div>
<p class="font-label-md text-label-md font-bold text-on-surface">Klik untuk pilih foto struk atau seret file ke sini</p>
<p class="font-body-sm text-body-sm text-on-surface-variant">Pastikan tanggal transaksi, nama pengirim, dan nominal Rp 206.188 terlihat jelas.</p>
</div>
<!-- Preview State (Initially Hidden) -->
<div class="hidden flex-col sm:flex-row items-center justify-between gap-4 text-left p-3 rounded-lg bg-surface-container-lowest shadow-sm" id="upload-preview-content">
<div class="flex items-center gap-3">
<div class="w-12 h-12 rounded-lg bg-surface-container-high overflow-hidden shrink-0 flex items-center justify-center">
<img class="w-full h-full object-cover" data-alt="Tangkapan layar struk bukti transfer mobile banking berhasil dengan nominal dua ratus enam ribu seratus delapan puluh delapan rupiah" id="preview-img" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBPwdXU--3t_mH9A8yRhUPxmrha96GIRPHP8B3dsJn6iqjh5eT2JNGZHtJZBGKFxOzr1nP2lGKSQogZemTH3UsbwR1TLfT_gTPNaiezikdzK6yRfiWa1Fsu4ATd06ZtE_iV8Fg4bSMxsGW0wEjWb8vWim0gNDjLGj1cPFdLIXif5mix_OdZ5NuC-ajXQgk1wCTS9T02Yh_PmhbEW3SfqnKco5cHyPNsUGfRBnCrA1I"/>
</div>
<div>
<p class="font-label-md text-label-md font-bold text-on-surface truncate max-w-[200px] sm:max-w-xs" id="file-name">struk_transfer_mBanking.jpg</p>
<p class="font-body-sm text-body-sm text-secondary font-semibold flex items-center gap-1">
<span class="material-symbols-outlined text-sm">check_circle</span>
                      Siap Dikirim ke Kasir
                    </p>
</div>
</div>
<button class="px-3 py-1.5 rounded-full bg-error-container text-on-error-container font-label-sm text-label-sm font-semibold hover:opacity-90" id="btn-remove-file" type="button">
                  Ganti File
                </button>
</div>
</div>
<!-- Status Pelayanan Kasir -->
<div class="p-3.5 rounded-xl bg-surface-container-low flex items-center gap-3 text-on-surface-variant font-body-sm text-body-sm">
<span class="material-symbols-outlined text-primary text-xl shrink-0 animate-spin">sync</span>
<p>Kasir Bang Zul siap memverifikasi pembayaran Anda dalam <strong class="text-on-surface font-semibold">maksimal 10 menit</strong> setelah bukti diunggah.</p>
</div>
</div>
</div>
</div>
<!-- Sisi Kanan: Ringkasan Pesanan & Checkout Sticky (4-5 Kolom Desktop) -->
<div class="lg:col-span-5 xl:col-span-4 space-y-6 lg:sticky lg:top-40">
<!-- Kartu Ringkasan Belanja Keranjang Telur -->
<div class="bg-surface-container-lowest rounded-xl p-5 shadow-[0_4px_20px_-2px_rgba(245,166,35,0.12)] space-y-4">
<div class="flex items-center justify-between pb-3 bg-gradient-to-r from-transparent via-surface-container to-transparent bg-[length:100%_1px] bg-bottom bg-no-repeat">
<h3 class="font-headline-md text-headline-md text-on-surface">Ringkasan Telur</h3>
<span class="px-2.5 py-0.5 rounded-full bg-surface-container-high font-label-sm text-label-sm font-bold text-on-surface-variant">3 Item</span>
</div>
<!-- List Produk Terpilih -->
<div class="space-y-3.5">
<!-- Item 1: Telur Ras -->
<div class="flex items-start gap-3">
<img class="w-14 h-14 rounded-lg object-cover bg-surface-container-low shrink-0" data-alt="Tumpukan krat telur ayam ras super segar Tanggamus dengan cangkang coklat seragam ditaruh di wadah karton telur tradisional pasar bersih" src="https://lh3.googleusercontent.com/aida-public/AB6AXuC_TApiR7qWxQhI4apcCmDL539Fhfhs5Dl-p29RzGbzFYV1LPhOYmqOV9fBzan-N0V4ZjtvOeq67rOQ4hM_griM0bY0kRe2TTimUvGBE0JqJ0DmHwy1C9C083WUXzTGdUPCfHU466lEUtkSCAL1z-RV0GjT9zsj-ipgZENfzLd5YFsuRHcdfhL8_CH-YxObfJO0ud8dNbyMfmfPmoYOpQe_N6GPEWBSkzp8cy8VM8M"/>
<div class="flex-1 min-w-0">
<h4 class="font-label-md text-label-md font-bold text-on-surface truncate">Telur Ayam Ras Super Karpet</h4>
<p class="font-body-sm text-body-sm text-on-surface-variant">2 Krat (Isi 60 Butir Timbang Basah)</p>
<div class="flex items-center justify-between mt-1">
<span class="font-label-sm text-label-sm text-tertiary">2x @ Rp 52.000</span>
<span class="font-label-lg text-label-lg font-bold text-on-surface">Rp 104.000</span>
</div>
</div>
</div>
<!-- Item 2: Telur Ayam Kampung -->
<div class="flex items-start gap-3">
<img class="w-14 h-14 rounded-lg object-cover bg-surface-container-low shrink-0" data-alt="Satu wadah anyaman bambu berisi telur ayam kampung asli dan telur omega dengan jerami padi pedesaan alami berlatar belakang dapur desa Tanggamus" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCeh1L49QDobDSloYxPxJlr9QZs_UV7GXAD1zES6M0iGTChu8ZkgfsDHdbxzeuz8UAXKIkdLF9oOx5GZdDX4xfKmQGOrLOBePpTbjClfPKdsputy59EikZptlSw3iZY1tqhUHgqG8lEaHvDoeryCdYpU6Hda2B-VDE_sa702z9eJe3W7_0byrMAaXEb0jtQlWmg_WcC5tNd5OaPwdoSzFPUzwshs_WJ8XZtgPo8zTE"/>
<div class="flex-1 min-w-0">
<h4 class="font-label-md text-label-md font-bold text-on-surface truncate">Telur Ayam Kampung Asli &amp; Omega-3</h4>
<p class="font-body-sm text-body-sm text-on-surface-variant">2 Mika (Isi 20 Butir)</p>
<div class="flex items-center justify-between mt-1">
<span class="font-label-sm text-label-sm text-tertiary">2x @ Rp 38.000</span>
<span class="font-label-lg text-label-lg font-bold text-on-surface">Rp 76.000</span>
</div>
</div>
</div>
<!-- Item 3: Telur Bebek Segar -->
<div class="flex items-start gap-3">
<img class="w-14 h-14 rounded-lg object-cover bg-surface-container-low shrink-0" data-alt="Telur bebek tambak segar berwarna biru kehijauan bersih tersusun rapi di atas tatakan kayu alami pasar tradisional Tanggamus Lampung" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDFPIPu2jsJnmOQCU3xJKwejNuEvWdUEMacE173kiDEyADNkV7oxIgX0gm-E3DJMjGbWdUhzbbcsk8LEaIes-rPtzXCQorKX_3JoWVcUNyEd94cnvbzZtTF5D21z-HF9KQHJkC4HK7kAnAD5ymgpjIJkBy1mf4cGZ1ozgxQUnnrL0UI3XbMuovddDDF--cW8yPP3KZB8O_KN7MSkWMJNM0D-_cpRfIbdgQdci9Z54I"/>
<div class="flex-1 min-w-0">
<h4 class="font-label-md text-label-md font-bold text-on-surface truncate">Telur Bebek Tambak Segar</h4>
<p class="font-body-sm text-body-sm text-on-surface-variant">1 Tray (Isi 10 Butir Siap Asin/Rebus)</p>
<div class="flex items-center justify-between mt-1">
<span class="font-label-sm text-label-sm text-tertiary">1x @ Rp 32.000</span>
<span class="font-label-lg text-label-lg font-bold text-on-surface">Rp 32.000</span>
</div>
</div>
</div>
</div>
<!-- Rincian Biaya -->
<div class="pt-3 space-y-2 bg-gradient-to-r from-transparent via-surface-container to-transparent bg-[length:100%_1px] bg-top bg-no-repeat">
<div class="flex items-center justify-between font-body-sm text-body-sm">
<span class="text-on-surface-variant">Subtotal Produk (3 Macam)</span>
<span class="text-on-surface font-semibold">Rp 212.000</span>
</div>
<div class="flex items-center justify-between font-body-sm text-body-sm">
<span class="text-on-surface-variant">Diskon Pelanggan Setia Tanggamus</span>
<span class="text-secondary font-bold">-Rp 6.000</span>
</div>
<div class="flex items-center justify-between font-body-sm text-body-sm">
<div class="flex items-center gap-1">
<span class="text-on-surface-variant">Ongkir Kurir Gisting</span>
<span class="material-symbols-outlined text-secondary text-sm" title="Gratis Pengantaran Wilayah Gisting">info</span>
</div>
<span class="text-secondary font-bold">GRATIS (Rp 0)</span>
</div>
<div class="flex items-center justify-between font-body-sm text-body-sm">
<span class="text-on-surface-variant">Kode Unik Verifikasi Kasir</span>
<span class="text-primary font-bold">+Rp 188</span>
</div>
<div class="pt-3 pb-1 flex items-baseline justify-between bg-gradient-to-r from-transparent via-surface-container to-transparent bg-[length:100%_1px] bg-top bg-no-repeat">
<div>
<p class="font-label-md text-label-md text-on-surface font-bold">Total Pembayaran</p>
<p class="font-label-sm text-label-sm text-on-surface-variant">Sudah termasuk paking krat aman</p>
</div>
<div class="text-right">
<p class="font-price-display text-price-display text-primary font-extrabold leading-none">Rp 206.188</p>
<span class="font-label-sm text-label-sm text-secondary font-semibold">Hemat Rp 6.000</span>
</div>
</div>
</div>
<!-- Tombol CTA Pesan -->
<button class="w-full py-3.5 px-4 rounded-xl bg-primary-container hover:bg-primary-fixed-dim text-on-primary-container font-headline-sm text-headline-sm font-extrabold shadow-md transition-all flex items-center justify-center gap-2 group" id="btn-submit-checkout" type="button">
<span class="material-symbols-outlined text-xl group-hover:scale-110 transition-transform">lock</span>
<span>Buat Pesanan Sekarang</span>
</button>
<!-- Safe Guarantees Badges -->
<div class="space-y-2 pt-2">
<div class="flex items-center gap-2 font-label-sm text-label-sm text-secondary">
<span class="material-symbols-outlined text-base">verified</span>
<span>Garansi 100% Telur Utuh &amp; Timbangan Akurat</span>
</div>
<div class="flex items-center gap-2 font-label-sm text-label-sm text-on-surface-variant">
<span class="material-symbols-outlined text-base text-primary">moped</span>
<span>Pengantaran Khusus Kurir Motor Bang Zul Bersekat</span>
</div>
</div>
<!-- CS Hubungi Langsung -->
<div class="p-3 rounded-lg bg-surface-container-low flex items-center justify-between text-body-sm text-body-sm">
<div class="flex items-center gap-2 text-on-surface">
<span class="material-symbols-outlined text-secondary text-lg">call</span>
<span>Butuh Bantuan Pesanan?</span>
</div>
<a class="font-label-sm text-label-sm text-primary font-bold hover:underline" href="https://wa.me/6281278900000" target="_blank">
              WA Bang Zul
            </a>
</div>
</div>
<!-- Edukasi / Keunggulan Belanja Lokal -->
<div class="p-4 rounded-xl bg-surface-container-low text-on-surface-variant space-y-2">
<p class="font-label-md text-label-md text-on-surface font-bold flex items-center gap-1.5">
<span class="material-symbols-outlined text-primary text-base">egg</span>
            Tips Cek Kesegaran Telur Saat Tiba
          </p>
<ul class="font-body-sm text-body-sm list-disc pl-4 space-y-1 text-on-surface-variant">
<li>Cangkang telur kesat dan tidak mengkilap berminyak.</li>
<li>Saat digoyang lembut di samping telinga, tidak bersuara kopyor.</li>
<li>Kuning telur saat dipecahkan berbentuk bulat kokoh &amp; kental.</li>
</ul>
</div>
</div>
</div>
</div>
<!-- Notification Toast Container -->
<div class="fixed bottom-6 right-6 z-50 transform translate-y-24 opacity-0 transition-all duration-300 pointer-events-none" id="toast">
<div class="bg-inverse-surface text-inverse-on-surface px-5 py-3 rounded-xl shadow-xl flex items-center gap-3">
<span class="material-symbols-outlined text-secondary-fixed text-xl" id="toast-icon">check_circle</span>
<span class="font-label-md text-label-md font-medium" id="toast-msg">Teks notifikasi</span>
</div>
</div>
</div>
<script>
  // Toast Helper
  function showToast(message, icon = 'check_circle') {
    const toast = document.getElementById('toast');
    const toastMsg = document.getElementById('toast-msg');
    const toastIcon = document.getElementById('toast-icon');
    if (!toast || !toastMsg) return;

    toastMsg.textContent = message;
    toastIcon.textContent = icon;
    toast.classList.remove('translate-y-24', 'opacity-0', 'pointer-events-none');
    toast.classList.add('translate-y-0', 'opacity-100');

    setTimeout(() => {
      toast.classList.add('translate-y-24', 'opacity-0', 'pointer-events-none');
      toast.classList.remove('translate-y-0', 'opacity-100');
    }, 3200);
  }

  // Toggle Alamat Form
  const btnToggleAddress = document.getElementById('btn-toggle-address');
  const addressForm = document.getElementById('address-form');
  const btnCancelAddress = document.getElementById('btn-cancel-address');
  const btnSaveAddress = document.getElementById('btn-save-address');

  if (btnToggleAddress && addressForm) {
    btnToggleAddress.addEventListener('click', () => {
      addressForm.classList.toggle('hidden');
    });
  }

  if (btnCancelAddress && addressForm) {
    btnCancelAddress.addEventListener('click', () => {
      addressForm.classList.add('hidden');
    });
  }

  if (btnSaveAddress && addressForm) {
    btnSaveAddress.addEventListener('click', () => {
      addressForm.classList.add('hidden');
      showToast('Alamat penerima berhasil diperbarui!');
    });
  }

  // Copy buttons
  const btnCopyRek = document.getElementById('btn-copy-rek');
  if (btnCopyRek) {
    btnCopyRek.addEventListener('click', () => {
      navigator.clipboard.writeText('014201002938531');
      showToast('Nomor Rekening BRI Berhasil Disalin!');
    });
  }

  const btnCopyNominal = document.getElementById('btn-copy-nominal');
  if (btnCopyNominal) {
    btnCopyNominal.addEventListener('click', () => {
      navigator.clipboard.writeText('206188');
      showToast('Nomor Nominal Rp 206.188 Berhasil Disalin!');
    });
  }

  // Slot selector highlight
  const slotCards = document.querySelectorAll('.delivery-slot');
  slotCards.forEach(card => {
    card.addEventListener('click', () => {
      slotCards.forEach(c => {
        c.classList.remove('ring-2', 'ring-primary-container', 'shadow-sm');
        c.classList.add('hover:bg-surface-container');
      });
      card.classList.add('ring-2', 'ring-primary-container', 'shadow-sm');
      card.classList.remove('hover:bg-surface-container');
    });
  });

  // Payment Method dynamic selector & visibility of bank instruction box
  const paymentCards = document.querySelectorAll('.payment-card');
  const bankInstructionBox = document.getElementById('bank-instruction-box');

  paymentCards.forEach(card => {
    card.addEventListener('click', () => {
      paymentCards.forEach(c => {
        c.classList.remove('ring-2', 'ring-primary-container');
      });
      card.classList.add('ring-2', 'ring-primary-container');

      const radio = card.querySelector('input[type="radio"]');
      if (radio && bankInstructionBox) {
        if (radio.value === 'bank_transfer') {
          bankInstructionBox.classList.remove('hidden');
        } else {
          bankInstructionBox.classList.add('hidden');
        }
      }
    });
  });

  // File Upload Struk Simulator
  const dropArea = document.getElementById('drop-area');
  const fileInput = document.getElementById('file-bukti');
  const uploadPlaceholder = document.getElementById('upload-placeholder-content');
  const uploadPreview = document.getElementById('upload-preview-content');
  const fileNameDisplay = document.getElementById('file-name');
  const btnRemoveFile = document.getElementById('btn-remove-file');

  if (dropArea && fileInput) {
    dropArea.addEventListener('click', (e) => {
      if (e.target !== btnRemoveFile && !btnRemoveFile.contains(e.target)) {
        fileInput.click();
      }
    });

    fileInput.addEventListener('change', (e) => {
      if (e.target.files && e.target.files[0]) {
        const file = e.target.files[0];
        fileNameDisplay.textContent = file.name;
        uploadPlaceholder.classList.add('hidden');
        uploadPreview.classList.remove('hidden');
        showToast('Bukti transfer terpilih!');
      }
    });
  }

  if (btnRemoveFile) {
    btnRemoveFile.addEventListener('click', (e) => {
      e.stopPropagation();
      fileInput.value = '';
      uploadPlaceholder.classList.remove('hidden');
      uploadPreview.classList.add('hidden');
      showToast('File bukti dihapus, silakan pilih ulang.', 'info');
    });
  }

  // Submit Checkout Action
  const btnSubmitCheckout = document.getElementById('btn-submit-checkout');
  if (btnSubmitCheckout) {
    btnSubmitCheckout.addEventListener('click', () => {
      showToast('Pesanan Berhasil Dibuat! Notifikasi WA sedang dikirim ke 0812-7890-8821', 'verified');
    });
  }
</script></main><footer class="w-full bg-surface-container-low mt-16 pt-12 pb-8 text-on-surface-variant"><div class="max-w-7xl mx-auto px-4 lg:px-8 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8"><div class="space-y-3"><div class="flex items-center gap-2"><img alt="Logo Bang Zul Egg Market" class="h-7 w-auto object-contain" src="https://lh3.googleusercontent.com/aida/ALJJyrAvuhgJbL1OqXYnorOpflEwk9ch2RB3i3nIpJf2khBHtFUraZYLjA49xnoYr5_XpY1inx_yvUKDG-f5ULodcAC4hoBl9QYWujU07wAAJsvNI88PefRZRNH2SgRzcvtvfP9LlMDgvobQRRrHxWwLlWY8MQoR1CS4kennwXqXJqn5PR3R5zkf-p4q0eleDblVHlCAtE__Wj8FbqU6db9zlBw02jnLdLpow_xGCN8RF4es"/><span class="font-headline-sm text-headline-sm text-primary">UD. Bang Zul Egg Market</span></div><p class="font-body-sm text-body-sm">Pusat distribusi telur segar langsung dari peternak binaan lokal Tanggamus. Menjaga kualitas kesegaran cangkang utuh dan timbangan presisi terpercaya.</p><div class="flex items-center gap-2 text-secondary font-label-sm text-label-sm"><span class="material-symbols-outlined text-sm">verified</span><span>Garansi Ganti Telur Pecah 100% Langsung di Tempat</span></div></div><div class="space-y-2"><h3 class="font-headline-sm text-headline-sm text-on-surface">Jam Operasional &amp; Panen</h3><p class="font-body-sm text-body-sm">Pengambilan Telur Kandang: 06.00 - 10.00 WIB</p><p class="font-body-sm text-body-sm">Jadwal Pengiriman Kurir: 08.00 - 18.00 WIB</p><p class="font-body-sm text-body-sm text-secondary font-semibold">Setiap Hari (Senin - Minggu Tetap Buka)</p><p class="font-label-sm text-label-sm text-on-surface-variant pt-1">Wilayah Gisting, Talang Padang, Wonosobo, Kota Agung &amp; Sekitarnya.</p></div><div class="space-y-2"><h3 class="font-headline-sm text-headline-sm text-on-surface">Metode Pembayaran</h3><div class="space-y-1 font-body-sm text-body-sm"><p class="flex items-center gap-1.5"><span class="material-symbols-outlined text-primary text-sm">qr_code_scanner</span>QRIS Seluruh Bank &amp; E-Wallet</p><p class="flex items-center gap-1.5"><span class="material-symbols-outlined text-primary text-sm">account_balance</span>Transfer Bank Lampung / BRI / BCA</p><p class="flex items-center gap-1.5"><span class="material-symbols-outlined text-primary text-sm">payments</span>COD (Bayar Tunai di Tempat saat Timbang)</p></div></div><div class="space-y-2"><h3 class="font-headline-sm text-headline-sm text-on-surface">Komitmen Peternak Lokal</h3><p class="font-body-sm text-body-sm">Mendukung keberlanjutan usaha peternak unggas pedesaan di Kabupaten Tanggamus, Lampung dengan harga adil, timbangan transparan, dan pakan alami bermutu.</p><div class="pt-2"><span class="inline-block px-3 py-1 bg-secondary-container text-on-secondary-container rounded-full font-label-sm text-label-sm">Asli Tanggamus, Segar Bergaransi</span></div></div></div><div class="max-w-7xl mx-auto px-4 lg:px-8 mt-10 pt-4 flex flex-col sm:flex-row items-center justify-between gap-2 font-label-sm text-label-sm text-on-surface-variant"><p>© 2024 UD. Bang Zul Egg Market Tanggamus Lampung. Hak Cipta Dilindungi.</p><p>Dibuat untuk ekosistem niaga agrikultur Kabupaten Tanggamus</p></div></footer></body></html>

<!-- Keranjang Belanja Pembeli -->
<!DOCTYPE html>

<html lang="id"><head><meta charset="utf-8"/><meta content="width=device-width, initial-scale=1.0" name="viewport"/><meta content="web_standard" name="shell-type"/><link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" rel="stylesheet"/><link href="https://fonts.googleapis.com" rel="preconnect"/><link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/><link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&amp;family=Plus+Jakarta+Sans:wght@700;800&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/><style>@layer base{html,body{margin:0;padding:0;}body{overscroll-behavior:none;}main>:first-child{margin-top:0!important;}main>:last-child{margin-bottom:0!important;}}::-webkit-scrollbar{display:none;}</style><script src="https://cdn.tailwindcss.com"></script><script id="tailwind-config">tailwind.config={darkMode:"class",theme:{extend:{colors:{"secondary-container":"#a0f399","on-tertiary-fixed-variant":"#3e4a41","on-background":"#1b1c1c","on-error":"#ffffff","on-primary":"#ffffff","primary":"#835500","surface-container-highest":"#e4e2e1","on-secondary-fixed-variant":"#005312","surface-container-low":"#f6f3f2","background":"#fcf9f8","surface":"#fcf9f8","on-tertiary-fixed":"#131e17","on-secondary-container":"#217128","outline-variant":"#d7c3ae","inverse-surface":"#303030","surface-container":"#f0eded","on-secondary-fixed":"#002204","surface-bright":"#fcf9f8","primary-fixed":"#ffddb4","surface-dim":"#dcd9d9","surface-container-lowest":"#ffffff","tertiary":"#556158","on-primary-fixed":"#291800","secondary-fixed":"#a3f69c","tertiary-container":"#acb9ae","on-primary-container":"#644000","on-primary-fixed-variant":"#633f00","on-tertiary":"#ffffff","surface-variant":"#e4e2e1","on-tertiary-container":"#3e4a41","on-secondary":"#ffffff","inverse-on-surface":"#f3f0f0","surface-tint":"#835500","primary-fixed-dim":"#ffb955","on-surface-variant":"#524534","on-error-container":"#93000a","surface-container-high":"#eae7e7","error":"#ba1a1a","primary-container":"#f5a623","inverse-primary":"#ffb955","outline":"#857462","tertiary-fixed":"#d9e6da","tertiary-fixed-dim":"#bdcabe","error-container":"#ffdad6","secondary":"#1b6d24","on-surface":"#1b1c1c","secondary-fixed-dim":"#88d982"},borderRadius:{"DEFAULT":"0.25rem","lg":"0.5rem","xl":"0.75rem","full":"9999px"},spacing:{"space-md":"1rem","gutter":"1rem","space-lg":"1.5rem","space-xl":"2rem","gutter-desktop":"1.5rem","space-xs":"0.25rem","space-sm":"0.5rem","margin":"1rem","margin-desktop":"2.5rem"},fontFamily:{"body-md":["Inter"],"label-sm":["Inter"],"price-display":["Plus Jakarta Sans"],"stock-counter":["Inter"],"headline-md":["Plus Jakarta Sans"],"body-lg":["Inter"],"label-md":["Inter"],"headline-sm":["Plus Jakarta Sans"],"display-lg":["Plus Jakarta Sans"],"label-lg":["Inter"],"headline-lg-mobile":["Plus Jakarta Sans"],"headline-lg":["Plus Jakarta Sans"],"body-sm":["Inter"],"display-lg-mobile":["Plus Jakarta Sans"]},fontSize:{"body-md":["14px",{"lineHeight":"22px","fontWeight":"400"}],"label-sm":["11px",{"lineHeight":"14px","letterSpacing":"0.02em","fontWeight":"600"}],"price-display":["22px",{"lineHeight":"28px","letterSpacing":"-0.02em","fontWeight":"800"}],"stock-counter":["18px",{"lineHeight":"24px","letterSpacing":"0.01em","fontWeight":"700"}],"headline-md":["20px",{"lineHeight":"28px","fontWeight":"700"}],"body-lg":["16px",{"lineHeight":"26px","fontWeight":"400"}],"label-md":["12px",{"lineHeight":"16px","fontWeight":"600"}],"headline-sm":["16px",{"lineHeight":"24px","fontWeight":"700"}],"display-lg":["40px",{"lineHeight":"48px","letterSpacing":"-0.02em","fontWeight":"800"}],"label-lg":["14px",{"lineHeight":"20px","fontWeight":"600"}],"headline-lg-mobile":["22px",{"lineHeight":"30px","letterSpacing":"0em","fontWeight":"700"}],"headline-lg":["28px",{"lineHeight":"36px","letterSpacing":"-0.01em","fontWeight":"700"}],"body-sm":["12px",{"lineHeight":"18px","fontWeight":"400"}],"display-lg-mobile":["30px",{"lineHeight":"38px","letterSpacing":"-0.01em","fontWeight":"800"}]}}}}</script></head><body class="bg-surface font-body-md text-body-md text-on-surface antialiased"><header class="fixed top-0 left-0 w-full z-50 bg-surface/95 backdrop-blur-md shadow-[0_4px_20px_-2px_rgba(245,166,35,0.12)]"><div class="bg-secondary text-on-secondary px-4 py-1.5"><div class="max-w-7xl mx-auto flex flex-col md:flex-row items-center justify-between gap-1 text-label-sm font-label-sm"><div class="flex items-center gap-2 text-center md:text-left"><span class="material-symbols-outlined text-secondary-fixed text-sm">local_shipping</span><span>Pengiriman Segar Hari Ini ke Wilayah Kota Agung, Gisting, Talang Padang, Wonosobo, Pringsewu sekitarnya | <strong class="text-secondary-fixed">Garansi Telur Pecah Diganti 100%</strong></span></div><a class="flex items-center gap-1.5 hover:text-secondary-fixed transition-colors whitespace-nowrap" href="https://wa.me/6281278900000"><span class="material-symbols-outlined text-sm">chat</span><span>WhatsApp CS Hubungi Bang Zul: 0812-7890-XXXX</span></a></div></div><div class="max-w-7xl mx-auto px-4 lg:px-8 py-3 flex items-center justify-between gap-4"><a class="flex items-center gap-3 shrink-0" data-path="katalog-belanja-pembeli" href="#"><img alt="Logo Bang Zul Egg Market" class="h-8 w-auto object-contain" src="https://lh3.googleusercontent.com/aida/ALJJyrAvuhgJbL1OqXYnorOpflEwk9ch2RB3i3nIpJf2khBHtFUraZYLjA49xnoYr5_XpY1inx_yvUKDG-f5ULodcAC4hoBl9QYWujU07wAAJsvNI88PefRZRNH2SgRzcvtvfP9LlMDgvobQRRrHxWwLlWY8MQoR1CS4kennwXqXJqn5PR3R5zkf-p4q0eleDblVHlCAtE__Wj8FbqU6db9zlBw02jnLdLpow_xGCN8RF4es"/><div class="flex flex-col"><span class="font-headline-md text-headline-md text-primary tracking-tight leading-none">Bang Zul</span><span class="font-label-sm text-label-sm text-secondary font-bold tracking-wider uppercase leading-none mt-0.5">Egg Market Tanggamus</span></div></a><div class="hidden lg:flex items-center gap-1.5 px-3 py-1.5 rounded-full bg-surface-container-low text-on-surface-variant font-label-sm text-label-sm shrink-0"><span class="material-symbols-outlined text-primary text-base">location_on</span><span class="max-w-[210px] truncate">Kab. Tanggamus (Gisting, Kota Agung &amp; Sekitarnya)</span></div><div class="hidden md:flex flex-1 max-w-md mx-2"><div class="relative w-full flex items-center"><span class="material-symbols-outlined absolute left-3 text-outline text-lg">search</span><input class="w-full pl-10 pr-4 py-2 rounded-full bg-surface-container-lowest text-body-sm font-body-sm text-on-surface placeholder:text-outline focus:outline-none focus:ring-2 focus:ring-primary-container shadow-[0_1px_4px_rgba(0,0,0,0.04)]" placeholder="Cari telur ayam ras, telur omega, telur bebek, puyuh..." type="text"/></div></div><div class="flex items-center gap-2 md:gap-3 shrink-0"><a class="flex items-center gap-2 px-3 py-1.5 rounded-full bg-primary-container text-on-primary-container hover:bg-primary-fixed-dim transition-colors shadow-sm" data-path="keranjang-belanja-pembeli" href="#"><span class="material-symbols-outlined text-lg">shopping_basket</span><span class="hidden sm:inline font-label-sm text-label-sm">Keranjang (3 Item)</span></a><div class="hidden sm:flex items-center gap-1.5 pl-1"><a class="px-3 py-1.5 rounded-full bg-surface-container text-on-surface hover:bg-surface-container-high transition-colors font-label-sm text-label-sm" data-path="masuk-akun-pembeli" href="#">Masuk</a><a class="px-3 py-1.5 rounded-full bg-primary text-on-primary hover:bg-on-primary-container transition-colors font-label-sm text-label-sm" data-path="daftar-akun-pembeli" href="#">Daftar</a></div><a class="flex items-center gap-1.5 p-1.5 rounded-full hover:bg-surface-container-high text-on-surface-variant" data-path="profil-akun-pembeli" href="#"><img alt="Foto Akun Pembeli" class="w-8 h-8 rounded-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBu4cCay1o-kcZkrepBjdwRhNkTeb5NSNF4V20H1AoEXr4ahIrRP9SktX37TUve3u7us_GHnlm1279EoAyYcFxqZTZV4CIOdstOTCqIMcitiPTCwpWm4m2okjdh9z8S2I2n0sK1hb3y3ohWU84Tu6ZWNoxKL7D1NVLhMsBA3C6eHNQmukclnmKpMzHXssx-xtkh1wF2y2OFEDgXUgTPjjAfLabaOsUrz91MId6by4k"/></a></div></div><div class="bg-surface-container-lowest shadow-[0_1px_4px_rgba(0,0,0,0.02)] overflow-x-auto"><div class="max-w-7xl mx-auto px-4 lg:px-8"><nav class="flex items-center gap-6 whitespace-nowrap py-2.5 text-label-sm font-label-sm" data-active-classes="text-primary font-bold border-b-2 border-primary"><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="katalog-belanja-pembeli" href="#">Katalog Telur Segar</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="detail-produk-telur" href="#">Detail Produk Telur</a><a aria-current="page" class="transition-colors pb-1 text-primary font-bold border-b-2 border-primary" data-path="keranjang-belanja-pembeli" href="#">Keranjang Belanja</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="checkout-pembayaran-pembeli" href="#">Checkout Pembayaran</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="profil-akun-pembeli" href="#">Profil Saya</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="masuk-akun-pembeli" href="#">Masuk Akun</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="daftar-akun-pembeli" href="#">Daftar Akun Baru</a></nav></div></div></header><main class="w-full pt-36 bg-surface min-h-screen"><div class="flex flex-col w-full">
<div class="max-w-7xl mx-auto w-full px-4 lg:px-8 py-6 space-y-8">
<!-- Top Progress / Free Shipping Banner -->
<div class="bg-surface-container-lowest rounded-xl p-5 shadow-sm space-y-3">
<div class="flex flex-col sm:flex-row sm:items-center justify-between gap-3">
<div class="flex items-center gap-3">
<div class="w-10 h-10 rounded-full bg-secondary-container text-on-secondary-container flex items-center justify-center shrink-0">
<span class="material-symbols-outlined text-xl">local_shipping</span>
</div>
<div>
<h1 class="font-headline-md text-headline-md text-on-surface">Keranjang Belanja Anda</h1>
<p class="font-label-sm text-label-sm text-secondary font-bold flex items-center gap-1.5 mt-0.5">
<span class="inline-block w-2 h-2 rounded-full bg-secondary"></span>
              Selamat! Anda berhak mendapatkan GRATIS Ongkos Kirim ke wilayah Tanggamus (Minimal belanja 2 karpet/tray terpenuhi)
            </p>
</div>
</div>
<div class="inline-flex items-center gap-2 self-start sm:self-auto px-3.5 py-1.5 rounded-full bg-surface-container text-on-surface font-label-md text-label-md">
<span class="material-symbols-outlined text-primary text-base">shopping_cart</span>
<span>3 Jenis Telur (Total 5 Item)</span>
</div>
</div>
<!-- Shipping Progress Indicator -->
<div class="space-y-1.5 pt-1">
<div class="w-full bg-surface-container h-2 rounded-full overflow-hidden">
<div class="bg-secondary h-full rounded-full transition-all duration-500" style="width: 100%;"></div>
</div>
<div class="flex justify-between items-center text-label-sm font-label-sm text-on-surface-variant">
<span>Target Gratis Ongkir Gisting &amp; Sekitarnya</span>
<span class="text-secondary font-bold">100% Tercapai (Hemat Ongkir Rp 15.000)</span>
</div>
</div>
</div>
<!-- Main Two Column Layout -->
<div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-start">
<!-- Sisi Kiri: List Item Keranjang -->
<div class="lg:col-span-8 space-y-6">
<!-- Cart Controls Bar -->
<div class="bg-surface-container-lowest rounded-xl px-5 py-3.5 shadow-sm flex items-center justify-between">
<label class="flex items-center gap-3 cursor-pointer select-none">
<input checked="" class="w-5 h-5 rounded text-primary focus:ring-primary-container cursor-pointer accent-primary" id="selectAllCheckbox" type="checkbox"/>
<span class="font-headline-sm text-headline-sm text-on-surface">Pilih Semua Item (3)</span>
</label>
<button class="flex items-center gap-1 text-on-surface-variant hover:text-error transition-colors font-label-md text-label-md" id="bulkDeleteBtn">
<span class="material-symbols-outlined text-lg">delete_sweep</span>
<span class="hidden sm:inline">Hapus yang Dipilih</span>
</button>
</div>
<!-- Items Container -->
<div class="space-y-4" id="cartItemList">
<!-- Item 1: Telur Ayam Ras Super Karpet -->
<div class="cart-item bg-surface-container-lowest rounded-xl p-5 shadow-sm space-y-4 transition-all" data-id="1" data-price="52000">
<div class="flex flex-col sm:flex-row gap-4">
<div class="flex items-start gap-3">
<input checked="" class="item-checkbox mt-2 w-5 h-5 rounded text-primary focus:ring-primary-container cursor-pointer accent-primary" type="checkbox"/>
<div class="relative w-24 h-24 sm:w-28 sm:h-28 rounded-lg overflow-hidden shrink-0 bg-surface-container">
<img class="w-full h-full object-cover" data-alt="Tumpukan karpet tray karton telur ayam ras segar cokelat kemerahan bertingkat rapi di lapak pasar tradisional Tanggamus Lampung dengan pencahayaan pagi hangat natural" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCo1UtX36kYxlPDDMxWKlgLnYvSbwVs_AX7w2Knn2v62tGskdEiSA8WETXMB9Z2VfbX0yL8f4W9MGSpSsR-zu2uEY5brl_axPN5K39IGoiCt7TFW7MrsIzj_ImGFN1dmILNEKK3rVUfjGwRzg6ePD1yujU7qQ7dqBgAm8Z_47qy5TP3IGhWGnluK60RvizSE3F_FY2iftGmt0XlrZwS187wn3KNp3CxjJNAKMXGE9w"/>
<span class="absolute bottom-1 right-1 px-1.5 py-0.5 rounded bg-on-surface/80 text-surface font-label-sm text-label-sm">30 Butir</span>
</div>
</div>
<div class="flex-1 min-w-0 flex flex-col justify-between space-y-2">
<div class="flex items-start justify-between gap-2">
<div>
<span class="inline-block px-2 py-0.5 mb-1 rounded bg-secondary-container text-on-secondary-container font-label-sm text-label-sm font-semibold">Ternak Petelur Gisting</span>
<h2 class="font-headline-sm text-headline-sm text-on-surface truncate">Telur Ayam Ras Super Karpet (30 Butir)</h2>
<p class="font-body-sm text-body-sm text-on-surface-variant">Kemasan Tray Karton Tebal (Kapasitas ±1.9 - 2.0 Kg)</p>
</div>
<div class="flex items-center gap-1 shrink-0">
<button class="p-1.5 rounded-full hover:bg-surface-container text-outline hover:text-primary transition-colors" title="Simpan ke Wishlist">
<span class="material-symbols-outlined text-lg">bookmark_add</span>
</button>
<button class="delete-btn p-1.5 rounded-full hover:bg-error-container text-outline hover:text-error transition-colors" title="Hapus Produk">
<span class="material-symbols-outlined text-lg">delete_outline</span>
</button>
</div>
</div>
<div class="flex flex-wrap items-center justify-between gap-3 pt-2">
<div>
<span class="font-label-sm text-label-sm text-on-surface-variant block">Harga Satuan</span>
<span class="font-headline-sm text-headline-sm text-on-surface">Rp 52.000</span>
</div>
<!-- Stepper & Subtotal -->
<div class="flex items-center gap-4">
<div class="flex items-center bg-surface-container-low rounded-lg p-1">
<button aria-label="Kurang kuantitas" class="step-btn-minus w-8 h-8 flex items-center justify-center rounded-md bg-surface-container-lowest text-on-surface hover:bg-surface-container transition-colors disabled:opacity-40">
<span class="material-symbols-outlined text-base">remove</span>
</button>
<span class="step-quantity font-headline-sm text-headline-sm px-4 min-w-[40px] text-center text-on-surface">2</span>
<button aria-label="Tambah kuantitas" class="step-btn-plus w-8 h-8 flex items-center justify-center rounded-md bg-surface-container-lowest text-on-surface hover:bg-surface-container transition-colors">
<span class="material-symbols-outlined text-base">add</span>
</button>
</div>
<div class="text-right min-w-[100px]">
<span class="font-label-sm text-label-sm text-on-surface-variant block">Subtotal</span>
<span class="item-subtotal font-price-display text-price-display text-primary leading-tight">Rp 104.000</span>
</div>
</div>
</div>
</div>
</div>
<!-- Catatan Pesanan Khusus -->
<div class="bg-surface-container-low rounded-lg p-3 flex flex-col sm:flex-row items-start sm:items-center justify-between gap-2">
<div class="flex items-center gap-2 text-on-surface-variant font-body-sm text-body-sm w-full">
<span class="material-symbols-outlined text-primary text-sm shrink-0">edit_note</span>
<span class="text-outline font-label-sm text-label-sm shrink-0">Catatan Toko:</span>
<span class="italic text-on-surface font-body-sm text-body-sm truncate">“Tolong pilih yang butirnya besar-besar rata”</span>
</div>
<button class="text-primary hover:text-on-primary-container font-label-sm text-label-sm font-bold shrink-0 self-end sm:self-auto">Ubah Catatan</button>
</div>
</div>
<!-- Item 2: Telur Ayam Kampung Asli & Omega-3 -->
<div class="cart-item bg-surface-container-lowest rounded-xl p-5 shadow-sm space-y-4 transition-all" data-id="2" data-price="38000">
<div class="flex flex-col sm:flex-row gap-4">
<div class="flex items-start gap-3">
<input checked="" class="item-checkbox mt-2 w-5 h-5 rounded text-primary focus:ring-primary-container cursor-pointer accent-primary" type="checkbox"/>
<div class="relative w-24 h-24 sm:w-28 sm:h-28 rounded-lg overflow-hidden shrink-0 bg-surface-container">
<img class="w-full h-full object-cover" data-alt="Telur ayam kampung organik bercangkang bintik alami di dalam mangkuk anyaman bambu pedesaan dengan latar jerami dan sinar matahari pagi pedesaan asri" src="https://lh3.googleusercontent.com/aida-public/AB6AXuA-s2oVziXu2dZunsjpORn8IkLTqLun9ibYCBbmoSpiRaOKDRwS6gSAbZRaSpgo86wES-Xjj94sE7pZ9ANxpjz57qKgDpchvYqWPzFtVYBt-uabpMcXjmnjY39IIxVsFsuphFYS5_-alQadlw8Zi321UXkpsNS_aD-2U-7elrleoemWuz_tptlATRM8hooWSYC4yZBh6hRRld8NdM0A9ovlwkl1xBqGNPYZxiZZ3qo"/>
<span class="absolute bottom-1 right-1 px-1.5 py-0.5 rounded bg-on-surface/80 text-surface font-label-sm text-label-sm">10 Butir</span>
</div>
</div>
<div class="flex-1 min-w-0 flex flex-col justify-between space-y-2">
<div class="flex items-start justify-between gap-2">
<div>
<span class="inline-block px-2 py-0.5 mb-1 rounded bg-primary-fixed text-on-primary-fixed font-label-sm text-label-sm font-semibold">Organik &amp; Segar</span>
<h2 class="font-headline-sm text-headline-sm text-on-surface truncate">Telur Ayam Kampung Asli &amp; Omega-3</h2>
<p class="font-body-sm text-body-sm text-on-surface-variant">Mika Food-grade Isi 10 Butir (Kuning Telur Jingga Pekat)</p>
</div>
<div class="flex items-center gap-1 shrink-0">
<button class="p-1.5 rounded-full hover:bg-surface-container text-outline hover:text-primary transition-colors" title="Simpan ke Wishlist">
<span class="material-symbols-outlined text-lg">bookmark_add</span>
</button>
<button class="delete-btn p-1.5 rounded-full hover:bg-error-container text-outline hover:text-error transition-colors" title="Hapus Produk">
<span class="material-symbols-outlined text-lg">delete_outline</span>
</button>
</div>
</div>
<div class="flex flex-wrap items-center justify-between gap-3 pt-2">
<div>
<span class="font-label-sm text-label-sm text-on-surface-variant block">Harga Satuan</span>
<span class="font-headline-sm text-headline-sm text-on-surface">Rp 38.000</span>
</div>
<!-- Stepper & Subtotal -->
<div class="flex items-center gap-4">
<div class="flex items-center bg-surface-container-low rounded-lg p-1">
<button aria-label="Kurang kuantitas" class="step-btn-minus w-8 h-8 flex items-center justify-center rounded-md bg-surface-container-lowest text-on-surface hover:bg-surface-container transition-colors disabled:opacity-40">
<span class="material-symbols-outlined text-base">remove</span>
</button>
<span class="step-quantity font-headline-sm text-headline-sm px-4 min-w-[40px] text-center text-on-surface">2</span>
<button aria-label="Tambah kuantitas" class="step-btn-plus w-8 h-8 flex items-center justify-center rounded-md bg-surface-container-lowest text-on-surface hover:bg-surface-container transition-colors">
<span class="material-symbols-outlined text-base">add</span>
</button>
</div>
<div class="text-right min-w-[100px]">
<span class="font-label-sm text-label-sm text-on-surface-variant block">Subtotal</span>
<span class="item-subtotal font-price-display text-price-display text-primary leading-tight">Rp 76.000</span>
</div>
</div>
</div>
</div>
</div>
<!-- Tambah Catatan Button (Empty State) -->
<div class="flex items-center gap-2 pt-1 text-on-surface-variant font-label-sm text-label-sm">
<span class="material-symbols-outlined text-base">note_add</span>
<button class="hover:text-primary transition-colors">+ Tambahkan catatan khusus untuk varian ini</button>
</div>
</div>
<!-- Item 3: Telur Bebek Tambak Segar -->
<div class="cart-item bg-surface-container-lowest rounded-xl p-5 shadow-sm space-y-4 transition-all" data-id="3" data-price="32000">
<div class="flex flex-col sm:flex-row gap-4">
<div class="flex items-start gap-3">
<input checked="" class="item-checkbox mt-2 w-5 h-5 rounded text-primary focus:ring-primary-container cursor-pointer accent-primary" type="checkbox"/>
<div class="relative w-24 h-24 sm:w-28 sm:h-28 rounded-lg overflow-hidden shrink-0 bg-surface-container">
<img class="w-full h-full object-cover" data-alt="Telur bebek tambak cangkang hijau kebiruan segar tersusun dalam wadah peti kayu rustic berlatar pasar agrikultur tradisional Tanggamus" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDJoaYxDP1QKQT1hAwDSElMS_KJd_wOn0Dpi8cuwGCt_3yaptFT7ZBUgtZoQmaG5ezsppz1TvTC0YzkNfpG5irKKw2MXGUaBb5Ebwkke1_26KHAIEcgCiA5r1w8twoN1e67vOcDJCzs2C8cVq1g7ridSgBDJ1hmZfK7Sq0wq8UJZG4ko8azpvuGu8RbcG4kaJ75QKV7ZrhIsypYYO2W6yb54_cJChnNRDabspzuZE4"/>
<span class="absolute bottom-1 right-1 px-1.5 py-0.5 rounded bg-on-surface/80 text-surface font-label-sm text-label-sm">Pack 10</span>
</div>
</div>
<div class="flex-1 min-w-0 flex flex-col justify-between space-y-2">
<div class="flex items-start justify-between gap-2">
<div>
<span class="inline-block px-2 py-0.5 mb-1 rounded bg-tertiary-fixed text-on-tertiary-fixed font-label-sm text-label-sm font-semibold">Peternak Pesisir</span>
<h2 class="font-headline-sm text-headline-sm text-on-surface truncate">Telur Bebek Tambak Segar (Pesisir Kota Agung)</h2>
<p class="font-body-sm text-body-sm text-on-surface-variant">Pack 10 Butir (Cocok untuk Olahan Jamu / Telur Asin)</p>
</div>
<div class="flex items-center gap-1 shrink-0">
<button class="p-1.5 rounded-full hover:bg-surface-container text-outline hover:text-primary transition-colors" title="Simpan ke Wishlist">
<span class="material-symbols-outlined text-lg">bookmark_add</span>
</button>
<button class="delete-btn p-1.5 rounded-full hover:bg-error-container text-outline hover:text-error transition-colors" title="Hapus Produk">
<span class="material-symbols-outlined text-lg">delete_outline</span>
</button>
</div>
</div>
<div class="flex flex-wrap items-center justify-between gap-3 pt-2">
<div>
<span class="font-label-sm text-label-sm text-on-surface-variant block">Harga Satuan</span>
<span class="font-headline-sm text-headline-sm text-on-surface">Rp 32.000</span>
</div>
<!-- Stepper & Subtotal -->
<div class="flex items-center gap-4">
<div class="flex items-center bg-surface-container-low rounded-lg p-1">
<button aria-label="Kurang kuantitas" class="step-btn-minus w-8 h-8 flex items-center justify-center rounded-md bg-surface-container-lowest text-on-surface hover:bg-surface-container transition-colors disabled:opacity-40">
<span class="material-symbols-outlined text-base">remove</span>
</button>
<span class="step-quantity font-headline-sm text-headline-sm px-4 min-w-[40px] text-center text-on-surface">1</span>
<button aria-label="Tambah kuantitas" class="step-btn-plus w-8 h-8 flex items-center justify-center rounded-md bg-surface-container-lowest text-on-surface hover:bg-surface-container transition-colors">
<span class="material-symbols-outlined text-base">add</span>
</button>
</div>
<div class="text-right min-w-[100px]">
<span class="font-label-sm text-label-sm text-on-surface-variant block">Subtotal</span>
<span class="item-subtotal font-price-display text-price-display text-primary leading-tight">Rp 32.000</span>
</div>
</div>
</div>
</div>
</div>
<div class="flex items-center gap-2 pt-1 text-on-surface-variant font-label-sm text-label-sm">
<span class="material-symbols-outlined text-base">note_add</span>
<button class="hover:text-primary transition-colors">+ Tambahkan catatan khusus untuk varian ini</button>
</div>
</div>
</div>
<!-- Action Bar under Items -->
<div class="flex flex-col sm:flex-row items-center justify-between gap-4 pt-2">
<a class="flex items-center gap-2 text-primary hover:text-on-primary-container font-label-lg text-label-lg transition-colors" href="#">
<span class="material-symbols-outlined text-base">arrow_back</span>
<span>Kembali ke Katalog Belanja Telur</span>
</a>
<button class="px-4 py-2 rounded-full bg-surface-container-high text-on-surface font-label-md text-label-md hover:bg-surface-variant transition-colors" id="clearSelectedBtn">
            Hapus yang Dipilih
          </button>
</div>
<!-- Bundling Recommendation Upsell Banner -->
<div class="bg-gradient-to-r from-primary-fixed to-surface-container-lowest rounded-xl p-5 shadow-sm flex flex-col sm:flex-row items-center justify-between gap-4">
<div class="flex items-center gap-4">
<div class="w-14 h-14 rounded-xl bg-surface-container-lowest overflow-hidden shrink-0 shadow-xs">
<img class="w-full h-full object-cover" data-alt="Piring keramik berisi puluhan butir telur puyuh segar bercorak unik di samping sendok kayu tradisional di pasar peternakan Tanggamus" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCG23NOB0t6rwDBR7iqk65T_XCq3u3ZSZvSbS-qI_dt0VTniEvEHR0bWi8btmNg1lIwjIsovDqsOnn2KP96Y4JD6KUMQVlslnklVM2JlYPJN0wS5Vh94u_Ce4zV5kBwjSdgu-EByrWU7Vc_rekuJh-IUz6hGElFG928DgMrTmtlY-_112fOgHSuqcZR8uFXiSyAAGE-r7NbspVBrppN_9h7MRIUChjSr59M2dT5q1M"/>
</div>
<div>
<div class="flex items-center gap-1.5">
<span class="material-symbols-outlined text-primary text-base">savings</span>
<span class="font-label-sm text-label-sm uppercase font-bold text-primary tracking-wide">Promo Bundling Spesial Hari Ini</span>
</div>
<p class="font-headline-sm text-headline-sm text-on-surface mt-0.5">Tambah Rp 22.000 lagi untuk dapat diskon telur puyuh 50 butir!</p>
<p class="font-body-sm text-body-sm text-on-surface-variant">Hemat Rp 6.000 ekstra bila digabung pesanan karpet.</p>
</div>
</div>
<button class="w-full sm:w-auto px-5 py-2.5 rounded-full bg-primary text-on-primary font-label-lg text-label-lg hover:bg-on-primary-container transition-colors shadow-sm shrink-0 whitespace-nowrap">
            + Tambah Puyuh
          </button>
</div>
</div>
<!-- Sisi Kanan: Order Summary Sticky Card -->
<div class="lg:col-span-4 lg:sticky lg:top-40 space-y-6">
<!-- Summary Card -->
<div class="bg-surface-container-lowest rounded-xl p-6 shadow-sm space-y-5">
<div class="flex items-center justify-between pb-2">
<h2 class="font-headline-md text-headline-md text-on-surface">Ringkasan Pesanan</h2>
<span class="material-symbols-outlined text-primary">receipt_long</span>
</div>
<!-- Breakdown List -->
<div class="space-y-3 font-body-md text-body-md">
<div class="flex justify-between items-center text-on-surface-variant">
<span>Total Harga Produk (5 Barang)</span>
<span class="font-headline-sm text-headline-sm text-on-surface" id="subtotalDisplay">Rp 212.000</span>
</div>
<div class="flex justify-between items-center text-secondary">
<span class="flex items-center gap-1">
<span class="material-symbols-outlined text-sm">sell</span>
                Diskon Promo Bundling
              </span>
<span class="font-headline-sm text-headline-sm text-secondary">-Rp 6.000</span>
</div>
<div class="flex justify-between items-start text-on-surface-variant">
<div>
<span class="block">Estimasi Ongkos Kirim</span>
<span class="font-label-sm text-label-sm text-outline">Kecamatan Gisting, Tanggamus</span>
</div>
<div class="text-right">
<span class="font-headline-sm text-headline-sm text-secondary font-bold">GRATIS</span>
<span class="block font-label-sm text-label-sm text-outline line-through">Rp 15.000</span>
</div>
</div>
<div class="flex justify-between items-start text-on-surface-variant">
<div>
<span class="block">Asuransi Telur Utuh &amp; Packing Busa</span>
<span class="font-label-sm text-label-sm text-secondary font-semibold">Jaminan Bang Zul 100% Ganti</span>
</div>
<span class="font-headline-sm text-headline-sm text-secondary font-bold">GRATIS</span>
</div>
</div>
<!-- Coupon Code Input -->
<div class="pt-2">
<label class="block font-label-sm text-label-sm text-on-surface-variant mb-1.5">Voucher Diskon Peternak Lokal</label>
<div class="flex gap-2">
<div class="relative flex-1">
<span class="material-symbols-outlined absolute left-3 top-2.5 text-outline text-lg">local_activity</span>
<input class="w-full pl-9 pr-3 py-2 rounded-lg bg-surface-container-low text-body-sm font-body-sm text-on-surface placeholder:text-outline focus:outline-none focus:ring-2 focus:ring-primary-container" id="voucherInput" placeholder="Masukkan kode promo" type="text" value="PETERNABANGZUL"/>
</div>
<button class="px-4 py-2 rounded-lg bg-surface-container-high text-on-surface hover:bg-surface-variant font-label-md text-label-md transition-colors shrink-0" id="applyVoucherBtn">
                Gunakan
              </button>
</div>
<p class="font-label-sm text-label-sm text-secondary mt-1 flex items-center gap-1">
<span class="material-symbols-outlined text-xs">check_circle</span>
              Voucher lokal Tanggamus aktif (-Rp 6.000)
            </p>
</div>
<!-- Total Calculation -->
<div class="bg-surface-container-low rounded-xl p-4 space-y-1">
<span class="font-label-sm text-label-sm text-on-surface-variant uppercase tracking-wider block">Total Pembayaran Akhir</span>
<div class="flex items-baseline justify-between">
<span class="font-display-lg text-display-lg-mobile sm:text-display-lg text-primary" id="grandTotalDisplay">Rp 206.000</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">Termasuk PPN</span>
</div>
</div>
<!-- CTA Button -->
<button class="w-full py-4 px-6 rounded-full bg-primary-container hover:bg-primary-fixed-dim text-on-primary-container font-headline-md text-headline-md tracking-tight flex items-center justify-center gap-3 shadow-md transition-all active:scale-[0.98]" id="checkoutBtn">
<span>Lanjut ke Pembayaran (Checkout)</span>
<span class="material-symbols-outlined">arrow_forward</span>
</button>
<!-- Delivery Note -->
<p class="text-center font-label-sm text-label-sm text-on-surface-variant">
            Pemesanan sebelum pukul 14.00 dikirim hari yang sama dengan kurir lokal Tanggamus.
          </p>
<!-- Trust Badges Section -->
<div class="space-y-3 pt-3">
<div class="flex items-center gap-3">
<div class="w-8 h-8 rounded-full bg-secondary-container text-on-secondary-container flex items-center justify-center shrink-0">
<span class="material-symbols-outlined text-base">verified</span>
</div>
<div class="text-left">
<span class="font-headline-sm text-headline-sm text-on-surface block leading-tight">Garansi 100% Ganti Pecah di Tempat</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">Kurir cek fisik telur bersama Anda saat tiba</span>
</div>
</div>
<div class="flex items-center gap-3">
<div class="w-8 h-8 rounded-full bg-primary-fixed text-on-primary-fixed flex items-center justify-center shrink-0">
<span class="material-symbols-outlined text-base">scale</span>
</div>
<div class="text-left">
<span class="font-headline-sm text-headline-sm text-on-surface block leading-tight">Timbangan Tera Ulang Bersertifikat</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">Transparan, pas, tanpa manipulasi timbangan</span>
</div>
</div>
<div class="flex items-center gap-3">
<div class="w-8 h-8 rounded-full bg-tertiary-fixed text-on-tertiary-fixed flex items-center justify-center shrink-0">
<span class="material-symbols-outlined text-base">payments</span>
</div>
<div class="text-left">
<span class="font-headline-sm text-headline-sm text-on-surface block leading-tight">Bisa COD / Bayar Tunai Saat Kurir Tiba</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">Atau QRIS cepat di tempat kurir</span>
</div>
</div>
</div>
</div>
</div>
</div>
<!-- Empty State Guide / Toggle Section -->
<div class="mt-12 bg-surface-container-lowest rounded-xl p-8 shadow-sm">
<div class="flex flex-col sm:flex-row items-center justify-between gap-4 pb-6">
<div>
<h2 class="font-headline-md text-headline-md text-on-surface">Panduan Kondisi Keranjang</h2>
<p class="font-body-sm text-body-sm text-on-surface-variant">Simulasi tampilan saat belum ada produk atau ingin belanja ulang</p>
</div>
<button class="px-4 py-2 rounded-full bg-surface-container text-on-surface font-label-md text-label-md hover:bg-surface-container-high transition-colors" id="toggleEmptyStateBtn">
          Lihat Tampilan Keranjang Kosong
        </button>
</div>
<!-- Preview Empty State Card (Initially Collapsed / Hidden or Visual preview) -->
<div class="hidden rounded-xl bg-surface-container-low p-8 text-center space-y-4" id="emptyStateContainer">
<div class="w-20 h-20 mx-auto rounded-full bg-surface-container-highest flex items-center justify-center text-primary">
<span class="material-symbols-outlined text-4xl">egg</span>
</div>
<div class="max-w-md mx-auto space-y-1">
<h3 class="font-headline-md text-headline-md text-on-surface">Keranjang Belanja Masih Kosong</h3>
<p class="font-body-md text-body-md text-on-surface-variant">
            Sarang telur Anda masih belum terisi. Yuk, pilih telur ayam ras segar, telur kampung omega, atau telur bebek langsung dari peternak lokal Tanggamus hari ini!
          </p>
</div>
<div class="pt-2">
<a class="inline-flex items-center gap-2 px-6 py-3 rounded-full bg-primary text-on-primary font-headline-sm text-headline-sm hover:bg-on-primary-container transition-colors shadow-sm" href="#">
<span class="material-symbols-outlined text-lg">storefront</span>
<span>Mulai Belanja Telur Segar</span>
</a>
</div>
</div>
</div>
</div>
<script>
    (function() {
      // Interactive logic for Stepper and Subtotal Updates
      const cartItems = document.querySelectorAll('.cart-item');
      const subtotalDisplay = document.getElementById('subtotalDisplay');
      const grandTotalDisplay = document.getElementById('grandTotalDisplay');
      const discount = 6000;

      function formatRupiah(number) {
        return 'Rp ' + number.toLocaleString('id-ID');
      }

      function updateTotals() {
        let total = 0;
        let count = 0;
        document.querySelectorAll('.cart-item').forEach(item => {
          const checkbox = item.querySelector('.item-checkbox');
          if (checkbox && checkbox.checked) {
            const price = parseInt(item.getAttribute('data-price') || 0, 10);
            const qty = parseInt(item.querySelector('.step-quantity').innerText || 0, 10);
            total += (price * qty);
            count += qty;
          }
        });

        if (subtotalDisplay) subtotalDisplay.innerText = formatRupiah(total);
        const grandTotal = Math.max(0, total - discount);
        if (grandTotalDisplay) grandTotalDisplay.innerText = formatRupiah(grandTotal);
      }

      cartItems.forEach(item => {
        const minusBtn = item.querySelector('.step-btn-minus');
        const plusBtn = item.querySelector('.step-btn-plus');
        const qtySpan = item.querySelector('.step-quantity');
        const subtotalSpan = item.querySelector('.item-subtotal');
        const deleteBtn = item.querySelector('.delete-btn');
        const checkbox = item.querySelector('.item-checkbox');
        const price = parseInt(item.getAttribute('data-price') || 0, 10);

        if (plusBtn && qtySpan) {
          plusBtn.addEventListener('click', () => {
            let current = parseInt(qtySpan.innerText, 10);
            current += 1;
            qtySpan.innerText = current;
            if (subtotalSpan) subtotalSpan.innerText = formatRupiah(current * price);
            updateTotals();
          });
        }

        if (minusBtn && qtySpan) {
          minusBtn.addEventListener('click', () => {
            let current = parseInt(qtySpan.innerText, 10);
            if (current > 1) {
              current -= 1;
              qtySpan.innerText = current;
              if (subtotalSpan) subtotalSpan.innerText = formatRupiah(current * price);
              updateTotals();
            }
          });
        }

        if (deleteBtn) {
          deleteBtn.addEventListener('click', () => {
            item.remove();
            updateTotals();
          });
        }

        if (checkbox) {
          checkbox.addEventListener('change', updateTotals);
        }
      });

      // Select All Toggle
      const selectAll = document.getElementById('selectAllCheckbox');
      if (selectAll) {
        selectAll.addEventListener('change', (e) => {
          const isChecked = e.target.checked;
          document.querySelectorAll('.item-checkbox').forEach(cb => {
            cb.checked = isChecked;
          });
          updateTotals();
        });
      }

      // Bulk Delete
      const bulkDeleteBtn = document.getElementById('bulkDeleteBtn');
      const clearSelectedBtn = document.getElementById('clearSelectedBtn');
      function deleteSelected() {
        document.querySelectorAll('.cart-item').forEach(item => {
          const cb = item.querySelector('.item-checkbox');
          if (cb && cb.checked) {
            item.remove();
          }
        });
        updateTotals();
      }

      if (bulkDeleteBtn) bulkDeleteBtn.addEventListener('click', deleteSelected);
      if (clearSelectedBtn) clearSelectedBtn.addEventListener('click', deleteSelected);

      // Voucher Apply feedback
      const applyBtn = document.getElementById('applyVoucherBtn');
      if (applyBtn) {
        applyBtn.addEventListener('click', () => {
          applyBtn.innerText = 'Diterapkan';
          applyBtn.classList.add('bg-secondary-container', 'text-on-secondary-container');
        });
      }

      // Toggle Empty State demo card
      const toggleEmptyStateBtn = document.getElementById('toggleEmptyStateBtn');
      const emptyStateContainer = document.getElementById('emptyStateContainer');
      if (toggleEmptyStateBtn && emptyStateContainer) {
        toggleEmptyStateBtn.addEventListener('click', () => {
          emptyStateContainer.classList.toggle('hidden');
          if (emptyStateContainer.classList.contains('hidden')) {
            toggleEmptyStateBtn.innerText = 'Lihat Tampilan Keranjang Kosong';
          } else {
            toggleEmptyStateBtn.innerText = 'Sembunyikan Panduan Kosong';
          }
        });
      }
    })();
  </script>
</div></main><footer class="w-full bg-surface-container-low mt-16 pt-12 pb-8 text-on-surface-variant"><div class="max-w-7xl mx-auto px-4 lg:px-8 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8"><div class="space-y-3"><div class="flex items-center gap-2"><img alt="Logo Bang Zul Egg Market" class="h-7 w-auto object-contain" src="https://lh3.googleusercontent.com/aida/ALJJyrAvuhgJbL1OqXYnorOpflEwk9ch2RB3i3nIpJf2khBHtFUraZYLjA49xnoYr5_XpY1inx_yvUKDG-f5ULodcAC4hoBl9QYWujU07wAAJsvNI88PefRZRNH2SgRzcvtvfP9LlMDgvobQRRrHxWwLlWY8MQoR1CS4kennwXqXJqn5PR3R5zkf-p4q0eleDblVHlCAtE__Wj8FbqU6db9zlBw02jnLdLpow_xGCN8RF4es"/><span class="font-headline-sm text-headline-sm text-primary">UD. Bang Zul Egg Market</span></div><p class="font-body-sm text-body-sm">Pusat distribusi telur segar langsung dari peternak binaan lokal Tanggamus. Menjaga kualitas kesegaran cangkang utuh dan timbangan presisi terpercaya.</p><div class="flex items-center gap-2 text-secondary font-label-sm text-label-sm"><span class="material-symbols-outlined text-sm">verified</span><span>Garansi Ganti Telur Pecah 100% Langsung di Tempat</span></div></div><div class="space-y-2"><h3 class="font-headline-sm text-headline-sm text-on-surface">Jam Operasional &amp; Panen</h3><p class="font-body-sm text-body-sm">Pengambilan Telur Kandang: 06.00 - 10.00 WIB</p><p class="font-body-sm text-body-sm">Jadwal Pengiriman Kurir: 08.00 - 18.00 WIB</p><p class="font-body-sm text-body-sm text-secondary font-semibold">Setiap Hari (Senin - Minggu Tetap Buka)</p><p class="font-label-sm text-label-sm text-on-surface-variant pt-1">Wilayah Gisting, Talang Padang, Wonosobo, Kota Agung &amp; Sekitarnya.</p></div><div class="space-y-2"><h3 class="font-headline-sm text-headline-sm text-on-surface">Metode Pembayaran</h3><div class="space-y-1 font-body-sm text-body-sm"><p class="flex items-center gap-1.5"><span class="material-symbols-outlined text-primary text-sm">qr_code_scanner</span>QRIS Seluruh Bank &amp; E-Wallet</p><p class="flex items-center gap-1.5"><span class="material-symbols-outlined text-primary text-sm">account_balance</span>Transfer Bank Lampung / BRI / BCA</p><p class="flex items-center gap-1.5"><span class="material-symbols-outlined text-primary text-sm">payments</span>COD (Bayar Tunai di Tempat saat Timbang)</p></div></div><div class="space-y-2"><h3 class="font-headline-sm text-headline-sm text-on-surface">Komitmen Peternak Lokal</h3><p class="font-body-sm text-body-sm">Mendukung keberlanjutan usaha peternak unggas pedesaan di Kabupaten Tanggamus, Lampung dengan harga adil, timbangan transparan, dan pakan alami bermutu.</p><div class="pt-2"><span class="inline-block px-3 py-1 bg-secondary-container text-on-secondary-container rounded-full font-label-sm text-label-sm">Asli Tanggamus, Segar Bergaransi</span></div></div></div><div class="max-w-7xl mx-auto px-4 lg:px-8 mt-10 pt-4 flex flex-col sm:flex-row items-center justify-between gap-2 font-label-sm text-label-sm text-on-surface-variant"><p>© 2024 UD. Bang Zul Egg Market Tanggamus Lampung. Hak Cipta Dilindungi.</p><p>Dibuat untuk ekosistem niaga agrikultur Kabupaten Tanggamus</p></div></footer></body></html>

<!-- Detail Produk Telur Bang Zul -->
<!DOCTYPE html>

<html lang="id"><head><meta charset="utf-8"/><meta content="width=device-width, initial-scale=1.0" name="viewport"/><meta content="web_standard" name="shell-type"/><link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" rel="stylesheet"/><link href="https://fonts.googleapis.com" rel="preconnect"/><link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/><link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&amp;family=Plus+Jakarta+Sans:wght@700;800&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/><style>@layer base{html,body{margin:0;padding:0;}body{overscroll-behavior:none;}main>:first-child{margin-top:0!important;}main>:last-child{margin-bottom:0!important;}}::-webkit-scrollbar{display:none;}</style><script src="https://cdn.tailwindcss.com"></script><script id="tailwind-config">tailwind.config={darkMode:"class",theme:{extend:{colors:{"secondary-container":"#a0f399","on-tertiary-fixed-variant":"#3e4a41","on-background":"#1b1c1c","on-error":"#ffffff","on-primary":"#ffffff","primary":"#835500","surface-container-highest":"#e4e2e1","on-secondary-fixed-variant":"#005312","surface-container-low":"#f6f3f2","background":"#fcf9f8","surface":"#fcf9f8","on-tertiary-fixed":"#131e17","on-secondary-container":"#217128","outline-variant":"#d7c3ae","inverse-surface":"#303030","surface-container":"#f0eded","on-secondary-fixed":"#002204","surface-bright":"#fcf9f8","primary-fixed":"#ffddb4","surface-dim":"#dcd9d9","surface-container-lowest":"#ffffff","tertiary":"#556158","on-primary-fixed":"#291800","secondary-fixed":"#a3f69c","tertiary-container":"#acb9ae","on-primary-container":"#644000","on-primary-fixed-variant":"#633f00","on-tertiary":"#ffffff","surface-variant":"#e4e2e1","on-tertiary-container":"#3e4a41","on-secondary":"#ffffff","inverse-on-surface":"#f3f0f0","surface-tint":"#835500","primary-fixed-dim":"#ffb955","on-surface-variant":"#524534","on-error-container":"#93000a","surface-container-high":"#eae7e7","error":"#ba1a1a","primary-container":"#f5a623","inverse-primary":"#ffb955","outline":"#857462","tertiary-fixed":"#d9e6da","tertiary-fixed-dim":"#bdcabe","error-container":"#ffdad6","secondary":"#1b6d24","on-surface":"#1b1c1c","secondary-fixed-dim":"#88d982"},borderRadius:{"DEFAULT":"0.25rem","lg":"0.5rem","xl":"0.75rem","full":"9999px"},spacing:{"space-md":"1rem","gutter":"1rem","space-lg":"1.5rem","space-xl":"2rem","gutter-desktop":"1.5rem","space-xs":"0.25rem","space-sm":"0.5rem","margin":"1rem","margin-desktop":"2.5rem"},fontFamily:{"body-md":["Inter"],"label-sm":["Inter"],"price-display":["Plus Jakarta Sans"],"stock-counter":["Inter"],"headline-md":["Plus Jakarta Sans"],"body-lg":["Inter"],"label-md":["Inter"],"headline-sm":["Plus Jakarta Sans"],"display-lg":["Plus Jakarta Sans"],"label-lg":["Inter"],"headline-lg-mobile":["Plus Jakarta Sans"],"headline-lg":["Plus Jakarta Sans"],"body-sm":["Inter"],"display-lg-mobile":["Plus Jakarta Sans"]},fontSize:{"body-md":["14px",{"lineHeight":"22px","fontWeight":"400"}],"label-sm":["11px",{"lineHeight":"14px","letterSpacing":"0.02em","fontWeight":"600"}],"price-display":["22px",{"lineHeight":"28px","letterSpacing":"-0.02em","fontWeight":"800"}],"stock-counter":["18px",{"lineHeight":"24px","letterSpacing":"0.01em","fontWeight":"700"}],"headline-md":["20px",{"lineHeight":"28px","fontWeight":"700"}],"body-lg":["16px",{"lineHeight":"26px","fontWeight":"400"}],"label-md":["12px",{"lineHeight":"16px","fontWeight":"600"}],"headline-sm":["16px",{"lineHeight":"24px","fontWeight":"700"}],"display-lg":["40px",{"lineHeight":"48px","letterSpacing":"-0.02em","fontWeight":"800"}],"label-lg":["14px",{"lineHeight":"20px","fontWeight":"600"}],"headline-lg-mobile":["22px",{"lineHeight":"30px","letterSpacing":"0em","fontWeight":"700"}],"headline-lg":["28px",{"lineHeight":"36px","letterSpacing":"-0.01em","fontWeight":"700"}],"body-sm":["12px",{"lineHeight":"18px","fontWeight":"400"}],"display-lg-mobile":["30px",{"lineHeight":"38px","letterSpacing":"-0.01em","fontWeight":"800"}]}}}}</script></head><body class="bg-surface font-body-md text-body-md text-on-surface antialiased"><header class="fixed top-0 left-0 w-full z-50 bg-surface/95 backdrop-blur-md shadow-[0_4px_20px_-2px_rgba(245,166,35,0.12)]"><div class="bg-secondary text-on-secondary px-4 py-1.5"><div class="max-w-7xl mx-auto flex flex-col md:flex-row items-center justify-between gap-1 text-label-sm font-label-sm"><div class="flex items-center gap-2 text-center md:text-left"><span class="material-symbols-outlined text-secondary-fixed text-sm">local_shipping</span><span>Pengiriman Segar Hari Ini ke Wilayah Kota Agung, Gisting, Talang Padang, Wonosobo, Pringsewu sekitarnya | <strong class="text-secondary-fixed">Garansi Telur Pecah Diganti 100%</strong></span></div><a class="flex items-center gap-1.5 hover:text-secondary-fixed transition-colors whitespace-nowrap" href="https://wa.me/6281278900000"><span class="material-symbols-outlined text-sm">chat</span><span>WhatsApp CS Hubungi Bang Zul: 0812-7890-XXXX</span></a></div></div><div class="max-w-7xl mx-auto px-4 lg:px-8 py-3 flex items-center justify-between gap-4"><a class="flex items-center gap-3 shrink-0" data-path="katalog-belanja-pembeli" href="#"><img alt="Logo Bang Zul Egg Market" class="h-8 w-auto object-contain" src="https://lh3.googleusercontent.com/aida/ALJJyrAvuhgJbL1OqXYnorOpflEwk9ch2RB3i3nIpJf2khBHtFUraZYLjA49xnoYr5_XpY1inx_yvUKDG-f5ULodcAC4hoBl9QYWujU07wAAJsvNI88PefRZRNH2SgRzcvtvfP9LlMDgvobQRRrHxWwLlWY8MQoR1CS4kennwXqXJqn5PR3R5zkf-p4q0eleDblVHlCAtE__Wj8FbqU6db9zlBw02jnLdLpow_xGCN8RF4es"/><div class="flex flex-col"><span class="font-headline-md text-headline-md text-primary tracking-tight leading-none">Bang Zul</span><span class="font-label-sm text-label-sm text-secondary font-bold tracking-wider uppercase leading-none mt-0.5">Egg Market Tanggamus</span></div></a><div class="hidden lg:flex items-center gap-1.5 px-3 py-1.5 rounded-full bg-surface-container-low text-on-surface-variant font-label-sm text-label-sm shrink-0"><span class="material-symbols-outlined text-primary text-base">location_on</span><span class="max-w-[210px] truncate">Kab. Tanggamus (Gisting, Kota Agung &amp; Sekitarnya)</span></div><div class="hidden md:flex flex-1 max-w-md mx-2"><div class="relative w-full flex items-center"><span class="material-symbols-outlined absolute left-3 text-outline text-lg">search</span><input class="w-full pl-10 pr-4 py-2 rounded-full bg-surface-container-lowest text-body-sm font-body-sm text-on-surface placeholder:text-outline focus:outline-none focus:ring-2 focus:ring-primary-container shadow-[0_1px_4px_rgba(0,0,0,0.04)]" placeholder="Cari telur ayam ras, telur omega, telur bebek, puyuh..." type="text"/></div></div><div class="flex items-center gap-2 md:gap-3 shrink-0"><a class="flex items-center gap-2 px-3 py-1.5 rounded-full bg-primary-container text-on-primary-container hover:bg-primary-fixed-dim transition-colors shadow-sm" data-path="keranjang-belanja-pembeli" href="#"><span class="material-symbols-outlined text-lg">shopping_basket</span><span class="hidden sm:inline font-label-sm text-label-sm">Keranjang (3 Item)</span></a><div class="hidden sm:flex items-center gap-1.5 pl-1"><a class="px-3 py-1.5 rounded-full bg-surface-container text-on-surface hover:bg-surface-container-high transition-colors font-label-sm text-label-sm" data-path="masuk-akun-pembeli" href="#">Masuk</a><a class="px-3 py-1.5 rounded-full bg-primary text-on-primary hover:bg-on-primary-container transition-colors font-label-sm text-label-sm" data-path="daftar-akun-pembeli" href="#">Daftar</a></div><a class="flex items-center gap-1.5 p-1.5 rounded-full hover:bg-surface-container-high text-on-surface-variant" data-path="profil-akun-pembeli" href="#"><img alt="Foto Akun Pembeli" class="w-8 h-8 rounded-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBu4cCay1o-kcZkrepBjdwRhNkTeb5NSNF4V20H1AoEXr4ahIrRP9SktX37TUve3u7us_GHnlm1279EoAyYcFxqZTZV4CIOdstOTCqIMcitiPTCwpWm4m2okjdh9z8S2I2n0sK1hb3y3ohWU84Tu6ZWNoxKL7D1NVLhMsBA3C6eHNQmukclnmKpMzHXssx-xtkh1wF2y2OFEDgXUgTPjjAfLabaOsUrz91MId6by4k"/></a></div></div><div class="bg-surface-container-lowest shadow-[0_1px_4px_rgba(0,0,0,0.02)] overflow-x-auto"><div class="max-w-7xl mx-auto px-4 lg:px-8"><nav class="flex items-center gap-6 whitespace-nowrap py-2.5 text-label-sm font-label-sm" data-active-classes="text-primary font-bold border-b-2 border-primary"><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="katalog-belanja-pembeli" href="#">Katalog Telur Segar</a><a aria-current="page" class="transition-colors pb-1 text-primary font-bold border-b-2 border-primary" data-path="detail-produk-telur" href="#">Detail Produk Telur</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="keranjang-belanja-pembeli" href="#">Keranjang Belanja</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="checkout-pembayaran-pembeli" href="#">Checkout Pembayaran</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="profil-akun-pembeli" href="#">Profil Saya</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="masuk-akun-pembeli" href="#">Masuk Akun</a><a class="text-on-surface-variant hover:text-on-surface transition-colors pb-1" data-path="daftar-akun-pembeli" href="#">Daftar Akun Baru</a></nav></div></div></header><main class="w-full pt-36 bg-surface min-h-screen"><div class="flex flex-col w-full">
<!-- Container Pembungkus Lebar Penuh -->
<div class="max-w-7xl mx-auto px-4 lg:px-8 py-6 w-full">
<!-- Breadcrumb Navigasi -->
<nav class="flex items-center gap-2 text-label-sm font-label-sm text-on-surface-variant mb-6 overflow-x-auto whitespace-nowrap py-1">
<a class="hover:text-primary transition-colors flex items-center gap-1" href="#">
<span class="material-symbols-outlined text-sm">home</span>
<span>Beranda</span>
</a>
<span class="material-symbols-outlined text-xs text-outline">chevron_right</span>
<a class="hover:text-primary transition-colors" href="#">Katalog Telur Segar</a>
<span class="material-symbols-outlined text-xs text-outline">chevron_right</span>
<a class="hover:text-primary transition-colors" href="#">Telur Ayam Ras</a>
<span class="material-symbols-outlined text-xs text-outline">chevron_right</span>
<span class="text-on-surface font-semibold truncate max-w-xs md:max-w-md">Telur Ayam Ras Super Karpet (30 Butir)</span>
</nav>
<!-- Bar Notifikasi Kesegaran Subuh -->
<div class="mb-6 bg-gradient-to-r from-primary-fixed to-surface-container-low p-3 md:p-4 rounded-xl flex flex-wrap items-center justify-between gap-3 shadow-sm">
<div class="flex items-center gap-3">
<span class="p-2 rounded-lg bg-primary text-on-primary flex items-center justify-center">
<span class="material-symbols-outlined text-lg" style="font-variation-settings: 'FILL' 1;">wb_sunny</span>
</span>
<div>
<p class="font-headline-sm text-headline-sm text-on-primary-fixed leading-tight">Batch Panen Subuh Tadi (Pukul 05.15 WIB)</p>
<p class="font-body-sm text-body-sm text-on-primary-fixed-variant">Langsung disortir dari kandang lereng Gisting. Telur belum masuk pendingin buatan, kesegaran 100% prima.</p>
</div>
</div>
<div class="flex items-center gap-2 bg-surface-container-lowest px-3 py-1.5 rounded-full shadow-xs">
<span class="w-2 h-2 rounded-full bg-secondary animate-pulse"></span>
<span class="font-label-sm text-label-sm text-secondary font-bold">Stok Siap Antar: 140 Karpet</span>
</div>
</div>
<!-- Grid Detail Produk Utama -->
<div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-start mb-12">
<!-- SISI KIRI: Galeri Gambar Interaktif (5 Kolom) -->
<div class="lg:col-span-5 flex flex-col gap-4">
<!-- Frame Gambar Utama -->
<div class="relative w-full aspect-square bg-surface-container-low rounded-2xl overflow-hidden shadow-md group">
<img alt="Telur Ayam Ras Super Karpet 30 Butir di Pasar Tradisional Bang Zul Tanggamus" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105" id="mainProductImage" src="https://lh3.googleusercontent.com/aida/ALJJyrBzqMYG7Kl3hKy_p8nmJCwyUDMb9FuoWxtyPnCVshW0vlklRkQ8Xy7vFl0RvF3bpisL0Irwd7esKCjJEmLHvESjfIo6_VPaZAlZ6m9_14CJcBrhht5Bbrm30ZAyGvbSK2DPqWbJsn5e7j1AyP1gbHXHFsDh2tdRCD2f8QSQqGGP6lzamocq3RE1dYp9UUjEsXptiGyYrh-H6-yMG2qkynIwtxDdxzKakoydZ5XL-_lp"/>
<!-- Badge Overlay Panen Subuh -->
<div class="absolute top-4 left-4 flex flex-col gap-1.5 z-10">
<span class="inline-flex items-center gap-1.5 px-3 py-1 rounded-full bg-primary-container text-on-primary-container font-label-sm text-label-sm font-bold shadow-md backdrop-blur-xs">
<span class="material-symbols-outlined text-xs" style="font-variation-settings: 'FILL' 1;">eco</span>
              100% Panen Subuh Tadi
            </span>
<span class="inline-flex items-center gap-1.5 px-2.5 py-0.5 rounded-full bg-surface-container-lowest/90 text-secondary font-label-sm text-label-sm font-semibold shadow-xs">
<span class="material-symbols-outlined text-xs">verified</span>
              Cangkang Tebal Grade A
            </span>
</div>
<!-- Tombol Zoom / Fullscreen Visual -->
<button aria-label="Perbesar foto telur" class="absolute bottom-4 right-4 p-2.5 rounded-full bg-surface-container-lowest/90 text-on-surface hover:bg-surface-container-lowest hover:text-primary transition-all shadow-md flex items-center justify-center" onclick="alert('Tampilan resolusi tinggi cangkang telur: cangkang pori rapat alami tanpa kotoran menempel.');" type="button">
<span class="material-symbols-outlined text-lg">zoom_in</span>
</button>
</div>
<!-- 4 Thumbnail Pilihan Sudut Pandang -->
<div class="grid grid-cols-4 gap-2.5 sm:gap-3">
<!-- Thumb 1 (Aktif Default) -->
<button class="thumb-btn active-thumb relative aspect-square rounded-xl overflow-hidden bg-surface-container-low ring-2 ring-primary-container transition-all shadow-xs" onclick="updateMainImage('https://lh3.googleusercontent.com/aida/ALJJyrBzqMYG7Kl3hKy_p8nmJCwyUDMb9FuoWxtyPnCVshW0vlklRkQ8Xy7vFl0RvF3bpisL0Irwd7esKCjJEmLHvESjfIo6_VPaZAlZ6m9_14CJcBrhht5Bbrm30ZAyGvbSK2DPqWbJsn5e7j1AyP1gbHXHFsDh2tdRCD2f8QSQqGGP6lzamocq3RE1dYp9UUjEsXptiGyYrh-H6-yMG2qkynIwtxDdxzKakoydZ5XL-_lp', this)" type="button">
<img alt="Tumpukan karpet telur 30 butir di rak kayu pasar" class="w-full h-full object-cover" src="https://lh3.googleusercontent.com/aida/ALJJyrBzqMYG7Kl3hKy_p8nmJCwyUDMb9FuoWxtyPnCVshW0vlklRkQ8Xy7vFl0RvF3bpisL0Irwd7esKCjJEmLHvESjfIo6_VPaZAlZ6m9_14CJcBrhht5Bbrm30ZAyGvbSK2DPqWbJsn5e7j1AyP1gbHXHFsDh2tdRCD2f8QSQqGGP6lzamocq3RE1dYp9UUjEsXptiGyYrh-H6-yMG2qkynIwtxDdxzKakoydZ5XL-_lp"/>
<span class="sr-only">Tampilan Karpet Telur</span>
</button>
<!-- Thumb 2: Kuning Telur Oranye Pekat -->
<button class="thumb-btn relative aspect-square rounded-xl overflow-hidden bg-surface-container-low opacity-75 hover:opacity-100 transition-all shadow-xs" onclick="updateMainImage('placeholder', this)" type="button">
<img class="w-full h-full object-cover" data-alt="Close up high-angle macro photograph of a cracked farm-fresh chicken egg on a rustic wooden spoon showing a deep, glowing orange yolk held firmly by thick, transparent egg whites. Natural soft morning sun lighting highlighting fresh texture, country kitchen table background with hints of warm amber." src="https://lh3.googleusercontent.com/aida-public/AB6AXuALSE4Hk0Xk9AvbF1Xri3Ga7wot6IK4S_dOb3TWYvM23qZ-qgCrjjdvpVvj6bIkkCAn87QtExwqNJNf0mPbDvUVQDlwY29mIP445ZH7-nzNNrr8qtbch6I8pQ63gA6KnHWYpQkC3-3-yUd6LTz4FO1fH7kzk02QDKjpmSTLzqSr9KVozRmIfOErGjwfOsLU-HiWnFt6yfMP8hVACtmU1ZjycW3S6Eys9WlMl1Sd6p8"/>
<span class="absolute bottom-0 inset-x-0 bg-inverse-surface/60 text-inverse-on-surface font-label-sm text-[10px] text-center py-0.5 truncate px-1">Kuning Oranye</span>
</button>
<!-- Thumb 3: Timbangan Tera Digital Presisi 1.85 kg -->
<button class="thumb-btn relative aspect-square rounded-xl overflow-hidden bg-surface-container-low opacity-75 hover:opacity-100 transition-all shadow-xs" onclick="updateMainImage('placeholder', this)" type="button">
<img class="w-full h-full object-cover" data-alt="Digital scale showing exactly 1.85 kilograms on glowing LED numbers, holding a full sturdy cardboard tray of thirty freshly collected brown chicken eggs. Rustic Indonesian market setting with wooden countertop and authentic egg packaging." src="https://lh3.googleusercontent.com/aida-public/AB6AXuATnSnpmH7V1FM-u1tMcRgyyxb4ITRmBry8e8K7amqIWTroYeG8e77XECxDatsryVS6l5Uqvnx4PQSUDKctU6zQvgTnuOo2zqtWENoOfQd08ydtmocjMIhTjmx29PLY6hjDeigeM16dS7Nd0NHcriTR0Eh-jdBigd6Vwu8G0U2iixgzE3mNVrhNeCTOuecJQu7d3p4XPZ8fC0Pp-9Q8CZHY4TVVW-a52u7zWBfa2YM"/>
<span class="absolute bottom-0 inset-x-0 bg-inverse-surface/60 text-inverse-on-surface font-label-sm text-[10px] text-center py-0.5 truncate px-1">Tera 1.85 Kg</span>
</button>
<!-- Thumb 4: Kemasan Kardus Busa Peredam Motor Tanggamus -->
<button class="thumb-btn relative aspect-square rounded-xl overflow-hidden bg-surface-container-low opacity-75 hover:opacity-100 transition-all shadow-xs" onclick="updateMainImage('placeholder', this)" type="button">
<img class="w-full h-full object-cover" data-alt="Protective courier delivery packaging for fresh chicken eggs featuring shock-absorbing custom foam inserts and eco-friendly corrugated carton box, ready for mountain road motorbike transport in rural Tanggamus." src="https://lh3.googleusercontent.com/aida-public/AB6AXuAj3l9zk29coMi_fqz0mWu2I6_Z-nnWCT19mokdAtCvCkyIPAQOy-Vn6aww5EoMSebxINbYdlOhqk0w5CfMTCcNSkj8OFrf-I7uzb353oElUGB4iBUvxNfpv3dBZpQNe__jRDHAHzGTcdKD_xH07Enh6b9vTGcE7lrOhgQnFK-t9Pmd8OzGNU6n7BIJrzk2Rr3RwsPh62SPswosXr7jkGcGLGpIF3RaEQGwuWfGVas"/>
<span class="absolute bottom-0 inset-x-0 bg-inverse-surface/60 text-inverse-on-surface font-label-sm text-[10px] text-center py-0.5 truncate px-1">Peredam Busa</span>
</button>
</div>
<!-- Catatan Transparansi Berat -->
<div class="bg-surface-container-low p-3.5 rounded-xl flex items-start gap-3">
<span class="material-symbols-outlined text-secondary text-lg mt-0.5" style="font-variation-settings: 'FILL' 1;">scale</span>
<div class="text-body-sm font-body-sm">
<span class="font-bold text-on-surface">Standar Bobot Bang Zul:</span> Rata-rata 61 - 63 gram per butir. Satu karpet berisi tepat 30 butir berkisar 1.80 kg s/d 1.88 kg (dijamin kenyang &amp; tidak oplosan telur kecil).
          </div>
</div>
</div>
<!-- SISI KANAN: Detail Informasi Produk & Pembelian (7 Kolom) -->
<div class="lg:col-span-7 flex flex-col">
<!-- Tag Kategori & Asal Kandang -->
<div class="flex flex-wrap items-center gap-2 mb-2">
<span class="px-2.5 py-1 rounded-full bg-secondary-container text-on-secondary-container font-label-sm text-label-sm font-semibold">
            Ayam Ras Pilihan
          </span>
<span class="px-2.5 py-1 rounded-full bg-surface-container-high text-on-surface-variant font-label-sm text-label-sm font-semibold flex items-center gap-1">
<span class="material-symbols-outlined text-xs">location_on</span>
            Ready Kandang Gisting
          </span>
<span class="px-2.5 py-1 rounded-full bg-primary-fixed text-on-primary-fixed font-label-sm text-label-sm">
            Grade A Super
          </span>
</div>
<!-- Judul Produk -->
<h1 class="font-headline-lg text-headline-lg text-on-surface font-bold tracking-tight mb-2">
          Telur Ayam Ras Super Karpet (30 Butir)
        </h1>
<!-- Rating & Indikator Penjualan -->
<div class="flex flex-wrap items-center gap-3 mb-4 pb-4 border-b border-surface-container-highest">
<div class="flex items-center gap-1 bg-surface-container-lowest px-2.5 py-1 rounded-lg shadow-xs">
<span class="material-symbols-outlined text-primary-container text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="font-label-lg text-label-lg font-bold text-on-surface">4.9</span>
<span class="text-on-surface-variant font-body-sm text-body-sm">/ 5.0</span>
</div>
<span class="text-outline-variant">•</span>
<a class="font-body-sm text-body-sm text-primary hover:underline font-semibold" href="#ulasan-section">
            248 Ulasan Pembeli Tanggamus
          </a>
<span class="text-outline-variant">•</span>
<span class="text-secondary font-label-sm text-label-sm font-bold flex items-center gap-1">
<span class="material-symbols-outlined text-xs">local_shipping</span>
            Terjual 3.200+ Karpet
          </span>
</div>
<!-- Bagian Harga & Pembaruan Harian Pasar -->
<div class="bg-surface-container-lowest p-4 rounded-2xl shadow-sm mb-6">
<div class="flex flex-col sm:flex-row sm:items-baseline justify-between gap-2">
<div>
<span class="font-body-sm text-body-sm text-on-surface-variant block mb-1">Harga Grosir Langsung Peternak:</span>
<div class="flex items-baseline gap-2">
<span class="font-price-display text-price-display text-primary font-extrabold" id="priceDisplay">
                  Rp 52.000
                </span>
<span class="font-body-sm text-body-sm text-on-surface-variant line-through">
                  Rp 55.000
                </span>
<span class="px-2 py-0.5 rounded-full bg-secondary-container text-on-secondary-container font-label-sm text-label-sm font-bold">
                  Hemat Rp 3.000
                </span>
</div>
</div>
<div class="flex items-center gap-1.5 text-tertiary font-label-sm text-label-sm bg-surface-container-low px-2.5 py-1 rounded-full self-start sm:self-auto">
<span class="material-symbols-outlined text-xs">update</span>
<span>Harga diperbarui hari ini 06.00 WIB</span>
</div>
</div>
</div>
<!-- Deskripsi Singkat Produk -->
<p class="font-body-md text-body-md text-on-surface-variant mb-6 leading-relaxed">
          Dipanen subuh hari dari mitra peternak ayam ras petelur lereng Gisting &amp; Talang Padang. Bebas antibiotik kimia, cangkang cokelat tebal tidak mudah retak, dengan kuning telur oranye alami yang kental sempurna untuk lauk keluarga, warung makan, maupun adonan kue martabak.
        </p>
<!-- Pemilihan Varian / Paket Kemasan -->
<div class="mb-6">
<label class="font-label-lg text-label-lg text-on-surface block mb-2.5 font-bold">
            Pilihan Paket Kemasan Telur:
          </label>
<div class="grid grid-cols-1 sm:grid-cols-3 gap-3" id="variantSelector">
<!-- Varian 1 -->
<button class="variant-btn flex flex-col p-3 rounded-xl bg-surface-container-lowest ring-2 ring-primary-container text-left transition-all shadow-xs relative" data-price="52000" data-variant="1-karpet" data-weight="1.85" onclick="selectVariant(this)" type="button">
<span class="font-label-md text-label-md text-on-surface font-bold">1 Karpet (30 Butir)</span>
<span class="font-body-sm text-body-sm text-primary font-semibold mt-0.5">Rp 52.000</span>
<span class="font-label-sm text-label-sm text-on-surface-variant mt-1">±1.85 Kg • Dus Kokoh</span>
<span class="variant-indicator absolute top-2 right-2 w-2 h-2 rounded-full bg-primary-container"></span>
</button>
<!-- Varian 2 (Best Seller) -->
<button class="variant-btn flex flex-col p-3 rounded-xl bg-surface-container-low hover:bg-surface-container text-left transition-all relative" data-price="102000" data-variant="2-karpet" data-weight="3.70" onclick="selectVariant(this)" type="button">
<div class="flex items-center justify-between">
<span class="font-label-md text-label-md text-on-surface font-bold">Paket 2 Karpet</span>
<span class="px-1.5 py-0.5 rounded bg-secondary-container text-on-secondary-container text-[10px] font-bold">Gratis Ongkir</span>
</div>
<span class="font-body-sm text-body-sm text-on-surface font-semibold mt-0.5">Rp 102.000</span>
<span class="font-label-sm text-label-sm text-on-surface-variant mt-1">60 Butir (Hemat Rp 2rb)</span>
<span class="variant-indicator hidden absolute top-2 right-2 w-2 h-2 rounded-full bg-primary-container"></span>
</button>
<!-- Varian 3 (Grosir Warung) -->
<button class="variant-btn flex flex-col p-3 rounded-xl bg-surface-container-low hover:bg-surface-container text-left transition-all relative" data-price="250000" data-variant="5-karpet" data-weight="9.25" onclick="selectVariant(this)" type="button">
<div class="flex items-center justify-between">
<span class="font-label-md text-label-md text-on-surface font-bold">Ikat Grosir (5 Karpet)</span>
<span class="px-1.5 py-0.5 rounded bg-primary-fixed text-on-primary-fixed text-[10px] font-bold">Warung</span>
</div>
<span class="font-body-sm text-body-sm text-on-surface font-semibold mt-0.5">Rp 250.000</span>
<span class="font-label-sm text-label-sm text-on-surface-variant mt-1">150 Butir • Tali Rafia Ikat</span>
<span class="variant-indicator hidden absolute top-2 right-2 w-2 h-2 rounded-full bg-primary-container"></span>
</button>
</div>
</div>
<!-- Quantity Stepper & Estimasi Timbangan Berat -->
<div class="flex flex-wrap items-center justify-between gap-4 p-4 rounded-xl bg-surface-container-low mb-6">
<div>
<span class="font-label-md text-label-md text-on-surface font-bold block">Tentukan Jumlah Pesanan:</span>
<span class="font-body-sm text-body-sm text-on-surface-variant" id="weightSummary">Estimasi total timbangan: ~1.85 kg</span>
</div>
<div class="flex items-center gap-3">
<div class="flex items-center bg-surface-container-lowest rounded-full p-1 shadow-xs">
<button aria-label="Kurangi jumlah" class="w-8 h-8 rounded-full flex items-center justify-center hover:bg-surface-container text-on-surface transition-colors" onclick="changeQuantity(-1)" type="button">
<span class="material-symbols-outlined text-base">remove</span>
</button>
<input class="w-12 text-center bg-transparent font-stock-counter text-stock-counter text-on-surface focus:outline-none" id="quantityInput" max="140" min="1" readonly="" type="number" value="1"/>
<button aria-label="Tambah jumlah" class="w-8 h-8 rounded-full flex items-center justify-center hover:bg-surface-container text-on-surface transition-colors" onclick="changeQuantity(1)" type="button">
<span class="material-symbols-outlined text-base">add</span>
</button>
</div>
<span class="font-label-md text-label-md text-on-surface-variant">Karpet</span>
</div>
</div>
<!-- Tombol Aksi Utama: Add to Cart & Beli Sekarang -->
<div class="flex flex-col sm:flex-row items-stretch gap-3 mb-6">
<button class="flex-1 min-h-[48px] px-6 py-3 rounded-full bg-surface-container-lowest hover:bg-surface-container-high text-primary font-label-lg text-label-lg font-bold shadow-sm transition-all flex items-center justify-center gap-2 ring-1 ring-primary/20" onclick="addToCartAnimation()" type="button">
<span class="material-symbols-outlined text-xl">add_shopping_cart</span>
<span>Tambah ke Keranjang</span>
</button>
<button class="flex-1 min-h-[48px] px-6 py-3 rounded-full bg-primary-container hover:bg-primary-fixed-dim text-on-primary-container font-label-lg text-label-lg font-bold shadow-md transition-all flex items-center justify-center gap-2 transform active:scale-95" onclick="directCheckout()" type="button">
<span class="material-symbols-outlined text-xl" style="font-variation-settings: 'FILL' 1;">bolt</span>
<span>Beli Sekarang (Kirim Hari Ini)</span>
</button>
</div>
<!-- Box Keunggulan Layanan Ekosistem Bang Zul -->
<div class="grid grid-cols-1 sm:grid-cols-3 gap-3 p-4 rounded-2xl bg-surface-container-lowest shadow-sm">
<div class="flex items-start gap-3">
<span class="p-2 rounded-xl bg-secondary-container text-on-secondary-container">
<span class="material-symbols-outlined text-lg" style="font-variation-settings: 'FILL' 1;">verified_user</span>
</span>
<div>
<h2 class="font-label-md text-label-md text-on-surface font-bold">Garansi Retak 100%</h2>
<p class="font-body-sm text-body-sm text-on-surface-variant">Jika ada telur retak saat dibuka, kurir ganti langsung di tempat tanpa ribet.</p>
</div>
</div>
<div class="flex items-start gap-3">
<span class="p-2 rounded-xl bg-primary-fixed text-on-primary-fixed">
<span class="material-symbols-outlined text-lg" style="font-variation-settings: 'FILL' 1;">balance</span>
</span>
<div>
<h2 class="font-label-md text-label-md text-on-surface font-bold">Timbangan Tera Pas</h2>
<p class="font-body-sm text-body-sm text-on-surface-variant">Ditimbang ulang di depan Anda dengan timbangan digital terkalibrasi resmi.</p>
</div>
</div>
<div class="flex items-start gap-3">
<span class="p-2 rounded-xl bg-tertiary-fixed text-on-tertiary-fixed">
<span class="material-symbols-outlined text-lg" style="font-variation-settings: 'FILL' 1;">two_wheeler</span>
</span>
<div>
<h2 class="font-label-md text-label-md text-on-surface font-bold">Kurir Motor Khusus</h2>
<p class="font-body-sm text-body-sm text-on-surface-variant">Kardus bersekat peredam guncangan jalanan berbukit Tanggamus.</p>
</div>
</div>
</div>
</div>
</div>
<!-- TABS INFORMASI MENDALAM -->
<div class="w-full bg-surface-container-lowest rounded-2xl p-6 shadow-sm mb-12" id="infoTabsContainer">
<!-- Navigasi Tab Header -->
<div class="flex items-center gap-2 border-b border-surface-container-highest pb-4 overflow-x-auto whitespace-nowrap mb-6">
<button class="tab-btn active-tab px-4 py-2 rounded-full font-label-md text-label-md font-bold bg-primary text-on-primary transition-all flex items-center gap-2" onclick="switchTab('desc', this)" type="button">
<span class="material-symbols-outlined text-sm">description</span>
<span>Deskripsi Lengkap &amp; Kualitas</span>
</button>
<button class="tab-btn px-4 py-2 rounded-full font-label-md text-label-md font-bold text-on-surface-variant hover:text-on-surface hover:bg-surface-container transition-all flex items-center gap-2" onclick="switchTab('shipping', this)" type="button">
<span class="material-symbols-outlined text-sm">local_shipping</span>
<span>Pengiriman &amp; Garansi Tanggamus</span>
</button>
<button class="tab-btn px-4 py-2 rounded-full font-label-md text-label-md font-bold text-on-surface-variant hover:text-on-surface hover:bg-surface-container transition-all flex items-center gap-2" id="tab-ulasan-btn" onclick="switchTab('reviews', this)" type="button">
<span class="material-symbols-outlined text-sm">reviews</span>
<span>Ulasan Pembeli (248)</span>
</button>
</div>
<!-- Tab Isi 1: Deskripsi Lengkap -->
<div class="tab-pane flex flex-col gap-6" id="tab-desc">
<div class="grid grid-cols-1 md:grid-cols-2 gap-6">
<div class="space-y-4">
<h3 class="font-headline-sm text-headline-sm text-on-surface font-bold">Kualitas Telur Ayam Ras Dari Peternak Lokal Tanggamus</h3>
<p class="font-body-md text-body-md text-on-surface-variant leading-relaxed">
              Telur yang kami distribusikan berasal dari peternakan ayam ras petelur sistem semi-terbuka di dataran tinggi Gisting dan Talang Padang dengan sirkulasi udara sejuk alami pegunungan. Ayam diberi pakan campuran jagung giling lokal bermutu tinggi tanpa hormon pertumbuhan berlebih, menghasilkan kuning telur dengan kekentalan tinggi (*Haugh Unit &gt; 80*).
            </p>
<ul class="space-y-2.5 font-body-sm text-body-sm text-on-surface-variant">
<li class="flex items-center gap-2">
<span class="material-symbols-outlined text-secondary text-base" style="font-variation-settings: 'FILL' 1;">check_circle</span>
<span><strong>Cangkang Tebal:</strong> Kaya kalsium alami, tahan tekanan tumpuk hingga 5 tingkat tanpa retak.</span>
</li>
<li class="flex items-center gap-2">
<span class="material-symbols-outlined text-secondary text-base" style="font-variation-settings: 'FILL' 1;">check_circle</span>
<span><strong>Aroma Segar:</strong> Tidak berbau amis menyengat karena dipanen harian dan disortir kering tanpa dicuci air kotor.</span>
</li>
<li class="flex items-center gap-2">
<span class="material-symbols-outlined text-secondary text-base" style="font-variation-settings: 'FILL' 1;">check_circle</span>
<span><strong>Kuning Telur Menonjol:</strong> Saat diceplok di wajan, kuning telur berdiri bulat tegak dan tidak mudah pecah bercampur putih.</span>
</li>
</ul>
</div>
<div class="bg-surface-container-low p-5 rounded-2xl flex flex-col justify-between">
<h4 class="font-headline-sm text-headline-sm text-on-surface font-bold mb-3 flex items-center gap-2">
<span class="material-symbols-outlined text-primary">tips_and_updates</span>
              Petunjuk Penyimpanan Tahan 30 Hari
            </h4>
<div class="space-y-3 font-body-sm text-body-sm text-on-surface-variant">
<p><strong>1. Posisi Meletakkan:</strong> Letakkan bagian telur yang tumpul di atas dan bagian runcing di bawah agar kantung udara tetap stabil.</p>
<p><strong>2. Jangan Dicuci Dahulu:</strong> Cuci telur hanya saat akan dimasak. Mencuci telur sebelum disimpan merusak lapisan pelindung alami (*kutikula*) cangkang.</p>
<p><strong>3. Suhu Ruang vs Kulkas:</strong> Di suhu ruang sejuk Tanggamus bertahan 14-21 hari. Di rak pendingin suhu 4°C-7°C awet segar hingga 35 hari.</p>
</div>
<div class="mt-4 pt-3 border-t border-surface-container-highest flex items-center justify-between text-label-sm font-label-sm text-secondary">
<span>Grade Laboratorium: Bebas Residu Kimia</span>
<span class="font-bold">Uji Lab 2024</span>
</div>
</div>
</div>
</div>
<!-- Tab Isi 2: Pengiriman & Garansi -->
<div class="tab-pane hidden flex-col gap-6" id="tab-shipping">
<div class="grid grid-cols-1 md:grid-cols-3 gap-4 mb-4">
<div class="p-4 rounded-xl bg-surface-container-low">
<span class="material-symbols-outlined text-primary text-2xl mb-1">alarm</span>
<h4 class="font-label-lg text-label-lg font-bold text-on-surface mb-1">Kloter Kurir Pagi (08.00 WIB)</h4>
<p class="font-body-sm text-body-sm text-on-surface-variant">Untuk order yang masuk sebelum pukul 07.30 WIB. Tiba di rumah sebelum waktu masak siang.</p>
</div>
<div class="p-4 rounded-xl bg-surface-container-low">
<span class="material-symbols-outlined text-primary text-2xl mb-1">schedule</span>
<h4 class="font-label-lg text-label-lg font-bold text-on-surface mb-1">Kloter Kurir Sore (14.00 WIB)</h4>
<p class="font-body-sm text-body-sm text-on-surface-variant">Untuk order siang hingga pukul 13.30 WIB. Cocok untuk warung martabak dan lauk makan malam.</p>
</div>
<div class="p-4 rounded-xl bg-surface-container-low">
<span class="material-symbols-outlined text-secondary text-2xl mb-1" style="font-variation-settings: 'FILL' 1;">local_shipping</span>
<h4 class="font-label-lg text-label-lg font-bold text-on-surface mb-1">Zona Bebas Ongkir (Min. 2 Karpet)</h4>
<p class="font-body-sm text-body-sm text-on-surface-variant">Kecamatan Gisting, Talang Padang, Gunung Alip, Wonosobo, Kota Agung &amp; Pugung.</p>
</div>
</div>
<div class="bg-error-container/20 p-4 rounded-xl flex items-start gap-3">
<span class="material-symbols-outlined text-error text-xl mt-0.5">policy</span>
<div>
<h4 class="font-label-lg text-label-lg text-on-surface font-bold">Prosedur Klaim Telur Pecah / Retak Instan</h4>
<p class="font-body-sm text-body-sm text-on-surface-variant mt-0.5">
              Periksa karpet telur saat kurir Bang Zul tiba di alamat Anda. Jika ditemukan butir telur yang retak/pecah akibat perjalanan jalan bergelombang, kurir membawa stok cadangan di keranjang motor dan akan <strong>langsung mengganti butir yang rusak seketika</strong> tanpa pengisian formulir rumit.
            </p>
</div>
</div>
</div>
<!-- Tab Isi 3: Ulasan Pembeli -->
<div class="tab-pane hidden flex-col gap-6" id="tab-reviews">
<!-- Ringkasan Nilai -->
<div class="flex flex-col sm:flex-row items-center gap-6 p-4 rounded-xl bg-surface-container-low">
<div class="text-center sm:text-left">
<span class="font-display-lg text-display-lg text-primary font-black leading-none">4.9</span>
<div class="flex items-center justify-center sm:justify-start gap-0.5 text-primary-container my-1">
<span class="material-symbols-outlined text-base" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-base" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-base" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-base" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-base" style="font-variation-settings: 'FILL' 1;">star</span>
</div>
<span class="font-label-sm text-label-sm text-on-surface-variant">Berdasarkan 248 Penilaian Asli</span>
</div>
<!-- Batang Kepuasan Pembeli -->
<div class="flex-1 w-full space-y-1.5">
<div class="flex items-center gap-2 text-label-sm font-label-sm">
<span class="w-12 text-on-surface">Bintang 5</span>
<div class="flex-1 h-2 rounded-full bg-surface-container-highest overflow-hidden">
<div class="h-full bg-primary-container w-[92%]"></div>
</div>
<span class="w-8 text-right text-on-surface-variant">228</span>
</div>
<div class="flex items-center gap-2 text-label-sm font-label-sm">
<span class="w-12 text-on-surface">Bintang 4</span>
<div class="flex-1 h-2 rounded-full bg-surface-container-highest overflow-hidden">
<div class="h-full bg-primary-container w-[6%]"></div>
</div>
<span class="w-8 text-right text-on-surface-variant">16</span>
</div>
<div class="flex items-center gap-2 text-label-sm font-label-sm">
<span class="w-12 text-on-surface">Bintang 3</span>
<div class="flex-1 h-2 rounded-full bg-surface-container-highest overflow-hidden">
<div class="h-full bg-primary-container w-[2%]"></div>
</div>
<span class="w-8 text-right text-on-surface-variant">4</span>
</div>
</div>
</div>
<!-- Daftar Komentar Testimoni Pelanggan -->
<div class="space-y-4">
<!-- Ulasan 1: Pemilik Usaha Martabak -->
<div class="p-4 rounded-xl bg-surface-container-low/60 flex flex-col gap-2.5">
<div class="flex items-center justify-between">
<div class="flex items-center gap-2.5">
<div class="w-9 h-9 rounded-full bg-primary-fixed flex items-center justify-center font-bold text-on-primary-fixed font-label-md text-label-md">
                  HM
                </div>
<div>
<h4 class="font-label-lg text-label-lg font-bold text-on-surface">Haji Mansyur (Martabak Bangka Gisting)</h4>
<p class="font-label-sm text-label-sm text-on-surface-variant">Langganan 15 Karpet/Minggu • Gisting Bawah</p>
</div>
</div>
<span class="text-tertiary font-label-sm text-label-sm">2 hari lalu</span>
</div>
<div class="flex items-center text-primary-container">
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
</div>
<p class="font-body-md text-body-md text-on-surface">
              "Alhamdulillah adonan martabak telur jadi mekar wangi. Kuning telurnya betul-betul oranye alami, bukan yang encer pucat. Kurir Bang Zul sudah hafal jadwal antar jam 2 siang sebelum buka lapak."
            </p>
</div>
<!-- Ulasan 2: Ibu Rumah Tangga -->
<div class="p-4 rounded-xl bg-surface-container-low/60 flex flex-col gap-2.5">
<div class="flex items-center justify-between">
<div class="flex items-center gap-2.5">
<div class="w-9 h-9 rounded-full bg-secondary-container flex items-center justify-center font-bold text-on-secondary-container font-label-md text-label-md">
                  RW
                </div>
<div>
<h4 class="font-label-lg text-label-lg font-bold text-on-surface">Ibu Rina Wulandari</h4>
<p class="font-label-sm text-label-sm text-on-surface-variant">Pembeli Rumah Tangga • Talang Padang</p>
</div>
</div>
<span class="text-tertiary font-label-sm text-label-sm">Kemarin</span>
</div>
<div class="flex items-center text-primary-container">
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">star</span>
</div>
<p class="font-body-md text-body-md text-on-surface">
              "Pesan 2 karpet buat stok sebulan. Sampai rumah dicek utuh semua cangkangnya, packing kardusnya tebal dan ada lapisan pelindungnya. Anak-anak suka banget diceplok setengah matang rasanya gurih manis."
            </p>
</div>
</div>
</div>
</div>
<!-- CAROUSEL / REKOMENDASI PRODUK LAINNYA -->
<div class="w-full mb-12">
<div class="flex items-end justify-between mb-6">
<div>
<span class="font-label-md text-label-md text-secondary uppercase font-bold tracking-wider">Kombinasi Belanja Favorit</span>
<h2 class="font-headline-lg text-headline-lg text-on-surface font-bold">Produk Telur Lainnya yang Sering Dibeli Bersama</h2>
</div>
<a class="hidden sm:flex items-center gap-1 text-primary font-label-lg text-label-lg font-bold hover:underline" href="#">
<span>Lihat Katalog Lengkap</span>
<span class="material-symbols-outlined text-base">arrow_forward</span>
</a>
</div>
<!-- Grid 4 Kartu Rekomendasi -->
<div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
<!-- Kartu 1: Telur Kampung Asli & Omega-3 -->
<div class="bg-surface-container-lowest rounded-2xl p-4 shadow-sm hover:shadow-md transition-shadow flex flex-col justify-between group">
<div>
<div class="relative w-full aspect-4/3 rounded-xl overflow-hidden bg-surface-container-low mb-3">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" data-alt="Handcrafted bamboo woven basket filled with speckled authentic free-range village chicken eggs resting on rustic straw bed in a sunlit Indonesian farm patio in Tanggamus." src="https://lh3.googleusercontent.com/aida-public/AB6AXuDwc4nHKpKDEKKH50cm_o9fbV1VeIm85CxEvQhAEHaQL2K2m-WbaX3FPdwDLQdohKInX9Fa1HiR3QNIy3oOTRB4MNiOoNeaKLUb5lM7Fe5xvWsKZums0FjFFD1iJMXDTJd7HNx4JFLYrUpJ_tI4EKNPE70ApRAoiK5x7SNmfbwH0n3tMlyFZ09Ixq-pTOPr5v3FBqTonjCHA12-AADnQMYY5e1l3iu4t4xPC17ih7g"/>
<span class="absolute top-2 left-2 px-2 py-0.5 rounded-full bg-secondary text-on-secondary font-label-sm text-label-sm font-semibold">
                Omega-3 Alami
              </span>
</div>
<h3 class="font-headline-sm text-headline-sm text-on-surface font-bold group-hover:text-primary transition-colors">
              Telur Ayam Kampung Asli
            </h3>
<p class="font-body-sm text-body-sm text-on-surface-variant line-clamp-2 mt-1">
              Dipelihara liar di kebun kopi Gisting, bebas bahan kimia, kuning telur oranye tua.
            </p>
</div>
<div class="mt-4 pt-3 border-t border-surface-container-highest flex items-center justify-between">
<div>
<span class="font-label-sm text-label-sm text-on-surface-variant block">Isi 10 Butir</span>
<span class="font-headline-sm text-headline-sm text-primary font-bold">Rp 28.000</span>
</div>
<button aria-label="Tambah Telur Ayam Kampung" class="w-10 h-10 rounded-full bg-primary-container text-on-primary-container flex items-center justify-center hover:bg-primary-fixed-dim transition-colors shadow-xs" onclick="alert('Telur Ayam Kampung ditambahkan ke keranjang belanja');" type="button">
<span class="material-symbols-outlined text-lg">add_shopping_cart</span>
</button>
</div>
</div>
<!-- Kartu 2: Telur Bebek Tambak Masir -->
<div class="bg-surface-container-lowest rounded-2xl p-4 shadow-sm hover:shadow-md transition-shadow flex flex-col justify-between group">
<div>
<div class="relative w-full aspect-4/3 rounded-xl overflow-hidden bg-surface-container-low mb-3">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" data-alt="Raw large fresh duck eggs with light blue-green shells in a vintage wooden produce crate at traditional market stall in South Sumatra, crisp textures under morning ambient light." src="https://lh3.googleusercontent.com/aida-public/AB6AXuAsjALzzTvssbY8-fMzd0avJOAVpnHsFvRIJTDfxcKE7KTilcFq6_AoE6Dfc7ijvFad_5ldr0p27Og0n5fPPY9_BFqiTJ3wf6S17lXyBqXtvQwl-HEraUumEICdRKQShD_FOX7SVpe4M3lg5p0XV_UZLwqW20M6vJF-7LXQAtnHoKTHGnVJQR6VjVeFjLyQVEMfox3BwQGGIJ7dDF4-Tep3VIoCfmQLKaZiun4YNNg"/>
<span class="absolute top-2 left-2 px-2 py-0.5 rounded-full bg-primary text-on-primary font-label-sm text-label-sm font-semibold">
                Cangkang Biru Tambak
              </span>
</div>
<h3 class="font-headline-sm text-headline-sm text-on-surface font-bold group-hover:text-primary transition-colors">
              Telur Bebek Mentah Super
            </h3>
<p class="font-body-sm text-body-sm text-on-surface-variant line-clamp-2 mt-1">
              Telur bebek tambak pesisir Kota Agung. Gurih berlemak tebal, sangat cocok untuk martabak gurih.
            </p>
</div>
<div class="mt-4 pt-3 border-t border-surface-container-highest flex items-center justify-between">
<div>
<span class="font-label-sm text-label-sm text-on-surface-variant block">Isi 10 Butir</span>
<span class="font-headline-sm text-headline-sm text-primary font-bold">Rp 30.000</span>
</div>
<button aria-label="Tambah Telur Bebek" class="w-10 h-10 rounded-full bg-primary-container text-on-primary-container flex items-center justify-center hover:bg-primary-fixed-dim transition-colors shadow-xs" onclick="alert('Telur Bebek Tambak ditambahkan ke keranjang belanja');" type="button">
<span class="material-symbols-outlined text-lg">add_shopping_cart</span>
</button>
</div>
</div>
<!-- Kartu 3: Telur Puyuh Gurih -->
<div class="bg-surface-container-lowest rounded-2xl p-4 shadow-sm hover:shadow-md transition-shadow flex flex-col justify-between group">
<div>
<div class="relative w-full aspect-4/3 rounded-xl overflow-hidden bg-surface-container-low mb-3">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" data-alt="Abundant speckled brown and cream spotted fresh quail eggs piled neatly inside a small wooden market box on a burlap cloth surface." src="https://lh3.googleusercontent.com/aida-public/AB6AXuAblf7ZGdIAw2xENabijoj2FzPTICVH_4shqoXov1hLGYWUdT3VMElv0fkebNTBTykIByv3V_H4xHU5FnNKHjjj4o8Sr9xVtijHPrmLCfeuKMjcZV5Yc0JPzqI57i9Nh5SxKegHhnjGnzXVwurz9Bf5A914JI_pBZGbYeWrNcyQv1LkDYv6Lxa4ATxM29CDyrtX__YRCGjgFxqdc6Qd_RHT9T_6cg3t0fhB9J4-MKw"/>
<span class="absolute top-2 left-2 px-2 py-0.5 rounded-full bg-tertiary text-on-tertiary font-label-sm text-label-sm font-semibold">
                Puyuh Peternak Lokal
              </span>
</div>
<h3 class="font-headline-sm text-headline-sm text-on-surface font-bold group-hover:text-primary transition-colors">
              Telur Puyuh Segar (50 Butir)
            </h3>
<p class="font-body-sm text-body-sm text-on-surface-variant line-clamp-2 mt-1">
              Dipanen harian dari Talang Padang. Bersih, cangkang kokoh, favorit untuk sup dan bekal anak.
            </p>
</div>
<div class="mt-4 pt-3 border-t border-surface-container-highest flex items-center justify-between">
<div>
<span class="font-label-sm text-label-sm text-on-surface-variant block">Isi 50 Butir (±500 gr)</span>
<span class="font-headline-sm text-headline-sm text-primary font-bold">Rp 22.000</span>
</div>
<button aria-label="Tambah Telur Puyuh" class="w-10 h-10 rounded-full bg-primary-container text-on-primary-container flex items-center justify-center hover:bg-primary-fixed-dim transition-colors shadow-xs" onclick="alert('Telur Puyuh Segar ditambahkan ke keranjang belanja');" type="button">
<span class="material-symbols-outlined text-lg">add_shopping_cart</span>
</button>
</div>
</div>
<!-- Kartu 4: Telur Asin Rempah Masir -->
<div class="bg-surface-container-lowest rounded-2xl p-4 shadow-sm hover:shadow-md transition-shadow flex flex-col justify-between group">
<div>
<div class="relative w-full aspect-4/3 rounded-xl overflow-hidden bg-surface-container-low mb-3">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" data-alt="Cooked Indonesian salted duck egg cut in half revealing a sandy oily vibrant red-orange yolk with delicate white shell against traditional woven banana leaf mat." src="https://lh3.googleusercontent.com/aida-public/AB6AXuCSD9ysymcC6PFz_rCFfeRJl5LlXJaBeZigF1qs7Xml409yWcgHqIxEdo-9WHYTCRUJ5kZ0dZ_xJFz5LTyMi0XMRimOWIA3ymfXMMYfvHp16TT4itPKE8lRELyYQu5B66LVHgxnPOqxC4sZVbOnuvmSLwsH70FeJKrlY7CRp26lJtGzRBK06Qxk_OKQyOYzv62fSCqJom-LIyXL2SlxJZzNP43J0I8Qp4LlJPa3Jkg"/>
<span class="px-2 py-0.5 rounded-full bg-secondary-container text-on-secondary-container font-label-sm text-label-sm font-semibold absolute top-2 left-2">
                Siap Makan Masir
              </span>
</div>
<h3 class="font-headline-sm text-headline-sm text-on-surface font-bold group-hover:text-primary transition-colors">
              Telur Asin Rempah Matang
            </h3>
<p class="font-body-sm text-body-sm text-on-surface-variant line-clamp-2 mt-1">
              Proses fermentasi batu bata &amp; rempah alami 14 hari. Kuning telur berminyak legit dan tidak asin menusuk.
            </p>
</div>
<div class="mt-4 pt-3 border-t border-surface-container-highest flex items-center justify-between">
<div>
<span class="font-label-sm text-label-sm text-on-surface-variant block">Paket 6 Butir Matang</span>
<span class="font-headline-sm text-headline-sm text-primary font-bold">Rp 24.000</span>
</div>
<button aria-label="Tambah Telur Asin" class="w-10 h-10 rounded-full bg-primary-container text-on-primary-container flex items-center justify-center hover:bg-primary-fixed-dim transition-colors shadow-xs" onclick="alert('Telur Asin Rempah ditambahkan ke keranjang belanja');" type="button">
<span class="material-symbols-outlined text-lg">add_shopping_cart</span>
</button>
</div>
</div>
</div>
</div>
</div>
<!-- INTERAKSI JAVASCRIPT INLINE UNTUK PDP -->
<script>
    // State lokal halaman detail
    let currentQuantity = 1;
    let baseUnitPrice = 52000;
    let baseWeightPerUnit = 1.85;

    // Ganti Gambar Utama dari Thumbnail
    function updateMainImage(srcUrl, clickedBtn) {
      const mainImg = document.getElementById('mainProductImage');
      if (mainImg) {
        mainImg.src = srcUrl;
      }
      // Reset styling thumbnail
      document.querySelectorAll('.thumb-btn').forEach(btn => {
        btn.classList.remove('ring-2', 'ring-primary-container', 'opacity-100');
        btn.classList.add('opacity-75');
      });
      clickedBtn.classList.remove('opacity-75');
      clickedBtn.classList.add('ring-2', 'ring-primary-container', 'opacity-100');
    }

    // Pemilihan Varian Kemasan
    function selectVariant(buttonElement) {
      // Update styling tombol varian
      document.querySelectorAll('.variant-btn').forEach(btn => {
        btn.classList.remove('ring-2', 'ring-primary-container', 'bg-surface-container-lowest');
        btn.classList.add('bg-surface-container-low');
        const indicator = btn.querySelector('.variant-indicator');
        if (indicator) indicator.classList.add('hidden');
      });

      buttonElement.classList.add('ring-2', 'ring-primary-container', 'bg-surface-container-lowest');
      buttonElement.classList.remove('bg-surface-container-low');
      const activeIndicator = buttonElement.querySelector('.variant-indicator');
      if (activeIndicator) activeIndicator.classList.remove('hidden');

      // Ambil data harga dan estimasi timbangan
      baseUnitPrice = parseInt(buttonElement.getAttribute('data-price'), 10);
      baseWeightPerUnit = parseFloat(buttonElement.getAttribute('data-weight'));
      
      updateCalculatedPrice();
    }

    // Ubah Kuantitas Stepper
    function changeQuantity(delta) {
      currentQuantity = Math.max(1, Math.min(140, currentQuantity + delta));
      const input = document.getElementById('quantityInput');
      if (input) input.value = currentQuantity;
      updateCalculatedPrice();
    }

    function updateCalculatedPrice() {
      const totalPrice = baseUnitPrice * currentQuantity;
      const totalWeight = (baseWeightPerUnit * currentQuantity).toFixed(2);
      
      const priceDisplay = document.getElementById('priceDisplay');
      if (priceDisplay) {
        priceDisplay.textContent = 'Rp ' + totalPrice.toLocaleString('id-ID');
      }

      const weightSummary = document.getElementById('weightSummary');
      if (weightSummary) {
        weightSummary.textContent = 'Estimasi total timbangan: ~' + totalWeight + ' kg';
      }
    }

    // Alih Tab Informasi
    function switchTab(tabId, clickedBtn) {
      // Sembunyikan semua tab pane
      document.querySelectorAll('.tab-pane').forEach(pane => {
        pane.classList.add('hidden');
        pane.classList.remove('flex');
      });

      // Tampilkan tab aktif
      const targetPane = document.getElementById('tab-' + tabId);
      if (targetPane) {
        targetPane.classList.remove('hidden');
        targetPane.classList.add('flex');
      }

      // Reset style tombol tab
      document.querySelectorAll('.tab-btn').forEach(btn => {
        btn.classList.remove('bg-primary', 'text-on-primary');
        btn.classList.add('text-on-surface-variant');
      });

      clickedBtn.classList.remove('text-on-surface-variant');
      clickedBtn.classList.add('bg-primary', 'text-on-primary');
    }

    // Micro-interactions Keranjang & Checkout
    function addToCartAnimation() {
      const qty = currentQuantity;
      alert('Berhasil memasukkan ' + qty + ' Karpet Telur Ayam Ras Super ke keranjang belanja Anda!');
    }

    function directCheckout() {
      const qty = currentQuantity;
      const total = (baseUnitPrice * qty).toLocaleString('id-ID');
      alert('Mengarahkan ke halaman Checkout Pembayaran: Rp ' + total + ' untuk wilayah pengiriman Tanggamus.');
    }
  </script>
</div></main><footer class="w-full bg-surface-container-low mt-16 pt-12 pb-8 text-on-surface-variant"><div class="max-w-7xl mx-auto px-4 lg:px-8 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8"><div class="space-y-3"><div class="flex items-center gap-2"><img alt="Logo Bang Zul Egg Market" class="h-7 w-auto object-contain" src="https://lh3.googleusercontent.com/aida/ALJJyrAvuhgJbL1OqXYnorOpflEwk9ch2RB3i3nIpJf2khBHtFUraZYLjA49xnoYr5_XpY1inx_yvUKDG-f5ULodcAC4hoBl9QYWujU07wAAJsvNI88PefRZRNH2SgRzcvtvfP9LlMDgvobQRRrHxWwLlWY8MQoR1CS4kennwXqXJqn5PR3R5zkf-p4q0eleDblVHlCAtE__Wj8FbqU6db9zlBw02jnLdLpow_xGCN8RF4es"/><span class="font-headline-sm text-headline-sm text-primary">UD. Bang Zul Egg Market</span></div><p class="font-body-sm text-body-sm">Pusat distribusi telur segar langsung dari peternak binaan lokal Tanggamus. Menjaga kualitas kesegaran cangkang utuh dan timbangan presisi terpercaya.</p><div class="flex items-center gap-2 text-secondary font-label-sm text-label-sm"><span class="material-symbols-outlined text-sm">verified</span><span>Garansi Ganti Telur Pecah 100% Langsung di Tempat</span></div></div><div class="space-y-2"><h3 class="font-headline-sm text-headline-sm text-on-surface">Jam Operasional &amp; Panen</h3><p class="font-body-sm text-body-sm">Pengambilan Telur Kandang: 06.00 - 10.00 WIB</p><p class="font-body-sm text-body-sm">Jadwal Pengiriman Kurir: 08.00 - 18.00 WIB</p><p class="font-body-sm text-body-sm text-secondary font-semibold">Setiap Hari (Senin - Minggu Tetap Buka)</p><p class="font-label-sm text-label-sm text-on-surface-variant pt-1">Wilayah Gisting, Talang Padang, Wonosobo, Kota Agung &amp; Sekitarnya.</p></div><div class="space-y-2"><h3 class="font-headline-sm text-headline-sm text-on-surface">Metode Pembayaran</h3><div class="space-y-1 font-body-sm text-body-sm"><p class="flex items-center gap-1.5"><span class="material-symbols-outlined text-primary text-sm">qr_code_scanner</span>QRIS Seluruh Bank &amp; E-Wallet</p><p class="flex items-center gap-1.5"><span class="material-symbols-outlined text-primary text-sm">account_balance</span>Transfer Bank Lampung / BRI / BCA</p><p class="flex items-center gap-1.5"><span class="material-symbols-outlined text-primary text-sm">payments</span>COD (Bayar Tunai di Tempat saat Timbang)</p></div></div><div class="space-y-2"><h3 class="font-headline-sm text-headline-sm text-on-surface">Komitmen Peternak Lokal</h3><p class="font-body-sm text-body-sm">Mendukung keberlanjutan usaha peternak unggas pedesaan di Kabupaten Tanggamus, Lampung dengan harga adil, timbangan transparan, dan pakan alami bermutu.</p><div class="pt-2"><span class="inline-block px-3 py-1 bg-secondary-container text-on-secondary-container rounded-full font-label-sm text-label-sm">Asli Tanggamus, Segar Bergaransi</span></div></div></div><div class="max-w-7xl mx-auto px-4 lg:px-8 mt-10 pt-4 flex flex-col sm:flex-row items-center justify-between gap-2 font-label-sm text-label-sm text-on-surface-variant"><p>© 2024 UD. Bang Zul Egg Market Tanggamus Lampung. Hak Cipta Dilindungi.</p><p>Dibuat untuk ekosistem niaga agrikultur Kabupaten Tanggamus</p></div></footer></body></html>

<!-- Data Produk dan Stok Bang Zul -->
<!DOCTYPE html>

<html lang="id"><head><meta charset="utf-8"/><meta content="width=device-width, initial-scale=1.0" name="viewport"/><meta content="web_dashboard" name="shell-type"/><link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&amp;family=Plus+Jakarta+Sans:wght@700;800&amp;display=swap" rel="stylesheet"/><link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/><style>@layer base{html,body{margin:0;padding:0;}body{overscroll-behavior:none;}main>:first-child{margin-top:0!important;}main>:last-child{margin-bottom:0!important;}}::-webkit-scrollbar{display:none;}</style><script src="https://cdn.tailwindcss.com"></script><script id="tailwind-config">tailwind.config={darkMode:"class",theme:{extend:{"colors":{"primary":"#835500","secondary-fixed":"#a3f69c","tertiary":"#556158","surface-container":"#f0eded","on-primary-container":"#644000","secondary-fixed-dim":"#88d982","on-surface-variant":"#524534","outline-variant":"#d7c3ae","on-tertiary-container":"#3e4a41","on-error-container":"#93000a","on-secondary-fixed":"#002204","tertiary-container":"#acb9ae","surface-container-high":"#eae7e7","on-primary":"#ffffff","tertiary-fixed-dim":"#bdcabe","error-container":"#ffdad6","on-tertiary":"#ffffff","on-secondary":"#ffffff","on-secondary-container":"#217128","on-background":"#1b1c1c","surface":"#fcf9f8","inverse-primary":"#ffb955","inverse-on-surface":"#f3f0f0","primary-container":"#f5a623","surface-container-lowest":"#ffffff","on-error":"#ffffff","inverse-surface":"#303030","error":"#ba1a1a","primary-fixed":"#ffddb4","background":"#fcf9f8","on-tertiary-fixed":"#131e17","on-secondary-fixed-variant":"#005312","on-primary-fixed":"#291800","surface-tint":"#835500","secondary-container":"#a0f399","surface-dim":"#dcd9d9","tertiary-fixed":"#d9e6da","surface-container-low":"#f6f3f2","surface-variant":"#e4e2e1","on-tertiary-fixed-variant":"#3e4a41","primary-fixed-dim":"#ffb955","outline":"#857462","on-primary-fixed-variant":"#633f00","surface-bright":"#fcf9f8","secondary":"#1b6d24","surface-container-highest":"#e4e2e1","on-surface":"#1b1c1c"},"borderRadius":{"DEFAULT":"0.25rem","lg":"0.5rem","xl":"0.75rem","full":"9999px"},"spacing":{"gutter":"1rem","space-xl":"2rem","margin":"1rem","space-xs":"0.25rem","space-sm":"0.5rem","gutter-desktop":"1.5rem","space-lg":"1.5rem","margin-desktop":"2.5rem","space-md":"1rem"},"fontFamily":{"label-lg":["Inter"],"price-display":["Plus Jakarta Sans"],"display-lg-mobile":["Plus Jakarta Sans"],"stock-counter":["Inter"],"headline-sm":["Plus Jakarta Sans"],"body-md":["Inter"],"headline-lg":["Plus Jakarta Sans"],"label-sm":["Inter"],"display-lg":["Plus Jakarta Sans"],"body-sm":["Inter"],"label-md":["Inter"],"body-lg":["Inter"],"headline-lg-mobile":["Plus Jakarta Sans"],"headline-md":["Plus Jakarta Sans"]},"fontSize":{"label-lg":["14px",{"lineHeight":"20px","fontWeight":"600"}],"price-display":["22px",{"lineHeight":"28px","letterSpacing":"-0.02em","fontWeight":"800"}],"display-lg-mobile":["30px",{"lineHeight":"38px","letterSpacing":"-0.01em","fontWeight":"800"}],"stock-counter":["18px",{"lineHeight":"24px","letterSpacing":"0.01em","fontWeight":"700"}],"headline-sm":["16px",{"lineHeight":"24px","fontWeight":"700"}],"body-md":["14px",{"lineHeight":"22px","fontWeight":"400"}],"headline-lg":["28px",{"lineHeight":"36px","letterSpacing":"-0.01em","fontWeight":"700"}],"label-sm":["11px",{"lineHeight":"14px","letterSpacing":"0.02em","fontWeight":"600"}],"display-lg":["40px",{"lineHeight":"48px","letterSpacing":"-0.02em","fontWeight":"800"}],"body-sm":["12px",{"lineHeight":"18px","fontWeight":"400"}],"label-md":["12px",{"lineHeight":"16px","fontWeight":"600"}],"body-lg":["16px",{"lineHeight":"26px","fontWeight":"400"}],"headline-lg-mobile":["22px",{"lineHeight":"30px","letterSpacing":"0em","fontWeight":"700"}],"headline-md":["20px",{"lineHeight":"28px","fontWeight":"700"}]}}}};</script></head><body class="bg-surface font-body-md text-on-surface antialiased min-h-screen selection:bg-primary-container selection:text-on-primary-container"><aside class="fixed left-0 top-0 h-full w-72 bg-surface-container-low shadow-[0_1px_8px_rgba(0,0,0,0.04)] z-50 flex flex-col justify-between select-none"><div class="flex flex-col"><div class="px-space-lg pt-space-lg pb-space-md"><div class="flex items-center gap-space-sm"><div class="w-10 h-10 rounded-xl bg-primary-container flex items-center justify-center text-on-primary-container shadow-[0_4px_20px_-2px_rgba(245,166,35,0.25)]"><span class="material-symbols-outlined text-[24px]">egg</span></div><div><span class="font-headline-sm text-headline-sm text-on-surface block tracking-tight">Bang Zul Eggs</span><span class="font-label-sm text-label-sm text-on-surface-variant block">Portal Penjual &amp; Admin</span></div></div><div class="mt-space-md p-space-sm rounded-xl bg-secondary-container/40 flex items-center gap-space-xs"><span class="w-2 h-2 rounded-full bg-secondary animate-pulse"></span><div class="overflow-hidden"><span class="font-label-sm text-label-sm text-on-secondary-container truncate block">Kandang Utama Lereng Gisting (Stok Live)</span></div></div></div><div class="px-space-md"><span class="font-label-sm text-label-sm text-outline uppercase tracking-wider px-space-sm mb-space-xs block">Menu Utama</span><nav class="flex flex-col gap-1" data-active-classes="bg-primary-container text-on-primary-container font-headline-sm font-bold shadow-[0_2px_8px_rgba(245,166,35,0.2)]"><a class="group flex items-center justify-between px-space-sm py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface transition-all" data-path="dashboard-utama" href="#"><div class="flex items-center gap-space-sm"><span class="material-symbols-outlined text-[20px] text-tertiary group-hover:text-primary transition-colors">dashboard</span><span class="font-label-lg text-label-lg">Dashboard Utama</span></div></a><a aria-current="page" class="group flex items-center justify-between px-space-sm py-2.5 rounded-xl transition-all bg-primary-container text-on-primary-container font-headline-sm font-bold shadow-[0_2px_8px_rgba(245,166,35,0.2)]" data-path="data-produk-dan-stok" href="#"><div class="flex items-center gap-space-sm"><span class="material-symbols-outlined text-[20px] text-tertiary group-hover:text-primary transition-colors">inventory_2</span><span class="font-label-lg text-label-lg">Data Produk &amp; Stok</span></div></a><a class="group flex items-center justify-between px-space-sm py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface transition-all" data-path="kategori-dan-varian" href="#"><div class="flex items-center gap-space-sm"><span class="material-symbols-outlined text-[20px] text-tertiary group-hover:text-primary transition-colors">category</span><span class="font-label-lg text-label-lg">Kategori &amp; Varian</span></div></a><a class="group flex items-center justify-between px-space-sm py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface transition-all" data-path="data-pesanan-masuk" href="#"><div class="flex items-center gap-space-sm"><span class="material-symbols-outlined text-[20px] text-tertiary group-hover:text-primary transition-colors">shopping_bag</span><span class="font-label-lg text-label-lg">Data Pesanan Masuk</span></div><span class="px-2 py-0.5 rounded-full bg-primary text-on-primary font-label-sm text-label-sm">8</span></a><a class="group flex items-center justify-between px-space-sm py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface transition-all" data-path="verifikasi-pembayaran" href="#"><div class="flex items-center gap-space-sm"><span class="material-symbols-outlined text-[20px] text-tertiary group-hover:text-primary transition-colors">verified</span><span class="font-label-lg text-label-lg">Verifikasi Pembayaran</span></div><span class="px-2 py-0.5 rounded-full bg-primary-container text-on-primary-container font-label-sm text-label-sm">3</span></a><a class="group flex items-center justify-between px-space-sm py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface transition-all" data-path="pengiriman-dan-armada-kurir" href="#"><div class="flex items-center gap-space-sm"><span class="material-symbols-outlined text-[20px] text-tertiary group-hover:text-primary transition-colors">two_wheeler</span><span class="font-label-lg text-label-lg">Pengiriman &amp; Kurir</span></div></a><a class="group flex items-center justify-between px-space-sm py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface transition-all" data-path="pelanggan-dan-mitra-warung" href="#"><div class="flex items-center gap-space-sm"><span class="material-symbols-outlined text-[20px] text-tertiary group-hover:text-primary transition-colors">storefront</span><span class="font-label-lg text-label-lg">Pelanggan &amp; Mitra</span></div></a><a class="group flex items-center justify-between px-space-sm py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface transition-all" data-path="laporan-penjualan" href="#"><div class="flex items-center gap-space-sm"><span class="material-symbols-outlined text-[20px] text-tertiary group-hover:text-primary transition-colors">query_stats</span><span class="font-label-lg text-label-lg">Laporan Penjualan</span></div></a><a class="group flex items-center justify-between px-space-sm py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface transition-all" data-path="pengaturan-toko-dan-rekening" href="#"><div class="flex items-center gap-space-sm"><span class="material-symbols-outlined text-[20px] text-tertiary group-hover:text-primary transition-colors">settings</span><span class="font-label-lg text-label-lg">Pengaturan Toko</span></div></a></nav></div></div><div class="p-space-md flex flex-col gap-space-xs"><div class="flex items-center justify-between px-space-sm py-2 rounded-lg bg-surface-container"><div class="flex items-center gap-space-xs"><span class="w-2.5 h-2.5 rounded-full bg-secondary"></span><span class="font-label-sm text-label-sm text-on-surface-variant">Server Kandang</span></div><span class="font-label-sm text-label-sm font-bold text-secondary">Terhubung</span></div><a class="flex items-center justify-between px-space-sm py-2 rounded-lg text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface transition-colors" data-path="etalase-publik" href="#"><div class="flex items-center gap-space-xs"><span class="material-symbols-outlined text-[18px]">store</span><span class="font-label-md text-label-md">Lihat Toko Publik</span></div><span class="material-symbols-outlined text-[16px]">north_east</span></a></div></aside><div class="pl-72"><header class="fixed top-0 left-72 right-0 h-20 bg-surface/90 backdrop-blur-xl shadow-[0_1px_8px_rgba(0,0,0,0.04)] z-40 flex items-center justify-between px-space-lg"><div class="flex items-center gap-space-md"><div class="flex flex-col"><div class="flex items-center gap-space-xs"><span class="font-headline-sm text-headline-sm text-on-surface font-bold tracking-tight">Bang Zul Egg Market</span><span class="inline-flex items-center px-2 py-0.5 rounded-full bg-primary-fixed text-on-primary-fixed font-label-sm text-label-sm">Sistem Operasional Tanggamus</span></div><div class="flex items-center gap-1.5 mt-0.5"><span class="material-symbols-outlined text-[14px] text-secondary">pin_drop</span><span class="font-body-sm text-body-sm text-on-surface-variant">Pos Operasional: Gisting - Talang Padang - Kota Agung</span></div></div></div><div class="flex items-center gap-space-md"><div class="relative hidden xl:block w-72"><span class="material-symbols-outlined absolute left-3 top-1/2 -translate-y-1/2 text-outline text-[18px]">search</span><input class="w-full pl-9 pr-3 py-1.5 rounded-xl bg-surface-container-lowest text-on-surface placeholder:text-outline font-body-sm text-body-sm focus:outline-none focus:ring-2 focus:ring-primary shadow-sm" placeholder="Cari pesanan, mitra, nota..." type="text"/></div><div class="flex items-center gap-space-xs px-space-sm py-1.5 rounded-full bg-secondary-container/50"><span class="material-symbols-outlined text-secondary text-[16px]">call</span><span class="font-label-sm text-label-sm text-on-secondary-container">CS WA: Aktif</span></div><button class="relative p-2 rounded-full text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface transition-colors"><span class="material-symbols-outlined text-[22px]">notifications</span><span class="absolute top-1 right-1 w-4 h-4 rounded-full bg-error text-on-error font-label-sm text-[10px] flex items-center justify-center font-bold">3</span></button><div class="flex items-center gap-space-sm pl-space-xs"><div class="text-right hidden md:block"><span class="font-label-lg text-label-lg text-on-surface block leading-tight">Bang Zul</span><span class="font-body-sm text-body-sm text-on-surface-variant block leading-tight">Pemilik &amp; Verifikator Kandang</span></div><div class="w-8 h-8 rounded-full bg-primary flex items-center justify-center"><span class="material-symbols-outlined text-on-primary text-[18px]">person</span></div></div></div></header><main class="relative pt-20 bg-surface min-h-[calc(100vh-5rem)] px-space-lg py-space-lg"><div class="flex flex-col w-full pb-space-xl">
<!-- BREADCRUMB & HEADER SECTION -->
<div class="flex flex-col gap-space-sm mb-space-lg">
<div class="flex items-center gap-space-xs text-on-surface-variant font-label-md text-label-md">
<span class="hover:text-primary cursor-pointer transition-colors">Beranda</span>
<span class="material-symbols-outlined text-[14px] text-outline">chevron_right</span>
<span class="hover:text-primary cursor-pointer transition-colors">Inventori &amp; Gudang</span>
<span class="material-symbols-outlined text-[14px] text-outline">chevron_right</span>
<span class="text-primary font-bold">Data Produk &amp; Stok</span>
</div>
<div class="flex flex-col xl:flex-row xl:items-center justify-between gap-space-md mt-1">
<div>
<h1 class="font-headline-lg text-headline-lg text-on-surface tracking-tight">Manajemen Produk &amp; Inventaris Stok Telur</h1>
<p class="font-body-md text-body-md text-on-surface-variant max-w-3xl mt-1">
          Kelola harga pasar harian, pantau pasokan panen lereng Gisting, update stok real-time, dan status ketersediaan komoditas di wilayah Tanggamus.
        </p>
</div>
<!-- Quick Action Buttons -->
<div class="flex flex-wrap items-center gap-space-sm">
<button class="px-space-md py-2.5 rounded-xl bg-surface-container hover:bg-surface-container-high text-on-surface font-label-lg text-label-lg flex items-center gap-2 shadow-sm transition-all">
<span class="material-symbols-outlined text-[18px] text-tertiary">ios_share</span>
<span>Ekspor Rekap (.XLS)</span>
</button>
<button class="px-space-md py-2.5 rounded-xl bg-surface-container hover:bg-surface-container-high text-on-surface font-label-lg text-label-lg flex items-center gap-2 shadow-sm transition-all group">
<span class="material-symbols-outlined text-[18px] text-secondary group-hover:rotate-180 transition-transform duration-500">sync</span>
<div class="flex flex-col text-left">
<span class="leading-none">Sinkron Timbangan</span>
<span class="font-label-sm text-[10px] text-on-surface-variant mt-0.5">06:15 WIB</span>
</div>
</button>
<button class="px-space-lg py-2.5 rounded-xl bg-primary-container hover:bg-primary-fixed-dim text-on-primary-container font-headline-sm text-headline-sm flex items-center gap-2 shadow-[0_4px_20px_-2px_rgba(245,166,35,0.35)] transition-all transform active:scale-95" onclick="document.getElementById('modalTambahProduk').classList.remove('hidden')">
<span class="material-symbols-outlined text-[20px]">add_circle</span>
<span>+ Tambah Varian Telur</span>
</button>
</div>
</div>
</div>
<!-- KPI SUMMARY STATS CARDS (4-GRID) -->
<div class="grid grid-cols-1 md:grid-cols-2 xl:grid-cols-4 gap-space-md mb-space-lg">
<!-- Stat 1: Total Variasi -->
<div class="p-space-lg rounded-2xl bg-surface-container-lowest shadow-[0_4px_20px_-2px_rgba(245,166,35,0.08)] flex flex-col justify-between relative overflow-hidden">
<div class="flex items-center justify-between">
<span class="font-label-md text-label-md text-on-surface-variant uppercase tracking-wider">Variasi Produk</span>
<div class="w-10 h-10 rounded-xl bg-surface-container flex items-center justify-center text-primary">
<span class="material-symbols-outlined text-[22px]">category</span>
</div>
</div>
<div class="my-space-sm">
<span class="font-display-lg text-display-lg text-on-surface tracking-tight">12 <span class="font-body-md text-body-md text-on-surface-variant font-normal">Varian</span></span>
</div>
<div class="flex items-center gap-space-xs font-label-sm text-label-sm">
<span class="inline-flex items-center px-2 py-0.5 rounded-md bg-secondary-container/60 text-on-secondary-container font-bold">10 Aktif</span>
<span class="text-on-surface-variant">2 Nonaktif (Habis/Musim)</span>
</div>
<div class="absolute -right-4 -bottom-4 w-20 h-20 rounded-full bg-primary/5 pointer-events-none"></div>
</div>
<!-- Stat 2: Total Butir Siap Jual -->
<div class="p-space-lg rounded-2xl bg-surface-container-lowest shadow-[0_4px_20px_-2px_rgba(245,166,35,0.08)] flex flex-col justify-between relative overflow-hidden">
<div class="flex items-center justify-between">
<span class="font-label-md text-label-md text-on-surface-variant uppercase tracking-wider">Total Stok Siap Jual</span>
<div class="w-10 h-10 rounded-xl bg-secondary-container/50 flex items-center justify-center text-secondary">
<span class="material-symbols-outlined text-[22px]">egg_alt</span>
</div>
</div>
<div class="my-space-sm">
<span class="font-display-lg text-display-lg text-on-surface tracking-tight">9.450 <span class="font-body-md text-body-md text-on-surface-variant font-normal">Butir</span></span>
</div>
<div class="flex items-center gap-space-xs font-label-sm text-label-sm text-secondary font-bold">
<span class="material-symbols-outlined text-[16px]">trending_up</span>
<span>+450 butir</span>
<span class="text-on-surface-variant font-normal">(Panen Subuh Gisting)</span>
</div>
<div class="absolute -right-4 -bottom-4 w-20 h-20 rounded-full bg-secondary/5 pointer-events-none"></div>
</div>
<!-- Stat 3: Peringatan Stok Menipis -->
<div class="p-space-lg rounded-2xl bg-surface-container-lowest shadow-[0_4px_20px_-2px_rgba(245,166,35,0.08)] flex flex-col justify-between relative overflow-hidden">
<div class="flex items-center justify-between">
<span class="font-label-md text-label-md text-on-surface-variant uppercase tracking-wider">Peringatan Menipis</span>
<div class="w-10 h-10 rounded-xl bg-error-container/60 flex items-center justify-center text-error">
<span class="material-symbols-outlined text-[22px]">warning</span>
</div>
</div>
<div class="my-space-sm">
<span class="font-display-lg text-display-lg text-error tracking-tight">3 <span class="font-body-md text-body-md text-on-surface-variant font-normal">Komoditas</span></span>
</div>
<div class="flex items-center gap-space-xs font-label-sm text-label-sm">
<span class="inline-flex items-center px-2 py-0.5 rounded-md bg-error-container text-on-error-container font-bold">Perlu Restok Segera</span>
</div>
<div class="absolute -right-4 -bottom-4 w-20 h-20 rounded-full bg-error/5 pointer-events-none"></div>
</div>
<!-- Stat 4: Rata-rata Harga Pasar -->
<div class="p-space-lg rounded-2xl bg-surface-container-lowest shadow-[0_4px_20px_-2px_rgba(245,166,35,0.08)] flex flex-col justify-between relative overflow-hidden">
<div class="flex items-center justify-between">
<span class="font-label-md text-label-md text-on-surface-variant uppercase tracking-wider">Harga Pasar (Karpet)</span>
<div class="w-10 h-10 rounded-xl bg-primary-fixed flex items-center justify-center text-on-primary-fixed">
<span class="material-symbols-outlined text-[22px]">payments</span>
</div>
</div>
<div class="my-space-sm">
<span class="font-price-display text-price-display text-primary tracking-tight">Rp 52.000 <span class="font-body-sm text-body-sm text-on-surface-variant font-normal">/ Tray 30 Btr</span></span>
</div>
<div class="flex items-center justify-between font-label-sm text-label-sm text-on-surface-variant">
<span>Batas Asosiasi Tanggamus:</span>
<span class="font-bold text-on-surface">51.5k - 53k</span>
</div>
<div class="absolute -right-4 -bottom-4 w-20 h-20 rounded-full bg-primary-container/10 pointer-events-none"></div>
</div>
</div>
<!-- CRITICAL STOCK ALERT BANNER -->
<div class="mb-space-lg rounded-2xl bg-primary-fixed/40 p-space-md flex flex-col md:flex-row md:items-center justify-between gap-space-md shadow-sm">
<div class="flex items-start gap-space-sm">
<div class="w-9 h-9 rounded-xl bg-primary-container text-on-primary-container flex items-center justify-center shrink-0 shadow-sm">
<span class="material-symbols-outlined text-[20px]">notifications_active</span>
</div>
<div>
<div class="flex items-center gap-space-xs">
<span class="font-headline-sm text-headline-sm text-on-surface">Perhatian Pasokan Terbatas</span>
<span class="px-2 py-0.2 rounded-full bg-error text-on-error font-label-sm text-[10px] font-bold uppercase">Kritis</span>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant mt-0.5">
<strong>3 Komoditas di bawah ambang aman:</strong> Telur Asin Masir Gisting (Sisa 5 Box), Telur Kampung Herbal MPASI (Sisa 4 Pack), dan Telur Puyuh Segar (Sisa 12 Mika).
        </p>
</div>
</div>
<div class="flex items-center gap-space-xs shrink-0 self-end md:self-auto">
<a class="px-space-md py-2 rounded-xl bg-secondary hover:bg-on-secondary-container text-on-secondary font-label-sm text-label-sm flex items-center gap-1.5 shadow-sm transition-colors" href="https://wa.me/6281234567890" target="_blank">
<span class="material-symbols-outlined text-[16px]">chat</span>
<span>Hubungi Peternak via WA</span>
</a>
<button class="px-space-md py-2 rounded-xl bg-surface-container-lowest hover:bg-surface-container-high text-on-surface font-label-sm text-label-sm transition-colors">
        Catatan Pasokan
      </button>
</div>
</div>
<!-- FILTER & SEARCH PANEL -->
<div class="p-space-md rounded-2xl bg-surface-container-lowest shadow-[0_4px_20px_-2px_rgba(245,166,35,0.06)] flex flex-col gap-space-md mb-space-md">
<!-- Row 1: Search & Controls -->
<div class="flex flex-col lg:flex-row items-stretch lg:items-center justify-between gap-space-sm">
<div class="relative flex-1">
<span class="material-symbols-outlined absolute left-3.5 top-1/2 -translate-y-1/2 text-outline text-[20px]">search</span>
<input class="w-full pl-11 pr-4 py-2.5 rounded-xl bg-surface-container-low text-on-surface placeholder:text-outline font-body-md text-body-md focus:bg-surface-container-lowest focus:ring-2 focus:ring-primary focus:outline-none transition-all" placeholder="Cari telur ayam ras, kode SKU (BZ-...), kemasan tray/mika..." type="text"/>
</div>
<div class="flex flex-wrap items-center gap-space-sm">
<div class="flex items-center gap-2 bg-surface-container-low px-space-sm py-1.5 rounded-xl">
<span class="material-symbols-outlined text-outline text-[18px]">filter_list</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">Stok:</span>
<select class="bg-transparent text-on-surface font-label-sm text-label-sm focus:outline-none cursor-pointer">
<option value="semua">Semua Status Stok</option>
<option value="ready">Ready (&gt;20)</option>
<option value="menipis">Menipis (&lt;10)</option>
<option value="habis">Habis (0)</option>
</select>
</div>
<div class="flex items-center gap-2 bg-surface-container-low px-space-sm py-1.5 rounded-xl">
<span class="material-symbols-outlined text-outline text-[18px]">swap_vert</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">Urutkan:</span>
<select class="bg-transparent text-on-surface font-label-sm text-label-sm focus:outline-none cursor-pointer">
<option value="terbanyak">Stok Terbanyak</option>
<option value="harga-tinggi">Harga Tertinggi</option>
<option value="harga-rendah">Harga Terendah</option>
<option value="update-terbaru">Terakhir Diupdate</option>
</select>
</div>
<button class="px-space-md py-2.5 rounded-xl bg-surface-container hover:bg-surface-container-high text-on-surface font-label-sm text-label-sm flex items-center gap-1.5 transition-colors">
<span class="material-symbols-outlined text-[16px]">price_change</span>
<span>Update Massal Harga</span>
</button>
</div>
</div>
<!-- Row 2: Category Filter Pills -->
<div class="flex items-center gap-space-xs overflow-x-auto pb-1 select-none">
<button class="px-4 py-1.5 rounded-full bg-primary text-on-primary font-label-sm text-label-sm shrink-0 shadow-sm">
        Semua Komoditas (12)
      </button>
<button class="px-4 py-1.5 rounded-full bg-surface-container-low hover:bg-surface-container-high text-on-surface font-label-sm text-label-sm shrink-0 transition-colors">
        Telur Ayam Ras (4)
      </button>
<button class="px-4 py-1.5 rounded-full bg-surface-container-low hover:bg-surface-container-high text-on-surface font-label-sm text-label-sm shrink-0 transition-colors">
        Ayam Kampung &amp; Omega (3)
      </button>
<button class="px-4 py-1.5 rounded-full bg-surface-container-low hover:bg-surface-container-high text-on-surface font-label-sm text-label-sm shrink-0 transition-colors">
        Telur Bebek &amp; Asin Masir (3)
      </button>
<button class="px-4 py-1.5 rounded-full bg-surface-container-low hover:bg-surface-container-high text-on-surface font-label-sm text-label-sm shrink-0 transition-colors">
        Telur Puyuh (2)
      </button>
</div>
</div>
<!-- PRODUCTS & STOCK DATA TABLE -->
<div class="rounded-2xl bg-surface-container-lowest shadow-[0_4px_20px_-2px_rgba(245,166,35,0.08)] overflow-hidden">
<div class="overflow-x-auto">
<table class="w-full text-left border-collapse">
<thead>
<tr class="bg-surface-container-low text-on-surface-variant font-label-md text-label-md uppercase tracking-wider select-none">
<th class="py-space-md px-space-md w-12 text-center">
<input class="w-4 h-4 rounded text-primary focus:ring-primary accent-primary" type="checkbox"/>
</th>
<th class="py-space-md px-space-md">Informasi Varian Telur</th>
<th class="py-space-md px-space-md">Kemasan &amp; Satuan</th>
<th class="py-space-md px-space-md">Harga Jual Pasar</th>
<th class="py-space-md px-space-md">Status &amp; Total Stok</th>
<th class="py-space-md px-space-md text-center">Update Cepat Stok</th>
<th class="py-space-md px-space-md text-center">Toko Pembeli</th>
<th class="py-space-md px-space-md text-center">Aksi</th>
</tr>
</thead>
<tbody class="divide-y divide-surface-container font-body-sm text-body-sm">
<!-- Row 1: Telur Ras Karpet Super -->
<tr class="hover:bg-surface/60 transition-colors group">
<td class="py-space-md px-space-md text-center">
<input class="w-4 h-4 rounded accent-primary" type="checkbox"/>
</td>
<td class="py-space-md px-space-md">
<div class="flex items-center gap-space-sm">
<div class="w-14 h-14 rounded-xl overflow-hidden shrink-0 bg-surface-container shadow-sm">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform" data-alt="Tumpukan telur ayam ras cokelat segar di rak karpet karton di pasar tradisional bernuansa kayu hangat pedesaan Tanggamus" src="https://lh3.googleusercontent.com/aida-public/AB6AXuACK-934zcy8IEaGHzb08S8ubrf08aiIY8gY0pOnfGOyBRNPQatG27u0YHfIbwhY-Jpl6bnfDy9WR9lAGH8X2DFr9JYSlCbRhQWh7V25roHNIo2ga0u8w69nXL1BZ3F3w8VQDMIYfiz2z0PRD__S2JiwfWdTQRSu41FmmLuGVzI4I58FDqDbYrXe6B7PJeJ-ZdaIQ-sw7odzsC2EhnMU7VIqEU_F8eVZWEsl1A7nbA"/>
</div>
<div>
<span class="font-headline-sm text-headline-sm text-on-surface block font-bold">Telur Ayam Ras Super Karpet</span>
<div class="flex items-center gap-1.5 mt-0.5">
<span class="font-label-sm text-label-sm px-1.5 py-0.5 rounded bg-surface-container text-on-surface-variant font-mono">BZ-RAS-01</span>
<span class="font-label-sm text-label-sm text-tertiary font-semibold">Ayam Ras Super</span>
</div>
</div>
</div>
</td>
<td class="py-space-md px-space-md">
<span class="font-label-md text-label-md text-on-surface block">Tray Karton (30 Butir)</span>
<span class="font-body-sm text-body-sm text-outline">±1.9 Kg - 2.0 Kg</span>
</td>
<td class="py-space-md px-space-md">
<div class="flex items-center gap-1.5">
<span class="font-price-display text-headline-sm text-primary font-bold">Rp 52.000</span>
<button class="p-1 rounded-md text-outline hover:text-primary transition-colors" title="Ubah harga">
<span class="material-symbols-outlined text-[16px]">edit</span>
</button>
</div>
<span class="text-[11px] text-on-surface-variant">Grosir &gt;10: Rp 50.500</span>
</td>
<td class="py-space-md px-space-md">
<div class="flex items-center gap-1.5">
<span class="w-2.5 h-2.5 rounded-full bg-secondary"></span>
<span class="font-headline-sm text-headline-sm text-secondary font-bold">140 Karpet</span>
</div>
<span class="font-body-sm text-body-sm text-on-surface-variant">Total 4.200 Butir Siap Angkut</span>
</td>
<td class="py-space-md px-space-md text-center">
<div class="inline-flex items-center bg-surface-container rounded-xl p-1 gap-1 shadow-inner">
<button class="w-7 h-7 rounded-lg bg-surface-container-lowest text-on-surface font-bold hover:bg-surface-container-high transition-colors flex items-center justify-center">-</button>
<input class="w-12 text-center bg-transparent font-stock-counter text-stock-counter text-on-surface font-bold focus:outline-none" type="text" value="140"/>
<button class="w-7 h-7 rounded-lg bg-surface-container-lowest text-on-surface font-bold hover:bg-surface-container-high transition-colors flex items-center justify-center">+</button>
<button class="w-7 h-7 rounded-lg bg-secondary text-on-secondary hover:bg-secondary/90 transition-colors flex items-center justify-center" title="Simpan Stok Cepat">
<span class="material-symbols-outlined text-[16px]">check</span>
</button>
</div>
</td>
<td class="py-space-md px-space-md text-center">
<button class="w-10 h-6 bg-secondary rounded-full relative inline-flex items-center p-0.5 cursor-pointer">
<span class="w-5 h-5 rounded-full bg-surface-container-lowest translate-x-4 shadow-sm transition-transform"></span>
</button>
</td>
<td class="py-space-md px-space-md text-center">
<div class="flex items-center justify-center gap-1">
<button class="p-2 rounded-xl text-on-surface-variant hover:bg-surface-container hover:text-on-surface transition-colors" title="Ubah Detail">
<span class="material-symbols-outlined text-[18px]">edit_note</span>
</button>
<button class="p-2 rounded-xl text-on-surface-variant hover:bg-surface-container hover:text-on-surface transition-colors" title="Riwayat Pasokan">
<span class="material-symbols-outlined text-[18px]">history</span>
</button>
</div>
</td>
</tr>
<!-- Row 2: Telur Ayam Kampung & Omega-3 -->
<tr class="hover:bg-surface/60 transition-colors group">
<td class="py-space-md px-space-md text-center">
<input class="w-4 h-4 rounded accent-primary" type="checkbox"/>
</td>
<td class="py-space-md px-space-md">
<div class="flex items-center gap-space-sm">
<div class="w-14 h-14 rounded-xl overflow-hidden shrink-0 bg-surface-container shadow-sm">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform" data-alt="Keranjang anyaman bambu pedesaan berisi telur ayam kampung alami dengan jerami kering dan suasana dapur rumah kayu tradisional yang hangat" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCdxVd0qdssEj3pfWOPuM4h_X4SpIle1vO8Si24AL-flhtTxK1pTpPYOohS6L7YSqD9I7NsdHV6Yb0ZQ0ZOP2kHWTG94FQG2Iz8GIvoyUrFSK_ENE59SH_LRsojub_YOwB7mq22J5x-IlTQK8FwqDYLx3nx4hhfownC6jqvZe_Kvb9IKIZNeVSKaxRQ7NiVfro7g9zcyNF_tCxAexElzuCCKDcZy3LOc5pxpJVNhDI"/>
</div>
<div>
<span class="font-headline-sm text-headline-sm text-on-surface block font-bold">Telur Ayam Kampung Asli &amp; Omega-3</span>
<div class="flex items-center gap-1.5 mt-0.5">
<span class="font-label-sm text-label-sm px-1.5 py-0.5 rounded bg-surface-container text-on-surface-variant font-mono">BZ-KMP-02</span>
<span class="font-label-sm text-label-sm text-tertiary font-semibold">Kampung Organik</span>
</div>
</div>
</div>
</td>
<td class="py-space-md px-space-md">
<span class="font-label-md text-label-md text-on-surface block">Mika Higienis (10 Butir)</span>
<span class="font-body-sm text-body-sm text-outline">Kuning telur oranye pekat</span>
</td>
<td class="py-space-md px-space-md">
<div class="flex items-center gap-1.5">
<span class="font-price-display text-headline-sm text-primary font-bold">Rp 38.000</span>
<button class="p-1 rounded-md text-outline hover:text-primary transition-colors" title="Ubah harga">
<span class="material-symbols-outlined text-[16px]">edit</span>
</button>
</div>
<span class="text-[11px] text-on-surface-variant">Kemasan Segel Higienis</span>
</td>
<td class="py-space-md px-space-md">
<div class="flex items-center gap-1.5">
<span class="w-2.5 h-2.5 rounded-full bg-secondary"></span>
<span class="font-headline-sm text-headline-sm text-secondary font-bold">85 Pack</span>
</div>
<span class="font-body-sm text-body-sm text-on-surface-variant">Total 850 Butir</span>
</td>
<td class="py-space-md px-space-md text-center">
<div class="inline-flex items-center bg-surface-container rounded-xl p-1 gap-1 shadow-inner">
<button class="w-7 h-7 rounded-lg bg-surface-container-lowest text-on-surface font-bold hover:bg-surface-container-high transition-colors flex items-center justify-center">-</button>
<input class="w-12 text-center bg-transparent font-stock-counter text-stock-counter text-on-surface font-bold focus:outline-none" type="text" value="85"/>
<button class="w-7 h-7 rounded-lg bg-surface-container-lowest text-on-surface font-bold hover:bg-surface-container-high transition-colors flex items-center justify-center">+</button>
<button class="w-7 h-7 rounded-lg bg-secondary text-on-secondary hover:bg-secondary/90 transition-colors flex items-center justify-center" title="Simpan Stok Cepat">
<span class="material-symbols-outlined text-[16px]">check</span>
</button>
</div>
</td>
<td class="py-space-md px-space-md text-center">
<button class="w-10 h-6 bg-secondary rounded-full relative inline-flex items-center p-0.5 cursor-pointer">
<span class="w-5 h-5 rounded-full bg-surface-container-lowest translate-x-4 shadow-sm transition-transform"></span>
</button>
</td>
<td class="py-space-md px-space-md text-center">
<div class="flex items-center justify-center gap-1">
<button class="p-2 rounded-xl text-on-surface-variant hover:bg-surface-container hover:text-on-surface transition-colors" title="Ubah Detail">
<span class="material-symbols-outlined text-[18px]">edit_note</span>
</button>
<button class="p-2 rounded-xl text-on-surface-variant hover:bg-surface-container hover:text-on-surface transition-colors" title="Riwayat Pasokan">
<span class="material-symbols-outlined text-[18px]">history</span>
</button>
</div>
</td>
</tr>
<!-- Row 3: Telur Bebek Tambak Segar -->
<tr class="hover:bg-surface/60 transition-colors group">
<td class="py-space-md px-space-md text-center">
<input class="w-4 h-4 rounded accent-primary" type="checkbox"/>
</td>
<td class="py-space-md px-space-md">
<div class="flex items-center gap-space-sm">
<div class="w-14 h-14 rounded-xl overflow-hidden shrink-0 bg-surface-container shadow-sm">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform" data-alt="Peti kayu pedesaan berisi butiran telur bebek cangkang hijau kebiruan segar dengan latar belakang pasar hasil tani tradisional" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAJyQYVrIhSpD-qqliFjr8Wjn5NcTV7zsf4AWzzqNCR6h7hivOWXSBAp3lNU9MAamFUeaS2BtfDC2xf2L0DZWhrDAnLRsLXj-GI2d_CCjjtYagMjuN044ljnRNzITlzqPB4nhUsoSj2jJTwa6n2x4veM__TQ-MkdZUFs0ldpES3WkoyDa84KlxtmtzzF8ckB0FIbAaUg2Pk2HPOKp45yfc1S8527Vbe9aJo1mqO-8Y"/>
</div>
<div>
<span class="font-headline-sm text-headline-sm text-on-surface block font-bold">Telur Bebek Tambak Segar (Pesisir)</span>
<div class="flex items-center gap-1.5 mt-0.5">
<span class="font-label-sm text-label-sm px-1.5 py-0.5 rounded bg-surface-container text-on-surface-variant font-mono">BZ-BBK-01</span>
<span class="font-label-sm text-label-sm text-tertiary font-semibold">Bebek Mentah</span>
</div>
</div>
</div>
</td>
<td class="py-space-md px-space-md">
<span class="font-label-md text-label-md text-on-surface block">Mika Karton (10 Butir)</span>
<span class="font-body-sm text-body-sm text-outline">Cangkang hijau toska tebal</span>
</td>
<td class="py-space-md px-space-md">
<div class="flex items-center gap-1.5">
<span class="font-price-display text-headline-sm text-primary font-bold">Rp 32.000</span>
<button class="p-1 rounded-md text-outline hover:text-primary transition-colors" title="Ubah harga">
<span class="material-symbols-outlined text-[16px]">edit</span>
</button>
</div>
<span class="text-[11px] text-on-surface-variant">Khusus martabak &amp; jamu</span>
</td>
<td class="py-space-md px-space-md">
<div class="flex items-center gap-1.5">
<span class="w-2.5 h-2.5 rounded-full bg-secondary"></span>
<span class="font-headline-sm text-headline-sm text-secondary font-bold">60 Pack</span>
</div>
<span class="font-body-sm text-body-sm text-on-surface-variant">Total 600 Butir</span>
</td>
<td class="py-space-md px-space-md text-center">
<div class="inline-flex items-center bg-surface-container rounded-xl p-1 gap-1 shadow-inner">
<button class="w-7 h-7 rounded-lg bg-surface-container-lowest text-on-surface font-bold hover:bg-surface-container-high transition-colors flex items-center justify-center">-</button>
<input class="w-12 text-center bg-transparent font-stock-counter text-stock-counter text-on-surface font-bold focus:outline-none" type="text" value="60"/>
<button class="w-7 h-7 rounded-lg bg-surface-container-lowest text-on-surface font-bold hover:bg-surface-container-high transition-colors flex items-center justify-center">+</button>
<button class="w-7 h-7 rounded-lg bg-secondary text-on-secondary hover:bg-secondary/90 transition-colors flex items-center justify-center" title="Simpan Stok Cepat">
<span class="material-symbols-outlined text-[16px]">check</span>
</button>
</div>
</td>
<td class="py-space-md px-space-md text-center">
<button class="w-10 h-6 bg-secondary rounded-full relative inline-flex items-center p-0.5 cursor-pointer">
<span class="w-5 h-5 rounded-full bg-surface-container-lowest translate-x-4 shadow-sm transition-transform"></span>
</button>
</td>
<td class="py-space-md px-space-md text-center">
<div class="flex items-center justify-center gap-1">
<button class="p-2 rounded-xl text-on-surface-variant hover:bg-surface-container hover:text-on-surface transition-colors" title="Ubah Detail">
<span class="material-symbols-outlined text-[18px]">edit_note</span>
</button>
<button class="p-2 rounded-xl text-on-surface-variant hover:bg-surface-container hover:text-on-surface transition-colors" title="Riwayat Pasokan">
<span class="material-symbols-outlined text-[18px]">history</span>
</button>
</div>
</td>
</tr>
<!-- Row 4: Telur Asin Masir Asli Gisting (CRITICAL STOCK ROW - HIGHLIGHTED) -->
<tr class="bg-primary-fixed/20 hover:bg-primary-fixed/30 transition-colors group">
<td class="py-space-md px-space-md text-center">
<input class="w-4 h-4 rounded accent-primary" type="checkbox"/>
</td>
<td class="py-space-md px-space-md">
<div class="flex items-center gap-space-sm">
<div class="w-14 h-14 rounded-xl overflow-hidden shrink-0 bg-surface-container shadow-sm relative">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform" data-alt="Peti kayu berisi telur asin matang masir berminyak khas daerah Gisting Lampung dengan suasana pasar tradisional otentik" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCBz9UfMsEniBsYHN9etO3xhEnKWRltR1OoBFAfBzASSgiVG8Rv5G37UaZMTOqaimi4X43C_8IhwKrozJ0t_dOIaVPenyom18xLzePgySoQmLmRNFhm2a8_JCU3krXo9L4CsQDRLaBQPYp2sfiOW3W56xqKRrBOsW5sFDugjOHj3NYDSSwxneav1HMGertyDHP9ZBH5H747ugu43Hnm3dz2Y2gMx7gGWEXBV2tWK8Q"/>
<span class="absolute top-1 left-1 w-2.5 h-2.5 rounded-full bg-error animate-ping"></span>
</div>
<div>
<div class="flex items-center gap-1.5">
<span class="font-headline-sm text-headline-sm text-on-surface font-bold">Telur Asin Masir Asli Gisting</span>
<span class="inline-flex items-center px-1.5 py-0.2 rounded bg-error-container text-on-error-container font-label-sm text-[10px] font-bold">RESTOK</span>
</div>
<div class="flex items-center gap-1.5 mt-0.5">
<span class="font-label-sm text-label-sm px-1.5 py-0.5 rounded bg-surface-container text-on-surface-variant font-mono">BZ-ASN-03</span>
<span class="font-label-sm text-label-sm text-tertiary font-semibold">Olahan Bebek</span>
</div>
</div>
</div>
</td>
<td class="py-space-md px-space-md">
<span class="font-label-md text-label-md text-on-surface block">Box Isi 10 Butir</span>
<span class="font-body-sm text-body-sm text-outline">Rasa gurih pulen masir</span>
</td>
<td class="py-space-md px-space-md">
<div class="flex items-center gap-1.5">
<span class="font-price-display text-headline-sm text-primary font-bold">Rp 36.000</span>
<button class="p-1 rounded-md text-outline hover:text-primary transition-colors" title="Ubah harga">
<span class="material-symbols-outlined text-[16px]">edit</span>
</button>
</div>
<span class="text-[11px] text-on-surface-variant">Siap konsumsi</span>
</td>
<td class="py-space-md px-space-md">
<div class="flex items-center gap-1.5">
<span class="material-symbols-outlined text-[18px] text-error">error</span>
<span class="font-headline-sm text-headline-sm text-error font-bold">Sisa 5 Box</span>
</div>
<span class="font-body-sm text-body-sm text-on-surface-variant">Tersisa 50 Butir (Ambang: 15)</span>
</td>
<td class="py-space-md px-space-md text-center">
<div class="inline-flex items-center bg-surface-container-lowest border border-error-container rounded-xl p-1 gap-1 shadow-sm">
<button class="w-7 h-7 rounded-lg bg-surface-container text-on-surface font-bold hover:bg-surface-container-high transition-colors flex items-center justify-center">-</button>
<input class="w-12 text-center bg-transparent font-stock-counter text-stock-counter text-error font-bold focus:outline-none" type="text" value="5"/>
<button class="w-7 h-7 rounded-lg bg-surface-container text-on-surface font-bold hover:bg-surface-container-high transition-colors flex items-center justify-center">+</button>
<button class="w-7 h-7 rounded-lg bg-primary-container text-on-primary-container font-bold hover:bg-primary-container/80 transition-colors flex items-center justify-center" title="Simpan Stok Cepat">
<span class="material-symbols-outlined text-[16px]">check</span>
</button>
</div>
</td>
<td class="py-space-md px-space-md text-center">
<button class="w-10 h-6 bg-secondary rounded-full relative inline-flex items-center p-0.5 cursor-pointer">
<span class="w-5 h-5 rounded-full bg-surface-container-lowest translate-x-4 shadow-sm transition-transform"></span>
</button>
</td>
<td class="py-space-md px-space-md text-center">
<div class="flex items-center justify-center gap-1">
<button class="p-2 rounded-xl text-on-surface-variant hover:bg-surface-container hover:text-on-surface transition-colors" title="Ubah Detail">
<span class="material-symbols-outlined text-[18px]">edit_note</span>
</button>
<button class="p-2 rounded-xl text-on-surface-variant hover:bg-surface-container hover:text-on-surface transition-colors" title="Riwayat Pasokan">
<span class="material-symbols-outlined text-[18px]">history</span>
</button>
</div>
</td>
</tr>
<!-- Row 5: Telur Ayam Kampung Herbal MPASI (CRITICAL STOCK ROW) -->
<tr class="bg-primary-fixed/20 hover:bg-primary-fixed/30 transition-colors group">
<td class="py-space-md px-space-md text-center">
<input class="w-4 h-4 rounded accent-primary" type="checkbox"/>
</td>
<td class="py-space-md px-space-md">
<div class="flex items-center gap-space-sm">
<div class="w-14 h-14 rounded-xl overflow-hidden shrink-0 bg-surface-container shadow-sm relative">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform" data-alt="Telur ayam kampung kecil bersih alami di dalam wadah karton jerami ramah lingkungan di atas meja kayu toko petani" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCpxo1RGF3Tk7Q40eGnFzraigAronCshRjP4pgTQ7-wrO5Jbn784WJIqGYU69gbVtJfJkQ2_X7K1i5kDseQVZ42kvi9SQgES-Xv49d9RdOFjLYf3Xfl0xdUmO_1Q8msETIytRDRncHWAFCfcnw0DAVWsQQXOVTSKL418r-Qvx_KpUVDbwbzbk3pSLxknOz8aNcacVGH0U0G3Spda4qvuGo3Vkw2K_d-Xhh06gxfMKQ"/>
<span class="absolute top-1 left-1 w-2.5 h-2.5 rounded-full bg-error animate-ping"></span>
</div>
<div>
<div class="flex items-center gap-1.5">
<span class="font-headline-sm text-headline-sm text-on-surface font-bold">Telur Ayam Kampung Herbal MPASI</span>
<span class="inline-flex items-center px-1.5 py-0.2 rounded bg-error-container text-on-error-container font-label-sm text-[10px] font-bold">RESTOK</span>
</div>
<div class="flex items-center gap-1.5 mt-0.5">
<span class="font-label-sm text-label-sm px-1.5 py-0.5 rounded bg-surface-container text-on-surface-variant font-mono">BZ-KMP-05</span>
<span class="font-label-sm text-label-sm text-tertiary font-semibold">Herbal &amp; Bebas Kimia</span>
</div>
</div>
</div>
</td>
<td class="py-space-md px-space-md">
<span class="font-label-md text-label-md text-on-surface block">Pack Higienis (6 Butir)</span>
<span class="font-body-sm text-body-sm text-outline">Standar bayi &amp; anak</span>
</td>
<td class="py-space-md px-space-md">
<div class="flex items-center gap-1.5">
<span class="font-price-display text-headline-sm text-primary font-bold">Rp 25.000</span>
<button class="p-1 rounded-md text-outline hover:text-primary transition-colors" title="Ubah harga">
<span class="material-symbols-outlined text-[16px]">edit</span>
</button>
</div>
<span class="text-[11px] text-on-surface-variant">Pakan kunyit &amp; jahe</span>
</td>
<td class="py-space-md px-space-md">
<div class="flex items-center gap-1.5">
<span class="material-symbols-outlined text-[18px] text-error">error</span>
<span class="font-headline-sm text-headline-sm text-error font-bold">Sisa 4 Pack</span>
</div>
<span class="font-body-sm text-body-sm text-on-surface-variant">Tersisa 24 Butir (Ambang: 10)</span>
</td>
<td class="py-space-md px-space-md text-center">
<div class="inline-flex items-center bg-surface-container-lowest border border-error-container rounded-xl p-1 gap-1 shadow-sm">
<button class="w-7 h-7 rounded-lg bg-surface-container text-on-surface font-bold hover:bg-surface-container-high transition-colors flex items-center justify-center">-</button>
<input class="w-12 text-center bg-transparent font-stock-counter text-stock-counter text-error font-bold focus:outline-none" type="text" value="4"/>
<button class="w-7 h-7 rounded-lg bg-surface-container text-on-surface font-bold hover:bg-surface-container-high transition-colors flex items-center justify-center">+</button>
<button class="w-7 h-7 rounded-lg bg-primary-container text-on-primary-container font-bold hover:bg-primary-container/80 transition-colors flex items-center justify-center" title="Simpan Stok Cepat">
<span class="material-symbols-outlined text-[16px]">check</span>
</button>
</div>
</td>
<td class="py-space-md px-space-md text-center">
<button class="w-10 h-6 bg-secondary rounded-full relative inline-flex items-center p-0.5 cursor-pointer">
<span class="w-5 h-5 rounded-full bg-surface-container-lowest translate-x-4 shadow-sm transition-transform"></span>
</button>
</td>
<td class="py-space-md px-space-md text-center">
<div class="flex items-center justify-center gap-1">
<button class="p-2 rounded-xl text-on-surface-variant hover:bg-surface-container hover:text-on-surface transition-colors" title="Ubah Detail">
<span class="material-symbols-outlined text-[18px]">edit_note</span>
</button>
<button class="p-2 rounded-xl text-on-surface-variant hover:bg-surface-container hover:text-on-surface transition-colors" title="Riwayat Pasokan">
<span class="material-symbols-outlined text-[18px]">history</span>
</button>
</div>
</td>
</tr>
<!-- Row 6: Telur Ras Kiloan Timbangan Digital -->
<tr class="hover:bg-surface/60 transition-colors group">
<td class="py-space-md px-space-md text-center">
<input class="w-4 h-4 rounded accent-primary" type="checkbox"/>
</td>
<td class="py-space-md px-space-md">
<div class="flex items-center gap-space-sm">
<div class="w-14 h-14 rounded-xl overflow-hidden shrink-0 bg-surface-container shadow-sm">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform" data-alt="Timbangan digital di meja pasar telur dengan keranjang anyaman penuh telur ayam negeri cokelat bersih" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBrAirKcsc9ov2dO9i25kfzKNaxB0Se7CtQYBpOyq_VrA68_woxRFkBWdayReCuo15CKkqqedT2I3O8bUegir_hs5vu_3WIwSaNqYVTKItm350Cv8WvIRu9iHt1eRm9i8f1ClRTq_d6-2yoaQrXBl0vVZ18qtPokDcyqR2QPFaywtHWxKS3kA8hpZYr4ZWMspU9idCm5UnzqLZK12DdgXVJG8Q8chmBcPgnIgYsIZY"/>
</div>
<div>
<span class="font-headline-sm text-headline-sm text-on-surface block font-bold">Telur Ras Kiloan (Timbangan Digital)</span>
<div class="flex items-center gap-1.5 mt-0.5">
<span class="font-label-sm text-label-sm px-1.5 py-0.5 rounded bg-surface-container text-on-surface-variant font-mono">BZ-RAS-02</span>
<span class="font-label-sm text-label-sm text-tertiary font-semibold">Eceran Warung</span>
</div>
</div>
</div>
</td>
<td class="py-space-md px-space-md">
<span class="font-label-md text-label-md text-on-surface block">Per Kilogram (Kg)</span>
<span class="font-body-sm text-body-sm text-outline">Isi ±16-17 Butir</span>
</td>
<td class="py-space-md px-space-md">
<div class="flex items-center gap-1.5">
<span class="font-price-display text-headline-sm text-primary font-bold">Rp 27.500</span>
<button class="p-1 rounded-md text-outline hover:text-primary transition-colors" title="Ubah harga">
<span class="material-symbols-outlined text-[16px]">edit</span>
</button>
</div>
<span class="text-[11px] text-on-surface-variant">Standar pasar Gisting</span>
</td>
<td class="py-space-md px-space-md">
<div class="flex items-center gap-1.5">
<span class="w-2.5 h-2.5 rounded-full bg-secondary"></span>
<span class="font-headline-sm text-headline-sm text-secondary font-bold">210 Kg</span>
</div>
<span class="font-body-sm text-body-sm text-on-surface-variant">±3.460 Butir di Gudang</span>
</td>
<td class="py-space-md px-space-md text-center">
<div class="inline-flex items-center bg-surface-container rounded-xl p-1 gap-1 shadow-inner">
<button class="w-7 h-7 rounded-lg bg-surface-container-lowest text-on-surface font-bold hover:bg-surface-container-high transition-colors flex items-center justify-center">-</button>
<input class="w-12 text-center bg-transparent font-stock-counter text-stock-counter text-on-surface font-bold focus:outline-none" type="text" value="210"/>
<button class="w-7 h-7 rounded-lg bg-surface-container-lowest text-on-surface font-bold hover:bg-surface-container-high transition-colors flex items-center justify-center">+</button>
<button class="w-7 h-7 rounded-lg bg-secondary text-on-secondary hover:bg-secondary/90 transition-colors flex items-center justify-center" title="Simpan Stok Cepat">
<span class="material-symbols-outlined text-[16px]">check</span>
</button>
</div>
</td>
<td class="py-space-md px-space-md text-center">
<button class="w-10 h-6 bg-secondary rounded-full relative inline-flex items-center p-0.5 cursor-pointer">
<span class="w-5 h-5 rounded-full bg-surface-container-lowest translate-x-4 shadow-sm transition-transform"></span>
</button>
</td>
<td class="py-space-md px-space-md text-center">
<div class="flex items-center justify-center gap-1">
<button class="p-2 rounded-xl text-on-surface-variant hover:bg-surface-container hover:text-on-surface transition-colors" title="Ubah Detail">
<span class="material-symbols-outlined text-[18px]">edit_note</span>
</button>
<button class="p-2 rounded-xl text-on-surface-variant hover:bg-surface-container hover:text-on-surface transition-colors" title="Riwayat Pasokan">
<span class="material-symbols-outlined text-[18px]">history</span>
</button>
</div>
</td>
</tr>
<!-- Row 7: Telur Puyuh Segar Peternak Wonosobo -->
<tr class="hover:bg-surface/60 transition-colors group">
<td class="py-space-md px-space-md text-center">
<input class="w-4 h-4 rounded accent-primary" type="checkbox"/>
</td>
<td class="py-space-md px-space-md">
<div class="flex items-center gap-space-sm">
<div class="w-14 h-14 rounded-xl overflow-hidden shrink-0 bg-surface-container shadow-sm">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform" data-alt="Wadah kayu bundar berisi puluhan telur puyuh bercak hitam alami yang sangat bersih dan segar dari kandang peternakan lokal" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCHWFoD-_fZj4JGWzhth9MmvI2O7_kMCT4Ne4UezqRIkGWXeRsvyzWUZn1IQQ7aH4xisNHkD2N8D4gYGOHB3HJhRTQGhiMUXHj7lLZdrHnuczijqHVK1y_0WAtWKOlMrsIIx802AUyBOoBJc22LJjZmNmUEzDmTWJMDEzWNRFgGUfv9eohdMMb1uL53PMx32uASVDbeO9HHBDWDHtrw8ulhdMAFjdQj2m0of_Cs6zI"/>
</div>
<div>
<span class="font-headline-sm text-headline-sm text-on-surface block font-bold">Telur Puyuh Segar Peternak Wonosobo</span>
<div class="flex items-center gap-1.5 mt-0.5">
<span class="font-label-sm text-label-sm px-1.5 py-0.5 rounded bg-surface-container text-on-surface-variant font-mono">BZ-PYH-01</span>
<span class="font-label-sm text-label-sm text-tertiary font-semibold">Puyuh Unggul</span>
</div>
</div>
</div>
</td>
<td class="py-space-md px-space-md">
<span class="font-label-md text-label-md text-on-surface block">Mika Khusus (50 Butir)</span>
<span class="font-body-sm text-body-sm text-outline">Bebas retak &amp; bersih</span>
</td>
<td class="py-space-md px-space-md">
<div class="flex items-center gap-1.5">
<span class="font-price-display text-headline-sm text-primary font-bold">Rp 22.000</span>
<button class="p-1 rounded-md text-outline hover:text-primary transition-colors" title="Ubah harga">
<span class="material-symbols-outlined text-[16px]">edit</span>
</button>
</div>
<span class="text-[11px] text-on-surface-variant">Cocok untuk sate warung</span>
</td>
<td class="py-space-md px-space-md">
<div class="flex items-center gap-1.5">
<span class="w-2.5 h-2.5 rounded-full bg-secondary"></span>
<span class="font-headline-sm text-headline-sm text-secondary font-bold">95 Mika</span>
</div>
<span class="font-body-sm text-body-sm text-on-surface-variant">Total 4.750 Butir</span>
</td>
<td class="py-space-md px-space-md text-center">
<div class="inline-flex items-center bg-surface-container rounded-xl p-1 gap-1 shadow-inner">
<button class="w-7 h-7 rounded-lg bg-surface-container-lowest text-on-surface font-bold hover:bg-surface-container-high transition-colors flex items-center justify-center">-</button>
<input class="w-12 text-center bg-transparent font-stock-counter text-stock-counter text-on-surface font-bold focus:outline-none" type="text" value="95"/>
<button class="w-7 h-7 rounded-lg bg-surface-container-lowest text-on-surface font-bold hover:bg-surface-container-high transition-colors flex items-center justify-center">+</button>
<button class="w-7 h-7 rounded-lg bg-secondary text-on-secondary hover:bg-secondary/90 transition-colors flex items-center justify-center" title="Simpan Stok Cepat">
<span class="material-symbols-outlined text-[16px]">check</span>
</button>
</div>
</td>
<td class="py-space-md px-space-md text-center">
<button class="w-10 h-6 bg-secondary rounded-full relative inline-flex items-center p-0.5 cursor-pointer">
<span class="w-5 h-5 rounded-full bg-surface-container-lowest translate-x-4 shadow-sm transition-transform"></span>
</button>
</td>
<td class="py-space-md px-space-md text-center">
<div class="flex items-center justify-center gap-1">
<button class="p-2 rounded-xl text-on-surface-variant hover:bg-surface-container hover:text-on-surface transition-colors" title="Ubah Detail">
<span class="material-symbols-outlined text-[18px]">edit_note</span>
</button>
<button class="p-2 rounded-xl text-on-surface-variant hover:bg-surface-container hover:text-on-surface transition-colors" title="Riwayat Pasokan">
<span class="material-symbols-outlined text-[18px]">history</span>
</button>
</div>
</td>
</tr>
<!-- Row 8: Telur Bebek Angon Organik Pesisir (HABIS - OUT OF STOCK) -->
<tr class="bg-surface-container-low/40 hover:bg-surface-container-low transition-colors group opacity-75">
<td class="py-space-md px-space-md text-center">
<input class="w-4 h-4 rounded accent-primary" type="checkbox"/>
</td>
<td class="py-space-md px-space-md">
<div class="flex items-center gap-space-sm">
<div class="w-14 h-14 rounded-xl overflow-hidden shrink-0 bg-surface-container shadow-sm grayscale">
<img class="w-full h-full object-cover" data-alt="Peti kayu sederhana di warung pasar tradisional berisi jerami kosong dengan sedikit telur bebek sisa display panen" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBrwf1wZcmuVb_GVL5WTO69gs2kjB4Kw7fs73ty4D6PDZe_WD4via7lPm83ebj8-j-MOOzgJwWB2Il0QMQ5lVuzfrlyvGPJA63sP9zjVNWhYXnuGx4SxM3hoURiROn9OxAn9IodNOkcQcF_wUnqxyWDEjXFOcYoM6BV9oTutqcN94-TXagrS73OsbtAJzvwzbNOMDh6lstrutbAO_lb17QGz5VUIhKVwUEgn4hHe6A"/>
</div>
<div>
<span class="font-headline-sm text-headline-sm text-on-surface-variant block font-bold">Telur Bebek Angon Organik</span>
<div class="flex items-center gap-1.5 mt-0.5">
<span class="font-label-sm text-label-sm px-1.5 py-0.5 rounded bg-surface-container text-on-surface-variant font-mono">BZ-BBK-04</span>
<span class="font-label-sm text-label-sm text-outline font-semibold">Organik Alami</span>
</div>
</div>
</div>
</td>
<td class="py-space-md px-space-md">
<span class="font-label-md text-label-md text-on-surface-variant block">Tray Karpet (30 Butir)</span>
<span class="font-body-sm text-body-sm text-outline">Bebas pakan pelet</span>
</td>
<td class="py-space-md px-space-md">
<div class="flex items-center gap-1.5">
<span class="font-price-display text-headline-sm text-on-surface-variant font-bold">Rp 95.000</span>
</div>
<span class="text-[11px] text-outline">Per karpet 30 butir</span>
</td>
<td class="py-space-md px-space-md">
<div class="flex items-center gap-1.5">
<span class="w-2.5 h-2.5 rounded-full bg-outline"></span>
<span class="font-headline-sm text-headline-sm text-outline font-bold">Habis (0 Butir)</span>
</div>
<span class="font-body-sm text-body-sm text-on-surface-variant">Menunggu Panen Besok Sore</span>
</td>
<td class="py-space-md px-space-md text-center">
<div class="inline-flex items-center bg-surface-container rounded-xl p-1 gap-1 shadow-inner">
<button class="w-7 h-7 rounded-lg bg-surface-container-lowest text-on-surface font-bold hover:bg-surface-container-high transition-colors flex items-center justify-center">-</button>
<input class="w-12 text-center bg-transparent font-stock-counter text-stock-counter text-outline font-bold focus:outline-none" type="text" value="0"/>
<button class="w-7 h-7 rounded-lg bg-surface-container-lowest text-on-surface font-bold hover:bg-surface-container-high transition-colors flex items-center justify-center">+</button>
<button class="w-7 h-7 rounded-lg bg-surface-container-highest text-outline transition-colors flex items-center justify-center" title="Simpan Stok Cepat">
<span class="material-symbols-outlined text-[16px]">check</span>
</button>
</div>
</td>
<td class="py-space-md px-space-md text-center">
<button class="w-10 h-6 bg-surface-variant rounded-full relative inline-flex items-center p-0.5 cursor-pointer">
<span class="w-5 h-5 rounded-full bg-surface-container-lowest translate-x-0 shadow-sm transition-transform"></span>
</button>
</td>
<td class="py-space-md px-space-md text-center">
<div class="flex items-center justify-center gap-1">
<button class="p-2 rounded-xl text-on-surface-variant hover:bg-surface-container hover:text-on-surface transition-colors" title="Ubah Detail">
<span class="material-symbols-outlined text-[18px]">edit_note</span>
</button>
<button class="p-2 rounded-xl text-on-surface-variant hover:bg-surface-container hover:text-on-surface transition-colors" title="Riwayat Pasokan">
<span class="material-symbols-outlined text-[18px]">history</span>
</button>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<!-- TABLE FOOTER & PAGINATION -->
<div class="py-space-md px-space-lg bg-surface-container-low flex flex-col sm:flex-row items-center justify-between gap-space-sm select-none">
<div class="flex items-center gap-2">
<span class="material-symbols-outlined text-secondary text-[16px]">scale</span>
<span class="font-body-sm text-body-sm text-on-surface-variant">
          Menampilkan <strong>1-8</strong> dari <strong>12</strong> Varian Komoditas • Terhubung ke timbangan Pos Gisting
        </span>
</div>
<div class="flex items-center gap-1">
<button class="px-3 py-1.5 rounded-lg bg-surface-container text-on-surface-variant hover:bg-surface-container-high font-label-sm text-label-sm disabled:opacity-40 transition-colors" disabled="">
          Sebelumnya
        </button>
<button class="w-8 h-8 rounded-lg bg-primary text-on-primary font-label-sm text-label-sm font-bold shadow-sm">
          1
        </button>
<button class="w-8 h-8 rounded-lg bg-surface-container text-on-surface hover:bg-surface-container-high font-label-sm text-label-sm transition-colors">
          2
        </button>
<button class="px-3 py-1.5 rounded-lg bg-surface-container text-on-surface hover:bg-surface-container-high font-label-sm text-label-sm transition-colors">
          Selanjutnya
        </button>
</div>
</div>
</div>
<!-- SLIDE-OVER / MODAL: FORM TAMBAH / UBAH PRODUK TELUR BARU -->
<div class="fixed inset-0 z-50 flex items-center justify-center p-4 bg-on-background/50 backdrop-blur-sm hidden transition-all" id="modalTambahProduk">
<div class="relative w-full max-w-2xl bg-surface-container-lowest rounded-3xl shadow-[0_20px_50px_rgba(0,0,0,0.2)] overflow-hidden flex flex-col max-h-[921px]">
<!-- Modal Header -->
<div class="px-space-lg py-space-md bg-surface-container-low flex items-center justify-between">
<div class="flex items-center gap-space-sm">
<div class="w-10 h-10 rounded-xl bg-primary-container text-on-primary-container flex items-center justify-center shadow-sm">
<span class="material-symbols-outlined text-[22px]">egg</span>
</div>
<div>
<h2 class="font-headline-md text-headline-md text-on-surface tracking-tight">Tambah Varian Telur Baru</h2>
<p class="font-label-sm text-label-sm text-on-surface-variant">Katalog pasar komoditas Bang Zul Eggs Tanggamus</p>
</div>
</div>
<button class="w-8 h-8 rounded-full bg-surface-container hover:bg-surface-container-high text-on-surface-variant flex items-center justify-center transition-colors" onclick="document.getElementById('modalTambahProduk').classList.add('hidden')">
<span class="material-symbols-outlined text-[18px]">close</span>
</button>
</div>
<!-- Modal Body (Form Fields) -->
<div class="p-space-lg overflow-y-auto flex flex-col gap-space-md">
<!-- Field 1: Nama Produk -->
<div class="flex flex-col gap-1.5">
<label class="font-label-md text-label-md text-on-surface">Nama Produk Telur <span class="text-error">*</span></label>
<input class="w-full px-space-md py-2.5 rounded-xl bg-surface-container-low text-on-surface font-body-md text-body-md focus:bg-surface-container-lowest focus:ring-2 focus:ring-primary focus:outline-none transition-all" placeholder="Contoh: Telur Ayam Ras Pilihan..." type="text" value="Telur Ayam Ras Super Karpet (30 Butir)"/>
</div>
<!-- Field 2 & 3: Kategori & Kemasan -->
<div class="grid grid-cols-1 md:grid-cols-2 gap-space-md">
<div class="flex flex-col gap-1.5">
<label class="font-label-md text-label-md text-on-surface">Kategori Unggas / Telur <span class="text-error">*</span></label>
<select class="w-full px-space-md py-2.5 rounded-xl bg-surface-container-low text-on-surface font-body-md text-body-md focus:bg-surface-container-lowest focus:ring-2 focus:ring-primary focus:outline-none transition-all">
<option selected="">Telur Ayam Ras</option>
<option>Telur Ayam Kampung</option>
<option>Telur Bebek Mentah</option>
<option>Telur Puyuh</option>
<option>Olahan Asin Gisting</option>
</select>
</div>
<div class="flex flex-col gap-1.5">
<label class="font-label-md text-label-md text-on-surface">Jenis Kemasan &amp; Satuan <span class="text-error">*</span></label>
<select class="w-full px-space-md py-2.5 rounded-xl bg-surface-container-low text-on-surface font-body-md text-body-md focus:bg-surface-container-lowest focus:ring-2 focus:ring-primary focus:outline-none transition-all">
<option selected="">Tray Karpet Karton (30 Butir)</option>
<option>Mika Higienis (10 Butir)</option>
<option>Mika Kecil (6 Butir)</option>
<option>Kiloan (±16-17 Butir)</option>
<option>Peti Kayu Besar (150 Butir)</option>
</select>
</div>
</div>
<!-- Field 4: Harga Harian & Grosir -->
<div class="grid grid-cols-1 md:grid-cols-2 gap-space-md">
<div class="flex flex-col gap-1.5">
<label class="font-label-md text-label-md text-on-surface">Harga Jual Normal (IDR) <span class="text-error">*</span></label>
<div class="relative">
<span class="absolute left-3.5 top-1/2 -translate-y-1/2 font-bold text-on-surface-variant font-label-md text-label-md">Rp</span>
<input class="w-full pl-11 pr-4 py-2.5 rounded-xl bg-surface-container-low font-headline-sm text-headline-sm text-primary font-bold focus:bg-surface-container-lowest focus:ring-2 focus:ring-primary focus:outline-none transition-all" type="text" value="52.000"/>
</div>
<span class="font-label-sm text-[10px] text-tertiary">Harga eceran per tray karpet</span>
</div>
<div class="flex flex-col gap-1.5">
<label class="font-label-md text-label-md text-on-surface">Harga Grosir Mitra (&gt;10 Tray)</label>
<div class="relative">
<span class="absolute left-3.5 top-1/2 -translate-y-1/2 font-bold text-on-surface-variant font-label-md text-label-md">Rp</span>
<input class="w-full pl-11 pr-4 py-2.5 rounded-xl bg-surface-container-low font-headline-sm text-headline-sm text-on-surface font-bold focus:bg-surface-container-lowest focus:ring-2 focus:ring-primary focus:outline-none transition-all" type="text" value="50.500"/>
</div>
<span class="font-label-sm text-[10px] text-tertiary">Otomatis aktif untuk warung terverifikasi</span>
</div>
</div>
<!-- Field 5: Stok Awal & Ambang Batas -->
<div class="grid grid-cols-1 md:grid-cols-2 gap-space-md">
<div class="flex flex-col gap-1.5">
<label class="font-label-md text-label-md text-on-surface">Jumlah Pasokan Stok Awal <span class="text-error">*</span></label>
<input class="w-full px-space-md py-2.5 rounded-xl bg-surface-container-low font-stock-counter text-stock-counter text-on-surface focus:bg-surface-container-lowest focus:ring-2 focus:ring-primary focus:outline-none transition-all" type="number" value="140"/>
</div>
<div class="flex flex-col gap-1.5">
<label class="font-label-md text-label-md text-on-surface">Ambang Peringatan Menipis</label>
<input class="w-full px-space-md py-2.5 rounded-xl bg-surface-container-low font-stock-counter text-stock-counter text-error focus:bg-surface-container-lowest focus:ring-2 focus:ring-primary focus:outline-none transition-all" type="number" value="15"/>
</div>
</div>
<!-- Field 6: Deskripsi & Manfaat -->
<div class="flex flex-col gap-1.5">
<label class="font-label-md text-label-md text-on-surface">Deskripsi Singkat &amp; Kualitas Panen</label>
<textarea class="w-full px-space-md py-2 rounded-xl bg-surface-container-low text-on-surface font-body-md text-body-md focus:bg-surface-container-lowest focus:ring-2 focus:ring-primary focus:outline-none transition-all" rows="3">Dipanen subuh hari dari mitra peternak ayam ras lereng Gisting. Telur disortir tanpa retak, cangkang tebal berserat cokelat bersih, kuning telur utuh &amp; bertekstur kental alami.</textarea>
</div>
<!-- Field 7: Foto Produk Upload Area -->
<div class="flex flex-col gap-1.5">
<label class="font-label-md text-label-md text-on-surface">Foto Produk Segar</label>
<div class="p-space-md rounded-2xl bg-surface-container-low flex flex-col sm:flex-row items-center gap-space-md">
<div class="w-20 h-20 rounded-xl overflow-hidden bg-surface-container shrink-0 shadow-sm relative group">
<img class="w-full h-full object-cover" data-alt="Foto close up tumpukan rak telur ayam ras berbutir cokelat segar di pasar tradisional dengan cahaya matahari pagi hangat" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBP8EwY0PtV-Idxg-ufyCx-2XLaoLieaU2ibyWU6T9xh9H2gqnxFTd9nB55s2v8e_nfIawtYdXJXjJWG9ShS8b4XqT2e-T03vVNl0y1Dh_ZQhnu1EVmHihD2ruVWvpa4G42DrV1ERb9A4VLsazVWl9Y6Yh55BAOrOc_2xrbGeOELEvwvr8yLd3P92ToaHwJD_7mseFMQkceBdv7GNpTcKh-qL7Xz_lxic_6osR3jyw"/>
<div class="absolute inset-0 bg-on-background/30 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity cursor-pointer">
<span class="material-symbols-outlined text-surface-container-lowest text-[18px]">edit</span>
</div>
</div>
<div class="flex-1 text-center sm:text-left">
<span class="font-headline-sm text-label-lg text-on-surface block">rak_telur_karpet_gisting.jpg</span>
<span class="font-body-sm text-body-sm text-on-surface-variant block">Ukuran file: 2.4 MB • Format: JPG siap tayang</span>
<div class="flex items-center justify-center sm:justify-start gap-2 mt-2">
<button class="px-3 py-1 rounded-lg bg-surface-container hover:bg-surface-container-high text-on-surface font-label-sm text-label-sm transition-colors" type="button">
                  Ganti Foto
                </button>
<button class="px-3 py-1 rounded-lg bg-error-container text-on-error-container font-label-sm text-label-sm transition-colors" type="button">
                  Hapus
                </button>
</div>
</div>
</div>
</div>
</div>
<!-- Modal Footer -->
<div class="px-space-lg py-space-md bg-surface-container-low flex items-center justify-between">
<button class="px-space-lg py-2.5 rounded-xl bg-surface-container hover:bg-surface-container-high text-on-surface font-label-lg text-label-lg transition-colors" onclick="document.getElementById('modalTambahProduk').classList.add('hidden')">
          Batal
        </button>
<button class="px-space-xl py-2.5 rounded-xl bg-primary-container hover:bg-primary-fixed-dim text-on-primary-container font-headline-sm text-headline-sm shadow-md transition-all" onclick="document.getElementById('modalTambahProduk').classList.add('hidden')">
          Simpan &amp; Tayangkan ke Etalase
        </button>
</div>
</div>
</div>
</div></main></div></body></html>

<!-- Laporan Penjualan & Analisis Omzet Bang Zul -->
<!DOCTYPE html>

<html lang="id"><head><meta charset="utf-8"/><meta content="width=device-width, initial-scale=1.0" name="viewport"/><meta content="web_dashboard" name="shell-type"/><link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&amp;family=Plus+Jakarta+Sans:wght@700;800&amp;display=swap" rel="stylesheet"/><link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/><style>@layer base{html,body{margin:0;padding:0;}body{overscroll-behavior:none;}main>:first-child{margin-top:0!important;}main>:last-child{margin-bottom:0!important;}}::-webkit-scrollbar{display:none;}</style><script src="https://cdn.tailwindcss.com"></script><script id="tailwind-config">tailwind.config={darkMode:"class",theme:{extend:{"colors":{"primary":"#835500","secondary-fixed":"#a3f69c","tertiary":"#556158","surface-container":"#f0eded","on-primary-container":"#644000","secondary-fixed-dim":"#88d982","on-surface-variant":"#524534","outline-variant":"#d7c3ae","on-tertiary-container":"#3e4a41","on-error-container":"#93000a","on-secondary-fixed":"#002204","tertiary-container":"#acb9ae","surface-container-high":"#eae7e7","on-primary":"#ffffff","tertiary-fixed-dim":"#bdcabe","error-container":"#ffdad6","on-tertiary":"#ffffff","on-secondary":"#ffffff","on-secondary-container":"#217128","on-background":"#1b1c1c","surface":"#fcf9f8","inverse-primary":"#ffb955","inverse-on-surface":"#f3f0f0","primary-container":"#f5a623","surface-container-lowest":"#ffffff","on-error":"#ffffff","inverse-surface":"#303030","error":"#ba1a1a","primary-fixed":"#ffddb4","background":"#fcf9f8","on-tertiary-fixed":"#131e17","on-secondary-fixed-variant":"#005312","on-primary-fixed":"#291800","surface-tint":"#835500","secondary-container":"#a0f399","surface-dim":"#dcd9d9","tertiary-fixed":"#d9e6da","surface-container-low":"#f6f3f2","surface-variant":"#e4e2e1","on-tertiary-fixed-variant":"#3e4a41","primary-fixed-dim":"#ffb955","outline":"#857462","on-primary-fixed-variant":"#633f00","surface-bright":"#fcf9f8","secondary":"#1b6d24","surface-container-highest":"#e4e2e1","on-surface":"#1b1c1c"},"borderRadius":{"DEFAULT":"0.25rem","lg":"0.5rem","xl":"0.75rem","full":"9999px"},"spacing":{"gutter":"1rem","space-xl":"2rem","margin":"1rem","space-xs":"0.25rem","space-sm":"0.5rem","gutter-desktop":"1.5rem","space-lg":"1.5rem","margin-desktop":"2.5rem","space-md":"1rem"},"fontFamily":{"label-lg":["Inter"],"price-display":["Plus Jakarta Sans"],"display-lg-mobile":["Plus Jakarta Sans"],"stock-counter":["Inter"],"headline-sm":["Plus Jakarta Sans"],"body-md":["Inter"],"headline-lg":["Plus Jakarta Sans"],"label-sm":["Inter"],"display-lg":["Plus Jakarta Sans"],"body-sm":["Inter"],"label-md":["Inter"],"body-lg":["Inter"],"headline-lg-mobile":["Plus Jakarta Sans"],"headline-md":["Plus Jakarta Sans"]},"fontSize":{"label-lg":["14px",{"lineHeight":"20px","fontWeight":"600"}],"price-display":["22px",{"lineHeight":"28px","letterSpacing":"-0.02em","fontWeight":"800"}],"display-lg-mobile":["30px",{"lineHeight":"38px","letterSpacing":"-0.01em","fontWeight":"800"}],"stock-counter":["18px",{"lineHeight":"24px","letterSpacing":"0.01em","fontWeight":"700"}],"headline-sm":["16px",{"lineHeight":"24px","fontWeight":"700"}],"body-md":["14px",{"lineHeight":"22px","fontWeight":"400"}],"headline-lg":["28px",{"lineHeight":"36px","letterSpacing":"-0.01em","fontWeight":"700"}],"label-sm":["11px",{"lineHeight":"14px","letterSpacing":"0.02em","fontWeight":"600"}],"display-lg":["40px",{"lineHeight":"48px","letterSpacing":"-0.02em","fontWeight":"800"}],"body-sm":["12px",{"lineHeight":"18px","fontWeight":"400"}],"label-md":["12px",{"lineHeight":"16px","fontWeight":"600"}],"body-lg":["16px",{"lineHeight":"26px","fontWeight":"400"}],"headline-lg-mobile":["22px",{"lineHeight":"30px","letterSpacing":"0em","fontWeight":"700"}],"headline-md":["20px",{"lineHeight":"28px","fontWeight":"700"}]}}}};</script></head><body class="bg-surface font-body-md text-on-surface antialiased min-h-screen selection:bg-primary-container selection:text-on-primary-container"><aside class="fixed left-0 top-0 h-full w-72 bg-surface-container-low shadow-[0_1px_8px_rgba(0,0,0,0.04)] z-50 flex flex-col justify-between select-none"><div class="flex flex-col"><div class="px-space-lg pt-space-lg pb-space-md"><div class="flex items-center gap-space-sm"><div class="w-10 h-10 rounded-xl bg-primary-container flex items-center justify-center text-on-primary-container shadow-[0_4px_20px_-2px_rgba(245,166,35,0.25)]"><span class="material-symbols-outlined text-[24px]">egg</span></div><div><span class="font-headline-sm text-headline-sm text-on-surface block tracking-tight">Bang Zul Eggs</span><span class="font-label-sm text-label-sm text-on-surface-variant block">Portal Penjual &amp; Admin</span></div></div><div class="mt-space-md p-space-sm rounded-xl bg-secondary-container/40 flex items-center gap-space-xs"><span class="w-2 h-2 rounded-full bg-secondary animate-pulse"></span><div class="overflow-hidden"><span class="font-label-sm text-label-sm text-on-secondary-container truncate block">Kandang Utama Lereng Gisting (Stok Live)</span></div></div></div><div class="px-space-md"><span class="font-label-sm text-label-sm text-outline uppercase tracking-wider px-space-sm mb-space-xs block">Menu Utama</span><nav class="flex flex-col gap-1" data-active-classes="bg-primary-container text-on-primary-container font-headline-sm font-bold shadow-[0_2px_8px_rgba(245,166,35,0.2)]"><a class="group flex items-center justify-between px-space-sm py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface transition-all" data-path="dashboard-utama" href="#"><div class="flex items-center gap-space-sm"><span class="material-symbols-outlined text-[20px] text-tertiary group-hover:text-primary transition-colors">dashboard</span><span class="font-label-lg text-label-lg">Dashboard Utama</span></div></a><a class="group flex items-center justify-between px-space-sm py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface transition-all" data-path="data-produk-dan-stok" href="#"><div class="flex items-center gap-space-sm"><span class="material-symbols-outlined text-[20px] text-tertiary group-hover:text-primary transition-colors">inventory_2</span><span class="font-label-lg text-label-lg">Data Produk &amp; Stok</span></div></a><a class="group flex items-center justify-between px-space-sm py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface transition-all" data-path="kategori-dan-varian" href="#"><div class="flex items-center gap-space-sm"><span class="material-symbols-outlined text-[20px] text-tertiary group-hover:text-primary transition-colors">category</span><span class="font-label-lg text-label-lg">Kategori &amp; Varian</span></div></a><a class="group flex items-center justify-between px-space-sm py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface transition-all" data-path="data-pesanan-masuk" href="#"><div class="flex items-center gap-space-sm"><span class="material-symbols-outlined text-[20px] text-tertiary group-hover:text-primary transition-colors">shopping_bag</span><span class="font-label-lg text-label-lg">Data Pesanan Masuk</span></div><span class="px-2 py-0.5 rounded-full bg-primary text-on-primary font-label-sm text-label-sm">8</span></a><a class="group flex items-center justify-between px-space-sm py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface transition-all" data-path="verifikasi-pembayaran" href="#"><div class="flex items-center gap-space-sm"><span class="material-symbols-outlined text-[20px] text-tertiary group-hover:text-primary transition-colors">verified</span><span class="font-label-lg text-label-lg">Verifikasi Pembayaran</span></div><span class="px-2 py-0.5 rounded-full bg-primary-container text-on-primary-container font-label-sm text-label-sm">3</span></a><a class="group flex items-center justify-between px-space-sm py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface transition-all" data-path="pengiriman-dan-armada-kurir" href="#"><div class="flex items-center gap-space-sm"><span class="material-symbols-outlined text-[20px] text-tertiary group-hover:text-primary transition-colors">two_wheeler</span><span class="font-label-lg text-label-lg">Pengiriman &amp; Kurir</span></div></a><a class="group flex items-center justify-between px-space-sm py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface transition-all" data-path="pelanggan-dan-mitra-warung" href="#"><div class="flex items-center gap-space-sm"><span class="material-symbols-outlined text-[20px] text-tertiary group-hover:text-primary transition-colors">storefront</span><span class="font-label-lg text-label-lg">Pelanggan &amp; Mitra</span></div></a><a class="group flex items-center justify-between px-space-sm py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface transition-all" data-path="laporan-penjualan" href="#"><div class="flex items-center gap-space-sm"><span class="material-symbols-outlined text-[20px] text-tertiary group-hover:text-primary transition-colors">query_stats</span><span class="font-label-lg text-label-lg">Laporan Penjualan</span></div></a><a class="group flex items-center justify-between px-space-sm py-2.5 rounded-xl text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface transition-all" data-path="pengaturan-toko-dan-rekening" href="#"><div class="flex items-center gap-space-sm"><span class="material-symbols-outlined text-[20px] text-tertiary group-hover:text-primary transition-colors">settings</span><span class="font-label-lg text-label-lg">Pengaturan Toko</span></div></a></nav></div></div><div class="p-space-md flex flex-col gap-space-xs"><div class="flex items-center justify-between px-space-sm py-2 rounded-lg bg-surface-container"><div class="flex items-center gap-space-xs"><span class="w-2.5 h-2.5 rounded-full bg-secondary"></span><span class="font-label-sm text-label-sm text-on-surface-variant">Server Kandang</span></div><span class="font-label-sm text-label-sm font-bold text-secondary">Terhubung</span></div><a class="flex items-center justify-between px-space-sm py-2 rounded-lg text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface transition-colors" data-path="etalase-publik" href="#"><div class="flex items-center gap-space-xs"><span class="material-symbols-outlined text-[18px]">store</span><span class="font-label-md text-label-md">Lihat Toko Publik</span></div><span class="material-symbols-outlined text-[16px]">north_east</span></a></div></aside><div class="pl-72"><header class="fixed top-0 left-72 right-0 h-20 bg-surface/90 backdrop-blur-xl shadow-[0_1px_8px_rgba(0,0,0,0.04)] z-40 flex items-center justify-between px-space-lg"><div class="flex items-center gap-space-md"><div class="flex flex-col"><div class="flex items-center gap-space-xs"><span class="font-headline-sm text-headline-sm text-on-surface font-bold tracking-tight">Bang Zul Egg Market</span><span class="inline-flex items-center px-2 py-0.5 rounded-full bg-primary-fixed text-on-primary-fixed font-label-sm text-label-sm">Sistem Operasional Tanggamus</span></div><div class="flex items-center gap-1.5 mt-0.5"><span class="material-symbols-outlined text-[14px] text-secondary">pin_drop</span><span class="font-body-sm text-body-sm text-on-surface-variant">Pos Operasional: Gisting - Talang Padang - Kota Agung</span></div></div></div><div class="flex items-center gap-space-md"><div class="relative hidden xl:block w-72"><span class="material-symbols-outlined absolute left-3 top-1/2 -translate-y-1/2 text-outline text-[18px]">search</span><input class="w-full pl-9 pr-3 py-1.5 rounded-xl bg-surface-container-lowest text-on-surface placeholder:text-outline font-body-sm text-body-sm focus:outline-none focus:ring-2 focus:ring-primary shadow-sm" placeholder="Cari pesanan, mitra, nota..." type="text"/></div><div class="flex items-center gap-space-xs px-space-sm py-1.5 rounded-full bg-secondary-container/50"><span class="material-symbols-outlined text-secondary text-[16px]">call</span><span class="font-label-sm text-label-sm text-on-secondary-container">CS WA: Aktif</span></div><button class="relative p-2 rounded-full text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface transition-colors"><span class="material-symbols-outlined text-[22px]">notifications</span><span class="absolute top-1 right-1 w-4 h-4 rounded-full bg-error text-on-error font-label-sm text-[10px] flex items-center justify-center font-bold">3</span></button><div class="flex items-center gap-space-sm pl-space-xs"><div class="text-right hidden md:block"><span class="font-label-lg text-label-lg text-on-surface block leading-tight">Bang Zul</span><span class="font-body-sm text-body-sm text-on-surface-variant block leading-tight">Pemilik &amp; Verifikator Kandang</span></div><div class="w-8 h-8 rounded-full bg-primary flex items-center justify-center"><span class="material-symbols-outlined text-on-primary text-[18px]">person</span></div></div></div></header><main class="relative pt-20 bg-surface min-h-[calc(100vh-5rem)] px-space-lg py-space-lg"><div class="flex flex-col w-full">
<!-- Top Breadcrumb & Status Pill -->
<div class="flex flex-wrap items-center justify-between gap-y-3 pb-space-md">
<nav class="flex items-center gap-space-xs text-on-surface-variant font-label-md text-label-md">
<a class="hover:text-primary transition-colors flex items-center gap-1" href="#">
<span class="material-symbols-outlined text-[16px]">home</span> Beranda
      </a>
<span class="text-outline-variant">/</span>
<span class="hover:text-primary transition-colors">Laporan &amp; Keuangan</span>
<span class="text-outline-variant">/</span>
<span class="text-on-surface font-bold">Rekapitulasi Penjualan &amp; Omzet</span>
</nav>
<div class="flex items-center gap-2 px-3 py-1 rounded-full bg-secondary-container/40 text-on-secondary-container font-label-sm text-label-sm">
<span class="w-2 h-2 rounded-full bg-secondary animate-ping"></span>
<span>Sinkronisasi Pembukuan Terakhir: Hari ini, 17:45 WIB</span>
</div>
</div>
<!-- Page Title & Operational Context -->
<div class="flex flex-col lg:flex-row lg:items-end justify-between gap-space-md mb-space-lg">
<div class="max-w-3xl">
<div class="inline-flex items-center gap-1.5 px-2.5 py-0.5 rounded-full bg-primary-fixed text-on-primary-fixed font-label-sm text-label-sm mb-2">
<span class="material-symbols-outlined text-[14px]">analytics</span>
        Rekap Penjualan Agribisnis Wilayah Tanggamus
      </div>
<h1 class="font-headline-lg text-headline-lg text-on-surface font-extrabold tracking-tight">
        Laporan Penjualan &amp; Analisis Omzet Toko
      </h1>
<p class="font-body-md text-body-md text-on-surface-variant mt-1">
        Pantau performa pendapatan harian, estimasi margin kotor, volume perputaran karpet telur, tren kanal pembayaran perbankan/tunai, serta log transaksi komoditas telur se-Kabupaten Tanggamus.
      </p>
</div>
<!-- Export Action Hub -->
<div class="flex items-center gap-space-sm flex-shrink-0">
<button class="inline-flex items-center gap-2 px-space-md py-2.5 rounded-xl bg-surface-container-lowest text-error font-label-lg text-label-lg shadow-sm hover:bg-error-container/30 transition-all">
<span class="material-symbols-outlined text-[20px] text-error">picture_as_pdf</span>
<span>Unduh PDF</span>
</button>
<button class="inline-flex items-center gap-2 px-space-md py-2.5 rounded-xl bg-secondary text-on-secondary font-label-lg text-label-lg shadow-sm hover:opacity-95 transition-all">
<span class="material-symbols-outlined text-[20px]">table_view</span>
<span>Unduh Excel (.XLSX)</span>
</button>
</div>
</div>
<!-- Interactive Query & Filter Bar -->
<div class="p-space-md rounded-2xl bg-surface-container-low shadow-[0_4px_20px_-2px_rgba(245,166,35,0.08)] mb-space-lg">
<div class="grid grid-cols-1 md:grid-cols-12 gap-space-sm items-center">
<!-- Date Range Selector -->
<div class="md:col-span-4 flex flex-col gap-1">
<label class="font-label-sm text-label-sm text-on-surface-variant uppercase tracking-wide">Rentang Waktu</label>
<div class="relative">
<select class="w-full appearance-none pl-9 pr-8 py-2 rounded-xl bg-surface-container-lowest font-body-md text-body-md text-on-surface focus:outline-none focus:ring-2 focus:ring-primary shadow-sm cursor-pointer">
<option>30 Hari Terakhir (1 Okt - 31 Okt 2024)</option>
<option>Hari Ini (31 Oktober 2024)</option>
<option>7 Hari Terakhir</option>
<option>Bulan Ini (Oktober Penuh)</option>
<option>Bulan Lalu (September 2024)</option>
<option>Pilih Rentang Kalender Kustom...</option>
</select>
<span class="material-symbols-outlined absolute left-2.5 top-1/2 -translate-y-1/2 text-outline text-[18px]">calendar_today</span>
<span class="material-symbols-outlined absolute right-2.5 top-1/2 -translate-y-1/2 text-outline text-[18px] pointer-events-none">expand_more</span>
</div>
</div>
<!-- Segment/Channel Selector -->
<div class="md:col-span-4 flex flex-col gap-1">
<label class="font-label-sm text-label-sm text-on-surface-variant uppercase tracking-wide">Segmen Pembeli / Kanal</label>
<div class="relative">
<select class="w-full appearance-none pl-9 pr-8 py-2 rounded-xl bg-surface-container-lowest font-body-md text-body-md text-on-surface focus:outline-none focus:ring-2 focus:ring-primary shadow-sm cursor-pointer">
<option>Semua Saluran &amp; Mitra Pembeli</option>
<option>Warung Makan &amp; Usaha Katering</option>
<option>Konsumen Rumah Tangga (Eceran)</option>
<option>Kios Kelontong &amp; Grosir Pasar</option>
</select>
<span class="material-symbols-outlined absolute left-2.5 top-1/2 -translate-y-1/2 text-outline text-[18px]">storefront</span>
<span class="material-symbols-outlined absolute right-2.5 top-1/2 -translate-y-1/2 text-outline text-[18px] pointer-events-none">expand_more</span>
</div>
</div>
<!-- Cluster Kecamatan Selector -->
<div class="md:col-span-3 flex flex-col gap-1">
<label class="font-label-sm text-label-sm text-on-surface-variant uppercase tracking-wide">Wilayah Pengiriman</label>
<div class="relative">
<select class="w-full appearance-none pl-9 pr-8 py-2 rounded-xl bg-surface-container-lowest font-body-md text-body-md text-on-surface focus:outline-none focus:ring-2 focus:ring-primary shadow-sm cursor-pointer">
<option>Seluruh Tanggamus (5 Cluster)</option>
<option>Kecamatan Gisting</option>
<option>Kecamatan Talang Padang</option>
<option>Kota Agung &amp; Pesisir</option>
<option>Wonosobo - Pugung</option>
</select>
<span class="material-symbols-outlined absolute left-2.5 top-1/2 -translate-y-1/2 text-outline text-[18px]">location_on</span>
<span class="material-symbols-outlined absolute right-2.5 top-1/2 -translate-y-1/2 text-outline text-[18px] pointer-events-none">expand_more</span>
</div>
</div>
<!-- Quick Reset / Refresh Filter -->
<div class="md:col-span-1 flex items-end">
<button class="w-full py-2 rounded-xl bg-surface-container-highest text-on-surface flex items-center justify-center hover:bg-surface-container transition-colors shadow-sm" title="Refresh Data">
<span class="material-symbols-outlined text-[20px]">sync</span>
</button>
</div>
</div>
</div>
<!-- 4 KPI Cards (Key Financial Performance) -->
<div class="grid grid-cols-1 sm:grid-cols-2 xl:grid-cols-4 gap-space-md mb-space-lg">
<!-- Card 1: Total Omzet -->
<div class="p-space-md rounded-2xl bg-surface-container-lowest shadow-[0_4px_20px_-2px_rgba(245,166,35,0.12)] flex flex-col justify-between">
<div>
<div class="flex items-center justify-between">
<span class="font-label-md text-label-md text-on-surface-variant uppercase tracking-wide">Total Omzet Penjualan</span>
<div class="w-9 h-9 rounded-xl bg-primary-container/20 text-primary flex items-center justify-center">
<span class="material-symbols-outlined text-[20px]">payments</span>
</div>
</div>
<div class="mt-3 flex items-baseline gap-2">
<span class="font-price-display text-price-display text-on-surface font-extrabold tracking-tight">Rp 148.650.000</span>
</div>
</div>
<div class="mt-4 pt-3 bg-surface-container-low/40 rounded-xl px-2.5 py-2">
<div class="flex items-center justify-between">
<div class="flex items-center gap-1 text-secondary font-label-md text-label-md">
<span class="material-symbols-outlined text-[16px]">trending_up</span>
<span>+14.8%</span>
</div>
<span class="font-body-sm text-body-sm text-on-surface-variant">1.420 Transaksi Berhasil</span>
</div>
</div>
</div>
<!-- Card 2: Volume Karpet & Kg -->
<div class="p-space-md rounded-2xl bg-surface-container-lowest shadow-[0_4px_20px_-2px_rgba(245,166,35,0.12)] flex flex-col justify-between">
<div>
<div class="flex items-center justify-between">
<span class="font-label-md text-label-md text-on-surface-variant uppercase tracking-wide">Total Telur Terdistribusi</span>
<div class="w-9 h-9 rounded-xl bg-secondary-container/50 text-secondary flex items-center justify-center">
<span class="material-symbols-outlined text-[20px]">egg</span>
</div>
</div>
<div class="mt-3">
<span class="font-price-display text-price-display text-on-surface font-extrabold tracking-tight">2.860 Karpet</span>
<span class="font-label-lg text-label-lg text-on-surface-variant font-medium ml-1">&amp; 940 Kg</span>
</div>
</div>
<div class="mt-4 pt-3 bg-surface-container-low/40 rounded-xl px-2.5 py-2">
<div class="flex items-center justify-between">
<div class="flex items-center gap-1 text-secondary font-label-md text-label-md">
<span class="material-symbols-outlined text-[16px]">trending_up</span>
<span>+8.5%</span>
</div>
<span class="font-body-sm text-body-sm text-on-surface-variant">Rata-rata 95 karpet / hari</span>
</div>
</div>
</div>
<!-- Card 3: AOV (Average Order Value) -->
<div class="p-space-md rounded-2xl bg-surface-container-lowest shadow-[0_4px_20px_-2px_rgba(245,166,35,0.12)] flex flex-col justify-between">
<div>
<div class="flex items-center justify-between">
<span class="font-label-md text-label-md text-on-surface-variant uppercase tracking-wide">Rata-rata Keranjang (AOV)</span>
<div class="w-9 h-9 rounded-xl bg-primary-fixed text-on-primary-fixed flex items-center justify-center">
<span class="material-symbols-outlined text-[20px]">shopping_basket</span>
</div>
</div>
<div class="mt-3">
<span class="font-price-display text-price-display text-on-surface font-extrabold tracking-tight">Rp 104.680</span>
<span class="font-body-sm text-body-sm text-on-surface-variant ml-1">/ pesanan</span>
</div>
</div>
<div class="mt-4 pt-3 bg-surface-container-low/40 rounded-xl px-2.5 py-2">
<div class="flex items-center justify-between">
<div class="flex items-center gap-1 text-secondary font-label-md text-label-md">
<span class="material-symbols-outlined text-[16px]">trending_up</span>
<span>+5.2%</span>
</div>
<span class="font-body-sm text-body-sm text-on-surface-variant truncate">Bundling 2 karpet + bebek</span>
</div>
</div>
</div>
<!-- Card 4: Gross Margin -->
<div class="p-space-md rounded-2xl bg-surface-container-lowest shadow-[0_4px_20px_-2px_rgba(245,166,35,0.12)] flex flex-col justify-between">
<div>
<div class="flex items-center justify-between">
<span class="font-label-md text-label-md text-on-surface-variant uppercase tracking-wide">Estimasi Laba Kotor Toko</span>
<div class="w-9 h-9 rounded-xl bg-secondary-fixed text-on-secondary-fixed flex items-center justify-center">
<span class="material-symbols-outlined text-[20px]">account_balance_wallet</span>
</div>
</div>
<div class="mt-3 flex items-baseline gap-2">
<span class="font-price-display text-price-display text-secondary font-extrabold tracking-tight">Rp 26.750.000</span>
<span class="px-2 py-0.5 rounded-full bg-secondary-container text-on-secondary-container font-label-sm text-label-sm font-bold">18.0%</span>
</div>
</div>
<div class="mt-4 pt-3 bg-surface-container-low/40 rounded-xl px-2.5 py-2">
<span class="font-body-sm text-body-sm text-on-surface-variant block truncate">
          Bersih dari HPP kandang &amp; bensin kurir
        </span>
</div>
</div>
</div>
<!-- Visual Analytics & Chart Grid -->
<div class="grid grid-cols-1 lg:grid-cols-12 gap-space-lg mb-space-lg">
<!-- Left Column: Trend Grafik Omzet (65%) -->
<div class="lg:col-span-8 flex flex-col justify-between p-space-lg rounded-2xl bg-surface-container-lowest shadow-[0_4px_20px_-2px_rgba(245,166,35,0.12)]">
<div>
<!-- Chart Header & Interactive Switcher -->
<div class="flex flex-wrap items-center justify-between gap-y-3 pb-space-md">
<div>
<h2 class="font-headline-md text-headline-md text-on-surface font-bold">
              Tren Penjualan &amp; Omzet Harian (Oktober 2024)
            </h2>
<div class="flex items-center gap-2 mt-1">
<span class="font-body-sm text-body-sm text-on-surface-variant">Menampilkan dinamika omzet harian terhadap target kandang</span>
<span class="w-1.5 h-1.5 rounded-full bg-outline-variant"></span>
<span class="font-label-sm text-label-sm text-secondary font-semibold">Lonjakan: Hari Pasaran Pasar Talang Padang</span>
</div>
</div>
<!-- Toggle Metric View -->
<div class="inline-flex p-1 rounded-xl bg-surface-container font-label-md text-label-md">
<button class="px-3 py-1.5 rounded-lg bg-surface-container-lowest text-on-surface font-bold shadow-sm transition-all" id="btn-chart-omzet">
              Omzet (Rp)
            </button>
<button class="px-3 py-1.5 rounded-lg text-on-surface-variant hover:text-on-surface transition-all" id="btn-chart-qty">
              Volume Karpet
            </button>
</div>
</div>
<!-- Target Line Benchmark Banner -->
<div class="flex flex-wrap items-center justify-between px-3 py-2 rounded-xl bg-surface-container-low mb-space-md text-on-surface-variant font-body-sm text-body-sm">
<div class="flex items-center gap-2">
<span class="w-3 h-0.5 bg-primary block"></span>
<span>Garis Target Harian: <strong class="text-on-surface font-label-md text-label-md">Rp 5.000.000 / hari</strong> (Target Capaian 94.6%)</span>
</div>
<div class="flex items-center gap-4">
<span class="flex items-center gap-1.5 text-on-surface-variant"><span class="w-2.5 h-2.5 rounded-sm bg-primary-container"></span> Hari Biasa</span>
<span class="flex items-center gap-1.5 text-on-surface-variant"><span class="w-2.5 h-2.5 rounded-sm bg-primary"></span> Akhir Pekan / Pasaran</span>
</div>
</div>
<!-- CSS/HTML Scaled Interactive Bar Chart Component -->
<div class="relative pt-6 pb-2">
<!-- Target Line Overlay (Horizontal) -->
<div class="absolute left-10 right-0 top-[38%] border-t-2 border-dashed border-primary/40 pointer-events-none z-10 flex justify-end">
<span class="text-[10px] font-mono text-primary font-bold bg-surface-container-lowest px-1.5 -translate-y-1/2 mr-2">Target Rp 5.0M</span>
</div>
<!-- Chart Grid & Bars Container -->
<div class="h-64 flex items-end justify-between gap-1.5 sm:gap-2 pl-10 pr-2 pb-6 border-b border-surface-container">
<!-- Y-Axis labels (Static reference) -->
<div class="absolute left-0 top-0 bottom-6 flex flex-col justify-between text-[11px] font-mono text-outline select-none">
<span>Rp 7M</span>
<span>Rp 5M</span>
<span>Rp 3M</span>
<span>Rp 1M</span>
<span>Rp 0</span>
</div>
<!-- Bar 1 (1 Okt) -->
<div class="group relative flex-1 flex flex-col items-center h-full justify-end">
<div class="w-full bg-primary-container rounded-t-md transition-all group-hover:bg-primary" style="height: 58%;"></div>
<span class="absolute -bottom-6 text-[10px] text-outline font-label-sm">01</span>
<div class="hidden group-hover:flex flex-col absolute -top-12 z-30 px-2 py-1 bg-inverse-surface text-inverse-on-surface rounded-lg shadow-lg text-[10px] whitespace-nowrap">
<span class="font-bold">1 Okt: Rp 4.250.000</span>
<span>86 Karpet Terjual</span>
</div>
</div>
<!-- Bar 2 (3 Okt) -->
<div class="group relative flex-1 flex flex-col items-center h-full justify-end">
<div class="w-full bg-primary-container rounded-t-md transition-all group-hover:bg-primary" style="height: 64%;"></div>
<span class="absolute -bottom-6 text-[10px] text-outline font-label-sm">03</span>
<div class="hidden group-hover:flex flex-col absolute -top-12 z-30 px-2 py-1 bg-inverse-surface text-inverse-on-surface rounded-lg shadow-lg text-[10px] whitespace-nowrap">
<span class="font-bold">3 Okt: Rp 4.600.000</span>
<span>92 Karpet Terjual</span>
</div>
</div>
<!-- Bar 3 (5 Okt - Sabtu Pasaran) -->
<div class="group relative flex-1 flex flex-col items-center h-full justify-end">
<div class="w-full bg-primary rounded-t-md transition-all group-hover:opacity-90" style="height: 88%;"></div>
<span class="absolute -bottom-6 text-[10px] text-primary font-bold font-label-sm">05*</span>
<div class="hidden group-hover:flex flex-col absolute -top-12 z-30 px-2 py-1 bg-inverse-surface text-inverse-on-surface rounded-lg shadow-lg text-[10px] whitespace-nowrap">
<span class="font-bold text-primary-fixed">5 Okt (Pasaran): Rp 6.250.000</span>
<span>124 Karpet Terjual</span>
</div>
</div>
<!-- Bar 4 (8 Okt) -->
<div class="group relative flex-1 flex flex-col items-center h-full justify-end">
<div class="w-full bg-primary-container rounded-t-md transition-all group-hover:bg-primary" style="height: 52%;"></div>
<span class="absolute -bottom-6 text-[10px] text-outline font-label-sm">08</span>
<div class="hidden group-hover:flex flex-col absolute -top-12 z-30 px-2 py-1 bg-inverse-surface text-inverse-on-surface rounded-lg shadow-lg text-[10px] whitespace-nowrap">
<span class="font-bold">8 Okt: Rp 3.900.000</span>
<span>78 Karpet Terjual</span>
</div>
</div>
<!-- Bar 5 (11 Okt) -->
<div class="group relative flex-1 flex flex-col items-center h-full justify-end">
<div class="w-full bg-primary-container rounded-t-md transition-all group-hover:bg-primary" style="height: 70%;"></div>
<span class="absolute -bottom-6 text-[10px] text-outline font-label-sm">11</span>
<div class="hidden group-hover:flex flex-col absolute -top-12 z-30 px-2 py-1 bg-inverse-surface text-inverse-on-surface rounded-lg shadow-lg text-[10px] whitespace-nowrap">
<span class="font-bold">11 Okt: Rp 5.100.000</span>
<span>102 Karpet Terjual</span>
</div>
</div>
<!-- Bar 6 (14 Okt) -->
<div class="group relative flex-1 flex flex-col items-center h-full justify-end">
<div class="w-full bg-primary-container rounded-t-md transition-all group-hover:bg-primary" style="height: 60%;"></div>
<span class="absolute -bottom-6 text-[10px] text-outline font-label-sm">14</span>
<div class="hidden group-hover:flex flex-col absolute -top-12 z-30 px-2 py-1 bg-inverse-surface text-inverse-on-surface rounded-lg shadow-lg text-[10px] whitespace-nowrap">
<span class="font-bold">14 Okt: Rp 4.400.000</span>
<span>88 Karpet Terjual</span>
</div>
</div>
<!-- Bar 7 (17 Okt) -->
<div class="group relative flex-1 flex flex-col items-center h-full justify-end">
<div class="w-full bg-primary-container rounded-t-md transition-all group-hover:bg-primary" style="height: 76%;"></div>
<span class="absolute -bottom-6 text-[10px] text-outline font-label-sm">17</span>
<div class="hidden group-hover:flex flex-col absolute -top-12 z-30 px-2 py-1 bg-inverse-surface text-inverse-on-surface rounded-lg shadow-lg text-[10px] whitespace-nowrap">
<span class="font-bold">17 Okt: Rp 5.480.000</span>
<span>109 Karpet Terjual</span>
</div>
</div>
<!-- Bar 8 (20 Okt - Akhir Pekan) -->
<div class="group relative flex-1 flex flex-col items-center h-full justify-end">
<div class="w-full bg-primary rounded-t-md transition-all group-hover:opacity-90" style="height: 94%;"></div>
<span class="absolute -bottom-6 text-[10px] text-primary font-bold font-label-sm">20*</span>
<div class="hidden group-hover:flex flex-col absolute -top-12 z-30 px-2 py-1 bg-inverse-surface text-inverse-on-surface rounded-lg shadow-lg text-[10px] whitespace-nowrap">
<span class="font-bold text-primary-fixed">20 Okt: Rp 6.820.000 (Puncak)</span>
<span>136 Karpet Terjual</span>
</div>
</div>
<!-- Bar 9 (23 Okt) -->
<div class="group relative flex-1 flex flex-col items-center h-full justify-end">
<div class="w-full bg-primary-container rounded-t-md transition-all group-hover:bg-primary" style="height: 68%;"></div>
<span class="absolute -bottom-6 text-[10px] text-outline font-label-sm">23</span>
<div class="hidden group-hover:flex flex-col absolute -top-12 z-30 px-2 py-1 bg-inverse-surface text-inverse-on-surface rounded-lg shadow-lg text-[10px] whitespace-nowrap">
<span class="font-bold">23 Okt: Rp 4.900.000</span>
<span>98 Karpet Terjual</span>
</div>
</div>
<!-- Bar 10 (26 Okt - Pasaran Talang Padang) -->
<div class="group relative flex-1 flex flex-col items-center h-full justify-end">
<div class="w-full bg-primary rounded-t-md transition-all group-hover:opacity-90" style="height: 92%;"></div>
<span class="absolute -bottom-6 text-[10px] text-primary font-bold font-label-sm">26*</span>
<div class="hidden group-hover:flex flex-col absolute -top-12 z-30 px-2 py-1 bg-inverse-surface text-inverse-on-surface rounded-lg shadow-lg text-[10px] whitespace-nowrap">
<span class="font-bold text-primary-fixed">26 Okt (Pasaran): Rp 6.600.000</span>
<span>130 Karpet Terjual</span>
</div>
</div>
<!-- Bar 11 (29 Okt) -->
<div class="group relative flex-1 flex flex-col items-center h-full justify-end">
<div class="w-full bg-primary-container rounded-t-md transition-all group-hover:bg-primary" style="height: 65%;"></div>
<span class="absolute -bottom-6 text-[10px] text-outline font-label-sm">29</span>
<div class="hidden group-hover:flex flex-col absolute -top-12 z-30 px-2 py-1 bg-inverse-surface text-inverse-on-surface rounded-lg shadow-lg text-[10px] whitespace-nowrap">
<span class="font-bold">29 Okt: Rp 4.750.000</span>
<span>94 Karpet Terjual</span>
</div>
</div>
<!-- Bar 12 (31 Okt - Hari Ini) -->
<div class="group relative flex-1 flex flex-col items-center h-full justify-end">
<div class="w-full bg-secondary-container rounded-t-md transition-all group-hover:bg-secondary" style="height: 72%;"></div>
<span class="absolute -bottom-6 text-[10px] text-secondary font-bold font-label-sm">31</span>
<div class="hidden group-hover:flex flex-col absolute -top-12 z-30 px-2 py-1 bg-inverse-surface text-inverse-on-surface rounded-lg shadow-lg text-[10px] whitespace-nowrap">
<span class="font-bold text-secondary-fixed">31 Okt: Rp 5.230.000</span>
<span>105 Karpet (Data Berjalan)</span>
</div>
</div>
</div>
</div>
</div>
<!-- Footer Micro Analysis inside Left Card -->
<div class="mt-8 pt-3 border-t border-surface-container flex flex-wrap items-center justify-between gap-2">
<div class="flex items-center gap-2">
<span class="w-2.5 h-2.5 rounded-full bg-secondary"></span>
<span class="font-body-sm text-body-sm text-on-surface">Hari Penjualan Terbaik: <strong>Minggu, 20 Oktober (Rp 6.820.000)</strong></span>
</div>
<a class="font-label-md text-label-md text-primary font-bold hover:underline inline-flex items-center gap-1" href="#">
          Lihat Buku Kas Harian Lengkap <span class="material-symbols-outlined text-[16px]">arrow_forward</span>
</a>
</div>
</div>
<!-- Right Column: 2 Critical Analytical Widgets (35%) -->
<div class="lg:col-span-4 flex flex-col gap-space-lg">
<!-- Widget 1: Proporsi Penjualan per Varian Komoditas -->
<div class="p-space-md rounded-2xl bg-surface-container-lowest shadow-[0_4px_20px_-2px_rgba(245,166,35,0.12)]">
<div class="flex items-center justify-between mb-space-sm">
<div>
<h3 class="font-headline-sm text-headline-sm text-on-surface font-bold">Proporsi Varian Telur</h3>
<span class="font-body-sm text-body-sm text-on-surface-variant">Berdasarkan total omzet kotor</span>
</div>
<span class="material-symbols-outlined text-[20px] text-tertiary">donut_small</span>
</div>
<!-- Stacked Progress Multi-segment Bar -->
<div class="h-3.5 w-full rounded-full bg-surface-container overflow-hidden flex my-3">
<div class="bg-primary-container h-full" style="width: 58%;" title="Telur Ras: 58%"></div>
<div class="bg-secondary h-full" style="width: 19%;" title="Ayam Kampung &amp; Omega: 19%"></div>
<div class="bg-primary h-full" style="width: 14%;" title="Telur Bebek: 14%"></div>
<div class="bg-tertiary h-full" style="width: 9%;" title="Telur Puyuh: 9%"></div>
</div>
<!-- Legend & Value Breakdown -->
<div class="flex flex-col gap-2.5 mt-4">
<div class="flex items-center justify-between text-body-sm font-body-sm">
<div class="flex items-center gap-2">
<span class="w-3 h-3 rounded-full bg-primary-container"></span>
<span class="text-on-surface font-medium">Telur Ayam Ras Super (Karpet)</span>
</div>
<div class="text-right">
<span class="font-bold text-on-surface">58%</span>
<span class="text-on-surface-variant text-[11px] block">Rp 86.2M</span>
</div>
</div>
<div class="flex items-center justify-between text-body-sm font-body-sm">
<div class="flex items-center gap-2">
<span class="w-3 h-3 rounded-full bg-secondary"></span>
<span class="text-on-surface font-medium">Ayam Kampung &amp; Omega-3</span>
</div>
<div class="text-right">
<span class="font-bold text-on-surface">19%</span>
<span class="text-on-surface-variant text-[11px] block">Rp 28.2M</span>
</div>
</div>
<div class="flex items-center justify-between text-body-sm font-body-sm">
<div class="flex items-center gap-2">
<span class="w-3 h-3 rounded-full bg-primary"></span>
<span class="text-on-surface font-medium">Telur Bebek Tambak &amp; Asin</span>
</div>
<div class="text-right">
<span class="font-bold text-on-surface">14%</span>
<span class="text-on-surface-variant text-[11px] block">Rp 20.8M</span>
</div>
</div>
<div class="flex items-center justify-between text-body-sm font-body-sm">
<div class="flex items-center gap-2">
<span class="w-3 h-3 rounded-full bg-tertiary"></span>
<span class="text-on-surface font-medium">Telur Puyuh Segar</span>
</div>
<div class="text-right">
<span class="font-bold text-on-surface">9%</span>
<span class="text-on-surface-variant text-[11px] block">Rp 13.4M</span>
</div>
</div>
</div>
</div>
<!-- Widget 2: Saluran Pembayaran Terbanyak -->
<div class="p-space-md rounded-2xl bg-surface-container-lowest shadow-[0_4px_20px_-2px_rgba(245,166,35,0.12)]">
<div class="flex items-center justify-between mb-3">
<div>
<h3 class="font-headline-sm text-headline-sm text-on-surface font-bold">Metode Pembayaran</h3>
<span class="font-body-sm text-body-sm text-on-surface-variant">Preferensi pelanggan Tanggamus</span>
</div>
<span class="material-symbols-outlined text-[20px] text-tertiary">account_balance</span>
</div>
<div class="space-y-3 mt-3">
<!-- Item 1: Transfer Bank -->
<div>
<div class="flex items-center justify-between font-body-sm text-body-sm mb-1">
<span class="text-on-surface font-medium flex items-center gap-1.5">
<span class="material-symbols-outlined text-[16px] text-primary">credit_card</span>
                Transfer Bank (Lampung, BRI, BCA)
              </span>
<span class="font-bold text-on-surface">46%</span>
</div>
<div class="w-full h-2 rounded-full bg-surface-container overflow-hidden">
<div class="h-full bg-primary rounded-full" style="width: 46%;"></div>
</div>
</div>
<!-- Item 2: COD Kurir -->
<div>
<div class="flex items-center justify-between font-body-sm text-body-sm mb-1">
<span class="text-on-surface font-medium flex items-center gap-1.5">
<span class="material-symbols-outlined text-[16px] text-secondary">handshake</span>
                Bayar di Tempat (COD Titip Kurir)
              </span>
<span class="font-bold text-on-surface">34%</span>
</div>
<div class="w-full h-2 rounded-full bg-surface-container overflow-hidden">
<div class="h-full bg-secondary rounded-full" style="width: 34%;"></div>
</div>
</div>
<!-- Item 3: QRIS Instan -->
<div>
<div class="flex items-center justify-between font-body-sm text-body-sm mb-1">
<span class="text-on-surface font-medium flex items-center gap-1.5">
<span class="material-symbols-outlined text-[16px] text-primary-container">qr_code_2</span>
                QRIS Toko &amp; Dompet Digital
              </span>
<span class="font-bold text-on-surface">20%</span>
</div>
<div class="w-full h-2 rounded-full bg-surface-container overflow-hidden">
<div class="h-full bg-primary-container rounded-full" style="width: 20%;"></div>
</div>
</div>
</div>
</div>
</div>
</div>
<!-- Section 4: Ringkasan Wilayah Pengantaran Terlaris (Kecamatan Tanggamus) -->
<div class="mb-space-lg">
<div class="flex flex-wrap items-center justify-between mb-space-sm">
<div class="flex items-center gap-2">
<span class="material-symbols-outlined text-secondary text-[22px]">explore</span>
<h2 class="font-headline-sm text-headline-sm text-on-surface font-bold">
          Distribusi Omzet per Kecamatan (Tanggamus Raya)
        </h2>
</div>
<span class="font-label-sm text-label-sm text-on-surface-variant">Layanan Antar Roda Dua &amp; Mobil Pickup</span>
</div>
<!-- Horizontal Region Cards Grid -->
<div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-5 gap-space-sm">
<!-- Gisting -->
<div class="p-space-sm rounded-xl bg-surface-container-lowest shadow-sm flex flex-col justify-between">
<div class="flex items-center justify-between">
<span class="font-headline-sm text-[15px] font-bold text-on-surface">Gisting</span>
<span class="px-1.5 py-0.5 rounded bg-primary-container/20 text-on-primary-container font-label-sm text-[10px] font-bold">Peringkat 1</span>
</div>
<div class="mt-2">
<span class="font-headline-sm text-headline-sm text-on-surface block font-extrabold">Rp 46.200.000</span>
<span class="font-body-sm text-body-sm text-on-surface-variant">420 Pesanan Sukses</span>
</div>
<div class="mt-2 pt-2 border-t border-surface-container flex items-center justify-between text-[11px] text-secondary font-semibold">
<span>Pasar Gisting Bawah</span>
<span class="material-symbols-outlined text-[14px]">local_shipping</span>
</div>
</div>
<!-- Talang Padang -->
<div class="p-space-sm rounded-xl bg-surface-container-lowest shadow-sm flex flex-col justify-between">
<div class="flex items-center justify-between">
<span class="font-headline-sm text-[15px] font-bold text-on-surface">Talang Padang</span>
<span class="px-1.5 py-0.5 rounded bg-secondary-container/40 text-on-secondary-container font-label-sm text-[10px] font-bold">Peringkat 2</span>
</div>
<div class="mt-2">
<span class="font-headline-sm text-headline-sm text-on-surface block font-extrabold">Rp 41.500.000</span>
<span class="font-body-sm text-body-sm text-on-surface-variant">385 Pesanan Sukses</span>
</div>
<div class="mt-2 pt-2 border-t border-surface-container flex items-center justify-between text-[11px] text-secondary font-semibold">
<span>Pusat Katering &amp; Warung</span>
<span class="material-symbols-outlined text-[14px]">local_shipping</span>
</div>
</div>
<!-- Kota Agung Pusat -->
<div class="p-space-sm rounded-xl bg-surface-container-lowest shadow-sm flex flex-col justify-between">
<div class="flex items-center justify-between">
<span class="font-headline-sm text-[15px] font-bold text-on-surface">Kota Agung</span>
<span class="px-1.5 py-0.5 rounded bg-surface-container-high text-on-surface-variant font-label-sm text-[10px] font-bold">Peringkat 3</span>
</div>
<div class="mt-2">
<span class="font-headline-sm text-headline-sm text-on-surface block font-extrabold">Rp 33.800.000</span>
<span class="font-body-sm text-body-sm text-on-surface-variant">310 Pesanan Sukses</span>
</div>
<div class="mt-2 pt-2 border-t border-surface-container flex items-center justify-between text-[11px] text-on-surface-variant">
<span>Kawasan Pelabuhan &amp; Kantor</span>
<span class="material-symbols-outlined text-[14px]">local_shipping</span>
</div>
</div>
<!-- Wonosobo & Pugung -->
<div class="p-space-sm rounded-xl bg-surface-container-lowest shadow-sm flex flex-col justify-between">
<div class="flex items-center justify-between">
<span class="font-headline-sm text-[15px] font-bold text-on-surface">Wonosobo &amp; Pugung</span>
<span class="px-1.5 py-0.5 rounded bg-surface-container-high text-on-surface-variant font-label-sm text-[10px] font-bold">Peringkat 4</span>
</div>
<div class="mt-2">
<span class="font-headline-sm text-headline-sm text-on-surface block font-extrabold">Rp 21.200.000</span>
<span class="font-body-sm text-body-sm text-on-surface-variant">205 Pesanan Sukses</span>
</div>
<div class="mt-2 pt-2 border-t border-surface-container flex items-center justify-between text-[11px] text-on-surface-variant">
<span>Pekon Rintisan Kurir</span>
<span class="material-symbols-outlined text-[14px]">local_shipping</span>
</div>
</div>
<!-- Pringsewu Perbatasan & Pulau Panggung -->
<div class="p-space-sm rounded-xl bg-surface-container-lowest shadow-sm flex flex-col justify-between">
<div class="flex items-center justify-between">
<span class="font-headline-sm text-[15px] font-bold text-on-surface truncate">Pulau Panggung / Batas</span>
<span class="px-1.5 py-0.5 rounded bg-surface-container-high text-on-surface-variant font-label-sm text-[10px] font-bold">Peringkat 5</span>
</div>
<div class="mt-2">
<span class="font-headline-sm text-headline-sm text-on-surface block font-extrabold">Rp 5.950.000</span>
<span class="font-body-sm text-body-sm text-on-surface-variant">100 Pesanan Sukses</span>
</div>
<div class="mt-2 pt-2 border-t border-surface-container flex items-center justify-between text-[11px] text-on-surface-variant">
<span>Jalur Lereng Gisting Atas</span>
<span class="material-symbols-outlined text-[14px]">local_shipping</span>
</div>
</div>
</div>
</div>
<!-- Section 5: Tabel Rekapitulasi Transaksi Terverifikasi -->
<div class="rounded-2xl bg-surface-container-lowest shadow-[0_4px_20px_-2px_rgba(245,166,35,0.12)] overflow-hidden mb-space-lg">
<!-- Table Interactive Toolbar -->
<div class="p-space-md border-b border-surface-container flex flex-col lg:flex-row lg:items-center justify-between gap-space-md">
<div>
<h2 class="font-headline-sm text-headline-sm text-on-surface font-bold">
          Rincian Transaksi Penjualan Terverifikasi
        </h2>
<span class="font-body-sm text-body-sm text-on-surface-variant">
          Menampilkan catatan buku kas aktual, pesanan lunas, dan nota faktur komoditas telur.
        </span>
</div>
<div class="flex flex-wrap items-center gap-space-sm">
<!-- Live Table Filter Input -->
<div class="relative w-full sm:w-64">
<span class="material-symbols-outlined absolute left-3 top-1/2 -translate-y-1/2 text-outline text-[18px]">search</span>
<input class="w-full pl-9 pr-3 py-1.5 rounded-xl bg-surface-container-low text-on-surface placeholder:text-outline font-body-sm text-body-sm focus:outline-none focus:ring-2 focus:ring-primary shadow-sm" placeholder="Cari nota, nama, kecamatan..." type="text"/>
</div>
<!-- Status Filter Tablets -->
<div class="flex items-center p-1 rounded-xl bg-surface-container-low font-label-sm text-label-sm">
<button class="px-2.5 py-1 rounded-lg bg-surface-container-lowest text-on-surface font-bold shadow-sm">Semua</button>
<button class="px-2.5 py-1 rounded-lg text-on-surface-variant hover:text-on-surface transition-colors">Lunas &amp; Selesai</button>
<button class="px-2.5 py-1 rounded-lg text-on-surface-variant hover:text-on-surface transition-colors">Dalam Pengantaran</button>
</div>
</div>
</div>
<!-- Data Table Container -->
<div class="overflow-x-auto">
<table class="w-full text-left border-collapse">
<thead>
<tr class="bg-surface-container-low text-on-surface-variant font-label-sm text-label-sm uppercase tracking-wider">
<th class="py-3 px-space-md">No. Nota &amp; Waktu</th>
<th class="py-3 px-space-md">Pelanggan &amp; Kategori</th>
<th class="py-3 px-space-md">Rincian Komoditas</th>
<th class="py-3 px-space-md">Total &amp; Metode</th>
<th class="py-3 px-space-md">Wilayah Antar</th>
<th class="py-3 px-space-md">Status</th>
<th class="py-3 px-space-md text-right">Aksi Dokumen</th>
</tr>
</thead>
<tbody class="divide-y divide-surface-container font-body-sm text-body-sm text-on-surface">
<!-- Row 1 -->
<tr class="hover:bg-surface-container-low/50 transition-colors">
<td class="py-3.5 px-space-md">
<div class="flex flex-col">
<span class="font-mono font-bold text-on-surface">#NOTA-BZ-8821</span>
<span class="text-[11px] text-on-surface-variant">31 Okt 2024, 14:20 WIB</span>
</div>
</td>
<td class="py-3.5 px-space-md">
<div class="flex flex-col">
<span class="font-label-md text-label-md text-on-surface">Warung Soto Barokah</span>
<span class="inline-flex items-center gap-1 text-[11px] text-tertiary">
<span class="material-symbols-outlined text-[13px]">restaurant</span> Mitra Kuliner Rutin
                </span>
</div>
</td>
<td class="py-3.5 px-space-md">
<span class="font-medium">3 Karpet Telur Ras Super</span>
<span class="text-[11px] text-on-surface-variant block">Kualitas A (Fresh Panen Pagi)</span>
</td>
<td class="py-3.5 px-space-md">
<div class="flex flex-col">
<span class="font-label-md text-label-md font-bold text-on-surface">Rp 156.000</span>
<span class="text-[11px] text-secondary font-medium">Transfer Bank Lampung</span>
</div>
</td>
<td class="py-3.5 px-space-md">
<span class="font-medium text-on-surface">Gisting Bawah</span>
<span class="text-[11px] text-on-surface-variant block">Dekat Pasar Induk Gisting</span>
</td>
<td class="py-3.5 px-space-md">
<span class="inline-flex items-center gap-1 px-2.5 py-0.5 rounded-full bg-secondary-container text-on-secondary-container font-label-sm text-[11px] font-bold">
<span class="w-1.5 h-1.5 rounded-full bg-secondary"></span> Selesai &amp; Lunas
              </span>
</td>
<td class="py-3.5 px-space-md text-right">
<div class="inline-flex items-center gap-1 justify-end">
<button class="p-1.5 rounded-lg text-on-surface-variant hover:text-primary hover:bg-surface-container transition-colors" title="Cetak Nota / Struk">
<span class="material-symbols-outlined text-[18px]">receipt_long</span>
</button>
<button class="p-1.5 rounded-lg text-on-surface-variant hover:text-primary hover:bg-surface-container transition-colors" title="Buka Detail Pesanan">
<span class="material-symbols-outlined text-[18px]">visibility</span>
</button>
</div>
</td>
</tr>
<!-- Row 2 -->
<tr class="hover:bg-surface-container-low/50 transition-colors">
<td class="py-3.5 px-space-md">
<div class="flex flex-col">
<span class="font-mono font-bold text-on-surface">#NOTA-BZ-8820</span>
<span class="text-[11px] text-on-surface-variant">31 Okt 2024, 13:05 WIB</span>
</div>
</td>
<td class="py-3.5 px-space-md">
<div class="flex flex-col">
<span class="font-label-md text-label-md text-on-surface">Ibu Megawati Pohan</span>
<span class="inline-flex items-center gap-1 text-[11px] text-tertiary">
<span class="material-symbols-outlined text-[13px]">person</span> Konsumen Rumah Tangga
                </span>
</div>
</td>
<td class="py-3.5 px-space-md">
<span class="font-medium">1 Karpet Telur Omega-3 + 10 Butir Bebek</span>
<span class="text-[11px] text-on-surface-variant block">Kemasan Karton Khusus</span>
</td>
<td class="py-3.5 px-space-md">
<div class="flex flex-col">
<span class="font-label-md text-label-md font-bold text-on-surface">Rp 88.500</span>
<span class="text-[11px] text-primary font-medium">QRIS Instan Statis</span>
</div>
</td>
<td class="py-3.5 px-space-md">
<span class="font-medium text-on-surface">Talang Padang</span>
<span class="text-[11px] text-on-surface-variant block">Komplek Perum Gisting Raya</span>
</td>
<td class="py-3.5 px-space-md">
<span class="inline-flex items-center gap-1 px-2.5 py-0.5 rounded-full bg-secondary-container text-on-secondary-container font-label-sm text-[11px] font-bold">
<span class="w-1.5 h-1.5 rounded-full bg-secondary"></span> Selesai &amp; Lunas
              </span>
</td>
<td class="py-3.5 px-space-md text-right">
<div class="inline-flex items-center gap-1 justify-end">
<button class="p-1.5 rounded-lg text-on-surface-variant hover:text-primary hover:bg-surface-container transition-colors" title="Cetak Nota / Struk">
<span class="material-symbols-outlined text-[18px]">receipt_long</span>
</button>
<button class="p-1.5 rounded-lg text-on-surface-variant hover:text-primary hover:bg-surface-container transition-colors" title="Buka Detail Pesanan">
<span class="material-symbols-outlined text-[18px]">visibility</span>
</button>
</div>
</td>
</tr>
<!-- Row 3 -->
<tr class="hover:bg-surface-container-low/50 transition-colors">
<td class="py-3.5 px-space-md">
<div class="flex flex-col">
<span class="font-mono font-bold text-on-surface">#NOTA-BZ-8819</span>
<span class="text-[11px] text-on-surface-variant">31 Okt 2024, 11:40 WIB</span>
</div>
</td>
<td class="py-3.5 px-space-md">
<div class="flex flex-col">
<span class="font-label-md text-label-md text-on-surface">Martabak Bangka 88</span>
<span class="inline-flex items-center gap-1 text-[11px] text-tertiary">
<span class="material-symbols-outlined text-[13px]">storefront</span> Pedagang Kuliner Malam
                </span>
</div>
</td>
<td class="py-3.5 px-space-md">
<span class="font-medium">5 Karpet Telur Ayam Ras + 30 Butir Bebek</span>
<span class="text-[11px] text-on-surface-variant block">Spesial Adonan Lembut</span>
</td>
<td class="py-3.5 px-space-md">
<div class="flex flex-col">
<span class="font-label-md text-label-md font-bold text-on-surface">Rp 342.000</span>
<span class="text-[11px] text-on-surface-variant font-medium">COD Kasir Kurir Bang Zul</span>
</div>
</td>
<td class="py-3.5 px-space-md">
<span class="font-medium text-on-surface">Kota Agung Pusat</span>
<span class="text-[11px] text-on-surface-variant block">Jalan Samudra No. 12</span>
</td>
<td class="py-3.5 px-space-md">
<span class="inline-flex items-center gap-1 px-2.5 py-0.5 rounded-full bg-primary-container/30 text-on-primary-container font-label-sm text-[11px] font-bold">
<span class="w-1.5 h-1.5 rounded-full bg-primary-container"></span> Terkirim Kurir (COD)
              </span>
</td>
<td class="py-3.5 px-space-md text-right">
<div class="inline-flex items-center gap-1 justify-end">
<button class="p-1.5 rounded-lg text-on-surface-variant hover:text-primary hover:bg-surface-container transition-colors" title="Cetak Nota / Struk">
<span class="material-symbols-outlined text-[18px]">receipt_long</span>
</button>
<button class="p-1.5 rounded-lg text-on-surface-variant hover:text-primary hover:bg-surface-container transition-colors" title="Buka Detail Pesanan">
<span class="material-symbols-outlined text-[18px]">visibility</span>
</button>
</div>
</td>
</tr>
<!-- Row 4 -->
<tr class="hover:bg-surface-container-low/50 transition-colors">
<td class="py-3.5 px-space-md">
<div class="flex flex-col">
<span class="font-mono font-bold text-on-surface">#NOTA-BZ-8818</span>
<span class="text-[11px] text-on-surface-variant">31 Okt 2024, 10:15 WIB</span>
</div>
</td>
<td class="py-3.5 px-space-md">
<div class="flex flex-col">
<span class="font-label-md text-label-md text-on-surface">Katering Bu Heni Novita</span>
<span class="inline-flex items-center gap-1 text-[11px] text-tertiary">
<span class="material-symbols-outlined text-[13px]">soup_kitchen</span> Dapur Katering Hajatan
                </span>
</div>
</td>
<td class="py-3.5 px-space-md">
<span class="font-medium">10 Karpet Telur Ras (Sortir Pilihan)</span>
<span class="text-[11px] text-on-surface-variant block">Pesanan Paket Resepsi Pernikahan</span>
</td>
<td class="py-3.5 px-space-md">
<div class="flex flex-col">
<span class="font-label-md text-label-md font-bold text-on-surface">Rp 515.000</span>
<span class="text-[11px] text-secondary font-medium">Transfer BRI Rekening Toko</span>
</div>
</td>
<td class="py-3.5 px-space-md">
<span class="font-medium text-on-surface">Talang Padang</span>
<span class="text-[11px] text-on-surface-variant block">Dusun Sukarame Pekon 3</span>
</td>
<td class="py-3.5 px-space-md">
<span class="inline-flex items-center gap-1 px-2.5 py-0.5 rounded-full bg-secondary-container text-on-secondary-container font-label-sm text-[11px] font-bold">
<span class="w-1.5 h-1.5 rounded-full bg-secondary"></span> Selesai &amp; Lunas
              </span>
</td>
<td class="py-3.5 px-space-md text-right">
<div class="inline-flex items-center gap-1 justify-end">
<button class="p-1.5 rounded-lg text-on-surface-variant hover:text-primary hover:bg-surface-container transition-colors" title="Cetak Nota / Struk">
<span class="material-symbols-outlined text-[18px]">receipt_long</span>
</button>
<button class="p-1.5 rounded-lg text-on-surface-variant hover:text-primary hover:bg-surface-container transition-colors" title="Buka Detail Pesanan">
<span class="material-symbols-outlined text-[18px]">visibility</span>
</button>
</div>
</td>
</tr>
<!-- Row 5 -->
<tr class="hover:bg-surface-container-low/50 transition-colors">
<td class="py-3.5 px-space-md">
<div class="flex flex-col">
<span class="font-mono font-bold text-on-surface">#NOTA-BZ-8817</span>
<span class="text-[11px] text-on-surface-variant">31 Okt 2024, 08:30 WIB</span>
</div>
</td>
<td class="py-3.5 px-space-md">
<div class="flex flex-col">
<span class="font-label-md text-label-md text-on-surface">Toko Kelontong Barokah Jaya</span>
<span class="inline-flex items-center gap-1 text-[11px] text-tertiary">
<span class="material-symbols-outlined text-[13px]">inventory</span> Grosir Pengecer Desa
                </span>
</div>
</td>
<td class="py-3.5 px-space-md">
<span class="font-medium">15 Karpet Telur Ras + 1 Peti Telur Asin</span>
<span class="text-[11px] text-on-surface-variant block">Pengiriman Pickup Armada 01</span>
</td>
<td class="py-3.5 px-space-md">
<div class="flex flex-col">
<span class="font-label-md text-label-md font-bold text-on-surface">Rp 890.000</span>
<span class="text-[11px] text-secondary font-medium">BCA Klik Bisnis</span>
</div>
</td>
<td class="py-3.5 px-space-md">
<span class="font-medium text-on-surface">Wonosobo Tanggamus</span>
<span class="text-[11px] text-on-surface-variant block">Pasar Wonosobo Kios No. 4</span>
</td>
<td class="py-3.5 px-space-md">
<span class="inline-flex items-center gap-1 px-2.5 py-0.5 rounded-full bg-secondary-container text-on-secondary-container font-label-sm text-[11px] font-bold">
<span class="w-1.5 h-1.5 rounded-full bg-secondary"></span> Selesai &amp; Lunas
              </span>
</td>
<td class="py-3.5 px-space-md text-right">
<div class="inline-flex items-center gap-1 justify-end">
<button class="p-1.5 rounded-lg text-on-surface-variant hover:text-primary hover:bg-surface-container transition-colors" title="Cetak Nota / Struk">
<span class="material-symbols-outlined text-[18px]">receipt_long</span>
</button>
<button class="p-1.5 rounded-lg text-on-surface-variant hover:text-primary hover:bg-surface-container transition-colors" title="Buka Detail Pesanan">
<span class="material-symbols-outlined text-[18px]">visibility</span>
</button>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<!-- Table Pagination Footer -->
<div class="p-space-md border-t border-surface-container flex flex-wrap items-center justify-between gap-y-3">
<div class="font-body-sm text-body-sm text-on-surface-variant">
        Menampilkan <span class="font-bold text-on-surface">1 - 5</span> dari <span class="font-bold text-on-surface">1.420</span> transaksi terverifikasi
      </div>
<div class="inline-flex items-center gap-1">
<button class="px-3 py-1.5 rounded-lg bg-surface-container text-on-surface-variant font-label-md text-label-md hover:bg-surface-container-high transition-colors disabled:opacity-50">
          Sebelumnya
        </button>
<button class="w-8 h-8 rounded-lg bg-primary-container text-on-primary-container font-label-md text-label-md font-bold shadow-sm">
          1
        </button>
<button class="w-8 h-8 rounded-lg bg-surface-container text-on-surface-variant font-label-md text-label-md hover:bg-surface-container-high transition-colors">
          2
        </button>
<button class="w-8 h-8 rounded-lg bg-surface-container text-on-surface-variant font-label-md text-label-md hover:bg-surface-container-high transition-colors">
          3
        </button>
<span class="px-1 text-outline">...</span>
<button class="w-8 h-8 rounded-lg bg-surface-container text-on-surface-variant font-label-md text-label-md hover:bg-surface-container-high transition-colors">
          142
        </button>
<button class="px-3 py-1.5 rounded-lg bg-surface-container text-on-surface-variant font-label-md text-label-md hover:bg-surface-container-high transition-colors">
          Selanjutnya
        </button>
</div>
</div>
</div>
<!-- Operational Closing Note -->
<div class="flex items-center justify-between p-space-md rounded-2xl bg-surface-container-low text-on-surface-variant text-body-sm font-body-sm">
<div class="flex items-center gap-2">
<span class="material-symbols-outlined text-[18px] text-secondary">verified_user</span>
<span>Seluruh kalkulasi omzet telah diaudit otomatis dengan catatan stok telur keluar dari Kandang Utama Gisting.</span>
</div>
<div class="hidden md:flex items-center gap-3">
<span>Verifikator: <strong>Bang Zul Tanggamus</strong></span>
<span>•</span>
<span>ID Sistem: <strong>BZ-ERP-2024-TGM</strong></span>
</div>
</div>
</div>
<script>
  // Simple Toggle interaction between Omzet & Volume Qty Button
  const btnOmzet = document.getElementById('btn-chart-omzet');
  const btnQty = document.getElementById('btn-chart-qty');

  if(btnOmzet && btnQty) {
    btnOmzet.addEventListener('click', () => {
      btnOmzet.className = 'px-3 py-1.5 rounded-lg bg-surface-container-lowest text-on-surface font-bold shadow-sm transition-all';
      btnQty.className = 'px-3 py-1.5 rounded-lg text-on-surface-variant hover:text-on-surface transition-all';
    });

    btnQty.addEventListener('click', () => {
      btnQty.className = 'px-3 py-1.5 rounded-lg bg-surface-container-lowest text-on-surface font-bold shadow-sm transition-all';
      btnOmzet.className = 'px-3 py-1.5 rounded-lg text-on-surface-variant hover:text-on-surface transition-all';
    });
  }
</script></main></div></body></html>
```
