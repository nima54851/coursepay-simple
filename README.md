<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🎯 CoursePay - 课程销售平台</title>
    <style>
        :root { --primary: #667eea; --secondary: #764ba2; --success: #00ff9d; }
        body { margin:0; padding:0; font-family:sans-serif; background:linear-gradient(135deg, var(--primary), var(--secondary)); color:white; min-height:100vh; display:flex; align-items:center; justify-content:center; }
        .container { background:rgba(255,255,255,0.1); backdrop-filter:blur(10px); padding:40px; border-radius:20px; max-width:800px; margin:20px; text-align:center; border:1px solid rgba(255,255,255,0.2); }
        h1 { color:var(--success); font-size:2.8em; margin-bottom:20px; }
        .status { background:var(--success); color:#333; padding:15px; border-radius:10px; margin:20px 0; font-weight:bold; }
        .paypal-account { font-size:2em; font-family:'Consolas',monospace; color:var(--success); font-weight:bold; margin:20px 0; background:rgba(0,0,0,0.2); padding:15px; border-radius:10px; }
        .btn { background:var(--success); color:#333; border:none; padding:15px 30px; border-radius:50px; font-size:1.1em; font-weight:bold; cursor:pointer; margin:10px; }
    </style>
</head>
<body>
<div class="container">
    <h1>🎯 CoursePay 课程销售平台</h1><div class="status">✅ GitHub Pages 部署成功</div>
    <p>💰 PayPal收款账户:</p>
    <div class="paypal-account">yinanzo@hotmail.com</div>
    <p>🎯 功能：选择课程 → 显示收款账户 → PayPal直接转账</p>
    <button class="btn" onclick="alert('✅ 功能正常！收款账户: yinanzo@hotmail.com')">🚀 测试支付</button>
    <button class="btn" onclick="copyAccount()">📋 复制收款账户</button>
</div>
<script>
function copyAccount() { navigator.clipboard.writeText('yinanzo@hotmail.com').then(() => alert('✅ 已复制到剪贴板')); }
</script>
</body>
</html>
