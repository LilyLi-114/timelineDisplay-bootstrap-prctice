# Timeline Display
simple timeline display model

## Bootsrap
使用bootstrap來進行排版

### 技巧
-row-reverse 做出圖片在左或在右的效果
-使用偽元素做出中間的時間軸
-在css中加入做出響應式的效果,當面小於576px時,中線消失
  @media (max-width: 576px) { 
    .timeline-section:after,
    .timeline-pointer:after {
      display: none;
    }