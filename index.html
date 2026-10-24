<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grewdon_GG21 | Creator & Speedrunner Hub</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts: Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        accent: {
                            purple: '#a855f7',
                            gold: '#f59e0b',
                            red: '#ef4444',
                            cyan: '#06b6d4',
                        }
                    },
                    animation: {
                        'pulse-glow': 'pulseGlow 3s infinite alternate',
                        'ping-slow': 'ping 2s cubic-bezier(0, 0, 0.2, 1) infinite',
                    },
                    keyframes: {
                        pulseGlow: {
                            '0%': { boxShadow: '0 0 15px var(--accent-glow-start)' },
                            '100%': { boxShadow: '0 0 35px var(--accent-glow-end)' },
                        }
                    }
                }
            }
        }
    </script>
    <style>
        /* Glassmorphism & Theme Design Tokens */
        :root {
            --accent-color: #a855f7;
            --accent-hover: #9333ea;
            --accent-glow-start: rgba(168, 85, 247, 0.25);
            --accent-glow-end: rgba(168, 85, 247, 0.65);
        }

        body {
            font-family: 'Inter', sans-serif;
            background-color: #080c14;
            color: #f3f4f6;
            overflow-x: hidden;
        }

        /* Translucent Glassmorphism Cards */
        .glass-card {
            background: rgba(15, 23, 42, 0.72);
            backdrop-filter: blur(16px);
            -webkit-backdrop-filter: blur(16px);
            border: 1px solid rgba(255, 255, 255, 0.08);
        }

        .glass-button {
            background: rgba(30, 41, 59, 0.65);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.09);
            transition: all 0.25s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .glass-button:hover {
            border-color: var(--accent-color);
            transform: translateY(-2px);
            box-shadow: 0 12px 28px -6px rgba(0, 0, 0, 0.4), 0 0 18px var(--accent-glow-start);
        }

        .theme-accent-text {
            color: var(--accent-color);
        }

        .theme-accent-bg {
            background-color: var(--accent-color);
        }

        .theme-accent-border {
            border-color: var(--accent-color);
        }

        /* Responsive Iframe Container for Twitch Player */
        .twitch-iframe-wrapper {
            position: relative;
            width: 100%;
            padding-top: 56.25%; /* 16:9 Aspect Ratio */
            border-radius: 0.75rem;
            overflow: hidden;
            background-color: #020617;
        }

        .twitch-iframe-wrapper iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100% !important;
            height: 100% !important;
            border: 0 !important;
        }

        /* Particle Canvas Positioning */
        #particles-canvas {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: 0;
            pointer-events: none;
        }

        /* Smooth Custom Scrollbar */
        ::-webkit-scrollbar {
            width: 6px;
        }
        ::-webkit-scrollbar-track {
            background: #080c14;
        }
        ::-webkit-scrollbar-thumb {
            background: #1e293b;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #334155;
        }
    </style>
