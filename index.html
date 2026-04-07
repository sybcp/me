<!DOCTYPE html>
<html lang="zh-CN" data-theme="dark">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>让每个人都享受到科技的乐趣 | Tech for Everyone</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600&family=Space+Grotesk:wght@300;500;700&display=swap" rel="stylesheet">
    <style>
        /* 基础变量 - 夜间模式（默认） */
        :root {
            --bg-primary: #0a0a0a;
            --bg-secondary: #111;
            --text-primary: #ffffff;
            --text-secondary: rgba(255, 255, 255, 0.6);
            --border-color: rgba(255, 255, 255, 0.1);
            --accent-glow: rgba(120, 119, 198, 0.15);
            --star-opacity: 1;
            --day-opacity: 0;
            --github-filter: invert(1);
        }
        
        /* 白天模式变量 - 通过属性选择器覆盖 */
        [data-theme="light"] {
            --bg-primary: #f5f5f0;
            --bg-secondary: #ffffff;
            --text-primary: #1a1a1a;
            --text-secondary: rgba(0, 0, 0, 0.6);
            --border-color: rgba(0, 0, 0, 0.1);
            --accent-glow: rgba(255, 193, 7, 0.15);
            --star-opacity: 0;
            --day-opacity: 1;
            --github-filter: none;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        html {
            transition: background-color 0.8s ease;
        }
        
        body {
            font-family: 'Inter', sans-serif;
            background-color: var(--bg-primary);
            color: var(--text-primary);
            overflow-x: hidden;
            cursor: none;
            transition: background-color 0.8s ease, color 0.8s ease;
            min-height: 100vh;
        }
        
        .font-display {
            font-family: 'Space Grotesk', sans-serif;
        }
        
        /* Custom Cursor */
        .cursor {
            width: 20px;
            height: 20px;
            border: 1px solid var(--text-primary);
            border-radius: 50%;
            position: fixed;
            pointer-events: none;
            z-index: 9999;
            transition: width 0.3s, height 0.3s, background 0.3s, border-color 0.8s;
            mix-blend-mode: difference;
        }
        
        .cursor.hover {
            width: 60px;
            height: 60px;
            background: rgba(128, 128, 128, 0.1);
        }
        
        /* Grain Overlay */
        .grain {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 9998;
            opacity: 0.03;
            background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noiseFilter'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noiseFilter)'/%3E%3C/svg%3E");
            transition: opacity 0.8s;
        }
        
        [data-theme="light"] .grain {
            opacity: 0.02;
        }
        
        /* Stars Container */
        .stars-container {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 1;
            opacity: var(--star-opacity);
            transition: opacity 0.8s ease;
        }
        
        .star {
            position: absolute;
            width: 2px;
            height: 2px;
            background: white;
            border-radius: 50%;
            animation: twinkle 3s infinite ease-in-out;
            box-shadow: 0 0 4px white;
        }
        
        @keyframes twinkle {
            0%, 100% { opacity: 0.2; transform: scale(1); }
            50% { opacity: 1; transform: scale(1.5); }
        }
        
        /* Day Elements Container */
        .day-elements {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 0;
            opacity: var(--day-opacity);
            transition: opacity 0.8s ease;
        }
        
        .sun {
            position: absolute;
            top: 10%;
            right: 10%;
            width: 80px;
            height: 80px;
            background: radial-gradient(circle, #ffd700 0%, #ffa500 70%, transparent 100%);
            border-radius: 50%;
            box-shadow: 0 0 60px rgba(255, 215, 0, 0.5), 0 0 100px rgba(255, 165, 0, 0.3);
            animation: sunPulse 4s ease-in-out infinite;
        }
        
        @keyframes sunPulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.1); }
        }
        
        .cloud {
            position: absolute;
            background: rgba(255, 255, 255, 0.9);
            border-radius: 100px;
            animation: float 20s infinite ease-in-out;
        }
        
        .cloud::before,
        .cloud::after {
            content: '';
            position: absolute;
            background: rgba(255, 255, 255, 0.9);
            border-radius: 100px;
        }
        
        .cloud:nth-child(2) {
            width: 100px;
            height: 40px;
            top: 20%;
            left: 10%;
        }
        
        .cloud:nth-child(2)::before {
            width: 50px;
            height: 50px;
            top: -25px;
            left: 10px;
        }
        
        .cloud:nth-child(2)::after {
            width: 60px;
            height: 40px;
            top: -15px;
            right: 10px;
        }
        
        .cloud:nth-child(3) {
            width: 80px;
            height: 35px;
            top: 40%;
            right: 20%;
            animation-delay: -5s;
        }
        
        .cloud:nth-child(3)::before {
            width: 40px;
            height: 40px;
            top: -20px;
            left: 15px;
        }
        
        .cloud:nth-child(3)::after {
            width: 50px;
            height: 35px;
            top: -10px;
            right: 15px;
        }
        
        .cloud:nth-child(4) {
            width: 120px;
            height: 45px;
            top: 60%;
            left: 30%;
            animation-delay: -10s;
        }
        
        .cloud:nth-child(4)::before {
            width: 60px;
            height: 60px;
            top: -30px;
            left: 20px;
        }
        
        .cloud:nth-child(4)::after {
            width: 70px;
            height: 45px;
            top: -20px;
            right: 20px;
        }
        
        /* Theme Toggle Button */
        .theme-toggle {
            position: fixed;
            top: 2rem;
            right: 6rem;
            z-index: 1000;
            width: 60px;
            height: 32px;
            background: var(--border-color);
            border-radius: 16px;
            cursor: pointer;
            padding: 4px;
            transition: all 0.5s cubic-bezier(0.34, 1.56, 0.64, 1), background 0.8s;
            border: 1px solid var(--border-color);
        }
        
        .theme-toggle:hover {
            transform: scale(1.1);
        }
        
        .toggle-slider {
            width: 24px;
            height: 24px;
            background: var(--text-primary);
            border-radius: 50%;
            position: relative;
            transition: transform 0
