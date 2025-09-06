# SilentNightWalker.github.io
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>ZPZCO | 0.0̅1 — Lead What's Real SHART </title>
  <meta name="description" content="ZPZCO provides keynotes, leadership training, IP strategy, and automation system design. Book JD for Tactical Strategies for Mental Fitness and more." />
  <meta property="og:title" content="ZPZCO | 0.0̅1 — Lead What's Real" />
  <meta property="og:description" content="Keynotes on mental fitness & resilience, consulting on IP & systems. Strip it all away. Lead what's real." />
  <meta property="og:type" content="website" />
  <meta name="theme-color" content="#000000" />
  
  <!-- Tailwind (CDN for fast start; convert to compiled Tailwind before launch if desired) -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            display: ['Inter', 'ui-sans-serif', 'system-ui', 'sans-serif'],
            body: ['Inter', 'ui-sans-serif', 'system-ui', 'sans-serif']
          },
          colors: {
            ink: '#0a0a0a',
            paper: '#ffffff',
            accent: '#C9F31D' // chartreuse‑ish accent; tune to brand guidelines
          },
          boxShadow: {
            soft: '0 10px 30px -12px rgba(0,0,0,0.35)'
          }
        }
      }
    }
  </script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800;900&display=swap" rel="stylesheet">
  <style>
    /* Subtle animated underline for links */
    .link-underline { position: relative; }
    .link-underline::after { content: ""; position: absolute; left: 0; bottom: -2px; width: 0; height: 2px; background: currentColor; transition: width .25s ease; }
    .link-underline:hover::after { width: 100%; }
  </style>
