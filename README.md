# bakulan-catering
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Monzi Catering | Premium Food Catering in Seremban, KL & Selangor</title>
  <meta name="description" content="Monzi Catering provides premium halal-friendly food catering for weddings, corporate events, and private parties in Seremban, KL & Selangor. Instant WhatsApp booking." />
  <meta name="keywords" content="catering, food catering, wedding catering, corporate catering, buffet, Malaysia, Seremban, Kuala Lumpur, Selangor" />
  <meta property="og:title" content="Monzi Catering – Premium Food Catering" />
  <meta property="og:description" content="Buffet & dome sets for weddings, corporate & private events. Instant WhatsApp booking." />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="https://picsum.photos/1200/630?random=1" />
  <meta name="twitter:card" content="summary_large_image" />

  <!-- Tailwind CSS (CDN for speed). For production, you can swap to a precompiled CSS if you prefer. -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            brand: {
              50: '#f0fdf4',
              100: '#dcfce7',
              200: '#bbf7d0',
              300: '#86efac',
              400: '#4ade80',
              500: '#22c55e',
              600: '#16a34a',
              700: '#15803d',
              800: '#166534',
              900: '#14532d'
            }
          }
        }
      }
    }
  </script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <style>
    html { scroll-behavior: smooth; }
    body { font-family: Inter, system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif; }
    /* Simple container utility for max width */
    .wrap { max-width: 1100px; margin-inline: auto; }
  </style>
