<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>按摩服務價目表與功效說明</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Microsoft JhengHei', Arial, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #f5f1e6 0%, #ffffff 100%);
            color: #5a4a42;
            line-height: 1.6;
            padding: 15px;
            min-height: 100vh;
            font-size: 18px; /* 增大基礎字體大小 */
        }
        
        .container {
            max-width: 100%;
            margin: 0 auto;
            background: white;
            border-radius: 15px;
            box-shadow: 0 5px 25px rgba(0,0,0,0.08);
            overflow: hidden;
            border: 1px solid #f0e6df;
        }
        
        header {
            background: linear-gradient(135deg, #8d6e63 0%, #a1887f 100%);
            color: white;
            padding: 25px 20px;
            text-align: center;
        }
        
        header h1 {
            font-size: 28px; /* 增大標題字體 */
            margin-bottom: 15px;
            line-height: 1.3;
        }
        
        header p {
            font-size: 18px; /* 增大副標題字體 */
            opacity: 0.9;
            max-width: 100%;
            margin: 0 auto;
            line-height: 1.5;
        }
        
        .price-section {
            padding: 20px 15px;
            border-bottom: 1px dashed #e0d6cf;
        }
        
        .price-section:last-child {
            border-bottom: none;
        }
        
        h2 {
            color: #8d6e63;
            font-size: 22px; /* 增大分類標題字體 */
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid #f0e6df;
            display: flex;
            align-items: center;
            font-weight: 600;
        }
        
        h2 i {
            margin-right: 10px;
            font-size: 20px;
            color: #a1887f;
        }
        
        .service-category {
            margin-bottom: 25px;
        }
        
        .service-item {
            padding: 18px 0;
            border-bottom: 1px dotted #e0d6cf;
            transition: all 0.3s ease;
        }
        
        .service-item:hover {
            background-color: #faf6f2;
            padding-left: 10px;
            padding-right: 10px;
            border-radius: 8px;
        }
        
        .service-item:last-child {
            border-bottom: none;
        }
        
        .service-header {
            display: flex;
            justify-content: space-between;
            margin-bottom: 10px;
            flex-wrap: wrap;
        }
        
        .service-name {
            font-weight: 600;
            font-size: 20px; /* 增大服務名稱字體 */
            flex: 2;
            margin-bottom: 5px;
        }
        
        .service-duration {
            color: #8d6e63;
            font-size: 18px; /* 增大時長字體 */
            flex: 1;
            text-align: right;
        }
        
        .service-price {
            flex-basis: 100%;
            text-align: left;
            font-weight: 700;
            color: #5d4037;
            font-size: 20px; /* 增大價格字體 */
            margin-top: 5px;
        }
        
        .service-benefit {
            margin-top: 10px;
            font-size: 17px; /* 增大功效說明字體 */
            color: #7a665d;
            line-height: 1.5;
            padding-left: 10px;
            border-left: 3px solid #d7ccc8;
        }
        
        .highlight {
            background-color: #faf6f2;
            padding: 15px;
            border-radius: 8px;
            margin: 15px 0;
            border-left: 4px solid #d7ccc8;
        }
        
        .note {
            font-size: 16px;
            color: #8d6e63;
            margin-top: 5px;
            font-style: italic;
        }
        
        .recommendation {
            background: linear-gradient(135deg, #e8f5e9 0%, #f1f8e9 100%);
            padding: 20px;
            border-radius: 10px;
            margin-top: 25px;
            border-left: 5px solid #81c784;
        }
        
        .recommendation h3 {
            color: #2e7d32;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            font-size: 22px; /* 增大建議標題字體 */
        }
        
        .recommendation h3 i {
            margin-right: 10px;
        }
        
        .recommendation ul {
            padding-left: 20px;
        }
        
        .recommendation li {
            margin-bottom: 12px;
            font-size: 18px; /* 增大建議內容字體 */
            line-height: 1.5;
        }
        
        footer {
            text-align: center;
            padding: 20px;
            color: #8d6e63;
            font-size: 16px;
            border-top: 1px solid #f0e6df;
            margin-top: 20px;
            line-height: 1.5;
        }
        
        /* 針對小屏幕設備的額外優化 */
        @media (max-width: 480px) {
            body {
                padding: 10px;
                font-size: 19px; /* 在極小屏幕上進一步增大字體 */
            }
            
            header {
                padding: 20px 15px;
            }
            
            header h1 {
                font-size: 26px;
            }
            
            header p {
                font-size: 17px;
            }
            
            h2 {
                font-size: 21px;
            }
            
            .service-name {
                font-size: 19px;
            }
            
            .service-duration {
                font-size: 17px;
            }
            
            .service-price {
                font-size: 19px;
            }
            
            .service-benefit {
                font-size: 16px;
            }
            
            .recommendation li {
                font-size: 17px;
            }
        }
        
        /* 確保觸控元素有足夠的大小 */
        .service-item {
            min-height: 60px; /* 確保觸控區域足夠大 */
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1><i class="fas fa-spa"></i> 舒壓服務項目</h1>
            <p>精心設計的按摩方案，針對不同需求提供專業護理，讓身心靈得到全面放鬆</p>
        </header>
        
        <div class="price-section">
            <div class="service-category">
                <h2><i class="fas fa-spa"></i> 足部放鬆</h2>
                
                <div class="service-item">
                    <div class="service-header">
                        <div class="service-name">漢方足部按摩（基礎）</div>
                        <div class="service-duration">60分鐘</div>
                    </div>
                    <div class="service-price">NT.700</div>
                    <div class="service-benefit">功效：針對足底穴位進行按摩，促進循環，緩解腿部疲勞，改善腳部冰冷問題，適合久站或長時間行走後放鬆。</div>
                </div>
                
                <div class="service-item">
                    <div class="service-header">
                        <div class="service-name">漢方足部按摩</div>
                        <div class="service-duration">90分鐘</div>
                    </div>
                    <div class="service-price">NT.1150</div>
                    <div class="service-benefit">功效：全面性足部護理，包含小腿按摩，深度放鬆筋膜，改善水腫問題，提升睡眠品質。</div>
                </div>
                
                <div class="service-item">
                    <div class="service-header">
                        <div class="service-name">漢方足部按摩</div>
                        <div class="service-duration">120分鐘</div>
                    </div>
                    <div class="service-price">NT.1400</div>
                    <div class="service-benefit">功效：完整足部與下肢護理，結合反射區，不僅放鬆雙腳,刺激五臟，達到全身性的保健效果。</div>
                </div>
            </div>
            
            <div class="service-category">
                <h2><i class="fas fa-concierge-bell"></i> 經絡套餐</h2>
                
                <div class="service-item">
                    <div class="service-header">
                        <div class="service-name">足部+身體按摩</div>
                        <div class="service-duration">100分鐘</div>
                    </div>
                    <div class="service-price">NT.1450</div>
                    <div class="service-benefit">功效：結合足部反射區與身體經絡按摩，疏通全身，緩解肌肉僵硬，提升能量流動，適合需要全面放鬆的客人。</div>
                </div>
            </div>
            
            <div class="service-category">
                <h2><i class="fas fa-hands"></i> 身體按摩</h2>
                
                <div class="service-item">
                    <div class="service-header">
                        <div class="service-name">身體鬆筋按摩</div>
                        <div class="service-duration">60分鐘</div>
                    </div>
                    <div class="service-price">NT.1000</div>
                    <div class="service-benefit">功效：指壓能深度刺激穴位，疏通經絡，緩解日常壓力造成的肌肉緊繃。</div>
                </div>
                
                <div class="service-item">
                    <div class="service-header">
                        <div class="service-name">身體鬆筋按摩（指壓/油壓）</div>
                        <div class="service-duration">90分鐘</div>
                    </div>
                    <div class="service-price">NT.1450</div>
                    <div class="service-benefit">功效：指壓能深度刺激穴位，疏通經絡；油壓則能滋潤肌膚，放鬆肌肉纖維。可根據個人需求選擇，有效緩解深層肌肉疲勞。</div>
                </div>
                
                <div class="service-item">
                    <div class="service-header">
                        <div class="service-name">身體鬆筋按摩（指壓/油壓）</div>
                        <div class="service-duration">120分鐘</div>
                    </div>
                    <div class="service-price">NT.1900</div>
                    <div class="service-benefit">功效：全身性深度護理，從頭到腳徹底放鬆，促進淋巴排毒，恢復身體活力，適合長期壓力大或運動後的深度恢復。</div>
                </div>
            </div>
        </div>
        
        <div class="price-section">
            <div class="service-category">
                <h2><i class="fas fa-star"></i> 特色護理項目</h2>
                
                <div class="service-item">
                    <div class="service-header">
                        <div class="service-name">肩頸刮痧舒壓</div>
                        <div class="service-duration">30分鐘</div>
                    </div>
                    <div class="service-price">NT.500</div>
                    <div class="service-benefit">功效：通過刮痧板刺激肩背經絡，排出體內濕氣，緩解頭痛、肩頸僵硬，改善循環。</div>
                </div>
                
                <div class="service-item">
                    <div class="service-header">
                        <div class="service-name">肩頸按摩放鬆</div>
                        <div class="service-duration">30分鐘</div>
                    </div>
                    <div class="service-price">NT.500</div>
                    <div class="service-benefit">功效：針對現代人使用電子產品的肩頸問題，使用專業手法鬆解肩、上背、手部，讓筋膜放鬆。</div>
                </div>
                
                <div class="service-item">
                    <div class="service-header">
                        <div class="service-name">耳燭香薰減壓護理</div>
                        <div class="service-duration">40分鐘</div>
                    </div>
                    <div class="service-price">NT.800</div>
                    <div class="service-benefit">功效：結合耳燭的溫和熱力與香薰療法，舒緩耳部壓力，改善耳鳴，同時通過香氣放鬆神經系統，顱氏負重。</div>
                </div>
                
                <div class="service-item">
                    <div class="service-header">
                        <div class="service-name">香薰臍燭舒壓護理</div>
                        <div class="service-duration">30分鐘</div>
                    </div>
                    <div class="service-price">NT.950</div>
                    <div class="service-benefit">功效：針對腹部區域的特殊護理，減輕消化系統不適並排除毒（如腹脹、胃氣、經痛）以及改善水腫等功效的保健護理。</div>
                </div>
                
                <div class="service-item">
                    <div class="service-header">
                        <div class="service-name">櫸木鬆筋護理</div>
                        <div class="service-duration">90分鐘</div>
                    </div>
                    <div class="service-price">NT.1700</div>
                    <div class="service-benefit">功效：使用櫸木工具進行筋膜放鬆，以疏通經絡、活絡氣血，能舒緩肌肉緊繃、促進血液與淋巴循環，排除體內廢物與水分，達到消除疲勞、提升免疫力等效果。</div>
                </div>
            </div>
        </div>
        
        <div class="price-section">
            <div class="service-category">
                <h2><i class="fas fa-plus-circle"></i> 加購選項</h2>
                
                <div class="highlight">
                    <div class="service-item">
                        <div class="service-header">
                            <div class="service-name">足部續時</div>
                            <div class="service-duration">每30分鐘</div>
                        </div>
                        <div class="service-price">NT.450</div>
                    </div>
                    <div class="service-item">
                        <div class="service-header">
                            <div class="service-name">身體續時</div>
                            <div class="service-duration">每30分鐘</div>
                        </div>
                        <div class="service-price">NT.550</div>
                    </div>
                    <div class="service-item">
                        <div class="service-header">
                            <div class="service-name">櫸木續時</div>
                            <div class="service-duration">每30分鐘</div>
                        </div>
                        <div class="service-price">NT.650</div>
                    </div>
                    <div class="service-item">
                        <div class="service-header">
                            <div class="service-name">升級多特瑞精油（足部）</div>
                            <div class="service-duration">單次加購</div>
                        </div>
                        <div class="service-price">NT.200</div>
                        <div class="service-benefit">功效：使用高品質精油增強按摩效果，加強舒緩肌肉痠痛。</div>
                    </div>
                </div>
            </div>
        </div>

        <div class="recommendation">
            <h3><i class="fas fa-lightbulb"></i> 專業建議</h3>
            <ul>
                <li><strong>日常疲勞</strong>：推薦60-90分鐘的身體按摩或足部放鬆</li>
                <li><strong>深度放鬆</strong>：建議選擇120分鐘的完整服務</li>
                <li><strong>特定問題</strong>：可考慮特色護理項目針對性解決</li>
                <li><strong>全面保健</strong>：經絡套餐提供最全面的護理效果</li>
                <li><strong>運動恢復</strong>：櫸木鬆筋護理特別適合運動後的肌肉恢復</li>
            </ul>
        </div>

<div style="text-align: center; margin: 30px 0;">
    <a href="https://lin.ee/I7QaQ2J" target="_blank">
        <img src="https://scdn.line-apps.com/n/line_add_friends/btn/zh-Hant.png" 
             alt="加入好友" height="50" border="1">
    </a>
        </div>
