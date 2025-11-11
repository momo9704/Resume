<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Neil Francis Degamo | Video Editor & Design Expert</title>
    <!-- Load Tailwind CSS for modern, responsive styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap" rel="stylesheet">
    <style>
        /* Custom styles */
        :root {
            --primary-color: #3b82f6; /* Blue-500 */
            --background-dark: #1f2937; /* Gray-800 */
            --text-light: #f3f4f6; /* Gray-100 */
        }
        body {
            font-family: 'Inter', sans-serif;
            background-color: var(--background-dark);
            color: var(--text-light);
            transition: background-color 0.3s, color 0.3s;
        }
        .section-card {
            background-color: #374151; /* Gray-700 */
            box-shadow: 0 10px 15px rgba(0, 0, 0, 0.2);
            border-radius: 1rem;
        }
        .header-bg {
            background-color: #111827; /* Gray-900 */
        }
        .contact-link:hover {
            color: var(--primary-color);
            transform: translateY(-2px);
            transition: all 0.2s ease-in-out;
        }
    </style>
</head>
<body class="min-h-screen">

    <!-- Header Section -->
    <header class="header-bg py-8 border-b-4 border-blue-500">
        <div class="max-w-4xl mx-auto px-6 text-center">
            <h1 class="text-4xl sm:text-5xl font-extrabold text-white mb-2">NEIL FRANCIS DEGAMO</h1>
            <p class="text-xl text-blue-300">Creative Video Editor & Canva Design Specialist</p>
        </div>
    </header>

    <main class="max-w-4xl mx-auto p-6 space-y-8">

        <!-- Contact/Social Links (Responsive to Flex on larger screens) -->
        <section class="section-card p-6 flex flex-col sm:flex-row justify-around items-center text-sm sm:text-base font-medium">
            <a href="mailto:janlopez285@gmail.com" class="contact-link flex items-center mb-2 sm:mb-0">
                <!-- Mail Icon (lucide-react equivalent) -->
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mr-2"><rect width="20" height="16" x="2" y="4" rx="2"/><path d="m22 7-8.97 5.7a1.83 1.83 0 0 1-2.06 0L2 7"/></svg>
                janlopez285@gmail.com
            </a>
            <span class="text-gray-400 hidden sm:inline">|</span>
            <a href="tel:+639302513527" class="contact-link flex items-center mb-2 sm:mb-0">
                <!-- Phone Icon -->
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mr-2"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.63A2 2 0 0 1 4.1 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"/></svg>
                +63-930-2513527
            </a>
            <span class="text-gray-400 hidden sm:inline">|</span>
            <a href="https://twitter.com/neilfrancisdegamo" target="_blank" class="contact-link flex items-center">
                <!-- User/At-Symbol Icon -->
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mr-2"><circle cx="12" cy="12" r="10"/><path d="M12 2a10 10 0 0 0 0 20 10 10 0 0 0 0-20z"/><path d="M15 9h5v5h-5zM9 15h5v5h-5zM9 9h5v5h-5zM15 15h5v5h-5zM4 4h5v5h-5zM4 15h5v5h-5zM15 4h5v5h-5zM4 9h5v5h-5z"/></svg>
                @neilfrancisdegamo
            </a>
        </section>

        <!-- Summary Section -->
        <section class="section-card p-6">
            <h2 class="text-2xl font-bold mb-4 border-b-2 border-blue-500 pb-2">Career Profile</h2>
            <p class="text-gray-300 leading-relaxed">
                Creative and detail-oriented Video Editor and Canva Design Specialist with hands-on
                experience producing engaging short-form video content for social media platforms. Skilled
                in using Canva and CapCut to create dynamic visuals, branded motion graphics, and
                seamless transitions. Brings additional background in graphic design and digital marketing,
                enabling cohesive visuals that align with brand tone and messaging.
            </p>
        </section>

        <!-- Experience Section -->
        <section class="section-card p-6">
            <h2 class="text-2xl font-bold mb-4 border-b-2 border-blue-500 pb-2">Professional Experience</h2>
            
            <!-- Job 1 -->
            <div class="mb-6 border-l-4 border-blue-500 pl-4">
                <h3 class="text-xl font-semibold text-blue-300">Video Editor / Canva Design Expert</h3>
                <p class="text-sm text-gray-400 mb-2">IBC Group of Companies (Remote) | Sept 2024 – Mar 2025</p>
                <ul class="list-disc list-inside space-y-1 text-gray-300 ml-4">
                    <li>Created visually compelling social media videos using Canva and CapCut.</li>
                    <li>Added transitions, subtitles, effects, and optimized aspect ratios for various platforms.</li>
                    <li>Designed supporting graphics and branded visual assets to maintain brand identity.</li>
                    <li>Collaborated with marketing and content teams to deliver campaigns aligned with engagement goals.</li>
                </ul>
            </div>

            <!-- Job 2 -->
            <div class="border-l-4 border-blue-500 pl-4">
                <h3 class="text-xl font-semibold text-blue-300">Graphic Designer / Social Media Creative</h3>
                <p class="text-sm text-gray-400 mb-2">Various Clients (Freelance) | Jan 2020 – Present</p>
                <ul class="list-disc list-inside space-y-1 text-gray-300 ml-4">
                    <li>Designed branded graphics, marketing visuals, and digital content packages.</li>
                    <li>Created social media templates, promotional banners, and ad visuals.</li>
                    <li>Maintained brand consistency across all designs.</li>
                </ul>
            </div>
        </section>

        <!-- Skills & Tools Section (Grid Layout for Mobile/Desktop) -->
        <section class="section-card p-6">
            <h2 class="text-2xl font-bold mb-4 border-b-2 border-blue-500 pb-2">Skills & Tools</h2>
            <div class="grid grid-cols-2 md:grid-cols-3 gap-4">
                
                <!-- Skill Set -->
                <div class="col-span-2 md:col-span-1">
                    <h4 class="text-lg font-semibold mb-2 text-blue-300">Key Skills</h4>
                    <ul class="space-y-1 text-gray-300">
                        <li class="flex items-center"><span class="text-blue-500 mr-2">&bull;</span> Video Editing (CapCut, Canva)</li>
                        <li class="flex items-center"><span class="text-blue-500 mr-2">&bull;</span> Graphic Design & Branding</li>
                        <li class="flex items-center"><span class="text-blue-500 mr-2">&bull;</span> Storyboarding & Visual Planning</li>
                        <li class="flex items-center"><span class="text-blue-500 mr-2">&bull;</span> Social Media Content Creation</li>
                        <li class="flex items-center"><span class="text-blue-500 mr-2">&bull;</span> Basic Motion Graphics</li>
                        <li class="flex items-center"><span class="text-blue-500 mr-2">&bull;</span> Content Scheduling & Coordination</li>
                    </ul>
                </div>

                <!-- Tools -->
                <div class="col-span-2 md:col-span-2">
                    <h4 class="text-lg font-semibold mb-2 text-blue-300">Primary Tools</h4>
                    <div class="flex flex-wrap gap-2">
                        <span class="bg-blue-600 text-white text-xs font-semibold px-3 py-1 rounded-full shadow-lg">Canva</span>
                        <span class="bg-blue-600 text-white text-xs font-semibold px-3 py-1 rounded-full shadow-lg">CapCut</span>
                        <span class="bg-blue-600 text-white text-xs font-semibold px-3 py-1 rounded-full shadow-lg">Adobe Photoshop</span>
                        <span class="bg-blue-600 text-white text-xs font-semibold px-3 py-1 rounded-full shadow-lg">Illustrator (Basic)</span>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="text-center py-6 mt-8 text-gray-400 text-sm border-t border-gray-700">
        <p>Built with HTML & Tailwind CSS | Based in Cebu City, Philippines</p>
    </footer>

    <!-- JavaScript for simple behavior (optional for this simple site, but good practice) -->
    <script>
        // Example: Optional simple JavaScript to greet on load, though not necessary for basic resume page
        document.addEventListener('DOMContentLoaded', () => {
            console.log("Welcome to Neil Francis Degamo's Digital Resume.");
        });
    </script>
</body>
</html>
