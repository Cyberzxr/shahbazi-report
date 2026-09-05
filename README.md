<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=yes" />
    <title>⚔️ شمشیرعلی – گزارش کانال شهبازی</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Inter:wght@300;400;600;700;800&display=swap');

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', 'Segoe UI', sans-serif;
            background: #0a0a0f;
            color: #e0e0e0;
            min-height: 100vh;
            padding: 16px;
            background-image:
                radial-gradient(ellipse at 10% 20%, rgba(0, 255, 0, 0.04) 0%, transparent 50%),
                radial-gradient(ellipse at 90% 80%, rgba(255, 0, 0, 0.04) 0%, transparent 50%);
        }

        .container {
            max-width: 1100px;
            width: 100%;
            margin: 0 auto;
            background: rgba(16, 16, 24, 0.95);
            backdrop-filter: blur(16px);
            border-radius: 36px;
            padding: 44px 38px;
            border: 2px solid rgba(0, 255, 0, 0.3);
            box-shadow: 0 30px 70px rgba(0, 0, 0, 0.85), 0 0 0 1px rgba(0, 255, 0, 0.1) inset;
        }

        .header {
            text-align: center;
            margin-bottom: 28px;
            border-bottom: 2px solid rgba(0, 255, 0, 0.2);
            padding-bottom: 20px;
        }

        .flag-icon {
            font-size: 52px;
            display: inline-block;
            margin: 0 10px;
            filter: drop-shadow(0 0 20px rgba(0, 255, 0, 0.3));
            animation: flagPulse 3s ease-in-out infinite;
        }

        @keyframes flagPulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }

        .title {
            font-family: 'Orbitron', monospace;
            font-size: 38px;
            font-weight: 700;
            background: linear-gradient(135deg, #00ff00, #ffffff, #ff0000);
            background-size: 300% 300%;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: shimmer 4s ease-in-out infinite;
            letter-spacing: 3px;
            display: inline-block;
        }

        @keyframes shimmer {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .iran-flag {
            display: inline-block;
            background: linear-gradient(to bottom, #00ff00 33%, #ffffff 33%, #ffffff 66%, #ff0000 66%);
            padding: 8px 32px;
            border-radius: 40px;
            color: #000;
            font-weight: 800;
            font-size: 16px;
            border: 2px solid #00ff00;
            text-shadow: 0 0 20px rgba(255, 255, 255, 0.3);
            margin-top: 10px;
            letter-spacing: 2px;
        }

        .badge {
            display: inline-block;
            background: rgba(0, 255, 0, 0.12);
            border: 1px solid rgba(0, 255, 0, 0.25);
            border-radius: 100px;
            padding: 6px 22px;
            font-size: 12px;
            letter-spacing: 2.5px;
            color: #00ff00;
            text-transform: uppercase;
            font-weight: 700;
            margin-bottom: 12px;
        }

        .info-box {
            background: rgba(0, 255, 0, 0.04);
            border-radius: 16px;
            padding: 16px 20px;
            margin-bottom: 14px;
            border: 1px solid rgba(0, 255, 0, 0.12);
            font-size: 14px;
        }

        .info-box strong {
            color: #00ff00;
        }

        .to-box {
            background: rgba(255, 0, 0, 0.04);
            border-radius: 16px;
            padding: 14px 20px;
            margin-bottom: 14px;
            border: 1px solid rgba(255, 0, 0, 0.12);
            font-size: 13.5px;
            color: #8892b0;
            text-align: center;
        }

        .to-box .addr {
            color: #4488ff;
            font-weight: 600;
            direction: ltr;
            display: inline-block;
            margin: 0 4px;
        }

        .to-box .addr-main {
            color: #ff4444;
            font-weight: 700;
            direction: ltr;
            display: inline-block;
            margin: 0 4px;
            background: rgba(255, 0, 0, 0.12);
            padding: 2px 12px;
            border-radius: 20px;
            border: 1px solid rgba(255, 0, 0, 0.25);
            font-size: 17px;
        }

        .to-box .label-main {
            color: #e0e0e0;
            font-weight: 600;
            font-size: 14px;
        }

        .id-box {
            background: rgba(0, 255, 0, 0.05);
            border-radius: 12px;
            padding: 10px 18px;
            border: 1px solid rgba(0, 255, 0, 0.1);
            font-size: 14px;
            text-align: center;
            margin-bottom: 14px;
            color: #00ff00;
        }

        .id-box strong {
            color: #fff;
        }

        .email-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin-top: 15px;
        }

        .email-card {
            background: rgba(255, 255, 255, 0.02);
            border-radius: 18px;
            padding: 20px;
            border: 1px solid rgba(0, 255, 0, 0.12);
            transition: all 0.3s ease;
        }

        .email-card:hover {
            border-color: rgba(0, 255, 0, 0.35);
            background: rgba(0, 255, 0, 0.04);
            box-shadow: 0 8px 35px rgba(0, 0, 0, 0.4);
        }

        .email-card .num {
            color: #00ff00;
            font-weight: 700;
            font-size: 13px;
            margin-bottom: 4px;
        }

        .email-card .subject {
            color: #e6f1ff;
            font-weight: 700;
            font-size: 15px;
            margin: 4px 0 8px;
            line-height: 1.4;
        }

        .email-card .body-preview {
            color: #c9d1d9;
            font-size: 12px;
            direction: ltr;
            text-align: left;
            font-family: 'Courier New', monospace;
            white-space: pre-wrap;
            word-break: break-word;
            line-height: 1.8;
            max-height: 180px;
            overflow-y: auto;
            padding: 12px 14px;
            background: rgba(0, 0, 0, 0.35);
            border-radius: 10px;
            margin-bottom: 10px;
            border: 1px solid rgba(0, 255, 0, 0.06);
        }

        .email-card .body-preview::-webkit-scrollbar {
            width: 3px;
        }
        .email-card .body-preview::-webkit-scrollbar-thumb {
            background: #00ff00;
            border-radius: 10px;
        }

        .email-card .links {
            font-size: 10px;
            color: #4488ff;
            margin: 6px 0;
            direction: ltr;
            text-align: left;
        }

        .email-card .links a {
            color: #4488ff;
            text-decoration: none;
        }

        .email-card .links a:hover {
            text-decoration: underline;
        }

        .btn-group {
            display: flex;
            gap: 6px;
            flex-wrap: wrap;
            margin-top: 10px;
        }

        .btn-gmail {
            background: linear-gradient(135deg, #00cc00, #009900);
            color: #fff;
            padding: 6px 14px;
            border-radius: 8px;
            font-size: 11px;
            font-weight: 700;
            border: none;
            cursor: pointer;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            gap: 4px;
            transition: all 0.2s ease;
            flex: 1;
            justify-content: center;
            min-width: 80px;
        }

        .btn-gmail:hover {
            transform: scale(0.95);
            box-shadow: 0 0 20px rgba(0, 255, 0, 0.3);
        }

        .btn-email {
            background: linear-gradient(135deg, #0066ff, #0044cc);
            color: #fff;
            padding: 6px 14px;
            border-radius: 8px;
            font-size: 11px;
            font-weight: 700;
            border: none;
            cursor: pointer;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            gap: 4px;
            transition: all 0.2s ease;
            flex: 1;
            justify-content: center;
            min-width: 80px;
        }

        .btn-email:hover {
            transform: scale(0.95);
            box-shadow: 0 0 20px rgba(0, 100, 255, 0.3);
        }

        .btn-copy {
            background: linear-gradient(135deg, #cc0000, #990000);
            color: #fff;
            padding: 6px 14px;
            border-radius: 8px;
            font-size: 11px;
            font-weight: 700;
            border: none;
            cursor: pointer;
            display: inline-flex;
            align-items: center;
            gap: 4px;
            transition: all 0.2s ease;
            flex: 1;
            justify-content: center;
            min-width: 80px;
        }

        .btn-copy:hover {
            transform: scale(0.95);
            box-shadow: 0 0 20px rgba(255, 0, 0, 0.3);
        }

        .status-msg {
            text-align: center;
            font-size: 12px;
            color: #8892b0;
            margin-top: 6px;
            min-height: 18px;
        }

        .pagination {
            display: flex;
            justify-content: center;
            gap: 6px;
            flex-wrap: wrap;
            margin: 15px 0;
        }

        .page-btn {
            background: rgba(0, 255, 0, 0.06);
            color: #8892b0;
            border: 1px solid rgba(0, 255, 0, 0.12);
            padding: 4px 14px;
            border-radius: 6px;
            font-size: 12px;
            cursor: pointer;
            transition: 0.2s;
        }

        .page-btn:hover {
            background: rgba(0, 255, 0, 0.12);
            color: #fff;
        }

        .page-btn.active {
            background: #00ff00;
            color: #000;
            border-color: #00ff00;
            font-weight: 700;
        }

        .counter {
            text-align: center;
            color: #8892b0;
            font-size: 13px;
            margin: 10px 0;
        }

        .footer {
            text-align: center;
            font-size: 12px;
            color: #495670;
            margin-top: 28px;
            border-top: 1px solid rgba(0, 255, 0, 0.08);
            padding-top: 22px;
        }

        .footer-links {
            display: flex;
            justify-content: center;
            gap: 24px;
            flex-wrap: wrap;
            margin-top: 10px;
        }

        .search-box {
            width: 100%;
            padding: 12px 18px;
            border-radius: 12px;
            border: 1px solid rgba(0, 255, 0, 0.12);
            background: #0d1117;
            color: #c9d1d9;
            font-size: 14px;
            margin-bottom: 15px;
        }

        .search-box:focus {
            outline: none;
            border-color: #00ff00;
        }

        .nav-bar {
            display: flex;
            justify-content: center;
            gap: 12px;
            margin: 10px 0;
        }

        .nav-btn {
            background: rgba(0, 255, 0, 0.06);
            color: #c9d1d9;
            border: 1px solid rgba(0, 255, 0, 0.12);
            padding: 6px 20px;
            border-radius: 8px;
            font-size: 13px;
            font-weight: 600;
            cursor: pointer;
            transition: 0.2s;
        }

        .nav-btn:hover {
            background: rgba(0, 255, 0, 0.12);
        }

        .nav-btn:disabled {
            opacity: 0.3;
            cursor: not-allowed;
        }

        @media (max-width: 768px) {
            .email-grid {
                grid-template-columns: 1fr;
            }
            .container {
                padding: 20px 16px;
            }
            .title {
                font-size: 28px;
            }
            .email-card .body-preview {
                font-size: 11px;
                max-height: 150px;
            }
            .btn-gmail,
            .btn-email,
            .btn-copy {
                font-size: 10px;
                padding: 5px 10px;
                min-width: 60px;
            }
        }
    </style>
</head>
<body>

    <div class="container">

        <!-- HEADER -->
        <div class="header">
            <div class="badge">⚡ 100 Reports | شهبازی Channel</div>
            <div>
                <span class="flag-icon">🇮🇷</span>
                <span class="title">⚔️ Shamshir Ali</span>
                <span class="flag-icon">🇮🇷</span>
            </div>
            <div class="iran-flag">جمهوری اسلامی ایران</div>
            <p class="sub">100 Unique Reports – Based on Telegram International Rules</p>
        </div>

        <!-- INFO -->
        <div class="info-box">
            <strong>📌 Target Channel:</strong> محمد مهدی شهبازی | اندیشه های من &nbsp;|&nbsp;
            <strong>🆔 ID:</strong> 2281180779<br />
            <strong>⚠️ Violations Found:</strong> Phishing, Fake News, Drugs, Hate Speech
        </div>

        <div class="to-box">
            <span class="label-main">📨 Send to:</span><br />
            <span class="addr-main">grievance-in@telegram.org</span><br /><br />
            <span style="color:#495670; font-size:13px;">✧ Backup:</span><br />
            <span class="addr">abuse@telegram.org</span> &nbsp;|&nbsp;
            <span class="addr">dmca@telegram.org</span> &nbsp;|&nbsp;
            <span class="addr">security@telegram.org</span>
        </div>

        <input class="search-box" id="searchBox" type="text" placeholder="🔍 Search emails..." oninput="renderPage()">

        <div class="counter" id="counterDisplay">Showing 1-20 of 100 emails</div>

        <div class="nav-bar">
            <button class="nav-btn" onclick="prevPage()">◀ Previous</button>
            <span id="pageInfo" style="color:#8b949e;display:flex;align-items:center;font-size:13px;">Page 1 of 5</span>
            <button class="nav-btn" onclick="nextPage()">Next ▶</button>
        </div>

        <div class="email-grid" id="emailGrid"></div>

        <div class="pagination" id="pagination"></div>

        <div class="footer">
            📨 Send to: grievance-in@telegram.org (Primary) | abuse@telegram.org | dmca@telegram.org |
            security@telegram.org
            <div class="footer-links">
                <span>© 2026 Shamshir Ali</span>
                <span style="color:#00ff00;">🇮🇷</span>
            </div>
        </div>
    </div>

    <script>
        // ============================================================
        // CONFIGURATION
        // ============================================================
        const TO_EMAILS = ["grievance-in@telegram.org", "abuse@telegram.org", "dmca@telegram.org",
            "security@telegram.org"
        ];
        const CHANNEL_NAME = "محمد مهدی شهبازی | اندیشه های من";
        const CHANNEL_ID = "2281180779";

        const VIOLATIONS = [
            "PHISHING (Fake financial scams)",
            "FAKE NEWS (Misinformation)",
            "DRUGS (Illegal substance promotion)",
            "HATE SPEECH (Discriminatory content)"
        ];

        const VIOLATION_DETAILS = [
            "The channel publishes phishing content impersonating US government agencies to scam users.",
            "The channel spreads fake news and misinformation about international events.",
            "The channel promotes illegal substances and drug-related activities.",
            "The channel shares hate speech and discriminatory content against individuals."
        ];

        // ============================================================
        // 100 UNIQUE EMAIL TEMPLATES
        // ============================================================
        const templates = [];

        const identities = [
            "a concerned global citizen", "a human rights defender", "a journalist", "a lawyer",
            "a university professor", "a doctor", "a student", "a researcher", "a writer",
            "a community leader", "a peace activist", "a humanitarian", "a psychologist",
            "a social worker", "a volunteer", "a nurse", "a counselor", "a mentor",
            "a guide", "a helper", "a friend", "a neighbor", "a colleague",
            "a partner", "a teammate", "a classmate", "a roommate", "a world citizen",
            "a justice advocate", "a truth seeker", "a freedom defender",
            "a protector of the vulnerable", "a voice for the voiceless", "a rights fighter",
            "a peace lover", "a oppression hater", "a dreamer of a better world",
            "an artist", "a musician", "a scientist", "a philosopher", "a historian",
            "a poet", "an engineer", "a programmer", "a designer", "a photographer",
            "a filmmaker", "a journalist", "an editor", "a publisher", "a librarian",
            "a teacher", "a sports coach", "a farmer", "a worker", "an industrialist",
            "a trader", "a merchant", "an entrepreneur", "an investor", "an analyst",
            "a financial advisor", "an accountant", "a manager", "a supervisor", "an employee",
            "a retired officer", "a soldier", "a police officer", "a firefighter", "a paramedic",
            "a forensic expert", "a psychiatrist", "a dentist", "a pharmacist", "a physiotherapist",
            "a pediatric nurse", "a midwife", "an orderly", "a technician", "a software engineer",
            "a hardware engineer", "an electrical engineer", "a mechanical engineer", "an architect", "an urban planner",
            "a geographer", "a geologist", "a meteorologist", "a biologist", "a chemist",
            "a physicist", "a mathematician", "a statistician", "an economist", "a sociologist"
        ];

        const intros = [
            "I am writing to formally report a channel that is violating Telegram's Terms of Service.",
            "This is an urgent report regarding a channel that is spreading illegal content.",
            "I have documented serious violations by a channel that is harming users.",
            "The following channel is being used for phishing, fake news, and hate speech.",
            "I am reporting a channel that violates multiple Telegram policies.",
            "This channel is a direct threat to user safety and privacy.",
            "I have evidence of systematic violations including phishing and hate speech.",
            "The content on this channel is illegal under international law.",
            "I am submitting this report to protect innocent people from harm.",
            "This channel poses a significant risk to public safety.",
            "I have identified multiple violations that require your urgent attention.",
            "This channel is actively harming individuals through scams and misinformation.",
            "The content on this channel is designed to deceive and exploit users.",
            "I am a user who has witnessed dangerous behavior on this channel.",
            "This report documents clear violations of Telegram's rules."
        ];

        const bodies = [
            "The channel publishes phishing content impersonating US government agencies to scam users.",
            "The channel spreads fake news and misinformation about international events.",
            "The channel promotes illegal substances and drug-related activities.",
            "The channel shares hate speech and discriminatory content against individuals.",
            "The channel is being used to spread dangerous propaganda and misinformation.",
            "The content on this channel is designed to deceive and manipulate users.",
            "The channel violates Telegram's policies against phishing and scams.",
            "The channel contains material that incites hatred and discrimination.",
            "The channel is a platform for spreading harmful misinformation.",
            "The channel engages in activities that violate Telegram's safety guidelines.",
            "The channel poses a threat to users through phishing attempts.",
            "The channel contains content that is illegal under international law.",
            "The channel is used to promote illegal activities and substances.",
            "The channel violates Telegram's community guidelines.",
            "The channel is a source of harmful and misleading content."
        ];

        const rules = [
            "Telegram's Terms of Service prohibit phishing and scams (Section 5.2).",
            "Spreading misinformation that causes harm is a violation of Telegram's community guidelines.",
            "Promoting illegal substances is forbidden under Telegram's content policies.",
            "Hate speech and incitement to discrimination violate Telegram's rules.",
            "All users have the right to safety and security as per Telegram's policy.",
            "Telegram's rules strictly prohibit deceptive practices.",
            "Content that incites violence or hatred is prohibited.",
            "Telegram's Terms of Service prohibit illegal content distribution.",
            "Users have the right to a safe and secure environment.",
            "Telegram's community guidelines protect users from harmful content."
        ];

        const closings = [
            "I urge you to investigate this channel and take immediate action to block it.",
            "Please take swift action to remove this channel and protect Telegram users.",
            "This channel must be shut down to prevent further harm to individuals.",
            "I request that you review this channel and take appropriate action.",
            "Please investigate this matter and enforce Telegram's rules.",
            "This is a serious violation that requires your immediate attention.",
            "I hope you will act swiftly to remove this dangerous channel.",
            "Please protect Telegram users by blocking this channel.",
            "This channel is a threat to safety and must be removed.",
            "I trust you will take the necessary action to stop this harmful activity.",
            "Your swift action will help protect innocent people from harm.",
            "Please take this report seriously and take appropriate action.",
            "I expect Telegram to uphold its own policies and remove this channel.",
            "This channel is causing real harm to real people right now.",
            "Please prioritize this report and take action as soon as possible."
        ];

        for (let i = 0; i < 100; i++) {
            const identity = identities[i % identities.length];
            const intro = intros[i % intros.length];
            const body = bodies[i % bodies.length];
            const rule = rules[i % rules.length];
            const closing = closings[i % closings.length];
            const num = i + 1;

            const violationType = VIOLATIONS[i % VIOLATIONS.length];
            const violationDetail = VIOLATION_DETAILS[i % VIOLATION_DETAILS.length];

            const subject =
                `🚨 Violation Report: ${CHANNEL_NAME} (Report #${num} - ${violationType})`;

            const emailBody =
                `Dear Telegram Trust & Safety Team,

${intro}

The channel is called "${CHANNEL_NAME}" (ID: ${CHANNEL_ID}) and has been active for a long time.

📋 VIOLATION TYPE: ${violationType}

🔍 DETAILED VIOLATION:
${violationDetail}

📜 APPLICABLE TELEGRAM RULE:
${rule}

🔗 EVIDENCE LINKS (sample violations):
Message ID: 22843 (PHISHING)
Message ID: 22400 (FAKE_NEWS)
Message ID: 20050 (DRUGS)
Message ID: 17618 (HATE_SPEECH)

${closing}

Thank you for your attention to this serious matter.

Sincerely,
${identity.charAt(0).toUpperCase() + identity.slice(1)}

---
Report ID: SB-${String(num).padStart(3, '0')}-${Date.now().toString(36)}
Channel: ${CHANNEL_NAME}
Channel ID: ${CHANNEL_ID}
Violation Type: ${violationType}
Evidence: Message IDs 22843, 22400, 20050, 17618
`;

            templates.push({ subject, body: emailBody });
        }

        // ============================================================
        // RENDER
        // ============================================================
        let currentPage = 1;
        const perPage = 20;
        let searchTerm = "";

        function getFiltered() {
            let f = templates;
            if (searchTerm.trim()) {
                const t = searchTerm.toLowerCase().trim();
                f = f.filter(e =>
                    e.subject.toLowerCase().includes(t) ||
                    e.body.toLowerCase().includes(t)
                );
            }
            return f;
        }

        function renderPage() {
            const filtered = getFiltered();
            const totalPages = Math.max(1, Math.ceil(filtered.length / perPage));
            if (currentPage > totalPages) currentPage = totalPages;
            const start = (currentPage - 1) * perPage;
            const end = Math.min(start + perPage, filtered.length);
            const pageEmails = filtered.slice(start, end);

            const grid = document.getElementById('emailGrid');
            grid.innerHTML = '';

            pageEmails.forEach((e, idx) => {
                const realIdx = templates.indexOf(e);
                const preview = e.body.substring(0, 160) + '...';
                const linkDisplay = e.body.match(/Message ID: \d+/g) || [];
                const linkHtml = linkDisplay.slice(0, 4).map(l =>
                    `<span style="color:#00ff00;">${l}</span>`
                ).join(' · ');

                const card = document.createElement('div');
                card.className = 'email-card';
                card.innerHTML = `
                    <div class="num">#${e.subject.match(/#(\d+)/)?.[1] || realIdx+1}</div>
                    <div class="subject">${e.subject}</div>
                    <div class="body-preview">${preview}</div>
                    <div class="links">🔗 ${linkHtml} ${linkDisplay.length > 4 ? '...' : ''}</div>
                    <div class="btn-group">
                        <button class="btn-gmail" onclick="sendGmail(${realIdx})">📧 Gmail</button>
                        <button class="btn-email" onclick="sendEmail(${realIdx})">📨 Email</button>
                        <button class="btn-copy" onclick="copyEmail(${realIdx})">📋 Copy</button>
                    </div>
                    <div class="status-msg" id="status${realIdx}"></div>
                `;
                grid.appendChild(card);
            });

            document.getElementById('counterDisplay').textContent =
                `Showing ${start+1}-${end} of ${filtered.length} emails`;
            document.getElementById('pageInfo').textContent = `Page ${currentPage} of ${totalPages}`;

            const pagDiv = document.getElementById('pagination');
            pagDiv.innerHTML = '';
            const startPage = Math.max(1, currentPage - 4);
            const endPage = Math.min(totalPages, startPage + 9);
            for (let p = startPage; p <= endPage; p++) {
                const btn = document.createElement('button');
                btn.className = `page-btn ${p === currentPage ? 'active' : ''}`;
                btn.textContent = p;
                btn.onclick = () => { currentPage = p;
                    renderPage(); };
                pagDiv.appendChild(btn);
            }
        }

        function nextPage() {
            const filtered = getFiltered();
            const totalPages = Math.max(1, Math.ceil(filtered.length / perPage));
            if (currentPage < totalPages) { currentPage++;
                renderPage(); }
        }

        function prevPage() {
            if (currentPage > 1) { currentPage--;
                renderPage(); }
        }

        // ============================================================
        // ACTIONS
        // ============================================================
        function sendGmail(index) {
            event.preventDefault();
            const e = templates[index];
            const to = TO_EMAILS.join(',');
            const sub = encodeURIComponent(e.subject);
            const body = encodeURIComponent(e.body);
            const url = `https://mail.google.com/mail/?view=cm&fs=1&to=${to}&su=${sub}&body=${body}`;
            window.open(url, '_blank');
            showStatus(index, '📧 Opening Gmail Web...');
        }

        function sendEmail(index) {
            event.preventDefault();
            const e = templates[index];
            const to = TO_EMAILS.join(',');
            const sub = encodeURIComponent(e.subject);
            const body = encodeURIComponent(e.body);
            window.location.href = `mailto:${to}?subject=${sub}&body=${body}`;
            showStatus(index, '📨 Opening Email app...');
        }

        function copyEmail(index) {
            const e = templates[index];
            const text = `Subject: ${e.subject}\n\n${e.body}`;
            navigator.clipboard.writeText(text)
                .then(() => showStatus(index, '✅ Copied!', '#00ff00'))
                .catch(() => showStatus(index, '❌ Failed', '#ff0000'));
        }

        function showStatus(idx, msg, color = '#8892b0') {
            const el = document.getElementById('status' + idx);
            if (!el) return;
            el.textContent = msg;
            el.style.color = color;
            clearTimeout(el._timeout);
            el._timeout = setTimeout(() => { el.textContent = ''; }, 3500);
        }

        document.getElementById('searchBox').addEventListener('input', function() {
            searchTerm = this.value;
            currentPage = 1;
            renderPage();
        });

        renderPage();
    </script>

</body>
</html>
