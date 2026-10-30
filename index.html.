<!DOCTYPE html>  
<html lang="en">  
<head>  
  <meta charset="UTF-8" />  
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, viewport-fit=cover" />  
  <meta name="apple-mobile-web-app-capable" content="yes" />  
  <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent" />  
  <meta name="apple-mobile-web-app-title" content="Rutvi's Study App" />  
  <title>RUTVI’S STUDY APP - Class 7 Maharashtra Board</title>  
  
  <!-- Google Fonts: Poppins & Noto Sans Devanagari for Marathi/Hindi -->  
  <link rel="preconnect" href="https://fonts.googleapis.com" />  
  <link rel="preconnect" href="https://fonts.gstatic.com" />  
  <link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@400;600;700&family=Noto+Sans+Devanagari:wght@400;600;700&family=Nunito:wght@400;600;700;800;900&display=swap" rel="stylesheet" />  
  
  <style>  
    :root {  
      --bg-base: #0f172a;  
      --bg-surface: #1e293b;  
      --bg-surface-elevated: #334155;  
      --text-main: #f8fafc;  
      --text-muted: #94a3b8;  
      --accent-primary: #6366f1;  
      --accent-hover: #4f46e5;  
      --success: #10b981;  
      --danger: #ef4444;  
      --warning: #f59e0b;  
      --radius-sm: 10px;  
      --radius-md: 16px;  
      --radius-lg: 24px;  
      --font-body: 'Nunito', 'Noto Sans Devanagari', -apple-system, sans-serif;  
      --font-display: 'Fredoka', 'Noto Sans Devanagari', sans-serif;  
    }  
  
    * {  
      box-sizing: border-box;  
      margin: 0;  
      padding: 0;  
      user-select: none;  
      -webkit-user-select: none;  
      -webkit-tap-highlight-color: transparent;  
    }  
  
    body {  
      background: radial-gradient(circle at top center, #1e1b4b 0%, var(--bg-base) 100%);  
      color: var(--text-main);  
      font-family: var(--font-body);  
      min-height: 100vh;  
      display: flex;  
      flex-direction: column;  
      overflow-x: hidden;  
      padding-bottom: env(safe-area-inset-bottom);  
    }  
  
    /* Top Navigation Header */  
    header {  
      background: rgba(30, 41, 59, 0.85);  
      backdrop-filter: blur(16px);  
      -webkit-backdrop-filter: blur(16px);  
      border-bottom: 1px solid rgba(255, 255, 255, 0.08);  
      position: sticky;  
      top: 0;  
      z-index: 50;  
      padding: 12px 24px;  
      display: flex;  
      align-items: center;  
      justify-content: space-between;  
    }  
  
    .brand {  
      display: flex;  
      align-items: center;  
      gap: 12px;  
      cursor: pointer;  
    }  
  
    .brand-icon {  
      width: 44px;  
      height: 44px;  
      background: linear-gradient(135deg, #ec4899, #8b5cf6);  
      border-radius: var(--radius-sm);  
      display: flex;  
      align-items: center;  
      justify-content: center;  
      font-size: 24px;  
      box-shadow: 0 4px 14px rgba(236, 72, 153, 0.35);  
    }  
  
    .brand-title {  
      font-family: var(--font-display);  
      font-weight: 700;  
      font-size: 1.25rem;  
      letter-spacing: 0.5px;  
      background: linear-gradient(90deg, #f472b6, #c084fc);  
      -webkit-background-clip: text;  
      -webkit-text-fill-color: transparent;  
    }  
  
    .brand-sub {  
      font-size: 0.72rem;  
      color: var(--text-muted);  
      font-weight: 600;  
      letter-spacing: 0.5px;  
    }  
  
    .gamify-hud {  
      display: flex;  
      align-items: center;  
      gap: 16px;  
    }  
  
    .hud-chip {  
      background: rgba(15, 23, 42, 0.75);  
      border: 1px solid rgba(255, 255, 255, 0.1);  
      padding: 6px 14px;  
      border-radius: 999px;  
      display: flex;  
      align-items: center;  
      gap: 8px;  
      font-weight: 800;  
      font-size: 0.9rem;  
    }  
  
    .hud-chip.stars { color: #fbbf24; border-color: rgba(251, 191, 36, 0.3); }  
    .hud-chip.xp { color: #38bdf8; border-color: rgba(56, 189, 248, 0.3); }  
  
    /* App Container & View Switcher */  
    main {  
      flex: 1;  
      max-width: 1200px;  
      width: 100%;  
      margin: 0 auto;  
      padding: 24px;  
      display: flex;  
      flex-direction: column;  
    }  
  
    .view-panel {  
      display: none;  
      animation: fadeIn 0.3s cubic-bezier(0.16, 1, 0.3, 1) forwards;  
    }  
  
    .view-panel.active {  
      display: block;  
    }  
  
    @keyframes fadeIn {  
      from { opacity: 0; transform: translateY(12px); }  
      to { opacity: 1; transform: translateY(0); }  
    }  
  
    /* DASHBOARD */  
    .hero-banner {  
      background: linear-gradient(135deg, rgba(99, 102, 241, 0.25), rgba(217, 70, 239, 0.25));  
      border: 1px solid rgba(255, 255, 255, 0.12);  
      border-radius: var(--radius-lg);  
      padding: 24px 32px;  
      margin-bottom: 28px;  
      display: flex;  
      align-items: center;  
      justify-content: space-between;  
      position: relative;  
      overflow: hidden;  
    }  
  
    .hero-text h1 {  
      font-family: var(--font-display);  
      font-size: 2rem;  
      margin-bottom: 6px;  
    }  
  
    .hero-text p {  
      color: var(--text-muted);  
      font-size: 0.95rem;  
      max-width: 520px;  
    }  
  
    .overall-progress-bar-wrap {  
      width: 240px;  
      background: rgba(15, 23, 42, 0.8);  
      border-radius: 999px;  
      height: 14px;  
      overflow: hidden;  
      margin-top: 12px;  
      border: 1px solid rgba(255, 255, 255, 0.1);  
    }  
  
    .overall-progress-fill {  
      height: 100%;  
      width: 0%;  
      background: linear-gradient(90deg, #10b981, #06b6d4);  
      transition: width 0.6s ease;  
    }  
  
    .section-title {  
      font-family: var(--font-display);  
      font-size: 1.4rem;  
      margin-bottom: 16px;  
      display: flex;  
      align-items: center;  
      gap: 10px;  
    }  
  
    /* 7 Subject Cards Grid */  
    .subject-grid {  
      display: grid;  
      grid-template-columns: repeat(auto-fill, minmax(260px, 1fr));  
      gap: 20px;  
    }  
  
    .subject-card {  
      background: var(--bg-surface);  
      border: 1px solid rgba(255, 255, 255, 0.08);  
      border-radius: var(--radius-md);  
      padding: 20px;  
      cursor: pointer;  
      transition: all 0.25s cubic-bezier(0.16, 1, 0.3, 1);  
      position: relative;  
      overflow: hidden;  
      display: flex;  
      flex-direction: column;  
      gap: 14px;  
    }  
  
    .subject-card:hover {  
      transform: translateY(-4px) scale(1.01);  
      border-color: rgba(255, 255, 255, 0.25);  
      box-shadow: 0 12px 30px rgba(0, 0, 0, 0.35);  
    }  
  
    .subject-card:active {  
      transform: scale(0.98);  
    }  
  
    .subject-card-top {  
      display: flex;  
      align-items: center;  
      justify-content: space-between;  
    }  
  
    .subject-badge {  
      width: 54px;  
      height: 54px;  
      border-radius: var(--radius-sm);  
      display: flex;  
      align-items: center;  
      justify-content: center;  
      font-size: 28px;  
    }  
  
    .subject-completion {  
      font-weight: 800;  
      font-size: 0.8rem;  
      color: var(--text-muted);  
    }  
  
    .subject-info h3 {  
      font-family: var(--font-display);  
      font-size: 1.25rem;  
      margin-bottom: 4px;  
    }  
  
    .subject-info p {  
      font-size: 0.82rem;  
      color: var(--text-muted);  
    }  
  
    .card-progress-bar {  
      height: 8px;  
      background: var(--bg-surface-elevated);  
      border-radius: 999px;  
      overflow: hidden;  
    }  
  
    .card-progress-fill {  
      height: 100%;  
      border-radius: 999px;  
      transition: width 0.4s ease;  
    }  
  
    /* CHAPTER VIEW */  
    .chapter-hero {  
      background: var(--bg-surface);  
      border: 1px solid rgba(255, 255, 255, 0.1);  
      border-radius: var(--radius-md);  
      padding: 24px;  
      margin-bottom: 24px;  
      display: flex;  
      align-items: center;  
      justify-content: space-between;  
    }  
  
    .btn-back {  
      background: var(--bg-surface-elevated);  
      color: var(--text-main);  
      border: 1px solid rgba(255, 255, 255, 0.1);  
      padding: 8px 16px;  
      border-radius: var(--radius-sm);  
      font-weight: 700;  
      font-size: 0.85rem;  
      cursor: pointer;  
      display: inline-flex;  
      align-items: center;  
      gap: 6px;  
      margin-bottom: 16px;  
      transition: background 0.2s;  
    }  
  
    .btn-back:hover { background: rgba(255, 255, 255, 0.15); }  
  
    .chapter-list {  
      display: flex;  
      flex-direction: column;  
      gap: 16px;  
    }  
  
    .chapter-card {  
      background: var(--bg-surface);  
      border: 1px solid rgba(255, 255, 255, 0.08);  
      border-radius: var(--radius-md);  
      padding: 20px;  
      display: flex;  
      align-items: center;  
      justify-content: space-between;  
      gap: 16px;  
    }  
  
    .chapter-meta h4 {  
      font-family: var(--font-display);  
      font-size: 1.2rem;  
      margin-bottom: 4px;  
    }  
  
    .chapter-meta p {  
      font-size: 0.85rem;  
      color: var(--text-muted);  
    }  
  
    .chapter-actions {  
      display: flex;  
      align-items: center;  
      gap: 12px;  
      flex-shrink: 0;  
    }  
  
    .btn-action {  
      border: none;  
      padding: 10px 18px;  
      border-radius: var(--radius-sm);  
      font-weight: 800;  
      font-size: 0.9rem;  
      cursor: pointer;  
      display: flex;  
      align-items: center;  
      gap: 8px;  
      transition: transform 0.2s, box-shadow 0.2s;  
    }  
  
    .btn-action:active { transform: scale(0.96); }  
    .btn-movie { background: linear-gradient(135deg, #6366f1, #8b5cf6); color: #fff; }  
    .btn-quiz { background: linear-gradient(135deg, #10b981, #059669); color: #fff; }  
  
    /* VISUAL MOVIE / STORY SCENE PLAYER */  
    .movie-player-container {  
      background: #000;  
      border-radius: var(--radius-lg);  
      border: 1px solid rgba(255, 255, 255, 0.15);  
      box-shadow: 0 20px 50px rgba(0, 0, 0, 0.6);  
      overflow: hidden;  
      display: flex;  
      flex-direction: column;  
    }  
  
    .movie-screen {  
      aspect-ratio: 16 / 9;  
      max-height: 480px;  
      background: linear-gradient(180deg, #1e1b4b 0%, #0f172a 100%);  
      position: relative;  
      display: flex;  
      align-items: center;  
      justify-content: center;  
      overflow: hidden;  
    }  
  
    .scene-overlay-badge {  
      position: absolute;  
      top: 16px;  
      left: 16px;  
      background: rgba(0, 0, 0, 0.65);  
      backdrop-filter: blur(8px);  
      padding: 6px 14px;  
      border-radius: 999px;  
      font-size: 0.8rem;  
      font-weight: 800;  
      color: #38bdf8;  
      border: 1px solid rgba(56, 189, 248, 0.3);  
      display: flex;  
      align-items: center;  
      gap: 6px;  
    }  
  
    .audio-cue-tag {  
      position: absolute;  
      bottom: 16px;  
      right: 16px;  
      background: rgba(15, 23, 42, 0.8);  
      backdrop-filter: blur(8px);  
      padding: 6px 14px;  
      border-radius: 999px;  
      font-size: 0.75rem;  
      font-weight: 700;  
      color: #fbbf24;  
      border: 1px solid rgba(251, 191, 36, 0.3);  
      display: flex;  
      align-items: center;  
      gap: 6px;  
    }  
  
    /* Subtitles / Script Box */  
    .movie-script-box {  
      background: var(--bg-surface);  
      padding: 24px 30px;  
      border-top: 1px solid rgba(255, 255, 255, 0.1);  
    }  
  
    .director-note {  
      font-size: 0.8rem;  
      color: #c084fc;  
      text-transform: uppercase;  
      letter-spacing: 0.8px;  
      font-weight: 800;  
      margin-bottom: 8px;  
      display: flex;  
      align-items: center;  
      gap: 6px;  
    }  
  
    .spoken-script {  
      font-size: 1.15rem;  
      line-height: 1.6;  
      color: #f1f5f9;  
      min-height: 60px;  
    }  
  
    /* Controls Bar */  
    .movie-controls {  
      background: rgba(15, 23, 42, 0.95);  
      padding: 16px 24px;  
      display: flex;  
      align-items: center;  
      justify-content: space-between;  
      border-top: 1px solid rgba(255, 255, 255, 0.08);  
    }  
  
    .scene-dots {  
      display: flex;  
      align-items: center;  
      gap: 8px;  
    }  
  
    .scene-dot {  
      width: 32px;  
      height: 6px;  
      border-radius: 999px;  
      background: var(--bg-surface-elevated);  
      transition: all 0.3s ease;  
    }  
  
    .scene-dot.active {  
      background: var(--accent-primary);  
      width: 48px;  
    }  
  
    .scene-nav-buttons {  
      display: flex;  
      align-items: center;  
      gap: 12px;  
    }  
  
    .btn-circle {  
      width: 44px;  
      height: 44px;  
      border-radius: 50%;  
      border: 1px solid rgba(255, 255, 255, 0.15);  
      background: var(--bg-surface);  
      color: var(--text-main);  
      display: flex;  
      align-items: center;  
      justify-content: center;  
      font-size: 18px;  
      cursor: pointer;  
      transition: background 0.2s, transform 0.2s;  
    }  
  
    .btn-circle:hover { background: var(--bg-surface-elevated); }  
    .btn-circle:active { transform: scale(0.92); }  
  
    /* QUIZ ARENA VIEW */  
    .quiz-card-container {  
      background: var(--bg-surface);  
      border: 1px solid rgba(255, 255, 255, 0.1);  
      border-radius: var(--radius-lg);  
      padding: 32px;  
      max-width: 800px;  
      margin: 0 auto;  
      box-shadow: 0 16px 40px rgba(0, 0, 0, 0.3);  
    }  
  
    .quiz-header {  
      display: flex;  
      align-items: center;  
      justify-content: space-between;  
      margin-bottom: 24px;  
      padding-bottom: 16px;  
      border-bottom: 1px solid rgba(255, 255, 255, 0.1);  
    }  
  
    .quiz-progress-text {  
      font-size: 0.85rem;  
      font-weight: 800;  
      color: var(--text-muted);  
    }  
  
    .quiz-question-box h3 {  
      font-family: var(--font-display);  
      font-size: 1.35rem;  
      margin-bottom: 20px;  
      line-height: 1.45;  
    }  
  
    .quiz-options-list {  
      display: flex;  
      flex-direction: column;  
      gap: 14px;  
      margin-bottom: 24px;  
    }  
  
    .quiz-option-btn {  
      background: var(--bg-surface-elevated);  
      border: 2px solid transparent;  
      padding: 16px 20px;  
      border-radius: var(--radius-md);  
      color: var(--text-main);  
      font-size: 1rem;  
      font-family: var(--font-body);  
      font-weight: 700;  
      text-align: left;  
      cursor: pointer;  
      display: flex;  
      align-items: center;  
      justify-content: space-between;  
      transition: all 0.2s;  
    }  
  
    .quiz-option-btn:hover:not(:disabled) {  
      border-color: rgba(99, 102, 241, 0.5);  
      background: rgba(99, 102, 241, 0.1);  
    }  
  
    .quiz-option-btn.correct {  
      background: rgba(16, 185, 129, 0.2) !important;  
      border-color: var(--success) !important;  
      color: #34d399;  
    }  
  
    .quiz-option-btn.wrong {  
      background: rgba(239, 68, 68, 0.2) !important;  
      border-color: var(--danger) !important;  
      color: #f87171;  
    }  
  
    .explanation-callout {  
      background: rgba(245, 158, 11, 0.1);  
      border-left: 4px solid var(--warning);  
      border-radius: 0 var(--radius-sm) var(--radius-sm) 0;  
      padding: 14px 18px;  
      margin-bottom: 20px;  
      font-size: 0.9rem;  
      line-height: 1.5;  
      display: none;  
    }  
  
    .explanation-callout.show { display: block; }  
  
    /* RESULTS VIEW */  
    .result-hero {  
      text-align: center;  
      padding: 40px 20px;  
    }  
  
    .trophy-bounce {  
      font-size: 80px;  
      margin-bottom: 16px;  
      animation: bounce 1s infinite alternate cubic-bezier(0.2, 0.8, 0.2, 1);  
    }  
  
    @keyframes bounce {  
      from { transform: translateY(0); }  
      to { transform: translateY(-16px); }  
    }  
  
    @media (max-width: 820px) {  
      main { padding: 16px; }  
      .hero-banner { flex-direction: column; align-items: flex-start; gap: 16px; }  
      .movie-screen { max-height: 340px; }  
      .spoken-script { font-size: 1rem; }  
    }  
  </style>  
</head>  
<body>  
  
  <!-- Header with Live Gamified Stats -->  
  <header>  
    <div class="brand" onclick="navigateToDashboard()">  
      <div class="brand-icon">📚</div>  
      <div>  
        <div class="brand-title">RUTVI’S STUDY APP</div>  
        <div class="brand-sub">CLASS 7 • MAHARASHTRA STATE BOARD</div>  
      </div>  
    </div>  
    <div class="gamify-hud">  
      <div class="hud-chip stars">⭐ <span id="hud-stars">0</span> Stars</div>  
      <div class="hud-chip xp">⚡ <span id="hud-xp">0</span> XP</div>  
    </div>  
  </header>  
  
  <main>  
    <!-- 1. DASHBOARD VIEW -->  
    <section id="view-dashboard" class="view-panel active">  
      <div class="hero-banner">  
        <div class="hero-text">  
          <h1>Welcome back, Rutvi! 🌟</h1>  
          <p>Ready for today's visual lessons? Dive into your 7 subjects, watch animated chapter stories, and ace the exam challenges.</p>  
        </div>  
        <div>  
          <div style="font-size: 0.85rem; font-weight: 800; color: #a5f3fc;">Overall Mastery: <span id="overall-percentage">0%</span></div>  
          <div class="overall-progress-bar-wrap">  
            <div id="overall-progress-fill" class="overall-progress-fill"></div>  
          </div>  
        </div>  
      </div>  
  
      <div class="section-title">✨ Select a Subject to Begin</div>  
      <div class="subject-grid" id="subject-cards-container"></div>  
    </section>  
  
    <!-- 2. SUBJECT CHAPTER LIST VIEW -->  
    <section id="view-subject" class="view-panel">  
      <button class="btn-back" onclick="navigateToDashboard()">← Back to Dashboard</button>  
      <div class="chapter-hero" id="subject-hero-card"></div>  
      <div class="section-title">📖 Chapter Lessons & Exams</div>  
      <div class="chapter-list" id="chapters-container"></div>  
    </section>  
  
    <!-- 3. VISUAL MOVIE / STORY SCENE PLAYER VIEW -->  
    <section id="view-movie" class="view-panel">  
      <button class="btn-back" onclick="navigateBackToSubject()">← Back to Chapters</button>  
        
      <div class="movie-player-container">  
        <!-- The Visual Scene Stage -->  
        <div class="movie-screen" id="movie-screen">  
          <div class="scene-overlay-badge" id="scene-badge">🎬 Scene 1 of 2</div>  
          <div class="audio-cue-tag" id="audio-cue">🔊 Audio Cue</div>  
          <div id="visual-stage-container" style="width:100%; height:100%; display:flex; align-items:center; justify-content:center;"></div>  
        </div>  
  
        <!-- Narrative Voice / Script Box -->  
        <div class="movie-script-box">  
          <div class="director-note" id="director-note">🎥 Director's Camera Note</div>  
          <div class="spoken-script" id="spoken-script">Loading visual script...</div>  
        </div>  
  
        <!-- Interactive Controls -->  
        <div class="movie-controls">  
          <div class="scene-dots" id="scene-dots-container"></div>  
          <div class="scene-nav-buttons">  
            <button class="btn-circle" onclick="speakCurrentScript()" title="Listen to Narration">🔊</button>  
            <button class="btn-circle" onclick="prevScene()" id="btn-prev-scene">◀</button>  
            <button class="btn-circle" onclick="nextScene()" id="btn-next-scene" style="background: var(--accent-primary);">▶</button>  
          </div>  
        </div>  
      </div>  
    </section>  
  
    <!-- 4. INTERACTIVE QUIZ ARENA VIEW -->  
    <section id="view-quiz" class="view-panel">  
      <button class="btn-back" onclick="navigateBackToSubject()">← Exit Quiz</button>  
        
      <div class="quiz-card-container">  
        <div class="quiz-header">  
          <span class="quiz-progress-text" id="quiz-question-counter">Question 1 of 2</span>  
          <span class="hud-chip stars" id="quiz-live-score">⭐ Score: 0</span>  
        </div>  
  
        <div class="quiz-question-box">  
          <h3 id="quiz-question-text">Question goes here...</h3>  
        </div>  
  
        <div class="quiz-options-list" id="quiz-options-container"></div>  
        <div class="explanation-callout" id="quiz-explanation"></div>  
  
        <div style="text-align: right;">  
          <button class="btn-action btn-quiz" id="btn-quiz-next" style="display:none; margin-left:auto;" onclick="nextQuizQuestion()">Next Question →</button>  
        </div>  
      </div>  
    </section>  
  
    <!-- 5. RESULTS & REWARD VIEW -->  
    <section id="view-result" class="view-panel">  
      <div class="quiz-card-container result-hero">  
        <div class="trophy-bounce">🏆</div>  
        <h2 style="font-family: var(--font-display); font-size: 2rem; margin-bottom: 8px;">Superb Job, Rutvi!</h2>  
        <p style="color: var(--text-muted); margin-bottom: 24px;" id="result-subtitle">You have conquered this lesson with flying colors.</p>  
          
        <div style="display:flex; justify-content:center; gap:20px; margin-bottom: 28px;">  
          <div class="hud-chip stars" style="font-size:1.1rem; padding:10px 20px;">⭐ +<span id="earned-stars">30</span> Stars</div>  
          <div class="hud-chip xp" style="font-size:1.1rem; padding:10px 20px;">⚡ +<span id="earned-xp">60</span> XP</div>  
        </div>  
  
        <button class="btn-action btn-movie" style="margin: 0 auto;" onclick="navigateToDashboard()">Return to Subject Dashboard</button>  
      </div>  
    </section>  
  </main>  
  
  <script>  
    const SYLLABUS_DATA = [  
      {  
        id: "science",  
        title: "General Science",  
        vernacular: "**सामान्य** **विज्ञान**",  
        icon: "🔬",  
        themeColor: "#10b981",  
        summary: "Living adaptations, motion, physical changes, and cellular mysteries.",  
        chapters: [  
          {  
            id: "sci-ch1",  
            number: 1,  
            title: "The Living World: Adaptations",  
            tagline: "Explore how cacti, snow leopards, and fish evolve to master their habitats.",  
            scenes: [  
              {  
                number: 1,  
                title: "Thar Desert: The Thorny Survivor",  
                directorNote: "Wide cinematic shot across scorching desert sands. Slow zoom onto a green cactus.",  
                audioCue: "Dry whistling desert breeze and heat shimmer",  
                script: "Welcome to the scorching Thar Desert. Water is exceedingly scarce. Notice how the Cactus survives: its leaves are not broad; they have transformed into sharp thorns to prevent transpiration! Its fleshy stem turns bright green to perform photosynthesis and store precious water.",  
                svgIllustration: `  
                  <svg viewBox="0 0 600 340" width="100%" height="100%">  
                    <rect width="600" height="340" fill="#f59e0b" opacity="0.3"/>  
                    <circle cx="500" cy="80" r="45" fill="#fef08a" />  
                    <path d="M0 240 Q150 180 300 250 T600 230 L600 340 L0 340 Z" fill="#d97706"/>  
                    <path d="M0 270 Q200 220 400 280 T600 260 L600 340 L0 340 Z" fill="#b45309"/>  
                    <g transform="translate(250, 140)">  
                      <rect x="35" y="20" width="30" height="130" rx="15" fill="#15803d"/>  
                      <path d="M35 80 H15 Q5 80 5 60 V40 Q5 30 15 30 H20" fill="none" stroke="#15803d" stroke-width="14" stroke-linecap="round"/>  
                      <path d="M65 95 H85 Q95 95 95 75 V60 Q95 50 85 50 H80" fill="none" stroke="#15803d" stroke-width="14" stroke-linecap="round"/>  
                      <line x1="25" y1="50" x2="15" y2="45" stroke="#fef08a" stroke-width="3"/>  
                      <line x1="75" y1="85" x2="85" y2="80" stroke="#fef08a" stroke-width="3"/>  
                      <line x1="45" y1="60" x2="45" y2="45" stroke="#fef08a" stroke-width="3"/>  
                      <line x1="55" y1="110" x2="55" y2="95" stroke="#fef08a" stroke-width="3"/>  
                    </g>  
                  </svg>  
                `  
              },  
              {  
                number: 2,  
                title: "Deep Ocean: Spindle-Shaped Fish",  
                directorNote: "Underwater tracking shot. Glistening azure light filtering through currents.",  
                audioCue: "Gentle bubbling underwater ambiance",  
                script: "Now dive below the ocean waves! Look at the fish gliding through the water. Its body is streamlined and spindle-shaped—tapering at both ends like a boat. This cuts water resistance, while gills extract dissolved oxygen and an internal swim bladder keeps it floating effortlessly.",  
                svgIllustration: `  
                  <svg viewBox="0 0 600 340" width="100%" height="100%">  
                    <rect width="600" height="340" fill="#0284c7" opacity="0.4"/>  
                    <circle cx="120" cy="180" r="14" fill="#bae6fd" opacity="0.6"/>  
                    <circle cx="140" cy="120" r="8" fill="#bae6fd" opacity="0.4"/>  
                    <g transform="translate(180, 100)">  
                      <polygon points="40,70 0,25 0,115" fill="#f97316"/>  
                      <ellipse cx="140" cy="70" rx="110" ry="48" fill="#fb923c"/>  
                      <circle cx="210" cy="60" r="8" fill="#ffffff"/>  
                      <circle cx="212" cy="60" r="4" fill="#000000"/>  
                      <path d="M120 70 Q90 95 125 105 Z" fill="#ea580c"/>  
                      <path d="M180 65 Q170 70 180 75" stroke="#7c2d12" stroke-width="3" fill="none"/>  
                    </g>  
                  </svg>  
                `  
              }  
            ],  
            quiz: [  
              {  
                q: "Why are the leaves of desert plants (like Cactus) modified into sharp thorns?",  
                options: [  
                  "To attract morning desert birds",  
                  "To prevent loss of water through transpiration",  
                  "To absorb nitrogen directly from the desert air",  
                  "To produce fragrant pollen"  
                ],  
                correct: 1,  
                explanation: "Class 7 Science Chapter 1: In desert conditions of extreme heat and dryness, leaves turn into thorns to eliminate water loss through transpiration."  
              },  
              {  
                q: "What body shape assists aquatic fish in effortlessly slicing through water?",  
                options: [  
                  "Broad rectangular shape",  
                  "Spindle-shaped, streamlined body tapering at both ends",  
                  "Perfect spherical body",  
                  "Asymmetrical coiled body"  
                ],  
                correct: 1,  
                explanation: "The streamlined, spindle-shaped body minimizes fluid friction, enabling swift aquatic locomotion."  
              }  
            ]  
          }  
        ]  
      },  
      {  
        id: "history",  
        title: "History",  
        vernacular: "**इतिहास**",  
        icon: "⚔️",  
        themeColor: "#8b5cf6",  
        summary: "Medieval India, the Rise of the Maratha Empire, and Chhatrapati Shivaji Maharaj.",  
        chapters: [  
          {  
            id: "hist-ch1",  
            number: 1,  
            title: "Foundation of the Swaraj",  
            tagline: "Relive the historic oath of Swaraj taken by young Shivaji Maharaj at Raireshwar.",  
            scenes: [  
              {  
                number: 1,  
                title: "The Sacred Oath at Raireshwar",  
                directorNote: "Atmospheric, candlelit interior of the secluded temple nestled in the Sahyadri mountains.",  
                audioCue: "Distant mountain thunderstorm and temple bell chime",  
                script: "Year 1645. High in the mist-veiled Sahyadri ranges at Raireshwar Temple, young Shivaji Maharaj gathers his loyal Mavala comrades. Inspired by his mother Jijabai's ideals of justice, Shivaji declares the historic oath: to establish 'Hindavi Swaraj'—a sovereign land free from tyranny and devoted to the welfare of all people.",  
                svgIllustration: `  
                  <svg viewBox="0 0 600 340" width="100%" height="100%">  
                    <rect width="600" height="340" fill="#312e81" opacity="0.6"/>  
                    <polygon points="0,340 120,160 260,340" fill="#1e1b4b"/>  
                    <polygon points="180,340 360,110 520,340" fill="#0f172a"/>  
                    <g transform="translate(360, 90)">  
                      <line x1="0" y1="0" x2="0" y2="120" stroke="#d1d5db" stroke-width="4"/>  
                      <polygon points="0,0 60,20 0,40" fill="#f97316"/>  
                      <polygon points="0,40 60,60 0,80" fill="#f97316"/>  
                    </g>  
                    <circle cx="280" cy="260" r="30" fill="#f59e0b" opacity="0.4"/>  
                    <circle cx="280" cy="260" r="10" fill="#fbbf24"/>  
                  </svg>  
                `  
              }  
            ],  
            quiz: [  
              {  
                q: "At which temple did young Shivaji Maharaj take the sacred oath of founding Swaraj?",  
                options: [  
                  "Bhavani Temple at Tuljapur",  
                  "Raireshwar Temple in the Sahyadris",  
                  "Kailasa Temple at Ellora",  
                  "Trimbakeshwar Temple"  
                ],  
                correct: 1,  
                explanation: "Shivaji Maharaj took the historic pledge to establish Hindavi Swaraj at the Raireshwar temple in the Maval region."  
              }  
            ]  
          }  
        ]  
      },  
      {  
        id: "geography",  
        title: "Geography",  
        vernacular: "**भूगोल**",  
        icon: "🌍",  
        themeColor: "#06b6d4",  
        summary: "Seasons, earth's axial tilt, tides, agriculture, and climate zones.",  
        chapters: [  
          {  
            id: "geo-ch1",  
            number: 1,  
            title: "How Seasons Occur",  
            tagline: "Discover why the Earth's tilted axis gives us summer, monsoon, and winter.",  
            scenes: [  
              {  
                number: 1,  
                title: "The Tilted Axis of Earth",  
                directorNote: "Cosmic view of space. The Sun shines in the center while the Earth orbits on an angle.",  
                audioCue: "Deep, celestial ambient drone",  
                script: "Have you ever wondered why daytime is longer in summer and shorter in winter? It is because the Earth does not stand upright—it is tilted on its axis at 23.5 degrees! As it revolves around the Sun, the hemisphere tilted toward the Sun enjoys longer hours of direct sunlight, causing summer.",  
                svgIllustration: `  
                  <svg viewBox="0 0 600 340" width="100%" height="100%">  
                    <rect width="600" height="340" fill="#030712"/>  
                    <circle cx="140" cy="170" r="60" fill="#f59e0b"/>  
                    <circle cx="140" cy="170" r="75" fill="#fef08a" opacity="0.2"/>  
                    <ellipse cx="300" cy="170" rx="220" ry="80" fill="none" stroke="#334155" stroke-dasharray="6,6" stroke-width="2"/>  
                    <g transform="translate(420, 140)">  
                      <line x1="-15" y1="-50" x2="15" y2="100" stroke="#ef4444" stroke-width="3"/>  
                      <circle cx="0" cy="25" r="40" fill="#0284c7"/>  
                      <ellipse cx="-8" cy="20" rx="14" ry="10" fill="#22c55e"/>  
                      <ellipse cx="14" cy="35" rx="12" ry="8" fill="#22c55e"/>  
                    </g>  
                  </svg>  
                `  
              }  
            ],  
            quiz: [  
              {  
                q: "What is the primary reason for the occurrence of cycles of seasons on Earth?",  
                options: [  
                  "The changing distance between Earth and Mars",  
                  "Earth's tilted axis combined with its revolution around the Sun",  
                  "High speed rotation of the Moon",  
                  "Oceanic surface evaporation"  
                ],  
                correct: 1,  
                explanation: "The Earth's axis remains tilted at 23.5° in the same direction throughout its revolution around the Sun, causing varying seasonal sunlight."  
              }  
            ]  
          }  
        ]  
      },  
      {  
        id: "civics",  
        title: "Civics",  
        vernacular: "**नागरिकशास्त्र**",  
        icon: "⚖️",  
        themeColor: "#eab308",  
        summary: "Introduction to the Indian Constitution, Fundamental Rights, and Duties.",  
        chapters: [  
          {  
            id: "civ-ch1",  
            number: 1,  
            title: "Introduction to Our Constitution",  
            tagline: "Learn how Dr. B.R. Ambedkar and the Constituent Assembly framed the nation's supreme law.",  
            scenes: [  
              {  
                number: 1,  
                title: "The Assembly of Ideals",  
                directorNote: "Stately grand hall of Parliament. Scholarly delegates seated around the Constitution draft.",  
                audioCue: "Dignified orchestral fanfare",  
                script: "A constitution is the supreme law book according to which a nation is governed. For independent India, the Constituent Assembly worked tirelessly for 2 years, 11 months, and 17 days. Dr. Babasaheb Ambedkar, Chairman of the Drafting Committee, shaped our foundational ideals: Justice, Liberty, Equality, and Fraternity.",  
                svgIllustration: `  
                  <svg viewBox="0 0 600 340" width="100%" height="100%">  
                    <rect width="600" height="340" fill="#1e293b"/>  
                    <rect x="60" y="30" width="24" height="260" fill="#475569" rx="4"/>  
                    <rect x="516" y="30" width="24" height="260" fill="#475569" rx="4"/>  
                    <g transform="translate(240, 80)">  
                      <rect x="0" y="0" width="120" height="160" rx="8" fill="#78350f" stroke="#fbbf24" stroke-width="4"/>  
                      <circle cx="60" cy="70" r="26" fill="none" stroke="#fbbf24" stroke-width="3"/>  
                      <circle cx="60" cy="70" r="4" fill="#fbbf24"/>  
                      <line x1="20" y1="120" x2="100" y2="120" stroke="#fef3c7" stroke-width="3"/>  
                      <line x1="30" y1="135" x2="90" y2="135" stroke="#fef3c7" stroke-width="3"/>  
                    </g>  
                  </svg>  
                `  
              }  
            ],  
            quiz: [  
              {  
                q: "Who was the Chairman of the Drafting Committee of the Indian Constitution?",  
                options: [  
                  "Dr. Rajendra Prasad",  
                  "Dr. Babasaheb Ambedkar",  
                  "Mahatma Gandhi",  
                  "Pandit Jawaharlal Nehru"  
                ],  
                correct: 1,  
                explanation: "Dr. B. R. Ambedkar served as Chairman of the Drafting Committee and made vital contributions to drafting the Constitution of India."  
              }  
            ]  
          }  
        ]  
      },  
      {  
        id: "marathi",  
        title: "Marathi Balbharati",  
        vernacular: "**मराठी** **सुलभभारती**",  
        icon: "🚩",  
        themeColor: "#f97316",  
        summary: "**श्यामचे** **बंधुप्रेम**, **स्वप्न** **विकणारा** **माणूस**, **आणि** **सुगम** **मराठी** **व्याकरण**.",  
        chapters: [  
          {  
            id: "mar-ch1",  
            number: 2,  
            title: "**श्यामचे** **बंधुप्रेम** (**साने** **गुरुजी**)",  
            tagline: "**पावसाची** **पर्वा** **न** **करता** **लहान** **भावासाठी** **नवीन** **कोट** **घेऊन** **जाणाऱ्या** **श्यामची** **हृदयस्पर्शी** **गोष्ट**.",  
            scenes: [  
              {  
                number: 1,  
                title: "**मुसळधार** **पाऊस** **आणि** **श्यामचा** **निश्चय**",  
                directorNote: "**दाट** **आभाळ**, **वीजांचा** **कडकडाट** **आणि** **पावसात** **धावणारा** **लहान** **श्याम**.",  
                audioCue: "**मुसळधार** **पावसाचा** **आवाज** **आणि** **वाऱ्याची** **झुळूक**",  
                script: "**मे** **महिन्याच्या** **सुट्टीत** **श्याम** **दापोलीहून** **घरी** **आला** **होता**. **त्याचा** **लहान** **भाऊ** **नेहमी** **नव्या** **कोटासाठी** **हट्ट** **करत** **असे**. **श्यामने** **स्वतःचे** **खाऊचे** **पैसे** **साठवून** **आपल्या** **धाकट्या** **भावासाठी** **एक** **सुंदर** **निळा** **कोट** **शिवून** **घेतला**. **मुसळधार** **पाऊस** **सुरू** **होता**, **नदी**-**नाले** **भरून** **वाहत** **होते**; **पण** **भावाच्या** **प्रेमापोटी** **श्याम** **अनवाणी** **धावत** **घराकडे** **निघाला**!",  
                svgIllustration: `  
                  <svg viewBox="0 0 600 340" width="100%" height="100%">  
                    <rect width="600" height="340" fill="#1e3a8a" opacity="0.6"/>  
                    <line x1="80" y1="20" x2="40" y2="140" stroke="#93c5fd" stroke-width="2"/>  
                    <line x1="220" y1="10" x2="180" y2="160" stroke="#93c5fd" stroke-width="2"/>  
                    <line x1="440" y1="30" x2="400" y2="180" stroke="#93c5fd" stroke-width="2"/>  
                    <path d="M0 240 Q150 200 300 240 T600 220 L600 340 L0 340 Z" fill="#1d4ed8"/>  
                    <g transform="translate(260, 150)">  
                      <circle cx="20" cy="20" r="14" fill="#fed7aa"/>  
                      <rect x="10" y="34" width="20" height="40" fill="#ea580c" rx="4"/>  
                      <rect x="24" y="44" width="22" height="18" fill="#3b82f6" stroke="#fbbf24" stroke-width="2" rx="3"/>  
                    </g>  
                  </svg>  
                `  
              }  
            ],  
            quiz: [  
              {  
                q: "**श्यामने** **स्वतःच्या** **खाऊचे** **पैसे** **साठवून** **लहान** **भावासाठी** **काय** **शिवून** **घेतले** **होते**?",  
                options: [  
                  "**नवीन** **टोपी**",  
                  "**सुंदर** **कोट**",  
                  "**रंगीत** **दप्तर**",  
                  "**नवीन** **चप्पल**"  
                ],  
                correct: 1,  
                explanation: "**साने** **गुरुजींच्या** '**श्यामचे** **बंधुप्रेम**' **या** **पाठात** **श्यामने** **खाऊचे** **पैसे** **वाचवून** **लहान** **भावासाठी** **प्रेमाने** **नवीन** **कोट** **शिवून** **घेतला** **होता**."  
              }  
            ]  
          }  
        ]  
      },  
      {  
        id: "hindi",  
        title: "Hindi Sulabhbharati",  
        vernacular: "**हिंदी** **सुलभभारती**",  
        icon: "🪶",  
        themeColor: "#ec4899",  
        summary: "**फूल** **और** **काँटा**, **दादी** **माँ** **का** **परिवार**, **और** **प्रेरणादायी** **बाल** **कहानियाँ।**",  
        chapters: [  
          {  
            id: "hin-ch1",  
            number: 2,  
            title: "**फूल** **और** **काँटा** (**अयोध्यासिंह** **उपाध्याय** '**हरिऔध**')",  
            tagline: "**एक** **ही** **पौधे** **पर** **रहकर** **फूल** **और** **काँटा** **अपने** **कर्मों** **से** **कैसे** **भिन्न** **बनते** **हैं**?",  
            scenes: [  
              {  
                number: 1,  
                title: "**एक** **ही** **पौधे** **का** **संसार**",  
                directorNote: "**हरे**-**भरे** **बगीचे** **में** **गुलाब** **के** **पौधे** **पर** **खिले** **कोमल** **फूल** **और** **उसके** **नीचे** **के** **नुकीले** **काँटे** **का** **क्लोज**-**अप।**",  
                audioCue: "**मधुमक्खियों** **की** **भिनभिनाहट** **और** **मंद** **हवा**",  
                script: "**कवि** **कहते** **हैं**: **फूल** **और** **काँटा** **दोनों** **एक** **ही** **पौधे** **पर** **जन्म** **लेते** **हैं।** **एक** **ही** **हवा** **और** **एक** **ही** **चाँदनी** **दोनों** **को** **पालती** **है।** **लेकिन** **काँटा** **दूसरों** **की** **उँगलियों** **में** **चुभकर** **लहूलुहान** **करता** **है**, **जबकि** **फूल** **अपनी** **सुगंध** **और** **मिठास** **से** **तितलियों** **और** **भौरों** **को** **गले** **लगाता** **है।** **बड़प्पन** **कुल** **से** **नहीं**, **कर्म** **से** **मिलता** **है**!",  
                svgIllustration: `  
                  <svg viewBox="0 0 600 340" width="100%" height="100%">  
                    <rect width="600" height="340" fill="#831843" opacity="0.3"/>  
                    <circle cx="480" cy="70" r="50" fill="#fef08a" opacity="0.4"/>  
                    <path d="M300 340 Q310 200 280 100" stroke="#15803d" stroke-width="12" fill="none"/>  
                    <polygon points="296,240 260,225 296,230" fill="#14532d"/>  
                    <polygon points="304,180 340,165 304,170" fill="#14532d"/>  
                    <g transform="translate(280, 90)">  
                      <circle cx="0" cy="0" r="34" fill="#f43f5e"/>  
                      <circle cx="-20" cy="-20" r="22" fill="#fb7185"/>  
                      <circle cx="20" cy="-20" r="22" fill="#fb7185"/>  
                      <circle cx="0" cy="0" r="14" fill="#fef08a"/>  
                    </g>  
                  </svg>  
                `  
              }  
            ],  
            quiz: [  
              {  
                q: "**कविता** '**फूल** **और** **काँटा**' **के** **अनुसार** **मनुष्य** **का** **बड़प्पन** **किससे** **आंका** **जाता** **है**?",  
                options: [  
                  "**उच्च** **कुल** **या** **खानदान** **में** **जन्म** **लेने** **से**",  
                  "**उसके** **अच्छे** **और** **परोपकारी** **कर्मों** **से**",  
                  "**कीमती** **वस्त्र** **पहनने** **से**",  
                  "**धन**-**दौलत** **के** **संग्रह** **से**"  
                ],  
                correct: 1,  
                explanation: "**कवि** **हरिऔध** **जी** **समझाते** **हैं** **कि** **इंसान** **केवल** **ऊँचे** **कुल** **में** **जन्म** **लेने** **से** **नहीं**, **बल्कि** **अपने** **भले** **स्वभाव** **और** **कर्मों** **से** **बड़ा** **बनता** **है।**"  
              }  
            ]  
          }  
        ]  
      },  
      {  
        id: "english",  
        title: "English Balbharati",  
        vernacular: "**इंग्रजी** **बालभारती**",  
        icon: "📖",  
        themeColor: "#3b82f6",  
        summary: "Odd One In, Past Present Future, In a Glass of Water, and Grammar.",  
        chapters: [  
          {  
            id: "eng-ch1",  
            number: 1,  
            title: "Odd One In",  
            tagline: "A poignant story about empathy, understanding, and friendship in school.",  
            scenes: [  
              {  
                number: 1,  
                title: "Malti's First Day in the Big City School",  
                directorNote: "A bustling, cheerful modern school classroom. Students laughing and chattering.",  
                audioCue: "School corridor bell ringing and joyful student murmurs",  
                script: "Malti, a gifted girl from a rural school, walks into a modern city classroom with oil in her hair and a shy bindi. Some girls whisper and giggle at her appearance. But when the teacher poses challenging questions, Malti's sharp intellect and pure heart shine brighter than all prejudice!",  
                svgIllustration: `  
                  <svg viewBox="0 0 600 340" width="100%" height="100%">  
                    <rect width="600" height="340" fill="#1e293b"/>  
                    <rect x="140" y="30" width="320" height="150" rx="6" fill="#064e3b" stroke="#78350f" stroke-width="10"/>  
                    <text x="180" y="80" fill="#a7f3d0" font-family="Nunito" font-size="20" font-weight="700">English Class 7</text>  
                    <text x="180" y="120" fill="#fef08a" font-family="Nunito" font-size="16">Be Kind & Welcoming ✨</text>  
                    <rect x="80" y="240" width="160" height="80" fill="#92400e" rx="4"/>  
                    <rect x="360" y="240" width="160" height="80" fill="#92400e" rx="4"/>  
                  </svg>  
                `  
              }  
            ],  
            quiz: [  
              {  
                q: "What is the central moral lesson highlighted in the story 'Odd One In'?",  
                options: [  
                  "Always wear branded shoes to school",  
                  "Never judge a person solely by their external appearance or background",  
                  "Only study mathematics and science",  
                  "Avoid speaking with new classmates"  
                ],  
                correct: 1,  
                explanation: "The chapter teaches students to respect diversity, overcome superficial biases, and welcome everyone with an open heart."  
              }  
            ]  
          }  
        ]  
      }  
    ];  
  
    let AppState = {  
      stars: parseInt(localStorage.getItem('rutvi_app_stars') || '0'),  
      xp: parseInt(localStorage.getItem('rutvi_app_xp') || '0'),  
      completedChapters: JSON.parse(localStorage.getItem('rutvi_completed_chapters') || '[]'),  
      currentSubject: null,  
      currentChapter: null,  
      currentSceneIndex: 0,  
      currentQuizIndex: 0,  
      currentQuizScore: 0  
    };  
  
    const AudioEngine = {  
      ctx: null,  
      init() {  
        if (!this.ctx) {  
          const AudioContext = window.AudioContext || window.webkitAudioContext;  
          if (AudioContext) this.ctx = new AudioContext();  
        }  
      },  
      playChime(type) {  
        try {  
          this.init();  
          if (!this.ctx) return;  
          const osc = this.ctx.createOscillator();  
          const gain = this.ctx.createGain();  
          osc.connect(gain);  
          gain.connect(this.ctx.destination);  
            
          const now = this.ctx.currentTime;  
          if (type === 'correct') {  
            osc.frequency.setValueAtTime(523.25, now);  
            osc.frequency.exponentialRampToValueAtTime(783.99, now + 0.2);  
            gain.gain.setValueAtTime(0.2, now);  
            gain.gain.exponentialRampToValueAtTime(0.001, now + 0.35);  
            osc.start(now);  
            osc.stop(now + 0.35);  
          } else if (type === 'wrong') {  
            osc.frequency.setValueAtTime(220, now);  
            osc.frequency.setValueAtTime(196, now + 0.15);  
            gain.gain.setValueAtTime(0.2, now);  
            gain.gain.exponentialRampToValueAtTime(0.001, now + 0.3);  
            osc.start(now);  
            osc.stop(now + 0.3);  
          } else if (type === 'click') {  
            osc.frequency.setValueAtTime(600, now);  
            gain.gain.setValueAtTime(0.08, now);  
            gain.gain.exponentialRampToValueAtTime(0.001, now + 0.08);  
            osc.start(now);  
            osc.stop(now + 0.08);  
          }  
        } catch (e) {}  
      }  
    };  
  
    function saveState() {  
      localStorage.setItem('rutvi_app_stars', AppState.stars);  
      localStorage.setItem('rutvi_app_xp', AppState.xp);  
      localStorage.setItem('rutvi_completed_chapters', JSON.stringify(AppState.completedChapters));  
      updateHUD();  
    }  
  
    function updateHUD() {  
      document.getElementById('hud-stars').innerText = AppState.stars;  
      document.getElementById('hud-xp').innerText = AppState.xp;  
  
      let totalChapters = 0;  
      SYLLABUS_DATA.forEach(sub => totalChapters += sub.chapters.length);  
      const completedCount = AppState.completedChapters.length;  
      const pct = totalChapters > 0 ? Math.round((completedCount / totalChapters) * 100) : 0;  
        
      const fillEl = document.getElementById('overall-progress-fill');  
      const textEl = document.getElementById('overall-percentage');  
      if (fillEl && textEl) {  
        fillEl.style.width = pct + '%';  
        textEl.innerText = pct + '%';  
      }  
    }  
  
    function showPanel(panelId) {  
      document.querySelectorAll('.view-panel').forEach(p => p.classList.remove('active'));  
      const target = document.getElementById(panelId);  
      if (target) target.classList.add('active');  
      window.scrollTo({ top: 0, behavior: 'smooth' });  
    }  
  
    function navigateToDashboard() {  
      AudioEngine.playChime('click');  
      window.speechSynthesis && window.speechSynthesis.cancel();  
      renderDashboard();  
      showPanel('view-dashboard');  
    }  
  
    function navigateBackToSubject() {  
      AudioEngine.playChime('click');  
      window.speechSynthesis && window.speechSynthesis.cancel();  
      if (AppState.currentSubject) {  
        openSubject(AppState.currentSubject.id);  
      } else {  
        navigateToDashboard();  
      }  
    }  
  
    function renderDashboard() {  
      updateHUD();  
      const container = document.getElementById('subject-cards-container');  
      container.innerHTML = '';  
  
      SYLLABUS_DATA.forEach(sub => {  
        const completedInSub = sub.chapters.filter(c => AppState.completedChapters.includes(c.id)).length;  
        const subPct = Math.round((completedInSub / sub.chapters.length) * 100);  
  
        const card = document.createElement('div');  
        card.className = 'subject-card';  
        card.onclick = () => openSubject(sub.id);  
  
        card.innerHTML = `  
          <div class="subject-card-top">  
            <div class="subject-badge" style="background: ${sub.themeColor}22; color: ${sub.themeColor}">  
              ${sub.icon}  
            </div>  
            <div class="subject-completion">${subPct}% Done</div>  
          </div>  
          <div class="subject-info">  
            <h3>${sub.title}</h3>  
            <p>${sub.vernacular} • ${sub.summary}</p>  
          </div>  
          <div class="card-progress-bar">  
            <div class="card-progress-fill" style="width: ${subPct}%; background: ${sub.themeColor};"></div>  
          </div>  
        `;  
        container.appendChild(card);  
      });  
    }  
  
    function openSubject(subjectId) {  
      AudioEngine.playChime('click');  
      const subject = SYLLABUS_DATA.find(s => s.id === subjectId);  
      if (!subject) return;  
  
      AppState.currentSubject = subject;  
  
      const heroContainer = document.getElementById('subject-hero-card');  
      heroContainer.innerHTML = `  
        <div style="display:flex; align-items:center; gap:16px;">  
          <div style="font-size: 40px; background:${subject.themeColor}22; padding:12px; border-radius:12px;">${subject.icon}</div>  
          <div>  
            <h2 style="font-family: var(--font-display); font-size:1.75rem;">${subject.title}</h2>  
            <p style="color:var(--text-muted); font-size:0.95rem;">${subject.vernacular} • Maharashtra Board Curriculum</p>  
          </div>  
        </div>  
      `;  
  
      const chaptersContainer = document.getElementById('chapters-container');  
      chaptersContainer.innerHTML = '';  
  
      subject.chapters.forEach(ch => {  
        const completed = AppState.completedChapters.includes(ch.id);  
        const card = document.createElement('div');  
        card.className = 'chapter-card';  
        card.innerHTML = `  
          <div class="chapter-meta">  
            <h4>Chapter ${ch.number}: ${ch.title} ${completed ? '✅' : ''}</h4>  
            <p>${ch.tagline}</p>  
          </div>  
          <div class="chapter-actions">  
            <button class="btn-action btn-movie" onclick="startMovieMode('${ch.id}')">  
              🎬 Watch Lesson  
            </button>  
            <button class="btn-action btn-quiz" onclick="startQuizArena('${ch.id}')">  
              📝 Test  
            </button>  
          </div>  
        `;  
        chaptersContainer.appendChild(card);  
      });  
  
      showPanel('view-subject');  
    }  
  
    function startMovieMode(chapterId) {  
      AudioEngine.playChime('click');  
      const chapter = AppState.currentSubject.chapters.find(c => c.id === chapterId);  
      if (!chapter) return;  
  
      AppState.currentChapter = chapter;  
      AppState.currentSceneIndex = 0;  
  
      renderScene();  
      showPanel('view-movie');  
    }  
  
    function renderScene() {  
      const chapter = AppState.currentChapter;  
      const scene = chapter.scenes[AppState.currentSceneIndex];  
      const totalScenes = chapter.scenes.length;  
  
      document.getElementById('scene-badge').innerHTML = `🎬 Scene ${AppState.currentSceneIndex + 1} of ${totalScenes}`;  
      document.getElementById('audio-cue').innerHTML = `🔊 ${scene.audioCue}`;  
      document.getElementById('visual-stage-container').innerHTML = scene.svgIllustration;  
  
      document.getElementById('director-note').innerHTML = `🎥 ${scene.directorNote}`;  
      document.getElementById('spoken-script').innerHTML = scene.script;  
  
      const dotsContainer = document.getElementById('scene-dots-container');  
      dotsContainer.innerHTML = '';  
      for (let i = 0; i < totalScenes; i++) {  
        const dot = document.createElement('div');  
        dot.className = `scene-dot ${i === AppState.currentSceneIndex ? 'active' : ''}`;  
        dotsContainer.appendChild(dot);  
      }  
  
      document.getElementById('btn-prev-scene').disabled = AppState.currentSceneIndex === 0;  
      const nextBtn = document.getElementById('btn-next-scene');  
      if (AppState.currentSceneIndex === totalScenes - 1) {  
        nextBtn.innerHTML = '📝 Start Quiz';  
        nextBtn.style.background = 'var(--success)';  
      } else {  
        nextBtn.innerHTML = '▶';  
        nextBtn.style.background = 'var(--accent-primary)';  
      }  
  
      speakCurrentScript();  
    }  
  
    function nextScene() {  
      AudioEngine.playChime('click');  
      const totalScenes = AppState.currentChapter.scenes.length;  
      if (AppState.currentSceneIndex < totalScenes - 1) {  
        AppState.currentSceneIndex++;  
        renderScene();  
      } else {  
        startQuizArena(AppState.currentChapter.id);  
      }  
    }  
  
    function prevScene() {  
      AudioEngine.playChime('click');  
      if (AppState.currentSceneIndex > 0) {  
        AppState.currentSceneIndex--;  
        renderScene();  
      }  
    }  
  
    function speakCurrentScript() {  
      if ('speechSynthesis' in window) {  
        window.speechSynthesis.cancel();  
        const script = AppState.currentChapter.scenes[AppState.currentSceneIndex].script;  
        const utterance = new SpeechSynthesisUtterance(script);  
        utterance.rate = 0.95;  
        utterance.pitch = 1.05;  
        window.speechSynthesis.speak(utterance);  
      }  
    }  
  
    function startQuizArena(chapterId) {  
      AudioEngine.playChime('click');  
      window.speechSynthesis && window.speechSynthesis.cancel();  
  
      const chapter = AppState.currentSubject.chapters.find(c => c.id === chapterId);  
      if (!chapter) return;  
  
      AppState.currentChapter = chapter;  
      AppState.currentQuizIndex = 0;  
      AppState.currentQuizScore = 0;  
  
      renderQuizQuestion();  
      showPanel('view-quiz');  
    }  
  
    function renderQuizQuestion() {  
      const quiz = AppState.currentChapter.quiz;  
      const qData = quiz[AppState.currentQuizIndex];  
  
      document.getElementById('quiz-question-counter').innerText = `Question ${AppState.currentQuizIndex + 1} of ${quiz.length}`;  
      document.getElementById('quiz-live-score').innerText = `⭐ Score: ${AppState.currentQuizScore}`;  
      document.getElementById('quiz-question-text').innerText = qData.q;  
  
      const explanationEl = document.getElementById('quiz-explanation');  
      explanationEl.className = 'explanation-callout';  
      explanationEl.innerHTML = '';  
  
      const nextBtn = document.getElementById('btn-quiz-next');  
      nextBtn.style.display = 'none';  
  
      const optionsContainer = document.getElementById('quiz-options-container');  
      optionsContainer.innerHTML = '';  
  
      qData.options.forEach((opt, idx) => {  
        const btn = document.createElement('button');  
        btn.className = 'quiz-option-btn';  
        btn.innerHTML = `<span>${opt}</span><span id="opt-icon-${idx}">⚪</span>`;  
        btn.onclick = () => selectQuizAnswer(idx, qData.correct, qData.explanation);  
        optionsContainer.appendChild(btn);  
      });  
    }  
  
    function selectQuizAnswer(selectedIdx, correctIdx, explanation) {  
      const allButtons = document.querySelectorAll('.quiz-option-btn');  
      allButtons.forEach(b => b.disabled = true);  
  
      const explanationEl = document.getElementById('quiz-explanation');  
      explanationEl.innerHTML = `<strong>💡 Board Solution Note:</strong> ${explanation}`;  
      explanationEl.classList.add('show');  
  
      if (selectedIdx === correctIdx) {  
        AudioEngine.playChime('correct');  
        allButtons[selectedIdx].classList.add('correct');  
        document.getElementById(`opt-icon-${selectedIdx}`).innerText = '✅';  
        AppState.currentQuizScore += 10;  
        document.getElementById('quiz-live-score').innerText = `⭐ Score: ${AppState.currentQuizScore}`;  
      } else {  
        AudioEngine.playChime('wrong');  
        allButtons[selectedIdx].classList.add('wrong');  
        document.getElementById(`opt-icon-${selectedIdx}`).innerText = '❌';  
        allButtons[correctIdx].classList.add('correct');  
        document.getElementById(`opt-icon-${correctIdx}`).innerText = '✅';  
      }  
  
      document.getElementById('btn-quiz-next').style.display = 'block';  
    }  
  
    function nextQuizQuestion() {  
      AudioEngine.playChime('click');  
      const quiz = AppState.currentChapter.quiz;  
      if (AppState.currentQuizIndex < quiz.length - 1) {  
        AppState.currentQuizIndex++;  
        renderQuizQuestion();  
      } else {  
        finishQuiz();  
      }  
    }  
  
    function finishQuiz() {  
      AppState.stars += 30;  
      AppState.xp += 60;  
  
      if (!AppState.completedChapters.includes(AppState.currentChapter.id)) {  
        AppState.completedChapters.push(AppState.currentChapter.id);  
      }  
  
      saveState();  
  
      document.getElementById('earned-stars').innerText = '30';  
      document.getElementById('earned-xp').innerText = '60';  
      document.getElementById('result-subtitle').innerText = `You finished the exam for ${AppState.currentChapter.title} with a score of ${AppState.currentQuizScore}!`;  
  
      AudioEngine.playChime('correct');  
      showPanel('view-result');  
    }  
  
    window.addEventListener('DOMContentLoaded', () => {  
      renderDashboard();  
    });  
  </script>  
</body>  
</html>  