</head>
<body class="bg-white text-slate-800">
  <!-- Top Bar -->
  <div class="bg-slate-900 text-white text-sm">
    <div class="wrap px-4 py-2 flex flex-col sm:flex-row gap-2 sm:items-center sm:justify-between">
      <div>Halal-friendly • Wedding • Corporate • Private Events</div>
      <div class="flex items-center gap-4">
        <a href="tel:+60123456789" class="hover:underline">Call: +60 12-345 6789</a>
        <a href="#contact" class="hover:underline">Get a Quote</a>
      </div>
    </div>
  </div>

  <!-- Header / Nav -->
  <header class="sticky top-0 z-40 bg-white/90 backdrop-blur border-b border-slate-200">
    <nav class="wrap px-4 py-3 flex items-center justify-between">
      <a href="#" class="flex items-center gap-2">
        <span class="inline-flex h-9 w-9 items-center justify-center rounded-xl bg-brand-600 text-white font-bold">MC</span>
        <span class="font-semibold text-slate-900">Monzi Catering</span>
      </a>
      <div class="hidden md:flex items-center gap-6 text-sm">
        <a href="#services" class="hover:text-brand-700">Services</a>
        <a href="#menus" class="hover:text-brand-700">Menus</a>
        <a href="#gallery" class="hover:text-brand-700">Gallery</a>
        <a href="#testimonials" class="hover:text-brand-700">Testimonials</a>
        <a href="#faq" class="hover:text-brand-700">FAQ</a>
        <a href="#contact" class="inline-flex items-center gap-2 px-3 py-2 rounded-xl bg-brand-600 text-white hover:bg-brand-700">WhatsApp</a>
      </div>
      <a href="#contact" class="md:hidden inline-flex items-center gap-2 px-3 py-2 rounded-xl bg-brand-600 text-white">WhatsApp</a>
    </nav>
  </header>

  <!-- Hero -->
  <section class="wrap px-4 pt-10 pb-8 md:pt-16 md:pb-12 grid md:grid-cols-2 gap-8 items-center">
    <div>
      <h1 class="text-3xl md:text-5xl font-extrabold leading-tight text-slate-900">Premium Food Catering in <span class="text-brand-700">Seremban, KL & Selangor</span></h1>
      <p class="mt-4 text-lg text-slate-600">Buffet, dome sets & canapés for weddings, corporate events and private parties. Fresh ingredients, beautiful presentation, on-time delivery.</p>
      <div class="mt-6 flex flex-wrap gap-3">
        <a href="#menus" class="px-5 py-3 rounded-xl bg-brand-600 text-white hover:bg-brand-700">View Menus</a>
        <a href="#contact" class="px-5 py-3 rounded-xl border border-slate-300 hover:bg-slate-50">Get Instant Quote</a>
      </div>
      <div class="mt-4 text-sm text-slate-500">Average lead time 3–7 days • Min. 30 pax • Custom menus available</div>
    </div>
    <div class="relative">
      <img src="https://images.unsplash.com/photo-1544025162-d76694265947?q=80&w=1600&auto=format&fit=crop" alt="Buffet catering" class="rounded-2xl shadow-lg w-full h-[320px] md:h-[420px] object-cover" loading="lazy" />
      <div class="absolute -bottom-4 -left-4 bg-white rounded-2xl shadow p-4 hidden md:block">
        <div class="text-3xl font-extrabold text-brand-700">500+</div>
        <div class="text-sm text-slate-600">Events served since 2021</div>
      </div>
    </div>
  </section>

  <!-- Trust badges -->
  <section class="wrap px-4 pb-6 grid grid-cols-2 sm:grid-cols-4 gap-3">
    <div class="p-4 rounded-xl border text-center">
      <div class="font-bold">Halal-friendly</div>
      <div class="text-sm text-slate-600">Certified suppliers</div>
    </div>
    <div class="p-4 rounded-xl border text-center">
      <div class="font-bold">On-time</div>
      <div class="text-sm text-slate-600">98% punctuality</div>
    </div>
    <div class="p-4 rounded-xl border text-center">
      <div class="font-bold">Fresh & Tasty</div>
      <div class="text-sm text-slate-600">Chef‑crafted menus</div>
    </div>
    <div class="p-4 rounded-xl border text-center">
      <div class="font-bold">Full Service</div>
      <div class="text-sm text-slate-600">Setup & cleanup</div>
    </div>
  </section>

  <!-- Services / Packages -->
  <section id="services" class="bg-slate-50 py-14">
    <div class="wrap px-4">
      <h2 class="text-2xl md:text-3xl font-bold">Packages & Services</h2>
      <p class="mt-2 text-slate-600">Simple pricing. Customisation available.</p>
      <div class="mt-8 grid md:grid-cols-3 gap-6">
        <!-- Package 1 -->
        <div class="rounded-2xl bg-white border p-6 flex flex-col">
          <div class="text-sm uppercase tracking-wide text-brand-700 font-semibold">Buffet Set</div>
          <div class="mt-2 text-3xl font-extrabold">From RM25<span class="text-base font-semibold text-slate-500">/pax</span></div>
          <ul class="mt-4 space-y-2 text-slate-700">
            <li>✅ 4 mains + 2 sides + dessert</li>
            <li>✅ Drinks station</li>
            <li>✅ Warmers & utensils</li>
            <li>✅ On‑site staff (2–4)</li>
          </ul>
          <a href="#contact" class="mt-6 inline-flex justify-center px-4 py-2 rounded-xl bg-brand-600 text-white hover:bg-brand-700">Get Quote</a>
        </div>
        <!-- Package 2 -->
        <div class="rounded-2xl bg-white border p-6 flex flex-col ring-2 ring-brand-600">
          <div class="text-sm uppercase tracking-wide text-brand-700 font-semibold">Dome / VIP</div>
          <div class="mt-2 text-3xl font-extrabold">From RM45<span class="text-base font-semibold text-slate-500">/pax</span></div>
          <ul class="mt-4 space-y-2 text-slate-700">
            <li>✅ 6 mains + 3 sides + dessert</li>
            <li>✅ Beverages + tea/coffee</li>
            <li>✅ Premium setup & décor</li>
            <li>✅ Dedicated supervisor</li>
          </ul>
          <a href="#contact" class="mt-6 inline-flex justify-center px-4 py-2 rounded-xl bg-brand-600 text-white hover:bg-brand-700">Reserve Slot</a>
        </div>
        <!-- Package 3 -->
        <div class="rounded-2xl bg-white border p-6 flex flex-col">
          <div class="text-sm uppercase tracking-wide text-brand-700 font-semibold">Canapés / Live</div>
          <div class="mt-2 text-3xl font-extrabold">From RM30<span class="text-base font-semibold text-slate-500">/pax</span></div>
          <ul class="mt-4 space-y-2 text-slate-700">
            <li>✅ Hand‑passed appetisers</li>
            <li>✅ Live pasta / grill station</li>
            <li>✅ Chef on site</li>
            <li>✅ Themed presentation</li>
          </ul>
          <a href="#contact" class="mt-6 inline-flex justify-center px-4 py-2 rounded-xl bg-brand-600 text-white hover:bg-brand-700">Check Availability</a>
        </div>
      </div>
    </div>
  </section>

  <!-- Menus -->
  <section id="menus" class="py-14">
    <div class="wrap px-4">
      <h2 class="text-2xl md:text-3xl font-bold">Popular Menus</h2>
      <p class="mt-2 text-slate-600">Swap dishes freely. Vegetarian/vegan options available.</p>
      <div class="mt-8 grid md:grid-cols-3 gap-6">
        <div class="border rounded-2xl p-6">
          <div class="font-semibold">Malay Classic</div>
          <ul class="mt-3 space-y-1 text-slate-700 text-sm">
            <li>• Nasi minyak / Nasi hujan panas</li>
            <li>• Ayam masak merah</li>
            <li>• Daging kurma</li>
            <li>• Dalca sayur / Acar</li>
            <li>• Buah & kuih</li>
          </ul>
        </div>
        <div class="border rounded-2xl p-6">
          <div class="font-semibold">Western Comfort</div>
          <ul class="mt-3 space-y-1 text-slate-700 text-sm">
            <li>• Butter rice / Aglio e olio</li>
            <li>• Herb roasted chicken</li>
            <li>• Creamy mushroom pasta</li>
            <li>• Garden salad</li>
            <li>• Brownies / fruit platter</li>
          </ul>
        </div>
        <div class="border rounded-2xl p-6">
          <div class="font-semibold">Corporate Bento</div>
          <ul class="mt-3 space-y-1 text-slate-700 text-sm">
            <li>• Rice / pasta base</li>
            <li>• Protein of choice</li>
            <li>• 2 sides + dessert</li>
            <li>• Drink included</li>
            <li>• Label & dietary notes</li>
          </ul>
        </div>
      </div>
      <div class="mt-6 flex flex-wrap gap-3">
        <a href="https://docs.google.com/spreadsheets/" class="px-4 py-2 rounded-xl border hover:bg-slate-50" target="_blank" rel="noopener">View Full Menu (Google Sheet)</a>
        <a href="/menu.pdf" class="px-4 py-2 rounded-xl border hover:bg-slate-50">Download PDF Menu</a>
      </div>
    </div>
  </section>

  <!-- Gallery -->
  <section id="gallery" class="bg-slate-50 py-14">
    <div class="wrap px-4">
      <h2 class="text-2xl md:text-3xl font-bold">Gallery</h2>
      <p class="mt-2 text-slate-600">A look at our recent setups & dishes.</p>
      <div class="mt-8 grid grid-cols-2 md:grid-cols-4 gap-3">
        <img src="https://images.unsplash.com/photo-1544025162-d76694265947?q=80&w=800&auto=format&fit=crop" alt="Buffet" class="rounded-xl object-cover w-full h-40" loading="lazy">
        <img src="https://images.unsplash.com/photo-1555244162-803834f70033?q=80&w=800&auto=format&fit=crop" alt="Canapés" class="rounded-xl object-cover w-full h-40" loading="lazy">
        <img src="https://images.unsplash.com/photo-1543352634-8730c0b88c51?q=80&w=800&auto=format&fit=crop" alt="Desserts" class="rounded-xl object-cover w-full h-40" loading="lazy">
        <img src="https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?q=80&w=800&auto=format&fit=crop" alt="Table setup" class="rounded-xl object-cover w-full h-40" loading="lazy">
      </div>
    </div>
  </section>

  <!-- Testimonials -->
  <section id="testimonials" class="py-14">
    <div class="wrap px-4">
      <h2 class="text-2xl md:text-3xl font-bold">What Clients Say</h2>
      <div class="mt-8 grid md:grid-cols-3 gap-6">
        <div class="border rounded-2xl p-6">
          <div class="font-semibold">Aisyah — Wedding</div>
          <p class="mt-2 text-slate-700">“Portion banyak, rasa sedap, setup pun cantik. Ramai puji!”</p>
        </div>
        <div class="border rounded-2xl p-6">
          <div class="font-semibold">Daniel — Corporate</div>
          <p class="mt-2 text-slate-700">“Professional & on time. Our directors were impressed.”</p>
        </div>
        <div class="border rounded-2xl p-6">
          <div class="font-semibold">Mira — Birthday</div>
          <p class="mt-2 text-slate-700">“Anak‑anak suka. Staff pun friendly. Recommended!”</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Service Areas -->
  <section class="bg-slate-900 text-white py-14">
    <div class="wrap px-4">
      <h2 class="text-2xl md:text-3xl font-bold">Service Areas</h2>
      <p class="mt-2 text-slate-300">Seremban • Nilai • Senawang • Bangi • Kajang • PJ • KL</p>
      <div class="mt-6 grid md:grid-cols-3 gap-6 text-slate-900">
        <div class="bg-white rounded-2xl p-6">
          <div class="font-semibold">Logistics</div>
          <p class="mt-2 text-sm text-slate-600">Delivery, setup, warmers, utensils, buffet tables & skirting.</p>
        </div>
        <div class="bg-white rounded-2xl p-6">
          <div class="font-semibold">Hygiene & Safety</div>
          <p class="mt-2 text-sm text-slate-600">Certified kitchens & safe food handling protocols.</p>
        </div>
        <div class="bg-white rounded-2xl p-6">
          <div class="font-semibold">Staffing</div>
          <p class="mt-2 text-sm text-slate-600">Experienced servers & a dedicated event supervisor.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section id="faq" class="py-14">
    <div class="wrap px-4">
      <h2 class="text-2xl md:text-3xl font-bold">FAQ</h2>
      <div class="mt-8 grid md:grid-cols-2 gap-6">
        <details class="border rounded-xl p-4 open:bg-slate-50">
          <summary class="font-semibold cursor-pointer">What is the minimum order?</summary>
          <p class="mt-2 text-slate-700">Minimum 30 pax for buffet/dome. Bento from 20 sets.</p>
        </details>
        <details class="border rounded-xl p-4">
          <summary class="font-semibold cursor-pointer">Do you provide tasting?</summary>
          <p class="mt-2 text-slate-700">Yes, for large events (&gt;150 pax). Nominal fee applies, rebated upon booking.</p>
        </details>
        <details class="border rounded-xl p-4">
          <summary class="font-semibold cursor-pointer">Are your ingredients halal?</summary>
          <p class="mt-2 text-slate-700">We source from halal-certified suppliers and maintain separate prep areas.</p>
        </details>
        <details class="border rounded-xl p-4">
          <summary class="font-semibold cursor-pointer">How far in advance should I book?</summary>
          <p class="mt-2 text-slate-700">Preferably 2–4 weeks. Urgent bookings subject to availability.</p>
        </details>
      </div>
    </div>
  </section>

  <!-- Contact / Quote Form -->
  <section id="contact" class="bg-slate-50 py-14">
    <div class="wrap px-4">
      <h2 class="text-2xl md:text-3xl font-bold">Get a Quick Quote</h2>
      <p class="mt-2 text-slate-600">Tell us about your event. We'll reply on WhatsApp within the day.</p>

      <div class="mt-8 grid md:grid-cols-2 gap-8">
        <form id="waForm" class="bg-white border rounded-2xl p-6">
          <div class="grid grid-cols-1 gap-4">
            <div>
              <label class="block text-sm font-medium">Your Name</label>
              <input id="fName" type="text" class="mt-1 w-full rounded-lg border-slate-300" required />
            </div>
            <div>
              <label class="block text-sm font-medium">WhatsApp Number</label>
              <input id="fPhone" type="tel" class="mt-1 w-full rounded-lg border-slate-300" placeholder="e.g., 0123456789" required />
            </div>
            <div class="grid grid-cols-2 gap-4">
              <div>
                <label class="block text-sm font-medium">Event Date</label>
                <input id="fDate" type="date" class="mt-1 w-full rounded-lg border-slate-300" required />
              </div>
              <div>
                <label class="block text-sm font-medium">Pax</label>
                <input id="fPax" type="number" min="10" class="mt-1 w-full rounded-lg border-slate-300" required />
              </div>
            </div>
            <div>
              <label class="block text-sm font-medium">Package</label>
              <select id="fPackage" class="mt-1 w-full rounded-lg border-slate-300">
                <option>Buffet Set</option>
                <option>Dome / VIP</option>
                <option>Canapés / Live</option>
                <option>Corporate Bento</option>
              </select>
            </div>
            <div>
              <label class="block text-sm font-medium">Notes (dietary, venue, time)</label>
              <textarea id="fNotes" rows="4" class="mt-1 w-full rounded-lg border-slate-300"></textarea>
            </div>
            <button type="submit" class="mt-2 inline-flex justify-center px-4 py-3 rounded-xl bg-brand-600 text-white hover:bg-brand-700">Send via WhatsApp</button>
          </div>
        </form>

        <div class="flex flex-col gap-4">
          <div class="rounded-2xl border p-6 bg-white">
            <div class="font-semibold">Reach Us</div>
            <div class="mt-2 text-slate-700 text-sm">
              <p><strong>Phone:</strong> <a href="tel:+60123456789" class="text-brand-700 hover:underline">+60 12-345 6789</a></p>
              <p><strong>Email:</strong> <a href="mailto:hello@monzicatering.com" class="text-brand-700 hover:underline">hello@monzicatering.com</a></p>
              <p><strong>Hours:</strong> Mon–Sun, 9am–6pm</p>
            </div>
          </div>
          <iframe class="rounded-2xl border w-full h-64" loading="lazy" referrerpolicy="no-referrer-when-downgrade" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3984.701230!2d101.938!3d2.663!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zMsKwMzknNDYuOCJOIDEwMcKwNTYnMTYuOCJF!5e0!3m2!1sen!2smy!4v0000000000"></iframe>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="border-t">
    <div class="wrap px-4 py-8 flex flex-col md:flex-row items-start md:items-center justify-between gap-6 text-sm">
      <div>
        <div class="font-semibold">Monzi Catering</div>
        <div class="text-slate-600">© <span id="year"></span> Monzi Catering. All rights reserved.</div>
      </div>
      <div class="flex items-center gap-4">
        <a href="#" class="hover:underline">Terms</a>
        <a href="#" class="hover:underline">Privacy</a>
        <a href="https://wa.me/60123456789" class="inline-flex items-center gap-2 px-3 py-2 rounded-xl bg-brand-600 text-white">WhatsApp Us</a>
      </div>
    </div>
  </footer>

  <!-- Floating WhatsApp button -->
  <a href="https://wa.me/60123456789" class="fixed bottom-5 right-5 inline-flex items-center justify-center h-14 w-14 rounded-full bg-brand-600 text-white shadow-lg focus:ring-4 focus:ring-brand-300" aria-label="WhatsApp">
    <!-- WhatsApp icon -->
    <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-7" fill="currentColor" viewBox="0 0 24 24"><path d="M.057 24l1.687-6.163A11.867 11.867 0 0112.017 0C18.628 0 24 5.373 24 11.982c0 6.61-5.372 11.983-11.983 11.983a11.95 11.95 0 01-6.096-1.651L.057 24zm6.597-3.807c1.741.995 3.276 1.591 5.392 1.593 5.448.003 9.886-4.429 9.889-9.877.003-5.462-4.415-9.887-9.881-9.89-5.451-.003-9.89 4.428-9.893 9.879-.001 2.225.651 3.891 1.746 5.634L2.2 21.8l4.454-1.607zM8.69 6.534c-.127-.28-.262-.286-.383-.292l-.327-.006a.741.741 0 00-.536.25c-.185.2-.707.69-.707 1.68 0 .99.724 1.945.825 2.079.102.134 1.413 2.256 3.414 3.158 1.897.836 2.283.671 2.695.629.412-.043 1.327-.542 1.514-1.066.186-.524.186-.973.13-1.066-.057-.093-.204-.148-.427-.26-.223-.111-1.327-.654-1.532-.729-.204-.074-.353-.111-.504.112-.15.223-.578.729-.709.879-.13.149-.26.168-.482.056-.223-.112-.94-.346-1.79-1.102-.662-.59-1.11-1.317-1.242-1.54-.13-.223-.014-.343.098-.454.101-.1.224-.26.335-.391.112-.13.149-.223.224-.372.074-.149.037-.28-.019-.391-.057-.111-.504-1.215-.688-1.657z"/></svg>
  </a>

  <!-- Schema.org (SEO) -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "LocalBusiness",
    "additionalType": "https://schema.org/CateringService",
    "name": "Monzi Catering",
    "url": "https://www.monzicatering.com",
    "telephone": "+60-12-345-6789",
    "address": {
      "@type": "PostalAddress",
      "addressLocality": "Seremban",
      "addressRegion": "Negeri Sembilan",
      "addressCountry": "MY"
    },
    "areaServed": ["Seremban","Kuala Lumpur","Selangor"],
    "priceRange": "RM25–RM80 per pax",
    "sameAs": [
      "https://instagram.com/yourbrand",
      "https://facebook.com/yourbrand"
    ]
  }
  </script>

  <script>
    // Update year
    document.getElementById('year').textContent = new Date().getFullYear();

    // WhatsApp form handler: builds a wa.me link including form values
    const form = document.getElementById('waForm');
    form.addEventListener('submit', function (e) {
      e.preventDefault();
      const name = document.getElementById('fName').value.trim();
      const phone = document.getElementById('fPhone').value.trim();
      const date = document.getElementById('fDate').value;
      const pax = document.getElementById('fPax').value;
      const pkg = document.getElementById('fPackage').value;
      const notes = document.getElementById('fNotes').value.trim();

      const msg = `Hi Monzi Catering!%0A%0A`+
        `Name: ${encodeURIComponent(name)}%0A`+
        `Contact: ${encodeURIComponent(phone)}%0A`+
        `Event Date: ${encodeURIComponent(date)}%0A`+
        `Pax: ${encodeURIComponent(pax)}%0A`+
        `Package: ${encodeURIComponent(pkg)}%0A`+
        `Notes: ${encodeURIComponent(notes)}`;

      // Replace with your real WhatsApp number (no dashes/spaces), e.g., 60123456789
      const waNumber = '60123456789';
      const url = `https://wa.me/${waNumber}?text=${msg}`;
      window.open(url, '_blank');
    });
  </script>

  <!-- Optional: Google Analytics / Tag (paste your ID) -->
  <!-- <script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXX"></script>
  <script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);} gtag('js', new Date()); gtag('config', 'G-XXXXXXX');
  </script> -->
</body>
</html>
