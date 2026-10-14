<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Michael Wilfrid Angelo O. Molles | Security & Systems Operations Professional</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        navy: {
                            800: '#0b132b',
                            900: '#070a13',
                            950: '#03050a',
                        },
                        accent: {
                            blue: '#3b82f6',
                            emerald: '#10b981',
                            amber: '#f59e0b',
                            cyan: '#06b6d4',
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #070a13;
            color: #f3f4f6;
        }
        .glass-card {
            background: rgba(17, 24, 39, 0.7);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.08);
        }
        .glass-card-hover {
            transition: all 0.3s ease;
        }
        .glass-card-hover:hover {
            transform: translateY(-4px);
            border-color: rgba(59, 130, 246, 0.4);
            box-shadow: 0 10px 30px -10px rgba(59, 130, 246, 0.2);
        }
        .custom-scrollbar::-webkit-scrollbar {
            width: 6px;
        }
        .custom-scrollbar::-webkit-scrollbar-track {
            background: #0b132b;
        }
        .custom-scrollbar::-webkit-scrollbar-thumb {
            background: #1f2937;
            border-radius: 4px;
        }
        .custom-scrollbar::-webkit-scrollbar-thumb:hover {
            background: #3b82f6;
        }
    </style>
</head>
<body class="custom-scrollbar antialiased">

    <!-- Navigation Bar -->
    <header class="fixed top-0 left-0 right-0 z-50 glass-card bg-opacity-80 border-b border-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-16">
                <!-- Logo / Name -->
                <a href="#hero" class="flex items-center gap-3">
                    <div class="w-10 h-10 rounded-lg bg-gradient-to-tr from-blue-600 to-cyan-400 flex items-center justify-center font-bold text-white shadow-lg shadow-blue-500/20">
                        MM
                    </div>
                    <div>
                        <span class="font-bold text-lg tracking-tight text-white block leading-none">MICHAEL MOLLES</span>
                        <span class="text-xs text-blue-400 font-medium tracking-wider">SECURITY & TECH ADMIN</span>
                    </div>
                </a>

                <!-- Desktop Navigation -->
                <nav class="hidden md:flex space-x-1 lg:space-x-4">
                    <a href="#about" class="px-3 py-2 rounded-md text-sm font-medium text-gray-300 hover:text-white hover:bg-gray-800 transition">About</a>
                    <a href="#experience" class="px-3 py-2 rounded-md text-sm font-medium text-gray-300 hover:text-white hover:bg-gray-800 transition">Experience</a>
                    <a href="#skills" class="px-3 py-2 rounded-md text-sm font-medium text-gray-300 hover:text-white hover:bg-gray-800 transition">Skills</a>
                    <a href="#trainings" class="px-3 py-2 rounded-md text-sm font-medium text-gray-300 hover:text-white hover:bg-gray-800 transition">Trainings</a>
                    <a href="#education" class="px-3 py-2 rounded-md text-sm font-medium text-gray-300 hover:text-white hover:bg-gray-800 transition">Education</a>
                    <a href="#contact" class="px-3 py-2 rounded-md text-sm font-medium text-gray-300 hover:text-white hover:bg-gray-800 transition">Contact</a>
                </nav>

                <!-- Action Button -->
                <div class="hidden md:flex items-center gap-3">
                    <a href="mailto:michaelmolles3@gmail.com" class="px-4 py-2 text-xs font-semibold rounded-lg bg-blue-600 hover:bg-blue-500 text-white shadow-md shadow-blue-600/30 transition flex items-center gap-2">
                        <i class="fa-solid me-1 fa-envelope"></i> Get In Touch
                    </a>
                </div>

                <!-- Mobile Menu Button -->
                <div class="md:hidden">
                    <button id="mobile-menu-btn" type="button" class="text-gray-400 hover:text-white p-2 rounded-lg focus:outline-none" aria-label="Toggle menu">
                        <i class="fa-solid fa-bars text-xl" id="menu-icon"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Mobile Menu Dropdown -->
        <div id="mobile-menu" class="hidden md:hidden glass-card border-t border-gray-800 px-4 pt-2 pb-6 space-y-2">
            <a href="#about" class="mobile-link block px-3 py-2 rounded-md text-base font-medium text-gray-300 hover:text-white hover:bg-gray-800">About</a>
            <a href="#experience" class="mobile-link block px-3 py-2 rounded-md text-base font-medium text-gray-300 hover:text-white hover:bg-gray-800">Experience</a>
            <a href="#skills" class="mobile-link block px-3 py-2 rounded-md text-base font-medium text-gray-300 hover:text-white hover:bg-gray-800">Skills</a>
            <a href="#trainings" class="mobile-link block px-3 py-2 rounded-md text-base font-medium text-gray-300 hover:text-white hover:bg-gray-800">Trainings</a>
            <a href="#education" class="mobile-link block px-3 py-2 rounded-md text-base font-medium text-gray-300 hover:text-white hover:bg-gray-800">Education</a>
            <a href="#contact" class="mobile-link block px-3 py-2 rounded-md text-base font-medium text-gray-300 hover:text-white hover:bg-gray-800">Contact</a>
            <a href="mailto:michaelmolles3@gmail.com" class="block text-center mt-4 w-full py-2 text-sm font-semibold rounded-lg bg-blue-600 hover:bg-blue-500 text-white">
                Contact Me
            </a>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="hero" class="pt-28 pb-16 md:pt-36 md:pb-24 relative overflow-hidden">
        <!-- Background Gradient Glows -->
        <div class="absolute top-1/4 left-1/2 -translate-x-1/2 -translate-y-1/2 w-96 h-96 bg-blue-600/10 rounded-full blur-3xl pointer-events-none"></div>
        <div class="absolute bottom-10 right-10 w-80 h-80 bg-cyan-600/10 rounded-full blur-3xl pointer-events-none"></div>

        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                <!-- Left Details -->
                <div class="lg:col-span-7 space-y-6 text-center lg:text-left">
                    <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full glass-card border border-blue-500/30 text-blue-400 text-xs font-semibold tracking-wide uppercase">
                        <span class="w-2 h-2 rounded-full bg-emerald-400 animate-pulse"></span>
                        Available for Security & System Operations Roles
                    </div>

                    <h1 class="text-3xl sm:text-5xl lg:text-6xl font-extrabold tracking-tight text-white leading-tight">
                        Michael Wilfrid Angelo <br class="hidden sm:inline" />
                        <span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-400 via-cyan-400 to-emerald-400">O. Molles</span>
                    </h1>

                    <p class="text-gray-300 text-base sm:text-lg max-w-2xl mx-auto lg:mx-0 leading-relaxed font-light">
                        Experienced <strong class="text-white font-medium">Security Systems Administrator</strong> & <strong class="text-white font-medium">CCTV Operations Specialist</strong> with a solid foundation in computer hardware servicing, RFID access control, building management systems, and technical customer support.
                    </p>

                    <!-- Quick Details Badges -->
                    <div class="flex flex-wrap gap-4 justify-center lg:justify-start pt-2">
                        <div class="flex items-center gap-2 text-sm text-gray-300 glass-card px-3.5 py-2 rounded-lg">
                            <i class="fa-solid fa-location-dot text-blue-400"></i>
                            <span>Quezon City, Metro Manila</span>
                        </div>
                        <div class="flex items-center gap-2 text-sm text-gray-300 glass-card px-3.5 py-2 rounded-lg">
                            <i class="fa-solid fa-phone text-emerald-400"></i>
                            <a href="tel:09277082012" class="hover:text-white transition">0927-708-2012</a>
                        </div>
                        <div class="flex items-center gap-2 text-sm text-gray-300 glass-card px-3.5 py-2 rounded-lg">
                            <i class="fa-solid fa-envelope text-cyan-400"></i>
                            <button onclick="copyToClipboard('michaelmolles3@gmail.com')" class="hover:text-white transition flex items-center gap-1.5" title="Click to copy email">
                                <span>michaelmolles3@gmail.com</span>
                                <i class="fa-regular fa-copy text-xs text-gray-400"></i>
                            </button>
                        </div>
                    </div>

                    <!-- CTA Buttons -->
                    <div class="flex flex-wrap gap-4 justify-center lg:justify-start pt-4">
                        <a href="#experience" class="px-6 py-3 rounded-lg bg-blue-600 hover:bg-blue-500 text-white font-medium text-sm transition shadow-lg shadow-blue-600/30 flex items-center gap-2">
                            <i class="fa-solid fa-briefcase"></i> View Career History
                        </a>
                        <a href="#contact" class="px-6 py-3 rounded-lg glass-card hover:bg-gray-800 text-gray-200 hover:text-white font-medium text-sm transition border border-gray-700 flex items-center gap-2">
                            <i class="fa-solid fa-id-card"></i> Personal Bio & Contact
                        </a>
                    </div>
                </div>

                <!-- Right Card / Avatar Photo Container -->
                <div class="lg:col-span-5 flex justify-center">
                    <div class="relative w-full max-w-sm">
                        <!-- Subtle Backing Glow -->
                        <div class="absolute -inset-1 rounded-2xl bg-gradient-to-r from-blue-600 to-cyan-500 opacity-30 blur-lg"></div>
                        
                        <div class="relative glass-card rounded-2xl p-6 text-center shadow-2xl border border-gray-800">
                            <!-- Photo with fallback handling -->
                            <div class="relative w-40 h-40 mx-auto mb-4 rounded-full overflow-hidden border-4 border-blue-500/40 p-1 shadow-inner bg-gray-900">
                                <img src="https://placehold.co/300x300/1e293b/38bdf8?text=Michael+Molles" 
                                     alt="Michael Wilfrid Angelo O. Molles" 
                                     class="w-full h-full object-cover rounded-full"
                                     onerror="this.src='https://placehold.co/300x300/111827/ffffff?text=MM'">
                            </div>

                            <h3 class="text-xl font-bold text-white">Michael W. A. Molles</h3>
                            <p class="text-xs text-blue-400 font-semibold uppercase tracking-wider mb-4">Security Systems Admin & CCTV Operator</p>

                            <!-- Key Metrics Highlight Grid -->
                            <div class="grid grid-cols-2 gap-3 text-left pt-2 border-t border-gray-800">
                                <div class="p-2.5 rounded-lg bg-gray-900/60 border border-gray-800">
                                    <div class="text-xs text-gray-400">Experience</div>
                                    <div class="text-base font-bold text-white">8+ Years</div>
                                </div>
                                <div class="p-2.5 rounded-lg bg-gray-900/60 border border-gray-800">
                                    <div class="text-xs text-gray-400">Specialization</div>
                                    <div class="text-base font-bold text-cyan-400">RFID / NVR / CCTV</div>
                                </div>
                                <div class="p-2.5 rounded-lg bg-gray-900/60 border border-gray-800">
                                    <div class="text-xs text-gray-400">High Profile Sites</div>
                                    <div class="text-sm font-semibold text-gray-200">Ateneo / P&G BGC</div>
                                </div>
                                <div class="p-2.5 rounded-lg bg-gray-900/60 border border-gray-800">
                                    <div class="text-xs text-gray-400">Tech Background</div>
                                    <div class="text-sm font-semibold text-emerald-400">Computer Prog/HW</div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- About & Summary Section -->
    <section id="about" class="py-16 bg-navy-900/50 border-y border-gray-800/80">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-12">
                <h2 class="text-xs font-bold text-blue-400 tracking-widest uppercase mb-2">Professional Summary</h2>
                <h3 class="text-2xl sm:text-3xl font-bold text-white">Versatile Technical Security & Operations Specialist</h3>
                <div class="w-16 h-1 bg-gradient-to-r from-blue-500 to-cyan-400 mx-auto mt-4 rounded-full"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <!-- Feature Card 1 -->
                <div class="glass-card glass-card-hover rounded-xl p-6 relative overflow-hidden group">
                    <div class="w-12 h-12 rounded-lg bg-blue-500/10 text-blue-400 flex items-center justify-center text-xl mb-4 group-hover:bg-blue-600 group-hover:text-white transition">
                        <i class="fa-solid fa-video"></i>
                    </div>
                    <h4 class="text-lg font-bold text-white mb-2">CCTV & NVR Monitoring</h4>
                    <p class="text-sm text-gray-300 leading-relaxed">
                        Expert in real-time night shift surveillance, footage review, evidence extraction, and rapid incident dispatch coordination with on-ground K9, EMT, and security personnel.
                    </p>
                </div>

                <!-- Feature Card 2 -->
                <div class="glass-card glass-card-hover rounded-xl p-6 relative overflow-hidden group">
                    <div class="w-12 h-12 rounded-lg bg-cyan-500/10 text-cyan-400 flex items-center justify-center text-xl mb-4 group-hover:bg-cyan-600 group-hover:text-white transition">
                        <i class="fa-solid fa-id-card-clip"></i>
                    </div>
                    <h4 class="text-lg font-bold text-white mb-2">Access Control & Systems Admin</h4>
                    <p class="text-sm text-gray-300 leading-relaxed">
                        Extensive hands-on experience in RFID employee access, turnstiles, Building Management Systems (BMS), server room environmental monitoring, and civil works supervision.
                    </p>
                </div>

                <!-- Feature Card 3 -->
                <div class="glass-card glass-card-hover rounded-xl p-6 relative overflow-hidden group">
                    <div class="w-12 h-12 rounded-lg bg-emerald-500/10 text-emerald-400 flex items-center justify-center text-xl mb-4 group-hover:bg-emerald-600 group-hover:text-white transition">
                        <i class="fa-solid fa-headset"></i>
                    </div>
                    <h4 class="text-lg font-bold text-white mb-2">Customer Support & HR Operations</h4>
                    <p class="text-sm text-gray-300 leading-relaxed">
                        Strong background in blended tech support, customer assistance, HR compliance, orientation, applicant pooling, and multi-channel client communication (MS Teams, Zoom, Viber).
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Experience Section -->
    <section id="experience" class="py-20 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-12">
                <div>
                    <h2 class="text-xs font-bold text-blue-400 tracking-widest uppercase mb-2">Career Journey</h2>
                    <h3 class="text-2xl sm:text-3xl font-bold text-white">Work Experience Timeline</h3>
                </div>
                <!-- Experience Filter Pills -->
                <div id="experience-filters" class="flex flex-wrap gap-2 mt-4 md:mt-0">
                    <button data-filter="all" class="filter-btn px-3 py-1.5 text-xs font-semibold rounded-lg bg-blue-600 text-white transition">All Roles</button>
                    <button data-filter="security" class="filter-btn px-3 py-1.5 text-xs font-semibold rounded-lg glass-card text-gray-300 hover:text-white transition">Security & Admin</button>
                    <button data-filter="tech" class="filter-btn px-3 py-1.5 text-xs font-semibold rounded-lg glass-card text-gray-300 hover:text-white transition">Tech & Customer Support</button>
                    <button data-filter="hr" class="filter-btn px-3 py-1.5 text-xs font-semibold rounded-lg glass-card text-gray-300 hover:text-white transition">HR & Services</button>
                </div>
            </div>

            <!-- Timeline Structure -->
            <div class="relative border-l-2 border-gray-800 ml-4 md:ml-32 space-y-12">

                <!-- Timeline Item 1: Megaforce Ateneo -->
                <div class="timeline-item relative pl-6 md:pl-8" data-category="security">
                    <!-- Date badge left side desktop -->
                    <div class="hidden md:flex absolute -left-32 top-0.5 w-24 justify-end text-xs font-semibold text-blue-400">
                        Jan 2025 - Present
                    </div>
                    <!-- Node Bullet -->
                    <div class="absolute -left-[9px] top-1 w-4 h-4 rounded-full bg-blue-500 border-4 border-navy-900 shadow"></div>
                    
                    <div class="glass-card glass-card-hover rounded-xl p-6">
                        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 mb-3">
                            <div>
                                <span class="md:hidden inline-block text-xs font-bold text-blue-400 mb-1">January 2025 – Present</span>
                                <h4 class="text-lg font-bold text-white">CCTV Operator / Monitoring Officer</h4>
                                <p class="text-sm text-gray-300 font-medium">Megaforce Security — <span class="text-blue-400">Ateneo De Manila Campus</span></p>
                            </div>
                            <span class="inline-flex items-center px-2.5 py-1 rounded-full text-xs font-semibold bg-blue-500/10 text-blue-400 border border-blue-500/20 w-fit">
                                Current Role
                            </span>
                        </div>

                        <ul class="space-y-2 text-sm text-gray-300 list-disc list-inside">
                            <li>Directly reports to the Assistant Detachment Commander in managing night shift guard operations and site safety.</li>
                            <li>Coordinates seamlessly with on-ground security personnel, K9 units, and EMT emergency responders via Radio and Phone.</li>
                            <li>Performs detailed CCTV footage reviews and evidence retrieval via NVR search for investigation team coordination.</li>
                            <li>Executes regular system checks for camera status and recording loss to dispatch maintenance teams for immediate repairs.</li>
                        </ul>
                    </div>
                </div>

                <!-- Timeline Item 2: Concentrix -->
                <div class="timeline-item relative pl-6 md:pl-8" data-category="tech">
                    <div class="hidden md:flex absolute -left-32 top-0.5 w-24 justify-end text-xs font-semibold text-cyan-400">
                        May 2024 - Oct 2024
                    </div>
                    <div class="absolute -left-[9px] top-1 w-4 h-4 rounded-full bg-cyan-500 border-4 border-navy-900 shadow"></div>

                    <div class="glass-card glass-card-hover rounded-xl p-6">
                        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 mb-3">
                            <div>
                                <span class="md:hidden inline-block text-xs font-bold text-cyan-400 mb-1">May 2024 – October 2024</span>
                                <h4 class="text-lg font-bold text-white">Advisor I (Blended Support)</h4>
                                <p class="text-sm text-gray-300 font-medium">Concentrix — <span class="text-cyan-400">UP Technohub</span></p>
                            </div>
                            <span class="inline-flex items-center px-2.5 py-1 rounded-full text-xs font-semibold bg-cyan-500/10 text-cyan-400 border border-cyan-500/20 w-fit">
                                Tech Support
                            </span>
                        </div>

                        <ul class="space-y-2 text-sm text-gray-300 list-disc list-inside">
                            <li>Resolved technical issues encountered by clients regarding application navigation and web portal functionality.</li>
                            <li>Walked clients through streaming app operations, payment gateways, and recommended optimized subscription packages.</li>
                            <li>Provided prompt updates regarding service structural changes, rates, and platform updates.</li>
                        </ul>
                    </div>
                </div>

                <!-- Timeline Item 3: Megaforce Procter & Gamble -->
                <div class="timeline-item relative pl-6 md:pl-8" data-category="security">
                    <div class="hidden md:flex absolute -left-32 top-0.5 w-24 justify-end text-xs font-semibold text-emerald-400">
                        Jul 2017 - Oct 2023
                    </div>
                    <div class="absolute -left-[9px] top-1 w-4 h-4 rounded-full bg-emerald-500 border-4 border-navy-900 shadow"></div>

                    <div class="glass-card glass-card-hover rounded-xl p-6">
                        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 mb-3">
                            <div>
                                <span class="md:hidden inline-block text-xs font-bold text-emerald-400 mb-1">July 2017 – October 2023</span>
                                <h4 class="text-lg font-bold text-white">Security System Administrator</h4>
                                <p class="text-sm text-gray-300 font-medium">Megaforce Security — <span class="text-emerald-400">Procter & Gamble / One Serendra, BGC</span></p>
                            </div>
                            <span class="inline-flex items-center px-2.5 py-1 rounded-full text-xs font-semibold bg-emerald-500/10 text-emerald-400 border border-emerald-500/20 w-fit">
                                6+ Years Core Role
                            </span>
                        </div>

                        <ul class="space-y-2 text-sm text-gray-300 list-disc list-inside">
                            <li>Managed RFID badge access control for employees, contractors, and visitors, including building turnstiles & parking access.</li>
                            <li>Monitored employee time logs using access card timestamps for attendance verification.</li>
                            <li>Oversee CCTV, door control hardware, and vendor contractors to execute routine preventive maintenance and rapid repairs.</li>
                            <li>Supervised critical server room access and closely monitored temperature levels via Building Management Systems (BMS) & FDAS.</li>
                            <li>Provided technical troubleshooting and prompt customer service regarding parking/access issues via Zoom, MS Teams, Viber.</li>
                            <li>Supervised contractor teams in executing civil, electrical, and hardware installation/repair projects.</li>
                        </ul>
                    </div>
                </div>

                <!-- Timeline Item 4: Sykes / Foundever -->
                <div class="timeline-item relative pl-6 md:pl-8" data-category="tech">
                    <div class="hidden md:flex absolute -left-32 top-0.5 w-24 justify-end text-xs font-semibold text-amber-400">
                        Nov 2021 - Jun 2022
                    </div>
                    <div class="absolute -left-[9px] top-1 w-4 h-4 rounded-full bg-amber-500 border-4 border-navy-900 shadow"></div>

                    <div class="glass-card glass-card-hover rounded-xl p-6">
                        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 mb-3">
                            <div>
                                <span class="md:hidden inline-block text-xs font-bold text-amber-400 mb-1">November 2021 – June 2022</span>
                                <h4 class="text-lg font-bold text-white">Customer Service Agent</h4>
                                <p class="text-sm text-gray-300 font-medium">Sykes Asia (Foundever)</p>
                            </div>
                        </div>

                        <ul class="space-y-2 text-sm text-gray-300 list-disc list-inside">
                            <li>Handled inbound/outbound calls to assist customers with credit card payments and account maintenance.</li>
                            <li>Updated client records online and processed online payment requests accurately.</li>
                            <li>Educated clients on credit card benefits, service features, interest rate structures, and recurring active subscriptions.</li>
                            <li>Processed fraudulent charge disputes following strict financial compliance protocols.</li>
                        </ul>
                    </div>
                </div>

                <!-- Timeline Item 5: ESA HR Officer -->
                <div class="timeline-item relative pl-6 md:pl-8" data-category="hr">
                    <div class="hidden md:flex absolute -left-32 top-0.5 w-24 justify-end text-xs font-semibold text-purple-400">
                        2014 - 2017
                    </div>
                    <div class="absolute -left-[9px] top-1 w-4 h-4 rounded-full bg-purple-500 border-4 border-navy-900 shadow"></div>

                    <div class="glass-card glass-card-hover rounded-xl p-6">
                        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 mb-3">
                            <div>
                                <span class="md:hidden inline-block text-xs font-bold text-purple-400 mb-1">2014 – 2017</span>
                                <h4 class="text-lg font-bold text-white">HR Officer</h4>
                                <p class="text-sm text-gray-300 font-medium">ESA Employment Specialist Corp.</p>
                            </div>
                        </div>

                        <ul class="space-y-2 text-sm text-gray-300 list-disc list-inside">
                            <li>Conducted onboarding orientations for new hires regarding employment contracts, policies, and payroll deductions.</li>
                            <li>Executed due process sanctions for policy violations and handled legal/HR documentation.</li>
                            <li>Managed company government compliance requirements (SSS, PhilHealth, Pag-IBIG).</li>
                            <li>Represented the company in job fairs, candidate pooling, client meetings, and routine store audit inspections.</li>
                        </ul>
                    </div>
                </div>

                <!-- Timeline Item 6: Mc Mary's -->
                <div class="timeline-item relative pl-6 md:pl-8" data-category="hr">
                    <div class="hidden md:flex absolute -left-32 top-0.5 w-24 justify-end text-xs font-semibold text-rose-400">
                        Jan 2013 - May 2014
                    </div>
                    <div class="absolute -left-[9px] top-1 w-4 h-4 rounded-full bg-rose-500 border-4 border-navy-900 shadow"></div>

                    <div class="glass-card glass-card-hover rounded-xl p-6">
                        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 mb-3">
                            <div>
                                <span class="md:hidden inline-block text-xs font-bold text-rose-400 mb-1">January 2013 – May 2014</span>
                                <h4 class="text-lg font-bold text-white">Service Crew</h4>
                                <p class="text-sm text-gray-300 font-medium">Mc Mary's Food Corp.</p>
                            </div>
                        </div>

                        <p class="text-sm text-gray-300 leading-relaxed">
                            Ensured a seamless dining experience by delivering friendly customer service, accurately preparing food orders, and maintaining strict food safety and cleanliness standards in a fast-paced environment.
                        </p>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Skills Breakdown Section -->
    <section id="skills" class="py-20 bg-navy-900/50 border-t border-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-xs font-bold text-blue-400 tracking-widest uppercase mb-2">Capabilities & Expertise</h2>
                <h3 class="text-2xl sm:text-3xl font-bold text-white">Core Skills Breakdown</h3>
                <div class="w-16 h-1 bg-gradient-to-r from-blue-500 to-cyan-400 mx-auto mt-4 rounded-full"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">

                <!-- Skill Category 1 -->
                <div class="glass-card rounded-xl p-6 border border-gray-800">
                    <div class="flex items-center gap-3 mb-4">
                        <div class="p-3 rounded-lg bg-blue-500/10 text-blue-400">
                            <i class="fa-solid fa-shield-halved text-xl"></i>
                        </div>
                        <h4 class="text-lg font-bold text-white">Security Operations</h4>
                    </div>
                    <ul class="space-y-3">
                        <li class="flex items-center justify-between text-sm">
                            <span class="text-gray-300">CCTV & NVR Search</span>
                            <span class="text-xs text-blue-400 font-semibold">Expert</span>
                        </li>
                        <div class="w-full bg-gray-800 h-1.5 rounded-full overflow-hidden">
                            <div class="bg-blue-500 h-full w-11/12 rounded-full"></div>
                        </div>

                        <li class="flex items-center justify-between text-sm">
                            <span class="text-gray-300">Emergency Dispatch & Radio</span>
                            <span class="text-xs text-blue-400 font-semibold">Advanced</span>
                        </li>
                        <div class="w-full bg-gray-800 h-1.5 rounded-full overflow-hidden">
                            <div class="bg-blue-500 h-full w-10/12 rounded-full"></div>
                        </div>

                        <li class="flex items-center justify-between text-sm">
                            <span class="text-gray-300">Evidence Extraction & Investigation</span>
                            <span class="text-xs text-blue-400 font-semibold">Advanced</span>
                        </li>
                        <div class="w-full bg-gray-800 h-1.5 rounded-full overflow-hidden">
                            <div class="bg-blue-500 h-full w-10/12 rounded-full"></div>
                        </div>
                    </ul>
                </div>

                <!-- Skill Category 2 -->
                <div class="glass-card rounded-xl p-6 border border-gray-800">
                    <div class="flex items-center gap-3 mb-4">
                        <div class="p-3 rounded-lg bg-cyan-500/10 text-cyan-400">
                            <i class="fa-solid fa-server text-xl"></i>
                        </div>
                        <h4 class="text-lg font-bold text-white">Systems & Admin</h4>
                    </div>
                    <ul class="space-y-3">
                        <li class="flex items-center justify-between text-sm">
                            <span class="text-gray-300">RFID Access Control & Turnstiles</span>
                            <span class="text-xs text-cyan-400 font-semibold">Expert</span>
                        </li>
                        <div class="w-full bg-gray-800 h-1.5 rounded-full overflow-hidden">
                            <div class="bg-cyan-500 h-full w-11/12 rounded-full"></div>
                        </div>

                        <li class="flex items-center justify-between text-sm">
                            <span class="text-gray-300">Building Management System (BMS)</span>
                            <span class="text-xs text-cyan-400 font-semibold">Proficient</span>
                        </li>
                        <div class="w-full bg-gray-800 h-1.5 rounded-full overflow-hidden">
                            <div class="bg-cyan-500 h-full w-9/12 rounded-full"></div>
                        </div>

                        <li class="flex items-center justify-between text-sm">
                            <span class="text-gray-300">FDAS & Server Room Temp Monitoring</span>
                            <span class="text-xs text-cyan-400 font-semibold">Advanced</span>
                        </li>
                        <div class="w-full bg-gray-800 h-1.5 rounded-full overflow-hidden">
                            <div class="bg-cyan-500 h-full w-10/12 rounded-full"></div>
                        </div>
                    </ul>
                </div>

                <!-- Skill Category 3 -->
                <div class="glass-card rounded-xl p-6 border border-gray-800">
                    <div class="flex items-center gap-3 mb-4">
                        <div class="p-3 rounded-lg bg-emerald-500/10 text-emerald-400">
                            <i class="fa-solid fa-microchip text-xl"></i>
                        </div>
                        <h4 class="text-lg font-bold text-white">Hardware & IT Skills</h4>
                    </div>
                    <ul class="space-y-3">
                        <li class="flex items-center justify-between text-sm">
                            <span class="text-gray-300">Computer Hardware Servicing</span>
                            <span class="text-xs text-emerald-400 font-semibold">Vocational Certified</span>
                        </li>
                        <div class="w-full bg-gray-800 h-1.5 rounded-full overflow-hidden">
                            <div class="bg-emerald-500 h-full w-10/12 rounded-full"></div>
                        </div>

                        <li class="flex items-center justify-between text-sm">
                            <span class="text-gray-300">Computer Programming Basics</span>
                            <span class="text-xs text-emerald-400 font-semibold">Foundational</span>
                        </li>
                        <div class="w-full bg-gray-800 h-1.5 rounded-full overflow-hidden">
                            <div class="bg-emerald-500 h-full w-8/12 rounded-full"></div>
                        </div>

                        <li class="flex items-center justify-between text-sm">
                            <span class="text-gray-300">Civil & Installation Works Supervision</span>
                            <span class="text-xs text-emerald-400 font-semibold">Proficient</span>
                        </li>
                        <div class="w-full bg-gray-800 h-1.5 rounded-full overflow-hidden">
                            <div class="bg-emerald-500 h-full w-9/12 rounded-full"></div>
                        </div>
                    </ul>
                </div>

            </div>

            <!-- Soft Skills & Tools Chips -->
            <div class="mt-8 glass-card rounded-xl p-6 border border-gray-800">
                <h4 class="text-sm font-bold text-gray-300 uppercase tracking-wider mb-4">Communication Tools & Operational Software</h4>
                <div class="flex flex-wrap gap-2">
                    <span class="px-3 py-1.5 rounded-lg bg-gray-800 text-gray-200 text-xs font-medium border border-gray-700 flex items-center gap-1.5">
                        <i class="fa-solid fa-video text-blue-400"></i> MS Teams / Zoom
                    </span>
                    <span class="px-3 py-1.5 rounded-lg bg-gray-800 text-gray-200 text-xs font-medium border border-gray-700 flex items-center gap-1.5">
                        <i class="fa-brands fa-viber text-purple-400"></i> Viber Coordination
                    </span>
                    <span class="px-3 py-1.5 rounded-lg bg-gray-800 text-gray-200 text-xs font-medium border border-gray-700 flex items-center gap-1.5">
                        <i class="fa-solid fa-headset text-emerald-400"></i> Blended Support
                    </span>
                    <span class="px-3 py-1.5 rounded-lg bg-gray-800 text-gray-200 text-xs font-medium border border-gray-700 flex items-center gap-1.5">
                        <i class="fa-solid fa-clipboard-check text-amber-400"></i> HR Compliance & Sanctions
                    </span>
                    <span class="px-3 py-1.5 rounded-lg bg-gray-800 text-gray-200 text-xs font-medium border border-gray-700 flex items-center gap-1.5">
                        <i class="fa-solid fa-users text-cyan-400"></i> Virtual Assistant Training
                    </span>
                </div>
            </div>
        </div>
    </section>

    <!-- Trainings and Seminars Section -->
    <section id="trainings" class="py-20 border-t border-gray-800 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-xs font-bold text-blue-400 tracking-widest uppercase mb-2">Professional Credentials</h2>
                <h3 class="text-2xl sm:text-3xl font-bold text-white">Trainings & Seminars Attended</h3>
                <div class="w-16 h-1 bg-gradient-to-r from-blue-500 to-cyan-400 mx-auto mt-4 rounded-full"></div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">

                <!-- Seminar 1 -->
                <div class="glass-card glass-card-hover rounded-xl p-6 border border-gray-800 relative flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between mb-3">
                            <span class="text-xs font-bold text-emerald-400 bg-emerald-500/10 px-2.5 py-1 rounded-md border border-emerald-500/20">
                                May 24, 2025
                            </span>
                            <i class="fa-solid fa-certificate text-emerald-400"></i>
                        </div>
                        <h4 class="text-base font-bold text-white mb-1">CCTV Operations and Management</h4>
                        <p class="text-xs text-gray-400">Right Eye Detective and Protective Services</p>
                    </div>
                </div>

                <!-- Seminar 2 -->
                <div class="glass-card glass-card-hover rounded-xl p-6 border border-gray-800 relative flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between mb-3">
                            <span class="text-xs font-bold text-blue-400 bg-blue-500/10 px-2.5 py-1 rounded-md border border-blue-500/20">
                                Sep 18, 2023
                            </span>
                            <i class="fa-solid fa-user-shield text-blue-400"></i>
                        </div>
                        <h4 class="text-base font-bold text-white mb-1">Basic Security Supervisory Course</h4>
                        <p class="text-xs text-gray-400">Intensity - C Security Training Center Inc (Quezon City)</p>
                    </div>
                </div>

                <!-- Seminar 3 -->
                <div class="glass-card glass-card-hover rounded-xl p-6 border border-gray-800 relative flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between mb-3">
                            <span class="text-xs font-bold text-blue-400 bg-blue-500/10 px-2.5 py-1 rounded-md border border-blue-500/20">
                                Sep 27, 2023
                            </span>
                            <i class="fa-solid fa-shield-halved text-blue-400"></i>
                        </div>
                        <h4 class="text-base font-bold text-white mb-1">In-Service Enhancement Security Training</h4>
                        <p class="text-xs text-gray-400">Intensity - C Security Training Center Inc (Quezon City)</p>
                    </div>
                </div>

                <!-- Seminar 4 -->
                <div class="glass-card glass-card-hover rounded-xl p-6 border border-gray-800 relative flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between mb-3">
                            <span class="text-xs font-bold text-cyan-400 bg-cyan-500/10 px-2.5 py-1 rounded-md border border-cyan-500/20">
                                April 30, 2022
                            </span>
                            <i class="fa-solid fa-laptop-code text-cyan-400"></i>
                        </div>
                        <h4 class="text-base font-bold text-white mb-1">Basic Virtual Assistant Training</h4>
                        <p class="text-xs text-gray-400">VA Training Philippines</p>
                    </div>
                </div>

                <!-- Seminar 5 -->
                <div class="glass-card glass-card-hover rounded-xl p-6 border border-gray-800 relative flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between mb-3">
                            <span class="text-xs font-bold text-amber-400 bg-amber-500/10 px-2.5 py-1 rounded-md border border-amber-500/20">
                                Jan 30, 2020
                            </span>
                            <i class="fa-solid fa-building text-amber-400"></i>
                        </div>
                        <h4 class="text-base font-bold text-white mb-1">One Mega Seminar</h4>
                        <p class="text-xs text-gray-400">Megaforce Security (Quezon City)</p>
                    </div>
                </div>

                <!-- Seminar 6 & 7 combined card -->
                <div class="glass-card glass-card-hover rounded-xl p-6 border border-gray-800 relative flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between mb-3">
                            <span class="text-xs font-bold text-purple-400 bg-purple-500/10 px-2.5 py-1 rounded-md border border-purple-500/20">
                                June - August 2016
                            </span>
                            <i class="fa-solid fa-store text-purple-400"></i>
                        </div>
                        <h4 class="text-base font-bold text-white mb-1">Store Ops & Employer Forum</h4>
                        <p class="text-xs text-gray-400">ESA Employment / Taguig City Employer Consultation</p>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Education & Personal Profile Section -->
    <section id="education" class="py-20 bg-navy-900/50 border-t border-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8">

                <!-- Education (7 Cols) -->
                <div class="lg:col-span-7 space-y-6">
                    <div>
                        <h2 class="text-xs font-bold text-blue-400 tracking-widest uppercase mb-2">Academic Foundation</h2>
                        <h3 class="text-2xl font-bold text-white">Educational Background</h3>
                    </div>

                    <div class="space-y-4">
                        <!-- Tertiary / Vocational -->
                        <div class="glass-card rounded-xl p-6 border border-gray-800 border-l-4 border-l-blue-500">
                            <div class="flex justify-between items-start">
                                <div>
                                    <h4 class="text-lg font-bold text-white">Quezon City Polytechnic University</h4>
                                    <p class="text-sm text-blue-400 font-medium">Vocational Courses (2010 – 2012)</p>
                                </div>
                                <span class="p-2 rounded-lg bg-blue-500/10 text-blue-400"><i class="fa-solid fa-graduation-cap"></i></span>
                            </div>
                            <div class="mt-3 flex flex-wrap gap-2">
                                <span class="text-xs bg-gray-800 text-gray-300 px-2.5 py-1 rounded border border-gray-700">Computer Programming (1 Year)</span>
                                <span class="text-xs bg-gray-800 text-gray-300 px-2.5 py-1 rounded border border-gray-700">Computer Hardware Servicing</span>
                            </div>
                        </div>

                        <!-- Secondary -->
                        <div class="glass-card rounded-xl p-5 border border-gray-800">
                            <div class="flex justify-between items-start">
                                <div>
                                    <h4 class="text-base font-bold text-white">Manuel Roxas High School</h4>
                                    <p class="text-xs text-gray-400">High School Diploma (2005 – 2009) — Quezon City</p>
                                </div>
                            </div>
                        </div>

                        <!-- Elementary -->
                        <div class="glass-card rounded-xl p-5 border border-gray-800">
                            <div class="flex justify-between items-start">
                                <div>
                                    <h4 class="text-base font-bold text-white">San Vicente Elementary School</h4>
                                    <p class="text-xs text-gray-400">Elementary Education (1999 – 2005) — Quezon City</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Personal Bio Details (5 Cols) -->
                <div class="lg:col-span-5 space-y-6">
                    <div>
                        <h2 class="text-xs font-bold text-cyan-400 tracking-widest uppercase mb-2">Personal Details</h2>
                        <h3 class="text-2xl font-bold text-white">Profile Overview</h3>
                    </div>

                    <div class="glass-card rounded-xl p-6 border border-gray-800 space-y-4">
                        <div class="grid grid-cols-2 gap-4 text-sm">
                            <div class="border-b border-gray-800 pb-2">
                                <span class="text-xs text-gray-400 block">Date of Birth</span>
                                <span class="font-semibold text-gray-200">January 19, 1993</span>
                            </div>
                            <div class="border-b border-gray-800 pb-2">
                                <span class="text-xs text-gray-400 block">Age</span>
                                <span class="font-semibold text-gray-200">33 Years Old</span>
                            </div>
                            <div class="border-b border-gray-800 pb-2">
                                <span class="text-xs text-gray-400 block">Civil Status</span>
                                <span class="font-semibold text-gray-200">Married</span>
                            </div>
                            <div class="border-b border-gray-800 pb-2">
                                <span class="text-xs text-gray-400 block">Height</span>
                                <span class="font-semibold text-gray-200">5'8"</span>
                            </div>
                            <div class="border-b border-gray-800 pb-2">
                                <span class="text-xs text-gray-400 block">Religion</span>
                                <span class="font-semibold text-gray-200">Roman Catholic</span>
                            </div>
                            <div class="border-b border-gray-800 pb-2">
                                <span class="text-xs text-gray-400 block">Birthplace</span>
                                <span class="font-semibold text-gray-200">Pagadian City, Zamboanga Del Sur</span>
                            </div>
                        </div>

                        <!-- Certification Statement -->
                        <div class="pt-2 text-xs text-gray-400 italic bg-gray-900/60 p-3 rounded-lg border border-gray-800">
                            "I hereby certify that all information indicated above is true and correct to the best of my knowledge."
                            <div class="mt-2 font-bold text-gray-300 not-italic">— MICHAEL WILFRID ANGELO O. MOLLES</div>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 border-t border-gray-800 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="max-w-4xl mx-auto glass-card rounded-2xl p-8 sm:p-12 border border-gray-800 shadow-2xl relative overflow-hidden">
                <!-- Top Accent Line -->
                <div class="absolute top-0 left-0 right-0 h-1 bg-gradient-to-r from-blue-500 via-cyan-400 to-emerald-400"></div>

                <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
                    <div>
                        <h2 class="text-2xl sm:text-3xl font-extrabold text-white mb-4">Let's Connect & Collaborate</h2>
                        <p class="text-gray-300 text-sm leading-relaxed mb-6">
                            Looking for a reliable Security Systems Administrator, CCTV Specialist, or Technical Operations professional? Reach out via phone or email directly.
                        </p>

                        <div class="space-y-4">
                            <div class="flex items-center gap-3">
                                <div class="w-10 h-10 rounded-lg bg-blue-500/10 text-blue-400 flex items-center justify-center shrink-0">
                                    <i class="fa-solid fa-phone"></i>
                                </div>
                                <div>
                                    <div class="text-xs text-gray-400">Contact Number</div>
                                    <a href="tel:09277082012" class="text-sm font-bold text-white hover:text-blue-400 transition">0927-708-2012</a>
                                </div>
                            </div>

                            <div class="flex items-center gap-3">
                                <div class="w-10 h-10 rounded-lg bg-cyan-500/10 text-cyan-400 flex items-center justify-center shrink-0">
                                    <i class="fa-solid fa-envelope"></i>
                                </div>
                                <div>
                                    <div class="text-xs text-gray-400">Email Address</div>
                                    <button onclick="copyToClipboard('michaelmolles3@gmail.com')" class="text-sm font-bold text-white hover:text-cyan-400 transition text-left">
                                        michaelmolles3@gmail.com
                                    </button>
                                </div>
                            </div>

                            <div class="flex items-center gap-3">
                                <div class="w-10 h-10 rounded-lg bg-emerald-500/10 text-emerald-400 flex items-center justify-center shrink-0">
                                    <i class="fa-solid fa-location-dot"></i>
                                </div>
                                <div>
                                    <div class="text-xs text-gray-400">Residential Address</div>
                                    <div class="text-sm font-bold text-white">1 Panther St, Area 4 Ext, Brgy Bagong Silangan, Quezon City</div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Interactive Quick Inquiry Form -->
                    <div class="bg-gray-900/80 p-6 rounded-xl border border-gray-800">
                        <h4 class="text-base font-bold text-white mb-4">Send a Direct Message</h4>
                        <form id="contact-form" onsubmit="handleFormSubmit(event)" class="space-y-4">
                            <div>
                                <label class="block text-xs font-medium text-gray-400 mb-1">Your Name</label>
                                <input type="text" required placeholder="John Doe" class="w-full px-3 py-2 rounded-lg bg-gray-800 border border-gray-700 text-sm text-white focus:outline-none focus:border-blue-500">
                            </div>
                            <div>
                                <label class="block text-xs font-medium text-gray-400 mb-1">Your Email or Phone</label>
                                <input type="text" required placeholder="name@company.com" class="w-full px-3 py-2 rounded-lg bg-gray-800 border border-gray-700 text-sm text-white focus:outline-none focus:border-blue-500">
                            </div>
                            <div>
                                <label class="block text-xs font-medium text-gray-400 mb-1">Message / Inquiry</label>
                                <textarea rows="3" required placeholder="Hello Michael, I would like to discuss..." class="w-full px-3 py-2 rounded-lg bg-gray-800 border border-gray-700 text-sm text-white focus:outline-none focus:border-blue-500"></textarea>
                            </div>
                            <button type="submit" class="w-full py-2.5 rounded-lg bg-blue-600 hover:bg-blue-500 text-white font-semibold text-sm transition shadow-lg shadow-blue-600/30">
                                Send Message
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-8 bg-navy-950 border-t border-gray-900 text-center text-xs text-gray-400">
        <div class="max-w-7xl mx-auto px-4">
            <p>© 2026 Michael Wilfrid Angelo O. Molles. All rights reserved.</p>
            <p class="mt-1 text-gray-400">Security Systems Admin & Operations Specialist — Quezon City, Philippines</p>
        </div>
    </footer>

    <!-- Notification Toast Container -->
    <div id="toast" class="fixed bottom-5 right-5 z-50 transform translate-y-20 opacity-0 transition-all duration-300 glass-card bg-emerald-900/90 border border-emerald-500 text-white px-4 py-3 rounded-lg shadow-xl flex items-center gap-3">
        <i class="fa-solid fa-circle-check text-emerald-400"></i>
        <span id="toast-message" class="text-xs font-semibold">Action completed successfully!</span>
    </div>

    <!-- Interactive Script -->
    <script>
        // Mobile Menu Toggle
        const menuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        const menuIcon = document.getElementById('menu-icon');
        const mobileLinks = document.querySelectorAll('.mobile-link');

        menuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
            if (mobileMenu.classList.contains('hidden')) {
                menuIcon.className = 'fa-solid fa-bars text-xl';
            } else {
                menuIcon.className = 'fa-solid fa-xmark text-xl';
            }
        });

        mobileLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
                menuIcon.className = 'fa-solid fa-bars text-xl';
            });
        });

        // Timeline Filter functionality
        const filterBtns = document.querySelectorAll('.filter-btn');
        const timelineItems = document.querySelectorAll('.timeline-item');

        filterBtns.forEach(btn => {
            btn.addEventListener('click', () => {
                // Remove active classes
                filterBtns.forEach(b => {
                    b.classList.remove('bg-blue-600', 'text-white');
                    b.classList.add('glass-card', 'text-gray-300');
                });
                // Add active state to clicked button
                btn.classList.add('bg-blue-600', 'text-white');
                btn.classList.remove('glass-card', 'text-gray-300');

                const filter = btn.getAttribute('data-filter');

                timelineItems.forEach(item => {
                    if (filter === 'all' || item.getAttribute('data-category') === filter) {
                        item.style.display = 'block';
                    } else {
                        item.style.display = 'none';
                    }
                });
            });
        });

        // Copy to clipboard helper
        function copyToClipboard(text) {
            const textarea = document.createElement('textarea');
            textarea.value = text;
            document.body.appendChild(textarea);
            textarea.select();
            try {
                document.execCommand('copy');
                showToast('Email address copied to clipboard!');
            } catch (err) {
                showToast('Failed to copy text.');
            }
            document.body.removeChild(textarea);
        }

        // Form Submit Handler
        function handleFormSubmit(e) {
            e.preventDefault();
            showToast('Thank you for your message! Michael will get back to you soon.');
            document.getElementById('contact-form').reset();
        }

        // Custom Toast Notification
        function showToast(message) {
            const toast = document.getElementById('toast');
            const toastMsg = document.getElementById('toast-message');
            toastMsg.textContent = message;

            toast.classList.remove('translate-y-20', 'opacity-0');
            toast.classList.add('translate-y-0', 'opacity-100');

            setTimeout(() => {
                toast.classList.add('translate-y-20', 'opacity-0');
                toast.classList.remove('translate-y-0', 'opacity-100');
            }, 3500);
        }
    </script>
</body>
</html>