</head>
<body class="bg-ink text-paper font-body antialiased">
  <!-- NAV -->
  <header class="sticky top-0 z-50 backdrop-blur bg-ink/70 border-b border-white/10">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="h-16 flex items-center justify-between">
        <a href="#top" class="flex items-center gap-3">
          <!-- Replace with your SVG mark -->
          <div class="h-8 w-8 rounded-full bg-accent"></div>
          <div class="leading-tight">
            <div class="text-xl font-black tracking-tight">ZPZCO <span class="select-none">| 0.0̅1</span></div>
            <div class="text-xs uppercase tracking-widest text-white/60">Lead What’s Real</div>
          </div>
        </a>
        <nav class="hidden md:flex items-center gap-8 text-sm">
          <a href="#speaking" class="text-white/90 hover:text-white link-underline">Speaking</a>
          <a href="#consulting" class="text-white/90 hover:text-white link-underline">Consulting & IP</a>
          <a href="#philosophy" class="text-white/90 hover:text-white link-underline">0.0̅1</a>
          <a href="#about" class="text-white/90 hover:text-white link-underline">About</a>
          <a href="#book" class="inline-flex items-center gap-2 bg-accent text-black font-semibold px-4 py-2 rounded-xl shadow-soft hover:translate-y-[-1px] active:translate-y-[1px] transition">Book JD</a>
        </nav>
        <button id="menuBtn" class="md:hidden inline-flex items-center justify-center w-10 h-10 rounded-xl border border-white/15">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-5 h-5"><path fill-rule="evenodd" d="M3.75 5.25a.75.75 0 0 1 .75-.75h15a.75.75 0 0 1 0 1.5h-15a.75.75 0 0 1-.75-.75Zm0 6a.75.75 0 0 1 .75-.75h15a.75.75 0 0 1 0 1.5h-15a.75.75 0 0 1-.75-.75Zm0 6a.75.75 0 0 1 .75-.75h15a.75.75 0 0 1 0 1.5h-15a.75.75 0 0 1-.75-.75Z" clip-rule="evenodd"/></svg>
        </button>
      </div>
    </div>
    <div id="mobileMenu" class="md:hidden hidden border-t border-white/10">
      <div class="px-4 py-4 space-y-3 text-sm">
        <a href="#speaking" class="block text-white/90">Speaking</a>
        <a href="#consulting" class="block text-white/90">Consulting & IP</a>
        <a href="#philosophy" class="block text-white/90">0.0̅1</a>
        <a href="#about" class="block text-white/90">About</a>
        <a href="#book" class="block text-black bg-accent font-semibold px-4 py-2 rounded-xl w-max">Book JD</a>
      </div>
    </div>
  </header>

  <!-- HERO -->
  <section id="top" class="relative overflow-hidden">
    <div class="absolute inset-0 bg-[radial-gradient(ellipse_at_top,rgba(201,243,29,0.15),transparent_45%)]"></div>
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="pt-20 pb-16 md:pt-28 md:pb-20 grid md:grid-cols-12 gap-10 items-center">
        <div class="md:col-span-7">
          <h1 class="text-4xl sm:text-6xl font-black leading-[1.05] tracking-tight">
            Strip it all away.<br/><span class="text-accent">Lead what’s real.</span>
          </h1>
          <p class="mt-6 text-lg text-white/80 max-w-2xl">
            ZPZCO delivers high‑impact keynotes on mental fitness, resilience, and culture change—starting with first responders and expanding to corporate teams and schools. We also consult on <span class="text-white">intellectual property strategy</span> and <span class="text-white">automation systems</span> to turn clarity into durable value.
          </p>
          <div class="mt-8 flex flex-wrap gap-3">
            <a href="#book" class="inline-flex items-center gap-2 bg-accent text-black font-semibold px-6 py-3 rounded-2xl shadow-soft">Book JD to Speak
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-5 h-5"><path fill-rule="evenodd" d="M12.97 3.97a.75.75 0 0 1 1.06 0l6 6a.75.75 0 1 1-1.06 1.06L14.25 6.31V20a.75.75 0 0 1-1.5 0V6.31l-4.72 4.72a.75.75 0 0 1-1.06-1.06l6-6Z" clip-rule="evenodd"/></svg>
            </a>
            <a href="#consulting" class="inline-flex items-center gap-2 px-6 py-3 rounded-2xl border border-white/15 text-white/90">Consulting & IP
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-5 h-5"><path fill-rule="evenodd" d="M3.75 12a8.25 8.25 0 1 1 16.5 0 8.25 8.25 0 0 1-16.5 0Zm8.78-3.53a.75.75 0 0 0-1.06 0l-4 4a.75.75 0 1 0 1.06 1.06L12 10.56l3.72 3.72a.75.75 0 0 0 1.06-1.06l-4-4Z" clip-rule="evenodd"/></svg>
            </a>
          </div>
          <div class="mt-6 text-sm text-white/50">
            "Mobilize Resources. Make Money. Lead What’s Real."
          </div>
        </div>
        <div class="md:col-span-5 relative">
          <!-- Replace the placeholder with your hero image -->
          <div class="aspect-[4/5] rounded-3xl bg-white/5 border border-white/10 overflow-hidden shadow-soft">
            <div class="h-full w-full bg-[url('https://images.unsplash.com/photo-1517245386807-bb43f82c33c4?q=80&w=1200&auto=format&fit=crop')] bg-cover bg-center"></div>
          </div>
          <div class="absolute -bottom-4 -left-4 rotate-[-2deg] bg-accent text-black text-xs font-bold px-3 py-1 rounded-md shadow">Sober • Surgical • High‑Impact</div>
        </div>
      </div>
    </div>
  </section>

  <!-- TRUST / TAGS (optional logos later) -->
  <section class="py-8 border-y border-white/10 bg-white/5">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-wrap items-center gap-x-10 gap-y-4 text-white/70 text-xs uppercase tracking-widest">
      <div class="flex items-center gap-2"><span class="h-2 w-2 rounded-full bg-accent"></span> First Responders</div>
      <div class="flex items-center gap-2"><span class="h-2 w-2 rounded-full bg-accent"></span> Corporate</div>
      <div class="flex items-center gap-2"><span class="h-2 w-2 rounded-full bg-accent"></span> Schools</div>
      <div class="flex items-center gap-2"><span class="h-2 w-2 rounded-full bg-accent"></span> IP Strategy</div>
      <div class="flex items-center gap-2"><span class="h-2 w-2 rounded-full bg-accent"></span> Automation Systems</div>
    </div>
  </section>

  <!-- SPEAKING -->
  <section id="speaking" class="py-20">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="grid md:grid-cols-12 gap-10 items-start">
        <div class="md:col-span-5">
          <h2 class="text-3xl sm:text-4xl font-extrabold tracking-tight">Tactical Strategies for Mental Fitness</h2>
          <p class="mt-4 text-white/80">A fast‑moving, no‑fluff keynote that gives people the tools to keep their heads and hearts online when the heat turns up. Built for first responders. Adapted for corporate teams and schools.</p>
          <ul class="mt-6 space-y-3 text-white/80">
            <li class="flex items-start gap-3"><span class="mt-1 h-2.5 w-2.5 rounded-full bg-accent"></span><span>Rapid nervous‑system resets (e.g., Box Breathing) for on‑scene and after‑scene recovery.</span></li>
            <li class="flex items-start gap-3"><span class="mt-1 h-2.5 w-2.5 rounded-full bg-accent"></span><span>Language that punctures stigma and builds a culture where strength and honesty coexist.</span></li>
            <li class="flex items-start gap-3"><span class="mt-1 h-2.5 w-2.5 rounded-full bg-accent"></span><span>Repeatable mental models for facing fear, processing load, and returning to mission.</span></li>
          </ul>
          <div class="mt-8 flex gap-3">
            <a href="#book" class="inline-flex items-center gap-2 bg-accent text-black font-semibold px-5 py-3 rounded-xl shadow-soft">Request Booking</a>
            <a href="#speaking-variants" class="inline-flex items-center gap-2 px-5 py-3 rounded-xl border border-white/15">Audience Versions</a>
          </div>
        </div>
        <div class="md:col-span-7" id="speaking-variants">
          <div class="grid sm:grid-cols-2 gap-6">
            <div class="p-6 rounded-2xl bg-white/5 border border-white/10">
              <div class="text-sm uppercase tracking-widest text-white/60">First Responders</div>
              <h3 class="mt-2 text-xl font-bold">Fire, EMS, Law</h3>
              <p class="mt-3 text-white/80">On‑scene tactics, after‑action recovery, peer support, and culture shifts that last.</p>
            </div>
            <div class="p-6 rounded-2xl bg-white/5 border border-white/10">
              <div class="text-sm uppercase tracking-widest text-white/60">Corporate</div>
              <h3 class="mt-2 text-xl font-bold">High‑stakes Teams</h3>
              <p class="mt-3 text-white/80">Resilience, precision communication, and performance under pressure—without burnout.</p>
            </div>
            <div class="p-6 rounded-2xl bg-white/5 border border-white/10">
              <div class="text-sm uppercase tracking-widest text-white/60">Schools</div>
              <h3 class="mt-2 text-xl font-bold">Students & Staff</h3>
              <p class="mt-3 text-white/80">What‑I‑Can‑Control, nervous‑system basics, and peer‑to‑peer language that lands.</p>
            </div>
            <div class="p-6 rounded-2xl bg-white/5 border border-white/10">
              <div class="text-sm uppercase tracking-widest text-white/60">Also available</div>
              <h3 class="mt-2 text-xl font-bold">Coming Home to Yourself</h3>
              <p class="mt-3 text-white/80">A keynote for first responders on culture change, sobriety, and post‑traumatic growth.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- CONSULTING & IP -->
  <section id="consulting" class="py-20 border-y border-white/10 bg-gradient-to-b from-ink to-[#0e0e0e]">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="grid md:grid-cols-12 gap-10 items-start">
        <div class="md:col-span-6">
          <h2 class="text-3xl sm:text-4xl font-extrabold tracking-tight">Consulting, IP Strategy & Automation Systems</h2>
          <p class="mt-4 text-white/80">We help founders and organizations turn raw clarity into defensible IP, repeatable systems, and revenue. From invention spotting and provisional filings to licensing narratives and automation that actually reduces workload.</p>
          <div class="mt-6 grid sm:grid-cols-2 gap-6">
            <div class="p-5 rounded-2xl bg-white/5 border border-white/10">
              <h3 class="font-bold">IP Strategy</h3>
              <ul class="mt-3 space-y-2 text-white/80 text-sm">
                <li>White‑space mapping</li>
                <li>Provisional drafting sprints</li>
                <li>Licensing & negotiation prep</li>
              </ul>
            </div>
            <div class="p-5 rounded-2xl bg-white/5 border border-white/10">
              <h3 class="font-bold">Automation & Systems</h3>
              <ul class="mt-3 space-y-2 text-white/80 text-sm">
                <li>Operational workflows (n8n, GPT)</li>
                <li>Reporting & accountability</li>
                <li>Human‑safe AI integration</li>
              </ul>
            </div>
          </div>
          <a href="#book" class="mt-8 inline-flex items-center gap-2 bg-accent text-black font-semibold px-5 py-3 rounded-xl shadow-soft">Request Consulting</a>
        </div>
        <div class="md:col-span-6">
          <div class="p-6 rounded-3xl bg-white/5 border border-white/10">
            <h3 class="text-xl font-bold">Why both under one roof?</h3>
            <p class="mt-3 text-white/80">Because they feed each other. The same principles that keep humans sharp under pressure are the ones that build durable companies: radical clarity, tight loops, and clean power. Speaking changes culture. Consulting installs systems. Together, they last.</p>
            <div class="mt-4 text-sm text-white/60">ZPZCO is a branded house. Pillar A: <span class="text-white">Speaking & Training</span>. Pillar B: <span class="text-white">IP & Systems</span>. One philosophy—<span class="text-accent font-bold">0.0̅1</span>.</div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- PHILOSOPHY / 0.0̅1 -->
  <section id="philosophy" class="py-20">
    <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
      <div class="text-sm uppercase tracking-widest text-white/60">ZPZCO Philosophy</div>
      <h2 class="mt-2 text-3xl sm:text-4xl font-extrabold tracking-tight">Everything compared to infinity is the same.</h2>
      <p class="mt-4 text-white/80 max-w-3xl mx-auto">That’s <span class="text-accent font-bold">0.0̅1</span>. It kills hierarchy and unlocks possibility. We don’t posture—we build. We don’t numb—we get clear. We don’t perform—we lead what’s real.</p>
    </div>
  </section>

  <!-- TESTIMONIALS (placeholder) -->
  <section class="py-20 bg-white/5 border-y border-white/10">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-2xl font-extrabold tracking-tight">What leaders are saying</h2>
      <div class="mt-8 grid md:grid-cols-3 gap-6">
        <figure class="p-6 rounded-2xl bg-ink border border-white/10">
          <blockquote class="text-white/80">“Exceeded expectations. Surgical, grounded, and immediately usable on the floor.”</blockquote>
          <figcaption class="mt-4 text-sm text-white/60">— Fire Chief, Washington</figcaption>
        </figure>
        <figure class="p-6 rounded-2xl bg-ink border border-white/10">
          <blockquote class="text-white/80">“Finally a talk that treats us like adults and hands us real tools.”</blockquote>
          <figcaption class="mt-4 text-sm text-white/60">— Battalion Captain</figcaption>
        </figure>
        <figure class="p-6 rounded-2xl bg-ink border border-white/10">
          <blockquote class="text-white/80">“Culture‑changing. Book him.”</blockquote>
          <figcaption class="mt-4 text-sm text-white/60">— Director, Safety & Ops</figcaption>
        </figure>
      </div>
    </div>
  </section>

  <!-- ABOUT -->
  <section id="about" class="py-20">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid md:grid-cols-12 gap-10 items-start">
      <div class="md:col-span-5">
        <div class="aspect-[4/5] rounded-3xl bg-white/5 border border-white/10 overflow-hidden shadow-soft">
          <div class="h-full w-full bg-[url('https://images.unsplash.com/photo-1557683316-973673baf926?q=80&w=1200&auto=format&fit=crop')] bg-cover bg-center"></div>
        </div>
      </div>
      <div class="md:col-span-7">
        <h2 class="text-3xl sm:text-4xl font-extrabold tracking-tight">About ZPZCO</h2>
        <p class="mt-4 text-white/80">ZPZCO exists to ignite what’s real—by stripping away everything that isn’t. We build companies, tools, and movements that awaken creators, leaders, and innovators to their infinite potential.</p>
        <ul class="mt-6 space-y-3 text-white/80">
          <li class="flex items-start gap-3"><span class="mt-1 h-2.5 w-2.5 rounded-full bg-accent"></span><span>Mission: Clear minds, bold action, sovereign lives.</span></li>
          <li class="flex items-start gap-3"><span class="mt-1 h-2.5 w-2.5 rounded-full bg-accent"></span><span>Values: Radical truth, clean power, sobriety, legacy over ego.</span></li>
          <li class="flex items-start gap-3"><span class="mt-1 h-2.5 w-2.5 rounded-full bg-accent"></span><span>Leadership: Earn followership daily. Lead without pretending.</span></li>
        </ul>
        <div class="mt-8 flex gap-3">
          <a href="#book" class="inline-flex items-center gap-2 bg-accent text-black font-semibold px-5 py-3 rounded-xl shadow-soft">Media & Booking</a>
          <a href="#consulting" class="inline-flex items-center gap-2 px-5 py-3 rounded-xl border border-white/15">Work With Us</a>
        </div>
      </div>
    </div>
  </section>

  <!-- BOOKING FORM -->
  <section id="book" class="py-20">
    <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="p-8 rounded-3xl bg-white/5 border border-white/10 shadow-soft">
        <h2 class="text-3xl font-extrabold tracking-tight">Request Booking</h2>
        <p class="mt-3 text-white/80">Tell us about your event or engagement. We’ll respond with next steps and a link to schedule an intro call.</p>
        <!-- Replace the `action` value with your Formspree endpoint or other form handler -->
        <form action="https://formspree.io/f/your-form-id" method="POST" class="mt-8 grid grid-cols-1 sm:grid-cols-2 gap-4">
          <div class="sm:col-span-1">
            <label class="block text-sm text-white/70">Name</label>
            <input type="text" name="name" required class="mt-1 w-full bg-ink border border-white/15 rounded-xl px-3 py-2 focus:outline-none focus:ring-2 focus:ring-accent/60" />
          </div>
          <div class="sm:col-span-1">
            <label class="block text-sm text-white/70">Email</label>
            <input type="email" name="email" required class="mt-1 w-full bg-ink border border-white/15 rounded-xl px-3 py-2 focus:outline-none focus:ring-2 focus:ring-accent/60" />
          </div>
          <div class="sm:col-span-1">
            <label class="block text-sm text-white/70">Organization</label>
            <input type="text" name="organization" class="mt-1 w-full bg-ink border border-white/15 rounded-xl px-3 py-2 focus:outline-none focus:ring-2 focus:ring-accent/60" />
          </div>
          <div class="sm:col-span-1">
            <label class="block text-sm text-white/70">Role/Title</label>
            <input type="text" name="role" class="mt-1 w-full bg-ink border border-white/15 rounded-xl px-3 py-2 focus:outline-none focus:ring-2 focus:ring-accent/60" />
          </div>
          <div class="sm:col-span-2">
            <label class="block text-sm text-white/70">Engagement Type</label>
            <select name="type" class="mt-1 w-full bg-ink border border-white/15 rounded-xl px-3 py-2 focus:outline-none focus:ring-2 focus:ring-accent/60">
              <option>Keynote — First Responders</option>
              <option>Keynote — Corporate</option>
              <option>Keynote — Schools</option>
              <option>Workshop / Training</option>
              <option>Consulting — IP Strategy</option>
              <option>Consulting — Automation Systems</option>
            </select>
          </div>
          <div class="sm:col-span-1">
            <label class="block text-sm text-white/70">Preferred Date(s)</label>
            <input type="text" name="dates" placeholder="e.g., Oct 15–16, 2025" class="mt-1 w-full bg-ink border border-white/15 rounded-xl px-3 py-2 focus:outline-none focus:ring-2 focus:ring-accent/60" />
          </div>
          <div class="sm:col-span-1">
            <label class="block text-sm text-white/70">Audience Size</label>
            <input type="number" name="audience_size" min="1" class="mt-1 w-full bg-ink border border-white/15 rounded-xl px-3 py-2 focus:outline-none focus:ring-2 focus:ring-accent/60" />
          </div>
          <div class="sm:col-span-2">
            <label class="block text-sm text-white/70">Goals & Context</label>
            <textarea name="goals" rows="5" placeholder="What outcomes matter most? Any current challenges or themes?" class="mt-1 w-full bg-ink border border-white/15 rounded-xl px-3 py-2 focus:outline-none focus:ring-2 focus:ring-accent/60"></textarea>
          </div>
          <div class="sm:col-span-2">
            <label class="block text-sm text-white/70">Budget Range (optional)</label>
            <input type="text" name="budget" placeholder="$—$$$" class="mt-1 w-full bg-ink border border-white/15 rounded-xl px-3 py-2 focus:outline-none focus:ring-2 focus:ring-accent/60" />
          </div>
          <div class="sm:col-span-2 flex items-center gap-3">
            <input id="sober" type="checkbox" name="sober_event" class="h-4 w-4 rounded border-white/20 bg-ink" />
            <label for="sober" class="text-sm text-white/70">We support a substance‑free event environment.</label>
          </div>
          <div class="sm:col-span-2">
            <button type="submit" class="w-full sm:w-auto inline-flex items-center gap-2 bg-accent text-black font-semibold px-6 py-3 rounded-2xl shadow-soft">Submit Request</button>
          </div>
          <input type="hidden" name="_subject" value="New ZPZCO Booking/Consulting Request" />
        </form>
        <p class="mt-4 text-xs text-white/50">By submitting, you agree to be contacted regarding your request. We don’t sell data. Ever.</p>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="border-t border-white/10 py-12">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid md:grid-cols-3 gap-8 items-start">
      <div>
        <div class="text-lg font-black">ZPZCO <span class="select-none">| 0.0̅1</span></div>
        <p class="mt-2 text-white/70 text-sm max-w-xs">We build what lasts: clear minds, clean power, sovereign lives.</p>
      </div>
      <div class="text-sm">
        <div class="font-semibold mb-2">Navigate</div>
        <ul class="space-y-1 text-white/70">
          <li><a class="hover:text-white" href="#speaking">Speaking</a></li>
          <li><a class="hover:text-white" href="#consulting">Consulting & IP</a></li>
          <li><a class="hover:text-white" href="#philosophy">0.0̅1</a></li>
          <li><a class="hover:text-white" href="#book">Book JD</a></li>
        </ul>
      </div>
      <div class="text-sm">
        <div class="font-semibold mb-2">Contact</div>
        <ul class="space-y-1 text-white/70">
          <li><a class="hover:text-white" href="mailto:hello@zpzco.com">hello@zpzco.com</a></li>
          <li>Olympia, Washington</li>
        </ul>
        <div class="mt-4 text-xs text-white/50">© <span id="year"></span> ZPZCO LLC. All rights reserved.</div>
      </div>
    </div>
  </footer>

  <!-- Sticky CTA -->
  <a href="#book" class="fixed right-4 bottom-4 md:right-8 md:bottom-8 inline-flex items-center gap-2 bg-accent text-black font-semibold px-5 py-3 rounded-2xl shadow-soft">Book JD</a>

  <script>
    // mobile menu toggle
    const btn = document.getElementById('menuBtn');
    const menu = document.getElementById('mobileMenu');
    btn?.addEventListener('click', () => menu.classList.toggle('hidden'));
    // year
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
