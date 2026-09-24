<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>隐私政策 - 腕上咖啡因追踪</title>
<style>
  :root{
    --bg:#f5f6f8;
    --card:#ffffff;
    --text:#1a1a1a;
    --sub:#5b6470;
    --line:#e4e7ec;
    --accent:#ff7a1a;
  }
  *{box-sizing:border-box;margin:0;padding:0;}
  body{
    background:var(--bg);
    color:var(--text);
    font-family:-apple-system,BlinkMacSystemFont,"PingFang SC","Microsoft YaHei","Helvetica Neue",Arial,sans-serif;
    line-height:1.8;
    padding:24px 16px 64px;
  }
  .wrap{max-width:800px;margin:0 auto;}
  header{
    background:var(--card);
    border-radius:16px;
    padding:32px 28px;
    margin-bottom:20px;
    border:1px solid var(--line);
  }
  h1{
    font-size:26px;
    font-weight:700;
    margin-bottom:10px;
    letter-spacing:.5px;
  }
  .meta{color:var(--sub);font-size:14px;}
  .summary{
    margin-top:18px;
    padding:16px 18px;
    background:linear-gradient(135deg,#fff3e8,#ffe9d6);
    border-left:4px solid var(--accent);
    border-radius:8px;
    font-size:15px;
    color:#7a3d00;
  }
  section{
    background:var(--card);
    border:1px solid var(--line);
    border-radius:16px;
    padding:26px 28px;
    margin-bottom:16px;
  }
  h2{
    font-size:19px;
    font-weight:700;
    margin-bottom:14px;
    padding-bottom:10px;
    border-bottom:1px solid var(--line);
  }
  h3{font-size:16px;font-weight:600;margin:18px 0 8px;}
  p{margin-bottom:12px;font-size:15px;}
  ul{margin:0 0 12px 20px;font-size:15px;}
  li{margin-bottom:8px;}
  table{
    width:100%;
    border-collapse:collapse;
    margin:12px 0 16px;
    font-size:14px;
  }
  th,td{
    border:1px solid var(--line);
    padding:10px 12px;
    text-align:left;
    vertical-align:top;
  }
  th{background:#fafbfc;font-weight:600;}
  .tag{
    display:inline-block;
    background:#eef1f4;
    color:#46505c;
    border-radius:4px;
    padding:2px 8px;
    font-size:13px;
    margin-right:6px;
  }
  footer{
    text-align:center;
    color:var(--sub);
    font-size:13px;
    margin-top:32px;
  }
  @media (max-width:600px){
    header,section{padding:22px 18px;border-radius:12px;}
    h1{font-size:22px;}
  }
</style>
</head>
<body>
<div class="wrap">

<header>
  <h1>隐私政策</h1>
  <div class="meta">应用名称：腕上咖啡因追踪　|　开发者：个人开发者　|　生效日期：2026 年 9 月 25 日</div>
  <div class="summary">
    <strong>一句话总结：本应用不联网、不收集、不上传任何个人信息。</strong><br>
    你记录的每一杯咖啡因数据都只保存在你的手表本地，我们无法看到，也不会传给任何第三方。
  </div>
</header>

<section>
  <h2>一、我们收集哪些信息</h2>
  <p><strong>我们不收集任何个人信息。</strong>本应用没有服务器、没有账号系统、不需要注册或登录，也不会采集你的身份、位置、设备标识符或通讯录等信息。</p>
  <p>你在应用中产生的以下数据，<strong>全部仅保存在你的设备本地</strong>（手表本地存储）：</p>
  <ul>
    <li><strong>咖啡因摄入记录</strong>：记录时间、饮品名称、咖啡因毫克数</li>
    <li><strong>自定义饮品</strong>：饮品名称、咖啡因含量、显示颜色</li>
    <li><strong>个人设置</strong>：目标睡眠时间、每日摄入上限、咖啡因半衰期、睡前阈值、最常用饮品、提醒开关等</li>
  </ul>
  <p>这些数据仅用于在本机计算“当前体内咖啡因含量”和“睡前残留量”，不会离开你的设备。</p>
</section>

<section>
  <h2>二、我们申请的系统权限</h2>
  <p>本应用仅申请以下两项系统权限，且都只在本地功能中使用：</p>
  <table>
    <tr>
      <th style="width:32%">权限</th>
      <th style="width:28%">用途</th>
      <th>是否涉及数据上传</th>
    </tr>
    <tr>
      <td><span class="tag">ohos.permission.VIBRATE</span>振动</td>
      <td>记录咖啡因时提供震动反馈</td>
      <td>否，仅在本地触发设备振动</td>
    </tr>
    <tr>
      <td><span class="tag">ohos.permission.PUBLISH_AGENT_REMINDER</span>代理提醒</td>
      <td>在睡前时刻和咖啡因宵禁时刻推送系统提醒</td>
      <td>否，提醒由系统本地定时触发</td>
    </tr>
  </table>
  <p><strong>本应用未申请网络访问权限</strong>（未声明 ohos.permission.INTERNET），代码中不包含任何联网、上传或数据同步行为。你可以在任何时候在系统设置中关闭上述权限，关闭后对应的震动反馈或提醒功能将不可用，但不影响记录与计算等核心功能。</p>
</section>

<section>
  <h2>三、第三方服务与数据共享</h2>
  <p>本应用<strong>不接入任何第三方 SDK</strong>，包括但不限于：</p>
  <ul>
    <li>不含广告 SDK，不展示任何广告</li>
    <li>不含数据统计 / 埋点 SDK，不统计你的使用行为</li>
    <li>不含支付、社交、地图、推送等第三方服务</li>
    <li>不含任何崩溃上报或性能监控组件</li>
  </ul>
  <p>因此，我们<strong>不会与任何第三方公司、组织或个人共享、转让或公开披露你的数据</strong>。本应用也不存在向境外提供数据的情形。</p>
</section>

<section>
  <h2>四、数据存储与删除</h2>
  <h3>存储位置</h3>
  <p>所有数据保存在你的手表本地存储中，随应用一起存在于设备内。</p>
  <h3>存储期限</h3>
  <p>数据自你记录之日起保存在本地，直至你主动删除。应用不会自动上传或备份这些数据，也没有云端副本。</p>
  <h3>如何删除</h3>
  <ul>
    <li><strong>删除单日数据</strong>：在应用「设置」页使用「清空今日」即可删除当天全部记录</li>
    <li><strong>删除全部数据</strong>：在系统设置中卸载应用，或清除应用数据，本地所有记录将被完全删除且无法恢复</li>
  </ul>
  <p>卸载应用后，本地存储的数据会一并移除。</p>
</section>

<section>
  <h2>五、未成年人保护</h2>
  <p>本应用为咖啡因摄入记录工具，不针对未成年人设计，也不会主动收集未成年人的任何信息。由于本应用本身不收集任何个人信息，不存在收集或使用未成年人信息的情形。若未成年人使用本应用，建议在监护人指导下进行。</p>
</section>

<section>
  <h2>六、信息安全</h2>
  <p>由于数据仅保存在你的设备本地、且不进行任何网络传输，数据在传输环节不存在泄露风险。设备本身的访问安全（如锁屏密码、生物识别）由你自行管理，建议你开启设备锁屏以保护本地数据。</p>
</section>

<section>
  <h2>七、政策更新</h2>
  <p>若未来本应用的功能发生变化并涉及个人信息处理方式的调整，我们会更新本隐私政策并在本页面公布最新版本。由于当前版本不收集任何信息，政策内容发生重大变化时，我们会以显著方式提示你。</p>
</section>

<section>
  <h2>八、联系我们</h2>
  <p>如你对本隐私政策有任何疑问、意见或需要行使你的相关权利，可通过应用商店中开发者页面公示的联系方式与我们联系。我们将在收到反馈后尽快回复。</p>
</section>

<footer>
  <p>本隐私政策最终解释权归应用开发者所有</p>
  <p>生效日期：2026 年 9 月 25 日</p>
</footer>

</div>
</body>
</html>
