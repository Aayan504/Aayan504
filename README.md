- 👋 Hi, I’m @Aayan504
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Aayan504/Aayan504 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import React from "react"; import { Button } from "@/components/ui/button";

export default function HomePage() { return ( <div className="min-h-screen bg-gradient-to-b from-gray-900 to-black text-white p-4"> <header className="text-center py-6"> <h1 className="text-4xl font-bold mb-2">Battle Arena</h1> <p className="text-lg">Choose your mode and dominate the battlefield!</p> </header>

<div className="grid grid-cols-1 md:grid-cols-2 gap-4 max-w-4xl mx-auto">
    <div className="bg-gray-800 rounded-2xl p-6 shadow-lg">
      <h2 className="text-2xl font-semibold mb-2">Battle Ground Mode</h2>
      <p className="mb-4">60 players, 4 teammates, 50 second start timer. Play across India map, Natural map, Lone Wolf and Craftland.</p>
      <Button className="w-full">Enter Battle Ground</Button>
    </div>

    <div className="bg-gray-800 rounded-2xl p-6 shadow-lg">
      <h2 className="text-2xl font-semibold mb-2">Class Squad Mode</h2>
      <p className="mb-4">8 players team fight. Fast-paced and tactical matches with real weapons and gloo walls.</p>
      <Button className="w-full">Enter Class Squad</Button>
    </div>
  </div>

  <section className="mt-10 text-center">
    <h3 className="text-3xl font-bold mb-4">Explore Maps</h3>
    <ul className="grid grid-cols-2 md:grid-cols-4 gap-4">
      <li className="bg-gray-700 p-4 rounded-xl">India State Map</li>
      <li className="bg-gray-700 p-4 rounded-xl">Natural Beauty Map</li>
      <li className="bg-gray-700 p-4 rounded-xl">Lone Wolf Map</li>
      <li className="bg-gray-700 p-4 rounded-xl">Craftland Map</li>
    </ul>
  </section>
</div>

); }

