original source: [kaggle - Brazilian E-Commerce Analysis](https://www.kaggle.com/code/mairedaai/brazilian-e-commerce-analysis)

***

## Brazilian E-Commerce Data Analysis  
브라질 전자상거래 데이터 분석 [kaggle](https://www.kaggle.com/code/scratchpad/notebook2d4645b505/edit)

이 프로젝트에서는 브라질 전자상거래 데이터셋을 분석하여 고객 행동, 결제 패턴, 배송 성과, 상품 트렌드를 이해합니다.
이 분석의 목표는 데이터셋을 탐색하고, 전자상거래 비즈니스가 운영 효율과 고객 만족도를 향상시키는 데 도움이 될 만한 의미 있는 인사이트를 도출하는 것입니다.

이 분석에는 Python, Pandas, 데이터 시각화 라이브러리 등이 사용되었습니다. 

***

## Dataset Overview  
데이터셋 개요 [kaggle - Brazilian E-Commerce Analysis](https://www.kaggle.com/code/mairedaai/brazilian-e-commerce-analysis)

이 데이터셋은 2016년부터 2018년 사이 브라질에서 발생한 전자상거래 주문 정보를 포함합니다. 

다음과 같은 여러 테이블로 구성되어 있습니다.
- Customers 데이터셋  
- Orders 데이터셋  
- Order items  
- Payments  
- Reviews  
- Products  
- Sellers  

이들 테이블은 고객 행동, 결제 수단, 배송 시간, 상품 성과에 대한 인사이트를 제공합니다. 

***

## Data Cleaning  
데이터 정제 

분석을 수행하기 전에 데이터 품질을 보장하기 위해 데이터셋을 점검하고 정제했습니다. 

정제 과정에는 다음 작업이 포함되었습니다. 
- 결측값 확인  
- 데이터 타입 검증  
- 중복 데이터 제거 여부 확인  
- 날짜 컬럼 포맷 정리  

데이터 정제는 정확한 분석과 신뢰할 수 있는 인사이트를 위해 필수적인 단계입니다.

***

<img width="628" height="467" alt="image" src="https://github.com/user-attachments/assets/21636e40-270a-4080-b5ff-f8e0bbb54467" />

<img width="607" height="618" alt="image" src="https://github.com/user-attachments/assets/792649de-c8d0-4597-9293-49f961f439b8" />

<img width="594" height="458" alt="image" src="https://github.com/user-attachments/assets/07aa7d4e-84a0-4781-ae8d-68ee61bb30a3" />


## Key Insights  

1. 데이터셋에 포함된 대부분의 주문은 성공적으로 배송되었으며, 이는 주문 이행 프로세스가 신뢰할 수 있음을 보여줍니다. 
2. 상파울루(São Paulo)는 고객 수와 주문 수가 가장 많으며, 플랫폼에 있어 가장 중요한 시장입니다.
3. 신용카드는 고객들이 가장 많이 사용하는 결제 수단입니다. 
4. 배송 지연은 고객 리뷰 점수에 부정적인 영향을 미치는 것으로 보입니다.
5. 일부 상품 카테고리는 다른 카테고리에 비해 훨씬 더 많은 주문을 발생시킵니다.

***

## Conclusion  

결론

브라질 전자상거래 데이터셋 분석을 통해 고객 행동, 결제 선호도, 배송 성과에서 중요한 패턴을 확인할 수 있었습니다. 

이러한 패턴을 이해하면 전자상거래 비즈니스는 물류를 개선하고, 고객 만족도를 높이며, 가장 수익성이 높은 상품 카테고리에 집중할 수 있습니다. 
