<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Strategic Consulting Proposal | Bridgeway ERP Solutions</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/flatpickr/dist/flatpickr.min.css">

    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc; /* slate-50 */
            color: #1e293b; /* slate-800 */
        }
        .nav-link.active {
            color: #2563eb; /* blue-600 */
            font-weight: 600;
        }
        .phase.active {
            border-color: #2563eb; /* blue-600 */
            background-color: #dbeafe; /* blue-100 */
        }
        .phase-content {
            display: none;
        }
        .phase-content.active {
            display: block;
        }
        .challenge-content {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.5s ease-in-out;
        }
        .chart-container {
            position: relative;
            margin: auto;
            height: 40vh;
            max-height: 400px;
            width: 100%;
            max-width: 500px;
        }

        /* Custom style for Flatpickr to make it full width */
        .flatpickr-calendar.inline {
            width: 100%; /* Make the calendar full width of its container */
            max-width: 400px; /* Limit max width for larger screens */
            margin: 0 auto; /* Center the calendar */
            box-shadow: none; /* Remove default shadow if you prefer */
        }
        .flatpickr-calendar {
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06); /* Tailwind shadow-md */
            border: 1px solid #e2e8f0; /* Tailwind border-slate-200 */
            border-radius: 0.5rem; /* Tailwind rounded-lg */
        }
    </style>
