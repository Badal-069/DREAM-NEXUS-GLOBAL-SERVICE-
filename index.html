<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dream Nexus Super App - Admin Console</title>
    <!-- Tailwind CSS for modern mobile styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
    <style>
        /* Mobile-first, Dark Theme Styling */
        body { font-family: 'Inter', sans-serif; background-color: #0c0f1a; }
        .super-app-container {
            /* Waxaa loo sameeyay inuu u ekaado mobile phone (max-width) */
            max-width: 420px;
            margin: 0 auto;
            min-height: 100vh;
            background-color: #1a1e28;
            box-shadow: 0 0 25px rgba(0, 0, 0, 0.4);
            padding: 16px;
            color: #e5e7eb;
        }
        .header-bg {
            background-color: #1a1e28;
            border-bottom: 1px solid #2d3340;
            padding-bottom: 16px;
            /* Si uu u dul fadhiyo marka la scrolling-gareeyo */
            position: sticky; 
            top: 0;
            z-index: 10;
        }
        .wallet-card {
            background-color: #2d3340;
            padding: 10px 15px;
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            color: #f9f9f9;
            flex-grow: 1; 
        }
        .service-icon-card {
            background-color: #2d3340;
            height: 90px;
            border-radius: 10px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 8px 4px;
            transition: transform 0.2s, background-color 0.2s;
            cursor: pointer;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
        }
        .service-icon-card:hover {
            transform: scale(1.05);
            background-color: #3b4354;
        }
        .service-label {
            font-size: 0.6rem;
            line-height: 1.1;
            margin-top: 5px;
            color: #cccccc;
            font-weight: 500;
        }
        /* Custom Modal Styling - Daaqadda Fariinta */
        .custom-modal {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.9);
            display: none;
            align-items: center;
            justify-content: center;
            z-index: 1000;
        }
        .modal-content {
            background: #2d3340;
            padding: 25px;
            border-radius: 15px;
            width: 90%;
            max-width: 350px;
            text-align: center;
            box-shadow: 0 0 50px rgba(0, 0, 0, 0.7);
            animation: fadeIn 0.3s;
            color: #e5e7eb;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: scale(0.9); }
            to { opacity: 1; transform: scale(1); }
        }
        .nexus-star { color: #facc15; } /* Yellow star */
        .ai-console-header {
             color: #93c5fd; /* light blue */
             margin-top: 30px;
             border-left: 4px solid #3b82f6;
             padding-left: 8px;
        }
        .ai-button-action {
            background-color: #3b82f6;
            color: white;
            padding: 10px;
            border-radius: 8px;
            font-weight: 700;
            transition: background-color 0.2s;
            width: 100%;
            margin-bottom: 10px;
        }
        .ai-button-action:hover {
            background-color: #2563eb;
        }
        .emergency-button {
            background-color: #ef4444; /* red */
            color: white;
            padding: 10px;
            border-radius: 8px;
            font-weight: 700;
            transition: background-color 0.2s;
            width: 100%;
            margin-top: 15px;
        }
        .emergency-button:hover {
            background-color: #dc2626;
        }
        /* New styling for Referral Box */
        .referral-box {
            background-color: #2d3340;
            padding: 15px;
            border-radius: 10px;
            border: 2px solid #5a647d;
        }
        /* Styling for the metrics cards */
        .metric-card {
            padding: 12px;
            border-radius: 8px;
            border: 1px solid #3b4354;
        }
    </style>
</head>
<body>

    <!-- Custom Modal Structure for displaying system messages and simulated notifications -->
    <div id="statusModal" class="custom-modal">
        <div class="modal-content">
            <h3 id="modalTitle" class="text-xl font-extrabold mb-3 text-yellow-400">Cusboonaysiinta Xaaladda</h3>
            <p id="modalMessage" class="text-gray-300 mb-5 whitespace-pre-line"></p>
            <button onclick="closeModal()" class="px-5 py-2 bg-indigo-600 text-white font-bold rounded-lg hover:bg-indigo-700 transition duration-150">Xir</button>
        </div>
    </div>

    <div class="super-app-container">
        
        <!-- Header: App Logo, Wallet, Rewards, Profile -->
        <div class="header-bg mb-6">
            <div class="flex justify-between items-center mb-4">
                <div class="flex items-center">
                    <span class="text-2xl nexus-star">★</span>
                    <h1 class="text-2xl font-extrabold text-white ml-2">NEXUS</h1>
                </div>
                <!-- Search Button -->
                <button class="text-white text-xl p-2 rounded-full hover:bg-gray-700">🔍</button>
                <div class="flex space-x-3 w-3/5"> 
                    <div class="wallet-card">
                        <span class="mr-2 font-bold text-sm">Wallet</span>
                        <span class="text-green-400 font-bold text-sm">$5,000</span>
                    </div>
                    <div class="wallet-card">
                        <span class="mr-2 font-bold text-sm">Rewards</span>
                        <span class="text-yellow-400 font-bold text-sm" id="rewardsBalance">0 🎁</span>
                    </div>
                    <button class="w-10 h-10 bg-indigo-500 rounded-full flex items-center justify-center text-white text-lg flex-shrink-0">👤</button>
                </div>
            </div>
            
            <!-- AI and Latency Metrics Console (Simulated Live Data) -->
            <h2 class="text-lg font-bold ai-console-header">Maamulka AI & Xaaladda Nidaamka</h2>
            <div class="grid grid-cols-2 gap-3 mt-3">
                <!-- AI Requests -->
                <div class="metric-card">
                    <p class="text-2xl font-extrabold text-green-400" id="aiRequests">1,245K</p>
                    <p class="text-xs font-semibold text-gray-400 mt-1">AI Support Codsi/min</p>
                </div>
                <!-- Global Latency -->
                <div class="metric-card">
                    <p class="text-2xl font-extrabold text-red-400" id="globalLatency">48ms</p>
                    <p class="text-xs font-semibold text-gray-400 mt-1">Global Latency (Avg)</p>
                </div>
            </div>
        </div>

        <!-- Referral System Box -->
        <div class="referral-box mt-5 mb-8">
            <h3 class="text-lg font-bold text-yellow-400 mb-2 flex items-center">
                <span class="text-2xl mr-2">🔗</span> Nidaamka Xiriirinta (Referral)
            </h3>
            <p class="text-sm text-gray-300 mb-3">Share garee 3 qof oo ay App-ka soo dejiyaan si aad u hesho hal Adeeg oo Bilaash ah (Free Service).</p>
            
            <!-- Referral Status -->
            <div class="flex justify-between items-center bg-gray-700 p-3 rounded-lg mb-3">
                <span class="text-base font-semibold text-gray-200">Xaqiijinta Qofka:</span>
                <span class="text-lg font-extrabold text-green-400" id="referralStatus">0 / 3</span>
            </div>
            
            <!-- Action Buttons for Referral -->
            <div class="grid grid-cols-2 gap-3">
                 <button onclick="handleShareApp()" class="ai-button-action bg-indigo-600 hover:bg-indigo-700 text-xs py-2">
                    <span class="mr-1">📤</span> Share App-ka
                </button>
                <button onclick="handleCheckRewardEligibility()" class="ai-button-action bg-yellow-600 hover:bg-yellow-700 text-xs py-2">
                    <span class="mr-1">🎁</span> Weydii Abaalmarinta AI
                </button>
            </div>
        </div>


        <!-- AI Action Buttons: Management, Security, Support -->
        <h2 class="text-lg font-bold ai-console-header mb-3">Tallaabooyinka AI</h2>
        <div class="grid grid-cols-3 gap-3 mb-4">
            <button onclick="handleAiManagerCommand()" class="ai-button-action col-span-1 bg-blue-600 hover:bg-blue-700 text-xs">
                Dir Amarka AI Manager
            </button>
            <button onclick="handleSecurityCheck()" class="ai-button-action col-span-1 bg-yellow-600 hover:bg-yellow-700 text-xs">
                Hubinta Amniga AI
            </button>
            <button onclick="handleAiSupportQuery()" class="ai-button-action col-span-1 bg-green-600 hover:bg-green-700 text-xs">
                Weydii AI Support
            </button>
        </div>
        
        <!-- Push Notification Simulation Button (Mobile Native Feature) -->
        <button onclick="sendPushNotification('Urgent Security Alert')" class="emergency-button mb-8">
            <span class="text-lg mr-2">🚨</span> Dir Digniinta Amniga Degdegga ah
        </button>


        <!-- 30 Microservices Grid -->
        <h2 class="text-lg font-bold ai-console-header mb-5">30-ka Adeeg ee Caalamiga ah</h2>
        <div class="grid grid-cols-4 gap-3 mb-10">
            <!-- Service Grid (All 30 services) -->
            
            <div onclick="handleService('Global Flight Booking')" class="service-icon-card"><span class="text-2xl">✈️</span><span class="service-label">Global Flight...</span></div>
            <div onclick="handleService('Hotel Reservation')" class="service-icon-card"><span class="text-2xl">🏨</span><span class="service-label">Hotel Reserv...</span></div>
            <div onclick="handleService('Local Food Delivery')" class="service-icon-card"><span class="text-2xl">🍔</span><span class="service-label">Local Food...</span></div>
            <div onclick="handleService('Digital Wallet')" class="service-icon-card"><span class="text-2xl">💳</span><span class="service-label">Digital Wallet</span></div>

            <div onclick="handleService('Professional Networking')" class="service-icon-card"><span class="text-2xl">🔗</span><span class="service-label">Professional...</span></div>
            <div onclick="handleService('Logistics & Delivery')" class="service-icon-card"><span class="text-2xl">📦</span><span class="service-label">Logistics &...</span></div>
            <div onclick="handleService('AI Automation Tools')" class="service-icon-card"><span class="text-2xl">🤖</span><span class="service-label">AI Automati...</span></div>
            <div onclick="handleService('Nexus Compliance Manager')" class="service-icon-card"><span class="text-2xl">📊</span><span class="service-label">Nexus Manag...</span></div>

            <div onclick="handleService('Instant Ride-Hailing')" class="service-icon-card"><span class="text-2xl">🚗</span><span class="service-label">Instant Ride...</span></div>
            <div onclick="handleService('E-Commerce Marketplace')" class="service-icon-card"><span class="text-2xl">🛒</span><span class="service-label">E-Commerce...</span></div>
            <div onclick="handleService('Telehealth Consultation')" class="service-icon-card"><span class="text-2xl">🩺</span><span class="service-label">Telehealth C...</span></div>
            <div onclick="handleService('Online Course/Ed-Tech')" class="service-icon-card"><span class="text-2xl">🎓</span><span class="service-label">Online Cours...</span></div>

            <div onclick="handleService('Event Ticketing')" class="service-icon-card"><span class="text-2xl">🎟️</span><span class="service-label">Event Ticketi...</span></div>
            <div onclick="handleService('Home Repair Services')" class="service-icon-card"><span class="text-2xl">🔨</span><span class="service-label">Home Repai...</span></div>
            <div onclick="handleService('Crypto Trading')" class="service-icon-card"><span class="text-2xl">📈</span><span class="service-label">Crypto Tradi...</span></div>
            <div onclick="handleService('Personal Banking/Finance')" class="service-icon-card"><span class="text-2xl">🏦</span><span class="service-label">Personal Ban...</span></div>
            
            <div onclick="handleService('Mobile Top-Up')" class="service-icon-card"><span class="text-2xl">📱</span><span class="service-label">Mobile Top-Up...</span></div>
            <div onclick="handleService('Premium News Access')" class="service-icon-card"><span class="text-2xl">📰</span><span class="service-label">Premium Ne...</span></div>
            <div onclick="handleService('Real Estate Listings')" class="service-icon-card"><span class="text-2xl">🏠</span><span class="service-label">Real Estate ...</span></div>
            <div onclick="handleService('Car Rental Services')" class="service-icon-card"><span class="text-2xl">🏎️</span><span class="service-label">Car Rental S...</span></div>

            <div onclick="handleService('Streaming/Media Access')" class="service-icon-card"><span class="text-2xl">🎬</span><span class="service-label">Streaming A...</span></div>
            <div onclick="handleService('Cloud Gaming Service')" class="service-icon-card"><span class="text-2xl">🎮</span><span class="service-label">Cloud Gaming</span></div>
            <div onclick="handleService('Digital Library/Books')" class="service-icon-card"><span class="text-2xl">📚</span><span class="service-label">Digital Librar...</span></div>
            <div onclick="handleService('Utility Bill Payments')" class="service-icon-card"><span class="text-2xl">💡</span><span class="service-label">Utility Bill Pa...</span></div>
            
            <div onclick="handleService('Legal Consultation')" class="service-icon-card"><span class="text-2xl">👩‍⚖️</span><span class="service-label">Legal Consu...</span></div>
            <div onclick="handleService('Digital Art Creation')" class="service-icon-card"><span class="text-2xl">🖼️</span><span class="service-label">Digital Art Cr...</span></div>
            <div onclick="handleService('Multi-Language Translation')" class="service-icon-card"><span class="text-2xl">🌍</span><span class="service-label">Multi-Langu...</span></div>
            <div onclick="handleService('Budgeting & Expense Tracking')" class="service-icon-card"><span class="text-2xl">💰</span><span class="service-label">Budgeting &...</span></div>

            <div onclick="handleService('Wellness & Fitness Tracking')" class="service-icon-card"><span class="text-2xl">🧘</span><span class="service-label">Wellness &...</span></div>
            <div onclick="handleService('Pet Care Booking')" class="service-icon-card"><span class="text-2xl">🐶</span><span class="service-label">Pet Care Bo...</span></div>
            <div class="service-icon-card opacity-0 pointer-events-none"></div> <!-- Placeholder -->
            <div class="service-icon-card opacity-0 pointer-events-none"></div> <!-- Placeholder -->

            <!-- Bottom Navigation placeholder -->
            <div class="col-span-4 mt-4 h-12 bg-gray-800 rounded-lg flex justify-around items-center text-2xl">
                <span class="text-blue-400">🎛️</span>
                <span class="text-gray-500">🧭</span>
                <span class="text-gray-500">$</span>
                <span class="text-gray-500">🕒</span>
                <span class="text-gray-500">🔔</span>
            </div>
        </div>

    </div>

    <script>
        // DOM Elements
        const aiRequestsElement = document.getElementById('aiRequests');
        const globalLatencyElement = document.getElementById('globalLatency');
        const rewardsBalanceElement = document.getElementById('rewardsBalance');
        const referralStatusElement = document.getElementById('referralStatus');
        const modal = document.getElementById('statusModal');
        const modalTitle = document.getElementById('modalTitle');
        const modalMessage = document.getElementById('modalMessage');
        
        // Initial simulated data
        let currentAiRequests = 1245678;
        let currentLatency = 48;
        
        // State for Referral System
        let completedReferrals = 0;
        let freeServiceReward = null; // Holds the name of the granted free service

        // List of all 30 Services (for selection)
        const allServices = [
            'Global Flight Booking', 'Hotel Reservation', 'Local Food Delivery', 'Digital Wallet', 
            'Professional Networking', 'Logistics & Delivery', 'AI Automation Tools', 'Nexus Compliance Manager',
            'Instant Ride-Hailing', 'E-Commerce Marketplace', 'Telehealth Consultation', 'Online Course/Ed-Tech',
            'Event Ticketing', 'Home Repair Services', 'Crypto Trading', 'Personal Banking/Finance',
            'Mobile Top-Up', 'Premium News Access', 'Real Estate Listings', 'Car Rental Services',
            'Streaming/Media Access', 'Cloud Gaming Service', 'Digital Library/Books', 'Utility Bill Payments',
            'Legal Consultation', 'Digital Art Creation', 'Multi-Language Translation', 'Budgeting & Expense Tracking',
            'Wellness & Fitness Tracking', 'Pet Care Booking'
        ];

        // --- CORE UI FUNCTIONS ---

        /**
         * Wuxuu soo saaraa daaqadda fariinta ee loo isticmaalo ogeysiiska iyo digniinta.
         * @param {string} title - Cinwaanka fariinta.
         * @param {string} message - Fariinta oo faahfaahsan.
         */
        function showModal(title, message) {
            modalTitle.textContent = title;
            modalMessage.textContent = message;
            modal.style.display = 'flex';
        }

        /**
         * Wuxuu xiraa daaqadda fariinta.
         */
        function closeModal() {
            modal.style.display = 'none';
        }
        
        /**
         * Wuxuu cusboonaysiiyaa xaaladda Rewards-ka dashboard-ka.
         */
        function updateRewardsUI() {
            referralStatusElement.textContent = `${completedReferrals} / 3`;
            if (freeServiceReward) {
                 rewardsBalanceElement.textContent = `1 🎁 (Free: ${freeServiceReward})`;
                 rewardsBalanceElement.classList.remove('text-yellow-400');
                 rewardsBalanceElement.classList.add('text-pink-400'); 
            } else {
                 rewardsBalanceElement.textContent = `0 🎁`;
                 rewardsBalanceElement.classList.remove('text-pink-400');
                 rewardsBalanceElement.classList.add('text-yellow-400');
            }
        }


        // --- MOBILE NATIVE FUNCTIONS (Simulated Push Notifications) ---

        /**
         * Wuxuu sameeyaa jilitaan (Simulation) digniinta Push Notification ee Mobile-ka.
         * @param {string} alertType - Nooca digniinta (e.g., 'Urgent Security Alert').
         */
        function sendPushNotification(alertType) {
            let title = "";
            let body = "";
            
            if (alertType === 'Urgent Security Alert') {
                title = "🚨 DIGNIIN DEGDEGA AH! Amniga Nexus";
                body = "Waxaa la arkay isku day aan la ogolayn oo lagu galay Wallet-kaaga. AI Nexus Manager wuxuu si toos ah u xannibay (Locked) akoonkaaga. Riix si aad u xaqiijiso.";
            } else if (alertType === 'New Transaction') {
                 title = "💳 Lacag-bixin Cusub Waa La Sameeyay";
                 body = "Waxaa Wallet-kaaga laga jaray $45.00 oo lagu bixiyay 'Local Food Delivery'. Haddii aadan adiga ahayn, si degdeg ah u riix!";
            } else if (alertType === 'Compliance Success') {
                 title = "✅ Amni Sharci Waa La Xaqiijiyay";
                 body = "Hubintii Amniga Sharciga ah ee 81 Compliance Points waa la dhammeeyay. Nidaamku wuxuu weli ku jiraa heerka ugu sareeya ee amniga.";
            } else if (alertType === 'Reward Granted') {
                title = "🎁 Abaalmarin Waa La Ku Siiyay!";
                body = `Hambalyo! Waxaad heshay Adeeg Bilaash ah oo ah: ${freeServiceReward}. Isticmaal Reward-kaaga!`;
            }

            // Waxaan ku jilaynaa ogeysiiska Mobile-ka annagoo isticmaalayna Modal Window
            showModal(
                `📱 Digniinta Mobile-ka (Simulated):`,
                `**Fariin Digniin ah:** ${title}\n\n**Faahfaahin:** ${body}`
            );
        }

        // --- LIVE DATA SIMULATION ---

        /**
         * Wuxuu cusboonaysiiyaa Metrics-ka nidaamka (AI Requests & Latency) si joogto ah.
         */
        function updateMetrics() {
            // Update AI Requests/min (Simulated fluctuation)
            currentAiRequests += Math.floor(Math.random() * 50000) - 25000;
            if (currentAiRequests < 1000000) currentAiRequests = 1000000;
            aiRequestsElement.textContent = (currentAiRequests / 1000).toFixed(0) + 'K';

            // Update Global Latency (Simulated fluctuation)
            currentLatency = Math.max(35, 50 + Math.floor(Math.random() * 10) - 5);
            globalLatencyElement.textContent = `${currentLatency}ms`;

            // Color code Latency based on health (Green, Yellow, Red)
            if (currentLatency > 55) {
                globalLatencyElement.classList.remove('text-green-400', 'text-yellow-400');
                globalLatencyElement.classList.add('text-red-400');
            } else if (currentLatency > 45) {
                globalLatencyElement.classList.remove('text-green-400', 'text-red-400');
                globalLatencyElement.classList.add('text-yellow-400');
            } else {
                 globalLatencyElement.classList.remove('text-red-400', 'text-yellow-400');
                globalLatencyElement.classList.add('text-green-400');
            }
        }

        setInterval(updateMetrics, 2000); // Update every 2 seconds

        // --- AI CONSOLE AND REFERRAL HANDLERS ---
        
        /**
         * Wuxuu qabtaa badhanka 'Share App-ka'. Wuxuu jilayaa in isticmaaluhu u diray xiriirinta 3 qof.
         */
        function handleShareApp() {
             showModal(
                "📤 Xiriirinta Waa La Diray",
                "Waxaad xiriirinta (Referral Link) u dirtay saaxiibbadaa. Hadda, sug inta 3 qof ay App-ka soo dejiyaan oo ay iska diiwaangaliyaan."
            );
             // Jilitaan: 2 qof ayaa soo dejiyay kadib 3 ilbidhiqsi
             setTimeout(() => {
                 // The system updates the completed referrals count
                 if (completedReferrals < 2) {
                    completedReferrals = 2;
                    updateRewardsUI();
                    showModal(
                        "Xaqiijinta Xiriirinta",
                        "AI Rewards Manager wuxuu xaqiijiyay in 2 qof ay soo dejiyeen. Hadda 1 qof oo kaliya ayaa kaa dhiman si aad u hesho abaalmarinta!"
                    );
                 }
             }, 3000);
        }

        /**
         * SHAQADA MUHIIMKA AH: AI Reward Manager wuxuu xaqiijinayaa tirada xiriirinta, wuxuuna abuurayaa abaalmarinta.
         */
        function handleCheckRewardEligibility() {
            if (freeServiceReward) {
                showModal(
                    "🎁 Abaalmarin Waa Hore Ayaad Heshay",
                    `Waxaad horey u heshay Adeeg Bilaash ah oo ah: ${freeServiceReward}. Isticmaal marka hore inta aadan mid cusub helin.`
                );
                return;
            }

            if (completedReferrals < 3) {
                 // Simulation: The 3rd person signs up right after the check
                 completedReferrals = 3;
                 
                 // AI selects a random service for the free reward
                 const selectedService = allServices[Math.floor(Math.random() * allServices.length)];
                 freeServiceReward = selectedService; 
                 
                 updateRewardsUI(); // Update UI to show 1 Free Reward

                 showModal(
                    "✅ AI Rewards Manager: Xaqiijin Guul Leh",
                    `AI-du waxay xaqiijisay in 3 qof ay iska diiwaangaliyeen App-ka. Abaalmarintaada waa la siiyay! Waxaad heshay hal Adeeg oo Bilaash ah oo ah: **${selectedService}**.`
                 );
                 sendPushNotification('Reward Granted');

            } else {
                 showModal(
                    "✅ AI Rewards Manager: Xaqiijin Guul Leh",
                    `Nidaamka Xiriirinta wuu dhammaystiran yahay. Waxaad horey u heshay Abaalmarintaada!`
                 );
            }
        }


        // Handlers for AI Console Buttons
        function handleAiManagerCommand() {
            const title = "Amarka AI Manager-ka Waa La Diray";
            const message = "AI Nexus Manager wuxuu heley amarka mulkiilaha. Wuxuu si toos ah u bilaabay isku-habaynta 30-ka Microservice si uu u xaqiijiyo Amniga Sharciga ah.";
            showModal(title, message);
        }

        function handleSecurityCheck() {
            // Jilitaan: Dir digniin ah in Amniga Sharci uu xaqiijiyay
            sendPushNotification('Compliance Success');
        }

        function handleAiSupportQuery() {
            const title = "Jawaabta Degdegga ah ee AI Support";
            const message = "AI Support Customer wuxuu xalliyay dhibaatadaada lacag-bixinta 0.5 ilbidhiqsiyo gudahood. Xallinta Codsiga: 'Transaction-ka waa la soo celiyay (Refunded) si waafaqsan Qaanuunka Adeegga'.";
            showModal(title, message);
            // Jilitaan: Dir digniin ah in Transaction-ka cusub uu yimid
            setTimeout(() => sendPushNotification('New Transaction'), 1500);
        }

        // --- HANDLER FOR 30 MICROSERVICES BUTTONS (Modified for Free Service Logic) ---

        /**
         * Wuxuu qabtaa dhammaan 30-ka adeeg ee la riixay, isagoo tixgelinaya Abaalmarinta Bilaashka ah.
         * @param {string} serviceName - Magaca Adeegga la riixay.
         */
        function handleService(serviceName) {
            let title = `Adeegga ${serviceName} Waa La Hawl-geliyay`;
            let message = `Adeegga ${serviceName} wuxuu si guul leh ula xiriiray Global Microservices Architecture. Waxaa la xaqiijiyay in xawaaraha adeeggu yahay mid degdeg ah (Latencyna: ${currentLatency}ms).`;

            if (serviceName === freeServiceReward) {
                // Tani waa Adeegga Bilaashka ah (Free Service) ee uu qofku doortay.
                title = `🎉 Adeegga BILAASHKA AH Waa La Isticmaalay!`;
                message = `Adeegga **${serviceName}** waxaa lagu bixiyay **Abaalmarintaada Xiriirinta** (Referral Reward). Lacagtii caadiga ahayd ee Adeeggan, oo dhan $15, LAMA JARIN. \n\n**Xusuusnaw:** Hadii aad doorato adeeg u baahan lacag-bixin dibadeed (sida 'Local Food Delivery'), waa inaad bixisaa lacagta asalka ah (tusaale, $30 ee cuntada ah) si loogu gudbiyo shirkadda adeega. Adeegga App-ka (10%) waa BILAASH.`;
                
                // Reset the reward state and referral count
                freeServiceReward = null;
                completedReferrals = 0; 
                updateRewardsUI();
                
            } else {
                // Adeeg caadi ah - Wuxuu u baahan yahay lacag-bixin (simulated)
                title = `Adeegga ${serviceName} Waa La Hawl-geliyay`;
                message += ` \n\nWaxaa si toos ah lagaa jaray kharashka 10% ee adeeggan ($5.00) Digital Wallet-kaaga.`;
            }

            showModal(title, message);
        }

        // Run initial metrics update and UI update when the app starts
        updateMetrics();
        updateRewardsUI();

    </script>
</body>
</html>

