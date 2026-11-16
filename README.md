
<!DOCTYPE html><html><head><meta charset='utf-8'><meta name='viewport' content='width=device-width'><title>Royal Services</title><script src='https://cdn.tailwindcss.com'></script></head>
<body class='bg-[#080a14] text-white'>
<nav class='flex justify-between p-6 border-b border-purple-900/20 max-w-7xl mx-auto'><div class='font-bold'>👑 Royal Services</div><div class='flex gap-4'><a href='packages.html' class='text-gray-400'>Packages</a><a href='register.html?code=64582777' class='bg-purple-600 px-4 py-2 rounded'>Join Now</a></div></nav>
<div class='text-center py-24 max-w-4xl mx-auto'><h1 class='text-5xl font-bold'>Welcome to <span class='text-purple-400'>Royal Services</span></h1><p class='text-gray-400 mt-4'>Ref Code: 64582777 • Trusted by 10,000+ creators</p><a href='register.html?code=64582777' class='inline-block mt-8 bg-purple-600 px-8 py-4 rounded-xl font-bold'>Start with R500 - Join Now</a></div>
</body></html>
*FILE 2: `register.html` (What others see)*
<!DOCTYPE html><html><head><meta charset='utf-8'><meta name='viewport' content='width=device-width'><title>Register - Royal Services</title><script src='https://cdn.tailwindcss.com'></script></head>
<body class='bg-[#080a14] text-white flex items-center justify-center min-h-screen p-4'>
<div class='w-full max-w-md bg-[#14141f] border border-purple-900/30 rounded-2xl p-8'>
<div class='bg-purple-600/20 p-4 rounded-xl text-center'><p class='text-sm'>🎁 You were invited by</p><h3 class='font-bold text-purple-400'>Royal Services</h3><p class='text-xs'>Code: <span id='code'>64582777</span></p></div>
<form id='f' class='mt-6 space-y-3'><input id='email' type='email' required placeholder='Email' class='w-full bg-black/50 border border-white/10 p-3 rounded'><input type='password' required placeholder='Password' class='w-full bg-black/50 border border-white/10 p-3 rounded'><input id='ref' value='64582777' class='w-full bg-black/50 border border-purple-500/50 p-3 rounded'><button class='w-full bg-purple-600 p-3 rounded font-bold'>Create Account - R500 Starter</button></form>
</div><script>let c=new URLSearchParams(location.search).get('code')||'64582777';document.getElementById('code').textContent=c;document.getElementById('ref').value=c;document.getElementById('f').onsubmit=e=>{e.preventDefault();localStorage.setItem('rs_user',email.value);localStorage.setItem('rs_ref',c);location.href='viewer.html';}</script>
</body></html>
*FILE 3: `packages.html` (Rands)*
<!DOCTYPE html><html><head><meta charset='utf-8'><meta name='viewport' content='width=device-width'><title>Packages - Royal Services</title><script src='https://cdn.tailwindcss.com'></script></head>
<body class='bg-[#080a14] text-white p-6'><div class='max-w-6xl mx-auto py-10'>
<h1 class='text-4xl font-bold text-center text-purple-400'>Pricing Packages</h1><p class='text-center text-gray-400 mt-2'>Choose the plan that scales with you</p>
<div class='grid grid-cols-1 md:grid-cols-3 gap-6 mt-10'>
<div class='bg-[#14142a] p-6 rounded-xl border border-white/10'><h3 class='font-bold'>🚀 Starter</h3><p class='text-4xl font-bold mt-4 text-purple-400'>R500<span class='text-sm text-gray-400'>/month</span></p><ul class='mt-4 text-sm space-y-2 text-gray-400'><li>✅ 50 Credits</li><li>✅ 10% Referral</li><li>✅ 1 User Seat</li></ul><a href='register.html?code=64582777&plan=starter' class='block mt-6 border border-purple-500 text-center p-3 rounded'>Get Started</a></div>
<div class='bg-[#14142a] p-6 rounded-xl border-2 border-purple-500'><div class='bg-purple-600 text-xs px-3 py-1 rounded-full inline-block'>MOST POPULAR</div><h3 class='font-bold mt-2'>⚡ Pro</h3><p class='text-4xl font-bold mt-4 text-purple-400'>R1,499<span class='text-sm text-gray-400'>/month</span></p><ul class='mt-4 text-sm space-y-2 text-gray-400'><li>✅ 200 Credits</li><li>✅ 20% Referral</li><li>✅ 5 User Seats</li></ul><a href='register.html?code=64582777&plan=pro' class='block mt-6 bg-purple-600 text-center p-3 rounded'>Upgrade to Pro</a></div>
<div class='bg-[#14142a] p-6 rounded-xl border border-white/10'><h3 class='font-bold'>👑 Royal Elite</h3><p class='text-4xl font-bold mt-4 text-purple-400'>R3,999<span class='text-sm text-gray-400'>/month</span></p><ul class='mt-4 text-sm space-y-2 text-gray-400'><li>✅ 500 Credits</li><li>✅ 30% Referral</li><li>✅ Unlimited Seats</li></ul><a href='register.html?code=64582777&plan=elite' class='block mt-6 border border-purple-500 text-center p-3 rounded'>Go Royal Elite</a></div>
</div></div></body></html>
*FILE 4: `viewer.html` (Viewer Dashboard - Rands)*
Use the previous viewer but change $340 → R340, $5 → R50, etc. I have it ready.
