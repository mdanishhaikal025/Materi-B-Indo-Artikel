<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ringkasan Artikel Ilmiah Populer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap');
        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-color: #f8fafc;
        }
        .gradient-banner {
            background: linear-gradient(135deg, #4f46e5 0%, #7c3aed 50%, #2563eb 100%);
        }
        .card-hover {
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }
        .card-hover:hover {
            transform: translateY(-4px);
            box-shadow: 0 12px 24px -8px rgba(79, 70, 229, 0.15);
        }
    </style>
</head>
<body class="text-slate-800 antialiased pb-12">

    <!-- Header / Banner Infografis -->
    <header class="gradient-banner text-white pt-10 pb-16 px-4 relative overflow-hidden">
        <div class="absolute -right-10 -bottom-10 opacity-10">
            <i class="fa-solid fa-newspaper text-9xl"></i>
        </div>
        <div class="max-w-5xl mx-auto text-center relative z-10">
            <span class="inline-block bg-white/20 backdrop-blur-md text-amber-300 font-semibold px-4 py-1.5 rounded-full text-xs uppercase tracking-wider mb-4 border border-white/20">
                <i class="fa-solid fa-lightbulb mr-1.5"></i> Panduan Visual Praktis
            </span>
            <h1 class="text-3xl md:text-5xl font-extrabold tracking-tight mb-4">
                Artikel Ilmiah Populer
            </h1>
            <p class="text-indigo-100 text-base md:text-lg max-w-2xl mx-auto font-normal leading-relaxed">
                Menyulap riset dan fakta sains yang rumit menjadi sajian tulisan yang renyah, seru, dan mudah dicerna semua orang!
            </p>
        </div>
    </header>

    <main class="max-w-5xl mx-auto px-4 -mt-8 relative z-20 space-y-8">

        <!-- 1. APA ITU ARTIKEL ILMIAH POPULER? -->
        <section class="bg-white rounded-2xl p-6 md:p-8 shadow-sm border border-slate-100 card-hover">
            <div class="flex items-center gap-3 mb-6">
                <div class="w-10 h-10 rounded-xl bg-indigo-100 text-indigo-600 flex items-center justify-center font-bold text-xl">
                    <i class="fa-solid fa-book-open"></i>
                </div>
                <h2 class="text-2xl font-bold text-slate-900">1. Apa Itu Artikel Ilmiah Populer?</h2>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                <!-- Komponen 1 -->
                <div class="p-5 rounded-xl bg-indigo-50/60 border border-indigo-100">
                    <div class="w-10 h-10 rounded-lg bg-indigo-600 text-white flex items-center justify-center mb-3">
                        <i class="fa-solid fa-flask text-lg"></i>
                    </div>
                    <h3 class="font-bold text-indigo-950 mb-1">Berbasis Ilmiah</h3>
                    <p class="text-sm text-slate-600">Berisi fakta, data, riset, atau temuan ilmiah teruji. Bukan karangan opini kosong.</p>
                </div>
                <!-- Komponen 2 -->
                <div class="p-5 rounded-xl bg-purple-50/60 border border-purple-100">
                    <div class="w-10 h-10 rounded-lg bg-purple-600 text-white flex items-center justify-center mb-3">
                        <i class="fa-solid fa-comments text-lg"></i>
                    </div>
                    <h3 class="font-bold text-purple-950 mb-1">Gaya Populer</h3>
                    <p class="text-sm text-slate-600">Bahasa komunikatif, santai, dan tidak kaku. Bebas dari jargon teknik berlebihan.</p>
                </div>
                <!-- Komponen 3 -->
                <div class="p-5 rounded-xl bg-emerald-50/60 border border-emerald-100">
                    <div class="w-10 h-10 rounded-lg bg-emerald-600 text-white flex items-center justify-center mb-3">
                        <i class="fa-solid fa-users text-lg"></i>
                    </div>
                    <h3 class="font-bold text-emerald-950 mb-1">Untuk Publik Awam</h3>
                    <p class="text-sm text-slate-600">Ditujukan bagi pembaca umum, agar sains bisa dipahami tanpa perlu gelar akademik.</p>
                </div>
            </div>
        </section>

        <!-- 2. PERBANDINGAN: ILMIAH MURNI VS ILMIAH POPULER -->
        <section class="bg-white rounded-2xl p-6 md:p-8 shadow-sm border border-slate-100 card-hover">
            <div class="flex items-center gap-3 mb-6">
                <div class="w-10 h-10 rounded-xl bg-amber-100 text-amber-600 flex items-center justify-center font-bold text-xl">
                    <i class="fa-solid fa-scale-balanced"></i>
                </div>
                <h2 class="text-2xl font-bold text-slate-900">2. Artikel Ilmiah Murni vs Populer</h2>
            </div>

            <div class="overflow-x-auto">
                <table class="w-full text-left border-collapse">
                    <thead>
                        <tr class="border-b border-slate-200 bg-slate-50 text-slate-700 text-sm">
                            <th class="p-3.5 rounded-l-xl">Aspek</th>
                            <th class="p-3.5 text-blue-700">Artikel Ilmiah Murni</th>
                            <th class="p-3.5 text-emerald-700 rounded-r-xl">Artikel Ilmiah Populer</th>
                        </tr>
                    </thead>
                    <tbody class="divide-y divide-slate-100 text-sm">
                        <tr>
                            <td class="p-3.5 font-semibold text-slate-900">Pembaca</td>
                            <td class="p-3.5 text-slate-600">Dosen, Peneliti, Akademisi</td>
                            <td class="p-3.5 text-emerald-700 font-medium">Masyarakat Umum & Awam</td>
                        </tr>
                        <tr>
                            <td class="p-3.5 font-semibold text-slate-900">Gaya Bahasa</td>
                            <td class="p-3.5 text-slate-600">Formal, Baku, Banyak istilah teknis</td>
                            <td class="p-3.5 text-emerald-700 font-medium">Santai, Komunikatif, Menggunakan Analogi</td>
                        </tr>
                        <tr>
                            <td class="p-3.5 font-semibold text-slate-900">Struktur Penulisan</td>
                            <td class="p-3.5 text-slate-600">Kaku (KTI/IMRaD: Bab I-V)</td>
                            <td class="p-3.5 text-emerald-700 font-medium">Bebas & Fleksibel (Esai / Narasi)</td>
                        </tr>
                        <tr>
                            <td class="p-3.5 font-semibold text-slate-900">Media Publikasi</td>
                            <td class="p-3.5 text-slate-600">Jurnal Ilmiah, Skripsi, Disertasi</td>
                            <td class="p-3.5 text-emerald-700 font-medium">Koran, Majalah, Blog, Media Sosial</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </section>

        <!-- 3. STRUKTUR UTAMA PENULISAN -->
        <section class="bg-white rounded-2xl p-6 md:p-8 shadow-sm border border-slate-100 card-hover">
            <div class="flex items-center gap-3 mb-6">
                <div class="w-10 h-10 rounded-xl bg-pink-100 text-pink-600 flex items-center justify-center font-bold text-xl">
                    <i class="fa-solid fa-cubes"></i>
                </div>
                <h2 class="text-2xl font-bold text-slate-900">3. Struktur Anatomi Artikel</h2>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                <!-- Judul -->
                <div class="p-4 rounded-xl border border-rose-200 bg-rose-50/40 flex gap-4 items-start">
                    <span class="w-8 h-8 rounded-full bg-rose-500 text-white flex items-center justify-center font-bold text-sm shrink-0">1</span>
                    <div>
                        <h3 class="font-bold text-slate-900 text-base">Judul Ciamik (Catchy Title)</h3>
                        <p class="text-xs text-slate-600 mt-1">Singkat, provokatif, dan memancing rasa ingin tahu pembaca. Hindari judul kaku seperti judul skripsi.</p>
                        <div class="mt-2 text-xs bg-white p-2 rounded border border-rose-200 text-rose-700 italic">
                            <i class="fa-regular fa-lightbulb mr-1"></i> Contoh: "Mengapa Kita Sering Tidur Lagi Setelah Alarm?"
                        </div>
                    </div>
                </div>

                <!-- Pendahuluan / Lead -->
                <div class="p-4 rounded-xl border border-sky-200 bg-sky-50/40 flex gap-4 items-start">
                    <span class="w-8 h-8 rounded-full bg-sky-500 text-white flex items-center justify-center font-bold text-sm shrink-0">2</span>
                    <div>
                        <h3 class="font-bold text-slate-900 text-base">Pendahuluan (Pembuka / Hook)</h3>
                        <p class="text-xs text-slate-600 mt-1">Mengaitkan topik sains dengan cerita sehari-hari, fenomena hangat, atau pertanyaan unik untuk memikat pembaca.</p>
                    </div>
                </div>

                <!-- Isi & Pembahasan -->
                <div class="p-4 rounded-xl border border-violet-200 bg-violet-50/40 flex gap-4 items-start">
                    <span class="w-8 h-8 rounded-full bg-violet-500 text-white flex items-center justify-center font-bold text-sm shrink-0">3</span>
                    <div>
                        <h3 class="font-bold text-slate-900 text-base">Isi & Penjelasan Ilmiah</h3>
                        <p class="text-xs text-slate-600 mt-1">Penjelasan fakta sains dengan contoh konkret, ilustrasi, atau perumpamaan (analogi) agar fakta teknis terasa ringan.</p>
                    </div>
                </div>

                <!-- Penutup -->
                <div class="p-4 rounded-xl border border-emerald-200 bg-emerald-50/40 flex gap-4 items-start">
                    <span class="w-8 h-8 rounded-full bg-emerald-500 text-white flex items-center justify-center font-bold text-sm shrink-0">4</span>
                    <div>
                        <h3 class="font-bold text-slate-900 text-base">Penutup & Pesan Praktis</h3>
                        <p class="text-xs text-slate-600 mt-1">Ringkasan temuan, refleksi, serta pesan/solusi praktis yang bisa langsung diterapkan oleh pembaca.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- 4. RUMUS & RAHASIA TULISAN POPULER MENARIK -->
        <section class="bg-gradient-to-br from-indigo-900 to-slate-900 text-white rounded-2xl p-6 md:p-8 shadow-md">
            <div class="text-center max-w-xl mx-auto mb-8">
                <span class="bg-indigo-500/30 text-indigo-300 border border-indigo-400/30 text-xs px-3 py-1 rounded-full uppercase font-semibold">Trik Khusus Penulis</span>
                <h2 class="text-2xl font-bold mt-2">Formula "3E" Penulisan Populer</h2>
                <p class="text-sm text-indigo-200 mt-1">Pastikan artikel ilmiah populer yang kamu buat memenuhi tiga kaidah emas ini:</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-6 text-center">
                <div class="p-5 rounded-xl bg-white/5 border border-white/10 backdrop-blur-sm">
                    <div class="w-12 h-12 rounded-full bg-indigo-500 text-white flex items-center justify-center mx-auto mb-3 text-xl font-bold">
                        E1
                    </div>
                    <h3 class="font-bold text-lg text-indigo-200 mb-1">Educational</h3>
                    <p class="text-xs text-slate-300">Tetap menyampaikan kebenaran data dan fakta sains yang valid.</p>
                </div>

                <div class="p-5 rounded-xl bg-white/5 border border-white/10 backdrop-blur-sm">
                    <div class="w-12 h-12 rounded-full bg-pink-500 text-white flex items-center justify-center mx-auto mb-3 text-xl font-bold">
                        E2
                    </div>
                    <h3 class="font-bold text-lg text-pink-200 mb-1">Empathetic</h3>
                    <p class="text-xs text-slate-300">Paham sudut pandang dan tingkat pemahaman pembaca awam.</p>
                </div>

                <div class="p-5 rounded-xl bg-white/5 border border-white/10 backdrop-blur-sm">
                    <div class="w-12 h-12 rounded-full bg-amber-500 text-white flex items-center justify-center mx-auto mb-3 text-xl font-bold">
                        E3
                    </div>
                    <h3 class="font-bold text-lg text-amber-200 mb-1">Entertaining</h3>
                    <p class="text-xs text-slate-300">Disampaikan dengan alur cerita menarik, lucu, atau menyentuh.</p>
                </div>
            </div>
        </section>

        <!-- 5. LANGKAH PENULISAN -->
        <section class="bg-white rounded-2xl p-6 md:p-8 shadow-sm border border-slate-100 card-hover">
            <div class="flex items-center gap-3 mb-6">
                <div class="w-10 h-10 rounded-xl bg-cyan-100 text-cyan-600 flex items-center justify-center font-bold text-xl">
                    <i class="fa-solid fa-list-check"></i>
                </div>
                <h2 class="text-2xl font-bold text-slate-900">5. 4 Langkah Mudah Mulai Menulis</h2>
            </div>

            <div class="space-y-4">
                <div class="flex items-start gap-4 p-4 rounded-xl bg-slate-50 border border-slate-200/80">
                    <div class="w-8 h-8 rounded-lg bg-cyan-600 text-white flex items-center justify-center font-bold text-sm shrink-0">L1</div>
                    <div>
                        <h3 class="font-bold text-slate-900 text-sm">Pilih Isu Dekat & Menarik</h3>
                        <p class="text-xs text-slate-600">Cari isu keseharian (gadget, pola tidur, makanan, cuaca, psikologi manusia).</p>
                    </div>
                </div>

                <div class="flex items-start gap-4 p-4 rounded-xl bg-slate-50 border border-slate-200/80">
                    <div class="w-8 h-8 rounded-lg bg-cyan-600 text-white flex items-center justify-center font-bold text-sm shrink-0">L2</div>
                    <div>
                        <h3 class="font-bold text-slate-900 text-sm">Kumpulkan Riset Rujukan</h3>
                        <p class="text-xs text-slate-600">Cari jurnal ilmiah atau sumber terpercaya sebagai fondasi kebenaran tulisan.</p>
                    </div>
                </div>

                <div class="flex items-start gap-4 p-4 rounded-xl bg-slate-50 border border-slate-200/80">
                    <div class="w-8 h-8 rounded-lg bg-cyan-600 text-white flex items-center justify-center font-bold text-sm shrink-0">L3</div>
                    <div>
                        <h3 class="font-bold text-slate-900 text-sm">Sederhanakan Istilah Rumit</h3>
                        <p class="text-xs text-slate-600">Ganti istilah latin/teknis dengan bahasa sederhana atau perumpamaan kehidupan sehari-hari.</p>
                    </div>
                </div>

                <div class="flex items-start gap-4 p-4 rounded-xl bg-slate-50 border border-slate-200/80">
                    <div class="w-8 h-8 rounded-lg bg-cyan-600 text-white flex items-center justify-center font-bold text-sm shrink-0">L4</div>
                    <div>
                        <h3 class="font-bold text-slate-900 text-sm">Baca Ulang & Uji ke Pembaca Awam</h3>
                        <p class="text-xs text-slate-600">Minta teman non-eksakta membaca. Jika mereka mengerti dengan mudah, artikelmu sukses!</p>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <footer class="text-center text-slate-500 text-xs mt-12">
        <p>© Ringkasan Materi Bahasa Indonesia & Penulisan Ilmiah Populer</p>
    </footer>

</body>
</html