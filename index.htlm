<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>৯০ ও ২০০০ দশকের নস্টালজিয়া</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Hind+Siliguri:wght@400;600;700&display=swap" rel="stylesheet">
    
    <style>
        body {
            font-family: 'Hind Siliguri', sans-serif;
            background-color: #0B0914; /* Dark nostalgic background */
            color: #ffffff;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }
        /* Neon Glow Effects */
        .neon-text {
            text-shadow: 0 0 5px #fff, 0 0 10px #0ea5e9, 0 0 20px #0ea5e9;
        }
        .neon-box {
            box-shadow: 0 0 15px rgba(168, 85, 247, 0.4);
            border: 2px solid #a855f7;
        }
        /* Custom Checkbox Design */
        input[type="checkbox"] {
            appearance: none;
            background-color: #1f2937;
            margin: 0;
            font: inherit;
            color: currentColor;
            width: 1.5em;
            height: 1.5em;
            border: 2px solid #4b5563;
            border-radius: 0.25em;
            display: grid;
            place-content: center;
            cursor: pointer;
            transition: all 0.2s ease-in-out;
        }
        input[type="checkbox"]::before {
            content: "";
            width: 0.8em;
            height: 0.8em;
            transform: scale(0);
            transition: 120ms transform ease-in-out;
            box-shadow: inset 1em 1em #facc15; /* Yellow Check */
            background-color: #facc15;
            transform-origin: center;
            clip-path: polygon(14% 44%, 0 65%, 50% 100%, 100% 16%, 80% 0%, 43% 62%);
        }
        input[type="checkbox"]:checked {
            border-color: #facc15;
            background-color: rgba(250, 204, 21, 0.2);
        }
        input[type="checkbox"]:checked::before {
            transform: scale(1);
        }
    </style>
</head>
<body class="antialiased">

    <!-- ==================== WELCOME MODAL (Exactly like your screenshot) ==================== -->
    <div id="welcomeModal" class="fixed inset-0 bg-black bg-opacity-90 z-50 flex items-center justify-center p-4 backdrop-blur-sm">
        <div class="bg-[#110c22] neon-box max-w-md w-full p-6 sm:p-8 relative rounded-xl overflow-hidden">
            
            <!-- Colorful Top Bar -->
            <div class="absolute top-0 left-0 w-full flex h-2 sm:h-3">
                <div class="flex-1 bg-white"></div>
                <div class="flex-1 bg-yellow-400"></div>
                <div class="flex-1 bg-cyan-400"></div>
                <div class="flex-1 bg-green-500"></div>
                <div class="flex-1 bg-pink-500"></div>
                <div class="flex-1 bg-red-500"></div>
                <div class="flex-1 bg-blue-600"></div>
            </div>

            <!-- Header Info -->
            <div class="flex justify-between items-center mt-4 mb-6">
                <span class="bg-yellow-400 text-[#0f0a2e] px-2 py-1 font-bold text-xs sm:text-sm rounded-sm">SIDE A • 90s/2000s</span>
                <span class="text-pink-500 font-bold text-sm animate-pulse flex items-center gap-1">
                    <span class="w-2 h-2 bg-pink-500 rounded-full inline-block"></span> REC
                </span>
            </div>

            <!-- Title -->
            <h2 class="text-2xl sm:text-3xl font-bold text-center text-yellow-400 mb-4 drop-shadow-[0_0_8px_rgba(250,204,21,0.6)]">
                আরে! আপনার শৈশব কেমন ছিল জেনে নেবেন না? 📼
            </h2>

            <!-- Description -->
            <p class="text-center text-gray-300 text-sm sm:text-base mb-6 leading-relaxed">
                ৯০ ও ২০০০ দশকের টিভি, খেলাধুলা, খাবার ও স্মৃতির চমৎকার সব কালেকশন নিয়ে তৈরি এই নস্টালজিয়া চেকলিস্ট! সবগুলোতে টিক দিয়ে দেখুন আপনার নস্টালজিয়া স্কোর কত!
            </p>

            <!-- Disclaimer -->
            <div class="border-2 border-dashed border-pink-600 rounded-lg p-3 mb-6 bg-pink-900 bg-opacity-20">
                <p class="text-xs sm:text-sm text-center text-gray-300">
                    <span class="text-yellow-400">⚠️</span> <strong>ডিসক্লেইমার:</strong> এটি শুধুমাত্র বিনোদন ও শৈশবের মিষ্টি স্মৃতি রোমন্থনের উদ্দেশ্যে তৈরি করা হয়েছে।
                </p>
            </div>

            <!-- START BUTTON (Fixed with direct onclick function) -->
            <button onclick="startApp()" class="w-full py-3 sm:py-4 mt-2 text-lg font-bold bg-yellow-400 text-[#0f0a2e] rounded-md transition-transform transform hover:scale-105 active:scale-95 border-none cursor-pointer" style="box-shadow: 4px 4px 0px #EC4899;">
                চলুন শুরু করি! 🚀
            </button>

            <!-- Colorful Bottom Bar -->
            <div class="absolute bottom-0 left-0 w-full flex h-2 sm:h-3">
                <div class="flex-1 bg-white"></div>
                <div class="flex-1 bg-yellow-400"></div>
                <div class="flex-1 bg-cyan-400"></div>
                <div class="flex-1 bg-green-500"></div>
                <div class="flex-1 bg-pink-500"></div>
                <div class="flex-1 bg-red-500"></div>
                <div class="flex-1 bg-blue-600"></div>
            </div>
        </div>
    </div>

    <!-- ==================== MAIN APP CONTENT (Hidden initially) ==================== -->
    <div id="mainApp" class="hidden min-h-screen pb-32 pt-8 px-4 max-w-3xl mx-auto">
        <h1 class="text-3xl sm:text-4xl font-bold text-center text-cyan-400 mb-8 neon-text">নস্টালজিয়া চেকলিস্ট 📻</h1>
        
        <div class="bg-[#151125] p-4 sm:p-6 rounded-xl border border-gray-700 shadow-lg">
            <div id="checklistContainer" class="space-y-3 sm:space-y-4">
                <!-- Checklist items will be generated here by JavaScript -->
            </div>
        </div>
    </div>

    <!-- ==================== STICKY SCORE FOOTER ==================== -->
    <div id="scoreFooter" class="hidden fixed bottom-0 left-0 w-full bg-[#110c22] border-t-2 border-purple-500 p-4 text-center z-40 shadow-[0_-5px_15px_rgba(0,0,0,0.5)]">
        <p class="text-xl sm:text-2xl font-bold text-white">
            আপনার স্কোর: <span id="scoreDisplay" class="text-yellow-400">০</span> / <span id="totalDisplay" class="text-cyan-400">০</span>
        </p>
        <p id="scoreMessage" class="text-sm sm:text-base font-semibold text-pink-400 mt-2 transition-all duration-300"></p>
    </div>

    <!-- ==================== JAVASCRIPT ==================== -->
    <script>
        // আপনার চেকলিস্টের প্রশ্নগুলো এখানে যুক্ত করতে পারেন
        const nostalgiaItems = [
            "স্কুল শেষে 'শক্তিমান' বা 'ক্যাপ্টেন প্ল্যানেট' দেখা",
            "ক্যাসেট ফিতায় পেন্সিল ঢুকিয়ে ঘোরানো",
            "টিফিনের টাকায় হাওয়াই মিঠাই বা চুরমুর খাওয়া",
            "লোডশেডিংয়ে ছাদে উঠে আড্ডা বা ভূত-এফএম শোনা",
            "খাতায় 'কাটাকুটি' (Tic-Tac-Toe) বা 'রাজা-মন্ত্রী-চোর-পুলিশ' খেলা",
            "টিভির এন্টেনা ঠিক করতে গিয়ে 'ক্লিয়ার আসছে?' বলে চিল্লানো",
            "সুপার মারিও বা কন্ট্রা (Contra) ভিডিও গেম খেলা",
            "প্লাস্টিকের ব্যাট দিয়ে বা পাড়ার গলিতে ক্রিকেট খেলা",
            "সাইকেলের চাকায় বোতল বা কাগজ লাগিয়ে বাইকের সাউন্ড করা",
            "প্রথম দিকের মোবাইল ফোনে 'স্নেক গেম' (Snake Game) খেলা",
            "স্কুলের বইয়ের মলাট ব্রাউন পেপার দিয়ে মোড়ানো",
            "বায়োস্কোপওয়ালা এলে দৌড়ে গিয়ে দেখা"
        ];

        let currentScore = 0;

        // Modal hide করা এবং Main app show করার ফাংশন
        function startApp() {
            // Modal গায়েব করা
            document.getElementById('welcomeModal').classList.add('hidden');
            document.getElementById('welcomeModal').classList.remove('flex');
            
            // Main Content ও Score Footer দেখানো
            document.getElementById('mainApp').classList.remove('hidden');
            document.getElementById('scoreFooter').classList.remove('hidden');
            
            // চেকলিস্ট রেন্ডার করা
            renderChecklist();
            
            // পেজ একদম উপরে স্ক্রল করা
            window.scrollTo(0, 0);
        }

        // বাংলা সংখ্যায় কনভার্ট করার ফাংশন
        function toBengaliNum(num) {
            const bengaliDigits = ['০', '১', '২', '৩', '৪', '৫', '৬', '৭', '৮', '৯'];
            return num.toString().split('').map(digit => bengaliDigits[digit] || digit).join('');
        }

        // চেকলিস্ট আইটেমগুলো HTML এ দেখানো
        function renderChecklist() {
            const container = document.getElementById('checklistContainer');
            container.innerHTML = ''; // Clear existing
            
            document.getElementById('totalDisplay').innerText = toBengaliNum(nostalgiaItems.length);
            
            nostalgiaItems.forEach((item, index) => {
                const itemDiv = document.createElement('div');
                // স্টাইলিং - Hover effect এবং click area
                itemDiv.className = "flex items-center p-3 sm:p-4 bg-[#1e1a33] rounded-lg border border-gray-700 hover:border-pink-500 transition-colors duration-200 cursor-pointer group";
                
                // পুরো div এ ক্লিক করলে যেন চেকবক্স সিলেক্ট হয়
                itemDiv.onclick = function(e) {
                    if (e.target.tagName !== 'INPUT') {
                        const checkbox = document.getElementById('item-' + index);
                        checkbox.checked = !checkbox.checked;
                        updateScore();
                    }
                };
                
                itemDiv.innerHTML = `
                    <input type="checkbox" id="item-${index}" class="shrink-0" onchange="updateScore()">
                    <label for="item-${index}" class="ml-4 text-base sm:text-lg text-gray-200 cursor-pointer select-none flex-1 group-hover:text-white transition-colors">
                        ${item}
                    </label>
                `;
                container.appendChild(itemDiv);
            });

            // মেসেজ ইনিশিয়ালাইজ করা
            updateScore();
        }

        // স্কোর আপডেট করার ফাংশন
        function updateScore() {
            const checkboxes = document.querySelectorAll('input[type="checkbox"]');
            currentScore = Array.from(checkboxes).filter(cb => cb.checked).length;
            
            // স্কোর দেখানো
            document.getElementById('scoreDisplay').innerText = toBengaliNum(currentScore);
            
            // স্কোরের উপর ভিত্তি করে মেসেজ
            let message = "";
            const total = nostalgiaItems.length;
            
            if (currentScore === 0) {
                message = "এখনো টিক দেওয়া শুরু করেননি! 😅";
            } else if (currentScore <= Math.floor(total * 0.3)) {
                message = "আপনি কি ২০০০ এর পরের জেনারেশন? 🤔";
            } else if (currentScore <= Math.floor(total * 0.7)) {
                message = "দারুণ! আপনার শৈশব অনেক কালারফুল ছিল! ✨";
            } else if (currentScore === total) {
                message = "বাপ রে! আপনি একদম ১০০% খাঁটি লিজেন্ড! 👑🏆";
            } else {
                message = "অসাধারণ! আপনি একদম খাঁটি ৯০ দশকের মানুষ! 😎";
            }
            
            document.getElementById('scoreMessage').innerText = message;
        }
    </script>
</body>
</html>
