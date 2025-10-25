<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Enhanced Random Generator</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', 'Microsoft YaHei', sans-serif;
        }
        
        :root {
            --primary: #4361ee;
            --secondary: #3a0ca3;
            --accent: #4cc9f0;
            --success: #4ade80;
            --warning: #f59e0b;
            --danger: #ef4444;
            --light: #f8fafc;
            --dark: #1e293b;
            --gray: #64748b;
            --bg-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            --card-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            --hover-shadow: 0 15px 40px rgba(0, 0, 0, 0.15);
        }
        
        /* Dark theme variables */
        .dark-theme {
            --primary: #5b6bf0;
            --secondary: #4c1d95;
            --accent: #60d9f0;
            --success: #5ae68a;
            --warning: #f7b955;
            --danger: #f87171;
            --light: #1e293b;
            --dark: #f1f5f9;
            --gray: #94a3b8;
            --bg-gradient: linear-gradient(135deg, #1e293b 0%, #334155 100%);
            --card-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
            --hover-shadow: 0 15px 40px rgba(0, 0, 0, 0.4);
        }
        
        body {
            background: var(--bg-gradient);
            color: var(--dark);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
            line-height: 1.6;
            transition: all 0.3s ease;
        }
        
        .container {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(20px);
            border-radius: 24px;
            box-shadow: 
                0 25px 50px -12px rgba(0, 0, 0, 0.25),
                inset 0 1px 0 rgba(255, 255, 255, 0.3);
            padding: 40px;
            max-width: 1000px;
            width: 100%;
            border: 1px solid rgba(255, 255, 255, 0.2);
            position: relative;
            overflow: hidden;
            animation: fadeIn 0.8s ease-out;
            transition: all 0.3s ease;
        }
        
        .dark-theme .container {
            background: rgba(30, 41, 59, 0.95);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .container::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 4px;
            background: linear-gradient(90deg, 
                var(--primary), 
                var(--accent), 
                var(--success), 
                var(--warning));
            border-radius: 24px 24px 0 0;
        }
        
        header {
            text-align: center;
            margin-bottom: 30px;
            position: relative;
        }
        
        .logo {
            width: 80px;
            height: 80px;
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            border-radius: 50%;
            margin: 0 auto 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 8px 25px rgba(67, 97, 238, 0.3);
            animation: floating 3s ease-in-out infinite;
        }
        
        @keyframes floating {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }
        
        .logo i {
            font-size: 2rem;
            color: white;
        }
        
        h1 {
            color: var(--dark);
            font-size: 2.5rem;
            font-weight: 700;
            margin-bottom: 10px;
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        
        .subtitle {
            color: var(--gray);
            font-size: 1.1rem;
            font-weight: 400;
        }
        
        .top-controls {
            display: flex;
            justify-content: space-between;
            margin-bottom: 20px;
            flex-wrap: wrap;
            gap: 15px;
        }
        
        .theme-toggle, .language-toggle {
            display: flex;
            align-items: center;
            gap: 10px;
            background: var(--light);
            border-radius: 50px;
            padding: 10px 20px;
            box-shadow: var(--card-shadow);
            border: 1px solid rgba(255, 255, 255, 0.5);
            cursor: pointer;
            transition: all 0.3s ease;
        }
        
        .dark-theme .theme-toggle, .dark-theme .language-toggle {
            background: #334155;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .theme-toggle:hover, .language-toggle:hover {
            transform: translateY(-2px);
            box-shadow: var(--hover-shadow);
        }
        
        .theme-toggle i, .language-toggle i {
            color: var(--primary);
        }
        
        .function-tabs {
            display: flex;
            justify-content: center;
            margin-bottom: 30px;
            gap: 10px;
            flex-wrap: wrap;
        }
        
        .tab-btn {
            padding: 12px 24px;
            background: var(--light);
            border: none;
            border-radius: 8px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
            color: var(--gray);
        }
        
        .dark-theme .tab-btn {
            background: #334155;
        }
        
        .tab-btn.active {
            background: var(--primary);
            color: white;
        }
        
        .tab-content {
            display: none;
        }
        
        .tab-content.active {
            display: block;
        }
        
        .range-controls {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-bottom: 30px;
            flex-wrap: wrap;
        }
        
        .range-input {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 10px;
        }
        
        .range-input label {
            font-weight: 600;
            color: var(--dark);
        }
        
        .range-input input {
            padding: 12px 16px;
            border: 2px solid var(--gray);
            border-radius: 12px;
            font-size: 1.1rem;
            width: 140px;
            text-align: center;
            transition: all 0.3s ease;
            background: var(--light);
            color: var(--dark);
        }
        
        .range-input input:focus {
            outline: none;
            border-color: var(--primary);
            box-shadow: 0 0 0 3px rgba(67, 97, 238, 0.2);
        }
        
        .control-panel {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-bottom: 30px;
            flex-wrap: wrap;
        }
        
        .btn {
            padding: 16px 32px;
            border: none;
            border-radius: 50px;
            font-size: 1.1rem;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            display: flex;
            align-items: center;
            gap: 12px;
            box-shadow: var(--card-shadow);
            position: relative;
            overflow: hidden;
        }
        
        .btn::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.4), transparent);
            transition: 0.5s;
        }
        
        .btn:hover::before {
            left: 100%;
        }
        
        .btn-primary {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
        }
        
        .btn-secondary {
            background: linear-gradient(135deg, var(--gray), #475569);
            color: white;
        }
        
        .btn:hover {
            transform: translateY(-3px);
            box-shadow: var(--hover-shadow);
        }
        
        .btn:active {
            transform: translateY(-1px);
        }
        
        .result-section {
            background: var(--light);
            border-radius: 20px;
            padding: 30px;
            margin-bottom: 30px;
            box-shadow: 
                inset 0 2px 4px rgba(0, 0, 0, 0.05),
                0 4px 20px rgba(0, 0, 0, 0.08);
            border: 1px solid rgba(255, 255, 255, 0.5);
            transition: all 0.3s ease;
            text-align: center;
        }
        
        .dark-theme .result-section {
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .result-section:hover {
            box-shadow: 
                inset 0 2px 4px rgba(0, 0, 0, 0.05),
                0 6px 25px rgba(0, 0, 0, 0.12);
        }
        
        .result-title {
            font-size: 1.2rem;
            font-weight: 600;
            color: var(--dark);
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }
        
        .result-display {
            font-size: 4rem;
            font-weight: 700;
            color: var(--primary);
            text-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin: 20px 0;
            transition: all 0.3s ease;
            min-height: 80px;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .color-result {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin: 20px auto;
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.2);
            transition: all 0.3s ease;
        }
        
        .color-result:hover {
            transform: scale(1.05);
        }
        
        .batch-result {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(80px, 1fr));
            gap: 15px;
            margin-top: 20px;
            max-height: 200px;
            overflow-y: auto;
            padding: 10px;
        }
        
        .batch-number {
            background: var(--primary);
            color: white;
            border-radius: 8px;
            padding: 12px;
            text-align: center;
            font-weight: 600;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease;
        }
        
        .batch-number:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
        }
        
        .string-result {
            font-family: 'Courier New', monospace;
            font-size: 1.5rem;
            font-weight: 600;
            color: var(--primary);
            margin: 20px 0;
            padding: 15px;
            background: rgba(67, 97, 238, 0.1);
            border-radius: 12px;
            word-break: break-all;
        }
        
        .history-section {
            background: var(--light);
            border-radius: 20px;
            padding: 25px;
            box-shadow: var(--card-shadow);
            border: 1px solid rgba(255, 255, 255, 0.5);
            transition: all 0.3s ease;
        }
        
        .dark-theme .history-section {
            background: #1e293b;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .history-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
            padding-bottom: 15px;
            border-bottom: 2px solid rgba(0, 0, 0, 0.1);
        }
        
        .dark-theme .history-header {
            border-bottom: 2px solid rgba(255, 255, 255, 0.1);
        }
        
        .history-title {
            font-size: 1.4rem;
            font-weight: 600;
            color: var(--dark);
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .history-list {
            max-height: 200px;
            overflow-y: auto;
            padding-right: 10px;
        }
        
        .history-item {
            background: white;
            border-radius: 12px;
            padding: 15px;
            margin-bottom: 15px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
            border-left: 4px solid var(--primary);
            transition: all 0.3s ease;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .dark-theme .history-item {
            background: #334155;
        }
        
        .history-item:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.1);
        }
        
        .history-number {
            font-size: 1.5rem;
            font-weight: 700;
            color: var(--primary);
        }
        
        .history-range {
            font-size: 0.9rem;
            color: var(--gray);
        }
        
        .history-time {
            font-size: 0.8rem;
            color: var(--gray);
        }
        
        .no-history {
            text-align: center;
            padding: 20px;
            color: var(--gray);
            font-style: italic;
        }
        
        .success-message {
            position: fixed;
            top: 20px;
            right: 20px;
            background: var(--success);
            color: white;
            padding: 15px 25px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
            transform: translateX(400px);
            transition: transform 0.3s ease;
            z-index: 1000;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .success-message.show {
            transform: translateX(0);
        }
        
        footer {
            margin-top: 30px;
            text-align: center;
            color: var(--gray);
            padding-top: 25px;
            border-top: 1px solid rgba(0, 0, 0, 0.1);
        }
        
        .dark-theme footer {
            border-top: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .footer-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 15px;
        }
        
        .version {
            background: var(--light);
            padding: 8px 16px;
            border-radius: 20px;
            font-size: 0.9rem;
            font-weight: 500;
        }
        
        .dark-theme .version {
            background: #334155;
        }
        
        @media (max-width: 768px) {
            .container {
                padding: 25px;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            .range-controls {
                flex-direction: column;
                align-items: center;
            }
            
            .control-panel {
                flex-direction: column;
                align-items: center;
            }
            
            .btn {
                width: 100%;
                max-width: 300px;
                justify-content: center;
            }
            
            .result-display {
                font-size: 3rem;
            }
            
            .footer-content {
                flex-direction: column;
                text-align: center;
            }
        }
        
        @media (max-width: 480px) {
            .container {
                padding: 20px;
            }
            
            h1 {
                font-size: 1.8rem;
            }
            
            .result-display {
                font-size: 2.5rem;
            }
        }
        
        /* Particles background effect */
        .particles {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            overflow: hidden;
        }
        
        .particle {
            position: absolute;
            background: rgba(255, 255, 255, 0.2);
            border-radius: 50%;
            animation: float 15s infinite linear;
        }
        
        @keyframes float {
            0% {
                transform: translateY(100vh) rotate(0deg);
                opacity: 0;
            }
            10% {
                opacity: 1;
            }
            90% {
                opacity: 1;
            }
            100% {
                transform: translateY(-100px) rotate(360deg);
                opacity: 0;
            }
        }
        
        /* Decorative border */
        .decorative-border {
            position: absolute;
            top: 10px;
            left: 10px;
            right: 10px;
            bottom: 10px;
            border: 2px dashed rgba(67, 97, 238, 0.2);
            border-radius: 20px;
            pointer-events: none;
        }
        
        /* Dynamic background pattern */
        .bg-pattern {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: 
                radial-gradient(circle at 10% 20%, rgba(67, 97, 238, 0.05) 0%, transparent 20%),
                radial-gradient(circle at 90% 80%, rgba(76, 201, 240, 0.05) 0%, transparent 20%),
                radial-gradient(circle at 50% 50%, rgba(74, 222, 128, 0.05) 0%, transparent 30%);
            z-index: -1;
        }
        
        /* Decorative stars */
        .decoration-star {
            position: absolute;
            color: rgba(255, 255, 255, 0.7);
            font-size: 1.2rem;
            animation: twinkle 3s infinite alternate;
        }
        
        @keyframes twinkle {
            0% { opacity: 0.3; transform: scale(0.8); }
            100% { opacity: 1; transform: scale(1.2); }
        }
        
        /* Time display */
        .time-display {
            position: absolute;
            top: 20px;
            left: 20px;
            background: rgba(255, 255, 255, 0.2);
            backdrop-filter: blur(10px);
            padding: 10px 15px;
            border-radius: 10px;
            font-size: 0.9rem;
            color: var(--dark);
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            border: 1px solid rgba(255, 255, 255, 0.3);
        }
        
        .dark-theme .time-display {
            background: rgba(30, 41, 59, 0.5);
            color: var(--dark);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        /* Progress bar */
        .progress-bar {
            height: 6px;
            background: rgba(67, 97, 238, 0.2);
            border-radius: 3px;
            overflow: hidden;
            margin-top: 15px;
            display: none;
        }
        
        .progress-fill {
            height: 100%;
            background: linear-gradient(90deg, var(--primary), var(--accent));
            width: 0%;
            transition: width 0.5s ease;
            border-radius: 3px;
        }
        
        /* Additional controls */
        .additional-controls {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-bottom: 30px;
            flex-wrap: wrap;
        }
        
        .additional-input {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 10px;
        }
        
        .additional-input label {
            font-weight: 600;
            color: var(--dark);
        }
        
        .additional-input input, .additional-input select {
            padding: 12px 16px;
            border: 2px solid var(--gray);
            border-radius: 12px;
            font-size: 1.1rem;
            width: 180px;
            text-align: center;
            transition: all 0.3s ease;
            background: var(--light);
            color: var(--dark);
        }
        
        .additional-input input:focus, .additional-input select:focus {
            outline: none;
            border-color: var(--primary);
            box-shadow: 0 0 0 3px rgba(67, 97, 238, 0.2);
        }
    </style>
</head>
<body>
    <!-- Particles background -->
    <div class="particles" id="particles"></div>
    
    <!-- Dynamic background pattern -->
    <div class="bg-pattern"></div>
    
    <!-- Decorative stars -->
    <div class="decoration-star" style="top: 10%; left: 5%;"><i class="fas fa-star"></i></div>
    <div class="decoration-star" style="top: 15%; right: 10%;"><i class="fas fa-star"></i></div>
    <div class="decoration-star" style="bottom: 20%; left: 15%;"><i class="fas fa-star"></i></div>
    <div class="decoration-star" style="bottom: 10%; right: 5%;"><i class="fas fa-star"></i></div>
    
    <div class="container">
        <!-- Time display -->
        <div class="time-display" id="timeDisplay"></div>
        
        <!-- Decorative border -->
        <div class="decorative-border"></div>
        
        <header>
            <div class="logo">
                <i class="fas fa-dice"></i>
            </div>
            <h1 id="pageTitle">Enhanced Random Generator</h1>
            <p class="subtitle" id="pageSubtitle">Multiple randomization functions in one tool</p>
        </header>
        
        <!-- Top controls -->
        <div class="top-controls">
            <div class="language-toggle" id="languageToggle">
                <i class="fas fa-globe"></i>
                <span id="languageText">中文</span>
            </div>
            <div class="theme-toggle" id="themeToggle">
                <i class="fas fa-moon"></i>
                <span id="themeText">Dark Mode</span>
            </div>
        </div>
        
        <!-- Function tabs -->
        <div class="function-tabs">
            <button class="tab-btn active" onclick="switchTab('number')">
                <i class="fas fa-hashtag"></i>
                <span id="numberTab">Single Number</span>
            </button>
            <button class="tab-btn" onclick="switchTab('batch')">
                <i class="fas fa-list"></i>
                <span id="batchTab">Batch Numbers</span>
            </button>
            <button class="tab-btn" onclick="switchTab('color')">
                <i class="fas fa-palette"></i>
                <span id="colorTab">Random Color</span>
            </button>
            <button class="tab-btn" onclick="switchTab('string')">
                <i class="fas fa-font"></i>
                <span id="stringTab">Random String</span>
            </button>
        </div>
        
        <!-- Single Number Tab -->
        <div class="tab-content active" id="number-tab">
            <!-- Range controls -->
            <div class="range-controls">
                <div class="range-input">
                    <label for="minValue" id="minLabel">Minimum</label>
                    <input type="number" id="minValue" value="1" min="-999999" max="999999">
                </div>
                <div class="range-input">
                    <label for="maxValue" id="maxLabel">Maximum</label>
                    <input type="number" id="maxValue" value="100" min="-999999" max="999999">
                </div>
            </div>
            
            <!-- Control panel -->
            <div class="control-panel">
                <button class="btn btn-primary" onclick="generateRandomNumber()">
                    <i class="fas fa-random"></i>
                    <span id="generateBtn">Generate Random Number</span>
                </button>
            </div>
            
            <!-- Result display -->
            <div class="result-section">
                <div class="result-title">
                    <i class="fas fa-bullseye"></i>
                    <span id="resultTitle">Generated Random Number</span>
                </div>
                <div class="result-display" id="resultDisplay">
                    Waiting for generation...
                </div>
            </div>
        </div>
        
        <!-- Batch Numbers Tab -->
        <div class="tab-content" id="batch-tab">
            <!-- Range controls -->
            <div class="range-controls">
                <div class="range-input">
                    <label for="batchMinValue">Minimum</label>
                    <input type="number" id="batchMinValue" value="1" min="-999999" max="999999">
                </div>
                <div class="range-input">
                    <label for="batchMaxValue">Maximum</label>
                    <input type="number" id="batchMaxValue" value="100" min="-999999" max="999999">
                </div>
                <div class="range-input">
                    <label for="batchCount">Count</label>
                    <input type="number" id="batchCount" value="10" min="1" max="100">
                </div>
            </div>
            
            <!-- Control panel -->
            <div class="control-panel">
                <button class="btn btn-primary" onclick="generateBatchNumbers()">
                    <i class="fas fa-random"></i>
                    <span id="batchGenerateBtn">Generate Batch Numbers</span>
                </button>
            </div>
            
            <!-- Result display -->
            <div class="result-section">
                <div class="result-title">
                    <i class="fas fa-list"></i>
                    <span id="batchResultTitle">Generated Batch Numbers</span>
                </div>
                <div class="batch-result" id="batchResultDisplay">
                    <!-- Batch numbers will be displayed here -->
                </div>
            </div>
        </div>
        
        <!-- Random Color Tab -->
        <div class="tab-content" id="color-tab">
            <!-- Additional controls -->
            <div class="additional-controls">
                <div class="additional-input">
                    <label for="colorFormat">Color Format</label>
                    <select id="colorFormat">
                        <option value="hex">HEX</option>
                        <option value="rgb">RGB</option>
                        <option value="hsl">HSL</option>
                    </select>
                </div>
            </div>
            
            <!-- Control panel -->
            <div class="control-panel">
                <button class="btn btn-primary" onclick="generateRandomColor()">
                    <i class="fas fa-random"></i>
                    <span id="colorGenerateBtn">Generate Random Color</span>
                </button>
            </div>
            
            <!-- Result display -->
            <div class="result-section">
                <div class="result-title">
                    <i class="fas fa-palette"></i>
                    <span id="colorResultTitle">Generated Random Color</span>
                </div>
                <div class="color-result" id="colorResultDisplay">
                    <!-- Color will be displayed here -->
                </div>
                <div class="result-display" id="colorValueDisplay">
                    Waiting for generation...
                </div>
            </div>
        </div>
        
        <!-- Random String Tab -->
        <div class="tab-content" id="string-tab">
            <!-- Additional controls -->
            <div class="additional-controls">
                <div class="additional-input">
                    <label for="stringLength">Length</label>
                    <input type="number" id="stringLength" value="10" min="1" max="100">
                </div>
                <div class="additional-input">
                    <label for="stringType">Character Set</label>
                    <select id="stringType">
                        <option value="alphanumeric">Alphanumeric</option>
                        <option value="alphabetic">Alphabetic</option>
                        <option value="numeric">Numeric</option>
                        <option value="symbols">Symbols</option>
                        <option value="all">All Characters</option>
                    </select>
                </div>
            </div>
            
            <!-- Control panel -->
            <div class="control-panel">
                <button class="btn btn-primary" onclick="generateRandomString()">
                    <i class="fas fa-random"></i>
                    <span id="stringGenerateBtn">Generate Random String</span>
                </button>
            </div>
            
            <!-- Result display -->
            <div class="result-section">
                <div class="result-title">
                    <i class="fas fa-font"></i>
                    <span id="stringResultTitle">Generated Random String</span>
                </div>
                <div class="string-result" id="stringResultDisplay">
                    Waiting for generation...
                </div>
            </div>
        </div>
        
        <!-- History section -->
        <div class="history-section">
            <div class="history-header">
                <div class="history-title">
                    <i class="fas fa-history"></i>
                    <span id="historyTitle">Generation History</span>
                </div>
                <button class="btn btn-secondary" onclick="clearHistory()">
                    <i class="fas fa-trash"></i>
                    <span id="clearBtn">Clear History</span>
                </button>
            </div>
            <div class="history-list" id="historyList">
                <div class="no-history" id="noHistoryText">No generation records yet</div>
            </div>
        </div>
        
        <footer>
            <div class="footer-content">
                <div>
                    <p id="footerText">© 2023 Enhanced Random Generator | Multiple randomization functions</p>
                </div>
                <div class="version">
                    <i class="fas fa-code"></i> <span id="versionText">Version 2.0.0</span>
                </div>
            </div>
        </footer>
    </div>

    <div class="success-message" id="successMessage">
        <i class="fas fa-check-circle"></i> <span id="successText">Random generation completed successfully!</span>
    </div>

    <script>
        // Language resources
        const resources = {
            en: {
                pageTitle: "Some useful random number tools.",
                pageSubtitle: "Multiple randomization functions in one tool",
                minLabel: "Minimum",
                maxLabel: "Maximum",
                generateBtn: "Generate Random Number",
                batchGenerateBtn: "Generate Batch Numbers",
                colorGenerateBtn: "Generate Random Color",
                stringGenerateBtn: "Generate Random String",
                clearBtn: "Clear History",
                resultTitle: "Generated Random Number",
                batchResultTitle: "Generated Batch Numbers",
                colorResultTitle: "Generated Random Color",
                stringResultTitle: "Generated Random String",
                historyTitle: "Generation History",
                noHistoryText: "No generation records yet",
                footerText: "© Some useful random number tools. | Multiple randomization functions",
                versionText: "Version 2.0.12,Made by wrh316",
                successText: "Random generation completed successfully!",
                waitingText: "Waiting for generation...",
                generatingText: "Generating...",
                rangeError: "Minimum must be less than maximum",
                languageText: "中文",
                themeText: "Dark Mode",
                lightThemeText: "Light Mode",
                numberTab: "Single Number",
                batchTab: "Batch Numbers",
                colorTab: "Random Color",
                stringTab: "Random String"
            },
            zh: {
                pageTitle: "一些有用的随机数工具",
                pageSubtitle: "多种随机化功能",
                minLabel: "最小值",
                maxLabel: "最大值",
                generateBtn: "生成随机数",
                batchGenerateBtn: "生成批量数字",
                colorGenerateBtn: "生成随机颜色",
                stringGenerateBtn: "生成随机字符串",
                clearBtn: "清空历史",
                resultTitle: "生成的随机数",
                batchResultTitle: "生成的批量数字",
                colorResultTitle: "生成的随机颜色",
                stringResultTitle: "生成的随机字符串",
                historyTitle: "生成历史",
                noHistoryText: "暂无生成记录",
                footerText: "© 一些有用的随机数工具 | 多种随机化功能",
                versionText: "版本 2.0.12，作者：wrh316",
                successText: "随机生成成功完成！",
                waitingText: "等待生成...",
                generatingText: "生成中...",
                rangeError: "最小值必须小于最大值",
                languageText: "English",
                themeText: "深色模式",
                lightThemeText: "浅色模式",
                numberTab: "单个数字",
                batchTab: "批量数字",
                colorTab: "随机颜色",
                stringTab: "随机字符串"
            }
        };

        // Global variables
        let history = JSON.parse(localStorage.getItem('randomHistory')) || [];
        let isDarkTheme = localStorage.getItem('darkTheme') === 'true';
        let currentLanguage = localStorage.getItem('language') || 'en';
        
        // Initialize app
        function initializeApp() {
            // Set theme
            if (isDarkTheme) {
                document.body.classList.add('dark-theme');
                updateThemeText();
            }
            
            // Set language
            setLanguage(currentLanguage);
            
            // Update clock
            updateClock();
            setInterval(updateClock, 1000);
            
            // Create particles background
            createParticles();
            
            // Render history
            renderHistory();
            
            // Add event listeners
            document.getElementById('themeToggle').addEventListener('click', toggleTheme);
            document.getElementById('languageToggle').addEventListener('click', toggleLanguage);
            
            // Validate range on input change
            document.getElementById('minValue').addEventListener('change', validateRange);
            document.getElementById('maxValue').addEventListener('change', validateRange);
        }
        
        // Set language
        function setLanguage(lang) {
            currentLanguage = lang;
            localStorage.setItem('language', lang);
            
            const resource = resources[lang];
            
            // Update all text elements
            document.getElementById('pageTitle').textContent = resource.pageTitle;
            document.getElementById('pageSubtitle').textContent = resource.pageSubtitle;
            document.getElementById('minLabel').textContent = resource.minLabel;
            document.getElementById('maxLabel').textContent = resource.maxLabel;
            document.getElementById('generateBtn').textContent = resource.generateBtn;
            document.getElementById('batchGenerateBtn').textContent = resource.batchGenerateBtn;
            document.getElementById('colorGenerateBtn').textContent = resource.colorGenerateBtn;
            document.getElementById('stringGenerateBtn').textContent = resource.stringGenerateBtn;
            document.getElementById('clearBtn').textContent = resource.clearBtn;
            document.getElementById('resultTitle').textContent = resource.resultTitle;
            document.getElementById('batchResultTitle').textContent = resource.batchResultTitle;
            document.getElementById('colorResultTitle').textContent = resource.colorResultTitle;
            document.getElementById('stringResultTitle').textContent = resource.stringResultTitle;
            document.getElementById('historyTitle').textContent = resource.historyTitle;
            document.getElementById('noHistoryText').textContent = resource.noHistoryText;
            document.getElementById('footerText').textContent = resource.footerText;
            document.getElementById('versionText').textContent = resource.versionText;
            document.getElementById('successText').textContent = resource.successText;
            document.getElementById('languageText').textContent = resource.languageText;
            document.getElementById('numberTab').textContent = resource.numberTab;
            document.getElementById('batchTab').textContent = resource.batchTab;
            document.getElementById('colorTab').textContent = resource.colorTab;
            document.getElementById('stringTab').textContent = resource.stringTab;
            
            // Update result display if it's the default text
            const resultDisplay = document.getElementById('resultDisplay');
            if (resultDisplay.textContent === "Waiting for generation..." || 
                resultDisplay.textContent === "等待生成...") {
                resultDisplay.textContent = resource.waitingText;
            }
            
            // Update theme text
            updateThemeText();
            
            // Re-render history to update language
            renderHistory();
        }
        
        // Toggle language
        function toggleLanguage() {
            const newLanguage = currentLanguage === 'en' ? 'zh' : 'en';
            setLanguage(newLanguage);
        }
        
        // Switch tabs
        function switchTab(tabName) {
            // Remove active class from all tabs
            document.querySelectorAll('.tab-content').forEach(tab => {
                tab.classList.remove('active');
            });
            document.querySelectorAll('.tab-btn').forEach(btn => {
                btn.classList.remove('active');
            });
            
            // Add active class to selected tab
            document.getElementById(`${tabName}-tab`).classList.add('active');
            event.target.classList.add('active');
        }
        
        // Create particles background
        function createParticles() {
            const particlesContainer = document.getElementById('particles');
            const particleCount = 30;
            
            for (let i = 0; i < particleCount; i++) {
                const particle = document.createElement('div');
                particle.classList.add('particle');
                
                // Random size
                const size = Math.random() * 10 + 5;
                particle.style.width = `${size}px`;
                particle.style.height = `${size}px`;
                
                // Random position
                particle.style.left = `${Math.random() * 100}%`;
                
                // Random animation delay
                particle.style.animationDelay = `${Math.random() * 15}s`;
                
                // Random animation duration
                const duration = Math.random() * 10 + 10;
                particle.style.animationDuration = `${duration}s`;
                
                particlesContainer.appendChild(particle);
            }
        }
        
        // Generate secure random number using Crypto API
        function getSecureRandomNumber(min, max) {
            const range = max - min + 1;
            const randomBuffer = new Uint32Array(1);
            window.crypto.getRandomValues(randomBuffer);
            return min + (randomBuffer[0] % range);
        }
        
        // Generate random number
        function generateRandomNumber() {
            const minInput = document.getElementById('minValue');
            const maxInput = document.getElementById('maxValue');
            const resultDisplay = document.getElementById('resultDisplay');
            
            const min = parseInt(minInput.value);
            const max = parseInt(maxInput.value);
            
            // Validate range
            if (min >= max) {
                showError(resources[currentLanguage].rangeError);
                return;
            }
            
            // Show loading animation
            resultDisplay.textContent = resources[currentLanguage].generatingText;
            resultDisplay.style.color = "var(--gray)";
            
            // Delay generation to show loading effect
            setTimeout(() => {
                const randomNumber = getSecureRandomNumber(min, max);
                
                // Display result
                resultDisplay.textContent = randomNumber;
                resultDisplay.style.color = "var(--primary)";
                
                // Add animation effect
                resultDisplay.style.transform = "scale(1.1)";
                setTimeout(() => {
                    resultDisplay.style.transform = "scale(1)";
                }, 300);
                
                // Save to history
                saveToHistory(randomNumber, min, max);
                
                // Show success message
                showSuccessMessage();
            }, 500);
        }
        
        // Generate batch numbers
        function generateBatchNumbers() {
            const minInput = document.getElementById('batchMinValue');
            const maxInput = document.getElementById('batchMaxValue');
            const countInput = document.getElementById('batchCount');
            const resultDisplay = document.getElementById('batchResultDisplay');
            
            const min = parseInt(minInput.value);
            const max = parseInt(maxInput.value);
            const count = parseInt(countInput.value);
            
            // Validate range
            if (min >= max) {
                showError(resources[currentLanguage].rangeError);
                return;
            }
            
            // Validate count
            if (count < 1 || count > 100) {
                showError("Count must be between 1 and 100");
                return;
            }
            
            // Clear previous results
            resultDisplay.innerHTML = '';
            
            // Generate batch numbers
            const numbers = [];
            for (let i = 0; i < count; i++) {
                numbers.push(getSecureRandomNumber(min, max));
            }
            
            // Display results
            numbers.forEach(number => {
                const numberElement = document.createElement('div');
                numberElement.className = 'batch-number';
                numberElement.textContent = number;
                resultDisplay.appendChild(numberElement);
            });
            
            // Save to history
            saveToHistory(`Batch: ${numbers.join(', ')}`, min, max);
            
            // Show success message
            showSuccessMessage();
        }
        
        // Generate random color
        function generateRandomColor() {
            const formatSelect = document.getElementById('colorFormat');
            const colorDisplay = document.getElementById('colorResultDisplay');
            const valueDisplay = document.getElementById('colorValueDisplay');
            
            const format = formatSelect.value;
            
            // Generate random RGB values
            const r = getSecureRandomNumber(0, 255);
            const g = getSecureRandomNumber(0, 255);
            const b = getSecureRandomNumber(0, 255);
            
            let colorValue;
            
            // Format color based on selection
            switch(format) {
                case 'hex':
                    colorValue = `#${r.toString(16).padStart(2, '0')}${g.toString(16).padStart(2, '0')}${b.toString(16).padStart(2, '0')}`;
                    break;
                case 'rgb':
                    colorValue = `rgb(${r}, ${g}, ${b})`;
                    break;
                case 'hsl':
                    // Convert RGB to HSL
                    const hsl = rgbToHsl(r, g, b);
                    colorValue = `hsl(${Math.round(hsl.h)}, ${Math.round(hsl.s)}%, ${Math.round(hsl.l)}%)`;
                    break;
            }
            
            // Display color
            colorDisplay.style.backgroundColor = `rgb(${r}, ${g}, ${b})`;
            valueDisplay.textContent = colorValue;
            valueDisplay.style.color = `rgb(${r}, ${g}, ${b})`;
            
            // Save to history
            saveToHistory(colorValue, 0, 0);
            
            // Show success message
            showSuccessMessage();
        }
        
        // Convert RGB to HSL
        function rgbToHsl(r, g, b) {
            r /= 255;
            g /= 255;
            b /= 255;
            
            const max = Math.max(r, g, b);
            const min = Math.min(r, g, b);
            let h, s, l = (max + min) / 2;
            
            if (max === min) {
                h = s = 0; // achromatic
            } else {
                const d = max - min;
                s = l > 0.5 ? d / (2 - max - min) : d / (max + min);
                
                switch (max) {
                    case r: h = (g - b) / d + (g < b ? 6 : 0); break;
                    case g: h = (b - r) / d + 2; break;
                    case b: h = (r - g) / d + 4; break;
                }
                
                h /= 6;
            }
            
            return {
                h: h * 360,
                s: s * 100,
                l: l * 100
            };
        }
        
        // Generate random string
        function generateRandomString() {
            const lengthInput = document.getElementById('stringLength');
            const typeSelect = document.getElementById('stringType');
            const resultDisplay = document.getElementById('stringResultDisplay');
            
            const length = parseInt(lengthInput.value);
            const type = typeSelect.value;
            
            // Validate length
            if (length < 1 || length > 100) {
                showError("Length must be between 1 and 100");
                return;
            }
            
            // Define character sets
            const charSets = {
                alphanumeric: 'ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789',
                alphabetic: 'ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz',
                numeric: '0123456789',
                symbols: '!@#$%^&*()_+-=[]{}|;:,.<>?',
                all: 'ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789!@#$%^&*()_+-=[]{}|;:,.<>?'
            };
            
            const charset = charSets[type];
            let result = '';
            
            // Generate random string
            for (let i = 0; i < length; i++) {
                const randomIndex = getSecureRandomNumber(0, charset.length - 1);
                result += charset[randomIndex];
            }
            
            // Display result
            resultDisplay.textContent = result;
            
            // Save to history
            saveToHistory(`String: ${result}`, 0, 0);
            
            // Show success message
            showSuccessMessage();
        }
        
        // Validate range
        function validateRange() {
            const minInput = document.getElementById('minValue');
            const maxInput = document.getElementById('maxValue');
            
            const min = parseInt(minInput.value);
            const max = parseInt(maxInput.value);
            
            if (min >= max) {
                minInput.style.borderColor = "var(--danger)";
                maxInput.style.borderColor = "var(--danger)";
            } else {
                minInput.style.borderColor = "var(--gray)";
                maxInput.style.borderColor = "var(--gray)";
            }
        }
        
        // Show error message
        function showError(message) {
            const resultDisplay = document.getElementById('resultDisplay');
            resultDisplay.textContent = message;
            resultDisplay.style.color = "var(--danger)";
        }
        
        // Save to history
        function saveToHistory(value, min, max) {
            const historyItem = {
                value: value,
                min: min,
                max: max,
                timestamp: new Date().toISOString(),
                time: new Date().toLocaleTimeString()
            };
            
            history.unshift(historyItem);
            
            // Limit history count
            if (history.length > 10) {
                history = history.slice(0, 10);
            }
            
            localStorage.setItem('randomHistory', JSON.stringify(history));
            renderHistory();
        }
        
        // Render history
        function renderHistory() {
            const historyList = document.getElementById('historyList');
            historyList.innerHTML = '';
            
            if (history.length === 0) {
                historyList.innerHTML = `<div class="no-history">${resources[currentLanguage].noHistoryText}</div>`;
                return;
            }
            
            history.forEach((item, index) => {
                const historyItem = document.createElement('div');
                historyItem.className = 'history-item';
                
                const rangeText = item.min !== 0 || item.max !== 0 ? 
                    (currentLanguage === 'en' ? 
                        `Range: ${item.min} - ${item.max}` : 
                        `范围: ${item.min} - ${item.max}`) : '';
                
                historyItem.innerHTML = `
                    <div>
                        <div class="history-number">${item.value}</div>
                        <div class="history-range">${rangeText}</div>
                    </div>
                    <div class="history-time">${item.time}</div>
                `;
                
                historyList.appendChild(historyItem);
            });
        }
        
        // Clear history
        function clearHistory() {
            history = [];
            localStorage.setItem('randomHistory', JSON.stringify(history));
            renderHistory();
        }
        
        // Toggle theme
        function toggleTheme() {
            isDarkTheme = !isDarkTheme;
            document.body.classList.toggle('dark-theme');
            
            updateThemeText();
            
            localStorage.setItem('darkTheme', isDarkTheme);
        }
        
        // Update theme text
        function updateThemeText() {
            const themeToggle = document.getElementById('themeToggle');
            const resource = resources[currentLanguage];
            
            if (isDarkTheme) {
                themeToggle.innerHTML = `<i class="fas fa-sun"></i><span id="themeText">${resource.lightThemeText}</span>`;
            } else {
                themeToggle.innerHTML = `<i class="fas fa-moon"></i><span id="themeText">${resource.themeText}</span>`;
            }
        }
        
        // Show success message
        function showSuccessMessage() {
            const message = document.getElementById('successMessage');
            message.classList.add('show');
            setTimeout(() => {
                message.classList.remove('show');
            }, 3000);
        }
        
        // Update clock display
        function updateClock() {
            const now = new Date();
            const options = { 
                year: 'numeric', 
                month: '2-digit', 
                day: '2-digit', 
                hour: '2-digit', 
                minute: '2-digit', 
                second: '2-digit',
                weekday: 'long' 
            };
            
            const timeString = now.toLocaleDateString(currentLanguage === 'en' ? 'en-US' : 'zh-CN', options);
            document.getElementById('timeDisplay').textContent = timeString;
        }
        
        // Initialize on page load
        window.addEventListener('DOMContentLoaded', initializeApp);
    </script>
</body>
</html>
