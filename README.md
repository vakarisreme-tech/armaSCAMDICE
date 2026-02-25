<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DicePlatform</title>
<script src="https://cdn.tailwindcss.com"></script>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
<style>
body { font-family: 'Inter', sans-serif; }
.scrollbar::-webkit-scrollbar { width: 6px; }
.scrollbar::-webkit-scrollbar-thumb { background: #1f2937; border-radius: 10px; }
</style>
</head>

<body class="bg-[#0f172a] text-white">

<div class="flex h-screen overflow-hidden">

    <!-- Sidebar -->
    <div class="w-64 bg-[#0b1220] p-5 space-y-4 hidden md:block">
        <h1 class="text-2xl font-bold text-blue-400">DicePlatform</h1>

        <div class="space-y-2 mt-6 text-gray-300">
            <div class="hover:text-white cursor-pointer">Rewards</div>
            <div class="hover:text-white cursor-pointer">Daily Race</div>

            <div class="text-gray-500 text-sm mt-4">Originals</div>
            <div class="space-y-2 pl-2">
                <div class="hover:text-white cursor-pointer">Dice</div>
                <div class="hover:text-white cursor-pointer">Cases</div>
                <div class="hover:text-white cursor-pointer">Case Battles</div>
                <div class="hover:text-white cursor-pointer">Crash</div>
                <div class="hover:text-white cursor-pointer">Mines</div>
                <div class="hover:text-white cursor-pointer">Tower</div>
                <div class="hover:text-white cursor-pointer">Limbo</div>
            </div>

            <div class="hover:text-white cursor-pointer mt-4">Leaderboard</div>
            <div class="hover:text-white cursor-pointer">Affiliates</div>
            <div class="hover:text-white cursor-pointer">Promo Codes</div>
            <div class="hover:text-white cursor-pointer">Live Support</div>
        </div>
    </div>

    <!-- Main Content -->
    <div class="flex-1 flex flex-col">

        <!-- Top Bar -->
        <div class="flex justify-between items-center p-4 bg-[#111827] border-b border-gray-800">
            <div class="text-lg font-semibold">Balance: <span class="text-blue-400">$0.00</span></div>
            <div class="flex items-center gap-4">
                <div class="text-green-400 text-sm">● 100 Online</div>
                <button class="bg-blue-500 px-4 py-2 rounded-lg hover:bg-blue-600">Deposit</button>
            </div>
        </div>

        <!-- Scroll Area -->
        <div class="flex-1 overflow-y-auto p-6 space-y-8 scrollbar">

            <!-- Banners -->
            <div class="grid md:grid-cols-4 gap-4">
                <div class="bg-gradient-to-r from-blue-600 to-blue-400 p-5 rounded-xl">Daily Race</div>
                <div class="bg-gradient-to-r from-yellow-600 to-yellow-400 p-5 rounded-xl">Open Cases</div>
                <div class="bg-gradient-to-r from-green-600 to-green-400 p-5 rounded-xl">Refer & Earn</div>
                <div class="bg-gradient-to-r from-purple-600 to-purple-400 p-5 rounded-xl">VIP Boost</div>
            </div>

            <!-- Originals -->
            <div>
                <h2 class="text-xl font-semibold mb-4">Original Games</h2>
                <div class="grid md:grid-cols-4 gap-6">

                    <div class="bg-[#1f2937] p-6 rounded-xl hover:bg-[#273449] cursor-pointer">🎲 Dice</div>
                    <div class="bg-[#1f2937] p-6 rounded-xl hover:bg-[#273449] cursor-pointer">📦 Cases</div>
                    <div class="bg-[#1f2937] p-6 rounded-xl hover:bg-[#273449] cursor-pointer">⚔️ Case Battles</div>
                    <div class="bg-[#1f2937] p-6 rounded-xl hover:bg-[#273449] cursor-pointer">📉 Crash</div>
                    <div class="bg-[#1f2937] p-6 rounded-xl hover:bg-[#273449] cursor-pointer">💣 Mines</div>
                    <div class="bg-[#1f2937] p-6 rounded-xl hover:bg-[#273449] cursor-pointer">🗼 Tower</div>
                    <div class="bg-[#1f2937] p-6 rounded-xl hover:bg-[#273449] cursor-pointer">🎯 Limbo</div>

                </div>
            </div>

        </div>
    </div>

    <!-- Chat Panel -->
    <div class="w-80 bg-[#0b1220] border-l border-gray-800 hidden lg:flex flex-col">
        <div class="p-4 border-b border-gray-800">
            <div class="text-green-400 font-semibold">Emerald Rain</div>
            <button class="bg-green-600 mt-2 w-full py-2 rounded-lg">Join</button>
        </div>

        <div class="flex-1 p-4 space-y-3 overflow-y-auto scrollbar text-sm">
            <div><span class="text-blue-400">User1:</span> Nice win!</div>
            <div><span class="text-purple-400">User2:</span> Good luck!</div>
            <div><span class="text-yellow-400">User3:</span> Big battle incoming 👀</div>
        </div>

        <div class="p-4 border-t border-gray-800">
            <input type="text" placeholder="Say something..."
                class="w-full bg-[#1f2937] p-2 rounded-lg outline-none">
        </div>
    </div>

</div>

</body>
</html>
