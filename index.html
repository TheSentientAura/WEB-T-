<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Vocal Decoder: Speech Emotion Recognition</title>
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Chart.js -->
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>

    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #FDFBF7; /* Warm neutral background */
            color: #1F2937;
        }

        /* Custom Range Slider Styling */
        input[type=range] {
            -webkit-appearance: none;
            width: 100%;
            background: transparent;
        }
        input[type=range]::-webkit-slider-thumb {
            -webkit-appearance: none;
            height: 20px;
            width: 20px;
            border-radius: 50%;
            background: #4B5563;
            cursor: pointer;
            margin-top: -8px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.2);
        }
        input[type=range]::-webkit-slider-runnable-track {
            width: 100%;
            height: 4px;
            cursor: pointer;
            background: #D1D5DB;
            border-radius: 2px;
        }
        
        /* Chart Container Standards */
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 600px;
            height: 350px;
            margin-left: auto;
            margin-right: auto;
        }
        
        @media (max-width: 640px) {
            .chart-container {
                height: 300px;
            }
        }
    </style>

    <!-- Chosen Palette: Warm Neutrals (Sand, Stone) with Functional Accents (Slate, Sage, Muted Red) for clarity and calm harmony. -->
    
    <!-- Application Structure Plan: 
         1. Header & Definition: Directly answers the user's question about the specific "Word" (SER/Prosody).
         2. The Audio Analyzer Simulation: A gamified dashboard where users manipulate the variables (Pitch, Rate, Volume) to see real-time mood classification based on the logic provided in the prompt. This turns abstract concepts into a concrete tool.
         3. Comparative Analysis (Radar Chart): Visualizes how different emotions have distinct "shapes" across paralinguistic features.
         4. Feature Breakdown (Bar Charts): Deep dive into specific text-based cues like filler words.
         This structure moves from Definition -> Interaction -> Data Visualization -> Synthesis. 
    -->

    <!-- Visualization & Content Choices:
         1. Interactive Dashboard (HTML/JS): Goal: Inform & Change. Allows users to adjust sliders to simulate voice input and see instantaneous "Mood Detection" text updates.
         2. Radar Chart (Chart.js): Goal: Compare/Relationships. Perfect for showing the multi-dimensional nature of emotion (Pitch vs Volume vs Speed) in a single shape.
         3. Horizontal Bar Chart (Chart.js): Goal: Compare. Breaks down the "Fluency" aspect (Filler words) specifically.
         4. Cards/Grid: Goal: Organize. Clean layout for definitions.
         NO SVG used. NO Mermaid used. All icons are CSS or Unicode.
    -->

    <!-- CONFIRMATION: NO SVG graphics used. NO Mermaid JS used. -->
