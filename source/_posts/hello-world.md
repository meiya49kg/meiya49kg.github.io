---
title: 1/25-1/31 蝦皮全站折扣碼
---

點擊按鈕自動複製代碼，跳轉網頁直接輸入領券

## **全站$100-20**

<style>
.coupon-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
  gap: 15px;
  padding: 20px;
  max-width: 1200px;
  margin: 0 auto;
}

.copy-button {
  background-color: white;
  color: #333;  /* 黑色文字 */
  border: 1px solid #ddd;
  border-radius: 8px;
  padding: 12px 20px;
  cursor: pointer;
  transition: all 0.2s ease;
  font-family: monospace;
  font-size: 1.1em;
  width: 100%;
  box-shadow: 0 2px 4px rgba(0,0,0,0.05);
}

.copy-button:hover {
  border-color: #999;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}

/* 複製成功時的樣式 */
.copy-button.copied {
  background-color: #f8f8f8;
  color: #666;
}
</style>

<div class="coupon-grid">
  <!-- 優惠碼按鈕 1 -->
  <button class="copy-button" onclick="copyCoupon(this, 'SACNY25BV', 'https://s.shopee.tw/gAc6N0qGX')">
    1/25
  </button>

  <div class="coupon-grid">
  <!-- 優惠碼按鈕 1 -->
  <button class="copy-button" onclick="copyCoupon(this, 'SACNY25BV', 'https://s.shopee.tw/gAc6N0qGX')">
    1/25
  </button>

  <!-- 優惠碼按鈕 2 -->
  <button class="copy-button" onclick="copyCoupon(this, 'SACNYBV26', 'https://s.shopee.tw/gAc6N0qGX')">
    1/26
  </button>

  <!-- 優惠碼按鈕 3 -->
  <button class="copy-button" onclick="copyCoupon(this, 'SA27CNYBV', 'https://s.shopee.tw/gAc6N0qGX')">
    1/27
  </button>

  <!-- 優惠碼按鈕 4 -->
  <button class="copy-button" onclick="copyCoupon(this, 'SACNY28BV', 'https://s.shopee.tw/gAc6N0qGX')">
    1/28
  </button>

  <!-- 優惠碼按鈕 5 -->
  <button class="copy-button" onclick="copyCoupon(this, 'SACNYBV29', 'https://s.shopee.tw/gAc6N0qGX')">
    1/29
  </button>

  <!-- 優惠碼按鈕 6 -->
  <button class="copy-button" onclick="copyCoupon(this, 'SA30CNY25BV', 'https://s.shopee.tw/gAc6N0qGX')">
    1/30
  </button>

  <!-- 優惠碼按鈕 7 -->
  <button class="copy-button" onclick="copyCoupon(this, 'SACNY31BV', 'https://s.shopee.tw/gAc6N0qGX')">
    1/31
  </button>
</div>

## **全站$499-50**
  
<div class="coupon-grid">
  <!-- 優惠碼按鈕 1 -->
  <button class="copy-button" onclick="copyCoupon(this, '25FNBOSHA', 'https://s.shopee.tw/gAc6N0qGX')">
    1/25
  </button>

  <!-- 優惠碼按鈕 2 -->
  <button class="copy-button" onclick="copyCoupon(this, '26FNBOSHA', 'https://s.shopee.tw/gAc6N0qGX')">
    1/26
  </button>

  <!-- 優惠碼按鈕 3 -->
  <button class="copy-button" onclick="copyCoupon(this, 'FNBOSHA27', 'https://s.shopee.tw/gAc6N0qGX')">
    1/27
  </button>

  <!-- 優惠碼按鈕 4 -->
  <button class="copy-button" onclick="copyCoupon(this, 'FNBOSHA28', 'https://s.shopee.tw/gAc6N0qGX')">
    1/28
  </button>

  <!-- 優惠碼按鈕 5 -->
  <button class="copy-button" onclick="copyCoupon(this, 'FNBO29SHA', 'https://s.shopee.tw/gAc6N0qGX')">
    1/29
  </button>

  <!-- 優惠碼按鈕 6 -->
  <button class="copy-button" onclick="copyCoupon(this, 'FNBO30SHA', 'https://s.shopee.tw/gAc6N0qGX')">
    1/30
  </button>

  <!-- 優惠碼按鈕 7 -->
  <button class="copy-button" onclick="copyCoupon(this, 'FNBO31SHA', 'https://s.shopee.tw/gAc6N0qGX')">
    1/31
  </button>
</div>


<script>
function copyCoupon(button, code, redirectUrl) {
  // 複製優惠碼
  navigator.clipboard.writeText(code).then(() => {
    // 暫時改變按鈕文字
    const originalText = button.textContent;
    button.textContent = '已複製!';
    button.classList.add('copied');
    
    // 1秒後恢復原始文字
    setTimeout(() => {
      button.textContent = originalText;
      button.classList.remove('copied');
    }, 1000);
    
    // 跳轉至指定網址
    window.open(redirectUrl, '_blank');
  }).catch(err => {
    console.error('複製失敗:', err);
    alert('複製失敗，請手動複製優惠碼');
  });
}
</script>
