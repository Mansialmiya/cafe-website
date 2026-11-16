# cafe-website

<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Eat & Sip Cafe | Artisanal Coffee & Kitchen</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,600;0,700;1,600&family=Plus+Jakarta+Sans:wght@400;500;600;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Plus Jakarta Sans', sans-serif;
      background-color: #F9F6F0;
      color: #1C2A23;
    }
    h1, h2, h3, .font-serif-heading {
      font-family: 'Cormorant Garamond', serif;
    }
  </style>
</head>
<body class="antialiased selection:bg-[#3A5A40] selection:text-white">

  <!-- ================= NAVIGATION ================= -->
  <header class="sticky top-0 z-50 bg-[#F9F6F0]/90 backdrop-blur-md border-b border-[#1C2A23]/10">
    <div class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">
      <a href="#" class="font-serif-heading text-2xl font-bold tracking-tight text-[#1C2A23] flex items-center gap-2">
        <span class="w-3 h-3 rounded-full bg-[#3A5A40]"></span>
        Eat & Sip Cafe
      </a>
      
      <nav class="hidden md:flex items-center gap-8 text-sm font-medium text-[#5A6B61]">
        <a href="#about" class="hover:text-[#3A5A40] transition">About</a>
        <a href="#menu" class="hover:text-[#3A5A40] transition">Menu</a>
        <a href="#featured" class="hover:text-[#3A5A40] transition">Chef’s Pick</a>
        <a href="#hours" class="hover:text-[#3A5A40] transition">Hours & Location</a>
      </nav>

      <div class="flex items-center gap-4">
        <a href="#reserve" class="bg-[#3A5A40] hover:bg-[#2c4531] text-white text-sm font-semibold px-5 py-2.5 rounded-full transition shadow-sm hover:shadow">
          Book a Table
        </a>
      </div>
    </div>
  </header>

  <!-- ================= HERO SECTION ================= -->
  <section class="relative pt-12 pb-24 md:py-32 overflow-hidden">
    <div class="max-w-7xl mx-auto px-6 grid grid-cols-1 md:grid-cols-12 gap-12 items-center">
      
      <div class="md:col-span-7 space-y-6">
        <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-[#EFECE6] border border-[#3A5A40]/20 text-xs font-semibold uppercase tracking-wider text-[#3A5A40]">
          🌿 Bhimtal’s Slow-Living Corner Cafe
        </div>
        <h1 class="font-serif-heading text-5xl md:text-7xl font-bold leading-[1.08] tracking-tight text-[#1C2A23]">
          Rooted in craft, <br>
          <span class="italic font-normal text-[#3A5A40]">brewed</span> for the soul.
        </h1>
        <p class="text-base md:text-lg text-[#5A6B61] max-w-xl leading-relaxed">
          An inviting sanctuary of farm-fresh small plates, single-origin pour-overs, and house-baked pastries tucked beneath the pines. Slow down, breathe in, and stay a while.
        </p>
        <div class="flex flex-wrap items-center gap-4 pt-2">
          <a href="#menu" class="bg-[#1C2A23] hover:bg-[#3A5A40] text-white font-medium px-7 py-3.5 rounded-full transition duration-300">
            View Menu
          </a>
          <a href="#reserve" class="border border-[#1C2A23]/20 hover:border-[#1C2A23] text-[#1C2A23] font-medium px-7 py-3.5 rounded-full transition duration-300">
            Reserve a Table
          </a>
        </div>
        
        <div class="pt-6 flex items-center gap-8 border-t border-[#1C2A23]/10">
          <div>
            <p class="font-serif-heading text-2xl font-bold text-[#1C2A23]">4.9 / 5.0</p>
            <p class="text-xs text-[#5A6B61]">Over 850+ local reviews</p>
          </div>
          <div class="h-8 w-px bg-[#1C2A23]/10"></div>
          <div>
            <p class="font-serif-heading text-2xl font-bold text-[#1C2A23]">100%</p>
            <p class="text-xs text-[#5A6B61]">Artisanal & Organic Sourced</p>
          </div>
        </div>
      </div>

      <div class="md:col-span-5 relative">
        <div class="relative rounded-3xl overflow-hidden shadow-2xl aspect-[4/5] group">
          <img src="https://images.unsplash.com/photo-1501339847302-ac426a4a7cbb?auto=format&fit=crop&w=900&q=80" 
               alt="Aesthetic cafe interior with coffee and pastries" 
               class="w-full h-full object-cover group-hover:scale-105 transition duration-700">
          <div class="absolute inset-0 bg-gradient-to-t from-[#1C2A23]/60 via-transparent to-transparent"></div>
          <div class="absolute bottom-6 left-6 right-6 text-white">
            <span class="text-xs uppercase tracking-widest text-[#D4A373] font-semibold">Today’s Special</span>
            <h3 class="font-serif-heading text-2xl font-bold">Honey-Lavender Oat Latte & Fig Scone</h3>
          </div>
        </div>
      </div>

    </div>
  </section>

  <!-- ================= ABOUT SNAPSHOT ================= -->
  <section id="about" class="py-20 bg-[#EFECE6]/50 border-y border-[#1C2A23]/5">
    <div class="max-w-5xl mx-auto px-6 text-center space-y-4">
      <span class="text-xs font-semibold uppercase tracking-widest text-[#3A5A40]">Our Philosophy</span>
      <h2 class="font-serif-heading text-3xl md:text-5xl font-bold text-[#1C2A23]">
        Where Good Food Meets Quiet Conversations
      </h2>
      <p class="text-[#5A6B61] text-base md:text-lg max-w-2xl mx-auto leading-relaxed">
        Sylvan & Sprout was born from a simple desire: to create a physical pause button in a rushed world. Whether you’re sketching in a notebook, catching up over cold brews, or sharing a candlelit dinner, every plate tells a story of local growers and patient craft.
      </p>
    </div>
  </section>

  <!-- ================= FEATURED / SIGNATURE DISH ================= -->
  <section id="featured" class="py-24">
    <div class="max-w-7xl mx-auto px-6">
      <div class="flex flex-col md:flex-row md:items-end justify-between mb-12">
        <div>
          <span class="text-xs font-semibold uppercase tracking-widest text-[#3A5A40]">Chef’s Selection</span>
          <h2 class="font-serif-heading text-4xl md:text-5xl font-bold text-[#1C2A23] mt-1">Signature Dish of the Season</h2>
        </div>
        <p class="text-sm text-[#5A6B61] mt-2 md:mt-0">Crafted fresh daily in limited batches.</p>
      </div>

      <div class="bg-white rounded-3xl overflow-hidden shadow-lg border border-[#1C2A23]/10 grid grid-cols-1 md:grid-cols-12">
        <div class="md:col-span-6 relative min-h-[320px]">
          <img src="https://images.unsplash.com/photo-1546069901-ba9599a7e63c?auto=format&fit=crop&w=1000&q=80" 
               alt="Wild Mushroom & Truffle Risotto" 
               class="w-full h-full object-cover">
          <span class="absolute top-4 left-4 bg-[#1C2A23] text-white text-xs font-semibold px-3 py-1.5 rounded-full uppercase tracking-wider">
            Most Popular
          </span>
        </div>
        <div class="md:col-span-6 p-8 md:p-12 flex flex-col justify-between">
          <div>
            <div class="flex items-center justify-between">
              <span class="text-xs uppercase tracking-widest text-[#3A5A40] font-semibold">Main Course</span>
              <span class="font-serif-heading text-2xl font-bold text-[#1C2A23]">₹480</span>
            </div>
            <h3 class="font-serif-heading text-3xl font-bold text-[#1C2A23] mt-2">Wild Mushroom & Truffle Arborio Risotto</h3>
            <p class="text-[#5A6B61] mt-4 leading-relaxed">
              Slow-stirred Carnaroli rice folded with porcini and chanterelle mushrooms, aged Parmigiano-Reggiano, thyme-infused white wine reduction, and finished with cold-pressed black truffle oil.
            </p>
            <ul class="mt-6 space-y-2 text-sm text-[#5A6B61]">
              <li class="flex items-center gap-2">✓ 100% Vegetarian & Gluten-Free adaptable</li>
              <li class="flex items-center gap-2">✓ Paired best with our House Spiced Hibiscus Fizz</li>
            </ul>
          </div>
          <div class="mt-8 pt-6 border-t border-[#1C2A23]/10 flex items-center justify-between">
            <span class="text-sm font-medium text-[#1C2A23]">Available from 12:00 PM onwards</span>
            <a href="#reserve" class="bg-[#3A5A40] hover:bg-[#2c4531] text-white text-sm font-semibold px-6 py-2.5 rounded-full transition">
              Order or Reserve
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ================= FULL MENU SECTION (3 Categories, 8 Items) ================= -->
  <section id="menu" class="py-24 bg-[#EFECE6]/40 border-t border-[#1C2A23]/5">
    <div class="max-w-5xl mx-auto px-6">
      
      <div class="text-center max-w-2xl mx-auto mb-16">
        <span class="text-xs font-semibold uppercase tracking-widest text-[#3A5A40]">Curated Offerings</span>
        <h2 class="font-serif-heading text-4xl md:text-5xl font-bold text-[#1C2A23] mt-2">Our Menu</h2>
        <p class="text-[#5A6B61] mt-3">Prepared from scratch using seasonal ingredients and house-made sauces.</p>
      </div>

      <!-- MENU GRID -->
      <div class="grid grid-cols-1 md:grid-cols-3 gap-10">

        <!-- Category 1: Starters -->
        <div class="space-y-6">
          <div class="border-b-2 border-[#3A5A40] pb-2 flex items-center justify-between">
            <h3 class="font-serif-heading text-2xl font-bold text-[#1C2A23]">Starters & Small Plates</h3>
            <span class="text-xs text-[#3A5A40] font-semibold uppercase">01</span>
          </div>

          <div class="space-y-6">
            <!-- Item 1 -->
            <div class="group">
              <div class="flex items-baseline justify-between">
                <h4 class="font-semibold text-[#1C2A23] group-hover:text-[#3A5A40] transition">Burrata & Heirloom Tomato Tartine</h4>
                <span class="font-serif-heading font-bold text-[#1C2A23] ml-2">₹320</span>
              </div>
              <p class="text-xs text-[#5A6B61] mt-1">Sourdough toast, creamy Apulian burrata, basil pesto, aged balsamic glaze.</p>
            </div>

            <!-- Item 2 -->
            <div class="group">
              <div class="flex items-baseline justify-between">
                <h4 class="font-semibold text-[#1C2A23] group-hover:text-[#3A5A40] transition">Crispy Polenta Fries</h4>
                <span class="font-serif-heading font-bold text-[#1C2A23] ml-2">₹260</span>
              </div>
              <p class="text-xs text-[#5A6B61] mt-1">Herb-crusted corn polenta sticks served with roasted garlic aioli.</p>
            </div>

            <!-- Item 3 -->
            <div class="group">
              <div class="flex items-baseline justify-between">
                <h4 class="font-semibold text-[#1C2A23] group-hover:text-[#3A5A40] transition">Roasted Pumpkin & Sage Soup</h4>
                <span class="font-serif-heading font-bold text-[#1C2A23] ml-2">₹280</span>
              </div>
              <p class="text-xs text-[#5A6B61] mt-1">Velvety roasted red pumpkin broth, toasted pumpkin seeds, brown butter drizzle.</p>
            </div>
          </div>
        </div>

        <!-- Category 2: Main Course -->
        <div class="space-y-6">
          <div class="border-b-2 border-[#3A5A40] pb-2 flex items-center justify-between">
            <h3 class="font-serif-heading text-2xl font-bold text-[#1C2A23]">Main Course</h3>
            <span class="text-xs text-[#3A5A40] font-semibold uppercase">02</span>
          </div>

          <div class="space-y-6">
            <!-- Item 4 -->
            <div class="group">
              <div class="flex items-baseline justify-between">
                <h4 class="font-semibold text-[#1C2A23] group-hover:text-[#3A5A40] transition">Wild Mushroom Risotto</h4>
                <span class="font-serif-heading font-bold text-[#1C2A23] ml-2">₹480</span>
              </div>
              <p class="text-xs text-[#5A6B61] mt-1">Carnaroli rice, porcini & chanterelle medley, truffle oil, Parmigiano.</p>
            </div>

            <!-- Item 5 -->
            <div class="group">
              <div class="flex items-baseline justify-between">
                <h4 class="font-semibold text-[#1C2A23] group-hover:text-[#3A5A40] transition">Handmade Gnocchi in Sage Butter</h4>
                <span class="font-serif-heading font-bold text-[#1C2A23] ml-2">₹440</span>
              </div>
              <p class="text-xs text-[#5A6B61] mt-1">Ricotta potato gnocchi, browned butter, crisp sage leaves, toasted walnuts.</p>
            </div>

            <!-- Item 6 -->
            <div class="group">
              <div class="flex items-baseline justify-between">
                <h4 class="font-semibold text-[#1C2A23] group-hover:text-[#3A5A40] transition">Sylvan Harvest Grain Bowl</h4>
                <span class="font-serif-heading font-bold text-[#1C2A23] ml-2">₹390</span>
              </div>
              <p class="text-xs text-[#5A6B61] mt-1">Quinoa, roasted sweet potato, kale, avocado, pickled beetroot, tahini dressing.</p>
            </div>
          </div>
        </div>

        <!-- Category 3: Drinks & Desserts -->
        <div class="space-y-6">
          <div class="border-b-2 border-[#3A5A40] pb-2 flex items-center justify-between">
            <h3 class="font-serif-heading text-2xl font-bold text-[#1C2A23]">Drinks & Desserts</h3>
            <span class="text-xs text-[#3A5A40] font-semibold uppercase">03</span>
          </div>

          <div class="space-y-6">
            <!-- Item 7 -->
            <div class="group">
              <div class="flex items-baseline justify-between">
                <h4 class="font-semibold text-[#1C2A23] group-hover:text-[#3A5A40] transition">Honey-Lavender Oat Latte</h4>
                <span class="font-serif-heading font-bold text-[#1C2A23] ml-2">₹240</span>
              </div>
              <p class="text-xs text-[#5A6B61] mt-1">Double espresso, house-steeped French lavender, raw wildflower honey, oat milk.</p>
            </div>

            <!-- Item 8 -->
            <div class="group">
              <div class="flex items-baseline justify-between">
                <h4 class="font-semibold text-[#1C2A23] group-hover:text-[#3A5A40] transition">Warm Dark Chocolate & Sea Salt Tart</h4>
                <span class="font-serif-heading font-bold text-[#1C2A23] ml-2">₹290</span>
              </div>
              <p class="text-xs text-[#5A6B61] mt-1">70% single-origin dark chocolate ganache, flaky Maldon sea salt, vanilla bean cream.</p>
            </div>

            <!-- Item 9 -->
            <div class="group">
              <div class="flex items-baseline justify-between">
                <h4 class="font-semibold text-[#1C2A23] group-hover:text-[#3A5A40] transition">Spiced Hibiscus & Rose Tonic</h4>
                <span class="font-serif-heading font-bold text-[#1C2A23] ml-2">₹220</span>
              </div>
              <p class="text-xs text-[#5A6B61] mt-1">Cold-brewed organic hibiscus flowers, damask rose water, sparkling tonic.</p>
            </div>
          </div>
        </div>

      </div>

    </div>
  </section>

  <!-- ================= GALLERY STRIP ================= -->
  <section class="py-12 bg-white">
    <div class="max-w-7xl mx-auto px-6">
      <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
        <div class="overflow-hidden rounded-2xl aspect-square">
          <img src="https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?auto=format&fit=crop&w=600&q=80" alt="Latte art" class="w-full h-full object-cover hover:scale-105 transition duration-500">
        </div>
        <div class="overflow-hidden rounded-2xl aspect-square">
          <img src="https://images.unsplash.com/photo-1559339352-11d035aa65de?auto=format&fit=crop&w=600&q=80" alt="Cafe interior" class="w-full h-full object-cover hover:scale-105 transition duration-500">
        </div>
        <div class="overflow-hidden rounded-2xl aspect-square">
          <img src="https://images.unsplash.com/photo-1565299624946-b28f40a0ae38?auto=format&fit=crop&w=600&q=80" alt="Artisanal food" class="w-full h-full object-cover hover:scale-105 transition duration-500">
        </div>
        <div class="overflow-hidden rounded-2xl aspect-square">
          <img src="https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?auto=format&fit=crop&w=600&q=80" alt="Dining atmosphere" class="w-full h-full object-cover hover:scale-105 transition duration-500">
        </div>
      </div>
    </div>
  </section>

  <!-- ================= HOURS, LOCATION & RESERVATION CTA ================= -->
  <section id="hours" class="py-24 bg-[#1C2A23] text-[#F9F6F0]">
    <div class="max-w-7xl mx-auto px-6 grid grid-cols-1 md:grid-cols-12 gap-12 items-center">
      
      <!-- Left: Hours & Location Info -->
      <div class="md:col-span-6 space-y-8">
        <div>
          <span class="text-xs font-semibold uppercase tracking-widest text-[#D4A373]">Visit Us</span>
          <h2 class="font-serif-heading text-4xl md:text-5xl font-bold mt-2">Come Sit by the Window</h2>
          <p class="text-sm text-[#F9F6F0]/70 mt-2">Easy parking available. Pets warmly welcomed on our garden patio.</p>
        </div>

        <div class="space-y-4 border-l-2 border-[#3A5A40] pl-6">
          <div>
            <h4 class="font-semibold text-lg">Hours of Operation</h4>
            <p class="text-sm text-[#F9F6F0]/70 mt-1">Tuesday – Sunday: 8:00 AM – 10:00 PM</p>
            <p class="text-xs text-[#D4A373]">Closed Mondays for rest & foraging</p>
          </div>
          <div>
            <h4 class="font-semibold text-lg mt-4">Location</h4>
            <p class="text-sm text-[#F9F6F0]/70 mt-1">Plot 44, Lakeside Ridge Road, Bhimtal, Uttarakhand 263136</p>
          </div>
        </div>
      </div>

      <!-- Right: Reservation / Booking Card -->
      <div id="reserve" class="md:col-span-6 bg-[#F9F6F0] text-[#1C2A23] p-8 md:p-10 rounded-3xl shadow-xl">
        <h3 class="font-serif-heading text-3xl font-bold">Reserve a Table</h3>
        <p class="text-xs text-[#5A6B61] mt-1">We’ll hold your table for up to 15 minutes past reservation time.</p>

        <form class="mt-6 space-y-4" onsubmit="event.preventDefault(); alert('Thank you! Your table reservation request has been received.');">
          <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
            <div>
              <label class="block text-xs font-semibold uppercase tracking-wider text-[#5A6B61] mb-1">Your Name</label>
              <input type="text" required placeholder="Aarav Sharma" class="w-full px-4 py-2.5 rounded-xl border border-[#1C2A23]/15 text-sm focus:outline-none focus:border-[#3A5A40]">
            </div>
            <div>
              <label class="block text-xs font-semibold uppercase tracking-wider text-[#5A6B61] mb-1">Phone Number</label>
              <input type="tel" required placeholder="+91 98765 43210" class="w-full px-4 py-2.5 rounded-xl border border-[#1C2A23]/15 text-sm focus:outline-none focus:border-[#3A5A40]">
            </div>
          </div>

          <div class="grid grid-cols-1 sm:grid-cols-3 gap-4">
            <div>
              <label class="block text-xs font-semibold uppercase tracking-wider text-[#5A6B61] mb-1">Date</label>
              <input type="date" required class="w-full px-3 py-2.5 rounded-xl border border-[#1C2A23]/15 text-sm focus:outline-none focus:border-[#3A5A40]">
            </div>
            <div>
              <label class="block text-xs font-semibold uppercase tracking-wider text-[#5A6B61] mb-1">Time</label>
              <select class="w-full px-3 py-2.5 rounded-xl border border-[#1C2A23]/15 text-sm focus:outline-none focus:border-[#3A5A40]">
                <option>09:00 AM</option>
                <option>11:30 AM</option>
                <option>01:00 PM</option>
                <option>04:30 PM</option>
                <option>07:00 PM</option>
                <option>08:30 PM</option>
              </select>
            </div>
            <div>
              <label class="block text-xs font-semibold uppercase tracking-wider text-[#5A6B61] mb-1">Guests</label>
              <select class="w-full px-3 py-2.5 rounded-xl border border-[#1C2A23]/15 text-sm focus:outline-none focus:border-[#3A5A40]">
                <option>2 Guests</option>
                <option>3 Guests</option>
                <option>4 Guests</option>
                <option>5+ Guests</option>
              </select>
            </div>
          </div>

          <button type="submit" class="w-full mt-4 bg-[#3A5A40] hover:bg-[#2c4531] text-white font-semibold py-3.5 rounded-xl transition">
            Confirm Table Reservation
          </button>
        </form>
      </div>

    </div>
  </section>

  <!-- ================= FOOTER ================= -->
  <footer class="bg-[#1C2A23] border-t border-white/10 text-white/60 py-10">
    <div class="max-w-7xl mx-auto px-6 flex flex-col md:flex-row items-center justify-between text-xs gap-4">
      <div class="font-serif-heading text-lg font-bold text-white">Sylvan & Sprout Cafe</div>
      <p>© 2026 Sylvan & Sprout Cafe. All rights reserved.</p>
      <div class="flex items-center gap-6">
        <a href="#menu" class="hover:text-white transition">Instagram</a>
        <a href="#menu" class="hover:text-white transition">Facebook</a>
        <a href="#menu" class="hover:text-white transition">Privacy Policy</a>
      </div>
    </div>
  </footer>

</body>
</html>
