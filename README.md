<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Md. Adnan Hossain | Civil Engineering Portfolio</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Times+New+Roman:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* Custom font loading for Times New Roman aesthetics */
        .font-serif-tnr {
            font-family: 'Times New Roman', Times, serif;
        }
    </style>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'primary-blue': '#1E90FF', /* Dodger Blue */
                        'bg-light': '#F8F9FA',
                        'text-dark': '#333333',
                    },
                    fontFamily: {
                        'serif': ['Times New Roman', 'Times', 'serif'],
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-white text-text-dark font-serif antialiased leading-relaxed tracking-wide">
    <!-- Navigation Bar -->
    <header class="shadow-md sticky top-0 z-50 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <nav class="flex justify-between items-center py-4">
                <h1 class="text-xl font-bold font-serif-tnr">Md. Adnan Hossain</h1>
                <div class="hidden md:flex space-x-8 text-sm font-medium">
                    <a href="#about" class="hover:text-primary-blue transition duration-300">About</a>
                    <a href="#skills" class="hover:text-primary-blue transition duration-300">Skills</a>
                    <a href="#portfolio" class="hover:text-primary-blue transition duration-300">Portfolio</a>
                    <a href="#academic" class="hover:text-primary-blue transition duration-300">Academics</a>
                    <a href="#contact" class="hover:text-primary-blue transition duration-300">Contact</a>
                </div>
            </nav>
        </div>
    </header>

    <main class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 pb-16">
        
        <!-- Hero/About Section -->
        <section id="about" class="py-20 border-b border-gray-200">
            <div class="text-center max-w-4xl mx-auto">
                <h2 class="text-5xl font-extrabold mb-4 text-text-dark font-serif-tnr">
                    Md. Adnan Hossain
                </h2>
                <p class="text-2xl text-primary-blue mb-8 font-light">
                    Civil Engineer | BIM Modeler | Quantity Surveyor
                </p>
                
                <div class="space-y-6 text-lg text-gray-700 text-left">
                    <p class="border-l-4 border-primary-blue pl-4 py-1 italic bg-bg-light p-4 rounded-lg">
                        Civil Engineering graduate with a strong background in RCC and Steel Building design. Proficient in **AutoCAD, BIM (Revit), ArcGIS, and BOQ (Planswift)**. Eager to apply my skills and knowledge in a dynamic engineering environment. Seeking a challenging position in a forward-thinking company where I can contribute to innovative projects and further develop my expertise.
                    </p>
                    <p>
                        My career is focused on the intersection of structural design and digital construction management. I leverage **Building Information Modeling (BIM)** to streamline complex projects, ensuring accuracy from conception through construction.
                    </p>
                    <p>
                        My passion lies in sustainable infrastructure development and utilizing data analytics, particularly in **Quantity Surveying (QS)**, to optimize resource allocation and project costs. I am dedicated to driving efficiency and innovation within the Architecture, Engineering, and Construction (AECO) industry.
                    </p>
                </div>
            </div>
        </section>

        <!-- Skills Section -->
        <section id="skills" class="py-20 border-b border-gray-200">
            <h2 class="text-3xl font-bold mb-10 text-center text-text-dark">Core Competencies & Technology Stack</h2>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">

                <!-- Design/Modeling -->
                <div class="bg-bg-light p-6 rounded-lg shadow-sm border border-gray-100">
                    <h3 class="text-xl font-semibold mb-3 text-primary-blue">Design & Modeling</h3>
                    <ul class="space-y-2 text-gray-700 text-sm">
                        <li class="flex items-center"><span class="mr-2 text-primary-blue">&bull;</span> AutoCAD</li>
                        <li class="flex items-center"><span class="mr-2 text-primary-blue">&bull;</span> Revit (BIM)</li>
                        <li class="flex items-center"><span class="mr-2 text-primary-blue">&bull;</span> Civil 3D</li>
                        <li class="flex items-center"><span class="mr-2 text-primary-blue">&bull;</span> SolidWorks (Basic)</li>
                    </ul>
                </div>
                
                <!-- Analysis/Reporting -->
                <div class="bg-bg-light p-6 rounded-lg shadow-sm border border-gray-100">
                    <h3 class="text-xl font-semibold mb-3 text-primary-blue">Analysis & BOQ</h3>
                    <ul class="space-y-2 text-gray-700 text-sm">
                        <li class="flex items-center"><span class="mr-2 text-primary-blue">&bull;</span> ETABS (Structural Analysis)</li>
                        <li class="flex items-center"><span class="mr-2 text-primary-blue">&bull;</span> SAP2000</li>
                        <li class="flex items-center"><span class="mr-2 text-primary-blue">&bull;</span> Planswift (Quantity Surveying)</li>
                        <li class="flex items-center"><span class="mr-2 text-primary-blue">&bull;</span> Microsoft Excel (Advanced)</li>
                    </ul>
                </div>
                
                <!-- Management & Geospatial -->
                <div class="bg-bg-light p-6 rounded-lg shadow-sm border border-gray-100">
                    <h3 class="text-xl font-semibold mb-3 text-primary-blue">Management & GIS</h3>
                    <ul class="space-y-2 text-gray-700 text-sm">
                        <li class="flex items-center"><span class="mr-2 text-primary-blue">&bull;</span> Project Management Principles (PMP)</li>
                        <li class="flex items-center"><span class="mr-2 text-primary-blue">&bull;</span> Site Supervision</li>
                        <li class="flex items-center"><span class="mr-2 text-primary-blue">&bull;</span> ArcGIS (Geospatial Analysis)</li>
                        <li class="flex items-center"><span class="mr-2 text-primary-blue">&bull;</span> Construction Documentation</li>
                    </ul>
                </div>

                <!-- Software/Tech -->
                <div class="bg-bg-light p-6 rounded-lg shadow-sm border border-gray-100">
                    <h3 class="text-xl font-semibold mb-3 text-primary-blue">Other Software</h3>
                    <ul class="space-y-2 text-gray-700 text-sm">
                        <li class="flex items-center"><span class="mr-2 text-primary-blue">&bull;</span> Python (Data Scripting)</li>
                        <li class="flex items-center"><span class="mr-2 text-primary-blue">&bull;</span> Microsoft Project</li>
                        <li class="flex items-center"><span class="mr-2 text-primary-blue">&bull;</span> Revit API Usage</li>
                        <li class="flex items-center"><span class="mr-2 text-primary-blue">&bull;</span> Technical Reporting</li>
                    </ul>
                </div>

            </div>
        </section>
        
        <!-- Portfolio Projects -->
        <section id="portfolio" class="py-20 border-b border-gray-200">
            <h2 class="text-3xl font-bold mb-10 text-center text-text-dark">Selected Projects</h2>
            
            <div class="space-y-12">
                
                <!-- Project 1 -->
                <div class="bg-bg-light p-8 rounded-lg shadow-lg">
                    <h3 class="text-2xl font-semibold mb-3 text-primary-blue">High-Rise Commercial Tower BIM Model</h3>
                    <p class="text-sm text-gray-500 mb-4">Technologies: Revit, ETABS, Navisworks</p>
                    <p class="text-gray-700 mb-6">
                        Developed comprehensive structural and MEP BIM models for a large-scale commercial tower. This initiative streamlined complex project coordination, leading to a verified **18% reduction in coordination errors** during the pre-construction phase.
                    </p>
                    <div class="flex space-x-4">
                        <a href="https://mock-demo-tower.com" target="_blank" class="text-white bg-primary-blue hover:bg-blue-700 py-2 px-4 rounded-lg text-sm font-medium transition duration-300 shadow-md">
                            Live Demo (Mock)
                        </a>
                        <a href="https://github.com/adnan-hossain-engr/high-rise-bim" target="_blank" class="text-primary-blue border border-primary-blue hover:bg-primary-blue hover:text-white py-2 px-4 rounded-lg text-sm font-medium transition duration-300">
                            View GitHub (Mock)
                        </a>
                    </div>
                </div>

                <!-- Project 2 -->
                <div class="bg-bg-light p-8 rounded-lg shadow-lg">
                    <h3 class="text-2xl font-semibold mb-3 text-primary-blue">Coastal Road Infrastructure Assessment</h3>
                    <p class="text-sm text-gray-500 mb-4">Technologies: ArcGIS, Civil 3D</p>
                    <p class="text-gray-700 mb-6">
                        Performed detailed geospatial analysis to determine optimal routing, and subsequently managed the design of drainage and grading for a 15km coastal highway project, focusing on resilience and environmental impact mitigation.
                    </p>
                    <div class="flex space-x-4">
                        <a href="https://mock-demo-coastal.com" target="_blank" class="text-white bg-primary-blue hover:bg-blue-700 py-2 px-4 rounded-lg text-sm font-medium transition duration-300 shadow-md">
                            Live Demo (Mock)
                        </a>
                        <a href="https://github.com/adnan-hossain-engr/coastal-analysis" target="_blank" class="text-primary-blue border border-primary-blue hover:bg-primary-blue hover:text-white py-2 px-4 rounded-lg text-sm font-medium transition duration-300">
                            View GitHub (Mock)
                        </a>
                    </div>
                </div>
                
                <!-- Project 3 -->
                <div class="bg-bg-light p-8 rounded-lg shadow-lg">
                    <h3 class="text-2xl font-semibold mb-3 text-primary-blue">Steel Warehouse Quantity Takeoff & Optimization</h3>
                    <p class="text-sm text-gray-500 mb-4">Technologies: Planswift, Excel (Advanced Macros)</p>
                    <p class="text-gray-700 mb-6">
                        Conducted a comprehensive material quantity takeoff for a 50,000 sq. ft. steel framed warehouse. Utilizing Planswift for accuracy, the process achieved **99% accuracy** in procurement estimates and identified potential material savings.
                    </p>
                    <div class="flex space-x-4">
                        <a href="https://mock-demo-warehouse.com" target="_blank" class="text-white bg-primary-blue hover:bg-blue-700 py-2 px-4 rounded-lg text-sm font-medium transition duration-300 shadow-md">
                            Live Demo (Mock)
                        </a>
                        <a href="https://github.com/adnan-hossain-engr/qs-warehouse" target="_blank" class="text-primary-blue border border-primary-blue hover:bg-primary-blue hover:text-white py-2 px-4 rounded-lg text-sm font-medium transition duration-300">
                            View GitHub (Mock)
                        </a>
                    </div>
                </div>

            </div>
        </section>

        <!-- Academic Papers & Writing -->
        <section id="academic" class="py-20 border-b border-gray-200">
            <h2 class="text-3xl font-bold mb-10 text-center text-text-dark">Academic & Technical Writing</h2>
            
            <div class="grid md:grid-cols-2 gap-8">
                
                <!-- Paper 1 -->
                <div class="p-6 border border-gray-200 rounded-lg">
                    <h3 class="text-xl font-semibold mb-2 text-text-dark">Impact of BIM Adoption on Mid-Sized Construction Firms</h3>
                    <p class="text-sm text-primary-blue mb-3">University Thesis (2023)</p>
                    <p class="text-gray-700 mb-4">
                        Quantitative study examining the Return on Investment (ROI) and common implementation hurdles of BIM for regional contractors in the local market.
                    </p>
                    <a href="https://mock-thesis-link.pdf" target="_blank" class="text-sm text-primary-blue hover:underline">
                        Read Full Paper &rarr;
                    </a>
                </div>

                <!-- Paper 2 -->
                <div class="p-6 border border-gray-200 rounded-lg">
                    <h3 class="text-xl font-semibold mb-2 text-text-dark">Optimizing RCC Beam Design using ETABS & Python Scripting</h3>
                    <p class="text-sm text-primary-blue mb-3">Technical Blog/Article</p>
                    <p class="text-gray-700 mb-4">
                        A detailed case study demonstrating automation of preliminary design checks using the ETABS API and Python, significantly speeding up iteration cycles.
                    </p>
                    <a href="https://mock-article-link.com" target="_blank" class="text-sm text-primary-blue hover:underline">
                        Read Article &rarr;
                    </a>
                </div>

            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-20">
            <h2 class="text-3xl font-bold mb-10 text-center text-text-dark">Get In Touch</h2>
            <div class="max-w-2xl mx-auto text-center space-y-6">
                
                <p class="text-lg text-gray-700">I am currently open to new opportunities and collaborations in structural design, BIM coordination, and quantity surveying. Feel free to connect!</p>

                <div class="flex justify-center space-x-8">
                    <!-- Email -->
                    <a href="mailto:adnan.hossain.civil@example.com" class="text-primary-blue hover:text-blue-700 text-lg font-medium transition duration-300">
                        Email
                    </a>
                    
                    <!-- LinkedIn -->
                    <a href="https://linkedin.com/in/mdadnanhossain" target="_blank" class="text-primary-blue hover:text-blue-700 text-lg font-medium transition duration-300">
                        LinkedIn
                    </a>
                    
                    <!-- GitHub -->
                    <a href="https://github.com/adnan-hossain-engr" target="_blank" class="text-primary-blue hover:text-blue-700 text-lg font-medium transition duration-300">
                        GitHub
                    </a>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-100 border-t border-gray-200 py-6">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center text-sm text-gray-600">
            <p>Md. Adnan Hossain | Civil Engineering & BIM Portfolio 2024</p>
            <p class="mt-1">Designed with a Corporate & Clean aesthetic.</p>
        </div>
    </footer>
</body>
</html>
