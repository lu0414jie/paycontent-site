<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <title>专属隐私空间 - 终身会员</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: "Microsoft YaHei", sans-serif; }
        body { background: #000; color: #fff; min-height: 100vh; position: relative; overflow-x: hidden; }
        .bg-puzzle { width: 100%; height: 50vh; display: grid; grid-template-columns: repeat(4,1fr); grid-template-rows: repeat(3,1fr); gap: 2px; opacity: 0.4; }
        .puzzle-item { width: 100%; height: 100%; background: center/cover no-repeat; transform: rotate(var(--rotate,0deg)); border-radius: 2px; }
        .puzzle-item:nth-child(1) { background-image: url("https://picsum.photos/200/200?random=1"); --rotate: -2deg; }
        .puzzle-item:nth-child(2) { background-image: url("https://picsum.photos/200/200?random=2"); --rotate: 3deg; }
        .puzzle-item:nth-child(3) { background-image: url("https://picsum.photos/200/200?random=3"); --rotate: -1deg; }
        .puzzle-item:nth-child(4) { background-image: url("https://picsum.photos/200/200?random=4"); --rotate: 2deg; }
        .puzzle-item:nth-child(5) { background-image: url("https://picsum.photos/200/200?random=5"); --rotate: 4deg; }
        .puzzle-item:nth-child(6) { background-image: url("https://picsum.photos/200/200?random=6"); --rotate: -3deg; }
        .puzzle-item:nth-child(7) { background-image: url("https://picsum.photos/200/200?random=7"); --rotate: 1deg; }
        .puzzle-item:nth-child(8) { background-image: url("https://picsum.photos/200/200?random=8"); --rotate: -4deg; }
        .puzzle-item:nth-child(9) { background-image: url("https://picsum.photos/200/200?random=9"); --rotate: 2deg; }
        .puzzle-item:nth-child(10) { background-image: url("https://picsum.photos/200/200?random=10"); --rotate: -1deg; }
        .puzzle-item:nth-child(11) { background-image: url("https://picsum.photos/200/200?random=11"); --rotate: 3deg; }
        .puzzle-item:nth-child(12) { background-image: url("https://picsum.photos/200/200?random=12"); --rotate: -2deg; }
        .bg-mask { position: absolute; top: 0; left: 0; width: 100%; height: 50vh; background: linear-gradient(to bottom, rgba(0,0,0,0.2), rgba(0,0,0,0.8)); z-index: 10; }
        .main-title { position: absolute; top: 40%; left: 50%; transform: translate(-50%,-50%); width: 100%; text-align: center; z-index: 20; }
        .main-title h1 { font-size: 24px; color: #fff; text-shadow: 0 0 15px #9d00ff; letter-spacing: 2px; }
        .price-section { width: 100%; padding: 20px 15px; margin-top: 20px; position: relative; z-index: 30; }
        .tag { background: #9d00ff; color: #fff; font-size: 12px; padding: 3px 10px; border-radius: 20px; display: inline-block; margin-bottom: 15px; }
        .price-card { background: linear-gradient(135deg, #2d004e, #1a1a1a); border: 2px solid #9d00ff; border-radius: 10px; padding: 20px; margin-bottom: 30px; text-align: center; }
        .price-card h3 { font-size: 18px; margin-bottom: 10px; color: #fff; }
        .price-card .price-big { font-size: 32px; color: #9d00ff; font-weight: bold; margin: 10px 0; }
        .price-card .price-desc { font-size: 14px; color: #ccc; margin-bottom: 10px; }
        .price-card .feature-list { text-align: left; font-size: 14px; margin-top: 15px; }
        .price-card .feature-list p { margin-bottom: 5px; color: #fff; }
        .open-btn-wrap { width: 100%; margin-top: 20px; }
        .open-btn { width: 100%; padding: 18px 0; background: linear-gradient(90deg, #9d00ff, #d342ff); border: none; border-radius: 30px; color: #fff; font-size: 18px; font-weight: bold; cursor: pointer; box-shadow: 0 0 20px rgba(157,0,255,0.5); }
        .privilege { padding: 0 15px; margin-top: 20px; font-size: 12px; color: #ccc; line-height: 1.6; }
        .privilege h4 { color: #fff; font-size: 14px; margin-bottom: 10px; }
        .member-page { display: none; padding: 30px 20px; background: #000; min-height: 100vh; }
        .member-header { text-align: center; margin-bottom: 30px; }
        .member-header h2 { color: #9d00ff; font-size: 32px; margin-bottom: 10px; }
        .resource-section { margin-bottom: 30px; }
        .resource-section h3 { color: #fff; font-size: 20px; margin-bottom: 15px; padding-bottom: 8px; border-bottom: 2px solid #333; }
        .resource-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(150px,1fr)); gap: 15px; }
        .resource-item { background: #1a1a1a; padding: 15px; border-radius: 8px; text-align: center; transition: all 0.3s; border: 1px solid #333; }
        .resource-item:hover { transform: translateY(-5px); box-shadow: 0 5px 15px rgba(157,0,255,0.3); border-color: #9d00ff; }
        .resource-item a { text-decoration: none; color: #fff; display: block; }
        .resource-item i { font-size: 24px; color: #9d00ff; margin-bottom: 10px; }
        .resource-item .name { font-weight: bold; margin-bottom: 5px; }
        .resource-item .desc { font-size: 12px; color: #666; }
        @import url("https://cdn.bootcdn.net/ajax/libs/font-awesome/6.4.0/css/all.min.css");
    </style>
</head>
<body>
<?php
// ======================================
// 【1. 选择部署平台（取消注释对应行）】
// ======================================
//$deploy_platform = "infinityfree"; // 部署到InfinityFree（HTTP）
$deploy_platform = "netlify"; // 部署到Netlify（HTTPS）

// ======================================
// 【2. 填写你的支付宝真实信息（必填）】
// ======================================

$alipay_appid = "2021006121606869";          // 你的支付宝开放平台APPID
$alipay_merchant_no = "2088032430157326";    // 你的支付宝商户号
$alipay_private_key = "MIIEvgIBADANBgkqhkiG9w0BAQEFAASCBKgwggSkAgEAAoIBAQC0JKKS6clhcjvi2nb6+kfbPDU0cZg7sPFV43wyvjmASIOzJ8nwzUc8lgEP+FXdTjlPxiNg1OAjf9Zyy3KbJ/pAWtLPx9Op1AIALlwyZLh7Zg/RAd5jqkV8ctSd1/FDfrGFo5CKiEMXlu+frxhOnN9aMTLoL40oOPTS/8Yq5uADlX90d1g4hHQP/4GQkzUeGbgA4s0zKUI7X26g9/Pco/P6kbnku6l8GlpSPoLuUrupspiIKPYRMS0Ek5Cu+2rkl/HjTl2Tn3NR9CCFIouJ7cjebbtWRRAKEBNdjKy0UU6nt6VCkpGDceMtf6aRsXWeTcgdPaO0kGivi8QI2+oXhoyBAgMBAAECggEBAK95zD9tqjPZEcrN4f5ilGJTiMQ4LwFeQAfZG19Wey6h9GAszwJZBB5ZRFmpHwL/MsapjEbDtj3+Rgf2dAH9dEEB975cuasBkJ1ai4avJCFX7uo6dsYA08UBGmlTM3n6zLQP+zlmuGwfI/YZmoThPJRfvmX8A/V9Xca3TfL2iJoTgNGaDNTW3TWVlOOoHvcJrr2+tfZce/TaEXlPViAIZ1q2fmD59oaaHqQjrPXlMeGkWR+TZ2dZE0kFf/hls8FScGUdoZOQajNVfaHNWrZl56PwAe9KIWc9b3isqWlkvBVDxLDeKPbu3h+jwbeBZA7KR2ondiEUNrUwPmuHATL7Yq0CgYEA3Rxysi4fGi33SOz/z49d0CDJD0e21TDEoKq26U5Z0JfhJg0AuSlpgof4s6SLJGIf7FcOozEBKujKAbw3CtYwJgvwxAoAABhzbwPNne4JMp7TXDxxmFq4HayG8gmXr8Iz6ZZ/HATAusoHf/WFHvSAzpM3dKZfVGCBFyb1WjNA8hMCgYEA0JFTrHUKmT6aEPVMHGOL+VyWgUE7pZkt5Kxt2isqh3b9S0xeyv6uTba33kWIR9MI7Ewg8s+hyK8GzvpQvV3twR69tvueHqQOVXXiDJJj+q6GATgyvIVHRmDGpm+PRbI20NbAgME9d2zjt0sAJSVfy5gGHEk7GfUVZl2urLEzeZsCgYBoLx9cFZ9SFpaOJh3jDwqFJu2V5ZSgn3oGumm1RNXNE8Niyn2swXaVqrvk6YMmgZXJJrwe6NhD/6wvZSAKWyIUy0uHE68sXFkH1iLsZ1yuHWg57cEYqKZYVRLAuQRgLIGJbwA1k4e8e7VM9cLj8xE+RN+8dygz+cTZw+GXvs67QQKBgQCEsSDZ5HDExFZCmb09hnvEPwql2zm2hnjzNlyBY9sf6i0GHeVlIpkEak4ahIRKpdHUfC6uLDkSs4ASaKC7iam8pvEuHHEhr2BLML+LHgurriMlXXqyA90vwlxAAVPWlKZZQXehss+HTmil8Xp7J4cFwYeJsXF/dzSRNuLtjaNhJwKBgDybaHnerkb4lQfTsQZa484G5Plcu0cMP7Bypon2Oq0H2+uCO+wXo/GOMWIZNJ8j0PMFbex3e0wMgR2wE+h6Ffn/MNM1hhI6nZq0cfbpBzeHIh1LgjqShGuSW1pLZLXKXbiL1dcFOgsjktRXN8eJpOan3TwWJ4FBEah2Ghh8NjOg"; // 支付宝开放平台生成
$alipay_public_key = "MIIBIjANBgkqhkiG9w0BAQEFAAOCAQ8AMIIBCgKCAQEAxgV3dMrgtyHfGwanBk6WTFgb1ad8AGHQ4wmCyjPsBaOgVs0DJX9DJFsvAih/NSoOTCR7B7u02AB3ReEM+xKZK0WHdsft4OKnNL5nbQliJzk4+DfbrTai7g4DU3Brpj1TGaKQ7Ip2lhxr1s694BSs1bSQtmcQUpWv7aQHTn49Qh3Rh/D1+Jcvxt8UczmE8RuN4QCQEfhewfqaZrAMOGbdmIFjpjjzmZLDNgcFUMd5uIggPBpnyNH4GypCgtQKrKgVxCGM7iLe4OD5AT9fnYaQbWCrAi7RpcPqN6EwjyMlbJYquypF961A9uMsMmyVm28eW4iFfLaW9vr0kaAjbN9v0wIDAQAB"; // 支付宝开放平台获取


// ======================================
// 【3. 已填入你的域名，无需修改】
// ======================================
$domain_infinityfree = "lu0414jie.free.nf";
$domain_netlify = "superlative-kashata-c77d5a.netlify.app";
// 自动适配回调地址（根据部署平台）
if ($deploy_platform === "infinityfree") {
    $notify_url = "http://{$domain_infinityfree}/index.php"; // InfinityFree（HTTP）
} else {
    $notify_url = "https://{$domain_netlify}/index.php"; // Netlify（HTTPS）
}

// ======================================
// 【4. 固定配置，无需修改】
// ======================================
$member_price = 9.9;                          // 会员价格
$user_data_file = "member_data.json";         // 多用户数据存储文件（自动生成）
$alipay_gateway = "https://openapi.alipay.com/gateway.do"; // 支付宝网关

// 工具函数：生成唯一订单号
function create_order_no() {
    return "VIP_" . date('YmdHis') . rand(1000, 9999);
}

// 工具函数：RSA2签名（无SDK核心）
function rsa2_sign($data, $private_key) {
    $search = ["-----BEGIN RSA PRIVATE KEY-----", "-----END RSA PRIVATE KEY-----", "\r", "\n"];
    $private_key = str_replace($search, "", $private_key);
    $private_key = "-----BEGIN RSA PRIVATE KEY-----\n" . wordwrap($private_key, 64, "\n", true) . "\n-----END RSA PRIVATE KEY-----";
    openssl_sign($data, $sign, $private_key, OPENSSL_ALGO_SHA256);
    return base64_encode($sign);
}

// 工具函数：验证支付宝签名（回调用）
function verify_sign($data, $sign, $public_key) {
    $search = ["-----BEGIN PUBLIC KEY-----", "-----END PUBLIC KEY-----", "\r", "\n"];
    $public_key = str_replace($search, "", $public_key);
    $public_key = "-----BEGIN PUBLIC KEY-----\n" . wordwrap($public_key, 64, "\n", true) . "\n-----END PUBLIC KEY-----";
    return openssl_verify($data, base64_decode($sign), $public_key, OPENSSL_ALGO_SHA256) === 1;
}

// 工具函数：多用户唯一标识（设备+IP+时间戳，避免冲突）
function get_user_id() {
    $user_agent = $_SERVER['HTTP_USER_AGENT'] ?? 'unknown';
    $ip = $_SERVER['REMOTE_ADDR'] ?? '127.0.0.1';
    return md5($user_agent . $ip . microtime());
}

// 支付宝异步回调处理（自动更新会员）
if ($_SERVER['REQUEST_METHOD'] === 'POST' && !empty($_POST['out_trade_no'])) {
    $data = $_POST;
    $sign = $data['sign'];
    unset($data['sign'], $data['sign_type']);
    
    ksort($data);
    $params_str = '';
    foreach ($data as $k => $v) {
        if ($v !== '' && !is_array($v)) $params_str .= $k . '=' . $v . '&';
    }
    $params_str = rtrim($params_str, '&');
    
    if (verify_sign($params_str, $sign, $GLOBALS['alipay_public_key']) && $data['trade_status'] === 'TRADE_SUCCESS') {
        $user_id = $data['passback_params'];
        $order_no = $data['out_trade_no'];
        
        $members = file_exists($GLOBALS['user_data_file']) ? json_decode(file_get_contents($GLOBALS['user_data_file']), true) : [];
        $members[$user_id] = [
            'order_no' => $order_no,
            'pay_time' => date('Y-m-d H:i:s'),
            'expire_time' => 'permanent'
        ];
        @file_put_contents($GLOBALS['user_data_file'], json_encode($members, JSON_UNESCAPED_UNICODE));
        echo 'success';
        exit;
    }
    echo 'fail';
    exit;
}

// 生成支付宝支付表单（点击支付触发）
if (isset($_GET['action']) && $_GET['action'] === 'pay') {
    $user_id = get_user_id();
    $order_no = create_order_no();
    $subject = "终身会员开通 - 专属隐私空间";
    
    $params = [
        'app_id' => $GLOBALS['alipay_appid'],
        'method' => 'alipay.trade.page.pay',
        'format' => 'json',
        'charset' => 'UTF-8',
        'sign_type' => 'RSA2',
        'timestamp' => date('Y-m-d H:i:s'),
        'version' => '1.0',
        'notify_url' => $GLOBALS['notify_url'],
        'return_url' => $GLOBALS['notify_url'],
        'biz_content' => json_encode([
            'out_trade_no' => $order_no,
            'total_amount' => $GLOBALS['member_price'],
            'subject' => $subject,
            'product_code' => 'FAST_INSTANT_TRADE_PAY',
            'passback_params' => $user_id
        ])
    ];
    
    ksort($params);
    $params_str = '';
    foreach ($params as $k => $v) {
        $params_str .= $k . '=' . $v . '&';
    }
    $params_str = rtrim($params_str, '&');
    $params['sign'] = rsa2_sign($params_str, $GLOBALS['alipay_private_key']);
    
    echo '<form id="alipay_form" action="' . $GLOBALS['alipay_gateway'] . '" method="post">';
    foreach ($params as $k => $v) {
        echo '<input type="hidden" name="' . $k . '" value="' . htmlspecialchars($v) . '">';
    }
    echo '</form><script>document.getElementById("alipay_form").submit();</script>';
    exit;
}

// 验证会员状态（多用户独立判断）
$is_member = false;
$user_id = get_user_id();
if (file_exists($user_data_file)) {
    $members = json_decode(@file_get_contents($user_data_file), true) ?? [];
    $is_member = isset($members[$user_id]) && $members[$user_id]['expire_time'] === 'permanent';
}
?>

<!-- 非会员页面 -->
<div id="non-member-page" style="display: <?php echo $is_member ? 'none' : 'block'; ?>">
    <div class="bg-puzzle">
        <div class="puzzle-item"></div><div class="puzzle-item"></div><div class="puzzle-item"></div><div class="puzzle-item"></div>
        <div class="puzzle-item"></div><div class="puzzle-item"></div><div class="puzzle-item"></div><div class="puzzle-item"></div>
        <div class="puzzle-item"></div><div class="puzzle-item"></div><div class="puzzle-item"></div><div class="puzzle-item"></div>
    </div>
    <div class="bg-mask"></div>
    <div class="main-title"><h1>您专属隐私空间</h1></div>
    
    <div class="price-section">
        <span class="tag">限时特价，90%人选</span>
        
        <div class="price-card">
            <h3>终身会员</h3>
            <div class="price-big">¥<?php echo $member_price; ?></div>
            <div class="price-desc">永久有效 | 平均0.03/天</div>
            <div class="feature-list">
                <p>✓ 私密空间 无限制导入</p>
                <p>✓ 高清原画 极速播放</p>
                <p>✓ 密码设置 保护隐私</p>
            </div>
            <div class="price-desc">永久解锁所有隐私空间功能</div>
        </div>
        <div class="open-btn-wrap">
            <a href="?action=pay" style="text-decoration: none;">
                <button class="open-btn">立即开启</button>
            </a>
        </div>
        <div class="privilege">
            <h4>会员特权</h4>
            <p>• 提供专属私密影视空间、私密照片空间；</p>
            <p>• 播放器设置解锁密码功能，防止他人访问；</p>
            <p>• 无限制导入本地文件，无容量上限；</p>
        </div>
    </div>
</div>

<!-- 会员页面 -->
<div id="member-page" class="member-page" style="display: <?php echo $is_member ? 'block' : 'none'; ?>">
    <div class="member-header">
        <h2>🎉 恭喜您成为终身VIP会员</h2>
        <p>以下为专属真实资源，点击直接访问</p>
    </div>
    <div class="resource-section">
        <h3><<i class="fas fa-film"></</i> 高清影视资源</h3>
        <div class="resource-grid">
            <div class="resource-item"><a href="https://www.iqiyi.com/" target="_blank"><<i class="fas fa-play"></</i><div class="name">爱奇艺</div><div class="desc">热门独播剧/综艺</div></a></div>
            <div class="resource-item"><a href="https://www.mgtv.com/" target="_blank"><<i class="fas fa-video"></</i><div class="name">芒果TV</div><div class="desc">自制综艺/偶像剧</div></a></div>
            <div class="resource-item"><a href="https://www.youku.com/" target="_blank"><<i class="fas fa-tv"></</i><div class="name">优酷视频</div><div class="desc">经典港剧/纪录片</div></a></div>
        </div>
    </div>
    <div class="resource-section">
        <h3><<i class="fas fa-book"></</i> 海量小说资源</h3>
        <div class="resource-grid">
            <div class="resource-item"><a href="https://fanqienovel.com/" target="_blank"><<i class="fas fa-book-open"></</i><div class="name">番茄小说</div><div class="desc">免费小说/听书</div></a></div>
            <div class="resource-item"><a href="https://www.jjwxc.net/" target="_blank"><<i class="fas fa-heart"></</i><div class="name">晋江文学城</div><div class="desc">原创言情/耽美</div></a></div>
            <div class="resource-item"><a href="https://www.qidian.com/" target="_blank"><<i class="fas fa-pen"></</i><div class="name">起点中文网</div><div class="desc">玄幻/都市/仙侠</div></a></div>
        </div>
    </div>
    <div class="resource-section">
        <h3><<i class="fas fa-mask"></</i> 热门动漫资源</h3>
        <div class="resource-grid">
            <div class="resource-item"><a href="https://www.bilibili.com/anime/" target="_blank"><<i class="fas fa-trophy"></</i><div class="name">B站动漫</div><div class="desc">正版番剧/国创</div></a></div>
            <div class="resource-item"><a href="https://ac.qq.com/" target="_blank"><<i class="fas fa-comic"></</i><div class="name">腾讯动漫</div><div class="desc">热门漫画/日漫</div></a></div>
            <div class="resource-item"><a href="https://www.dmzj.com/" target="_blank"><<i class="fas fa-magic"></</i><div class="name">动漫之家</div><div class="desc">海量漫画/无广告</div></a></div>
        </div>
    </div>
</div>
</body>
</html>
