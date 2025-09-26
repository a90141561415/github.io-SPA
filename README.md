# a90141561415.github.io-
<!DOCTYPE html>
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
            padding: 20px;
            min-height: 100vh;
        }
        
        .container {
            max-width: 1100px;
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
            padding: 30px;
            text-align: center;
        }
        
        header h1 {
            font-size: 2.2rem;
            margin-bottom: 10px;
        }
        
        header p {
            font-size: 1.1rem;
            opacity: 0.9;
            max-width: 700px;
            margin: 0 auto;
        }
        
        .price-section {
            padding: 25px;
            border-bottom: 1px dashed #e0d6cf;
        }
        
        .price-section:last-child {
            border-bottom: none;
        }
        
        h2 {
            color: #8d6e63;
            font-size: 1.5rem;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid #f0e6df;
            display: flex;
            align-items: center;
            font-weight: 600;
        }
        
        h2 i {
            margin-right: 10px;
            font-size: 1.3rem;
            color: #a1887f;
        }
        
        .service-category {
            margin-bottom: 30px;
        }
        
        .service-item {
            display: flex;
            justify-content: space-between;
            padding: 15px 0;
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
        
        .service-name {
            flex: 2;
            font-weight: 500;
            font-size: 1.1rem;
        }
        
        .service-duration {
            flex: 1;
            color: #8d6e63;
            font-size: 0.95rem;
        }
        
        .service-price {
            flex: 1;
            text-align: right;
            font-weight: 600;
            color: #5d4037;
            font-size: 1.1rem;
        }
        
        .service-benefit {
            flex-basis: 100%;
            margin-top: 8px;
            font-size: 0.95rem;
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
            font-size: 0.9rem;
            color: #8d6e63;
            margin-top: 5px;
            font-style: italic;
        }
        
        .recommendation {
            background: linear-gradient(135deg, #e8f5e9 0%, #f1f8e9 100%);
            padding: 20px;
            border-radius: 10px;
            margin-top: 30px;
            border-left: 5px solid #81c784;
        }
        
        .recommendation h3 {
            color: #2e7d32;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
        }
        
        .recommendation h3 i {
            margin-right: 10px;
        }
        
        .recommendation ul {
            padding-left: 20px;
        }
        
        .recommendation li {
            margin-bottom: 10px;
        }
        
        footer {
            text-align: center;
            padding: 20px;
            color: #8d6e63;
            font-size: 0.9rem;
            border-top: 1px solid #f0e6df;
            margin-top: 20px;
        }
        
        @media (max-width: 768px) {
            .service-item {
                flex-direction: column;
            }
            
            .service-duration, .service-price {
                margin-top: 5px;
                margin-left: 20px;
            }
            
            header h1 {
                font-size: 1.8rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1><i class="fas fa-spa"></i> 專業按摩服務價目表</h1>
            <p>精心設計的按摩方案，針對不同需求提供專業護理，讓身心靈得到全面放鬆</p>
        </header>
        
        <div class="price-section">
            <div class="service-category">
                <h2><i class="fas fa-spa"></i> 足部放鬆</h2>
                
                <div class="service-item">
                    <div class="service-name">基礎足部放鬆</div>
                    <div class="service-duration">60分鐘</div>
                    <div class="service-price">NT.700</div>
                    <div class="service-benefit">功效：針對足底穴位進行按摩，促進血液循環，緩解腿部疲勞，改善腳部冰冷問題，適合久站或長時間行走後放鬆。</div>
                </div>
                
                <div class="service-item">
                    <div class="service-name">足部放鬆</div>
                    <div class="service-duration">90分鐘</div>
                    <div class="service-price">NT.1150</div>
                    <div class="service-benefit">功效：全面性足部護理，包含小腿按摩，深度放鬆筋膜，改善水腫問題，提升睡眠品質。</div>
                </div>
                
                <div class="service-item">
                    <div class="service-name">足部放鬆</div>
                    <div class="service-duration">120分鐘</div>
                    <div class="service-price">NT.1400</div>
                    <div class="service-benefit">功效：完整足部與下肢護理，結合反射區療法，不僅放鬆雙腳，更能調理對應的器官功能，達到全身性的保健效果。</div>
                </div>
            </div>
            
            <div class="service-category">
                <h2><i class="fas fa-concierge-bell"></i> 經絡套餐</h2>
                
                <div class="service-item">
                    <div class="service-name">足部+身體按摩</div>
                    <div class="service-duration">100分鐘</div>
                    <div class="service-price">NT.1450</div>
                    <div class="service-benefit">功效：結合足部反射區與身體經絡按摩，疏通全身氣血，緩解肌肉僵硬，提升能量流動，適合需要全面放鬆的客人。</div>
                </div>
            </div>
            
            <div class="service-category">
                <h2><i class="fas fa-hands"></i> 身體按摩</h2>
                
                <div class="service-item">
                    <div class="service-name">身體按摩</div>
                    <div class="service-duration">60分鐘</div>
                    <div class="service-price">NT.1000</div>
                    <div class="service-benefit">功效：針對肩頸、背部重點區域進行放鬆，緩解日常壓力造成的肌肉緊繃，改善姿勢不良問題。</div>
                </div>
                
                <div class="service-item">
                    <div class="service-name">身體按摩（指壓/油壓）</div>
                    <div class="service-duration">90分鐘</div>
                    <div class="service-price">NT.1450</div>
                    <div class="service-benefit">功效：指壓能深度刺激穴位，疏通經絡；油壓則能滋潤肌膚，放鬆肌肉纖維。可根據個人需求選擇，有效緩解深層肌肉疲勞。</div>
                </div>
                
                <div class="service-item">
                    <div class="service-name">身體按摩（指壓/油壓）</div>
                    <div class="service-duration">120分鐘</div>
                    <div class="service-price">NT.1900</div>
                    <div class="service-benefit">功效：全身性深度護理，從頭到腳徹底放鬆，促進淋巴排毒，恢復身體活力，適合長期壓力大或運動後的深度恢復。</div>
                </div>
            </div>
        </div>
        
        <div class="price-section">
            <div class="service-category">
                <h2><i class="fas fa-star"></i> 特色護理項目</h2>
                
                <div class="service-item">
                    <div class="service-name">肩頸刮痧舒壓</div>
                    <div class="service-duration">30分鐘</div>
                    <div class="service-price">NT.500</div>
                    <div class="service-benefit">功效：通過刮痧板刺激肩頸經絡，排出體內濕氣，緩解頭痛、肩頸僵硬，改善氣血循環。</div>
                </div>
                
                <div class="service-item">
                    <div class="service-name">肩頸按摩放鬆</div>
                    <div class="service-duration">30分鐘</div>
                    <div class="service-price">NT.500</div>
                    <div class="service-benefit">功效：針對現代人常見的肩頸問題，使用專業手法鬆解筋膜，預防頸椎病，提升頭部血液供應。</div>
                </div>
                
                <div class="service-item">
                    <div class="service-name">耳燭香薰減壓護理</div>
                    <div class="service-duration">40分鐘</div>
                    <div class="service-price">NT.800</div>
                    <div class="service-benefit">功效：結合耳燭的溫和熱力與香薰療法，舒緩耳部壓力，改善耳鳴，同時通過香氣放鬆神經系統。</div>
                </div>
                
                <div class="service-item">
                    <div class="service-name">香薰臍燭舒壓護理</div>
                    <div class="service-duration">30分鐘</div>
                    <div class="service-price">NT.950</div>
                    <div class="service-benefit">功效：針對腹部區域的特殊護理，溫暖子宮，改善消化系統功能，緩解經期不適，平衡內分泌。</div>
                </div>
                
                <div class="service-item">
                    <div class="service-name">櫸木鬆筋護理</div>
                    <div class="service-duration">90分鐘</div>
