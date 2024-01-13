<template>
  <section class="py-32 max-lg:px-4 from-sky-300/20 via-gray-300/40 to-sky-500/40 bg-gradient-to-tl">
    <div class="lg:container mx-auto text-center">
      <h4 class="text-transparent from-blue-500 to-emrald-500 bg-gradient-to-tr bg-clip-text uppercase font-semibold tracking-wide">Features that set us apart</h4>
      <h3 class="text-4xl my-6 font-bold">Helping you take your trading to the next level</h3>

      <div class="grid md:grid-cols-3 gap-6 items-stretch mt-24">
        <div v-for="feature in features" :key="feature.title" class="p-8 rounded-lg flex flex-col gap-7 bg-white shadow-sm shadow-gray-200 text-left">
          <h3 class="font-bold text-2xl text-left">{{ feature.title }}</h3>
          <p class="text-gray-600/90">{{ feature.description }}</p>
        </div>
      </div>


      <button class="rounded-lg flex items-center text-lg justify-center p-4 px-14 bg-green-700 text-white mx-auto mt-16">let's start</button>
    </div>
  </section>
</template>

<script setup lang="ts">
const features = [
  {
    title: 'Minimalist use',
    description: 'Operation of our platform is clear, intuitive and effortless, allowing you to trade stress-free at all times without the unnecessary complexity and overthinking that comes with most tools.'
  },
  {
    title: 'Trading automation',
    description: '“Set and Forget” - Quantum App Trader Easy Bot helps you trade cryptocurrencies automatically so you can spend more time making money and less time worrying.'
  },
  {
    title: 'The trading environment is 100% safe',
    description: 'Our platform puts security first, ensuring you trade in a safe environment.'
  },
  {
    title: 'Tailor-made trading strategies for you',
    description: 'Quantum App Trader can provide you with a variety of reliable and suitable strategy suggestions through unremitting training in cryptocurrency trading protocols, so you can trade like an expert.'
  },
  {
    title: 'Free Demo',
    description: 'Want to test our cryptocurrency trading platform trading robot without risk? Our free demo mode familiarizes you with every tool and feature we offer so you learn through experience rather than from mistakes.'
  },
  {
    title: 'Safety',
    description: 'Our platform undergoes a series of tests and is audited by top industry experts to ensure security is a priority. Your funds are completely safe on our platform'
  }
]
</script>

<style scoped></style>