</head>
<body class="min-h-screen flex flex-col items-center justify-between relative selection:bg-purple-500 selection:text-white">

    <!-- Dynamic Animated Network Canvas -->
    <canvas id="particles-canvas"></canvas>

    <!-- Interactive Copy Toast Notification -->
    <div id="toast" class="fixed top-5 right-5 z-50 transform translate-y-[-100px] opacity-0 transition-all duration-300 ease-out bg-slate-900 text-white px-4 py-3 rounded-xl shadow-2xl border border-slate-700 flex items-center gap-3">
        <svg class="w-5 h-5 text-emerald-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
        </svg>
        <span id="toast-message" class="text-sm font-medium">Link copied to clipboard!</span>
    </div>

    <!-- Top Header & Action Controls -->
    <header class="w-full max-w-xl px-4 pt-6 z-10 flex justify-between items-center">
        <!-- Live Status Pill Indicator -->
        <div class="inline-flex items-center gap-2 px-3 py-1.5 rounded-full glass-card text-xs font-medium text-slate-300 border border-slate-800 shadow-md">
            <span class="relative flex h-2.5 w-2.5">
              <span class="animate-ping-slow absolute inline-flex h-full w-full rounded-full bg-purple-400 opacity-75"></span>
              <span class="relative inline-flex rounded-full h-2.5 w-2.5 bg-purple-500"></span>
            </span>
            <span id="live-indicator-text" class="font-semibold text-slate-200">LIVE ON TWITCH</span>
        </div>

        <!-- Customizer Drawer Gear Button -->
        <button id="toggle-customizer" class="p-2.5 rounded-xl glass-card text-slate-300 hover:text-white transition-all duration-200 hover:scale-105 active:scale-95 border border-slate-800 shadow-lg" title="Open Theme Settings">
            <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z"></path>
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"></path>
            </svg>
        </button>
    </header>

    <!-- Customizer Panel (Drawer Overlay) -->
    <div id="customizer-panel" class="fixed inset-y-0 right-0 w-full sm:w-80 glass-card z-50 transform translate-x-full transition-transform duration-300 ease-in-out p-6 overflow-y-auto border-l border-slate-800 shadow-2xl flex flex-col justify-between hidden">
        <div>
            <div class="flex items-center justify-between pb-4 border-b border-slate-800">
                <h3 class="text-base font-bold text-white flex items-center gap-2">
                    <svg class="w-5 h-5 theme-accent-text" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4"></path></svg>
                    Page Settings
                </h3>
                <button id="close-customizer" class="text-slate-400 hover:text-white p-1">
                    <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path></svg>
                </button>
            </div>

            <div class="mt-5 space-y-4">
                <!-- Theme Presets -->
                <div>
                    <label class="block text-xs font-semibold text-slate-400 uppercase tracking-wider mb-2">Theme Accent</label>
                    <div class="grid grid-cols-4 gap-2">
                        <button class="color-btn p-2 rounded-xl bg-purple-900/40 border border-purple-500/50 hover:border-purple-400 text-center flex flex-col items-center gap-1 group" data-color="#a855f7" title="Twitch Purple">
                            <span class="w-5 h-5 rounded-full bg-purple-500 shadow-md"></span>
                            <span class="text-[10px] text-slate-300 group-hover:text-white">Purple</span>
                        </button>
                        <button class="color-btn p-2 rounded-xl bg-amber-900/40 border border-amber-500/50 hover:border-amber-400 text-center flex flex-col items-center gap-1 group" data-color="#f59e0b" title="Speedrunner Gold">
                            <span class="w-5 h-5 rounded-full bg-amber-500 shadow-md"></span>
                            <span class="text-[10px] text-slate-300 group-hover:text-white">Gold</span>
                        </button>
                        <button class="color-btn p-2 rounded-xl bg-red-900/40 border border-red-500/50 hover:border-red-400 text-center flex flex-col items-center gap-1 group" data-color="#ef4444" title="YouTube Crimson">
                            <span class="w-5 h-5 rounded-full bg-red-500 shadow-md"></span>
                            <span class="text-[10px] text-slate-300 group-hover:text-white">Crimson</span>
                        </button>
                        <button class="color-btn p-2 rounded-xl bg-cyan-900/40 border border-cyan-500/50 hover:border-cyan-400 text-center flex flex-col items-center gap-1 group" data-color="#06b6d4" title="Cyber Cyan">
                            <span class="w-5 h-5 rounded-full bg-cyan-400 shadow-md"></span>
                            <span class="text-[10px] text-slate-300 group-hover:text-white">Cyan</span>
                        </button>
                    </div>
                </div>

                <!-- Text Customization -->
                <div>
                    <label class="block text-xs font-semibold text-slate-400 uppercase tracking-wider mb-1">Display Name</label>
                    <input type="text" id="input-name" value="Grewdon_GG21" class="w-full px-3 py-2 bg-slate-900/90 border border-slate-700 rounded-xl text-xs text-white focus:outline-none focus:border-purple-500">
                </div>
                <div>
                    <label class="block text-xs font-semibold text-slate-400 uppercase tracking-wider mb-1">Tagline</label>
                    <input type="text" id="input-tagline" value="@Grewdon_GG21 • Content Creator & Speedrunner" class="w-full px-3 py-2 bg-slate-900/90 border border-slate-700 rounded-xl text-xs text-white focus:outline-none focus:border-purple-500">
                </div>
                <div>
                    <label class="block text-xs font-semibold text-slate-400 uppercase tracking-wider mb-1">Bio</label>
                    <textarea id="input-bio" rows="3" class="w-full px-3 py-2 bg-slate-900/90 border border-slate-700 rounded-xl text-xs text-white focus:outline-none focus:border-purple-500 resize-none">Livestreamer, Speedrunner & Content Creator | Crushing world records & hosting live streams on Twitch!</textarea>
                </div>

                <!-- Avatar URL Customization -->
                <div>
                    <label class="block text-xs font-semibold text-slate-400 uppercase tracking-wider mb-1">Avatar Image URL</label>
                    <input type="text" id="input-avatar-url" class="w-full px-3 py-2 bg-slate-900/90 border border-slate-700 rounded-xl text-xs text-white focus:outline-none focus:border-purple-500 truncate">
                </div>
            </div>
        </div>

        <div class="pt-4 border-t border-slate-800 space-y-2">
            <button id="reset-defaults" class="w-full py-2 bg-slate-800 hover:bg-slate-700 text-xs text-slate-300 font-semibold rounded-xl transition-colors">
                Reset Profile Defaults
            </button>
        </div>
    </div>

    <!-- Main Content Container -->
    <main class="w-full max-w-xl px-4 py-8 z-10 flex flex-col items-center">

        <!-- Profile Header -->
        <div class="flex flex-col items-center text-center space-y-3.5 mb-6">
            <!-- Glowing Avatar -->
            <div class="relative group">
                <div class="absolute -inset-0.5 rounded-full theme-accent-bg blur opacity-80 group-hover:opacity-100 transition duration-500 animate-pulse-glow"></div>
                <img id="profile-avatar" 
                     src="https://instagram.fmkc1-1.fna.fbcdn.net/v/t51.2885-19/419592256_915324233546479_3572091680982987181_n.jpg?stp=dst-jpg_s150x150_tt6&_nc_cat=111&ccb=7-5&_nc_sid=f7ccc5&efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLnd3dy41NTYuQzMifQ%3D%3D&_nc_ohc=NyPzdz0walAQ7kNvwG3FcyH&_nc_oc=AdpI9F2dULNuQZSSnsZNbPx9MynYxSI0Zs2nbxXYgs1OT_PQHVDnv98LBDzyOVScsS7ik3HLuWzatYnbTdffEjG6&_nc_zt=24&_nc_ht=instagram.fmkc1-1.fna&_nc_ss=7b6a8&oh=00_AQPUjwrH_nKwPfW3reTV3Kv6tzHEbAP3FYTH447UAFLXhg&oe=6AE2177D" 
                     alt="Grewdon_GG21 Avatar" 
                     class="relative w-28 h-28 sm:w-32 sm:h-32 rounded-full object-cover border-2 border-slate-800 shadow-2xl">
                <!-- Verified Badge -->
                <div class="absolute bottom-1 right-1 bg-slate-900 rounded-full p-1.5 border border-slate-800 shadow-md" title="Verified Creator & Speedrunner">
                    <svg class="w-5 h-5 theme-accent-text" fill="currentColor" viewBox="0 0 20 20">
                        <path fill-rule="evenodd" d="M6.267 3.455a3.066 3.066 0 001.745-.723 3.066 3.066 0 013.976 0 3.066 3.066 0 001.745.723 3.066 3.066 0 012.812 2.812c.051.643.304 1.254.723 1.745a3.066 3.066 0 010 3.976 3.066 3.066 0 00-.723 1.745 3.066 3.066 0 01-2.812 2.812 3.066 3.066 0 00-1.745.723 3.066 3.066 0 01-3.976 0 3.066 3.066 0 00-1.745-.723 3.066 3.066 0 01-2.812-2.812 3.066 3.066 0 00-.723-1.745 3.066 3.066 0 010-3.976 3.066 3.066 0 00.723-1.745 3.066 3.066 0 012.812-2.812zm7.44 5.252a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                    </svg>
                </div>
            </div>

            <!-- Profile Info -->
            <div class="space-y-1">
                <h1 id="profile-name" class="text-2xl sm:text-3xl font-extrabold tracking-tight text-white">Grewdon_GG21</h1>
                <p id="profile-tagline" class="text-xs sm:text-sm font-semibold theme-accent-text tracking-wide">@Grewdon_GG21 • Content Creator & Speedrunner</p>
            </div>

            <!-- Bio -->
            <p id="profile-bio" class="text-xs sm:text-sm text-slate-300 max-w-md leading-relaxed font-normal">
                Livestreamer, Speedrunner & Content Creator | Crushing world records & hosting live streams on Twitch!
            </p>
        </div>

        <!-- Twitch Live Stream Container -->
        <div class="w-full mb-6">
            <div class="glass-card rounded-2xl p-3 border border-purple-500/30 shadow-2xl relative overflow-hidden">
                <div class="flex items-center justify-between mb-2.5 px-1">
                    <div class="flex items-center gap-2">
                        <span class="relative flex h-2 w-2">
                            <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-red-400 opacity-75"></span>
                            <span class="relative inline-flex rounded-full h-2 w-2 bg-red-500"></span>
                        </span>
                        <span class="text-xs font-bold uppercase tracking-wider text-purple-300">Live Broadcast</span>
                    </div>
                    <a href="https://twitch.tv/grewdon_gg21" target="_blank" class="text-[11px] text-purple-400 hover:text-purple-300 hover:underline flex items-center gap-1 font-medium">
                        Watch on Twitch
                        <svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"></path></svg>
                    </a>
                </div>

                <!-- Exact Specified Twitch Stream Iframe Embed -->
                <div class="twitch-iframe-wrapper">
                    <iframe 
                        src="https://player.twitch.tv/?channel=grewdon_gg21&parent=https://grewdon.github.io/" 
                        frameborder="0" 
                        allowfullscreen="true" 
                        scrolling="no" 
                        height="378" 
                        width="620">
                    </iframe>
                </div>
            </div>
        </div>

        <!-- Links Grid Container -->
        <div class="w-full space-y-3.5">

            <!-- 1. YouTube Link -->
            <a href="https://youtube.com/@Grewdon_GG21" target="_blank" class="glass-button w-full p-4 rounded-2xl flex items-center justify-between group">
                <div class="flex items-center gap-3.5">
                    <div class="p-2.5 rounded-xl bg-red-500/20 text-red-500 group-hover:bg-red-600 group-hover:text-white transition-colors duration-200">
                        <svg class="w-6 h-6 fill-current" viewBox="0 0 24 24">
                            <path d="M23.498 6.186a3.016 3.016 0 0 0-2.122-2.136C19.505 3.545 12 3.545 12 3.545s-7.505 0-9.377.505A3.017 3.017 0 0 0 .502 6.186C0 8.07 0 12 0 12s0 3.93.502 5.814a3.016 3.016 0 0 0 2.122 2.136c1.871.505 9.376.505 9.376.505s7.505 0 9.377-.505a3.015 3.015 0 0 0 2.122-2.136C24 15.93 24 12 24 12s0-3.93-.502-5.814zM9.545 15.568V8.432L15.818 12l-6.273 3.568z"/>
                        </svg>
                    </div>
                    <div class="text-left">
                        <div class="font-semibold text-sm text-slate-100 group-hover:text-white">YouTube Channel</div>
                        <div class="text-xs text-slate-400">youtube.com/@Grewdon_GG21</div>
                    </div>
                </div>
                <svg class="w-5 h-5 text-slate-500 group-hover:text-slate-200 transform group-hover:translate-x-1 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path>
                </svg>
            </a>

            <!-- 2. Twitch Link -->
            <a href="https://twitch.tv/grewdon_gg21" target="_blank" class="glass-button w-full p-4 rounded-2xl flex items-center justify-between group">
                <div class="flex items-center gap-3.5">
                    <div class="p-2.5 rounded-xl bg-purple-500/20 text-purple-400 group-hover:bg-purple-600 group-hover:text-white transition-colors duration-200">
                        <svg class="w-6 h-6 fill-current" viewBox="0 0 24 24">
                            <path d="M11.571 1.429L1.429 4.286v15.714h5.714V22.5l2.857-2.857h4.286l7.143-7.143V1.429h-9.857zm8.429 10L17.143 14.286h-4.286l-2.857 2.857v-2.857H5.714V2.857h14.286v8.572zM15.714 5.714h-2.857v5.714h2.857V5.714zm-5.714 0H7.143v5.714h2.857V5.714z"/>
                        </svg>
                    </div>
                    <div class="text-left">
                        <div class="font-semibold text-sm text-slate-100 group-hover:text-white flex items-center gap-2">
                            <span>Twitch Channel</span>
                            <span class="text-[10px] bg-purple-500/30 text-purple-300 px-2 py-0.5 rounded-full font-mono">STREAM</span>
                        </div>
                        <div class="text-xs text-slate-400">twitch.tv/grewdon_gg21</div>
                    </div>
                </div>
                <svg class="w-5 h-5 text-slate-500 group-hover:text-slate-200 transform group-hover:translate-x-1 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path>
                </svg>
            </a>

            <!-- 3. Discord Community Link -->
            <a href="https://discord.gg" target="_blank" class="glass-button w-full p-4 rounded-2xl flex items-center justify-between group">
                <div class="flex items-center gap-3.5">
                    <div class="p-2.5 rounded-xl bg-indigo-500/20 text-indigo-400 group-hover:bg-indigo-600 group-hover:text-white transition-colors duration-200">
                        <svg class="w-6 h-6 fill-current" viewBox="0 0 24 24">
                            <path d="M20.317 4.37a19.791 19.791 0 0 0-4.885-1.515.074.074 0 0 0-.079.037c-.21.375-.444.864-.608 1.25a18.27 18.27 0 0 0-5.487 0 12.64 12.64 0 0 0-.617-1.25.077.077 0 0 0-.079-.037A19.736 19.736 0 0 0 3.677 4.37a.07.07 0 0 0-.032.027C.533 9.046-.32 13.58.099 18.057a.082.082 0 0 0 .031.057 19.9 19.9 0 0 0 5.993 3.03.078.078 0 0 0 .084-.028 14.09 14.09 0 0 0 1.226-1.994.076.076 0 0 0-.041-.106 13.107 13.107 0 0 1-1.872-.892.077.077 0 0 1-.008-.128 10.2 10.2 0 0 0 .372-.292.074.074 0 0 1 .077-.01c3.928 1.793 8.18 1.793 12.061 0a.074.074 0 0 1 .078.01c.12.098.246.198.373.292a.077.077 0 0 1-.006.127 12.299 12.299 0 0 1-1.873.892.077.077 0 0 0-.041.107c.36.698.772 1.362 1.225 1.993a.076.076 0 0 0 .084.028 19.839 19.839 0 0 0 6.002-3.03.077.077 0 0 0 .032-.054c.5-5.177-.838-9.674-3.549-13.66a.061.061 0 0 0-.031-.028zM8.02 15.33c-1.183 0-2.157-1.085-2.157-2.419 0-1.333.956-2.419 2.157-2.419 1.21 0 2.176 1.096 2.157 2.42 0 1.333-.956 2.418-2.157 2.418zm7.975 0c-1.183 0-2.157-1.085-2.157-2.419 0-1.333.955-2.419 2.157-2.419 1.21 0 2.176 1.096 2.157 2.42 0 1.333-.946 2.418-2.157 2.418z"/>
                        </svg>
                    </div>
                    <div class="text-left">
                        <div class="font-semibold text-sm text-slate-100 group-hover:text-white">Discord Server</div>
                        <div class="text-xs text-slate-400">Join the Community</div>
                    </div>
                </div>
                <svg class="w-5 h-5 text-slate-500 group-hover:text-slate-200 transform group-hover:translate-x-1 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path>
                </svg>
            </a>

            <!-- 4. Twitter / X Link -->
            <a href="https://x.com/Grewdon_GG21" target="_blank" class="glass-button w-full p-4 rounded-2xl flex items-center justify-between group">
                <div class="flex items-center gap-3.5">
                    <div class="p-2.5 rounded-xl bg-slate-700/40 text-slate-200 group-hover:bg-slate-100 group-hover:text-slate-900 transition-colors duration-200">
                        <svg class="w-6 h-6 fill-current" viewBox="0 0 24 24">
                            <path d="M18.244 2.25h3.308l-7.227 8.26 8.502 11.24H16.17l-5.214-6.817L4.99 21.75H1.68l7.73-8.835L1.254 2.25H8.08l4.713 6.231zm-1.161 17.52h1.833L7.084 4.126H5.117z"/>
                        </svg>
                    </div>
                    <div class="text-left">
                        <div class="font-semibold text-sm text-slate-100 group-hover:text-white">Twitter / X</div>
                        <div class="text-xs text-slate-400">@Grewdon_GG21</div>
                    </div>
                </div>
                <svg class="w-5 h-5 text-slate-500 group-hover:text-slate-200 transform group-hover:translate-x-1 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path>
                </svg>
            </a>

            <!-- 5. GitHub Link -->
            <a href="https://github.com/Grewdon" target="_blank" class="glass-button w-full p-4 rounded-2xl flex items-center justify-between group">
                <div class="flex items-center gap-3.5">
                    <div class="p-2.5 rounded-xl bg-slate-800/80 text-slate-200 group-hover:bg-slate-700 group-hover:text-white transition-colors duration-200">
                        <svg class="w-6 h-6 fill-current" viewBox="0 0 24 24">
                            <path d="M12 0C5.37 0 0 5.37 0 12c0 5.31 3.435 9.795 8.205 11.385.6.105.825-.255.825-.57 0-.285-.015-1.23-.015-2.235-3.015.555-3.795-.735-4.035-1.41-.135-.345-.72-1.41-1.23-1.695-.42-.225-1.02-.78-.015-.795.945-.015 1.62.87 1.845 1.23 1.08 1.815 2.805 1.305 3.495.99.105-.78.42-1.305.765-1.605-2.67-.3-5.46-1.335-5.46-5.925 0-1.305.465-2.385 1.23-3.225-.12-.3-.54-1.53.12-3.18 0 0 1.005-.315 3.3 1.23.96-.27 1.98-.405 3-.405s2.04.135 3 .405c2.295-1.56 3.3-1.23 3.3-1.23.66 1.65.24 2.88.12 3.18.765.84 1.23 1.905 1.23 3.225 0 4.605-2.805 5.625-5.475 5.925.435.375.81 1.095.81 2.22 0 1.605-.015 2.895-.015 3.3 0 .315.225.69.825.57A12.02 12.02 0 0024 12c0-6.63-5.37-12-12-12z"/>
                        </svg>
                    </div>
                    <div class="text-left">
                        <div class="font-semibold text-sm text-slate-100 group-hover:text-white">GitHub Profile</div>
                        <div class="text-xs text-slate-400">github.com/Grewdon</div>
                    </div>
                </div>
                <svg class="w-5 h-5 text-slate-500 group-hover:text-slate-200 transform group-hover:translate-x-1 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path>
                </svg>
            </a>

            <!-- 6. Instagram Link -->
            <a href="https://instagram.com/grewdon_gg21" target="_blank" class="glass-button w-full p-4 rounded-2xl flex items-center justify-between group">
                <div class="flex items-center gap-3.5">
                    <div class="p-2.5 rounded-xl bg-pink-500/20 text-pink-400 group-hover:bg-pink-600 group-hover:text-white transition-colors duration-200">
                        <svg class="w-6 h-6 fill-current" viewBox="0 0 24 24">
                            <path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/>
                        </svg>
                    </div>
                    <div class="text-left">
                        <div class="font-semibold text-sm text-slate-100 group-hover:text-white">Instagram</div>
                        <div class="text-xs text-slate-400">@grewdon_gg21</div>
                    </div>
                </div>
                <svg class="w-5 h-5 text-slate-500 group-hover:text-slate-200 transform group-hover:translate-x-1 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path>
                </svg>
            </a>

            <!-- 7. Speedrun.com Link (AT THE VERY BOTTOM) -->
            <a href="https://www.speedrun.com/user/Grewdon_GG21" target="_blank" class="glass-button w-full p-4 rounded-2xl flex items-center justify-between group border-amber-500/30">
                <div class="flex items-center gap-3.5">
                    <div class="p-2.5 rounded-xl bg-amber-500/20 text-amber-400 group-hover:bg-amber-500 group-hover:text-slate-950 transition-colors duration-200 shadow-inner">
                        <svg class="w-6 h-6 fill-current" viewBox="0 0 24 24">
                            <path d="M12 2a10 10 0 1 0 10 10 A10 10 0 0 0 12 2zm1 14.59L8.71 12.3a1 1 0 1 1 1.41-1.42L12 12.79l4.88-4.88a1 1 0 0 1 1.41 1.42zM12 4a1 1 0 0 1 1 1v1a1 1 0 0 1-2 0V5a1 1 0 0 1 1-1z"/>
                        </svg>
                    </div>
                    <div class="text-left">
                        <div class="font-semibold text-sm text-slate-100 group-hover:text-white flex items-center gap-2">
                            <span>Speedrun.com Profile</span>
                            <span class="text-[10px] bg-amber-500/30 text-amber-300 px-2 py-0.5 rounded-full font-mono font-bold">RECORDS</span>
                        </div>
                        <div class="text-xs text-slate-400">speedrun.com/user/Grewdon_GG21</div>
                    </div>
                </div>
                <svg class="w-5 h-5 text-slate-500 group-hover:text-amber-400 transform group-hover:translate-x-1 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path>
                </svg>
            </a>

        </div>

        <!-- Share Profile Button -->
        <div class="mt-8">
            <button id="share-btn" class="glass-card hover:bg-slate-800 text-slate-300 hover:text-white px-5 py-2.5 rounded-full text-xs font-semibold border border-slate-800 transition-all duration-200 flex items-center gap-2 shadow-lg">
                <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8.684 13.342C8.886 12.938 9 12.482 9 12c0-.482-.114-.938-.316-1.342m0 2.684a3 3 0 110-2.684m0 2.684l6.632 3.316m-6.632-6l6.632-3.316m0 0a3 3 0 105.367-2.684 3 3 0 00-5.367 2.684zm0 9.316a3 3 0 105.368 2.684 3 3 0 00-5.368-2.684z"></path>
                </svg>
                <span>Share Profile Hub</span>
            </button>
        </div>
    </main>

    <!-- Footer -->
    <footer class="w-full text-center py-6 z-10 text-xs text-slate-500">
        <p>© <span id="current-year"></span> Grewdon_GG21 • Hosted on GitHub Pages</p>
    </footer>

    <!-- Interactive Canvas & Controls JavaScript -->
    <script>
        // --- 1. Dynamic Canvas Background ---
        const canvas = document.getElementById('particles-canvas');
        const ctx = canvas.getContext('2d');

        let particles = [];
        let particleCount = 40;
        let themeRGB = { r: 168, g: 85, b: 247 }; // Twitch Purple default

        function resizeCanvas() {
            canvas.width = window.innerWidth;
            canvas.height = window.innerHeight;
        }

        window.addEventListener('resize', resizeCanvas);
        resizeCanvas();

        class Particle {
            constructor() {
                this.reset();
            }

            reset() {
                this.x = Math.random() * canvas.width;
                this.y = Math.random() * canvas.height;
                this.size = Math.random() * 2 + 0.5;
                this.speedX = (Math.random() - 0.5) * 0.4;
                this.speedY = (Math.random() - 0.5) * 0.4;
                this.alpha = Math.random() * 0.5 + 0.1;
            }

            update() {
                this.x += this.speedX;
                this.y += this.speedY;

                if (this.x < 0 || this.x > canvas.width || this.y < 0 || this.y > canvas.height) {
                    this.reset();
                }
            }

            draw() {
                ctx.beginPath();
                ctx.arc(this.x, this.y, this.size, 0, Math.PI * 2);
                ctx.fillStyle = `rgba(${themeRGB.r}, ${themeRGB.g}, ${themeRGB.b}, ${this.alpha})`;
                ctx.fill();
            }
        }

        function initParticles() {
            particles = [];
            for (let i = 0; i < particleCount; i++) {
                particles.push(new Particle());
            }
        }

        function animateParticles() {
            ctx.clearRect(0, 0, canvas.width, canvas.height);

            for (let a = 0; a < particles.length; a++) {
                for (let b = a; b < particles.length; b++) {
                    let dx = particles[a].x - particles[b].x;
                    let dy = particles[a].y - particles[b].y;
                    let distance = Math.sqrt(dx * dx + dy * dy);

                    if (distance < 110) {
                        ctx.beginPath();
                        ctx.strokeStyle = `rgba(${themeRGB.r}, ${themeRGB.g}, ${themeRGB.b}, ${0.15 - distance / 1100})`;
                        ctx.lineWidth = 0.5;
                        ctx.moveTo(particles[a].x, particles[a].y);
                        ctx.lineTo(particles[b].x, particles[b].y);
                        ctx.stroke();
                    }
                }
            }

            particles.forEach(p => {
                p.update();
                p.draw();
            });

            requestAnimationFrame(animateParticles);
        }

        function hexToRgb(hex) {
            let result = /^#?([a-f\d]{2})([a-f\d]{2})([a-f\d]{2})$/i.exec(hex);
            return result ? {
                r: parseInt(result[1], 16),
                g: parseInt(result[2], 16),
                b: parseInt(result[3], 16)
            } : null;
        }

        // --- 2. Customizer Modal Controls ---
        const customizerPanel = document.getElementById('customizer-panel');
        const toggleBtn = document.getElementById('toggle-customizer');
        const closeBtn = document.getElementById('close-customizer');

        toggleBtn.addEventListener('click', () => {
            customizerPanel.classList.remove('hidden');
            setTimeout(() => customizerPanel.classList.remove('translate-x-full'), 10);
        });

        closeBtn.addEventListener('click', () => {
            customizerPanel.classList.add('translate-x-full');
            setTimeout(() => customizerPanel.classList.add('hidden'), 300);
        });

        // Dynamic Form Live Inputs
        const inputName = document.getElementById('input-name');
        const inputTagline = document.getElementById('input-tagline');
        const inputBio = document.getElementById('input-bio');
        const inputAvatarUrl = document.getElementById('input-avatar-url');

        const profileName = document.getElementById('profile-name');
        const profileTagline = document.getElementById('profile-tagline');
        const profileBio = document.getElementById('profile-bio');
        const profileAvatar = document.getElementById('profile-avatar');

        inputName.addEventListener('input', (e) => profileName.textContent = e.target.value || 'Grewdon_GG21');
        inputTagline.addEventListener('input', (e) => profileTagline.textContent = e.target.value || '@Grewdon_GG21');
        inputBio.addEventListener('input', (e) => profileBio.textContent = e.target.value || '');

        const defaultIgAvatar = "https://instagram.fmkc1-1.fna.fbcdn.net/v/t51.2885-19/419592256_915324233546479_3572091680982987181_n.jpg?stp=dst-jpg_s150x150_tt6&_nc_cat=111&ccb=7-5&_nc_sid=f7ccc5&efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLnd3dy41NTYuQzMifQ%3D%3D&_nc_ohc=NyPzdz0walAQ7kNvwG3FcyH&_nc_oc=AdpI9F2dULNuQZSSnsZNbPx9MynYxSI0Zs2nbxXYgs1OT_PQHVDnv98LBDzyOVScsS7ik3HLuWzatYnbTdffEjG6&_nc_zt=24&_nc_ht=instagram.fmkc1-1.fna&_nc_ss=7b6a8&oh=00_AQPUjwrH_nKwPfW3reTV3Kv6tzHEbAP3FYTH447UAFLXhg&oe=6AE2177D";
        const fallbackAvatar = "https://images.unsplash.com/photo-1566492031773-4f4e44671857?w=300&auto=format&fit=crop&q=80";

        inputAvatarUrl.value = defaultIgAvatar;

        profileAvatar.onerror = function() {
            this.onerror = null;
            this.src = fallbackAvatar;
        };

        inputAvatarUrl.addEventListener('change', (e) => {
            const val = e.target.value.trim();
            profileAvatar.src = val !== '' ? val : defaultIgAvatar;
        });

        // Theme Switcher
        const colorBtns = document.querySelectorAll('.color-btn');
        colorBtns.forEach(btn => {
            btn.addEventListener('click', () => {
                const color = btn.getAttribute('data-color');
                document.documentElement.style.setProperty('--accent-color', color);
                themeRGB = hexToRgb(color) || themeRGB;
            });
        });

        // Reset Settings
        document.getElementById('reset-defaults').addEventListener('click', () => {
            inputName.value = "Grewdon_GG21";
            inputTagline.value = "@Grewdon_GG21 • Content Creator & Speedrunner";
            inputBio.value = "Livestreamer, Speedrunner & Content Creator | Crushing world records & hosting live streams on Twitch!";
            inputAvatarUrl.value = defaultIgAvatar;

            profileName.textContent = inputName.value;
            profileTagline.textContent = inputTagline.value;
            profileBio.textContent = inputBio.value;
            profileAvatar.src = defaultIgAvatar;

            colorBtns[0].click();
        });

        // --- 3. Copy to Clipboard ---
        const shareBtn = document.getElementById('share-btn');
        const toast = document.getElementById('toast');
        const toastMessage = document.getElementById('toast-message');

        function showToast(msg) {
            toastMessage.textContent = msg;
            toast.classList.remove('translate-y-[-100px]', 'opacity-0');
            toast.classList.add('translate-y-0', 'opacity-100');

            setTimeout(() => {
                toast.classList.remove('translate-y-0', 'opacity-100');
                toast.classList.add('translate-y-[-100px]', 'opacity-0');
            }, 3000);
        }

        shareBtn.addEventListener('click', () => {
            const pageUrl = window.location.href;
            const tempInput = document.createElement('input');
            document.body.appendChild(tempInput);
            tempInput.value = pageUrl;
            tempInput.select();
            document.execCommand('copy');
            document.body.removeChild(tempInput);
            showToast("Grewdon_GG21 hub link copied!");
        });

        window.onload = function() {
            initParticles();
            animateParticles();
            document.getElementById('current-year').textContent = new Date().getFullYear();
        };
    </script>
</body>
</html>
