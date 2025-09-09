<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>论文README模板</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
            line-height: 1.6;
            color: #24292e;
        }
        
        .paper-title {
            text-align: center;
            font-weight: bold;
            font-size: 32px;
            margin-bottom: 20px;
        }
        
        .divider {
            height: 1px;
            background-color: #ddd;
            margin: 20px 0;
            border: none;
        }
        
        .authors {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            margin-bottom: 30px;
        }
        
        .author {
            font-weight: bold;
            font-size: 18px;
            margin: 5px 15px;
        }
        
        .core-figure {
            text-align: center;
            margin: 30px 0;
        }
        
        .core-figure img {
            max-width: 100%;
            border: 1px solid #ddd;
            border-radius: 4px;
            padding: 4px;
        }
        
        .figure-caption {
            font-style: italic;
            margin-top: 10px;
            font-size: 16px;
        }
        
        .supplementary {
            font-size: 18px;
            text-align: center;
            margin-top: 30px;
            font-weight: normal;
        }
        
        @media (max-width: 768px) {
            .paper-title {
                font-size: 24px;
            }
            
            .author {
                font-size: 16px;
            }
            
            .supplementary {
                font-size: 16px;
            }
        }
    </style>
</head>
<body>
    <div class="paper-title">基于深度学习的图像识别技术在医学影像分析中的应用研究</div>
    
    <hr class="divider">
    
    <div class="authors">
        <span class="author">张明</span>
        <span class="author">李华</span>
        <span class="author">王强</span>
        <span class="author">赵雪</span>
    </div>
    
    <div class="core-figure">
        <img src="https://via.placeholder.com/800x400?text=论文核心图" alt="论文核心示意图">
        <div class="figure-caption">图1：提出的模型架构及其性能对比</div>
    </div>
    
    <div class="supplementary">
        本研究得到国家自然科学基金(No.12345678)的支持，相关代码已开源。
    </div>
</body>
</html>
