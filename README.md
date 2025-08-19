# Aurora-Advisory-Studio
Overview and Capabilities 
[index.html](https://github.com/user-attachments/files/21860044/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aurora Advisory Studio - Strategic Business Development Solutions</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #0c2340 0%, #1e3a5f 25%, #0f4c5c 50%, #134e4a 75%, #022c22 100%);
            background-size: 400% 400%;
            animation: deepOceanFlow 30s ease infinite;
            min-height: 100vh;
            padding: 20px;
        }
        
        @keyframes deepOceanFlow {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: white;
            border-radius: 15px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            overflow: hidden;
        }
        
        .header {
            background: linear-gradient(135deg, #0c2340 0%, #1e3a5f 100%);
            color: white;
            padding: 40px;
            text-align: center;
            position: relative;
        }
        
        .header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1000 100"><path d="M0,0 L1000,0 L1000,80 Q500,120 0,80 Z" fill="rgba(79,209,197,0.1)"/></svg>') no-repeat bottom;
            background-size: cover;
        }
        
        .header-content {
            position: relative;
            z-index: 1;
        }
        
        .headshot {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            border: 4px solid rgba(79,209,197,0.3);
            margin: 0 auto 15px;
            object-fit: cover;
            box-shadow: 0 8px 20px rgba(0,0,0,0.3);
            display: block;
        }
        
        h1 {
            font-size: 2.2em;
            margin-bottom: 10px;
            font-weight: 300;
        }
        
        .tagline {
            font-size: 1.2em;
            opacity: 0.9;
            font-weight: 300;
        }
        
        .contact-info {
            margin-top: 20px;
            font-size: 1.1em;
        }
        
        .contact-info a {
            color: white;
            text-decoration: none;
            margin: 0 5px;
            transition: opacity 0.3s ease;
        }
        
        .contact-info a:hover {
            opacity: 0.8;
            text-decoration: underline;
        }
        
        .content {
            padding: 50px 40px;
        }
        
        .attention-grabber {
            background: linear-gradient(135deg, #064e6b 0%, #0f4c5c 50%, #4fd1c5 100%);
            color: white;
            padding: 30px;
            border-radius: 15px;
            margin-bottom: 40px;
            text-align: center;
            position: relative;
            overflow: hidden;
            animation: auroraPulse 3s infinite;
        }
        
        @keyframes auroraPulse {
            0% { box-shadow: 0 0 0 0 rgba(79, 209, 197, 0.5); }
            70% { box-shadow: 0 0 0 20px rgba(79, 209, 197, 0); }
            100% { box-shadow: 0 0 0 0 rgba(79, 209, 197, 0); }
        }
        
        .attention-grabber h2 {
            font-size: 2em;
            margin-bottom: 15px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.2);
        }
        
        .attention-grabber p {
            font-size: 1.2em;
            font-weight: 500;
        }
        
        .value-prop {
            text-align: center;
            margin-bottom: 50px;
            padding: 30px;
            background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
            border-radius: 10px;
            border-left: 5px solid #064e6b;
        }
        
        .value-prop h2 {
            color: #0c2340;
            font-size: 1.8em;
            margin-bottom: 15px;
        }
        
        .value-prop p {
            font-size: 1.1em;
            color: #1e3a5f;
        }
        
        .expertise-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin: 40px 0;
        }
        
        .expertise-card {
            background: white;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.08);
            border-top: 4px solid #064e6b;
            transition: transform 0.3s ease;
        }
        
        .expertise-card:hover {
            transform: translateY(-5px);
        }
        
        .expertise-card h3 {
            color: #0c2340;
            margin-bottom: 15px;
            font-size: 1.3em;
        }
        
        .expertise-card ul {
            list-style: none;
            padding: 0;
        }
        
        .expertise-card li {
            padding: 5px 0;
            border-bottom: 1px solid #eee;
        }
        
        .expertise-card li:last-child {
            border-bottom: none;
        }
        
        .results-section {
            background: linear-gradient(135deg, #064e6b 0%, #134e4a 100%);
            color: white;
            padding: 40px;
            border-radius: 10px;
            margin: 40px 0;
        }
        
        .results-section h2 {
            text-align: center;
            margin-bottom: 30px;
            font-size: 1.8em;
        }
        
        .results-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 30px;
            text-align: center;
        }
        
        .result-item {
            background: rgba(255,255,255,0.1);
            padding: 20px;
            border-radius: 8px;
            backdrop-filter: blur(10px);
        }
        
        .result-number {
            font-size: 2.5em;
            font-weight: bold;
            margin-bottom: 10px;
        }
        
        .result-description {
            font-size: 0.95em;
            opacity: 0.9;
        }
        
        .cta-section {
            text-align: center;
            padding: 40px;
            background: #f8f9fa;
            border-radius: 10px;
            margin-top: 40px;
        }
        
        .cta-section h2 {
            color: #0c2340;
            margin-bottom: 20px;
        }
        
        .cta-button {
            display: inline-block;
            background: linear-gradient(135deg, #064e6b 0%, #134e4a 100%);
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            margin: 10px;
            transition: transform 0.3s ease;
        }
        
        .cta-button:hover {
            transform: translateY(-2px);
        }
        
        .chart-container {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.08);
            margin: 20px 0;
        }
        
        .progress-bar {
            background: #e9ecef;
            border-radius: 10px;
            height: 20px;
            margin: 10px 0;
            overflow: hidden;
            position: relative;
        }
        
        .progress-fill {
            height: 100%;
            background: linear-gradient(90deg, #064e6b, #0f4c5c);
            border-radius: 10px;
            transition: width 2s ease-in-out;
            position: relative;
        }
        
        .progress-fill::after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.3), transparent);
            animation: shine 2s infinite;
        }
        
        @keyframes shine {
            0% { transform: translateX(-100%); }
            100% { transform: translateX(100%); }
        }
        
        .metric-chart {
            display: flex;
            align-items: end;
            justify-content: space-around;
            height: 150px;
            margin: 20px 0;
            padding: 20px;
            background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
            border-radius: 10px;
        }
        
        .bar {
            width: 60px;
            background: linear-gradient(180deg, #064e6b, #134e4a);
            border-radius: 5px 5px 0 0;
            transition: height 2s ease-in-out;
            position: relative;
            animation: growUp 2s ease-in-out;
        }
        
        @keyframes growUp {
            from { height: 0; }
        }
        
        .bar-label {
            text-align: center;
            margin-top: 10px;
            font-size: 0.9em;
            color: #0c2340;
            font-weight: bold;
        }
        
        .pie-chart {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            background: conic-gradient(#064e6b 0deg 144deg, #0f4c5c 144deg 234deg, #1e3a5f 234deg 288deg, #0c2340 288deg 342deg, #134e4a 342deg 360deg);
            margin: 20px auto;
            position: relative;
            animation: spin 3s ease-in-out;
        }
        
        @keyframes growWidth {
            from { width: 0; }
        }
        
        @keyframes spin {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }
        
        .pie-legend {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 10px;
            margin-top: 20px;
        }
        
        .legend-item {
            display: flex;
            align-items: center;
            font-size: 0.9em;
        }
        
        .legend-color {
            width: 16px;
            height: 16px;
            border-radius: 50%;
            margin-right: 8px;
        }
        
        @media (max-width: 768px) {
            .container {
                margin: 10px;
            }
            
            .header, .content {
                padding: 30px 20px;
            }
            
            h1 {
                font-size: 2em;
            }
            
            .expertise-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <div class="header-content">
                <!-- Aurora-inspired Brand Logo -->
                <div style="margin: 0 auto 30px; display: flex; justify-content: center;">
                    <svg viewBox="0 0 300 120" width="300" xmlns="http://www.w3.org/2000/svg" style="filter: drop-shadow(0 4px 8px rgba(0,0,0,0.2));">
                        <defs>
                            <linearGradient id="aurora-gradient" x1="0%" y1="0%" x2="100%" y2="100%">
                                <stop offset="0%" style="stop-color:#4fd1c5;stop-opacity:0.8">
                                    <animate attributeName="stop-color" values="#4fd1c5;#064e6b;#4fd1c5" dur="6s" repeatCount="indefinite" />
                                </stop>
                                <stop offset="50%" style="stop-color:#064e6b;stop-opacity:1">
                                    <animate attributeName="stop-color" values="#064e6b;#0f4c5c;#064e6b" dur="6s" repeatCount="indefinite" />
                                </stop>
                                <stop offset="100%" style="stop-color:#134e4a;stop-opacity:0.8">
                                    <animate attributeName="stop-color" values="#134e4a;#4fd1c5;#134e4a" dur="6s" repeatCount="indefinite" />
                                </stop>
                            </linearGradient>
                            
                            <filter id="ethereal-glow">
                                <feGaussianBlur stdDeviation="2" result="coloredBlur"/>
                                <feMerge>
                                    <feMergeNode in="coloredBlur"/>
                                    <feMergeNode in="SourceGraphic"/>
                                </feMerge>
                            </filter>
                        </defs>
                        
                        <!-- Aurora waves representing growth -->
                        <path d="M 30 45 Q 150 20 270 45" stroke="url(#aurora-gradient)" stroke-width="3" fill="none" filter="url(#ethereal-glow)" opacity="0.9"/>
                        <path d="M 50 50 Q 150 30 250 50" stroke="url(#aurora-gradient)" stroke-width="2" fill="none" opacity="0.6"/>
                        <path d="M 70 55 Q 150 40 230 55" stroke="url(#aurora-gradient)" stroke-width="1.5" fill="none" opacity="0.4"/>
                        
                        <!-- Illuminating dots -->
                        <circle cx="150" cy="35" r="3" fill="#4fd1c5" opacity="0.8">
                            <animate attributeName="opacity" values="0.4;1;0.4" dur="3s" repeatCount="indefinite" />
                        </circle>
                        <circle cx="80" cy="48" r="2" fill="#4fd1c5" opacity="0.6">
                            <animate attributeName="opacity" values="0.2;0.8;0.2" dur="4s" repeatCount="indefinite" />
                        </circle>
                        <circle cx="220" cy="48" r="2" fill="#4fd1c5" opacity="0.6">
                            <animate attributeName="opacity" values="0.2;0.8;0.2" dur="4s" begin="2s" repeatCount="indefinite" />
                        </circle>
                        
                        <!-- Main brand text -->
                        <text x="150" y="85" text-anchor="middle" font-family="'Didot', 'Optima', 'Georgia', serif" font-size="24" font-weight="300" letter-spacing="4" fill="white" style="text-shadow: 0 2px 4px rgba(0,0,0,0.3);">AURORA</text>
                        <text x="150" y="105" text-anchor="middle" font-family="'Helvetica Neue', Arial, sans-serif" font-size="10" font-weight="300" letter-spacing="3" fill="#a7d3d4">ADVISORY STUDIO</text>
                    </svg>
                </div>
                
                <h1 style="font-size: 2.2em;">Growth Solutions & Team Extension</h1>
                <div class="tagline">Illuminating Your Mission</div>
                <div style="font-size: 1em; margin-top: 10px; opacity: 0.8;">Led by Kathryn Morgan | Your Strategic Illumination Partner</div>
                <div class="contact-info">
                    <a href="tel:+12026692908">+1 202.669.2908</a> • 
                    <a href="mailto:Kathryn@AuroraAdvisoryStudio.com">Kathryn@AuroraAdvisoryStudio.com</a> • 
                    <a href="https://linkedin.com/in/kathrynrmorgan" target="_blank">LinkedIn</a>
                </div>
            </div>
        </div>
        
        <div class="content">
            <!-- Call to Action -->
            <div class="attention-grabber">
                <h2>🌟 Ready to Transform Your Impact?</h2>
                <p>Aurora Advisory Studio delivers measurable growth and seamless team integration for mission-driven organizations.</p>
            </div>
            
            <div class="value-prop">
                <h2>🌌 Your Strategic Illumination Partner</h2>
                <p>With over 15 years of proven experience, Aurora Advisory Studio seamlessly integrates with your existing team, delivering specialized business development, membership growth, and event expertise that drives transformational results. We become your strategic illumination partner for sustained success in the depths of your mission.</p>
            </div>
            
            <!-- Visual Services Overview -->
            <div style="background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%); padding: 40px; border-radius: 15px; margin: 40px 0; text-align: center;">
                <h2 style="color: #0c2340; margin-bottom: 30px;">🎯 What We Deliver</h2>
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 30px;">
                    <div style="background: white; padding: 25px; border-radius: 12px; box-shadow: 0 5px 15px rgba(6,78,107,0.08);">
                        <div style="font-size: 3em; margin-bottom: 10px;">📈</div>
                        <h3 style="color: #0c2340; margin-bottom: 10px;">Revenue Growth</h3>
                        <p style="font-size: 0.9em; color: #1e3a5f;">Strategic partnerships & sponsorship optimization</p>
                    </div>
                    <div style="background: white; padding: 25px; border-radius: 12px; box-shadow: 0 5px 15px rgba(6,78,107,0.08);">
                        <div style="font-size: 3em; margin-bottom: 10px;">👥</div>
                        <h3 style="color: #0c2340; margin-bottom: 10px;">Membership Growth</h3>
                        <p style="font-size: 0.9em; color: #1e3a5f;">Engagement strategies & retention optimization</p>
                    </div>
                    <div style="background: white; padding: 25px; border-radius: 12px; box-shadow: 0 5px 15px rgba(6,78,107,0.08);">
                        <div style="font-size: 3em; margin-bottom: 10px;">🎯</div>
                        <h3 style="color: #0c2340; margin-bottom: 10px;">Event Excellence</h3>
                        <p style="font-size: 0.9em; color: #1e3a5f;">Conference strategy & experiential marketing</p>
                    </div>
                    <div style="background: white; padding: 25px; border-radius: 12px; box-shadow: 0 5px 15px rgba(6,78,107,0.08);">
                        <div style="font-size: 3em; margin-bottom: 10px;">⚡</div>
                        <h3 style="color: #0c2340; margin-bottom: 10px;">Process Innovation</h3>
                        <p style="font-size: 0.9em; color: #1e3a5f;">Systems optimization & automation</p>
                    </div>
                </div>
            </div>
            
            <!-- Growth Acceleration Curve -->
            <div class="chart-container">
                <h3 style="text-align: center; color: #0c2340; margin-bottom: 30px;">📈 Growth Acceleration Curve</h3>
                
                <!-- Curve Chart -->
                <div style="position: relative; height: 300px; margin: 40px 20px; padding: 40px; background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%); border-radius: 15px; overflow: hidden;">
                    <!-- Background grid -->
                    <div style="position: absolute; top: 40px; left: 60px; right: 40px; bottom: 80px; opacity: 0.1;">
                        <div style="position: absolute; top: 0; left: 0; right: 0; height: 1px; background: #0c2340;"></div>
                        <div style="position: absolute; top: 25%; left: 0; right: 0; height: 1px; background: #0c2340;"></div>
                        <div style="position: absolute; top: 50%; left: 0; right: 0; height: 1px; background: #0c2340;"></div>
                        <div style="position: absolute; top: 75%; left: 0; right: 0; height: 1px; background: #0c2340;"></div>
                        <div style="position: absolute; bottom: 0; left: 0; right: 0; height: 1px; background: #0c2340;"></div>
                        <div style="position: absolute; top: 0; bottom: 0; left: 25%; width: 1px; background: #0c2340;"></div>
                        <div style="position: absolute; top: 0; bottom: 0; left: 50%; width: 1px; background: #0c2340;"></div>
                        <div style="position: absolute; top: 0; bottom: 0; left: 75%; width: 1px; background: #0c2340;"></div>
                    </div>
                    
                    <!-- Y-axis labels -->
                    <div style="position: absolute; left: 10px; top: 40px; bottom: 80px; display: flex; flex-direction: column; justify-content: space-between; font-size: 0.8em; color: #0c2340; font-weight: 500;">
                        <span>$500K</span>
                        <span>$400K</span>
                        <span>$300K</span>
                        <span>$200K</span>
                        <span>$100K</span>
                    </div>
                    
                    <!-- X-axis labels -->
                    <div style="position: absolute; left: 60px; right: 40px; bottom: 40px; display: flex; justify-content: space-between; font-size: 0.8em; color: #0c2340; font-weight: 500;">
                        <span>Month 1</span>
                        <span>Month 6</span>
                        <span>Month 12</span>
                        <span>Month 18</span>
                        <span>Month 24</span>
                    </div>
                    
                    <!-- SVG Curve -->
                    <svg style="position: absolute; top: 40px; left: 60px; right: 40px; bottom: 80px; width: calc(100% - 100px); height: calc(100% - 120px);" viewBox="0 0 400 200" preserveAspectRatio="none">
                        <defs>
                            <linearGradient id="curve-gradient" x1="0%" y1="0%" x2="100%" y2="0%">
                                <stop offset="0%" style="stop-color:#064e6b;stop-opacity:1" />
                                <stop offset="50%" style="stop-color:#0f4c5c;stop-opacity:1" />
                                <stop offset="100%" style="stop-color:#4fd1c5;stop-opacity:1" />
                            </linearGradient>
                            <linearGradient id="area-gradient" x1="0%" y1="0%" x2="0%" y2="100%">
                                <stop offset="0%" style="stop-color:#4fd1c5;stop-opacity:0.3" />
                                <stop offset="100%" style="stop-color:#064e6b;stop-opacity:0.1" />
                            </linearGradient>
                        </defs>
                        
                        <!-- Area under curve -->
                        <path d="M 0 180 Q 100 160, 200 120 T 400 40 L 400 200 L 0 200 Z" fill="url(#area-gradient)" opacity="0.6"/>
                        
                        <!-- Main growth curve -->
                        <path d="M 0 180 Q 100 160, 200 120 T 400 40" stroke="url(#curve-gradient)" stroke-width="4" fill="none" style="filter: drop-shadow(0 2px 4px rgba(6,78,107,0.3));">
                            <animate attributeName="stroke-dasharray" values="0 1000; 1000 0" dur="3s" fill="freeze"/>
                            <animate attributeName="stroke-dashoffset" values="1000; 0" dur="3s" fill="freeze"/>
                        </path>
                    </svg>
                    
                    <!-- Intervention Points -->
                    <div style="position: absolute; top: 55%; left: 20%; transform: translate(-50%, -50%);">
                        <div style="width: 12px; height: 12px; background: #064e6b; border-radius: 50%; border: 3px solid white; box-shadow: 0 2px 6px rgba(6,78,107,0.4); animation: pulse 2s infinite;"></div>
                        <div style="position: absolute; top: -40px; left: 50%; transform: translateX(-50%); background: white; padding: 8px 12px; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); font-size: 0.75em; color: #0c2340; font-weight: bold; white-space: nowrap; border-left: 3px solid #064e6b;">
                            Partnership Strategy
                        </div>
                    </div>
                    
                    <div style="position: absolute; top: 40%; left: 50%; transform: translate(-50%, -50%);">
                        <div style="width: 12px; height: 12px; background: #0f4c5c; border-radius: 50%; border: 3px solid white; box-shadow: 0 2px 6px rgba(15,76,92,0.4); animation: pulse 2s infinite 0.5s;"></div>
                        <div style="position: absolute; top: -40px; left: 50%; transform: translateX(-50%); background: white; padding: 8px 12px; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); font-size: 0.75em; color: #0c2340; font-weight: bold; white-space: nowrap; border-left: 3px solid #0f4c5c;">
                            Event Optimization
                        </div>
                    </div>
                    
                    <div style="position: absolute; top: 25%; left: 80%; transform: translate(-50%, -50%);">
                        <div style="width: 12px; height: 12px; background: #4fd1c5; border-radius: 50%; border: 3px solid white; box-shadow: 0 2px 6px rgba(79,209,197,0.4); animation: pulse 2s infinite 1s;"></div>
                        <div style="position: absolute; top: -40px; left: 50%; transform: translateX(-50%); background: white; padding: 8px 12px; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); font-size: 0.75em; color: #0c2340; font-weight: bold; white-space: nowrap; border-left: 3px solid #4fd1c5;">
                            Sustained Growth
                        </div>
                    </div>
                </div>
                
                <!-- Key insights below curve -->
                <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 20px; margin-top: 30px;">
                    <div style="text-align: center; padding: 20px; background: white; border-radius: 10px; border-left: 4px solid #064e6b;">
                        <div style="font-size: 1.5em; font-weight: bold; color: #064e6b; margin-bottom: 5px;">3-6 Months</div>
                        <div style="font-size: 0.9em; color: #1e3a5f;">Initial momentum & strategy implementation</div>
                    </div>
                    <div style="text-align: center; padding: 20px; background: white; border-radius: 10px; border-left: 4px solid #0f4c5c;">
                        <div style="font-size: 1.5em; font-weight: bold; color: #0f4c5c; margin-bottom: 5px;">6-12 Months</div>
                        <div style="font-size: 0.9em; color: #1e3a5f;">Acceleration phase with measurable gains</div>
                    </div>
                    <div style="text-align: center; padding: 20px; background: white; border-radius: 10px; border-left: 4px solid #4fd1c5;">
                        <div style="font-size: 1.5em; font-weight: bold; color: #4fd1c5; margin-bottom: 5px;">12+ Months</div>
                        <div style="font-size: 0.9em; color: #1e3a5f;">Sustained exponential growth trajectory</div>
                    </div>
                </div>
            </div>
            
            <div class="expertise-grid">
                <div class="expertise-card">
                    <h3>💼 Strategic Business Development</h3>
                    <ul>
                        <li>Partnership strategy & execution</li>
                        <li>Sponsorship program optimization</li>
                        <li>Market opportunity analysis</li>
                        <li>Revenue diversification</li>
                    </ul>
                </div>
                
                <div class="expertise-card">
                    <h3>🤝 Membership Growth & Engagement</h3>
                    <ul>
                        <li>Member acquisition strategies</li>
                        <li>Retention & engagement programs</li>
                        <li>Membership value optimization</li>
                        <li>Community building initiatives</li>
                    </ul>
                </div>
                
                <div class="expertise-card">
                    <h3>🎯 Event Strategy & Execution</h3>
                    <ul>
                        <li>Conference & summit planning</li>
                        <li>Experiential marketing design</li>
                        <li>Event sponsorship & exhibit maximization</li>
                        <li>Onsite management & support</li>
                    </ul>
                </div>
                
                <div class="expertise-card">
                    <h3>🌍 Mission-Driven Specialization</h3>
                    <ul>
                        <li>Association & nonprofit focus</li>
                        <li>Global partnership networks</li>
                        <li>Member engagement strategies</li>
                        <li>Stakeholder relationship management</li>
                    </ul>
                    <div class="progress-bar">
                        <div class="progress-fill" style="width: 100%;"></div>
                    </div>
                    <div style="text-align: center; font-size: 0.8em; color: #666; margin-top: 5px;">100% Nonprofit Focus</div>
                </div>
            </div>
            
            <!-- Service Distribution Pie Chart -->
            <div class="chart-container">
                <h3 style="text-align: center; color: #0c2340; margin-bottom: 20px;">🎯 Our Service Focus Areas</h3>
                <div class="pie-chart"></div>
                <div class="pie-legend">
                    <div class="legend-item">
                        <div class="legend-color" style="background: #064e6b;"></div>
                        <span>Business Development (40%)</span>
                    </div>
                    <div class="legend-item">
                        <div class="legend-color" style="background: #0f4c5c;"></div>
                        <span>Membership Engagement (25%)</span>
                    </div>
                    <div class="legend-item">
                        <div class="legend-color" style="background: #1e3a5f;"></div>
                        <span>Event Management (15%)</span>
                    </div>
                    <div class="legend-item">
                        <div class="legend-color" style="background: #0c2340;"></div>
                        <span>Strategic Consulting (15%)</span>
                    </div>
                    <div class="legend-item">
                        <div class="legend-color" style="background: #134e4a;"></div>
                        <span>Process Innovation (5%)</span>
                    </div>
                </div>
            </div>
            
            <div class="results-section">
                <h2>📊 Our Impact by the Numbers</h2>
                <div class="results-grid">
                    <div class="result-item">
                        <div class="result-number">20%+</div>
                        <div class="result-description">Revenue growth delivered within 12 months</div>
                    </div>
                    <div class="result-item">
                        <div class="result-number">15+</div>
                        <div class="result-description">Years of transformational expertise</div>
                    </div>
                    <div class="result-item">
                        <div class="result-number">100%</div>
                        <div class="result-description">Client satisfaction and successful team integration rate</div>
                    </div>
                </div>
            </div>
            
            <div style="background: white; padding: 30px; border-radius: 10px; box-shadow: 0 5px 15px rgba(6,78,107,0.08); margin: 30px 0;">
                <h3 style="color: #0c2340; margin-bottom: 20px; text-align: center;">🌟 Recent Aurora Engagements</h3>
                <div style="display: grid; gap: 20px;">
                    <div style="border-left: 4px solid #064e6b; padding-left: 20px;">
                        <strong>American Association for Justice (AAJ)</strong><br>
                        <em>Strategic Business Development Partnership</em><br>
                        Led comprehensive revenue transformation and modernized event sponsorship strategy. Delivered measurable growth while building internal team capabilities.
                    </div>
                    <div style="border-left: 4px solid #064e6b; padding-left: 20px;">
                        <strong>Finseca (GAMA Global)</strong><br>
                        <em>Global Expansion & Membership Strategy</em><br>
                        Developed multi-regional growth initiatives and enhanced conference portfolio across Asia, LATAM, and Caribbean markets with quantifiable ROI. Led membership initiatives for chapter growth management and regional expansion strategies.
                    </div>
                </div>
            </div>
            
            <div class="cta-section">
                <h2>🚀 Ready to Scale Your Growth?</h2>
                <p style="margin-bottom: 25px; font-size: 1.1em; color: #1e3a5f;">Let's discuss how Aurora Advisory Studio can seamlessly extend your team's capabilities and accelerate your organization's impact.</p>
                <a href="mailto:Kathryn@AuroraAdvisoryStudio.com" class="cta-button">Start the Conversation</a>
                <a href="tel:+12026692908" class="cta-button">Call: +1 202.669.2908</a>
            </div>
        </div>
    </div>
</body>
</html>