</head>
<body class="antialiased">

    <!-- Navigation / Header -->
    <header class="bg-white border-b border-stone-200 sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16 items-center">
                <div class="flex items-center">
                    <span class="text-2xl mr-2">🎙️</span>
                    <h1 class="text-xl font-bold text-stone-800 tracking-tight">Vocal<span class="text-stone-500">Decoder</span></h1>
                </div>
                <nav class="hidden md:flex space-x-8">
                    <button onclick="scrollToSection('definition')" class="text-stone-500 hover:text-stone-900 px-3 py-2 rounded-md text-sm font-medium transition-colors">The Word</button>
                    <button onclick="scrollToSection('simulator')" class="text-stone-500 hover:text-stone-900 px-3 py-2 rounded-md text-sm font-medium transition-colors">Analyzer</button>
                    <button onclick="scrollToSection('patterns')" class="text-stone-500 hover:text-stone-900 px-3 py-2 rounded-md text-sm font-medium transition-colors">Data Patterns</button>
                </nav>
            </div>
        </div>
    </header>

    <main class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-10 space-y-16">

        <!-- SECTION 1: THE ANSWER (Definition) -->
        <section id="definition" class="space-y-6">
            <div class="bg-stone-50 border border-stone-200 rounded-xl p-8 shadow-sm">
                <div class="max-w-3xl">
                    <h2 class="text-3xl font-bold text-stone-900 mb-4">What is the word?</h2>
                    <p class="text-lg text-stone-700 leading-relaxed mb-6">
                        Based on academic research, the analysis of how words are spoken via microphone to detect mood is formally known as <span class="font-bold text-indigo-700 bg-indigo-50 px-2 py-1 rounded">Speech Emotion Recognition (SER)</span>.
                    </p>
                    <p class="text-stone-600 mb-6">
                        The specific aspects you listed—tone, rate, volume, and quality—are collectively called <span class="font-bold text-stone-900">Prosodic Features</span> or <span class="font-bold text-stone-900">Paralinguistics</span>.
                    </p>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                        <div class="bg-white p-4 rounded-lg border border-stone-100">
                            <h3 class="font-semibold text-stone-900 mb-2">🎯 Prosody</h3>
                            <p class="text-sm text-stone-600">The rhythm, stress, and intonation of speech. It is the "music" of the language.</p>
                        </div>
                        <div class="bg-white p-4 rounded-lg border border-stone-100">
                            <h3 class="font-semibold text-stone-900 mb-2">📊 Paralinguistics</h3>
                            <p class="text-sm text-stone-600">The non-lexical component of communication by speech, for example intonation, pitch and speed of speaking.</p>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="text-sm text-stone-500 bg-white p-4 rounded-lg border-l-4 border-indigo-500">
                <strong>Academic Context:</strong> Researchers use algorithms to extract these "acoustic features" from audio waveforms to classify the speaker's emotional state with high accuracy.
            </div>
        </section>

        <!-- SECTION 2: THE SIMULATOR -->
        <section id="simulator">
            <div class="mb-6">
                <h2 class="text-2xl font-bold text-stone-900">The Paralinguistic Analyzer</h2>
                <p class="text-stone-600 mt-2 max-w-3xl">
                    This interactive tool lets you simulate the "Microphone Analysis" process. By adjusting the three core variables identified in your research—Pitch (Prosody), Speed, and Volume—you can see how an algorithm would classify the speaker's mood.
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8">
                <!-- Controls -->
                <div class="lg:col-span-7 bg-white rounded-xl shadow-sm border border-stone-200 p-6">
                    <h3 class="text-lg font-semibold text-stone-800 mb-6 border-b pb-2">Input Parameters</h3>
                    
                    <!-- Pitch Control -->
                    <div class="mb-8">
                        <div class="flex justify-between mb-2">
                            <label class="font-medium text-stone-700">Tone / Pitch (Prosody)</label>
                            <span id="pitch-val" class="text-sm text-stone-500">Normal</span>
                        </div>
                        <input type="range" id="pitch-slider" min="0" max="100" value="50" class="w-full">
                        <div class="flex justify-between text-xs text-stone-400 mt-2">
                            <span>Low/Monotone</span>
                            <span>High/Varied</span>
                        </div>
                    </div>

                    <!-- Speed Control -->
                    <div class="mb-8">
                        <div class="flex justify-between mb-2">
                            <label class="font-medium text-stone-700">Speech Rate</label>
                            <span id="speed-val" class="text-sm text-stone-500">Conversational</span>
                        </div>
                        <input type="range" id="speed-slider" min="0" max="100" value="50" class="w-full">
                        <div class="flex justify-between text-xs text-stone-400 mt-2">
                            <span>Slow/Slurred</span>
                            <span>Fast/Energetic</span>
                        </div>
                    </div>

                    <!-- Volume Control -->
                    <div class="mb-6">
                        <div class="flex justify-between mb-2">
                            <label class="font-medium text-stone-700">Volume (Intensity)</label>
                            <span id="volume-val" class="text-sm text-stone-500">Moderate</span>
                        </div>
                        <input type="range" id="volume-slider" min="0" max="100" value="50" class="w-full">
                        <div class="flex justify-between text-xs text-stone-400 mt-2">
                            <span>Soft/Quiet</span>
                            <span>Loud</span>
                        </div>
                    </div>
                </div>

                <!-- Output Display -->
                <div class="lg:col-span-5 flex flex-col">
                    <div class="bg-stone-900 text-white rounded-xl shadow-lg p-8 flex-1 flex flex-col justify-center items-center text-center relative overflow-hidden">
                        <div class="absolute top-0 left-0 w-full h-2 bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500"></div>
                        
                        <h4 class="text-stone-400 text-sm uppercase tracking-wider font-semibold mb-4">Detected Mood</h4>
                        
                        <div id="mood-display" class="text-4xl md:text-5xl font-bold mb-4 transition-all duration-300">
                            Neutral
                        </div>
                        
                        <p id="mood-desc" class="text-stone-300 text-sm max-w-xs leading-relaxed">
                            Standard conversational baseline. No extremes detected in acoustic features.
                        </p>

                        <div class="mt-8 flex gap-2">
                            <span id="tag-1" class="px-3 py-1 bg-white/10 rounded-full text-xs hidden">High Energy</span>
                            <span id="tag-2" class="px-3 py-1 bg-white/10 rounded-full text-xs hidden">Variation</span>
                        </div>
                    </div>

                    <!-- Legend / Mini Key -->
                    <div class="mt-4 bg-white p-4 rounded-lg border border-stone-200 text-xs text-stone-600">
                        <strong>Simulation Logic:</strong> <br>
                        • Fast + Loud + High Pitch = Anger/Joy<br>
                        • Slow + Quiet + Low Pitch = Sadness/Boredom<br>
                        • Fast + Varied Pitch = Anxiety/Excitement
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 3: VISUAL PATTERNS -->
        <section id="patterns">
            <div class="mb-6">
                <h2 class="text-2xl font-bold text-stone-900">Acoustic Signatures</h2>
                <p class="text-stone-600 mt-2 max-w-3xl">
                    Research maps emotions to specific geometric "shapes" when plotted on data charts. Below, we compare how three distinct emotions manifest across the four dimensions you provided: Pitch, Speed, Volume, and Clarity.
                </p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Radar Chart Card -->
                <div class="bg-white rounded-xl shadow-sm border border-stone-200 p-6 flex flex-col">
                    <h3 class="text-lg font-semibold text-stone-800 mb-4">The Emotional Footprint (Radar Analysis)</h3>
                    <div class="flex-grow flex items-center justify-center">
                        <div class="chart-container">
                            <canvas id="emotionRadarChart"></canvas>
                        </div>
                    </div>
                    <p class="text-xs text-stone-500 mt-4 text-center">
                        Comparison of Anger, Sadness, and Anxiety across key Prosodic markers.
                    </p>
                </div>

                <!-- Bar Chart Card -->
                <div class="bg-white rounded-xl shadow-sm border border-stone-200 p-6 flex flex-col">
                    <h3 class="text-lg font-semibold text-stone-800 mb-4">Fluency & Hesitation Indicators</h3>
                    <p class="text-sm text-stone-600 mb-4">
                        Analysis of speech disfluency (hesitations like "um", "ah") and rate provides insight into cognitive load and honesty.
                    </p>
                    <div class="flex-grow flex items-center justify-center">
                        <div class="chart-container">
                            <canvas id="fluencyChart"></canvas>
                        </div>
                    </div>
                    <div class="mt-4 grid grid-cols-2 gap-2 text-xs">
                        <div class="p-2 bg-stone-50 rounded">
                            <strong>Nervousness:</strong> High frequency of filler words.
                        </div>
                        <div class="p-2 bg-stone-50 rounded">
                            <strong>Sadness:</strong> Slow rate, long pauses.
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 4: SUMMARY & QUALITY -->
        <section class="bg-indigo-50 rounded-2xl p-8 border border-indigo-100">
            <h2 class="text-xl font-bold text-indigo-900 mb-4">Voice Quality & Nuance</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <div>
                    <h4 class="font-bold text-indigo-800 mb-2">📉 Shaky / Trembling</h4>
                    <p class="text-sm text-indigo-700">
                        Often indicates <strong>Fear</strong> or intense <strong>Sadness</strong>. This is caused by irregular vocal fold vibration due to physiological stress response.
                    </p>
                </div>
                <div>
                    <h4 class="font-bold text-indigo-800 mb-2">⚡ Harsh / Grating</h4>
                    <p class="text-sm text-indigo-700">
                        A strong indicator of <strong>Anger</strong> or <strong>Aggression</strong>. Characterized by high vocal tension and "rough" spectral noise.
                    </p>
                </div>
                <div>
                    <h4 class="font-bold text-indigo-800 mb-2">☁️ Breathy / Soft</h4>
                    <p class="text-sm text-indigo-700">
                        Can indicate <strong>Intimacy</strong>, <strong>Secrecy</strong>, or <strong>Shyness</strong>. In clinical settings, excessive breathiness can also signal fatigue.
                    </p>
                </div>
            </div>
        </section>

    </main>

    <footer class="bg-white border-t border-stone-200 mt-12 py-8">
        <div class="max-w-7xl mx-auto px-4 text-center text-stone-400 text-sm">
            <p>Generated based on provided Paralinguistics source material.</p>
        </div>
    </footer>

    <!-- JAVASCRIPT LOGIC -->
    <script>
        // --- Navigation ---
        function scrollToSection(id) {
            document.getElementById(id).scrollIntoView({ behavior: 'smooth' });
        }

        // --- Simulator Logic ---
        const pitchSlider = document.getElementById('pitch-slider');
        const speedSlider = document.getElementById('speed-slider');
        const volumeSlider = document.getElementById('volume-slider');
        
        const moodDisplay = document.getElementById('mood-display');
        const moodDesc = document.getElementById('mood-desc');
        const tag1 = document.getElementById('tag-1');
        const tag2 = document.getElementById('tag-2');

        const updateMood = () => {
            const p = parseInt(pitchSlider.value); // 0-100
            const s = parseInt(speedSlider.value); // 0-100
            const v = parseInt(volumeSlider.value); // 0-100

            // Text Label Updates
            document.getElementById('pitch-val').textContent = p < 30 ? "Low/Monotone" : p > 70 ? "High/Varied" : "Normal";
            document.getElementById('speed-val').textContent = s < 30 ? "Slow/Slurred" : s > 70 ? "Fast/Energetic" : "Conversational";
            document.getElementById('volume-val').textContent = v < 30 ? "Soft/Quiet" : v > 70 ? "Loud" : "Moderate";

            // Logic Tree for Mood Detection
            // High Energy Cluster
            if (p > 60 && s > 60 && v > 60) {
                moodDisplay.textContent = "Anger / Joy";
                moodDisplay.style.color = "#DC2626"; // Red
                moodDesc.textContent = "High volume, speed, and pitch indicate high arousal. Distinction relies on 'harshness' (Anger) vs 'openness' (Joy).";
            } 
            // Low Energy Cluster
            else if (p < 40 && s < 40 && v < 40) {
                moodDisplay.textContent = "Sadness";
                moodDisplay.style.color = "#4F46E5"; // Indigo
                moodDesc.textContent = "Consistent low pitch, slow rate, and low volume are classic markers of sadness or clinical depression.";
            }
            // Anxiety Cluster
            else if (p > 65 && s > 60) {
                moodDisplay.textContent = "Anxiety / Fear";
                moodDisplay.style.color = "#D97706"; // Amber
                moodDesc.textContent = "Fast speech combined with high, varied pitch suggests nervousness or panic.";
            }
            // Boredom Cluster
            else if (p < 30 && s < 50) {
                moodDisplay.textContent = "Boredom";
                moodDisplay.style.color = "#6B7280"; // Gray
                moodDesc.textContent = "Monotone (low pitch variation) combined with slow delivery.";
            }
            // Secrecy/Intimacy
            else if (v < 30 && p < 60) {
                moodDisplay.textContent = "Secrecy / Intimacy";
                moodDisplay.style.color = "#9333EA"; // Purple
                moodDesc.textContent = "Low volume suggests a desire to exclude others or create closeness.";
            }
            // Baseline
            else {
                moodDisplay.textContent = "Neutral / Mixed";
                moodDisplay.style.color = "#1F2937"; // Dark Gray
                moodDesc.textContent = "Parameters are within standard conversational ranges or conflicting.";
            }
        };

        pitchSlider.addEventListener('input', updateMood);
        speedSlider.addEventListener('input', updateMood);
        volumeSlider.addEventListener('input', updateMood);

        // --- Chart.js Implementations ---

        // 1. Radar Chart (Comparison)
        const radarCtx = document.getElementById('emotionRadarChart').getContext('2d');
        new Chart(radarCtx, {
            type: 'radar',
            data: {
                labels: ['Pitch (Tone)', 'Speed (Rate)', 'Volume', 'Variability'],
                datasets: [
                    {
                        label: 'Anger',
                        data: [80, 90, 95, 70],
                        backgroundColor: 'rgba(220, 38, 38, 0.2)',
                        borderColor: 'rgba(220, 38, 38, 1)',
                        borderWidth: 2
                    },
                    {
                        label: 'Sadness',
                        data: [20, 20, 25, 10],
                        backgroundColor: 'rgba(79, 70, 229, 0.2)',
                        borderColor: 'rgba(79, 70, 229, 1)',
                        borderWidth: 2
                    },
                    {
                        label: 'Anxiety',
                        data: [90, 85, 50, 90], // High pitch, fast, but not necessarily loud, very shaky
                        backgroundColor: 'rgba(217, 119, 6, 0.2)',
                        borderColor: 'rgba(217, 119, 6, 1)',
                        borderWidth: 2
                    }
                ]
            },
            options: {
                maintainAspectRatio: false,
                scales: {
                    r: {
                        angleLines: { color: '#E5E7EB' },
                        grid: { color: '#E5E7EB' },
                        pointLabels: {
                            font: { size: 12, family: 'Inter' }
                        },
                        suggestedMin: 0,
                        suggestedMax: 100
                    }
                },
                plugins: {
                    legend: { position: 'bottom' }
                }
            }
        });

        // 2. Bar Chart (Fluency)
        const fluencyCtx = document.getElementById('fluencyChart').getContext('2d');
        new Chart(fluencyCtx, {
            type: 'bar',
            data: {
                labels: ['Nervousness', 'Deception', 'Excitement', 'Fatigue'],
                datasets: [{
                    label: 'Likelihood of Hesitations ("Ums", "Ahs")',
                    data: [90, 85, 30, 40],
                    backgroundColor: [
                        'rgba(217, 119, 6, 0.7)',  // Orange
                        'rgba(220, 38, 38, 0.7)',  // Red
                        'rgba(16, 185, 129, 0.7)', // Green
                        'rgba(107, 114, 128, 0.7)' // Gray
                    ],
                    borderWidth: 0,
                    borderRadius: 4
                }]
            },
            options: {
                indexAxis: 'y', // Horizontal bar chart
                maintainAspectRatio: false,
                scales: {
                    x: {
                        grid: { display: false },
                        max: 100,
                        title: { display: true, text: 'Frequency of Disfluency (%)' }
                    },
                    y: {
                        grid: { display: false }
                    }
                },
                plugins: {
                    legend: { display: false },
                    tooltip: {
                        callbacks: {
                            label: function(context) {
                                return context.raw + '% Frequency';
                            }
                        }
                    }
                }
            }
        });

    </script>
</body>
</html>
