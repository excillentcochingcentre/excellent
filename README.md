# excellent
class 0 to 10th home toution available in your area. can contact -> rameshhbabu6@gmail.com
import React from "react"; import { Card, CardContent } from "@/components/ui/card"; import { Button } from "@/components/ui/button"; import { Mail, Phone } from "lucide-react";

export default function TuitionCenterWebsite() { return ( <div className="min-h-screen bg-gradient-to-b from-blue-100 to-white p-4"> <header className="text-center py-6"> <h1 className="text-4xl font-bold text-blue-800">Bright Minds Tuition Center</h1> <p className="text-lg text-gray-600 mt-2">Guiding Children Towards a Brighter Future</p> </header>

<nav className="flex justify-center gap-6 mb-8">
    <a href="#home" className="text-blue-700 hover:underline">Home</a>
    <a href="#about" className="text-blue-700 hover:underline">About Us</a>
    <a href="#contact" className="text-blue-700 hover:underline">Contact</a>
  </nav>

  <section id="home" className="grid md:grid-cols-2 gap-6 mb-12 items-center">
    <img src="https://images.unsplash.com/photo-1600209182405-9b7f6e8b7b5e" alt="Kids learning" className="rounded-2xl shadow-md" />
    <div>
      <h2 className="text-2xl font-semibold text-blue-900 mb-2">Welcome to Bright Minds</h2>
      <p className="text-gray-700 text-base">
        We provide personalized tuition for children from Kindergarten to Grade 8. Our experienced teachers focus on foundational learning in Math, English, and Science.
      </p>
    </div>
  </section>

  <section id="about" className="mb-12">
    <h2 className="text-2xl font-semibold text-center text-blue-900 mb-4">About Us</h2>
    <Card className="max-w-3xl mx-auto">
      <CardContent className="p-6 text-gray-700">
        Bright Minds Tuition Center was established in 2020 with the goal of helping young learners build strong academic foundations. We believe in nurturing curiosity, confidence, and creativity through interactive learning.
      </CardContent>
    </Card>
  </section>

  <section id="contact" className="mb-12">
    <h2 className="text-2xl font-semibold text-center text-blue-900 mb-4">Contact Us</h2>
    <div className="flex flex-col items-center gap-4">
      <div className="flex items-center gap-2 text-gray-800">
        <Phone /> <span>+91 98765 43210</span>
      </div>
      <div className="flex items-center gap-2 text-gray-800">
        <Mail /> <span>contact@brightminds.com</span>
      </div>
      <Button className="mt-4">Send a Message</Button>
    </div>
  </section>

  <footer className="text-center text-sm text-gray-500 py-4">
    © 2025 Bright Minds Tuition Center. All rights reserved.
  </footer>
</div>

); }

