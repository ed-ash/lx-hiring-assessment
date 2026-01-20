<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Explore-AI/Public-Data@master/de-alx/styles.css">
<!--
    <metadata>
        <meta name="course_name" content="AiCE">
        <meta name="content_title" content="Staying Safe with AI: Personal + Workplace Cyber Hygiene (Skeleton)">
        <meta name="order" content="1">
        <meta name="date_updated" content="2024-11-06 00:00:00">
        <meta name="creator" content="Codex Assistant">
        <meta name="version" content="1">
        <meta name="is_on_Savanna" content="False">
        <meta name="content_type" content="concept">
    </metadata>
-->

![ALX Content Header](https://raw.githubusercontent.com/Explore-AI/Pictures/master/alx-courses/aice/assets/Content_page_banner_blue_dots.png)

<h1>Staying Safe with AI: Personal + Workplace Cyber Hygiene</h1>
<p><strong>Estimated time:</strong> 30–60 minutes</p>

<h2>Lesson Overview</h2>
<div class="text-segment">
  <p>Imagine today is a regular workday. You open your laptop, skim through emails, reply to a WhatsApp message, and ask an AI tool to tidy up a report. Everything feels routine and efficient.</p>
  <p>Then a message pops up. It looks legitimate. The tone is professional. It sounds urgent. It might even sound like someone you know. <strong>That’s the challenge!</strong></p>
  <p>AI has made work faster and smarter, but it has also made scams, fake messages, and impersonation far more convincing. A <a href="https://www.cloudflare.com/learning/access-management/phishing-attack/" target="_blank">phishing</a> email can sound perfectly human. A fake voice note can sound exactly like your manager. A helpful-looking AI tool can quietly ask for more information than it should.</p>
  <p>This lesson helps you <strong>pause</strong>, <strong>spot the signs</strong>, and <strong>respond safely</strong>. You do not need technical cybersecurity knowledge — just awareness, judgment, and the confidence to verify before acting.</p>
</div>

<h2>Learning Outcomes</h2>
<ul>
  <li>Identify common AI-enabled cyber threats such as phishing messages, deepfake requests, fake IT or HR chats, and malicious links.</li>
  <li>Apply five practical cyber hygiene habits when using AI tools.</li>
  <li>Use workplace AI tools safely without exposing customer, company, or personal data.</li>
</ul>

<h2>The Evolving Cyber Threat Landscape</h2>
<div class="text-segment">
  <div class="video-wrapper">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/B4jNttRvbpU?si=S0rt3tu8VakERW1b" title="How to spot AI-generated misinformation" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
  </div>
  <br>
  <style>
    .scenario-block { border: 1px solid #e5e7eb; padding: 12px; border-radius: 10px; margin: 12px 0; }
    .scenario-options { display: flex; gap: 8px; flex-wrap: wrap; margin-top: 8px; }
    .scenario-option { border: 1px solid #d1d5db; background: #fff; padding: 8px 12px; border-radius: 8px; cursor: pointer; font-weight: 700; }
    .scenario-option.selected { border-color: #0ea35a; box-shadow: 0 0 0 2px rgba(14,163,90,0.15); }
    .scenario-feedback { margin-top: 6px; font-weight: 700; }
    #validate-scenarios { margin-top: 10px; padding: 10px 14px; border: none; border-radius: 10px; background: #0b6ef6; color: #fff; font-weight: 700; cursor: pointer; }
    .wrapup-collapsible { border: 1px solid #e2e8f0; border-radius: 12px; background: #ffffff; padding: 8px 12px; margin: 12px 0; }
    .wrapup-toggle { width: 100%; display: flex; align-items: center; gap: 10px; border: none; background: transparent; font-size: 18px; font-weight: 700; cursor: pointer; padding: 8px 4px; text-align: left; }
    .wrapup-icon { display: inline-flex; width: 20px; height: 20px; align-items: center; justify-content: center; border-radius: 50%; border: 1px solid #0b6ef6; color: #0b6ef6; font-weight: 800; }
    .wrapup-content { display: none; margin-top: 10px; }
    .wrapup-content.open { display: block; }
  </style>

  <p>Read each scenario and answer the question. Go with your first reaction.</p>

  <div class="scenario-block" data-correct="unsafe">
    <h4>Scenario 1: Message</h4>
    <p>“Hi, this is IT Support. We detected unusual activity on your account. Please click the link below to verify your details within the next 30 minutes to avoid suspension.”</p>
    <div class="scenario-options">
      <button class="scenario-option" data-question="s1" data-value="safe">Safe</button>
      <button class="scenario-option" data-question="s1" data-value="unsafe">Unsafe</button>
    </div>
    <div class="scenario-feedback"></div>
  </div>

  <div class="scenario-block" data-correct="unsafe">
    <h4>Scenario 2: Email</h4>
    <p>Subject: <em>Updated Salary Structure – Immediate Review Required</em>. Branded, professional, asks you to log in via a link.</p>
    <div class="scenario-options">
      <button class="scenario-option" data-question="s2" data-value="safe">Safe</button>
      <button class="scenario-option" data-question="s2" data-value="unsafe">Unsafe</button>
    </div>
    <div class="scenario-feedback"></div>
  </div>

  <div class="scenario-block" data-correct="unsafe">
    <h4>Scenario 3: Voice Note</h4>
    <p>A voice note sounds exactly like your manager asking for an urgent document or payment.</p>
    <div class="scenario-options">
      <button class="scenario-option" data-question="s3" data-value="safe">Safe</button>
      <button class="scenario-option" data-question="s3" data-value="unsafe">Unsafe</button>
    </div>
    <div class="scenario-feedback"></div>
  </div>

  <div class="scenario-block" data-correct="safe">
    <h4>Scenario 4: Calendar Invite</h4>
    <p>An event invite arrives from your manager’s usual company email, through your standard calendar app, with no links or requests for logins or files—just the meeting time and agenda.</p>
    <div class="scenario-options">
      <button class="scenario-option" data-question="s4" data-value="safe">Safe</button>
      <button class="scenario-option" data-question="s4" data-value="unsafe">Unsafe</button>
    </div>
    <div class="scenario-feedback"></div>
  </div>

  <button id="validate-scenarios">Validate answers</button>

  <p></p>
  
  <div class="reflection-element">
    <h>Reflect:</h><br>
    Which signals (tone, links, sender details, urgency) made you choose SAFE vs UNSAFE in each scenario?
  </div>
</div>

<h2>Your Cyber Hygiene Checklist</h2>
<div class="text-segment">
  <style>
    .flip-row { display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 12px; margin-bottom: 12px; }
    .flip-card { border-radius: 12px; overflow: hidden; box-shadow: 0 10px 24px rgba(0,0,0,0.1); background: #fff; }
    .flip-inner { display: flex; flex-direction: column; width: 100%; }
    .flip-face { width: 100%; box-sizing: border-box; }
    .flip-front { height: 160px; background-size: cover; background-position: center; }
    .flip-back { padding: 12px; background: #0f172a; color: #e5e7eb; }
    .flip-step { display: inline-block; padding: 4px 10px; border-radius: 999px; background: #eef2ff; color: #0f172a; font-weight: 700; font-size: 12px; margin-bottom: 6px; }
    .flip-title { font-weight: 800; font-size: 18px; text-transform: uppercase; letter-spacing: 0.5px; }
    .flip-back ul { padding-left: 18px; margin: 6px 0; }
    .flip-credit { font-size: 10px; color: #94a3b8; margin-top: 6px; }
  </style>

  <div class="flip-row">
    <div class="flip-card">
      <div class="flip-step">Step 1</div>
      <div class="flip-inner">
        <div class="flip-face flip-front" style="background-image:url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRCDYcvRSXxH-CY3I_1Nq9WAvZ0RSASLXDYgQ&s');">
        </div>
        <div class="flip-face flip-back">
          <div class="flip-title">PAUSE</div>
          <ul>
            <li>Notice urgency or pressure.</li>
            <li>Ask if the request is expected.</li>
            <li>Identify asks for access, data, or action.</li>
          </ul>
        </div>
      </div>
    </div>
    <div class="flip-card">
      <div class="flip-step">Step 2</div>
      <div class="flip-inner">
        <div class="flip-face flip-front" style="background-image:url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRI9l74CnQoC4PU7VyAo4KXfvOCSWCIcFdJ8w&s');">
        </div>
        <div class="flip-face flip-back">
          <div class="flip-title">CHECK</div>
          <ul>
            <li>Verify the source via another channel.</li>
            <li>Hover links; avoid unexpected logins.</li>
            <li>Redact data before prompting AI.</li>
          </ul>
        </div>
      </div>
    </div>
    <div class="flip-card">
      <div class="flip-step">Step 3</div>
      <div class="flip-inner">
        <div class="flip-face flip-front" style="background-image:url('data:image/jpeg;base64,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');">
        </div>
        <div class="flip-face flip-back">
          <div class="flip-title">DECIDE</div>
          <ul>
            <li>Proceed only if everything checks out.</li>
            <li>Stop and escalate when unsure.</li>
            <li>Report if data or access requests are risky.</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
  <p class="flip-credit">Image credits: <a href="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRCDYcvRSXxH-CY3I_1Nq9WAvZ0RSASLXDYgQ&s" target="_blank" rel="noreferrer">Pause</a>, <a href="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRI9l74CnQoC4PU7VyAo4KXfvOCSWCIcFdJ8w&s" target="_blank" rel="noreferrer">Check</a>, <a href="data:image/jpeg;base64,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">Decide</a>.</p>
</div>

<div class="flag-box" style="border:1px solid #e5e7eb; padding:12px; border-radius:12px; background:#f8fafc; margin:12px 0;">
  <h4>Spot the Red Flags (Practice)</h4>
  <div class="flag-grid" style="display:grid; gap:12px; grid-template-columns:repeat(auto-fit, minmax(260px, 1fr)); margin-top:8px;">
    <div class="flag-item" style="border:1px solid #e2e8f0; border-radius:10px; padding:8px; background:#ffffff;">
      <p class="flag-label" style="font-weight:600; margin:4px 0;">Phishing Email Example</p>
      <img src="https://cdn.prod.website-files.com/5e5ff4f0165cd367cc7ca88f/601325eb86e72e4aa5b0d4df_lastpass-phishing-example.png" alt="Example phishing email" style="width:100%; border-radius:8px;" />
    </div>
    <div class="flag-item" style="border:1px solid #e2e8f0; border-radius:10px; padding:8px; background:#ffffff;">
      <p class="flag-label" style="font-weight:600; margin:4px 0;">Invoice Example</p>
      <img src="https://timely-benefit-e63d540317.media.strapiapp.com/Picture_8_Phishing_Scenario_Example_Fake_Invoice_Scam_c9d7286a8d.png" alt="Fake invoice or chat scam" style="width:100%; border-radius:8px;" />
      <p class="flag-credit" style="font-size:11px; color:#64748b; margin-top:4px;">Invoice scam context: <a href="https://in.norton.com/blog/online-scams/whatsapp-scams" target="_blank" rel="noreferrer">Norton blog</a></p>
    </div>
  </div>
  <div class="flag-checklist" style="margin-top:10px; display:grid; gap:6px;">
    <p style="margin:0; font-weight:600;">Select the red flags you can spot:</p>
    <label><input class="flag-choice" data-flag="urgent" type="checkbox"> Urgent or threatening language</label>
    <label><input class="flag-choice" data-flag="sender" type="checkbox"> Mismatched sender email/number</label>
    <label><input class="flag-choice" data-flag="attachment" type="checkbox"> Unexpected attachment or link</label>
    <label><input class="flag-choice" data-flag="sensitive" type="checkbox"> Requests for passwords or sensitive data</label>
    <label><input class="flag-choice" data-flag="grammar" type="checkbox"> Poor grammar or off-brand tone</label>
    <label><input class="flag-choice" data-flag="domain" type="checkbox"> Unfamiliar domain/URL</label>
    <label><input class="flag-choice" data-flag="payment" type="checkbox"> Payment or credential request via chat</label>
  </div>
  <button id="flag-validate" style="margin-top:10px; padding:8px 12px; border:none; background:#0ea5e9; color:white; border-radius:8px; cursor:pointer;">Check my selections</button>
  <p id="flag-feedback" style="margin-top:8px; font-weight:600; color:#0f172a;"></p>
</div>

<script>
  (function () {
    const required = ["urgent", "sender", "attachment", "sensitive", "domain", "payment"];
    const optional = ["grammar"];
    const validateBtn = document.getElementById("flag-validate");
    const feedbackEl = document.getElementById("flag-feedback");
    if (!validateBtn || !feedbackEl) return;
    validateBtn.addEventListener("click", () => {
      const choices = Array.from(document.querySelectorAll(".flag-choice"));
      const selected = choices.filter(c => c.checked).map(c => c.dataset.flag);
      const hasAllRequired = required.every(flag => selected.includes(flag));
      const hasOptionalOnly = !selected.includes(optional[0]);
      if (hasAllRequired && hasOptionalOnly) {
        feedbackEl.textContent = "Great catch. You spotted the key red flags without over-relying on style or grammar.";
        feedbackEl.style.color = "#15803d";
      } else {
        feedbackEl.textContent = "Not quite. Make sure you catch all the access/data red flags. Grammar or tone alone can’t confirm safety.";
        feedbackEl.style.color = "#b91c1c";
      }
    });
  })();
</script>

<div class="wrapup-collapsible">
  <button class="wrapup-toggle" id="wrapup-toggle">
    <span class="wrapup-icon" id="wrapup-icon">▾</span>
    <span>Wrap-Up: Your Safe AI Playbook</span>
  </button>

  <div class="text-segment wrapup-content open" id="wrapup-content">
    <div class="flag-box" style="border:1px solid #e5e7eb; padding:14px; border-radius:12px; background:#ffffff; margin:12px 0;">
      <p>
        <strong>You’ve reached the end of the lesson.</strong> The main takeaway is simple:
        AI can make scams look and sound real, but good habits still reduce risk.
      </p>
    </div>
    <div class="flag-box" style="border:1px solid #e5e7eb; padding:14px; border-radius:12px; background:#f8fafc; margin:12px 0;">
      <h4>Key Principles to Remember</h4>
      <ul>
        <li><strong>Professional tone does not equal safety.</strong> AI can produce polished, on-brand messages.</li>
        <li><strong>Urgency is often intentional.</strong> When something feels rushed, slow down.</li>
        <li><strong>Verify unexpected requests</strong> using a trusted channel you already know.</li>
        <li><strong>Protect sensitive information.</strong> Do not paste customer, company, or personal data into AI tools.</li>
        <li><strong>When unsure, stop and escalate.</strong> Pausing is a sign of good judgment.</li>
      </ul>
    </div>
    <div class="flag-box" style="border:1px solid #e5e7eb; padding:14px; border-radius:12px; background:#ffffff; margin:12px 0;">
      <h4>The 60-Second Rule: Pause → Check → Decide</h4>
      <p><strong>Pause:</strong> What is being requested — data, access, money, or urgency?</p>
      <p><strong>Check:</strong> Confirm the sender, review links, and ask if this fits normal process.</p>
      <p><strong>Decide:</strong> Proceed safely, rewrite the request, report it, or escalate.</p>
    </div>
    <div class="flag-box" style="border:1px solid #e5e7eb; padding:14px; border-radius:12px; background:#f8fafc; margin:12px 0;">
      <h4>Using AI Without Exposing Data</h4>
      <p>
        AI can still help you do strong work — you just need to be deliberate about what you share.
        Before using an AI tool, do a quick check.
      </p>
      <ul>
        <li>Would this be safe to display in a shared or public workspace?</li>
        <li>Does it include customer or client identifiers (names, numbers, IDs, addresses)?</li>
        <li>Does it include internal company information (pricing, contracts, strategy, credentials, incidents)?</li>
        <li>If yes, remove it, mask it, or summarize it before prompting.</li>
      </ul>
      <h4>Example: Unsafe vs Safe Prompt</h4>
      <p>
        <strong>Unsafe:</strong>
        “Summarize this complaint from <em>Joshua William</em>, account ID <em>12345</em>, phone <em>024xxxxxxx</em>.
        Include the full email thread.”
      </p>
      <p>
        <strong>Safe:</strong>
        “Summarize the key issues in a customer complaint and draft a professional response.
        Do not include any personal or identifying details.”
      </p>
      <p style="font-size:12px; color:#64748b;">
        <strong>Tip:</strong> Use placeholders like [CUSTOMER], [ACCOUNT], [DATE], or describe the situation in your own words.
      </p>
    </div>
    <div class="flag-box" style="border:1px solid #e5e7eb; padding:14px; border-radius:12px; background:#ffffff; margin:12px 0;">
      <h4>How to Report Suspicions</h4>
      <p>
        If a message involves sensitive data, urgent action, or unusual requests,
        the safest move is to pause and report it. You can fkag this by using a 
        template similar to this:
      </p>
      <div class="flag-box" style="border:1px solid #e2e8f0; padding:12px; border-radius:10px; background:#ffffff; margin-top:8px;">
        <p>
          “Hi team, I received a message that appears to be from <strong>[HR / IT / Manager]</strong>.
          It asks me to <strong>[click a link / share information / approve a payment]</strong>.
          I have <strong>[not clicked / clicked]</strong>. Please advise next steps. Screenshot attached.”
        </p>
        <p style="font-size:12px; color:#64748b;">
          Use your organization’s official reporting channel if available
          (for example, a security mailbox or IT helpdesk).
        </p>
      </div>
    </div>
  </div>
</div>


<script>
  (function() {
    const toggle = document.getElementById('wrapup-toggle');
    const content = document.getElementById('wrapup-content');
    const icon = document.getElementById('wrapup-icon');
    if (!toggle || !content || !icon) return;
    toggle.addEventListener('click', () => {
      const isOpen = content.classList.toggle('open');
      icon.textContent = isOpen ? '▾' : '+';
    });
  })();
</script>

<script>
  // Scenario selection & validation
  const optionButtons = document.querySelectorAll('.scenario-option');
  optionButtons.forEach(btn => {
    btn.addEventListener('click', () => {
      const q = btn.dataset.question;
      const group = document.querySelectorAll(`.scenario-option[data-question="${q}"]`);
      group.forEach(b => b.classList.remove('selected'));
      btn.classList.add('selected');
      const block = btn.closest('.scenario-block');
      if (block) {
        const fb = block.querySelector('.scenario-feedback');
        if (fb) fb.textContent = '';
      }
    });
  });

  const validateBtn = document.getElementById('validate-scenarios');
  if (validateBtn) {
    validateBtn.addEventListener('click', () => {
      document.querySelectorAll('.scenario-block').forEach(block => {
        const correct = block.dataset.correct;
        const selected = block.querySelector('.scenario-option.selected');
        const fb = block.querySelector('.scenario-feedback');
        if (!fb) return;
        if (!selected) {
          fb.textContent = 'Pick an option first.';
          fb.style.color = '#f59e0b';
          return;
        }
        const choice = selected.dataset.value;
        if (choice === correct) {
          fb.textContent = `Correct. This scenario is ${correct.toUpperCase()}.`;
          fb.style.color = '#0ea35a';
        } else {
          fb.textContent = `Not quite. This scenario is ${correct.toUpperCase()}.`;
          fb.style.color = '#e11d48';
        }
      });
    });
  }
</script>

<div class="section">
  <p><em>End of lesson.</em></p>
</div>
