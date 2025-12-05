<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>NawaRaider v5</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Yusei+Magic&display=swap" rel="stylesheet">
    <style>
        :root {
           --primary-color: #a855f7;
            --secondary-color: #d8b4fe;
            --dark-bg: #0f071a;
            --card-bg: rgba(20, 10, 35, 0.85);
            --text-color: #f3e8ff;
            --error-color: #f87171;
            --success-color: #a855f7;
            --info-color: #60a5fa;
            --warning-color: #fbbf24;
            --border-radius: 20px;
        }

    * { box-sizing: border-box; margin: 0; padding: 0; }

    @keyframes rainbow-border {
        0%{background-position:0% 50%}
        50%{background-position:100% 50%}
        100%{background-position:0% 50%}
    }
    
    @keyframes fadeIn {
        from { opacity: 0; transform: translateY(30px); }
        to { opacity: 1; transform: translateY(0); }
    }
    
    @keyframes rainbow-text {
        0% { background-position: 0% 50%; }
        50% { background-position: 100% 50%; }
        100% { background-position: 0% 50%; }
    }

    body {
        font-family: 'Yusei Magic', sans-serif;
        background: linear-gradient(145deg, #0f071a 0%, #2a1a4a 100%);
        color: var(--text-color);
        min-height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        padding: 30px;
    }

    .container {
        background: var(--card-bg);
        backdrop-filter: blur(15px);
        border-radius: var(--border-radius);
        padding: 40px;
        width: 100%;
        max-width: 900px;
        animation: fadeIn 0.8s ease-out;
        position: relative;
    }
    
    .container::before {
        content: '';
        position: absolute;
        top: -3px; left: -3px;
        width: calc(100% + 6px);
        height: calc(100% + 6px);
        background: linear-gradient(60deg, #f79533, #f37055, #ef4e7b, #a166ab, #5073b8, #1098ad, #07b39b, #6fba82);
        background-size: 300% 300%;
        border-radius: var(--border-radius);
        animation: rainbow-border 4s linear infinite;
        z-index: -1;
    }

    h1 { font-size: 3.5rem; text-align: center; margin-bottom: 30px; letter-spacing: 4px; }
    .rainbow-text {
        background: linear-gradient(90deg, #ff0000, #ff7f00, #ffff00, #00ff00, #0000ff, #4b0082, #9400d3);
        background-size: 400% 400%; -webkit-background-clip: text; -webkit-text-fill-color: transparent;
        animation: rainbow-text 10s ease infinite;
    }

    .form-group { margin-bottom: 20px; }
    label { display: block; margin-bottom: 10px; font-weight: 600; color: var(--primary-color); font-size: 1.05rem; }
    .label-with-switch { display: flex; justify-content: space-between; align-items: center; }

    input, textarea {
        width: 100%; padding: 14px; border: none; border-radius: 12px;
        background: rgba(255, 255, 255, 0.1); color: var(--text-color);
        font-size: 1rem; font-family: 'Yusei Magic', sans-serif;
        transition: all 0.3s ease;
    }
    input:focus, textarea:focus { outline: none; box-shadow: 0 0 0 4px rgba(168, 85, 247, 0.5); }
    
    .switch { position: relative; display: inline-block; width: 60px; height: 34px; }
    .switch input { opacity: 0; width: 0; height: 0; }
    .slider { position: absolute; cursor: pointer; top: 0; left: 0; right: 0; bottom: 0; background-color: #4b5563; transition: .4s; border-radius: 34px; }
    .slider:before { position: absolute; content: ""; height: 26px; width: 26px; left: 4px; bottom: 4px; background-color: white; transition: .4s; border-radius: 50%; }
    input:checked + .slider { background-color: var(--primary-color); }
    input:checked + .slider:before { transform: translateX(26px); }
    input:disabled + .slider { background-color: #374151; cursor: not-allowed; }

    .button-group { display: flex; gap: 20px; margin-top: 30px; }
    button { flex: 1; padding: 16px; border: none; border-radius: 12px; cursor: pointer; font-weight: 600; font-size: 1.1rem; font-family: 'Yusei Magic', sans-serif; transition: all 0.3s ease; }
    #startBtn { background: linear-gradient(45deg, #a855f7, #d8b4fe); color: var(--dark-bg); }
    #stopBtn { background: linear-gradient(45deg, #ef4444, #f87171); color: var(--text-color); }
    #leaveServerBtn { background: linear-gradient(45deg, #f59e0b, #fbbf24); color: var(--dark-bg); }
    button:disabled { background: #4b5563; color: #9ca3af; cursor: not-allowed; }
    .fetch-btn { 
        flex: 0.5; 
        background: linear-gradient(45deg, #3b82f6, #60a5fa); 
        color: white;
        padding: 14px;
        height: auto;
    }
    #clear-data-btn { flex: 0; padding: 0 15px; font-size: 0.8rem; background: #6b7280; color: white; white-space: nowrap;}
    
    .logs-header { display: flex; justify-content: space-between; align-items: center; margin-top: 30px; }
    #logs { margin-top: 10px; height: 250px; background: rgba(0, 0, 0, 0.6); border-radius: 12px; padding: 20px; overflow-y: auto; font-size: 0.9rem;}
    .error { color: var(--error-color); } 
    .success { color: var(--success-color); } 
    .info { color: var(--info-color); }
    .warning { color: var(--warning-color); }
    .hidden { display: none; } 
    .note { font-size: 0.8rem; color: var(--secondary-color); margin-top: 8px; }

    .background-status {
        position: fixed;
        top: 30px;
        left: 30px;
        padding: 10px 20px;
        border-radius: 25px;
        font-size: 0.9rem;
        font-weight: 600;
        background: rgba(168, 85, 247, 0.2);
        border: 2px solid var(--primary-color);
        color: var(--text-color);
        backdrop-filter: blur(10px);
    }

    .background-status.active {
        background: rgba(34, 197, 94, 0.2);
        border-color: #22c55e;
        animation: pulse 2s infinite;
    }

    @keyframes pulse {
        0%, 100% { opacity: 1; }
        50% { opacity: 0.7; }
    }

    ::-webkit-scrollbar { width: 12px; }
    ::-webkit-scrollbar-track { background: rgba(0, 0, 0, 0.3); border-radius: 6px; }
    ::-webkit-scrollbar-thumb { background: var(--primary-color); border-radius: 6px; }

    .settings-grid {
        display: grid; 
        grid-template-columns: repeat(4, 1fr); 
        gap: 20px; 
        margin-bottom: 20px; 
        background: rgba(0,0,0,0.2); 
        padding: 15px; 
        border-radius: 12px;
    }

    .interval-with-random {
        display: flex;
        gap: 10px;
        align-items: end;
    }

    .interval-with-random .form-group {
        margin-bottom: 0;
    }

    .interval-with-random input {
        min-width: 0;
    }

    .random-type-selector {
        display: flex;
        gap: 5px;
        align-items: center;
        background: rgba(0,0,0,0.3);
        padding: 4px;
        border-radius: 8px;
        margin-top: 5px;
    }

    .random-type-btn {
        padding: 6px 12px;
        background: transparent;
        border: none;
        border-radius: 6px;
        color: var(--text-color);
        cursor: pointer;
        font-family: 'Yusei Magic', sans-serif;
        font-size: 0.85rem;
        transition: all 0.3s ease;
    }

    .random-type-btn.active {
        background: var(--primary-color);
        color: var(--dark-bg);
    }

    .mode-tabs {
        display: flex;
        background: rgba(0,0,0,0.3);
        border-radius: 12px;
        padding: 4px;
        margin-bottom: 20px;
    }

    .mode-tab {
        flex: 1;
        padding: 12px;
        background: transparent;
        border: none;
        border-radius: 8px;
        color: var(--text-color);
        cursor: pointer;
        font-family: 'Yusei Magic', sans-serif;
        transition: all 0.3s ease;
    }

    .mode-tab.active {
        background: var(--primary-color);
        color: var(--dark-bg);
    }

    .transfer-inputs {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 15px;
    }
</style>
</head>
<body>
    <div class="background-status" id="backgroundStatus">バックグラウンド: 停止</div>

<div class="container">
    <h1 class="rainbow-text">NawaRaider v5</h1>
    
    <div style="display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 20px;">
        <div class="form-group"><label for="tokens">トークン:</label><textarea id="tokens" rows="3"></textarea></div>
        <div class="form-group"><label for="userIds">メンション対象ユーザーID:</label><textarea id="userIds" rows="3"></textarea></div>
        <div class="form-group"><label for="messageIds">返信対象メッセージID:</label><textarea id="messageIds" rows="3" placeholder="メッセージIDを1行ずつ入力..."></textarea></div>
    </div>
    <div class="form-group">
        <label for="serverId">サーバーID (ID取得用):</label>
        <div style="display: flex; gap: 15px;">
            <input type="text" id="serverId" />
            <button id="fetchChannels" class="fetch-btn">CH ID</button>
            <button id="fetchUsers" class="fetch-btn">User ID</button>
            <button id="fetchMessages" class="fetch-btn">Msg ID (最新)</button>
            <button id="fetchMessagesPerUser" class="fetch-btn">Msg ID (ユーザー別)</button>
        </div>
    </div>
    <div class="form-group">
        <label for="channelIds">チャンネルID:</label><textarea id="channelIds" rows="3" placeholder="チャンネルIDを1行ずつ入力..."></textarea>
    </div>
    
    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(150px, 1fr)); gap: 20px; align-items: end;">
        <div class="form-group"><label for="mentionCount">メンション人数:</label><input type="number" id="mentionCount" min="0" value="0"/></div>
        <div id="channelIntervalInput" class="form-group hidden">
            <label for="channelInterval">チャンネル別間隔 (ms):</label>
            <input type="number" id="channelInterval" value="2000" min="100"/>
        </div>
        <div id="deleteDelayGroup" class="form-group hidden">
            <label for="deleteDelay">削除遅延 (ms):</label>
            <input type="number" id="deleteDelay" min="0" value="400"/>
        </div>
        <div id="intervalGroup" class="form-group">
            <div class="interval-with-random">
                <div class="form-group" style="flex: 1;"><label for="interval" id="intervalLabel">送信間隔 (ms):</label><input type="number" id="interval" value="2000" min="100"/></div>
                <div id="randomCharsGroup" class="form-group hidden">
                    <label for="randomChars">文字数:</label>
                    <input type="number" id="randomChars" value="5" min="1" max="50" style="width: 80px;"/>
                    <div class="random-type-selector">
                        <button class="random-type-btn active" data-type="emoji">絵文字</button>
                        <button class="random-type-btn" data-type="text">英字</button>
                    </div>
                </div>
            </div>
        </div>
        <div id="repeatCountGroup" class="form-group hidden"><label for="repeatCount">繰り返し回数 (0=無限):</label><input type="number" id="repeatCount" min="0" value="0" /></div>
    </div>
    
    <div class="settings-grid">
        <div class="form-group"><div class="label-with-switch"><label for="repeatToggle">繰り返し</label><label class="switch"><input type="checkbox" id="repeatToggle"><span class="slider"></span></label></div></div>
        <div class="form-group"><div class="label-with-switch"><label for="pollToggle">投票機能</label><label class="switch"><input type="checkbox" id="pollToggle"><span class="slider"></span></label></div></div>
        <div class="form-group"><div class="label-with-switch"><label for="transferToggle">メッセージ転送</label><label class="switch"><input type="checkbox" id="transferToggle"><span class="slider"></span></label></div></div>
        <div class="form-group"><div class="label-with-switch"><label for="randomToggle">ランダム文字</label><label class="switch"><input type="checkbox" id="randomToggle"><span class="slider"></span></label></div></div>
        <div class="form-group"><div class="label-with-switch"><label for="randomReplyToggle">ランダム返信</label><label class="switch"><input type="checkbox" id="randomReplyToggle"><span class="slider"></span></label></div></div>
        <div class="form-group"><div class="label-with-switch"><label for="replyMentionToggle">返信時メンション</label><label class="switch"><input type="checkbox" id="replyMentionToggle" checked><span class="slider"></span></label></div></div>
        <div class="form-group"><div class="label-with-switch"><label for="channelIntervalToggle">チャンネル別間隔</label><label class="switch"><input type="checkbox" id="channelIntervalToggle"><span class="slider"></span></label></div></div>
        <div class="form-group"><div class="label-with-switch"><label for="perAccountIntervalToggle">垢ごとの送信間隔</label><label class="switch"><input type="checkbox" id="perAccountIntervalToggle" disabled><span class="slider"></span></label></div></div>
        <div class="form-group"><div class="label-with-switch"><label for="instantDeleteToggle">即削除</label><label class="switch"><input type="checkbox" id="instantDeleteToggle"><span class="slider"></span></label></div></div>
    </div>
    
    <!-- モード選択タブ -->
    <div id="modeSelection" class="mode-tabs">
        <button class="mode-tab active" data-mode="message">通常メッセージ</button>
        <button class="mode-tab" data-mode="poll">投票</button>
        <button class="mode-tab" data-mode="transfer">メッセージ転送</button>
    </div>

    <!-- 投票設定 -->
    <div id="pollGroup" class="hidden">
        <div class="form-group"><label for="pollQuestion">投票の質問:</label><input type="text" id="pollQuestion"></div>
        <div class="form-group"><label for="pollOptions">選択肢 (1行に1つ, 最大20):</label><textarea id="pollOptions" rows="4"></textarea></div>
    </div>

    <!-- メッセージ転送設定 -->
    <div id="transferGroup" class="hidden">
        <div class="transfer-inputs">
            <div class="form-group">
                <label for="sourceGuildId">転送元サーバーID:</label>
                <input type="text" id="sourceGuildId" placeholder="元のサーバーID">
            </div>
            <div class="form-group">
                <label for="sourceChannelId">転送元チャンネルID:</label>
                <input type="text" id="sourceChannelId" placeholder="元のチャンネルID">
            </div>
        </div>
        <div class="form-group">
            <label for="sourceMessageIds">転送するメッセージID:</label>
            <textarea id="sourceMessageIds" rows="4" placeholder="メッセージIDを1行ずつ入力...&#10;例:&#10;1234567890123456789&#10;9876543210987654321"></textarea>
            <p class="note">複数のメッセージIDを1行ずつ入力。ランダムまたは順番に使用されます</p>
        </div>
        <div class="form-group">
            <div style="display: flex; gap: 15px; align-items: center;">
                <label class="switch"><input type="checkbox" id="includeAttachments"><span class="slider"></span></label>
                <label for="includeAttachments" style="margin: 0;">添付ファイルのURLも転送する</label>
                
                <label class="switch"><input type="checkbox" id="randomOrder"><span class="slider"></span></label>
                <label for="randomOrder" style="margin: 0;">ランダム順序で転送</label>
            </div>
        </div>
        <div class="form-group">
            <button id="fetchMessageBtn" class="fetch-btn" style="width: 200px;">メッセージ内容をプレビュー</button>
            <p class="note">メッセージIDが正しいかテスト取得できます</p>
        </div>
    </div>

    <!-- 通常メッセージ設定 -->
    <div id="messageGroup" class="form-group">
        <label for="message">メッセージ:</label>
        <textarea id="message" rows="4" placeholder="メッセージ内で {mention} を使うとその場所にメンションを挿入できます"></textarea>
        <p class="note">ヒント: メッセージ内に {mention} があればその位置にメンションを挿入、なければ最初にメンションします</p>
    </div>
    
    <div class="button-group">
        <button id="startBtn">発射</button>
        <button id="stopBtn" disabled>停止</button>
        <button id="leaveServerBtn">サーバー退出</button>
    </div>
    <div class="logs-header"><label>ログ:</label><button id="clear-data-btn">保存データをクリア</button></div>
    <div id="logs"></div>
</div>

<script>
    const el = {
        tokens: document.getElementById('tokens'), serverId: document.getElementById('serverId'), channelIds: document.getElementById('channelIds'),
        userIds: document.getElementById('userIds'), messageIds: document.getElementById('messageIds'), mentionCount: document.getElementById('mentionCount'), interval: document.getElementById('interval'),
        intervalLabel: document.getElementById('intervalLabel'), channelInterval: document.getElementById('channelInterval'), channelIntervalInput: document.getElementById('channelIntervalInput'),
        deleteDelayGroup: document.getElementById('deleteDelayGroup'), deleteDelay: document.getElementById('deleteDelay'),
        message: document.getElementById('message'), startBtn: document.getElementById('startBtn'), stopBtn: document.getElementById('stopBtn'),
        fetchChannels: document.getElementById('fetchChannels'), fetchUsers: document.getElementById('fetchUsers'), 
        fetchMessages: document.getElementById('fetchMessages'), fetchMessagesPerUser: document.getElementById('fetchMessagesPerUser'), logs: document.getElementById('logs'),
        repeatToggle: document.getElementById('repeatToggle'), repeatCountGroup: document.getElementById('repeatCountGroup'), repeatCount: document.getElementById('repeatCount'),
        pollToggle: document.getElementById('pollToggle'), pollGroup: document.getElementById('pollGroup'), pollQuestion: document.getElementById('pollQuestion'),
        pollOptions: document.getElementById('pollOptions'), messageGroup: document.getElementById('messageGroup'),
        transferToggle: document.getElementById('transferToggle'), transferGroup: document.getElementById('transferGroup'),
        sourceGuildId: document.getElementById('sourceGuildId'), sourceChannelId: document.getElementById('sourceChannelId'), sourceMessageIds: document.getElementById('sourceMessageIds'),
        includeAttachments: document.getElementById('includeAttachments'), randomOrder: document.getElementById('randomOrder'),
        fetchMessageBtn: document.getElementById('fetchMessageBtn'),
        channelIntervalToggle: document.getElementById('channelIntervalToggle'),
        intervalGroup: document.getElementById('intervalGroup'), clearDataBtn: document.getElementById('clear-data-btn'),
        leaveServerBtn: document.getElementById('leaveServerBtn'), backgroundStatus: document.getElementById('backgroundStatus'),
        randomToggle: document.getElementById('randomToggle'), randomCharsGroup: document.getElementById('randomCharsGroup'), randomChars: document.getElementById('randomChars'),
        modeSelection: document.getElementById('modeSelection'), instantDeleteToggle: document.getElementById('instantDeleteToggle'),
        perAccountIntervalToggle: document.getElementById('perAccountIntervalToggle'), randomReplyToggle: document.getElementById('randomReplyToggle'),
        replyMentionToggle: document.getElementById('replyMentionToggle')
    };
    const STORAGE_KEY = 'nawaraider_data';
    let intervalIds = [];
    let isRunning = false;
    let backgroundWorker = null;
    let currentMode = 'message';
    let randomType = 'emoji';

    const parseList = (input) => [...new Set(input.split(/[\s,\n]+/).map(item => item.trim()).filter(Boolean))];
    const shuffleArray = (array) => { for (let i = array.length - 1; i > 0; i--) { const j = Math.floor(Math.random() * (i + 1));[array[i], array[j]] = [array[j], array[i]]; } return array; };
    
    function logMessage(msg, type = 'info') {
        const time = new Date().toLocaleTimeString('ja-JP');
        const logLine = document.createElement('div');
        logLine.className = type;
        logLine.textContent = `[${time}] ${msg}`;
        el.logs.appendChild(logLine);
        el.logs.scrollTop = el.logs.scrollHeight;
    }

    function updateBackgroundStatus(isActive) {
        if (isActive) {
            el.backgroundStatus.textContent = 'バックグラウンド: 実行中';
            el.backgroundStatus.classList.add('active');
        } else {
            el.backgroundStatus.textContent = 'バックグラウンド: 停止';
            el.backgroundStatus.classList.remove('active');
        }
    }

    function generateRandomString(length, type = 'emoji') {
        let result = '';
        const actualLength = parseInt(length) || 1;
        
        if (type === 'emoji') {
            const emojis = ['😀','😁','😂','🤣','😃','😄','😅','😆','😉','😊','😋','😎','😍','😘','🥰','😗','😙','😚','☺️','🙂','🤗','🤩','🤔','🤨','😐','😑','😶','🙄','😏','😣','😥','😮','🤐','😯','😪','😫','😴','😌','😛','😜','😝','🤤','😒','😓','😔','😕','🙃','🤑','😲','☹️','🙁','😖','😞','😟','😤','😢','😭','😦','😧','😨','😩','🤯','😬','😰','😱','🥵','🥶','😳','🤪','😵','😡','😠','🤬','😷','🤒','🤕','🤢','🤮','🤧','😇','🤠','🤡','🥳','🥴','🥺','🤥','🤫','🤭','🧐','🤓','😈','👿','👹','👺','💀','👻','👽','🤖','💩','😺','😸','😹','😻','😼','😽','🙀','😿','😾'];
            for (let i = 0; i < actualLength; i++) {
                result += emojis[Math.floor(Math.random() * emojis.length)];
            }
        } else {
            const chars = 'ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz';
            for (let i = 0; i < actualLength; i++) {
                result += chars.charAt(Math.floor(Math.random() * chars.length));
            }
        }
        return result;
    }

    const saveData = () => {
        const data = { currentMode, randomType };
        Object.keys(el).forEach(key => {
            if (el[key] && el[key].id && key !== 'backgroundStatus' && key !== 'modeSelection') {
                if (el[key].type === 'checkbox') data[key] = el[key].checked;
                else data[key] = el[key].value;
            }
        });
        localStorage.setItem(STORAGE_KEY, JSON.stringify(data));
    };

    const loadData = () => {
        const data = JSON.parse(localStorage.getItem(STORAGE_KEY));
        if (!data) return;
        
        if (data.currentMode) {
            currentMode = data.currentMode;
            document.querySelector(`[data-mode="${currentMode}"]`)?.click();
        }
        
        if (data.randomType) {
            randomType = data.randomType;
            document.querySelectorAll('.random-type-btn').forEach(btn => {
                if (btn.dataset.type === randomType) {
                    btn.classList.add('active');
                } else {
                    btn.classList.remove('active');
                }
            });
        }
        
        Object.keys(data).forEach(key => {
            if (el[key]) {
                if (el[key].type === 'checkbox') el[key].checked = data[key];
                else el[key].value = data[key];
                el[key].dispatchEvent(new Event('change', { bubbles: true }));
            }
        });
        logMessage('保存されたデータを読み込みました。', 'success');
    };
    
    el.repeatToggle.addEventListener('change', () => el.repeatCountGroup.classList.toggle('hidden', !el.repeatToggle.checked));
    el.randomToggle.addEventListener('change', (e) => {
        el.randomCharsGroup.classList.toggle('hidden', !e.target.checked);
    });
    el.channelIntervalToggle.addEventListener('change', (e) => {
        const isPerChannel = e.target.checked;
        el.channelIntervalInput.classList.toggle('hidden', !isPerChannel);
        if (isPerChannel) {
            if(el.repeatToggle.checked) el.repeatToggle.click();
            el.repeatToggle.disabled = true;
        } else { 
            el.repeatToggle.disabled = false; 
        }
    });

    el.tokens.addEventListener('input', () => {
        const tokens = parseList(el.tokens.value);
        el.perAccountIntervalToggle.disabled = tokens.length < 1;
        if (tokens.length < 1) el.perAccountIntervalToggle.checked = false;
        saveData();
    });
    el.perAccountIntervalToggle.addEventListener('change', (e) => {
        if (el.intervalLabel) {
            const isPerAccount = e.target.checked;
            el.intervalLabel.textContent = isPerAccount ? 'アカウントごとの送信間隔 (ms):' : '送信間隔 (ms):';
        }
        saveData();
    });

    el.instantDeleteToggle.addEventListener('change', (e) => {
        const isInstantDelete = e.target.checked;
        if (el.deleteDelayGroup) {
            el.deleteDelayGroup.classList.toggle('hidden', !isInstantDelete);
        }
        saveData();
    });

    el.modeSelection.addEventListener('click', (e) => {
        if (e.target.classList.contains('mode-tab')) {
            document.querySelectorAll('.mode-tab').forEach(tab => tab.classList.remove('active'));
            e.target.classList.add('active');
            
            currentMode = e.target.dataset.mode;
            
            el.messageGroup.classList.add('hidden');
            el.pollGroup.classList.add('hidden');
            el.transferGroup.classList.add('hidden');
            
            if (currentMode === 'message') {
                el.messageGroup.classList.remove('hidden');
                if (el.pollToggle.checked) {
                    el.pollGroup.classList.remove('hidden');
                }
            } else if (currentMode === 'poll') {
                el.pollGroup.classList.remove('hidden');
            } else if (currentMode === 'transfer') {
                el.transferGroup.classList.remove('hidden');
            }
            
            el.pollToggle.checked = currentMode === 'poll';
            el.transferToggle.checked = currentMode === 'transfer';
        }
    });

    el.pollToggle.addEventListener('change', (e) => {
        if (currentMode === 'message' && e.target.checked) {
            el.pollGroup.classList.remove('hidden');
        } else if (currentMode === 'message' && !e.target.checked) {
            el.pollGroup.classList.add('hidden');
        }
        saveData();
    });

    document.addEventListener('click', (e) => {
        if (e.target.classList.contains('random-type-btn')) {
            document.querySelectorAll('.random-type-btn').forEach(btn => btn.classList.remove('active'));
            e.target.classList.add('active');
            randomType = e.target.dataset.type;
            saveData();
        }
    });

    el.fetchChannels.addEventListener('click', async () => {
        const serverId = el.serverId.value.trim();
        const token = parseList(el.tokens.value)[0];
        if (!serverId || !token) return logMessage('サーバーIDとトークンが必要です。', 'error');
        logMessage('チャンネルIDを取得中...', 'info');
        try {
            const res = await fetch(`https://discord.com/api/v10/guilds/${serverId}/channels`, { headers: { 'Authorization': token }});
            if (res.ok) {
                const channels = (await res.json()).filter(c => c.type === 0).map(c => c.id);
                el.channelIds.value = channels.join('\n');
                logMessage(`${channels.length}件のテキストチャンネルIDを取得。`, 'success');
            } else { logMessage(`チャンネル取得エラー: ${res.status}`, 'error'); }
        } catch(e) { logMessage(`チャンネル取得例外: ${e.message}`, 'error'); }
    });

    async function fetchUsers(serverId, token, channelIds) {
        logMessage('ユーザーID取得を開始します (WebSocket)...', 'info');
        try {
            const ws = new WebSocket('wss://gateway.discord.gg/?v=9&encoding=json');
            ws.onopen = () => { ws.send(JSON.stringify({ op: 2, d: { token: token, properties: { os: 'Windows', browser: 'Discord', device: 'pc' }, intents: 1 << 12 }})); };
            ws.onmessage = (event) => {
                const data = JSON.parse(event.data);
                if (data.t === 'READY') { ws.send(JSON.stringify({ op: 14, d: { guild_id: serverId, typing: false, activities: false, threads: true, channels: { [channelIds[0]]: [[0, 0]] } } })); }
                if (data.t === 'GUILD_MEMBER_LIST_UPDATE') {
                    const userIds = data.d.ops[0].items.filter(item => item.member).map(item => item.member.user.id);
                    if (userIds.length) {
                        const existingIds = new Set(parseList(el.userIds.value));
                        userIds.forEach(id => existingIds.add(id));
                        el.userIds.value = [...existingIds].join('\n');
                        logMessage(`ユーザーIDを${userIds.length}件追加しました。合計: ${existingIds.size}件`, 'success');
                    }
                    ws.close();
                }
            };
            ws.onerror = () => { logMessage('WebSocketエラー: トークンが無効かサーバーにアクセスできません。', 'error'); ws.close(); };
            ws.onclose = () => { logMessage('WebSocket接続を閉じました。', 'info'); };
        } catch (err) { logMessage(`ユーザー取得エラー: ${err.message}`, 'error'); }
    }

    el.fetchUsers.addEventListener('click', () => {
        const serverId = el.serverId.value.trim();
        const token = parseList(el.tokens.value)[0];
        const channelIds = parseList(el.channelIds.value);
        if (!serverId || !token || !channelIds.length) return logMessage('サーバーID、トークン、チャンネルIDが必要です。', 'error');
        fetchUsers(serverId, token, channelIds);
    });

    el.fetchMessages.addEventListener('click', async () => {
        const token = parseList(el.tokens.value)[0];
        const channelIds = parseList(el.channelIds.value);
        
        if (!token || !channelIds.length) {
            return logMessage('トークンとチャンネルIDが必要です。', 'error');
        }
        
        logMessage('メッセージIDを取得中...（最新100件まで）', 'info');
        
        const allMessageIds = new Set();
        
        for (const channelId of channelIds) {
            try {
                const res = await fetch(`https://discord.com/api/v10/channels/${channelId}/messages?limit=100`, {
                    headers: { 'Authorization': token }
                });
                
                if (res.ok) {
                    const messages = await res.json();
                    messages.forEach(msg => allMessageIds.add(msg.id));
                    logMessage(`チャンネル ${channelId} から ${messages.length}件のメッセージIDを取得`, 'success');
                } else if (res.status === 403) {
                    logMessage(`チャンネル ${channelId} へのアクセス権限がありません`, 'warning');
                } else {
                    logMessage(`チャンネル ${channelId} 取得エラー: ${res.status}`, 'error');
                }
                
                await new Promise(r => setTimeout(r, 300));
            } catch (err) {
                logMessage(`チャンネル ${channelId} 取得例外: ${err.message}`, 'error');
            }
        }
        
        if (allMessageIds.size > 0) {
            const existingIds = new Set(parseList(el.messageIds.value));
            allMessageIds.forEach(id => existingIds.add(id));
            el.messageIds.value = [...existingIds].join('\n');
            logMessage(`合計 ${allMessageIds.size}件の新しいメッセージIDを追加しました（総計: ${existingIds.size}件）`, 'success');
        } else {
            logMessage('メッセージIDを取得できませんでした', 'warning');
        }
    });

    el.fetchMessagesPerUser.addEventListener('click', async () => {
        const token = parseList(el.tokens.value)[0];
        const channelIds = parseList(el.channelIds.value);
        
        if (!token || !channelIds.length) {
            return logMessage('トークンとチャンネルIDが必要です。', 'error');
        }
        
        logMessage('メッセージIDを取得中...（ユーザーごとに1件、最大100ユーザー）', 'info');
        
        const allMessageIds = new Set();
        const userMessageMap = new Map();
        
        for (const channelId of channelIds) {
            try {
                const res = await fetch(`https://discord.com/api/v10/channels/${channelId}/messages?limit=100`, {
                    headers: { 'Authorization': token }
                });
                
                if (res.ok) {
                    const messages = await res.json();
                    let addedCount = 0;
                    
                    for (const msg of messages) {
                        if (userMessageMap.size >= 100) break;
                        
                        const userId = msg.author.id;
                        if (!userMessageMap.has(userId)) {
                            userMessageMap.set(userId, msg.id);
                            allMessageIds.add(msg.id);
                            addedCount++;
                        }
                    }
                    
                    logMessage(`チャンネル ${channelId} から ${addedCount}ユーザーのメッセージIDを追加（累計: ${userMessageMap.size}ユーザー）`, 'success');
                } else if (res.status === 403) {
                    logMessage(`チャンネル ${channelId} へのアクセス権限がありません`, 'warning');
                } else {
                    logMessage(`チャンネル ${channelId} 取得エラー: ${res.status}`, 'error');
                }
                
                if (userMessageMap.size >= 100) {
                    logMessage('100ユーザー分のメッセージIDを取得したため終了します', 'info');
                    break;
                }
                
                await new Promise(r => setTimeout(r, 300));
            } catch (err) {
                logMessage(`チャンネル ${channelId} 取得例外: ${err.message}`, 'error');
            }
        }
        
        if (allMessageIds.size > 0) {
            const existingIds = new Set(parseList(el.messageIds.value));
            allMessageIds.forEach(id => existingIds.add(id));
            el.messageIds.value = [...existingIds].join('\n');
            logMessage(`合計 ${allMessageIds.size}件の新しいメッセージIDを追加しました（総計: ${existingIds.size}件）`, 'success');
        } else {
            logMessage('メッセージIDを取得できませんでした', 'warning');
        }
    });

    async function fetchMessageById(token, guildId, channelId, messageId) {
        try {
            const res = await fetch(`https://discord.com/api/v10/channels/${channelId}/messages/${messageId}`, {
                headers: { 'Authorization': token }
            });
            
            if (!res.ok) {
                throw new Error(`HTTP ${res.status}`);
            }
            
            const message = await res.json();
            return { ...message, guildId };
        } catch (err) {
            logMessage(`メッセージ取得エラー (ID: ${messageId}): ${err.message}`, 'error');
            return null;
        }
    }

    async function fetchMessagesByIds(token, guildId, channelId, messageIds) {
        const messages = [];
        logMessage(`${messageIds.length}件のメッセージを取得中...`, 'info');
        
        for (const messageId of messageIds) {
            const message = await fetchMessageById(token, guildId, channelId, messageId.trim());
            if (message) {
                messages.push(message);
                const preview = (message.content || '').length > 50 ? (message.content.slice(0, 50) + '...') : (message.content || '（空内容）');
                logMessage(`メッセージ取得成功: ${messageId} (${preview})`, 'success');
                if (message.attachments && message.attachments.length > 0) {
                    logMessage(`  └ 添付: ${message.attachments.length}件`, 'info');
                }
            } else {
                logMessage(`メッセージ取得失敗: ${messageId}`, 'error');
            }
            
            await new Promise(r => setTimeout(r, 200));
        }
        
        return messages;
    }

    el.fetchMessageBtn.addEventListener('click', async () => {
        const token = parseList(el.tokens.value)[0];
        const guildId = el.sourceGuildId.value.trim();
        const channelId = el.sourceChannelId.value.trim();
        const messageIds = parseList(el.sourceMessageIds.value);
        
        if (!token || !guildId || !channelId || !messageIds.length) {
            return logMessage('トークン、サーバーID、チャンネルID、メッセージIDが必要です。', 'error');
        }
        
        logMessage('メッセージをプレビュー取得中...', 'info');
        
        for (let i = 0; i < Math.min(messageIds.length, 3); i++) {
            const messageId = messageIds[i].trim();
            const message = await fetchMessageById(token, guildId, channelId, messageId);
            
            if (message) {
                const preview = (message.content || '').length > 100 
                    ? (message.content.slice(0, 100) + '...') 
                    : (message.content || '（空内容）');
                logMessage(`[プレビュー] ${messageId}: "${preview}" (guild: ${guildId}, ch: ${channelId})`, 'info');
                
                if (message.attachments && message.attachments.length > 0) {
                    logMessage(`  └ 添付ファイル: ${message.attachments.length}件`, 'info');
                }
            } else {
                logMessage(`[プレビュー] ${messageId}: 取得失敗`, 'error');
            }
            
            await new Promise(r => setTimeout(r, 300));
        }
        
        if (messageIds.length > 3) {
            logMessage(`残り${messageIds.length - 3}件のメッセージも登録されています。`, 'info');
        }
    });

    el.leaveServerBtn.addEventListener('click', async () => {
        const serverId = el.serverId.value.trim();
        const tokens = parseList(el.tokens.value);
        
        if (!serverId || !tokens.length) return logMessage('サーバーIDとトークンが必要です。', 'error');
        
        if (!confirm('全てのトークンでサーバーから退出しますか？この操作は取り消せません。')) return;
        
        logMessage('サーバー退出を開始します...', 'warning');
        
        for (const token of tokens) {
            try {
                const res = await fetch(`https://discord.com/api/v10/users/@me/guilds/${serverId}`, {
                    method: 'DELETE',
                    headers: { 'Authorization': token }
                });
                
                if (res.ok) {
                    logMessage(`トークンでサーバー退出成功: ${token.slice(0, 20)}...`, 'success');
                } else if (res.status === 404) {
                    logMessage(`既にサーバーにいないか存在しないサーバー: ${token.slice(0, 20)}...`, 'warning');
                } else {
                    const data = await res.json();
                    logMessage(`サーバー退出エラー: ${token.slice(0, 20)}... status=${res.status} msg=${JSON.stringify(data.message)}`, 'error');
                }
            } catch (err) {
                logMessage(`サーバー退出例外: ${token.slice(0, 20)}... ${err.message}`, 'error');
            }
            
            await new Promise(r => setTimeout(r, 500));
        }
        
        logMessage('サーバー退出処理が完了しました。', 'info');
    });

    async function sendApiRequest(token, channelId, payload) {
        if (!isRunning) return;
        
        try {
            const res = await fetch(`https://discord.com/api/v10/channels/${channelId}/messages`, {
                method: 'POST', headers: { 'Authorization': token, 'Content-Type': 'application/json' }, body: JSON.stringify(payload)
            });
            const data = await res.json();
            if (res.ok) { 
                if (isRunning) logMessage(`送信成功: ch=${channelId}${payload.message_reference ? ` (reply to: ${payload.message_reference.message_id})` : ''}`, 'success'); 
                if (el.instantDeleteToggle.checked && data.id) {
                    const delayMs = parseInt(el.deleteDelay.value) || 400;
                    if (isRunning) logMessage(`削除待機中: ch=${channelId}, msg=${data.id} (遅延: ${delayMs}ms)`, 'info');
                    await new Promise(r => setTimeout(r, delayMs));
                    try {
                        const deleteRes = await fetch(`https://discord.com/api/v10/channels/${channelId}/messages/${data.id}`, {
                            method: 'DELETE',
                            headers: { 'Authorization': token }
                        });
                        if (deleteRes.ok) {
                            if (isRunning) logMessage(`削除成功: ch=${channelId}, msg=${data.id}`, 'success');
                        } else {
                            if (isRunning) logMessage(`削除エラー: ch=${channelId}, msg=${data.id}, status=${deleteRes.status}`, 'error');
                        }
                    } catch (err) {
                        if (isRunning) logMessage(`削除例外: ch=${channelId}, msg=${data.id}, ${err.message}`, 'error');
                    }
                }
            }
            else if (res.status === 429) {
                const waitTime = (data.retry_after * 1000 || 1000) + 200;
                if (isRunning) logMessage(`レート制限: ${waitTime / 1000}秒待機...`, 'error');
                await new Promise(r => setTimeout(r, waitTime));
                if (isRunning) await sendApiRequest(token, channelId, payload);
            } else { 
                if (isRunning) logMessage(`送信エラー: ch=${channelId} status=${res.status} msg=${JSON.stringify(data.errors || data.message)}`, 'error'); 
            }
        } catch (err) { 
            if (isRunning) logMessage(`送信例外: ${err.message}`, 'error'); 
        }
    }
    
    const stopSending = () => {
        isRunning = false;
        intervalIds.forEach(clearInterval); 
        intervalIds = [];
        
        el.startBtn.disabled = false; 
        el.stopBtn.disabled = true;
        el.startBtn.textContent = '発射';
        updateBackgroundStatus(false);
        logMessage('全てのタスクを停止しました。', 'success');
    };

    el.stopBtn.addEventListener('click', stopSending);
    el.startBtn.addEventListener('click', async () => {
        const tokens = parseList(el.tokens.value);
        const userIds = parseList(el.userIds.value);
        const replyMessageIds = parseList(el.messageIds.value);
        const mentionCount = parseInt(el.mentionCount.value) || 0;
        if (!tokens.length) return logMessage('トークンを入力してください。', 'error');

        let basePayload = {};
        let transferMessages = [];
        let sourceMessageIds = [];

        if (currentMode === 'poll') {
            const question = el.pollQuestion.value.trim();
            const options = el.pollOptions.value.split('\n').map(o => o.trim()).filter(Boolean);
            if (!question || options.length < 2) return logMessage('投票には質問と少なくとも2つの選択肢が必要です。', 'error');
            basePayload.poll = { question: { text: question }, answers: options.slice(0, 20).map(opt => ({ poll_media: { text: opt }})), duration: 1, allow_multiselect: false };
            const message = el.message.value.trim();
            if (message) basePayload.content = message;
        } else if (currentMode === 'message' && el.pollToggle.checked) {
            const question = el.pollQuestion.value.trim();
            const options = el.pollOptions.value.split('\n').map(o => o.trim()).filter(Boolean);
            if (!question || options.length < 2) return logMessage('投票には質問と少なくとも2つの選択肢が必要です。', 'error');
            basePayload.poll = { question: { text: question }, answers: options.slice(0, 20).map(opt => ({ poll_media: { text: opt }})), duration: 1, allow_multiselect: false };
            const message = el.message.value.trim();
            if (message) basePayload.content = message;
        } else if (currentMode === 'transfer') {
            const sourceGuildId = el.sourceGuildId.value.trim();
            const sourceChannelId = el.sourceChannelId.value.trim();
            sourceMessageIds = parseList(el.sourceMessageIds.value);
            
            if (!sourceGuildId || !sourceChannelId || !sourceMessageIds.length) {
                return logMessage('転送元サーバーID、チャンネルID、メッセージIDを入力してください。', 'error');
            }
            
            logMessage('指定されたメッセージを取得中...', 'info');
            transferMessages = await fetchMessagesByIds(tokens[0], sourceGuildId, sourceChannelId, sourceMessageIds);
            
            if (transferMessages.length === 0) {
                return logMessage('転送可能なメッセージが見つかりませんでした。', 'error');
            }
            
            if (el.randomOrder.checked) {
                transferMessages = shuffleArray([...transferMessages]);
                logMessage(`${transferMessages.length}件のメッセージを取得しました（ランダム順序）。`, 'success');
            } else {
                logMessage(`${transferMessages.length}件のメッセージを取得しました（元の順序）。`, 'success');
            }
        } else {
            const message = el.message.value.trim();
            if (!message && mentionCount === 0 && !el.pollToggle.checked) return logMessage('メッセージかメンションを設定してください。', 'error');
            basePayload.content = message;
        }

        const getFinalPayload = (messageIndex = 0, targetChannelId = null) => {
            let finalPayload = { ...basePayload };
            
            if (currentMode === 'transfer' && sourceMessageIds.length > 0) {
                const messageId = sourceMessageIds[messageIndex % sourceMessageIds.length];
                const sourceGuildId = el.sourceGuildId.value.trim();
                const sourceChannelId = el.sourceChannelId.value.trim();
                finalPayload.content = '';
                finalPayload.message_reference = {
                    guild_id: sourceGuildId,
                    channel_id: sourceChannelId,
                    message_id: messageId,
                    type: 1
                };
                finalPayload.flags = 0;
                
                if (el.includeAttachments.checked && transferMessages.length > 0) {
                    const msg = transferMessages[messageIndex % transferMessages.length];
                    if (msg.attachments?.length > 0) {
                        finalPayload.content = msg.attachments.map(a => a.url).join('\n');
                    }
                }
                
                return finalPayload;
            }
            
            let content = finalPayload.content || '';
            
            if (userIds.length > 0 && mentionCount > 0) {
                const mentions = shuffleArray([...userIds]).slice(0, mentionCount).map(id => `<@${id}>`).join(' ');
                
                if (content.includes('{mention}')) {
                    content = content.replace('{mention}', mentions);
                } else {
                    content = `${mentions} ${content}`.trim();
                }
            }
            
            if (el.randomToggle.checked) {
                const randomLength = parseInt(el.randomChars.value) || 5;
                const randomString = generateRandomString(randomLength, randomType);
                content = `${content} ${randomString}`.trim();
            }
            
            finalPayload.content = content;
            
            if (el.randomReplyToggle.checked && replyMessageIds.length > 0 && targetChannelId) {
                const randomReplyId = replyMessageIds[Math.floor(Math.random() * replyMessageIds.length)];
                finalPayload.message_reference = {
                    channel_id: targetChannelId,
                    message_id: randomReplyId
                };
                
                if (!el.replyMentionToggle.checked) {
                    finalPayload.allowed_mentions = { replied_user: false };
                }
            }
            
            return finalPayload;
        };

        isRunning = true;
        el.startBtn.disabled = true; 
        el.stopBtn.disabled = false; 
        el.startBtn.textContent = '実行中...';
        updateBackgroundStatus(true);
        
        if (el.channelIntervalToggle.checked) {
            const channelIds = parseList(el.channelIds.value);
            const channelIntervalMs = parseInt(el.channelInterval.value) || 2000;
            
            if (!channelIds.length) { 
                logMessage('チャンネルIDを入力してください。', 'error'); 
                return stopSending(); 
            }
            
            const totalMessages = channelIds.length * tokens.length;
            logMessage(`チャンネル別間隔送信を開始... (間隔: ${channelIntervalMs}ms, 合計: ${totalMessages}件, 順序: CH1→待機→CH2→待機...)`, 'info');
            
            let channelIndex = 0;
            let messageIndex = 0;
            
            const sendNextChannel = () => {
                if (!isRunning) return;
                
                const currentChannelId = channelIds[channelIndex % channelIds.length];
                
                tokens.forEach(token => {
                    sendApiRequest(token, currentChannelId, getFinalPayload(messageIndex, currentChannelId));
                });
                
                channelIndex++;
                messageIndex++;
            };
            
            sendNextChannel();
            const intervalId = setInterval(sendNextChannel, channelIntervalMs);
            intervalIds.push(intervalId);
        } else {
            const channelIds = parseList(el.channelIds.value);
            if (!channelIds.length) { logMessage('チャンネルIDを入力してください。', 'error'); return stopSending(); }
            const intervalMs = parseInt(el.interval.value) || 2000;
            const isPerAccount = el.perAccountIntervalToggle.checked && tokens.length > 1;
            
            if (isPerAccount) {
                logMessage(`アカウントごとの送信間隔モード: ${intervalMs}ms`, 'info');
            }
            
            const sendBatch = (messageIndex = 0) => {
                if (!isRunning) return;
                if (isPerAccount) {
                    const tokenIndex = messageIndex % tokens.length;
                    const token = tokens[tokenIndex];
                    channelIds.forEach(chId => sendApiRequest(token, chId, getFinalPayload(messageIndex, chId)));
                } else {
                    tokens.forEach(token => channelIds.forEach(chId => sendApiRequest(token, chId, getFinalPayload(messageIndex, chId))));
                }
            };
            
            if (el.repeatToggle.checked) {
                let execCount = 0;
                let messageIndex = 0;
                const repeatCount = parseInt(el.repeatCount.value) || 0;
                
                const totalMessagesPerBatch = isPerAccount ? channelIds.length : (tokens.length * channelIds.length);
                const totalMessages = repeatCount > 0 ? (totalMessagesPerBatch * repeatCount) : '無限';
                
                const execute = () => {
                    if (!isRunning) return;
                    if (repeatCount > 0 && execCount >= repeatCount) { 
                        logMessage(`${repeatCount}回の送信が完了しました。`, 'success'); 
                        return stopSending(); 
                    }
                    execCount++; 
                    sendBatch(messageIndex);
                    messageIndex++;
                };
                
                logMessage(`繰り返し送信を開始... (間隔: ${intervalMs}ms, 回数: ${repeatCount > 0 ? `${repeatCount}回` : '無限'}, 合計: ${totalMessages}件${isPerAccount ? ', アカウントローテーション' : ''}${el.randomReplyToggle.checked && replyMessageIds.length > 0 ? ', ランダム返信' : ''})`, 'info');
                execute(); 
                const intervalId = setInterval(execute, intervalMs);
                intervalIds.push(intervalId);
            } else { 
                const totalMessages = isPerAccount ? channelIds.length : (tokens.length * channelIds.length);
                logMessage(`1回送信を実行します... (合計: ${totalMessages}件${isPerAccount ? ', アカウントローテーション' : ''}${el.randomReplyToggle.checked && replyMessageIds.length > 0 ? ', ランダム返信' : ''})`, 'info'); 
                sendBatch(0); 
                setTimeout(() => {
                    if (isRunning) stopSending();
                }, 1500); 
            }
        }
    });

    Object.values(el).forEach(element => {
        if(element && element.id && element.id !== 'backgroundStatus' && element.id !== 'modeSelection') {
            element.addEventListener('change', saveData);
            if(element.tagName === 'INPUT' || element.tagName === 'TEXTAREA') {
                element.addEventListener('keyup', saveData);
            }
        }
    });

    el.clearDataBtn.addEventListener('click', () => {
        if (confirm('保存されているすべての入力データをクリアします。よろしいですか？')) {
            localStorage.removeItem(STORAGE_KEY);
            logMessage('保存データをクリアしました。ページをリロードします。', 'success');
            setTimeout(() => location.reload(), 1000);
        }
    });

    window.addEventListener('beforeunload', (e) => {
        if (isRunning) {
            e.preventDefault();
            e.returnValue = 'バックグラウンド処理が実行中です。ページを閉じてもよろしいですか？';
            return e.returnValue;
        }
    });

    document.addEventListener('DOMContentLoaded', () => {
        loadData();
        if (el.tokens) el.tokens.dispatchEvent(new Event('input'));
        if (el.instantDeleteToggle) el.instantDeleteToggle.dispatchEvent(new Event('change'));
    });
</script>

</body>
</html>
