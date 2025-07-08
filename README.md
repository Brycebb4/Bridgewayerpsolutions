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
            <div class="hidden md:flex items-center">
                <div class="flex space-x-12 mr-8"> 
                    <a href="#challenge" class="nav-link text-slate-600 hover:text-blue-600 transition-colors">The Challenge</a>
                    <a href="#approach" class="nav-link text-slate-600 hover:text-blue-600 transition-colors">Our Approach</a>
                    <a href="#plan" class="nav-link text-slate-600 hover:text-blue-600 transition-colors">The Plan</a>
                    <a href="#impact" class="nav-link text-slate-600 hover:text-blue-600 transition-colors">The Impact</a>
                    <a href="#investment" class="nav-link text-slate-600 hover:text-blue-600 transition-colors">Investment</a>
                </div>
                <a href="#schedule-meeting" class="hidden md:inline-block bg-blue-600 text-white font-semibold px-5 py-2 rounded-lg hover:bg-blue-700 transition-colors">
                    Next Steps
                </a>
            </div>
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
                <p class="text-lg text-blue-200 max-w-2xl mx-auto mb-8">Please provide your details and select a preferred date and time from the calendar below. We look forward to connecting with you!</p>
                
                <form id="user-details-form" class="max-w-lg mx-auto space-y-4 mb-8 text-left">
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                        <div>
                            <label for="first-name" class="block text-sm font-medium text-blue-200">First Name</label>
                            <input type="text" id="first-name" name="first-name" required class="mt-1 block w-full bg-blue-800 border-blue-600 rounded-md shadow-sm py-2 px-3 text-white focus:outline-none focus:ring-blue-500 focus:border-blue-500">
                        </div>
                        <div>
                            <label for="last-name" class="block text-sm font-medium text-blue-200">Last Name</label>
                            <input type="text" id="last-name" name="last-name" required class="mt-1 block w-full bg-blue-800 border-blue-600 rounded-md shadow-sm py-2 px-3 text-white focus:outline-none focus:ring-blue-500 focus:border-blue-500">
                        </div>
                    </div>
                    <div>
                        <label for="email" class="block text-sm font-medium text-blue-200">Email Address</label>
                        <input type="email" id="email" name="email" required class="mt-1 block w-full bg-blue-800 border-blue-600 rounded-md shadow-sm py-2 px-3 text-white focus:outline-none focus:ring-blue-500 focus:border-blue-500">
                    </div>
                    <div>
                        <label for="company" class="block text-sm font-medium text-blue-200">Organization / Company Name</label>
                        <input type="text" id="company" name="company" required class="mt-1 block w-full bg-blue-800 border-blue-600 rounded-md shadow-sm py-2 px-3 text-white focus:outline-none focus:ring-blue-500 focus:border-blue-500">
                    </div>
                </form>

                <p class="text-blue-100 text-sm mb-4 max-w-lg mx-auto">Use the arrows next to the month name to navigate through the next 12+ months and select your ideal time.</p>

                <div id="calendar-container" class="bg-white p-6 rounded-lg shadow-lg max-w-lg mx-auto">
                    <input type="text" id="meeting-calendar" class="hidden"> 
                </div>

                <p id="selected-datetime" class="mt-6 text-xl text-blue-100 font-semibold"></p>
                <button id="confirm-meeting-btn" class="mt-8 bg-blue-600 text-white font-bold px-8 py-4 rounded-lg opacity-50 cursor-not-allowed" disabled>
                    Confirm Selected Time
                </button>

                <div id="meeting-confirmation" class="hidden mt-8 p-6 bg-green-500 rounded-lg shadow-md max-w-md mx-auto text-white">
                    <h3 class="text-2xl font-bold mb-2">Appointment Scheduled!</h3>
                    <p class="text-lg mb-4">Your meeting has been tentatively scheduled. A confirmation email with details will be sent shortly to the provided address.</p>
                    <p id="confirmed-datetime-display" class="text-xl font-semibold mb-4"></p>
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

                    document.querySelectorAll('.challenge-item button').forEach(otherButton => {
                        if (otherButton !== button) {
                            otherButton.setAttribute('aria-expanded', 'false');
                            otherButton.nextElementSibling.style.maxHeight = null;
                            otherButton.querySelector('span').style.transform = 'rotate(0deg)';
                        }
                    });

                    if (isExpanded) {
                        content.style.maxHeight = null;
                        arrow.style.transform = 'rotate(0deg)';
                        button.setAttribute('aria-expanded', 'false');
                    } else {
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
            phaseButtons.forEach(button => {
                button.addEventListener('click', () => {
                    const phaseNum = button.dataset.phase;
                    const targetContent = document.getElementById(`phase-${phaseNum}-content`);
                    document.querySelector('.phase.active').classList.remove('active');
                    document.querySelector('.phase-content.active').classList.remove('active');
                    button.classList.add('active');
                    targetContent.classList.add('active');
                });
            });

            // Nav link active state on scroll
            const sections = document.querySelectorAll('section');
            const navLinks = document.querySelectorAll('.nav-link');
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        navLinks.forEach(link => {
                            link.classList.remove('active');
                            link.removeAttribute('aria-current');
                        });
                        const currentNavLink = document.querySelector(`.nav-link[href="#${entry.target.id}"]`);
                        if (currentNavLink) {
                            currentNavLink.classList.add('active');
                            currentNavLink.setAttribute('aria-current', 'page');
                        }
                    }
                });
            }, { rootMargin: "-50% 0px -50% 0px" });
            sections.forEach(section => observer.observe(section));

            // Chart.js Radar Chart
            const ctx = document.getElementById('impactChart');
            if(ctx) {
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
                            data: [98, 95, 100, 92, 96], // Increased values to extend points
                            fill: true,
                            backgroundColor: 'rgba(37, 99, 235, 0.2)',
                            borderColor: 'rgb(37, 99, 235)',
                            pointBackgroundColor: 'rgb(37, 99, 235)',
                            pointBorderColor: '#fff',
                            pointHoverBackgroundColor: '#fff',
                            pointHoverBorderColor: 'rgb(37, 99, 235)'
                        }]
                    },
                    options: {
                        layout: {
                            padding: 15 // Adds padding to prevent labels from being cut off
                        },
                        scales: {
                            r: {
                                beginAtZero: true,
                                max: 100,
                                angleLines: { color: 'rgba(0, 0, 0, 0.1)' },
                                grid: { color: 'rgba(0, 0, 0, 0.1)' },
                                pointLabels: {
                                    font: { size: 14 },
                                    color: '#1e293b'
                                },
                                ticks: {
                                    backdropColor: 'rgba(255, 255, 255, 0)',
                                    stepSize: 25
                                }
                            }
                        },
                        plugins: { legend: { display: false } }
                    }
                });
            }

            // --- Meeting Scheduler Logic ---
            const confirmBtn = document.getElementById('confirm-meeting-btn');
            const userForm = document.getElementById('user-details-form');
            const formInputs = userForm.querySelectorAll('input');
            const selectedDatetimeDisplay = document.getElementById('selected-datetime');
            const confirmationDiv = document.getElementById('meeting-confirmation');
            const confirmedDatetimeDisplay = document.getElementById('confirmed-datetime-display');
            const dismissBtn = document.getElementById('dismiss-confirmation-btn');
            let flatpickrInstance;

            function validateAndEnableButton() {
                const isDateSelected = flatpickrInstance && flatpickrInstance.selectedDates.length > 0;
                const isFormValid = Array.from(formInputs).every(input => input.value.trim() !== '');

                if (isDateSelected && isFormValid) {
                    confirmBtn.disabled = false;
                    confirmBtn.classList.remove('opacity-50', 'cursor-not-allowed');
                    confirmBtn.classList.add('hover:bg-blue-700', 'transition-colors', 'hover:scale-105');
                } else {
                    confirmBtn.disabled = true;
                    confirmBtn.classList.add('opacity-50', 'cursor-not-allowed');
                    confirmBtn.classList.remove('hover:bg-blue-700', 'transition-colors', 'hover:scale-105');
                }
            }

            flatpickrInstance = flatpickr("#meeting-calendar", {
                inline: true,
                enableTime: true,
                minDate: "today",
                dateFormat: "F j, Y at h:i K",
                onChange: function(selectedDates, dateStr, instance) {
                    if (selectedDates.length > 0) {
                        selectedDatetimeDisplay.textContent = `Selected: ${dateStr}`;
                    } else {
                        selectedDatetimeDisplay.textContent = '';
                    }
                    validateAndEnableButton();
                }
            });

            formInputs.forEach(input => input.addEventListener('input', validateAndEnableButton));

            confirmBtn.addEventListener('click', () => {
                const selectedDate = flatpickrInstance.selectedDates[0];
                if (!selectedDate || !Array.from(formInputs).every(input => input.value.trim() !== '')) return;

                const formData = new FormData(userForm);
                const firstName = formData.get('first-name');
                const email = formData.get('email');
                const selectedDateFormatted = flatpickr.formatDate(selectedDate, "F j, Y at h:i K");

                // --- BACKEND INTEGRATION REQUIRED ---
                // In a real application, you would now take the form data and the selected date
                // and send it to your backend server via an API call (e.g., using fetch()).
                // The server would then handle validating the data and sending the confirmation email.
                //
                // Example of what the server-side call might look like:
                //
                // const payload = {
                //     firstName: firstName,
                //     lastName: formData.get('last-name'),
                //     email: email,
                //     company: formData.get('company'),
                //     meetingTime: selectedDate.toISOString()
                // };
                //
                // fetch('/api/schedule-meeting', { 
                //     method: 'POST',
                //     headers: { 'Content-Type': 'application/json' },
                //     body: JSON.stringify(payload) 
                // })
                // .then(response => response.json())
                // .then(data => {
                //     // Handle success from server
                //     console.log('Meeting scheduled:', data);
                // })
                // .catch(error => {
                //     // Handle error from server
                //     console.error('Scheduling failed:', error);
                // });
                //
                // For this frontend-only demo, we will just simulate success by showing the confirmation message.
                // --- END OF NOTE ---

                confirmedDatetimeDisplay.textContent = `Time: ${selectedDateFormatted}`;
                confirmationDiv.classList.remove('hidden');
                confirmBtn.classList.add('hidden');
                selectedDatetimeDisplay.classList.add('hidden');
            });

            dismissBtn.addEventListener('click', () => {
                confirmationDiv.classList.add('hidden');
                confirmBtn.classList.remove('hidden');
                selectedDatetimeDisplay.classList.remove('hidden');
                userForm.reset();
                flatpickrInstance.clear();
                validateAndEnableButton();
            });
        });
    </script>

</body>
</html>