</head>
<body class="antialiased">

    <header id="header" class="bg-white/80 backdrop-blur-md sticky top-0 z-50 shadow-sm">
        <nav class="container mx-auto px-6 py-4 flex justify-between items-center">
            <div class="text-2xl font-bold text-slate-900">
                Bridgeway <span class="text-blue-600">ERP Solutions</span>
            </div>
            <div class="hidden md:flex space-x-12"> 
                <a href="#challenge" class="nav-link text-slate-600 hover:text-blue-600 transition-colors">The Challenge</a>
                <a href="#approach" class="nav-link text-slate-600 hover:text-blue-600 transition-colors">Our Approach</a>
                <a href="#plan" class="nav-link text-slate-600 hover:text-blue-600 transition-colors">The Plan</a>
                <a href="#impact" class="nav-link text-slate-600 hover:text-blue-600 transition-colors">The Impact</a>
                <a href="#investment" class="nav-link text-slate-600 hover:text-blue-600 transition-colors">Investment</a>
                </div>
            <a href="#schedule-meeting" class="hidden md:inline-block bg-blue-600 text-white font-semibold px-5 py-2 rounded-lg hover:bg-blue-700 transition-colors">
                Next Steps
            </a>
        </nav>
    </header>

    <main>
        <section id="hero" class="py-20 md:py-32 bg-white">
            <div class="container mx-auto px-6 text-center">
                <p class="text-blue-600 font-semibold mb-2">A STRATEGIC PARTNERSHIP FOR [Client Company Name]</p>
                <h1 class="text-4xl md:text-6xl font-bold text-slate-900 leading-tight mb-4">Transforming Your Technology Investment into Tangible Business Growth</h1>
                <p class="text-lg md:text-xl text-slate-600 max-w-3xl mx-auto">This proposal outlines a focused engagement to optimize your ERP and data ecosystems, delivering actionable insights, enhanced user proficiency, and a maximized return on your technology investment.</p>
            </div>
        </section>

        <section id="challenge" class="py-16 md:py-24">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-bold text-slate-900">Understanding Your Challenge</h2>
                    <p class="text-lg text-slate-600 mt-4 max-w-2xl mx-auto">Many organizations face a disconnect between technology's promise and real-world impact. Click on a challenge below to see how we address these common hurdles.</p>
                </div>
                <div class="max-w-3xl mx-auto space-y-4">
                    <div class="challenge-item bg-white rounded-lg shadow-sm border border-slate-200">
                        <button class="w-full flex justify-between items-center p-5 text-left font-semibold text-lg text-slate-800" aria-expanded="false" aria-controls="challenge-content-1">
                            Complex Implementations
                            <span class="transform transition-transform duration-300">▼</span>
                        </button>
                        <div id="challenge-content-1" class="challenge-content px-5 pb-5">
                            <p class="text-slate-600">We address the difficulty in realizing the full benefits of Microsoft Dynamics ERP by providing expert guidance on configuration, ensuring a setup that aligns perfectly with your business workflows for complete and effective adoption.</p>
                        </div>
                    </div>
                    <div class="challenge-item bg-white rounded-lg shadow-sm border border-slate-200">
                        <button class="w-full flex justify-between items-center p-5 text-left font-semibold text-lg text-slate-800" aria-expanded="false" aria-controls="challenge-content-2">
                            Fragmented Data
                            <span class="transform transition-transform duration-300">▼</span>
                        </button>
                        <div id="challenge-content-2" class="challenge-content px-5 pb-5">
                            <p class="text-slate-600">Our data strategy and governance frameworks turn fragmented data into a strategic asset. We create a single source of truth, enabling clear, actionable insights from disparate data sources to drive informed decision-making.</p>
                        </div>
                    </div>
                    <div class="challenge-item bg-white rounded-lg shadow-sm border border-slate-200">
                        <button class="w-full flex justify-between items-center p-5 text-left font-semibold text-lg text-slate-800" aria-expanded="false" aria-controls="challenge-content-3">
                            Operational Inefficiencies
                            <span class="transform transition-transform duration-300">▼</span>
                        </button>
                        <div id="challenge-content-3" class="challenge-content px-5 pb-5">
                            <p class="text-slate-600">By redesigning suboptimal processes and streamlining workflows, we ensure technology delivers its full potential. Our focus is on eliminating wasted resources and capitalizing on opportunities for enhanced productivity.</p>
                        </div>
                    </div>
                    <div class="challenge-item bg-white rounded-lg shadow-sm border border-slate-200">
                        <button class="w-full flex justify-between items-center p-5 text-left font-semibold text-lg text-slate-800" aria-expanded="false" aria-controls="challenge-content-4">
                            Underutilized Capabilities
                            <span class="transform transition-transform duration-300">▼</span>
                        </button>
                        <div id="challenge-content-4" class="challenge-content px-5 pb-5">
                            <p class="text-slate-600">Our customized user training programs bridge the gap between system capabilities and user proficiency. We empower your team to not just use, but master the ERP system, ensuring it's leveraged to its fullest potential across the organization.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="approach" class="py-16 md:py-24 bg-white">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-bold text-slate-900">Our Differentiated Approach</h2>
                    <p class="text-lg text-slate-600 mt-4 max-w-2xl mx-auto">We believe technology should be a powerful catalyst for your success. Our approach is built on three core pillars.</p>
                </div>
                <div class="grid md:grid-cols-3 gap-8 max-w-6xl mx-auto">
                    <div class="bg-slate-50 p-8 rounded-lg border border-slate-200">
                        <h3 class="text-xl font-bold text-blue-900 mb-2">Precision.</h3>
                        <h4 class="text-lg font-semibold text-slate-800 mb-3">Bespoke, Strategic Solutions</h4>
                        <p class="text-slate-600">We dive deep into your unique business goals to craft highly customized strategies, ensuring your technology precisely aligns with your operational needs and long-term vision.</p>
                    </div>
                    <div class="bg-slate-50 p-8 rounded-lg border border-slate-200">
                        <h3 class="text-xl font-bold text-blue-900 mb-2">Agility.</h3>
                        <h4 class="text-lg font-semibold text-slate-800 mb-3">Direct Senior-Level Engagement</h4>
                        <p class="text-slate-600">You work directly with a seasoned expert from day one. This guarantees swift decision-making, clear communication, and unparalleled flexibility to meet evolving requirements.</p>
                    </div>
                    <div class="bg-slate-50 p-8 rounded-lg border border-slate-200">
                        <h3 class="text-xl font-bold text-blue-900 mb-2">Partnership.</h3>
                        <h4 class="text-lg font-semibold text-slate-800 mb-3">Unwavering Commitment</h4>
                        <p class="text-slate-600">As an independent firm, our reputation is built on your results. We are personally invested in delivering tangible outcomes and fostering a trusted, long-term partnership.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="plan" class="py-16 md:py-24">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-bold text-slate-900">The Proposed Engagement Plan</h2>
                    <p class="text-lg text-slate-600 mt-4 max-w-2xl mx-auto">Our engagement is structured in four key phases to ensure a comprehensive and effective transformation. Click each phase to explore the objectives and activities.</p>
                </div>

                <div class="max-w-5xl mx-auto">
                    <div class="flex flex-col md:flex-row justify-center items-center border-b-2 border-slate-200 mb-8">
                        <button data-phase="1" class="phase active w-full md:w-auto text-center font-semibold p-4 border-b-4 hover:text-blue-600 hover:border-blue-300 transition-colors">Phase 1: Discovery</button>
                        <button data-phase="2" class="phase w-full md:w-auto text-center font-semibold p-4 border-b-4 border-transparent hover:text-blue-600 hover:border-blue-300 transition-colors">Phase 2: Design & Plan</button>
                        <button data-phase="3" class="phase w-full md:w-auto text-center font-semibold p-4 border-b-4 border-transparent hover:text-blue-600 hover:border-blue-300 transition-colors">Phase 3: Implementation</button>
                        <button data-phase="4" class="phase w-full md:w-auto text-center font-semibold p-4 border-b-4 border-transparent hover:text-blue-600 hover:border-blue-300 transition-colors">Phase 4: Optimization</button>
                    </div>

                    <div id="phase-content-container" class="bg-white p-8 rounded-lg shadow-md border border-slate-200">
                        <div id="phase-1-content" class="phase-content active">
                            <h3 class="text-2xl font-bold text-slate-800 mb-1">Phase 1: Discovery & Strategic Alignment</h3>
                            <p class="text-slate-500 mb-4">(Weeks 1-2)</p>
                            <p class="text-lg text-slate-700 font-medium mb-4">Objective: To gain a deep understanding of your current state, key challenges, and strategic objectives related to your ERP and data ecosystem.</p>
                            <ul class="list-disc list-inside space-y-2 text-slate-600">
                                <li>Conduct stakeholder interviews across relevant departments.</li>
                                <li>Perform a thorough system and data assessment of your Microsoft Dynamics ERP.</li>
                                <li>Map current business processes to identify inefficiencies.</li>
                                <li>Facilitate a strategic alignment workshop with leadership.</li>
                            </ul>
                        </div>
                        <div id="phase-2-content" class="phase-content">
                            <h3 class="text-2xl font-bold text-slate-800 mb-1">Phase 2: Solution Design & Planning</h3>
                            <p class="text-slate-500 mb-4">(Weeks 3-6)</p>
                            <p class="text-lg text-slate-700 font-medium mb-4">Objective: To develop a tailored solution design and detailed implementation plan that addresses identified challenges and aligns with strategic goals.</p>
                            <ul class="list-disc list-inside space-y-2 text-slate-600">
                                <li>Design optimized business processes leveraging ERP capabilities.</li>
                                <li>Develop a comprehensive data strategy and governance framework.</li>
                                <li>Outline specific ERP optimization and module integration plans.</li>
                                <li>Develop customized user training programs and a change management strategy.</li>
                            </ul>
                        </div>
                        <div id="phase-3-content" class="phase-content">
                            <h3 class="text-2xl font-bold text-slate-800 mb-1">Phase 3: Implementation & Execution</h3>
                            <p class="text-slate-500 mb-4">(Weeks 7-16)</p>
                            <p class="text-lg text-slate-700 font-medium mb-4">Objective: To implement the designed solutions, refine processes, and empower your team through targeted training and support.</p>
                            <ul class="list-disc list-inside space-y-2 text-slate-600">
                                <li>Assist with the configuration and tuning of Microsoft Dynamics modules.</li>
                                <li>Support the implementation of BI tools and dashboard design.</li>
                                <li>Manage the rollout of new processes and conduct user acceptance testing.</li>
                                <li>Deliver hands-on, customized user training sessions.</li>
                            </ul>
                        </div>
                        <div id="phase-4-content" class="phase-content">
                            <h3 class="text-2xl font-bold text-slate-800 mb-1">Phase 4: Optimization & Sustained Impact</h3>
                            <p class="text-slate-500 mb-4">(Weeks 17-20)</p>
                            <p class="text-lg text-slate-700 font-medium mb-4">Objective: To ensure the long-term sustainability of improvements and provide ongoing support for continuous optimization.</p>
                            <ul class="list-disc list-inside space-y-2 text-slate-600">
                                <li>Establish KPIs and reporting to track the impact of solutions.</li>
                                <li>Ensure comprehensive knowledge transfer and documentation.</li>
                                <li>Provide post-project support and advisory services.</li>
                                <li>Collaborate on a future roadmap for continued growth.</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        <section id="impact" class="py-16 md:py-24 bg-white">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-bold text-slate-900">Visualizing The Impact You Can Expect</h2>
                    <p class="text-lg text-slate-600 mt-4 max-w-2xl mx-auto">Our partnership delivers more than just a technology upgrade; it achieves transformative business outcomes across key areas.</p>
                </div>
                <div class="grid lg:grid-cols-2 gap-12 items-center max-w-6xl mx-auto">
                    <div class="chart-container">
                        <canvas id="impactChart"></canvas>
                    </div>
                    <div class="space-y-4">
                        <div class="flex items-start">
                            <span class="text-blue-500 text-2xl mr-4">✓</span>
                            <div>
                                <h4 class="font-semibold text-lg text-slate-800">Maximized Technology ROI</h4>
                                <p class="text-slate-600">Transform your ERP and data investments into tangible assets that directly contribute to your bottom line.</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <span class="text-blue-500 text-2xl mr-4">✓</span>
                            <div>
                                <h4 class="font-semibold text-lg text-slate-800">Enhanced Operational Efficiency</h4>
                                <p class="text-slate-600">Streamline processes and empower your teams with integrated, effective systems, leading to significant cost savings.</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <span class="text-blue-500 text-2xl mr-4">✓</span>
                            <div>
                                <h4 class="font-semibold text-lg text-slate-800">Strategic Clarity & Agility</h4>
                                <p class="text-slate-600">Gain clear, data-driven insights to make informed decisions and adapt quickly to market changes.</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <span class="text-blue-500 text-2xl mr-4">✓</span>
                            <div>
                                <h4 class="font-semibold text-lg text-slate-800">Boosted User Proficiency</h4>
                                <p class="text-slate-600">Ensure your teams are not just using the ERP system, but mastering it to maximize its value across your organization.</p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="mt-20">
                    <div class="text-center mb-12">
                        <h3 class="text-2xl md:text-3xl font-bold text-slate-900">Key Project Deliverables</h3>
                        <p class="text-lg text-slate-600 mt-4 max-w-2xl mx-auto">Upon completion, you will receive a suite of tangible assets to guide your continued success.</p>
                    </div>
                    <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-6 max-w-6xl mx-auto">
                        <div class="bg-slate-50 p-6 rounded-lg border border-slate-200"><p class="font-semibold text-slate-800">✓ Comprehensive Assessment Report</p></div>
                        <div class="bg-slate-50 p-6 rounded-lg border border-slate-200"><p class="font-semibold text-slate-800">✓ Optimized Business Process Maps</p></div>
                        <div class="bg-slate-50 p-6 rounded-lg border border-slate-200"><p class="font-semibold text-slate-800">✓ ERP Optimization Plan</p></div>
                        <div class="bg-slate-50 p-6 rounded-lg border border-slate-200"><p class="font-semibold text-slate-800">✓ Data Strategy & Governance Document</p></div>
                        <div class="bg-slate-50 p-6 rounded-lg border border-slate-200"><p class="font-semibold text-slate-800">✓ Actionable BI Dashboards/Reports</p></div>
                        <div class="bg-slate-50 p-6 rounded-lg border border-slate-200"><p class="font-semibold text-slate-800">✓ Customized User Training Materials</p></div>
                    </div>
                </div>
            </div>
        </section>

        <section id="investment" class="py-16 md:py-24">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-bold text-slate-900">Investment</h2>
                    <p class="text-lg text-slate-600 mt-4 max-w-2xl mx-auto">Our pricing reflects the senior-level expertise and customized approach we bring to each engagement. We offer the following flexible options.</p>
                </div>
                <div class="grid md:grid-cols-2 gap-8 max-w-4xl mx-auto">
                    <div class="bg-white p-8 rounded-lg shadow-lg border-2 border-blue-600">
                        <h3 class="text-2xl font-bold text-slate-900 mb-4">Option A: Fixed-Fee Engagement</h3>
                        <p class="text-slate-600 mb-6">This option provides a clear, upfront cost for the entire scope of work, offering budget predictability. Ideal for well-defined projects. Our fixed-fee packages include:</p>
                        <ul class="list-disc list-inside space-y-2 text-slate-700 mb-6">
                            <li><strong>Process Documentation Package:</strong> $5,000 – $8,000</li>
                            <li><strong>ERP Process Mapping or Readiness:</strong> $10,000 – $20,000</li>
                        </ul>
                        <p class="text-sm text-slate-500">Payment Terms: [e.g., 25% upon signing, 25% on Phase 2 completion, 25% on Phase 3 completion, 25% upon project close-out].</p>
                    </div>
                    <div class="bg-white p-8 rounded-lg shadow-lg border-2 border-blue-600">
                        <h3 class="text-2xl font-bold text-slate-900 mb-4">Option B: Phased Retainer / T&M</h3>
                        <p class="text-slate-600 mb-6">This model offers greater flexibility, allowing the scope to evolve. Ideal for engagements where requirements may be refined over time.</p>
                        <div class="text-4xl font-bold text-slate-900 mb-6">$95 – $110 <span class="text-xl font-medium text-slate-500">per hour</span></div>
                         <p class="text-sm text-slate-500">Estimated Range: Determined by project scope and duration. Billed monthly.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="schedule-meeting" class="py-16 md:py-24 bg-blue-900 text-white">
            <div class="container mx-auto px-6 text-center">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">Ready to Schedule Our Discussion?</h2>
                <p class="text-lg text-blue-200 max-w-2xl mx-auto mb-8">Please select your preferred date and time from the calendar below. We look forward to connecting with you!</p>
                
                <p class="text-blue-100 text-sm mb-4 max-w-lg mx-auto">Use the arrows next to the month name to navigate through the next 12+ months and select your ideal time.</p>

                <div id="calendar-container" class="bg-white p-6 rounded-lg shadow-lg max-w-lg mx-auto">
                    <input type="text" id="meeting-calendar" class="hidden"> 
                </div>

                <p id="selected-datetime" class="mt-6 text-xl text-blue-100 font-semibold"></p>
                <button id="confirm-meeting-btn" class="mt-8 bg-blue-600 text-white font-bold px-8 py-4 rounded-lg hover:bg-blue-700 transition-transform hover:scale-105 opacity-50 cursor-not-allowed" disabled>
                    Confirm Selected Time
                </button>

                <div id="meeting-confirmation" class="hidden mt-8 p-6 bg-green-500 rounded-lg shadow-md max-w-md mx-auto text-white">
                    <h3 class="text-2xl font-bold mb-2">Appointment Scheduled!</h3>
                    <p class="text-lg mb-4">Your meeting has been tentatively scheduled for:</p>
                    <p id="confirmed-datetime-display" class="text-xl font-semibold mb-4"></p>
                    <p class="text-sm">A confirmation email with details will be sent shortly. We look forward to speaking with you!</p>
                    <button id="dismiss-confirmation-btn" class="mt-4 bg-green-700 text-white px-6 py-2 rounded-lg hover:bg-green-800 transition-colors">
                        Dismiss
                    </button>
                </div>

            </div>
        </section>
    </main>

    <footer class="bg-slate-800 text-slate-400 py-6">
        <div class="container mx-auto px-6 text-center">
            <p>&copy; 2025 Bridgeway ERP Solutions. All Rights Reserved.</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/flatpickr"></script>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            // Challenge Accordion
            const challengeItems = document.querySelectorAll('.challenge-item button');
            challengeItems.forEach(button => {
                button.addEventListener('click', () => {
                    const content = button.nextElementSibling;
                    const arrow = button.querySelector('span');
                    const isExpanded = button.getAttribute('aria-expanded') === 'true';

                    // Close all other accordions
                    document.querySelectorAll('.challenge-item button').forEach(otherButton => {
                        if (otherButton !== button) {
                            otherButton.setAttribute('aria-expanded', 'false');
                            otherButton.nextElementSibling.style.maxHeight = null;
                            otherButton.querySelector('span').style.transform = 'rotate(0deg)';
                        }
                    });

                    // Toggle current accordion
                    if (isExpanded) {
                        content.style.maxHeight = null;
                        arrow.style.transform = 'rotate(0deg)';
                        button.setAttribute('aria-expanded', 'false');
                    } else {
                        // Use requestAnimationFrame for smoother transition
                        requestAnimationFrame(() => {
                            content.style.maxHeight = content.scrollHeight + "px";
                            arrow.style.transform = 'rotate(180deg)';
                            button.setAttribute('aria-expanded', 'true');
                        });
                    }
                });
            });

            // Phase Navigation
            const phaseButtons = document.querySelectorAll('.phase');
            const phaseContents = document.querySelectorAll('.phase-content');
            
            let currentActivePhaseButton = document.querySelector('.phase.active');
            let currentActivePhaseContent = document.querySelector('.phase-content.active');

            phaseButtons.forEach(button => {
                button.addEventListener('click', () => {
                    const phaseNum = button.dataset.phase;
                    const targetContent = document.getElementById(`phase-${phaseNum}-content`);

                    // Remove active from previous button and content
                    if (currentActivePhaseButton) {
                        currentActivePhaseButton.classList.remove('active');
                    }
                    if (currentActivePhaseContent) {
                        currentActivePhaseContent.classList.remove('active');
                    }

                    // Add active to new button and content
                    button.classList.add('active');
                    targetContent.classList.add('active');

                    // Update current active references
                    currentActivePhaseButton = button;
                    currentActivePhaseContent = targetContent;
                });
            });

            // Nav link active state on scroll
            const sections = document.querySelectorAll('section');
            const navLinks = document.querySelectorAll('.nav-link');

            const observerOptions = {
                rootMargin: "-50% 0px -50% 0px" // Adjusted to trigger when section is roughly in the middle
            };

            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        // Remove active from all nav links
                        navLinks.forEach(link => {
                            link.classList.remove('active');
                            link.removeAttribute('aria-current'); // Remove aria-current
                        });
                        // Add active to the current section's nav link
                        const currentNavLink = document.querySelector(`.nav-link[href="#${entry.target.id}"]`);
                        if (currentNavLink) {
                            currentNavLink.classList.add('active');
                            currentNavLink.setAttribute('aria-current', 'page'); // Add aria-current
                        }
                    }
                });
            }, observerOptions);

            sections.forEach(section => {
                observer.observe(section);
            });

            // Chart.js Radar Chart
            const ctx = document.getElementById('impactChart');
            if(ctx) { // Check if canvas element exists before initializing chart
                new Chart(ctx, {
                    type: 'radar',
                    data: {
                        labels: [
                            'Technology ROI',
                            'Operational Efficiency',
                            'User Proficiency',
                            'Strategic Clarity',
                            'Business Agility'
                        ],
                        datasets: [{
                            label: 'Impact of Partnership',
                            data: [90, 85, 95, 80, 88],
                            fill: true,
                            backgroundColor: 'rgba(37, 99, 235, 0.2)', // blue-600 with opacity
                            borderColor: 'rgb(37, 99, 235)', // blue-600
                            pointBackgroundColor: 'rgb(37, 99, 235)',
                            pointBorderColor: '#fff',
                            pointHoverBackgroundColor: '#fff',
                            pointHoverBorderColor: 'rgb(37, 99, 235)'
                        }] // This was the missing closing bracket for datasets
                    }, // This was the missing closing bracket for data
                    options: {
                        responsive: true,
                        maintainAspectRatio: false,
                        elements: {
                            line: {
                                borderWidth: 3
                            }
                        },
                        scales: {
                            r: {
                                angleLines: {
                                    color: 'rgba(100, 116, 139, 0.3)' // slate-400 with opacity
                                },
                                grid: {
                                    color: 'rgba(100, 116, 139, 0.3)' // slate-400 with opacity
                                },
                                pointLabels: {
                                    color: '#1e293b', // slate-800
                                    font: {
                                        size: 14,
                                        weight: 'bold'
                                    }
                                },
                                ticks: {
                                    display: false, // Hide the ticks values
                                    beginAtZero: true,
                                    max: 100 // Set maximum value for the scale
                                }
                            }
                        },
                        plugins: {
                            legend: {
                                display: true,
                                position: 'top',
                                labels: {
                                    color: '#1e293b' // slate-800
                                }
                            }
                        }
                    }
                });
            }

            // Flatpickr Calendar for meeting scheduling
            const meetingCalendarInput = document.getElementById('meeting-calendar');
            const selectedDatetimeDisplay = document.getElementById('selected-datetime');
            const confirmMeetingBtn = document.getElementById('confirm-meeting-btn');
            const meetingConfirmationDiv = document.getElementById('meeting-confirmation');
            const confirmedDatetimeDisplay = document.getElementById('confirmed-datetime-display');
            const dismissConfirmationBtn = document.getElementById('dismiss-confirmation-btn');

            let selectedDateTime = null; // To store the selected date and time

            const fp = flatpickr(meetingCalendarInput, {
                inline: true, // Display the calendar inline
                minDate: "today",
                enableTime: true,
                dateFormat: "Y-m-d H:i",
                altInput: true,
                altFormat: "F j, Y h:i K", // e.g., "July 8, 2025 10:30 AM"
                minuteIncrement: 30,
                // Disable dates in the past (already handled by minDate: "today")
                // You can add more complex disable logic here if needed, e.g., for weekends or holidays
                onChange: function(selectedDates, dateStr, instance) {
                    if (selectedDates.length > 0) {
                        selectedDateTime = selectedDates[0];
                        selectedDatetimeDisplay.textContent = `You selected: ${dateStr}`;
                        confirmMeetingBtn.disabled = false;
                        confirmMeetingBtn.classList.remove('opacity-50', 'cursor-not-allowed');
                        confirmMeetingBtn.classList.add('hover:bg-blue-700', 'hover:scale-105');
                    } else {
                        selectedDatetimeDisplay.textContent = '';
                        confirmMeetingBtn.disabled = true;
                        confirmMeetingBtn.classList.add('opacity-50', 'cursor-not-allowed');
                        confirmMeetingBtn.classList.remove('hover:bg-blue-700', 'hover:scale-105');
                    }
                },
                onOpen: function(selectedDates, dateStr, instance) {
                    // This is optional, but helps ensure the calendar is fully visible in its container
                    // if it was initially hidden or its container dynamically resized.
                    instance.calendarContainer.style.maxWidth = '100%';
                }
            });

            confirmMeetingBtn.addEventListener('click', () => {
                if (selectedDateTime) {
                    confirmedDatetimeDisplay.textContent = fp.altInput.value; // Use the formatted date string
                    meetingConfirmationDiv.classList.remove('hidden');
                    // Optionally hide the calendar and main button after confirmation
                    meetingCalendarInput.closest('#calendar-container').classList.add('hidden');
                    confirmMeetingBtn.classList.add('hidden');
                    selectedDatetimeDisplay.classList.add('hidden');
                }
            });

            dismissConfirmationBtn.addEventListener('click', () => {
                meetingConfirmationDiv.classList.add('hidden');
                // Reset to show calendar and button again for a new selection
                meetingCalendarInput.closest('#calendar-container').classList.remove('hidden');
                confirmMeetingBtn.classList.remove('hidden', 'opacity-50', 'cursor-not-allowed');
                confirmMeetingBtn.disabled = true; // Disable until a new date is selected
                selectedDatetimeDisplay.classList.remove('hidden');
                selectedDatetimeDisplay.textContent = '';
                // Clear selected date in flatpickr instance
                fp.clear();
            });

            // Smooth scrolling for navigation links
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function (e) {
                    e.preventDefault();
                    document.querySelector(this.getAttribute('href')).scrollIntoView({
                        behavior: 'smooth'
                    });
                });
            });
        });
    </script>
</body>
</html>
