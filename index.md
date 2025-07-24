---
layout: default
title: Home
---

<!-- Hero Section -->
<section class="relative h-screen flex items-center justify-center text-white">
    <!-- Background Image -->
    <div class="absolute inset-0 bg-cover bg-center hero-overlay" style="background-image: url('{{ '/assets/images/hero_main.jpg' | relative_url }}');">
    </div>
    
    <!-- Fallback gradient if no image -->
    <div class="absolute inset-0 hero-gradient opacity-50"></div>
    
    <!-- Hero Content -->
    <div class="relative z-10 text-center px-6 max-w-4xl mx-auto fade-in-up">
        <h1 class="text-5xl md:text-7xl font-bold mb-6 leading-tight">
            Empowering Small Businesses
            <span class="block text-primary bg-gray-900 bg-opacity-80 px-6 py-2 rounded-lg inline-block shadow-2xl border-2 border-primary">with GabsLabs</span>
        </h1>
        <p class="text-xl md:text-2xl mb-8 opacity-90 max-w-2xl mx-auto text-white drop-shadow-lg">
            Affordable software solutions designed specifically for small and medium 
            businesses. Quality technology shouldn't break the bank.
        </p>
        <div class="flex flex-col sm:flex-row gap-4 justify-center">
            <a href="/orderly" class="bg-white text-gray-800 px-8 py-4 rounded-lg font-semibold text-lg hover:bg-gray-100 transition-colors duration-200 btn-hover-scale">
                See Our Solution
            </a>
            <a href="mailto:dan@gabslabs.co.uk" class="border-2 border-white text-white px-8 py-4 rounded-lg font-semibold text-lg hover:bg-white hover:text-gray-800 transition-colors duration-200 btn-hover-scale">
                Get Started
            </a>
        </div>
    </div>
    
    <!-- Scroll indicator -->
    <div class="absolute bottom-8 left-1/2 transform -translate-x-1/2 animate-bounce">
        <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 14l-7 7m0 0l-7-7m7 7V3"></path>
        </svg>
    </div>
</section>

<!-- About Section -->
<section id="about" class="py-20 bg-white">
    <div class="container mx-auto px-6">
        <div class="max-w-4xl mx-auto text-center">
            <h2 class="text-4xl font-bold text-gray-800 mb-8">About GabsLabs</h2>
            <p class="text-xl text-gray-600 mb-12 leading-relaxed">
                GabsLabs is a one-person software house with a clear mission: to enable 
                small and medium businesses with affordable, high-quality technology solutions. 
                I believe that every business, regardless of size, deserves access to powerful 
                software that helps them thrive without breaking their budget.
            </p>
            
            <div class="grid md:grid-cols-3 gap-8 mt-16">
                <div class="text-center p-6">
                    <div class="bg-primary text-white w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                        <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3-.895 3-2-1.343-2-3-2z"></path>
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 14c-3.314 0-6 1.343-6 3v1h12v-1c0-1.657-2.686-3-6-3z"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">SMB Focused</h3>
                    <p class="text-gray-600">Purpose-built solutions designed specifically for small and medium business needs and budgets.</p>
                </div>
                
                <div class="text-center p-6">
                    <div class="bg-primary text-white w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                        <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2-3-.895-3-2 1.343-2 3-2 3 .895 3 2-1.343 2-3 2z"></path>
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">Affordable Pricing</h3>
                    <p class="text-gray-600">Low, flat monthly fees with no hidden costs. Quality software that fits your budget.</p>
                </div>
                
                <div class="text-center p-6">
                    <div class="bg-primary text-white w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                        <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">Quick Setup</h3>
                    <p class="text-gray-600">Get started in minutes, not months. Simple onboarding with 2 months free to try risk-free.</p>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- CTA Section -->
<section class="py-20 bg-gray-800 text-white">
    <div class="container mx-auto px-6 text-center">
        <h2 class="text-4xl font-bold mb-6">Ready to Transform Your Business?</h2>
        <p class="text-xl mb-8 opacity-90 max-w-2xl mx-auto">
            Join small businesses who have already started serving their customers better with our affordable solutions.
        </p>
        <a href="mailto:dan@gabslabs.co.uk" class="bg-primary text-white px-8 py-4 rounded-lg font-semibold text-lg hover:bg-primary-dark transition-colors duration-200 btn-hover-scale inline-block">
            Contact Us Today
        </a>
    </div>
</section>

```<!-- Featured Product Section -->
<section class="py-20 bg-primary bg-opacity-5">
    <div class="container mx-auto px-6">
        <div class="max-w-4xl mx-auto text-center mb-16">
            <h2 class="text-4xl font-bold text-gray-800 mb-8">Our Current Solution</h2>
            <div class="bg-white rounded-xl shadow-xl p-8 md:p-12">
                <div class="flex items-center justify-center mb-6">
                    <div class="bg-primary text-white w-20 h-20 rounded-full flex items-center justify-center mr-4">
                        <svg class="w-10 h-10" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.746 0 3.332.477 4.5 1.253v13C19.832 18.477 18.246 18 16.5 18c-1.746 0-3.332.477-4.5 1.253"></path>
                        </svg>
                    </div>
                    <div class="text-left">
                        <h3 class="text-3xl font-bold text-gray-800">Orderly</h3>
                        <p class="text-lg text-gray-600">Complete Restaurant Solution</p>
                    </div>
                </div>
                <p class="text-xl text-gray-700 mb-8 leading-relaxed">
                    A white-label restaurant platform that helps restaurants serve their loyal customers 
                    at a fraction of the cost of traditional solutions. Low monthly fees, first 2 months free, 
                    and money goes directly to your business.
                </p>
                <div class="grid md:grid-cols-2 gap-6 mb-8">
                    <div class="text-center p-4">
                        <div class="text-primary text-2xl font-bold mb-2">📱</div>
                        <h4 class="font-semibold text-gray-800 mb-2">Delivery & Collection</h4>
                        <p class="text-gray-600 text-sm">Complete ordering system for takeaway and delivery</p>
                    </div>
                    <div class="text-center p-4">
                        <div class="text-primary text-2xl font-bold mb-2">💰</div>
                        <h4 class="font-semibold text-gray-800 mb-2">Direct Payments</h4>
                        <p class="text-gray-600 text-sm">Money goes straight to you - we never hold your funds</p>
                    </div>
                </div>
                <a href="/orderly" class="bg-primary text-white px-8 py-4 rounded-lg font-semibold text-lg hover:bg-primary-dark transition-colors duration-200 btn-hover-scale inline-block">
                    Learn More About Orderly
                </a>
            </div>
        </div>
    </div>
</section>
