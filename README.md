<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Essence Connect</title>

  <script src="https://cdn.tailwindcss.com"></script>

  <style>
    body {
      margin: 0;
      background: black;
      color: white;
      font-family: Arial, sans-serif;
      overflow-x: hidden;
    }

    .glow {
      text-shadow: 0 0 20px rgba(255,255,255,0.8);
    }

    .hero {
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      text-align: center;
      padding: 20px;
      background:
        radial-gradient(circle at top, rgba(255,255,255,0.1), transparent 40%),
        black;
    }

    .card {
      background: rgba(255,255,255,0.05);
      border: 1px solid rgba(255,255,255,0.1);
      backdrop-filter: blur(10px);
    }

    .fade {
      animation: fadeIn 2s ease forwards;
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(40px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    .btn {
      transition: 0.3s;
    }

    .btn:hover {
      transform: scale(1.08);
    }
  </style>
</head>

<body>

  <section class="hero">

    <h1 class="text-6xl md:text-7xl font-bold glow fade">
      ESSENCE CONNECT
    </h1>

    <p class="mt-6 text-gray-300 text-lg max-w-2xl fade">
      The future of connected perfume marketing.
      Build your income, grow your network,
      and discover luxury fragrances through modern digital entrepreneurship.
    </p>

    <div class="mt-10 flex gap-4 flex-wrap justify-center fade">

      <a href="https://instagram.com/a.s.h.r.a.f19" target="_blank">
        <button class="btn bg-white text-black px-8 py-4 rounded-full font-bold">
          Instagram
        </button>
      </a>

      <a href="tel:0708099733">
        <button class="btn border border-white px-8 py-4 rounded-full font-bold">
          Contact Us
        </button>
      </a>

    </div>

  </section>

  <section class="py-20 px-6">

    <h2 class="text-4xl font-bold text-center mb-14">
      Why Join Essence Connect?
    </h2>

    <div class="grid md:grid-cols-3 gap-8 max-w-6xl mx-auto">

      <div class="card p-8 rounded-3xl">
        <h3 class="text-2xl font-bold mb-4">
          Luxury Perfumes
        </h3>

        <p class="text-gray-300">
          Access premium fragrances and build a trusted customer base.
        </p>
      </div>

      <div class="card p-8 rounded-3xl">
        <h3 class="text-2xl font-bold mb-4">
          Connected Marketing
        </h3>

        <p class="text-gray-300">
          Grow through referrals, partnerships, and social influence.
        </p>
      </div>

      <div class="card p-8 rounded-3xl">
        <h3 class="text-2xl font-bold mb-4">
          Modern Business
        </h3>

        <p class="text-gray-300">
          Build an online brand and create multiple income opportunities.
        </p>
      </div>

    </div>

  </section>

  <section class="py-20 text-center px-6">

    <h2 class="text-5xl font-bold mb-6">
      Start Your Journey
    </h2>

    <p class="text-gray-300 max-w-2xl mx-auto">
      Join the next generation of perfume entrepreneurship and connected marketing.
    </p>

    <div class="mt-10">
      <a href="https://instagram.com/a.s.h.r.a.f19" target="_blank">
        <button class="btn bg-white text-black px-10 py-5 rounded-full text-lg font-bold">
          Join Essence Connect
        </button>
      </a>
    </div>

  </section>

</body>
</html># index.html